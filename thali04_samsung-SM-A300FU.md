#### Test 81095569cb9dee4_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
,08-23 18:34:46.145  1014  1251 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
--------- beginning of main
08-23 18:34:46.145  1167  1167 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 18:34:46.145  1014  1251 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 18:34:46.145  1167  1167 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 18:34:46.145  1014  1251 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 18:34:46.145  1014  1251 D BatteryService: stay LED for fully charged
08-23 18:34:46.145  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 18:34:46.145  1014  1014 I MotionRecognitionService: Plugged
08-23 18:34:46.145  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
08-23 18:34:46.155  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 18:34:46.155  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-23 18:34:46.165  3163  3163 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 18:34:46.165  3163  3269 D HeadsetStateMachine: Disconnected process message: 10
08-23 18:34:46.175  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 18:34:46.175  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 18:34:46.175  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 18:34:46.405  6783  6783 D AndroidRuntime: 
08-23 18:34:46.405  6783  6783 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 18:34:46.415  6783  6783 D AndroidRuntime: CheckJNI is OFF
08-23 18:34:46.415  6783  6783 D AndroidRuntime: readGMSProperty: start
08-23 18:34:46.415  6783  6783 D AndroidRuntime: readGMSProperty: already setted!!
08-23 18:34:46.415  6783  6783 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 18:34:46.415  6783  6783 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 18:34:46.415  6783  6783 D AndroidRuntime: readGMSProperty: end
08-23 18:34:46.415  6783  6783 D AndroidRuntime: addProductProperty: start
08-23 18:34:46.535  6783  6783 E AffinityControl: AffinityControl: registerfunction enter
08-23 18:34:46.565  6783  6783 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 18:34:46.585  1014  1474 E PersonaManagerService: inState():  stateMachine is null !!
08-23 18:34:46.585  1014  1474 I PersonaManagerService: PersonaId don't exist
08-23 18:34:46.585  1014  1474 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-23 18:34:46.585  1014  1474 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 18:34:46.605  1014  1474 W ActivityManager: mDVFSHelper.acquire()
08-23 18:34:46.615   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-23 18:34:46.615   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-23 18:34:46.625  1014  1474 D FocusedStackFrame: Set to : 0
08-23 18:34:46.625  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:34:46.625  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:34:46.625  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:34:46.625  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:34:46.625  1014  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 18:34:46.625  1014  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-23 18:34:46.635  6794  6794 E Zygote  : MountEmulatedStorage()
08-23 18:34:46.635  6794  6794 E Zygote  : v2
08-23 18:34:46.635  6794  6794 I libpersona: KNOX_SDCARD checking this for 10171
08-23 18:34:46.635  6794  6794 I libpersona: KNOX_SDCARD not a persona
08-23 18:34:46.635  1014  1474 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 18:34:46.635  1014  1474 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6794 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 18:34:46.635  1014  1474 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 18:34:46.645  6794  6794 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 18:34:46.645  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 18:34:46.645  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 18:34:46.645   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-23 18:34:46.645  6794  6794 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 18:34:46.645  6794  6794 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 18:34:46.665  1014  1474 D InputDispatcher: Focused application set to: xxxx
08-23 18:34:46.665  1014  1474 D InputDispatcher: Focus left window: 1480
08-23 18:34:46.665  6783  6783 D AndroidRuntime: Shutting down VM
08-23 18:34:46.665  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 18:34:46.665  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 18:34:46.675  6794  6794 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 18:34:46.675  6794  6794 D ActivityThread: Added TimaKeyStore provider
08-23 18:34:46.675  1014  1027 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-23 18:34:46.685  1014  1014 V ActivityManager: Display changed displayId=0
08-23 18:34:46.685  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 18:34:46.705  1014  1027 D PersonaManager: isKioskContainerExistOnDevice
08-23 18:34:46.715   257   445 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-23 18:34:46.715   257  1036 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-23 18:34:46.715  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-23 18:34:46.725  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{22696388 token=android.os.BinderProxy@34b5d5b2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 18:34:46.725  1480  1480 D Launcher: onTrimMemory. Level: 20
08-23 18:34:46.815  6794  6794 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-23 18:34:46.835  6794  6794 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6862-6864)
08-23 18:34:46.835  6794  6794 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 18:34:46.865  6794  6794 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d74d42f}
08-23 18:34:46.865  6794  6794 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 18:34:46.875  6783  6783 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 18:34:46.885  6794  6794 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 18:34:46.925  6794  6794 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-23 18:34:46.925  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 18:34:46.935  6794  6794 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 18:34:46.965  6794  6794 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 18:34:46.965  6794  6794 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 18:34:46.965  6794  6794 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 18:34:46.965  6794  6794 I Adreno-EGL: Local Branch: 
08-23 18:34:46.965  6794  6794 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 18:34:46.965  6794  6794 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 18:34:46.965  6794  6794 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 18:34:47.055  6794  6794 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 18:34:47.075  6794  6794 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-23 18:34:47.075  6794  6794 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-23 18:34:47.075   287   287 E SMD     : DCD OFF
,08-23 18:34:47.085  6794  6794 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-23 18:34:47.085  6794  6794 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-23 18:34:47.205  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 18:34:47.215  1014  1040 W ActivityManager: Activity pause timeout for ActivityRecord{38d08f7 u0 com.test.thalitest/.MainActivity t2}
,08-23 18:34:47.215  6794  6794 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 18:34:47.225  6794  6794 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-23 18:34:47.225  6794  6794 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-23 18:34:47.235  6794  6794 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 18:34:47.235  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 18:34:47.235  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 18:34:47.365  6794  6834 D OpenGLRenderer: Render dirty regions requested: true
,08-23 18:34:47.365  1014  1800 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 18:34:47.365  1014  1800 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-23 18:34:47.375  1014  1800 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-23 18:34:47.375  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 18:34:47.375  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 18:34:47.375  6794  6821 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-23 18:34:47.385  6794  6794 V ActivityThread: updateVisibility : ActivityRecord{210160f token=android.os.BinderProxy@1ace4370 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
,08-23 18:34:47.385  6794  6794 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 18:34:47.385  6794  6794 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-23 18:34:47.395   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-23 18:34:47.405  1014  1132 D InputDispatcher: Focus entered window: 6794
,08-23 18:34:47.415  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-23 18:34:47.415  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 18:34:47.415  6794  6794 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 18:34:47.415  6794  6834 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 18:34:47.415  6794  6834 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-23 18:34:47.415  6794  6834 D OpenGLRenderer: Enabling debug mode 0
,08-23 18:34:47.445  1014  4757 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 18:34:47.445  1167  1167 I StatusBar: Icon Only
,08-23 18:34:47.445  1167  1167 D PanelView: There is/are notification(s) 
,08-23 18:34:47.455  1014  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 18:34:47.465  1014  1045 I ActivityManager: Displayed Component not be shown by security: +749ms (total +835ms)
,08-23 18:34:47.465  1014  1045 W ActivityManager: mDVFSHelper.release()
,08-23 18:34:47.465  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{38d08f7 u0 com.test.thalitest/.MainActivity t2} time:107492
,08-23 18:34:47.465   257  1036 I SurfaceFlinger: id=12 Removed uhalitest (7/9),
,08-23 18:34:47.475   257  1036 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-23 18:34:47.475  6794  6794 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-23 18:34:47.475  6794  6794 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1ace4370 time:107506
,08-23 18:34:47.475  1872  1872 I SamsungIME: getCurrentCandidateView,
,08-23 18:34:47.505  6794  6794 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6794
,08-23 18:34:47.575  1872  1872 D SamsungIME: Dismiss ExpandCandiate
,08-23 18:34:47.695  6794  6794 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 18:34:47.735  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 18:34:47.785  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 18:34:47.795  6794  6838 D jxcore_app_log: JniHelper::setJavaVM(0xb8e952b0), pthread_self() = -1186825920
,08-23 18:34:47.795  1872  1872 I SamsungIME: KeybaordView init() : load resources
,08-23 18:34:47.805  6794  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 18:34:47.805  6794  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 18:34:47.805  6794  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 18:34:47.805  6794  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 18:34:47.805  6794  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 18:34:47.805  6794  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e33c75d added. We now have 1 listener(s)
,08-23 18:34:47.805  6794  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-23 18:34:47.805  6794  6838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-23 18:34:47.815  6794  6838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 18:34:47.815  6794  6838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 18:34:47.815  6794  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107168a0 added. We now have 1 listener(s)
,08-23 18:34:47.815  6794  6838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:34:47.825  6794  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 18:34:47.825  6794  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 18:34:47.825  6794  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-23 18:34:47.825  6794  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 18:34:47.825  6794  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 18:34:47.825  6794  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:34:47.825  6794  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27,
,08-23 18:34:47.835  6794  6838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 18:34:47.835  6794  6838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:34:47.835  6794  6838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:34:47.835  6794  6838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:34:47.835  6794  6838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:34:47.835  6794  6838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:34:47.835  6794  6838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:34:47.835  6794  6838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:34:47.835  6794  6838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:34:47.835  6794  6838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 18:34:47.835  6794  6838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:34:47.835  1872  1872 I SamsungIME: getCurrentKeyboard
08-23 18:34:47.835  1872  1872 I SamsungIME: getTextKeyboard
,08-23 18:34:47.835  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:34:47.835  6794  6838 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 18:34:47.845  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:34:47.865  1872  1872 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-23 18:34:47.865  6794  6794 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 18:34:48.345  1014  1314 E Watchdog: !@Sync 3
,08-23 18:34:48.385  6794  6848 W jxcore-log: Initializing JXcore engine
08-23 18:34:48.385  6794  6848 W jxcore-log: JXcore engine is ready
,08-23 18:34:48.445  1990  1990 E audit   : type=1400 msg=audit(1471970088.445:205): avc:  denied  { ioctl } for  pid=6848 comm="Thread-1245" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 18:34:48.445  1990  1990 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-23 18:34:48.445  1990  1990 E audit   : type=1300 msg=audit(1471970088.445:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f63b8f8 items=0 ppid=305 ppcomm=main pid=6848 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1245" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-23 18:34:48.445  1990  1990 E audit   : type=1320 msg=audit(1471970088.445:205): 
,08-23 18:34:48.455  6794  6848 W jxcore-log: Starting JXcore engine
,08-23 18:34:48.565  6794  6848 W jxcore-log: Platform android
08-23 18:34:48.565  6794  6848 W jxcore-log: 
08-23 18:34:48.565  6794  6848 W jxcore-log: Process ARCH arm
08-23 18:34:48.565  6794  6848 W jxcore-log: 
,08-23 18:34:48.765  6794  6848 I jxcore-log: JXcore Cordova bridge is ready!
08-23 18:34:48.765  6794  6848 I jxcore-log: 
,08-23 18:34:48.765  6794  6848 W jxcore-log: JXcore engine is started
,08-23 18:34:48.775  6794  6838 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 18:34:48.775  6794  6794 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 18:34:49.085   314   314 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-23 18:34:49.085   314   314 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 18:34:50.075   287   287 E SMD     : DCD OFF
,08-23 18:34:52.895  1014  1047 I PowerManagerService: [PWL] Off : 50s ago,
,08-23 18:34:53.085   287   287 E SMD     : DCD OFF,
,08-23 18:34:53.095  1014  3342 D SSRM:n  : SIOP:: AP = 330
,08-23 18:34:54.085   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 18:34:54.285  5617  5617 D FactoryTest: Not factory mode
,08-23 18:34:54.285  5617  5617 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-23 18:34:54.285  5617  5617 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-23 18:34:54.285  5617  5617 D MTPRx   : still no open session command from host, so toast
08-23 18:34:54.285  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-23 18:34:54.285  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 ,
,08-23 18:34:54.295  5617  5617 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114320,
08-23 18:34:54.295  1014  1800 E PersonaManagerService: inState():  stateMachine is null !!
08-23 18:34:54.295  1014  1800 I PersonaManagerService: PersonaId don't exist
,08-23 18:34:54.295  1014  1800 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-23 18:34:54.295  1014  1800 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-23 18:34:54.295  1014  1800 W ActivityManager: userId = 0, bbcId = -10000,
08-23 18:34:54.295  1014  1800 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:34:54.295  1014  1800 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings,
,08-23 18:34:54.305  1014  1800 W ActivityManager: mDVFSHelper.acquire()
,08-23 18:34:54.325  1014  1800 D PersonaManager: isKioskContainerExistOnDevice
,08-23 18:34:54.335  1014  1800 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 18:34:54.335  1014  1800 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 18:34:54.335  1014  1800 D InputDispatcher: Focused application set to: xxxx
,08-23 18:34:54.335  1014  1800 D InputDispatcher: Focus left window: 6794
,08-23 18:34:54.335  5617  5617 E MTPRx   : started activity for popup
,08-23 18:34:54.345  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 18:34:54.345  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 18:34:54.355  5617  5617 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-23 18:34:54.355  5617  5617 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-23 18:34:54.365  5617  5617 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-23 18:34:54.365  5617  5617 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 18:34:54.365  5617  5617 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 18:34:54.365  5617  5617 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 18:34:54.385  5617  5617 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-23 18:34:54.395  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 18:34:54.395  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 18:34:54.395  1014  1027 D InputDispatcher: Focused application set to: xxxx
,08-23 18:34:54.395  1014  1027 D InputDispatcher: Focus entered window: 6794
,08-23 18:34:54.395  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-23 18:34:54.405  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 18:34:54.405  1014  1026 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 18:34:54.405  1014  1026 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@9e9c906 attribute=null, token = android.os.BinderProxy@22af1e56
,08-23 18:34:54.445  5617  5617 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-23 18:34:54.455  5617  5617 D PhoneWindow: *FMB* installDecor mIsFloating : true
,08-23 18:34:54.455  5617  5617 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-23 18:34:54.475  6794  6794 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-23 18:34:54.475  6794  6794 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-23 18:34:54.475  6794  6794 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-23 18:34:54.475  6794  6794 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-23 18:34:54.485  1014  4757 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 18:34:54.485  1014  4757 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-23 18:34:54.485  1014  4757 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 18:34:54.485  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-23 18:34:54.485  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 18:34:54.495  6794  6794 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 18:34:54.495  6794  6794 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 18:34:54.495  6794  6794 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1ace4370 time:114525
,08-23 18:34:54.495  6794  6794 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@158b4a6c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@37250a7d, 16908290=android.view.AbsSavedState$1@37250a7d}, android:focusedViewId=100}]}]
08-23 18:34:54.495  6794  6794 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-23 18:34:54.495  6794  6794 V ActivityThread: updateVisibility : ActivityRecord{210160f token=android.os.BinderProxy@1ace4370 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-23 18:34:54.495  6794  6794 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 18:34:54.495  6794  6794 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-23 18:34:54.515  1014  1027 D PersonaManager: isKioskContainerExistOnDevice
,08-23 18:34:55.085   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 18:34:56.085   287   287 E SMD     : DCD OFF
,08-23 18:34:56.085   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 18:34:56.195  1014  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 18:34:56.195  1014  1467 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-23 18:34:56.195  1014  1467 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 18:34:56.195  1014  1467 D BatteryService: stay LED for fully charged
08-23 18:34:56.195  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 18:34:56.205  1167  1167 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 18:34:56.205  1167  1167 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 18:34:56.205  1014  1014 I MotionRecognitionService: Plugged
,08-23 18:34:56.205  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 18:34:56.205  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 18:34:56.205  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 18:34:56.215  3163  3163 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 18:34:56.215  3163  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-23 18:34:56.235  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 18:34:56.235  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 18:34:56.235  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 18:34:56.675  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-23 18:34:57.085   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 18:34:57.305  1014  1040 W ActivityManager: mDVFSHelper.release(),
,08-23 18:34:58.085   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 18:34:59.085   287   287 E SMD     : DCD OFF,
,08-23 18:34:59.085   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-23 18:34:59.975  1014  1093 V AlarmManager: waitForAlarm result :4
08-23 18:34:59.975  1014  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-23 18:34:59.985  1014  1093 V AlarmManager: waitForAlarm result :8
,08-23 18:35:00.095  4776  4776 D ConnectivityManager: CallingUid : 10011, CallingPid : 4776
,08-23 18:35:00.095  1014  1800 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 18:35:00.095  1014  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-23 18:35:00.095  1014  1126 D ConnectivityService: apparently satisfied.  currentScore=60
,08-23 18:35:00.095  1014  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-23 18:35:00.095  4776  6856 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-23 18:35:00.145  4776  6857 W DriveInitializer: Background init thread started
,08-23 18:35:00.185   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-23 18:35:00.185   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 18:35:00.195  4776  6857 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-23 18:35:00.235  4776  6857 W DriveInitializer: Background init thread ended
,08-23 18:35:01.225  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 18:35:01.225  6794  6848 I jxcore-log: 
08-23 18:35:01.225  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 18:35:01.225  6794  6848 I jxcore-log: 
,08-23 18:35:01.245  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:01.245  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:01.245  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:01.245  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:01.245  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:01.245  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:01.245  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:01.245  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:01.245  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:01.245  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 18:35:01.245  6794  6848 I jxcore-log: 
08-23 18:35:01.245  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 18:35:01.245  6794  6848 I jxcore-log: 
,08-23 18:35:01.475  1014  3364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 18:35:01.915  6794  6848 D ExecuteNativeTests: Running unit tests,
,08-23 18:35:02.005  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:02.005  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 added. We now have 2 listener(s)
,08-23 18:35:02.005  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 18:35:02.005  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:02.005  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:02.005  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:02.005  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 added. We now have 2 listener(s)
08-23 18:35:02.005  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:02.005  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 18:35:02.015  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:02.015  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:02.015  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:02.015  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:02.015  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:02.015  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:02.015  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:02.015  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:02.015  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:02.015  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:02.015  6794  6848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:35:02.015  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:02.025  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:02.025  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-23 18:35:02.025  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 18:35:02.025  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 18:35:02.025  6794  6848 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-23 18:35:02.025  6794  6848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 18:35:02.025  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 18:35:02.025  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 18:35:02.025  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-23 18:35:02.025  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 18:35:02.025  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.025  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.025  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.025  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.025  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:02.025  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:02.025  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 removed from the list
08-23 18:35:02.025  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.025  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 removed from the list
08-23 18:35:02.025  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.025  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.025  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.025  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.025  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.025  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.025  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.025  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.035  6794  6848 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-23 18:35:02.035  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.035  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.035  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.035  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.035  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.035  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.035  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.035  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.035  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.035  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.035  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.035  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.035  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.035  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.035  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.035  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.035  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.035  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.035  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 18:35:02.035  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 18:35:02.035  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 18:35:02.035  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 18:35:02.035  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 18:35:02.035  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 18:35:02.035  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 18:35:02.045  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.045  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.045  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.045  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.045  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.045  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.045  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.045  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.045  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.045  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.045  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.045  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.045  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.045  6794  6848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 18:35:02.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:02.055  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:02.055  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:02.055  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:02.055  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:02.055  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:02.055  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:02.055  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:02.055  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:35:02.055  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:02.055  6794  6848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:35:02.055  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:02.055  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:35:02.055  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:35:02.055  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:02.055  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:35:02.055  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 18:35:02.055  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:02.055  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:02.065  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 18:35:02.065  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 18:35:02.075  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-23 18:35:02.075  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-23 18:35:02.075  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 18:35:02.075  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 18:35:02.075  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 18:35:02.085  3163  3348 D BtGatt.GattService: registerClient() - UUID=d08d84e1-cdcc-4dfe-86e2-66d727883046
08-23 18:35:02.085   287   287 E SMD     : DCD OFF
,08-23 18:35:02.135  3163  3260 D BtGatt.GattService: onClientRegistered() - UUID=d08d84e1-cdcc-4dfe-86e2-66d727883046, clientIf=6
,08-23 18:35:02.135  6794  6802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 18:35:02.135  3163  3350 D BtGatt.GattService: start scan with filters
,08-23 18:35:02.135  3163  3266 D BtGatt.ScanManager: handling starting scan
,08-23 18:35:02.135  3163  3266 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:02.135  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 18:35:02.135  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 18:35:02.135  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 18:35:02.135  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 18:35:02.145  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:02.145  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 18:35:02.145  3163  3260 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-23 18:35:02.145  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:02.145  3163  3266 D BtGatt.ScanManager: allow scan with filters
08-23 18:35:02.145  3163  3266 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-23 18:35:02.145  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 18:35:02.145  3163  3266 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-23 18:35:02.145  3163  3260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 18:35:02.145  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:02.145  3163  3266 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 18:35:02.145  3163  3266 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 18:35:02.145  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:02.155  3163  3260 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-23 18:35:02.155  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:02.155  6794  6848 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 18:35:02.165  3163  3260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-23 18:35:02.165  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:02.165  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 18:35:02.165  6794  6848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 18:35:02.165  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 18:35:02.175  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 18:35:02.175  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.175  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 18:35:02.175  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 18:35:02.175  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:35:02.175  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:35:02.175  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 18:35:02.175  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 18:35:02.175  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 18:35:02.175  3163  3350 D BtGatt.GattService: stopScan() - queue size =1
,08-23 18:35:02.175  3163  3349 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-23 18:35:02.175  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:35:02.175  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 18:35:02.175  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 18:35:02.175  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 18:35:02.175  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 18:35:02.175  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:02.185  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 18:35:02.185  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 18:35:02.185  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 18:35:02.185  3163  3266 D BtGatt.ScanManager: filter size is 1
08-23 18:35:02.185  3163  3266 D BtGatt.ScanManager: delete FilterIndex - 3
,08-23 18:35:02.185  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:02.185  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:02.185  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.185  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.185  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:02.185  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.185  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.185  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.185  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.185  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.185  6794  6848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 18:35:02.185  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:02.185  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:02.185  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:02.185  3163  3260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-23 18:35:02.185  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:02.185  3163  3266 D BtGatt.ScanManager: stopping BLe Batch
,08-23 18:35:02.195  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:02.195  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:02.195  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:02.195  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:02.195  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:02.195  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:02.195  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:02.195  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:02.195  3163  3260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-23 18:35:02.195  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:02.195  6794  6848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:35:02.195  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:02.195  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:35:02.195  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:35:02.195  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:02.195  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 18:35:02.195  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:02.195  3163  3266 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-23 18:35:02.205  3163  3260 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-23 18:35:02.205  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:02.205  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:02.205  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 18:35:02.205  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:02.215  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 18:35:02.215  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 18:35:02.215  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 18:35:02.215  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-23 18:35:02.215  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 18:35:02.215  3163  3350 D BtGatt.GattService: registerClient() - UUID=977cd0a8-506a-4af6-a58a-bcb73e9cf413
,08-23 18:35:02.255  3163  3260 D BtGatt.GattService: onClientRegistered() - UUID=977cd0a8-506a-4af6-a58a-bcb73e9cf413, clientIf=6
,08-23 18:35:02.265  6794  6806 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 18:35:02.265  3163  3348 D BtGatt.GattService: start scan with filters
,08-23 18:35:02.265  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 18:35:02.265  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 18:35:02.265  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-23 18:35:02.265  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 18:35:02.265  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:02.265  3163  3266 D BtGatt.ScanManager: handling starting scan
,08-23 18:35:02.275  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 18:35:02.275  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:02.275  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:02.275  3163  3260 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-23 18:35:02.275  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:02.275  3163  3266 D BtGatt.ScanManager: allow scan with filters
08-23 18:35:02.275  3163  3266 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-23 18:35:02.275  3163  3266 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-23 18:35:02.275  6794  6848 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 18:35:02.285  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-23 18:35:02.285  6794  6848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 18:35:02.285  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.285  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 18:35:02.285  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:02.285  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 18:35:02.285  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 18:35:02.285  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:35:02.285  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:35:02.285  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 18:35:02.285  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 18:35:02.285  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 18:35:02.285  3163  3260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 18:35:02.285  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:02.285  3163  3266 D BtGatt.ScanManager: Starting BLE batch scan
08-23 18:35:02.285  3163  3266 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 18:35:02.285  3163  3348 D BtGatt.GattService: stopScan() - queue size =1
,08-23 18:35:02.285  3163  3349 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-23 18:35:02.285  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 18:35:02.285  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-23 18:35:02.285  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 18:35:02.285  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-23 18:35:02.285  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 18:35:02.295  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:02.295  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 18:35:02.295  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 18:35:02.295  3163  3260 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-23 18:35:02.295  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:02.295  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 18:35:02.295  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:02.295  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 18:35:02.295  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 18:35:02.295  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:02.295  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.295  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.295  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:02.295  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.295  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.295  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.295  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.295  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.295  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.295  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.305  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.305  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.305  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.305  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.305  3163  3260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-23 18:35:02.305  6794  6848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 18:35:02.305  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:02.305  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:02.305  3163  3266 D BtGatt.ScanManager: filter size is 1
08-23 18:35:02.305  3163  3266 D BtGatt.ScanManager: delete FilterIndex - 4
,08-23 18:35:02.315  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:02.315  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:02.315  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:02.315  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:02.315  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:02.315  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:02.315  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:02.315  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:02.315  3163  3260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-23 18:35:02.315  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:02.315  3163  3266 D BtGatt.ScanManager: stopping BLe Batch
,08-23 18:35:02.315  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:02.315  6794  6848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:35:02.315  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:02.315  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:35:02.315  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:35:02.315  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:02.315  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 18:35:02.315  3163  3260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-23 18:35:02.315  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:02.315  3163  3266 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-23 18:35:02.325  3163  3260 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-23 18:35:02.325  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:02.325  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 18:35:02.325  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:02.325  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:02.325  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 18:35:02.335  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 18:35:02.335  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 18:35:02.335  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 18:35:02.335  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 18:35:02.335  3163  3348 D BtGatt.GattService: registerClient() - UUID=39db15cc-66a0-420e-ad8c-02690e16e41a
,08-23 18:35:02.385  3163  3260 D BtGatt.GattService: onClientRegistered() - UUID=39db15cc-66a0-420e-ad8c-02690e16e41a, clientIf=6
,08-23 18:35:02.385  6794  6802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 18:35:02.385  3163  3349 D BtGatt.GattService: start scan with filters
,08-23 18:35:02.385  3163  3266 D BtGatt.ScanManager: handling starting scan
,08-23 18:35:02.385  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 18:35:02.385  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 18:35:02.385  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 18:35:02.385  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 18:35:02.385  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:02.395  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 18:35:02.395  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:02.395  3163  3260 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-23 18:35:02.395  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:02.395  3163  3266 D BtGatt.ScanManager: allow scan with filters
08-23 18:35:02.395  3163  3266 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-23 18:35:02.395  3163  3266 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-23 18:35:02.395  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:02.395  3163  3260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 18:35:02.395  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:02.395  3163  3266 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 18:35:02.395  3163  3266 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 18:35:02.405  6794  6848 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 18:35:02.405  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.405  6794  6848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 18:35:02.405  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.405  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 18:35:02.405  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 18:35:02.405  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 18:35:02.405  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:35:02.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:35:02.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 18:35:02.405  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 18:35:02.405  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 18:35:02.405  3163  3184 D BtGatt.GattService: stopScan() - queue size =1,
08-23 18:35:02.405  3163  3350 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-23 18:35:02.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:35:02.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-23 18:35:02.405  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 18:35:02.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-23 18:35:02.405  3163  3260 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-23 18:35:02.405  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:02.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 18:35:02.415  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:02.415  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 18:35:02.415  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 18:35:02.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 18:35:02.415  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:02.415  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:02.415  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.415  6794  6848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 18:35:02.415  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.415  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.415  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.415  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:02.415  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.415  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.415  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.415  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.415  3163  3260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-23 18:35:02.415  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:02.415  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:02.415  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:02.415  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.415  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.425  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.425  6794  6848 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-23 18:35:02.425  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.425  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.425  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.425  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.425  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.425  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.425  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.425  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.425  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.425  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.425  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.425  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.425  3163  3266 D BtGatt.ScanManager: filter size is 1
,08-23 18:35:02.425  3163  3266 D BtGatt.ScanManager: delete FilterIndex - 5
,08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.425  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.425  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 18:35:02.425  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.425  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.425  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.425  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.425  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.425  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.425  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.425  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.425  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.425  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.425  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.425  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.425  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.425  6794  6848 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-23 18:35:02.425  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.425  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 18:35:02.425  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.425  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.425  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.425  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.425  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:02.425  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.425  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.425  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.425  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.425  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.425  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.435  3163  3260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-23 18:35:02.435  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:02.435  3163  3266 D BtGatt.ScanManager: stopping BLe Batch
08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:02.435  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.435  6794  6848 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-23 18:35:02.435  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.435  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.435  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.435  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.435  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.435  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:02.435  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.435  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.435  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:02.435  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.435  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.435  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.435  3163  3260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-23 18:35:02.435  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:02.435  3163  3266 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:02.435  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 18:35:02.435  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 18:35:02.435  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-23 18:35:02.435  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 18:35:02.435  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.435  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.435  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.435  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.435  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.435  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.435  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.435  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.435  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.435  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.435  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.435  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.435  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.445  3163  3260 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-23 18:35:02.445  3163  3260 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:02.445  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.445  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.445  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.445  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.445  6794  6848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:35:02.445  6794  6848 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-23 18:35:02.445  6794  6848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:35:02.445  6794  6848 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 18:35:02.445  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 18:35:02.455  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 18:35:02.455  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 18:35:02.455  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 18:35:02.455  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 18:35:02.455  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 18:35:02.455  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 18:35:02.455  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 18:35:02.455  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 18:35:02.455  6794  6848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-23 18:35:02.455  6794  6848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 18:35:02.455  6794  6848 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-23 18:35:02.455  6794  6848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:35:02.455  6794  6848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 18:35:02.455  6794  6848 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-23 18:35:02.455  6794  6848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:35:02.455  6794  6848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 18:35:02.455  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-23 18:35:02.455  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-23 18:35:02.455  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-23 18:35:02.455  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-23 18:35:02.455  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-23 18:35:02.455  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-23 18:35:02.455  6794  6848 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-23 18:35:02.455  6794  6848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:35:02.455  6794  6848 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-23 18:35:02.455  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.455  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.455  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.455  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.455  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.455  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.455  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-23 18:35:02.455  6794  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1309)
,08-23 18:35:02.455  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.455  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.455  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.455  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.455  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.455  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.455  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.455  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.465  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.465  6794  6848 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-23 18:35:02.465  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.465  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.465  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.465  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.465  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.465  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.465  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.465  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.465  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.465  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.465  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.465  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.465  6794  6868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1309
,08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.465  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.465  6794  6848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-23 18:35:02.465  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.465  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.465  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.465  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.465  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.465  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.465  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.465  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.465  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.465  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.465  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.465  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.465  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.465  6794  6867 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,08-23 18:35:02.465  6794  6848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-23 18:35:02.465  6794  6848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-23 18:35:02.465  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 18:35:02.465  6794  6848 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-23 18:35:02.465  6794  6848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 18:35:02.465  6794  6848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-23 18:35:02.465  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 18:35:02.465  6794  6848 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-23 18:35:02.465  6794  6848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 18:35:02.465  6794  6848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 18:35:02.465  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 18:35:02.465  6794  6848 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-23 18:35:02.465  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.465  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.465  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.465  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.465  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.465  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.465  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.465  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.465  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.465  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.465  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.465  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.465  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: ,1 listener(s) left
,08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.475  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.475  6794  6867 D BluetoothSocket: connect(): myUserId = 0
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.475  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.475  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.475  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.475  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.475  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.475  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.475  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.475  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.475  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.475  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.475  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.475  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.475  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.475  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.475  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.475  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.interna,l.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.475  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.475  6794  6867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.475  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-23 18:35:02.475  3163  3350 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 18:35:02.475  6794  6794 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-23 18:35:02.475  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.475  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 18:35:02.475  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.475  6794  6794 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-23 18:35:02.475  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.475  6794  6869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-23 18:35:02.475  6794  6869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-23 18:35:02.475  6794  6867 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-23 18:35:02.485  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:02.485  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.485  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.485  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:02.485  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.485  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.485  6794  6794 I org.thaliproject.p2p.btconnec,torlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.485  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.485  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.485  6794  6794 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-23 18:35:02.485  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.485  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:02.485  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.485  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.485  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.485  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.485  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.485  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.485  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.485  6794  6848 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-23 18:35:02.485  6794  6848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 18:35:02.485  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 18:35:02.485  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.485  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.485  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.485  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.485  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.485  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:02.485  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.485  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.485  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.485  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.485  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:02.485  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.485  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.485  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:02.485  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.485  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:02.485  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.485  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.485  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.485  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
08-23 18:35:02.485  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.485  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.485  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.485  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.485  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.485  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.485  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.485  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 18:35:02.485  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:02.485  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:02.495  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-23 18:35:02.495  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.495  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.495  6794  6848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c046722 not in the list
08-23 18:35:02.495  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:02.495  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:02.495  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.495  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.495  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:02.495  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:02.495  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:02.495  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:02.495  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:02.495  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9875b3 not in the list
,08-23 18:35:02.495  6794  6848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 18:35:02.495  6794  6848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 18:35:02.495  6794  6848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-23 18:35:02.495  6794  6848 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1,
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 18:35:02.495  6794  6848 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 18:35:02.495  6794  6848 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-23 18:35:02.495  6794  6848 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-23 18:35:02.495  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:02.495  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@141d8b5d added. We now have 2 listener(s)
08-23 18:35:02.495  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:02.505  6794  6848 D BluetoothAdapter: enable()
,08-23 18:35:02.505  6794  6848 D BluetoothAdapter: enable(): BT is already enabled..!
,08-23 18:35:02.505  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-23 18:35:02.505  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 18:35:02.505  1014  1027 D SecContentProvider2: mCursor = null
,08-23 18:35:02.505  1014  1027 D WifiService: setWifiEnabled: true pid=6794, uid=10171
,08-23 18:35:02.515  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-23 18:35:02.515  1014  1027 W WifiService: Failed getting userId using ActivityManagerNative
08-23 18:35:02.515  1014  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 18:35:02.515  1014  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 18:35:02.515  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-23 18:35:02.515  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-23 18:35:02.515  1014  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-23 18:35:02.515  1014  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 18:35:02.515  1014  1027 D SettingsProvider: name = wifi_on
,08-23 18:35:02.515  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:35:02.515  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37f8dcd2 added. We now have 3 listener(s)
08-23 18:35:02.515  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:02.525  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:35:02.525  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4aa31a3 added. We now have 4 listener(s)
08-23 18:35:02.525  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:02.525  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:35:02.525  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ea8fca0 added. We now have 5 listener(s)
08-23 18:35:02.525  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:02.525  1014  1474 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-23 18:35:02.525  1014  1474 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 18:35:02.525  1014  1474 D SecContentProvider2: mCursor = null
,08-23 18:35:02.535  1014  1474 D WifiService: setWifiEnabled: false pid=6794, uid=10171
,08-23 18:35:02.535  1014  1474 D SettingsProvider: name = wifi_on
,08-23 18:35:02.545  1014  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state,
,08-23 18:35:02.545  1354  1354 I wpa_supplicant: reset timer : RESET_TIMER 0
08-23 18:35:02.545  1354  1354 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-23 18:35:02.545  1354  1354 I wpa_supplicant: P2P: Current p2p state = IDLE
08-23 18:35:02.545  6794  6848 D BluetoothAdapter: disable()
,08-23 18:35:02.545  1354  1354 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-23 18:35:02.555  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 18:35:02.555  1014  1132 D SettingsProvider: name = bluetooth_on,
,08-23 18:35:02.575  3163  3257 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-23 18:35:02.575  3163  3257 D BluetoothAdapterProperties: Setting state to 13
08-23 18:35:02.575  1014  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:02.575  3163  3257 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 18:35:02.575  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-23 18:35:02.575  3163  3257 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 18:35:02.575  3163  3257 D BluetoothAdapterService: updateAdapterState state is 13,
08-23 18:35:02.575  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:02.575  1014  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:02.575  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:02.585  3163  3163 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-23 18:35:02.585  3163  3257 D BluetoothAdapterService: Autoconnection is available 
08-23 18:35:02.585  3163  3257 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-23 18:35:02.585  3163  3257 D BluetoothAdapterService: terminating service from this receiver
08-23 18:35:02.585  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-23 18:35:02.585  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:02.585  1014  4756 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:02.585  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 18:35:02.585  3163  3163 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c162dc9, channel: 19, state: LISTENING
,08-23 18:35:02.585  3163  3163 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c162dc9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@367e5d91, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39daeccemSocket: android.net.LocalSocket@bb1c7ef impl:android.net.LocalSocketImpl@377722fc fd:FileDescriptor[74]
,08-23 18:35:02.585  1354  1354 I wpa_supplicant: nl80211: Received scan results (13 BSSes)
08-23 18:35:02.585  3163  3163 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@bb1c7ef impl:android.net.LocalSocketImpl@377722fc fd:FileDescriptor[74]
,08-23 18:35:02.585  3163  3257 D BluetoothAdapterProperties: onBluetoothDisable()
,08-23 18:35:02.585  3163  3257 D BluetoothAdapterProperties: mDiscovering is false
,08-23 18:35:02.585  1014  1124 E WifiNative-wlan0: do suspend true
08-23 18:35:02.585  1014  1800 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 18:35:02.585  1014  1123 D WifiP2pService: InactiveState{ what=147461 }
,08-23 18:35:02.585  3163  3257 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-23 18:35:02.585  1014  1123 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-23 18:35:02.595  1014  1123 D WifiP2pService: DefaultState{ what=147461 }
,08-23 18:35:02.595  1303  1303 D BluetoothPbap: Proxy object disconnected
08-23 18:35:02.595  1303  1303 D PbapServerProfile: Bluetooth service disconnected
,08-23 18:35:02.595  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:02.595  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:02.595  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
08-23 18:35:02.595  3163  3260 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-23 18:35:02.595  3163  3260 D BluetoothAdapterProperties: Scan Mode:20
,08-23 18:35:02.605  1167  1167 D BluetoothTile:  onBluetoothStateChange:
,08-23 18:35:02.605  1167  1167 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 18:35:02.605  1167  1167 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:02.605  1167  1167 D BluetoothTile:  getBluetoothState : 13
,08-23 18:35:02.605  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 18:35:02.605  1872  1872 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 18:35:02.615  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:02.615  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 18:35:02.615  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:02.615  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:02.615  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:02.615  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:02.615  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:02.615  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:02.615  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:02.615  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:02.615  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:02.615  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:02.615  6794  6848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:35:02.615  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-23 18:35:02.615  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:02.615  1014  1026 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 18:35:02.625  1014  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 18:35:02.625  3163  3257 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-23 18:35:02.625  1014  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-23 18:35:02.625  3163  3257 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-23 18:35:02.625  3163  3257 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-23 18:35:02.625  3163  3257 E bt-btif : cmd socket is not created
,08-23 18:35:02.625  3163  5123 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 18:35:02.625  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:02.625  3163  3282 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-23 18:35:02.625  3163  3282 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-23 18:35:02.625  6794  6867 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c63f41e, channel: -1, state: INIT
08-23 18:35:02.625  6794  6867 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c63f41e, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@82444ff, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@20b142ccmSocket: android.net.LocalSocket@239bc915 impl:android.net.LocalSocketImpl@3bd7342a fd:FileDescriptor[106]
08-23 18:35:02.625  6794  6867 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@239bc915 impl:android.net.LocalSocketImpl@3bd7342a fd:FileDescriptor[106]
08-23 18:35:02.625  6794  6867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1309)
,08-23 18:35:02.625  3163  3282 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:35:02.625  3163  3282 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:35:02.625  3163  3282 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:35:02.625  3163  3257 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 18:35:02.625  1014  1026 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 18:35:02.625  1014  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:02.625  1014  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:02.625  1014  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:02.625  1167  1167 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 18:35:02.635  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:02.635  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 18:35:02.635  1014  1800 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-23 18:35:02.635  1014  1800 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 18:35:02.635  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:02.635  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:02.635  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:02.635  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:02.635  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:02.635  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:02.635  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:02.635  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:02.635  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:02.635  1014  1800 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:02.635  1014  1800 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:02.635  1014  1800 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-23 18:35:02.635  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:02.635  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:02.645  3163  3163 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a3d07da, channel: 5, state: LISTENING
08-23 18:35:02.645  3163  3163 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1a3d07da, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@237634f6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30fcf40bmSocket: android.net.LocalSocket@399172e8 impl:android.net.LocalSocketImpl@1b60cd01 fd:FileDescriptor[76]
08-23 18:35:02.645  3163  3163 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@399172e8 impl:android.net.LocalSocketImpl@1b60cd01 fd:FileDescriptor[76]
,08-23 18:35:02.645  3163  3163 I BtOppRfcommListener: stopping Accept Thread
,08-23 18:35:02.645  3163  3163 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3673c7a6, channel: 12, state: LISTENING
08-23 18:35:02.645  3163  3163 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3673c7a6, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@318039d0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@684c5e7mSocket: android.net.LocalSocket@327ed594 impl:android.net.LocalSocketImpl@298c383d fd:FileDescriptor[79]
08-23 18:35:02.645  3163  3163 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@327ed594 impl:android.net.LocalSocketImpl@298c383d fd:FileDescriptor[79]
,08-23 18:35:02.645  3163  5123 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-23 18:35:02.645  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:02.655  3163  3163 V BluetoothOppManager: cleanUp...
,08-23 18:35:02.655  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:02.655  1303  1303 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:35:02.655  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:02.655  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 18:35:02.665  1167  1167 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:02.665  1167  1167 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-23 18:35:02.665  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-23 18:35:02.665  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:02.665  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:02.665  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:02.665  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:02.675  6876  6876 E Zygote  : MountEmulatedStorage()
08-23 18:35:02.675  6876  6876 E Zygote  : v2
,08-23 18:35:02.675  6876  6876 I libpersona: KNOX_SDCARD checking this for 10055
08-23 18:35:02.675  6876  6876 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:02.685  1014  1027 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6876 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-23 18:35:02.685  6876  6876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:02.685  6876  6876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:02.685  6876  6876 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 18:35:02.715  6876  6876 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:02.715  6876  6876 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:02.725  1014  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-23 18:35:02.725  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 18:35:02.725   276   972 D CommandListener: Clearing all IP addresses on wlan0
,08-23 18:35:02.735  2025  3016 V NativeCrypto: Read error: ssl=0xb938bc00: I/O error during system call, Connection timed out
08-23 18:35:02.735  2025  3016 V NativeCrypto: SSL shutdown failed: ssl=0xb938bc00: I/O error during system call, Broken pipe
,08-23 18:35:02.735  2025  3016 E GCM     : Wifi connection closed with errorCode 20
,08-23 18:35:02.735  1014  1126 E ConnectivityService: updateNetworkInfo()
08-23 18:35:02.735  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:35:02.735  1014  1126 E ConnectivityService: updateNetworkInfo()
08-23 18:35:02.735  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-23 18:35:02.735  1014  1132 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-23 18:35:02.745  1167  1167 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:02.745  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-23 18:35:02.745  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:02.745  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.745  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.745  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:02.755  1014  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-11ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:35:02.755  1014  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-11ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:35:02.755  1014  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,08-23 18:35:02.755  1014  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:35:02.755  1014  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-23 18:35:02.755  1014  1761 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 18:35:02.755  1014  1761 I qtaguid : Tagging socket 352 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1014, getuid(): 1000
,08-23 18:35:02.755  1014  1761 I qtaguid : Untagging socket 352
,08-23 18:35:02.755  1014  1761 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 18:35:02.765  1014  1123 D WifiP2pService: InactiveState{ what=131204 }
08-23 18:35:02.765  1014  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
08-23 18:35:02.765  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-23 18:35:02.765  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-23 18:35:02.775  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-23 18:35:02.775  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:02.775  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.775  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:02.775  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.775  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.775  6876  6876 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-23 18:35:02.775  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
08-23 18:35:02.775  1014  1014 D RttService: SCAN_AVAILABLE : 1
,08-23 18:35:02.775  1014  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler },
08-23 18:35:02.775  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:35:02.775  1014  1148 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:35:02.775  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-23 18:35:02.785  1014  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-23 18:35:02.785  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-23 18:35:02.785  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-23 18:35:02.785  1014  1123 D WifiP2pService: P2pDisablingState
,08-23 18:35:02.795  1014  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
08-23 18:35:02.795  1014  1123 D WifiP2pService: p2p socket connection lost
,08-23 18:35:02.795  1014  1123 D WifiP2pService: P2pDisabledState
,08-23 18:35:02.795  1014  1124 E WifiNative-wlan0: do suspend true
,08-23 18:35:02.805  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-23 18:35:02.805  6876  6876 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-23 18:35:02.805  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-23 18:35:02.805  6876  6876 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-23 18:35:02.805  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-23 18:35:02.805  6876  6876 D UserAnalysis: Create SecureDbHelper
08-23 18:35:02.805  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 18:35:02.805  1014  1045 D WifiDisplayController: disconnect
08-23 18:35:02.805  1014  1045 D WifiDisplayController: updateConnection
08-23 18:35:02.805  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-23 18:35:02.805  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-23 18:35:02.805  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-23 18:35:02.805  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 18:35:02.805  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-23 18:35:02.815  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 18:35:02.815  1167  1167 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-23 18:35:02.815  6876  6876 D IntelligenceServiceApplication: onCreate(),
08-23 18:35:02.815  1014  4757 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 18:35:02.815  1167  1167 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0,
,08-23 18:35:02.825  1014  1467 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-23 18:35:02.825  3163  3336 I bt_userial_mct: exiting userial_read_thread
08-23 18:35:02.825  3163  3336 D bt_userial_mct: Leaving userial_evt_read_thread()
08-23 18:35:02.825  1014  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:02.825  3163  3282 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:35:02.825  1014  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:02.825  3163  3282 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:35:02.825  1014  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:02.825  3163  3282 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:35:02.825  1014  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:02.825  3163  3282 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:35:02.825  3163  3282 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:35:02.825  3163  3282 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:35:02.825  3163  3282 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:35:02.825  3163  3282 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:35:02.825  3163  3282 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:35:02.825  3163  3282 W bt-btif : ag scb idx 1 not allocated
08-23 18:35:02.825  3163  3282 W bt-btif : ag scb idx 2 not allocated
08-23 18:35:02.825  3163  3282 E bt-btif : BTA AG is already disabled, ignoring ...
08-23 18:35:02.825  3163  3260 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-23 18:35:02.825  3163  3284 I bt_vendor: hw_epilog_process
08-23 18:35:02.825  3163  3260 D bt_userial_mct: userial_close
08-23 18:35:02.825  3163  3260 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-23 18:35:02.825  6876  6876 D IntelligenceServiceApplication: no applications having user consent for prediction,
,08-23 18:35:02.835  6899  6899 E Zygote  : MountEmulatedStorage()
,08-23 18:35:02.835  6899  6899 I libpersona: KNOX_SDCARD checking this for 10105
08-23 18:35:02.835  6899  6899 E Zygote  : v2
08-23 18:35:02.835  6899  6899 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:02.835  6899  6899 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:02.835  1014  1467 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6899 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-23 18:35:02.845  6899  6899 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 18:35:02.845  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-23 18:35:02.845  6899  6899 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 18:35:02.845  6876  6876 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-23 18:35:02.855  6876  6876 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-23 18:35:02.855  1014  1132 I ActivityManager: Killing 6448:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-23 18:35:02.875  6899  6899 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:02.875  6899  6899 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:02.925  1014  1123 D WifiP2pService: P2pDisabledState{ what=143375 },
08-23 18:35:02.925  1014  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-23 18:35:02.925  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 18:35:02.925  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:02.935  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:02.935  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.935  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.935  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:02.935  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-23 18:35:02.935  1014  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-23 18:35:02.935  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-23 18:35:02.935  1014  1126 V NetworkStats: updateIfacesLocked()
08-23 18:35:02.935  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 18:35:02.935  1014  1126 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:02.935   276   968 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-23 18:35:02.935   276   968 D Netd    : getNetworkForDns: using netid 0 for uid 1000,
08-23 18:35:02.945   276   972 D CommandListener: Clearing all IP addresses on wlan0
08-23 18:35:02.945  1014  1126 V NetworkStats: performPollLocked() took 9ms
08-23 18:35:02.945  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:02.945  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-23 18:35:02.945  1014  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,08-23 18:35:02.945  1014  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-23 18:35:02.955  1354  1354 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-23 18:35:02.955  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:02.955  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:02.955  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.955  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.955  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.955  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:02.955  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:02.955  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:02.955  1014  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-23 18:35:02.965  1167  1676 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-23 18:35:02.965  4776  6856 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-23 18:35:02.965  1014  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:35:02.965  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-23 18:35:02.965  1014  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:35:02.965  1014  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-23 18:35:02.965  1014  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-23 18:35:02.965  1014  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-23 18:35:02.965  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-23 18:35:02.965  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:02.965  1014  1124 D SecContentProvider2: mCursor = null
08-23 18:35:02.965  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-23 18:35:02.965  1456  1456 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 18:35:02.975  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-23 18:35:02.975  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
08-23 18:35:02.975  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.975  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 18:35:02.975  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:02.975  1167  1167 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 18:35:02.975  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.975  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:02.975  1167  1167 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 18:35:02.975  1167  1167 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-23 18:35:02.975  1167  1167 D HotspotTile: onReceive : 0, 0
,08-23 18:35:02.985  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-23 18:35:02.985  6794  6794 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 18:35:02.985  1014  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-23 18:35:02.985  1014  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-23 18:35:02.985  1014  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-23 18:35:02.985  1014  1126 E ConnectivityService: updateNetworkInfo()
08-23 18:35:02.985  1014  1126 E ConnectivityService: updateNetworkInfo()
08-23 18:35:02.985  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-23 18:35:02.985  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:02.985  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-23 18:35:02.985  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:02.985  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:02.985  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:02.985  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:02.985  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:02.985  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:02.985  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:02.985  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:35:02.985  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:02.985  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:02.995  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:02.995  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:02.995  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:02.995  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:02.995  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:02.995  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:02.995  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:02.995  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:02.995  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:02.995  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:02.995  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:02.995  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-23 18:35:02.995  1014  1127 D Tethering: MasterInitialState.processMessage what=3
,08-23 18:35:02.995  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:02.995  1014  1121 V NetworkStats: updateIfacesLocked()
08-23 18:35:02.995  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:02.995  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 18:35:02.995  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 18:35:02.995  1167  1167 D StatusBar.NetworkController: EthernetConnected: false
08-23 18:35:02.995  1167  1167 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-23 18:35:02.995  1167  1167 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-23 18:35:02.995  1167  1167 D StatusBar.NetworkController: updateDataNetType()
08-23 18:35:02.995  1167  1167 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-23 18:35:02.995  1167  1167 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-23 18:35:03.005  1014  1121 V NetworkStats: performPollLocked() took 5ms
,08-23 18:35:03.005  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:03.005  1167  1167 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-23 18:35:03.005  1167  1167 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-23 18:35:03.005  1167  1167 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-23 18:35:03.005  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:03.005  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 18:35:03.005  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:03.005  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:03.005  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:03.005  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:03.005  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:03.005  1014  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-23 18:35:03.005  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:03.005  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:03.005  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:03.005  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:03.005  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:03.015   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-23 18:35:03.015   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 18:35:03.025  6899  6919 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 18:35:03.025   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-23 18:35:03.025   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 18:35:03.025  6899  6919 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 18:35:03.035  3163  3260 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-23 18:35:03.035  3163  3260 I bt_vendor: bluetooth satus is on
08-23 18:35:03.035  3163  3260 I bt_vendor: bt-vendor : resetting BT status
08-23 18:35:03.035  3163  3260 I bt_vendor: Starting hciattach daemon
08-23 18:35:03.035  3163  3260 I bt_vendor: try to set false
,08-23 18:35:03.035  3163  3260 I bt_vendor: Starting hciattach daemon
08-23 18:35:03.035  3163  3260 I bt_vendor: try to set false
,08-23 18:35:03.035  3163  3260 I bt_vendor: cleanup
,08-23 18:35:03.035  3163  3282 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-23 18:35:03.035  3163  3260 I GKI_LINUX: GKI_exit_task 0 done
,08-23 18:35:03.035  3163  3260 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-23 18:35:03.035  3163  3257 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-23 18:35:03.035  3163  3257 D BtConfig.SecureMode: isSecureModeOn:false
08-23 18:35:03.035  3163  3257 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-23 18:35:03.035  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-23 18:35:03.035  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-23 18:35:03.045  3163  3257 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-23 18:35:03.045  1014  4756 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:03.045  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-23 18:35:03.045  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:03.045  1014  4756 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:03.045  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:03.045  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-23 18:35:03.045  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-23 18:35:03.045  3163  3257 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-23 18:35:03.045  1014  4757 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:03.045  1014  4757 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-23 18:35:03.045  1014  4757 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:03.045  1014  4757 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:03.045  1014  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:03.045  3163  3163 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 18:35:03.055  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-23 18:35:03.055  3163  3163 D BtGatt.GattService: Received stop request...Stopping profile...
,08-23 18:35:03.055  3163  3163 D BtGatt.GattService: stop()
08-23 18:35:03.055  3163  3163 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 18:35:03.055  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-23 18:35:03.055  3163  3257 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-23 18:35:03.055  1014  4756 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:03.055  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 18:35:03.055  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:03.055  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:03.055  1014  4756 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:03.055  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:03.055  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-23 18:35:03.055  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-23 18:35:03.065  3163  3257 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-23 18:35:03.065  1014  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:03.065  1014  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 18:35:03.065  1014  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:03.065  1014  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:03.065  1014  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:03.065  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-23 18:35:03.065  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-23 18:35:03.065  3163  3163 D HeadsetService: Received stop request...Stopping profile...
,08-23 18:35:03.065  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:03.075  1354  1354 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 18:35:03.075  3163  3257 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-23 18:35:03.075  1014  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:03.075  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-23 18:35:03.075  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:03.075  1014  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:03.075  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:03.075  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-23 18:35:03.075  1303  1303 D HeadsetProfile: Bluetooth service disconnected
,08-23 18:35:03.075  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-23 18:35:03.075  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-23 18:35:03.075  3163  3257 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-23 18:35:03.075  1014  4757 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:03.075  1014  4757 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 18:35:03.085  1014  4757 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:03.085  1014  4757 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:03.085  1014  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:03.085  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-23 18:35:03.085  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:03.085  3163  3257 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:03.085  1014  4756 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:03.085  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 18:35:03.085  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:03.085  1014  4756 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:03.085  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:03.085  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService,
08-23 18:35:03.085  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 18:35:03.085  3163  3257 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-23 18:35:03.085  1014  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:03.085  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-23 18:35:03.085  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:03.085  1014  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:03.085  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:03.095  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 18:35:03.095  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 18:35:03.095  3163  3257 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 18:35:03.095  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:03.095  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-23 18:35:03.095  3163  3257 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:03.095  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-23 18:35:03.095  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-23 18:35:03.095  3163  3257 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-23 18:35:03.095  3163  3257 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-23 18:35:03.095  3163  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-23 18:35:03.095  3163  3257 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 18:35:03.095  3163  3257 D BluetoothAdapterState: Stopping profile services that were post enabled
08-23 18:35:03.095  3163  3163 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-23 18:35:03.105  1354  1354 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-23 18:35:03.105  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 18:35:03.105  3163  3163 D A2dpService: Received stop request...Stopping profile...
,08-23 18:35:03.105  3163  3273 D A2dpStateMachine: Exit Disconnected: -1
08-23 18:35:03.105  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-23 18:35:03.105  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-23 18:35:03.105  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:03.115  1303  1303 D BluetoothA2dp: Proxy object disconnected
08-23 18:35:03.115  1303  1303 D A2dpProfile: Bluetooth service disconnected
,08-23 18:35:03.115  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-23 18:35:03.115  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-23 18:35:03.115  3163  3163 D HidService: Received stop request...Stopping profile...
,08-23 18:35:03.115  3163  3163 D HidService: Stopping Bluetooth HidService
,08-23 18:35:03.115  3163  3163 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 18:35:03.115  3163  3163 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-23 18:35:03.115  3163  3163 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-23 18:35:03.115  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:03.115  3163  3163 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-23 18:35:03.115  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 18:35:03.115  3163  3163 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-23 18:35:03.115  1303  1303 D BluetoothInputDevice: Proxy object disconnected
08-23 18:35:03.115  1303  1303 D HidProfile: Bluetooth service disconnected
08-23 18:35:03.115  1014  3342 D SSRM:n  : SIOP:: AP = 340
,08-23 18:35:03.125  3163  3163 D HealthService: Received stop request...Stopping profile...
,08-23 18:35:03.125  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:03.125  1354  1354 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-23 18:35:03.125  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:03.125  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:03.125  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-23 18:35:03.125  1354  1354 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-23 18:35:03.125  1354  1354 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-23 18:35:03.125  1354  1354 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-23 18:35:03.125  1354  1354 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-23 18:35:03.125  1014  1127 D Tethering: InitialState.processMessage what=4
,08-23 18:35:03.125  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:03.125  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-23 18:35:03.135  3163  3163 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 18:35:03.135  3163  3163 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-23 18:35:03.135  3163  3163 D PanService: Received stop request...Stopping profile...
08-23 18:35:03.135  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:03.135  1014  1127 E Tethering: No numeric data
08-23 18:35:03.135  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 18:35:03.135  1303  1303 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 18:35:03.135  1303  1303 D PanProfile: Bluetooth service disconnected
,08-23 18:35:03.135  1014  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 18:35:03.135  3163  3163 D BluetoothMapService: Received stop request...Stopping profile...
,08-23 18:35:03.135  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:03.135  1014  1127 D Tethering: clearTetheredNotification()
,08-23 18:35:03.135  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:03.135  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:03.135  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:03.135  1014  1042 D Tethering: interfaceStatusChanged wlan0, false,
08-23 18:35:03.135  1167  1167 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 18:35:03.135  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 18:35:03.135  1167  1167 D HotspotTile: updateTetherState():false, false
08-23 18:35:03.145  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 18:35:03.145  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 18:35:03.145  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 18:35:03.145  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:03.145  1014  1121 V NetworkStats: performPollLocked() took 5ms
,08-23 18:35:03.145  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:03.145  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:03.145  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:03.145  3163  3163 D SapService: Received stop request...Stopping profile...
08-23 18:35:03.145  3163  3163 D SapService: Stopping Bluetooth SapService
08-23 18:35:03.145  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
08-23 18:35:03.145  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 18:35:03.145  3163  3163 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-23 18:35:03.145  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 18:35:03.155  3163  3163 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-23 18:35:03.155  3163  3274 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-23 18:35:03.155  3163  3163 I GKI_LINUX: GKI_exit_task 2 done
08-23 18:35:03.155  3163  3163 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-23 18:35:03.155  3163  3163 D BluetoothA2dp: Proxy object disconnected
08-23 18:35:03.155  3163  3163 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-23 18:35:03.155  3163  3163 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-23 18:35:03.155  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 18:35:03.155  3163  3163 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:03.155  3163  3163 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-23 18:35:03.155  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 18:35:03.155  3163  3163 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-23 18:35:03.155  3163  3163 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 18:35:03.155  3163  3163 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-23 18:35:03.155  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 18:35:03.155  3163  3163 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-23 18:35:03.155  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 18:35:03.155  3163  3163 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:03.155  3163  3163 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 18:35:03.155  3163  3163 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-23 18:35:03.155  1303  1303 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-23 18:35:03.155  1303  1303 D SapProfile: Bluetooth service disconnected
,08-23 18:35:03.155  3163  3163 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-23 18:35:03.155  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 18:35:03.155  3163  3163 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-23 18:35:03.155  3163  3163 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-23 18:35:03.155  3163  3163 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-23 18:35:03.155  3163  3163 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-23 18:35:03.155  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 18:35:03.155  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 18:35:03.155  3163  3257 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-23 18:35:03.155  3163  3257 D BluetoothAdapterProperties: Setting state to 10
08-23 18:35:03.155  3163  3257 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-23 18:35:03.155  3163  3257 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 18:35:03.155  3163  3257 D BluetoothAdapterService: updateAdapterState state is 10
,08-23 18:35:03.155  3163  3257 D BluetoothAdapterService: Autoconnection is available 
08-23 18:35:03.165  3163  3257 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-23 18:35:03.165  3163  3257 I BluetoothAdapterState: Entering OffState
,08-23 18:35:03.165  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 18:35:03.165  1303  1303 D BluetoothMap: Proxy object disconnected
08-23 18:35:03.165  1303  1303 D MapProfile: Bluetooth service disconnected
08-23 18:35:03.165  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 18:35:03.165  1303  1312 D Bluetoothsap: onBluetoothStateChange: up=false
08-23 18:35:03.165  1303  1312 D Bluetoothsap: Unbinding service...
,08-23 18:35:03.165  2025  2195 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 18:35:03.165  2025  2195 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:03.165  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 18:35:03.165  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 18:35:03.165  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 18:35:03.165  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 18:35:03.165  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 18:35:03.165  1303  6930 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 18:35:03.165  1303  1312 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 18:35:03.165  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 18:35:03.175  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 18:35:03.175  1303  1316 D BluetoothMap: onBluetoothStateChange: up=false
,08-23 18:35:03.175  1303  6930 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 18:35:03.175  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 18:35:03.175  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 18:35:03.175  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 18:35:03.175  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 18:35:03.175  6794  6806 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 18:35:03.175  6794  6806 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 18:35:03.175  6794  6806 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-23 18:35:03.175  6794  6806 D BluetoothLeAdvertiser: Exit stop advertising
08-23 18:35:03.175  6794  6806 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-23 18:35:03.175  6794  6806 D BluetoothLeScanner: Exiting stopAllScan
,08-23 18:35:03.175  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 18:35:03.175  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 18:35:03.175  1429  1437 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 18:35:03.175  1429  1437 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 18:35:03.175  1303  1316 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 18:35:03.175  1303  1316 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 18:35:03.175  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 18:35:03.175  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 18:35:03.175  1456  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 18:35:03.175  1456  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:03.175  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 18:35:03.175  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 18:35:03.175  1439  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 18:35:03.175  1439  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 18:35:03.175  3163  3184 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 18:35:03.175  1167  2343 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 18:35:03.175  1167  2343 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:03.185  3163  3348 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 18:35:03.185  3163  3348 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 18:35:03.185  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 18:35:03.185  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 18:35:03.185  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 18:35:03.185  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-23 18:35:03.185  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 18:35:03.185   269   269 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8c487c8
08-23 18:35:03.185   269   269 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-23 18:35:03.185  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 18:35:03.185  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 18:35:03.185   269   269 I rmt_storage: wakelock acquired: 1, error no: 42
08-23 18:35:03.185   269   366 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1195079544)
,08-23 18:35:03.195  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 18:35:03.195  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-23 18:35:03.195  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 18:35:03.195  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 18:35:03.195  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:03.195  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-23 18:35:03.195  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-23 18:35:03.205  1167  1167 D BluetoothAdapter: 120810158: getState() :  mService = null. Returning STATE_OFF
08-23 18:35:03.205  1167  1167 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-23 18:35:03.205  1167  1745 D BluetoothAdapter: 120810158: getState() :  mService = null. Returning STATE_OFF
,08-23 18:35:03.205  1167  1167 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:03.205  1167  1167 D BluetoothTile:  getBluetoothState : 10
,08-23 18:35:03.205  1167  1745 D BluetoothAdapter: 120810158: getState() :  mService = null. Returning STATE_OFF
08-23 18:35:03.205  1167  1167 D BluetoothAdapter: 120810158: getState() :  mService = null. Returning STATE_OFF
08-23 18:35:03.205  1167  1167 D BluetoothAdapter: 120810158: getState() :  mService = null. Returning STATE_OFF
08-23 18:35:03.205  1014  1026 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-23 18:35:03.205  1014  1319 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 18:35:03.205  1872  1872 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-23 18:35:03.205  1167  1167 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 18:35:03.205  2025  2219 D BluetoothAdapter: 692429084: getState() :  mService = null. Returning STATE_OFF
,08-23 18:35:03.205  2025  2219 D BluetoothAdapter: 692429084: getState() :  mService = null. Returning STATE_OFF
,08-23 18:35:03.215  1014  4756 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 18:35:03.215  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 18:35:03.215  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:03.215  1014  4756 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:03.215  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:03.215  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:03.215  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:03.215  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:03.215  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:03.215  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:03.215  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:03.215  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:03.215  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:03.215  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:03.215  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:03.215  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:03.235  3163  3260 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-23 18:35:03.235  3163  3163 I GKI_LINUX: GKI_exit_task 1 done
08-23 18:35:03.235  3163  3163 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-23 18:35:03.235  3163  3163 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-23 18:35:03.235  3163  3163 I art     : System.exit called, status: 0
,08-23 18:35:03.235  3163  3163 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 18:35:03.245   269   366 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-23 18:35:03.245   269   366 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-23 18:35:03.245   269   366 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1195079544) wakelock released: 1, error no: 0
08-23 18:35:03.245   269   366 I rmt_storage: 
,08-23 18:35:03.245   269   269 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8c487c8
,08-23 18:35:03.275  6899  6899 D StrictMode: StrictMode policy violation; ~duration=245 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:03.275  6899  6899 D StrictMode: StrictMode policy violation; ~duration=244 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:03.275  6899  6899 D StrictMode: StrictMode policy violation; ~duration=244 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:03.275  6899  6899 D StrictMode: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:03.275  6899  6899 D StrictMode: StrictMode policy violation; ~duration=238 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:03.,275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:03.275  6899  6899 D StrictMode: StrictMode policy violation; ~duration=235 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.k.d(PG:583)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:03.275  6899  6899 D StrictMode: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:03.275  1014  1319 I ActivityManager: Killing 6477:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-23 18:35:03.275  6899  6899 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-23 18:35:03.275  6899  6899 D StrictMode: StrictMode policy violation; ~duration=204 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-23 18:35:03.275  6899  6899 D StrictMode: StrictMode policy violation; ~duration=204 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:03.275  6899  6899 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-23 18:35:03.275  2025  2025 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:03.295  1354  1354 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 18:35:03.295  2025  2025 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.,
08-23 18:35:03.295  1014  1132 W ActivityManager: userId = 0, bbcId = -10000,
08-23 18:35:03.295  1014  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:03.295  1014  1132 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-23 18:35:03.295  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-23 18:35:03.295  1014  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:03.295  1014  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:03.295  1014  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:03.295  1014  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:03.315  6953  6953 E Zygote  : MountEmulatedStorage()
,08-23 18:35:03.315  6953  6953 E Zygote  : v2
08-23 18:35:03.315  6953  6953 I libpersona: KNOX_SDCARD checking this for 10102
08-23 18:35:03.315  6953  6953 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:03.315  6953  6953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-23 18:35:03.315  1014  1132 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6953 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-23 18:35:03.315  6953  6953 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:03.315  6953  6953 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 18:35:03.335  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:03.335  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:03.335  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-23 18:35:03.335  1354  1354 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-23 18:35:03.335  6899  6936 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-23 18:35:03.335  1014  1477 I ActivityManager: Process com.android.bluetooth (pid 3163)(adj 0) has died(28,720)
,08-23 18:35:03.345  6953  6953 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 18:35:03.345  6953  6953 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:03.365  1014  4757 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 18:35:03.365  1014  4757 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:03.365  1014  4757 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:03.365  1014  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-23 18:35:03.365  6953  6953 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-23 18:35:03.435  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-23 18:35:03.435  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-23 18:35:03.445  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 18:35:03.445  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 18:35:03.445  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:03.445  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:03.445  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:03.445  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:03.445  1167  1167 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:35:03.445  1167  1167 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-23 18:35:03.445  1167  1167 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:35:03.445  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-23 18:35:03.445  2025  2219 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 18:35:03.445  1167  1167 D HotspotTile: onReceive : 1, 0
,08-23 18:35:03.455  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:03.455  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:03.455  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:35:03.485  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:03.485  1014  1014 I ApplicationPolicy: updateDataUsageMap
,08-23 18:35:03.505  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:03.505  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:03.505  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:03.575  6953  6976 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-23 18:35:03.575  6953  6976 I Babel_SMS: MmsConfig.loadMmsSettings
08-23 18:35:03.575  6953  6976 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-23 18:35:03.575  6953  6976 I Babel_SMS: MmsConfig.loadFromDatabase
,08-23 18:35:03.595  6953  6976 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-23 18:35:03.595  6953  6976 I Babel_SMS: MmsConfig.loadFromResources
,08-23 18:35:03.605  6953  6976 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-23 18:35:03.605  6953  6976 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-23 18:35:03.615  1014  1474 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-23 18:35:03.615  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-23 18:35:03.615  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:03.615  1014  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:03.615  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-23 18:35:03.635  6953  6953 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 18:35:03.645  6953  6953 I Babel_Crash: startup - clean
,08-23 18:35:03.675  1014  1132 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 18:35:03.675  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:03.675  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:03.675  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:03.675  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:03.675  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 18:35:03.675  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 18:35:03.685  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-23 18:35:03.685  1621  1621 I Hs20UtilService: Starting #8
,08-23 18:35:03.685  1621  1646 I Hs20UtilService: Message received 5007
08-23 18:35:03.685  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 18:35:03.685  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-23 18:35:03.685  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 18:35:03.685  1303  2230 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 18:35:03.685  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 18:35:03.695  6953  6953 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-23 18:35:03.695  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 18:35:03.695  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 18:35:03.695  6953  6953 W AudioCapabilities: Unsupported mime audio/evrc
,08-23 18:35:03.695  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 18:35:03.695  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 18:35:03.695  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 18:35:03.695  6953  6953 W AudioCapabilities: Unsupported mime audio/qcelp
08-23 18:35:03.695  1303  2230 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 18:35:03.695  1014  1800 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-23 18:35:03.695  1014  1800 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:03.695  1014  1800 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:03.695  1014  1800 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:03.695  1014  1800 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:03.695  6953  6953 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-23 18:35:03.705  6953  6953 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-23 18:35:03.705  6953  6953 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-23 18:35:03.705  6953  6953 W AudioCapabilities: Unsupported mime audio/x-ima
,08-23 18:35:03.705  6953  6953 W AudioCapabilities: Unsupported mime audio/qcelp
,08-23 18:35:03.705  6953  6953 W AudioCapabilities: Unsupported mime audio/evrc
,08-23 18:35:03.715  6979  6979 E Zygote  : MountEmulatedStorage(),
,08-23 18:35:03.715  6979  6979 E Zygote  : v2,
08-23 18:35:03.715  6979  6979 I libpersona: KNOX_SDCARD checking this for 10064
,08-23 18:35:03.715  6979  6979 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:03.715  6979  6979 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-23 18:35:03.715  1014  1800 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6979 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 18:35:03.725  6979  6979 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 18:35:03.725  6979  6979 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 18:35:03.735  6953  6953 W VideoCapabilities: Unsupported mime video/wvc1
08-23 18:35:03.735  6953  6953 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-23 18:35:03.745  6979  6979 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 18:35:03.745  6979  6979 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:03.775  6953  6953 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-23 18:35:03.775  6953  6953 W VideoCapabilities: Unsupported mime video/wvc1
,08-23 18:35:03.775  6953  6953 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-23 18:35:03.775  6979  6979 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-23 18:35:03.775  6953  6953 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-23 18:35:03.775  6953  6953 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-23 18:35:03.785  6953  6953 W VideoCapabilities: Unsupported mime video/mp43
,08-23 18:35:03.785  6953  6953 W VideoCapabilities: Unsupported mime video/sorenson
,08-23 18:35:03.785  6953  6953 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-23 18:35:03.795  6979  6979 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 18:35:03.795  6979  6979 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-23 18:35:03.805  6953  6953 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-23 18:35:03.825  6953  6953 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 18:35:03.825  6953  6953 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 18:35:03.825  6953  6953 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 18:35:03.835  6979  6979 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 18:35:03.835  1014  1479 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
08-23 18:35:03.835  6953  6953 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 18:35:03.835  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:03.835  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:03.835  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:03.835  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:03.855  6994  6994 E Zygote  : MountEmulatedStorage(),
08-23 18:35:03.855  6994  6994 E Zygote  : v2,
08-23 18:35:03.855  6994  6994 I libpersona: KNOX_SDCARD checking this for 10065
08-23 18:35:03.855  6994  6994 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:03.855  6994  6994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 18:35:03.855  1014  1479 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6994 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 18:35:03.855  6953  6953 I vclib   : onServiceConnected
,08-23 18:35:03.855  6994  6994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 18:35:03.855  1014  1479 I ActivityManager: Killing 6507:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-23 18:35:03.855  1014  1319 I ActivityManager: Killing 6526:com.samsung.android.sm/1000 (adj 15): empty #21
,08-23 18:35:03.865  6994  6994 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 18:35:03.875  6994  6994 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:03.885  6994  6994 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:03.905  6994  6994 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 18:35:03.905  1014  1474 I ActivityManager: Killing 6546:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-23 18:35:03.915  1014  1800 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 18:35:03.915  1014  1800 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:03.915  1014  1800 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:03.915  1014  1800 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:03.915  1014  1800 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:03.915  1621  1621 I Hs20UtilService: Starting #9
,08-23 18:35:03.915  1621  1646 I Hs20UtilService: Message received 5007
,08-23 18:35:03.925  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 18:35:03.925  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 18:35:03.925  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 18:35:03.925  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 18:35:03.925  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 18:35:03.925  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 18:35:03.925  1303  2230 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 18:35:03.935  1014  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 18:35:03.935  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 18:35:03.935  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:03.935  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:03.935  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:03.935  1621  1621 I Hs20UtilService: Starting #10
,08-23 18:35:03.935  1621  1646 I Hs20UtilService: Message received 5011
,08-23 18:35:04.025  1014  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:04.025  1014  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.025  1014  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.025  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
08-23 18:35:04.025  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:04.025  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.035  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:04.035  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.035  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.035  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:04.035  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.035  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.035  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:04.045  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.045  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.045  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:04.045  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:04.045  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.045  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:04.055  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.055  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.055  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:04.055  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.055  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.055  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:04.055  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:04.065  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.065  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
08-23 18:35:04.065  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.065  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.065  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:04.065  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:04.065  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-23 18:35:04.075  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:04.075  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.075  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.075  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:04.075  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.075  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.085  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:04.085  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.085  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-23 18:35:04.085  1014  1042 D Tethering: interfaceRemoved wlan0
08-23 18:35:04.085  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-23 18:35:04.085  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:04.085  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.085  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 18:35:04.095   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 18:35:04.095  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 18:35:04.095  1014  1800 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-23 18:35:04.095  1014  1800 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 18:35:04.095  1014  1800 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:04.095  1014  1800 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:04.095  1014  1800 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 18:35:04.105  1303  1303 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:35:04.115  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 18:35:04.115  1167  1167 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:04.115  1167  1167 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-23 18:35:04.125  1014  1319 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-23 18:35:04.125  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.125  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.125  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.125  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.145  7010  7010 E Zygote  : MountEmulatedStorage()
,08-23 18:35:04.145  7010  7010 E Zygote  : v2
08-23 18:35:04.145  7010  7010 I libpersona: KNOX_SDCARD checking this for 1002
08-23 18:35:04.145  7010  7010 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:04.145  7010  7010 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 18:35:04.145  1014  1319 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7010 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-23 18:35:04.155  7010  7010 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 18:35:04.155  7010  7010 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 18:35:04.185  7010  7010 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:04.185  7010  7010 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:04.205  7010  7010 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-23 18:35:04.205  7010  7010 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 18:35:04.245  7010  7010 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-23 18:35:04.245  1014  1042 D Tethering: interfaceRemoved p2p0
,08-23 18:35:04.245  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding GattService
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding HeadsetService
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding A2dpService
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding HidService
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding HealthService
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding PanService
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding SapService
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding SapClientService
,08-23 18:35:04.285  7010  7010 D BtSettings.ProfileConfig: Adding HidDevService
,08-23 18:35:04.295  7010  7010 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-23 18:35:04.295  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-23 18:35:04.295  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:04.295  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 18:35:04.295  1014  1026 D SettingsProvider: selectionArgs: false
08-23 18:35:04.295  1014  1026 D SettingsProvider: selectionArgs: 1002
,08-23 18:35:04.295  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 18:35:04.295  1014  1026 D SettingsProvider: ret = -1
,08-23 18:35:04.295  1014  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-23 18:35:04.295  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:04.295  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 18:35:04.295  1014  1479 D SettingsProvider: selectionArgs: false
08-23 18:35:04.295  1014  1479 D SettingsProvider: selectionArgs: 1002
,08-23 18:35:04.295  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:04.295  1014  1479 D SettingsProvider: ret = -1
,08-23 18:35:04.305  1014  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-23 18:35:04.305  1014  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:04.305  1014  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 18:35:04.305  1014  1477 D SettingsProvider: selectionArgs: false
08-23 18:35:04.305  1014  1477 D SettingsProvider: selectionArgs: 1002
,08-23 18:35:04.305  1014  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:04.305  1014  1477 D SettingsProvider: ret = -1
,08-23 18:35:04.305  1014  1132 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-23 18:35:04.305  1014  1132 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:04.305  1014  1132 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:04.305  1014  1132 D SettingsProvider: selectionArgs: false
08-23 18:35:04.305  1014  1132 D SettingsProvider: selectionArgs: 1002
,08-23 18:35:04.305  1014  1132 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 18:35:04.305  1014  1132 D SettingsProvider: ret = -1,
08-23 18:35:04.305  1014  4756 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-23 18:35:04.305  1014  4756 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-23 18:35:04.305  1014  4756 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-23 18:35:04.305  1014  4756 D SettingsProvider: selectionArgs: false,
08-23 18:35:04.305  1014  4756 D SettingsProvider: selectionArgs: 1002
08-23 18:35:04.305  1014  4756 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:04.305  1014  4756 D SettingsProvider: ret = -1
,08-23 18:35:04.305  1014  1251 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-23 18:35:04.305  1014  1251 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:04.305  1014  1251 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 18:35:04.305  1014  1251 D SettingsProvider: selectionArgs: false
08-23 18:35:04.305  1014  1251 D SettingsProvider: selectionArgs: 1002
08-23 18:35:04.305  1014  1251 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:04.305  1014  1251 D SettingsProvider: ret = -1
08-23 18:35:04.305  1014  4757 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-23 18:35:04.305  1014  4757 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 18:35:04.305  1014  4757 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:04.305  1014  4757 D SettingsProvider: selectionArgs: false
08-23 18:35:04.305  1014  4757 D SettingsProvider: selectionArgs: 1002
08-23 18:35:04.305  1014  4757 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:04.305  1014  4757 D SettingsProvider: ret = -1
08-23 18:35:04.305  1014  1474 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-23 18:35:04.305  1014  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:04.305  1014  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:04.305  1014  1474 D SettingsProvider: selectionArgs: false
08-23 18:35:04.305  1014  1474 D SettingsProvider: selectionArgs: 1002
08-23 18:35:04.305  1014  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 18:35:04.305  1014  1474 D SettingsProvider: ret = -1
08-23 18:35:04.305  1014  1467 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-23 18:35:04.305  1014  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:04.305  1014  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:04.305  1014  1467 D SettingsProvider: selectionArgs: false
,08-23 18:35:04.305  1014  1467 D SettingsProvider: selectionArgs: 1002
08-23 18:35:04.305  1014  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:04.305  1014  1467 D SettingsProvider: ret = -1
08-23 18:35:04.305  1014  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:04.305  1014  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:04.305  1014  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:04.305  1014  1319 D SettingsProvider: selectionArgs: false
,08-23 18:35:04.305  1014  1319 D SettingsProvider: selectionArgs: 1002
08-23 18:35:04.305  1014  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:04.305  1014  1319 D SettingsProvider: ret = -1,
08-23 18:35:04.305  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-23 18:35:04.305  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 18:35:04.305  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:04.305  1014  1027 D SettingsProvider: selectionArgs: false
08-23 18:35:04.305  1014  1027 D SettingsProvider: selectionArgs: 1002
08-23 18:35:04.305  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:04.305  1014  1027 D SettingsProvider: ret = -1
08-23 18:35:04.305  1014  1800 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-23 18:35:04.305  1014  1800 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:04.305  1014  1800 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:04.305  1014  1800 D SettingsProvider: selectionArgs: false
08-23 18:35:04.305  1014  1800 D SettingsProvider: selectionArgs: 1002,
08-23 18:35:04.305  1014  1800 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:04.305  1014  1800 D SettingsProvider: ret = -1
,08-23 18:35:04.325  1014  1478 I ActivityManager: Killing 6578:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-23 18:35:04.325  2025  2025 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:04.325  1014  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 18:35:04.325  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-23 18:35:04.325  1014  1477 W ActivityManager: userId = 0, bbcId = -10000,
08-23 18:35:04.325  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:04.325  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:04.335  2025  7026 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-23 18:35:04.335  2025  2025 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 18:35:04.335  1014  1467 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 18:35:04.345  1014  1467 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:04.345  1014  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:04.345  1014  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:04.345  1014  1474 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 18:35:04.345  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:04.345  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:04.345  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:04.345  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:04.355  1621  1621 I Hs20UtilService: Starting #11
,08-23 18:35:04.355  1621  1646 I Hs20UtilService: Message received 5011
,08-23 18:35:04.495  1014  1132 I art     : Explicit concurrent mark sweep GC freed 59623(3MB) AllocSpace objects, 17(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.480ms total 150.090ms
,08-23 18:35:04.505  1014  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-23 18:35:04.505  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.505  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.505  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.505  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.525  7027  7027 E Zygote  : MountEmulatedStorage(),
08-23 18:35:04.535  7027  7027 E Zygote  : v2
08-23 18:35:04.535  7027  7027 I libpersona: KNOX_SDCARD checking this for 1000
08-23 18:35:04.535  7027  7027 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:04.535  7027  7027 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 18:35:04.535  7027  7027 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:04.535  7027  7027 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 18:35:04.535  1014  1477 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7027 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 18:35:04.545  1014  1132 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-23 18:35:04.555  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:04.555  1014  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:04.555  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:04.565  2025  7026 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-23 18:35:04.575  7027  7027 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:04.585  7027  7027 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:04.615  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-23 18:35:04.615  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-23 18:35:04.615  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
,08-23 18:35:04.615  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 18:35:04.625  1014  1478 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-23 18:35:04.625  1014  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.625  1014  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.625  1014  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.625  1014  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.645  7043  7043 E Zygote  : MountEmulatedStorage(),
08-23 18:35:04.645  7043  7043 I libpersona: KNOX_SDCARD checking this for 1000
08-23 18:35:04.645  7043  7043 E Zygote  : v2
08-23 18:35:04.645  7043  7043 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:04.645  7043  7043 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-23 18:35:04.645  1014  1478 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7043 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 18:35:04.655  7043  7043 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:04.655  7043  7043 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 18:35:04.665  7043  7043 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:04.665  7043  7043 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:04.685  7043  7043 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-23 18:35:04.685  7043  7043 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-23 18:35:04.685  7043  7043 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-23 18:35:04.695  7043  7043 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-23 18:35:04.695  7043  7043 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-23 18:35:04.695  7043  7043 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-23 18:35:04.695  7043  7043 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:04.705  1014  1026 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-23 18:35:04.705  1014  1026 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
08-23 18:35:04.705  7043  7058 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-23 18:35:04.705  1014  1026 I ActivityManager: Killing 6594:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-23 18:35:04.715  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-23 18:35:04.715  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.715  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.715  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.715  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.725  7060  7060 E Zygote  : MountEmulatedStorage(),
08-23 18:35:04.725  7060  7060 E Zygote  : v2
08-23 18:35:04.725  7060  7060 I libpersona: KNOX_SDCARD checking this for 10001
08-23 18:35:04.725  7060  7060 I libpersona: KNOX_SDCARD not a persona,
08-23 18:35:04.725  7060  7060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:04.725  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7060 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 18:35:04.735  7060  7060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 18:35:04.735  7060  7060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 18:35:04.735  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-23 18:35:04.735  1678  1678 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-23 18:35:04.735  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.735  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.735  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.735  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.755  7074  7074 E Zygote  : MountEmulatedStorage()
,08-23 18:35:04.755  7074  7074 E Zygote  : v2
08-23 18:35:04.755  7074  7074 I libpersona: KNOX_SDCARD checking this for 10121
08-23 18:35:04.755  7074  7074 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:04.755  7074  7074 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 18:35:04.755  7074  7074 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 18:35:04.755  7060  7060 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:04.755  7060  7060 D ActivityThread: Added TimaKeyStore provider,
08-23 18:35:04.765  1014  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7074 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-23 18:35:04.765  7074  7074 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 18:35:04.765  1014  1474 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
08-23 18:35:04.765  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.765  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.765  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.765  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.785   305   305 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 21.577ms
,08-23 18:35:04.795  7074  7074 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:04.795  7074  7074 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:04.795   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 16.196ms
,08-23 18:35:04.815   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 672us total 19.421ms
,08-23 18:35:04.835  7090  7090 E Zygote  : MountEmulatedStorage()
,08-23 18:35:04.835  7090  7090 E Zygote  : v2,
08-23 18:35:04.835  7090  7090 I libpersona: KNOX_SDCARD checking this for 10031
08-23 18:35:04.835  7090  7090 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:04.835  7090  7090 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:04.835  1014  1474 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7090 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-23 18:35:04.835  7090  7090 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:04.835  7090  7090 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 18:35:04.865  7090  7090 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:04.865  2470  2478 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
08-23 18:35:04.865  7090  7090 D ActivityThread: Added TimaKeyStore provider
08-23 18:35:04.865  1678  1678 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-23 18:35:04.865  1678  1678 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-23 18:35:04.865  1678  1678 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-23 18:35:04.865  1678  1678 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-23 18:35:04.875  1678  1678 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-23 18:35:04.875  7074  7074 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 18:35:04.875  7074  7074 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 18:35:04.885  7074  7074 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 18:35:04.885  1678  1678 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-23 18:35:04.885  1014  1251 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-23 18:35:04.885  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.885  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.885  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.885  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.895  7074  7074 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
,08-23 18:35:04.905  7105  7105 E Zygote  : MountEmulatedStorage(),
08-23 18:35:04.905  7105  7105 E Zygote  : v2,
08-23 18:35:04.905  7105  7105 I libpersona: KNOX_SDCARD checking this for 10077
,08-23 18:35:04.905  7105  7105 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 18:35:04.905  7105  7105 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:04.905  7074  7074 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-23 18:35:04.905  1014  1251 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7105 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 18:35:04.905  7105  7105 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 18:35:04.915  7105  7105 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-23 18:35:04.915  7074  7074 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-23 18:35:04.915  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-23 18:35:04.925  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.925  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.925  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.925  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.925  7090  7090 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-23 18:35:04.935  7118  7118 E Zygote  : MountEmulatedStorage()
08-23 18:35:04.935  7118  7118 I libpersona: KNOX_SDCARD checking this for 10141
08-23 18:35:04.935  7118  7118 E Zygote  : v2
08-23 18:35:04.935  7118  7118 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:04.935  7118  7118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:04.945  7118  7118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 18:35:04.945  1014  1026 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7118 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-23 18:35:04.945  1014  1026 I ActivityManager: Killing 6608:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-23 18:35:04.945  7118  7118 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 18:35:04.945  1014  1026 I ActivityManager: Killing 6631:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-23 18:35:04.955  7105  7105 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:04.955  7105  7105 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:04.965  1014  1478 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-23 18:35:04.965  1014  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.965  1014  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.965  1014  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:04.965  1014  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:04.975  2757  7132 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-23 18:35:04.975  2757  7132 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
08-23 18:35:04.975  2757  7132 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-23 18:35:04.985  2757  7132 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0,
,08-23 18:35:04.985  2757  7132 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-23 18:35:04.985  7137  7137 I libpersona: KNOX_SDCARD checking this for 10032
08-23 18:35:04.985  7137  7137 E Zygote  : MountEmulatedStorage()
08-23 18:35:04.985  7137  7137 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:04.985  7137  7137 E Zygote  : v2
08-23 18:35:04.985  7137  7137 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 18:35:04.985  1014  1478 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7137 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 18:35:04.985  7137  7137 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:04.995  7137  7137 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-23 18:35:04.995  7118  7118 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 18:35:04.995  7118  7118 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:05.005  7118  7118 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-23 18:35:05.005  7118  7118 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 18:35:05.005  7118  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 18:35:05.005  7118  7118 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-23 18:35:05.015  1014  1467 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-23 18:35:05.025  1014  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.025  1014  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.025  1014  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.025  1014  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:05.025  7137  7137 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:05.025  7137  7137 D ActivityThread: Added TimaKeyStore provider,
,08-23 18:35:05.035  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-23 18:35:05.045  1014  1467 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7153 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 18:35:05.045  7153  7153 E Zygote  : MountEmulatedStorage()
08-23 18:35:05.045  7153  7153 E Zygote  : v2
08-23 18:35:05.045  7153  7153 I libpersona: KNOX_SDCARD checking this for 1000
08-23 18:35:05.045  7153  7153 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:05.045  1014  1467 I ActivityManager: Killing 6073:com.android.mms/u0a41 (adj 15): empty #21
08-23 18:35:05.045  7153  7153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:05.045  7153  7153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 18:35:05.045  7153  7153 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 18:35:05.065  7153  7153 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:05.065  7153  7153 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:05.075  1014  1477 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 18:35:05.085   287   287 E SMD     : DCD OFF,
,08-23 18:35:05.095   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 18:35:05.095  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 18:35:05.105  7153  7153 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-23 18:35:05.115  7137  7169 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-23 18:35:05.115  7137  7169 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-23 18:35:05.115  1014  4757 D CountryDetector: No listener is left
,08-23 18:35:05.125  7137  7169 D SPPClientService: PushLog.txt file is not deleted.
,08-23 18:35:05.125  7137  7169 D SPPClientService: PushLog.txt file is not deleted.
08-23 18:35:05.125  7137  7169 D SPPClientService: ============PushLog. stop!
,08-23 18:35:05.135  1014  1477 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 18:35:05.145  7137  7137 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-23 18:35:05.145  1014  1319 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 18:35:05.145  1014  1251 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
08-23 18:35:05.145  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.145  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.145  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.145  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:05.165  7176  7176 E Zygote  : MountEmulatedStorage(),
08-23 18:35:05.175  7176  7176 E Zygote  : v2
08-23 18:35:05.175  7176  7176 I libpersona: KNOX_SDCARD checking this for 10036
08-23 18:35:05.175  7176  7176 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:05.175  7176  7176 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 18:35:05.175  1014  1251 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7176 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 18:35:05.175  1014  1251 I ActivityManager: Killing 6559:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-23 18:35:05.175  7176  7176 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:05.175  7176  7176 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-23 18:35:05.205  1014  1800 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-23 18:35:05.205  1014  1800 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-23 18:35:05.205  1014  1800 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:05.205  1014  1800 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,08-23 18:35:05.205  1014  1800 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-23 18:35:05.215  7176  7176 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:05.215  7176  7176 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:05.235  7137  7190 E SPPClientService: [[SystemStateMonitorService]] No Active Internet,
,08-23 18:35:05.265  7176  7176 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@24727537
,08-23 18:35:05.265  1014  1251 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-23 18:35:05.265  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.265  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.265  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.265  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:05.275  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId,
08-23 18:35:05.275  7176  7176 I SA      : [SSP] onCreated
,08-23 18:35:05.285  7195  7195 E Zygote  : MountEmulatedStorage()
08-23 18:35:05.285  7195  7195 E Zygote  : v2
08-23 18:35:05.285  7195  7195 I libpersona: KNOX_SDCARD checking this for 10068
08-23 18:35:05.285  7195  7195 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:05.285  7195  7195 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:05.285  1014  1251 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7195 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-23 18:35:05.285  7195  7195 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:05.295  7195  7195 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-23 18:35:05.295  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 18:35:05.305  7153  7153 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-23 18:35:05.315  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 18:35:05.315  7153  7153 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-23 18:35:05.315  7153  7153 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:05.315  7153  7153 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-23 18:35:05.315  7153  7153 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-23 18:35:05.315  7153  7153 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
08-23 18:35:05.325  7176  7176 I SA      : [TPM] There is no property file
,08-23 18:35:05.325  1014  1474 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-23 18:35:05.325  7195  7195 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:05.325  7195  7195 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:05.325  1014  1800 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 18:35:05.325  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:05.325  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:05.325  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.325  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:05.335  7176  7176 I SA      : [SCU] isHaveSA() - false
08-23 18:35:05.345  7215  7215 I libpersona: KNOX_SDCARD checking this for 10008
08-23 18:35:05.335  7176  7176 I SA      : [TPM] getModelProperty : null
08-23 18:35:05.345  7215  7215 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:05.335  7176  7176 I SA      : [TPM] getCSCProperty : null
08-23 18:35:05.345  1014  1474 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7215 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 18:35:05.335  7176  7176 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-23 18:35:05.335  7176  7176 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-23 18:35:05.345  1014  1474 I ActivityManager: Killing 6654:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-23 18:35:05.335  7176  7176 I SA      : [DM] TFT FEATURE: false
08-23 18:35:05.345  7215  7215 E Zygote  : MountEmulatedStorage()
08-23 18:35:05.345  7215  7215 E Zygote  : v2
08-23 18:35:05.345  7215  7215 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 18:35:05.345  7215  7215 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 18:35:05.345  7215  7215 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-23 18:35:05.355  1014  1474 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-23 18:35:05.355  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.355  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.355  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.355  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:05.365  7176  7176 I SA      : [DM] init START
,08-23 18:35:05.375  7176  7176 I SA      : [DM] This device is not a Vodafone
,08-23 18:35:05.375  7215  7215 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 18:35:05.375  7230  7230 I libpersona: KNOX_SDCARD checking this for 10009
08-23 18:35:05.375  7215  7215 D ActivityThread: Added TimaKeyStore provider
08-23 18:35:05.375  7230  7230 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:05.375  7230  7230 E Zygote  : MountEmulatedStorage()
08-23 18:35:05.375  7230  7230 E Zygote  : v2
08-23 18:35:05.375  7230  7230 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:05.385  1014  1474 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7230 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-23 18:35:05.385  7230  7230 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:05.385  1014  1474 I ActivityManager: Killing 6487:com.android.calendar/u0a131 (adj 15): empty #21,
08-23 18:35:05.385  7230  7230 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-23 18:35:05.385  1014  1474 I ActivityManager: Killing 6682:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #22
,08-23 18:35:05.395  7176  7176 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-23 18:35:05.405  7195  7195 D BadgeProvider: onCreate
,08-23 18:35:05.405  7176  7176 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-23 18:35:05.405  7195  7195 D BadgeProvider: DatabaseHelper
,08-23 18:35:05.405  7176  7176 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-23 18:35:05.405  7230  7230 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 18:35:05.405  7176  7176 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-23 18:35:05.405  7230  7230 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:05.415  7176  7176 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-23 18:35:05.415  7176  7176 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-23 18:35:05.415  7176  7176 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-23 18:35:05.415  7176  7176 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 18:35:05.415  7176  7176 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-23 18:35:05.415  7176  7176 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-23 18:35:05.415  7176  7176 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-23 18:35:05.415  7176  7176 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-23 18:35:05.425  1014  1477 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-23 18:35:05.425  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-23 18:35:05.425  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:05.425  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:05.425  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-23 18:35:05.425  7195  7212 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-23 18:35:05.425  7176  7176 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-23 18:35:05.435  1014  1474 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-23 18:35:05.435  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.435  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.435  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:05.435  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:05.445  7176  7176 I SA      : [SCU] isHaveSA() - false
08-23 18:35:05.445  7176  7176 I SA      : support phone number id : false
08-23 18:35:05.445  7176  7176 I SA      : [DM] Supports Ref Jpn : true
,08-23 18:35:05.445  7176  7176 I SA      : [DM] init END
08-23 18:35:05.445  7176  7176 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
08-23 18:35:05.445  7247  7247 E Zygote  : MountEmulatedStorage(),
08-23 18:35:05.445  7247  7247 E Zygote  : v2
08-23 18:35:05.445  7247  7247 I libpersona: KNOX_SDCARD checking this for 10110
08-23 18:35:05.445  7247  7247 I libpersona: KNOX_SDCARD not a persona,
,08-23 18:35:05.445  7176  7176 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
08-23 18:35:05.455  1014  1474 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7247 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 18:35:05.455  7247  7247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:05.455  1014  1477 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-23 18:35:05.455  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-23 18:35:05.455  7247  7247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:05.455  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:05.455  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 18:35:05.455  7247  7247 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-23 18:35:05.455  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-23 18:35:05.465  7176  7176 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-23 18:35:05.465  6953  7245 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-23 18:35:05.485  7176  7176 I SA      : [SLFUCHKMGR] constructor called
,08-23 18:35:05.485  7195  7212 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-23 18:35:05.485  7195  7212 D BadgeProvider: sendNotify, [notify] : null
08-23 18:35:05.485  7195  7212 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-23 18:35:05.485  7195  7212 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-23 18:35:05.485  7195  7212 D BadgeProvider: update, [UpdateCount] : 1
,08-23 18:35:05.485  1480  1480 D Launcher.Model: reloadBadges entered.
,08-23 18:35:05.485  7247  7247 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:05.495  7247  7247 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:05.505  7176  7176 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-23 18:35:05.505  7176  7176 I SA      : [OR] == isSIMCardReady false ==
,08-23 18:35:05.515  7176  7176 I SA      : [SCU] == networkStateCheck == false
08-23 18:35:05.515  7176  7176 I SA      : [OR] onReceive END
,08-23 18:35:05.515  1014  1474 I ActivityManager: Killing 6669:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-23 18:35:05.515  1222  1222 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:05.525  1014  1800 I ActivityManager: Killing 6013:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-23 18:35:05.535  2817  2817 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 18:35:05 GMT+02:00 2016
,08-23 18:35:05.535  1014  1026 I ActivityManager: Killing 5827:com.android.vending/u0a26 (adj 15): empty #21
,08-23 18:35:05.535  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-23 18:35:05.535  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-23 18:35:05.535  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:05.535  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:05.535  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 18:35:05.545  2817  2817 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-23 18:35:05.545  2817  2817 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-23 18:35:05.555  2817  2817 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 18:35:05.555  1014  1478 I ActivityManager: Killing 6731:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-23 18:35:05.555  2817  2817 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 18:35:05.555  2817  7265 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-23 18:35:05.555  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 18:35:05.555  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-23 18:35:05.565  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:05.565  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:05.565  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:05.565  2817  7265 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-23 18:35:05.575  2817  7265 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-23 18:35:05.575  2817  7265 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-23 18:35:05.585  2817  2817 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-23 18:35:05.585  4776  7266 I iu.SyncManager: SYNC; picasa accounts
,08-23 18:35:05.595  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-23 18:35:05.595  1014  1319 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-23 18:35:05.595  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-23 18:35:05.595  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-23 18:35:05.605  4776  4776 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-23 18:35:05.615  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-23 18:35:05.615  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 18:35:05.615  1014  1027 D SecContentProvider2: mCursor = null
,08-23 18:35:05.615  1014  1027 D WifiService: setWifiEnabled: true pid=6794, uid=10171
,08-23 18:35:05.615  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-23 18:35:05.615  1014  1027 W WifiService: Failed getting userId using ActivityManagerNative
08-23 18:35:05.615  1014  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 18:35:05.615  1014  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 18:35:05.615  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-23 18:35:05.615  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-23 18:35:05.615  1014  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-23 18:35:05.615  1014  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-23 18:35:05.615  1014  1027 D SettingsProvider: name = wifi_on
,08-23 18:35:05.635  1014  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-23 18:35:05.735  1014  1251 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 18:35:05.875  7247  7247 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-23 18:35:05.875  7247  7247 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 18:35:05.875  7247  7247 I GAv4    :   adb logcat -s GAv4
,08-23 18:35:05.875   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-23 18:35:05.875   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 18:35:05.875  7247  7271 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-23 18:35:05.885   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-23 18:35:05.885   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 18:35:05.885  7247  7271 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-23 18:35:05.895   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-23 18:35:05.895   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 18:35:05.895  7247  7279 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-23 18:35:05.895   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-23 18:35:05.895   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 18:35:05.895  7247  7279 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-23 18:35:05.905  7247  7247 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 18:35:05.905  1014  1026 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 18:35:05.915  7247  7247 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 18:35:05.925  7247  7280 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 18:35:05.995  1014  1042 D Tethering: interfaceAdded wlan0
,08-23 18:35:06.005  1014  1127 E Tethering: No numeric data
,08-23 18:35:06.005  1014  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 18:35:06.005  1014  1127 D Tethering: clearTetheredNotification()
,08-23 18:35:06.005  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:06.005  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-23 18:35:06.005  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 18:35:06.005  1014  1127 D Tethering: InitialState.processMessage what=4
,08-23 18:35:06.015  1014  1127 E Tethering: No numeric data
,08-23 18:35:06.015  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
08-23 18:35:06.015  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:06.015  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-23 18:35:06.015  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 18:35:06.015  1167  1167 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 18:35:06.015  1167  1167 D HotspotTile: updateTetherState():false, false
,08-23 18:35:06.015  1014  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 18:35:06.015  1014  1127 D Tethering: clearTetheredNotification()
,08-23 18:35:06.025  1167  1167 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 18:35:06.025  1167  1167 D HotspotTile: updateTetherState():false, false
,08-23 18:35:06.025  1014  1042 D Tethering: interfaceAdded p2p0
08-23 18:35:06.025  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-23 18:35:06.025  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 18:35:06.025  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-23 18:35:06.025  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 18:35:06.025  1014  1121 V NetworkStats: performPollLocked() took 14ms
,08-23 18:35:06.025  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:06.025   276   972 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-23 18:35:06.025   276   972 D SoftapController: Softap fwReload - Ok
,08-23 18:35:06.025  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:06.035  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:06.035   276   972 D CommandListener: Setting iface cfg
08-23 18:35:06.035   276   972 D CommandListener: Trying to bring down wlan0
,08-23 18:35:06.035  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:06.035  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:06.035   276   972 D CommandListener: Clearing all IP addresses on wlan0
,08-23 18:35:06.035  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 18:35:06.035  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 18:35:06.035  1014  1121 V NetworkStats: performPollLocked() took 6ms
08-23 18:35:06.035  1014  1124 E WifiHW  : supplicant_name : p2p_supplicant
,08-23 18:35:06.035  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:06.035  1014  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-23 18:35:06.045  1014  1124 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
,08-23 18:35:06.045  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-23 18:35:06.045  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 18:35:06.045  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:06.045  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:06.045  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:06.045  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:06.045  1167  1167 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 18:35:06.045  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 18:35:06.045  1167  1167 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-23 18:35:06.045  1167  1167 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-23 18:35:06.055  1167  1167 D HotspotTile: onReceive : 2, 0,
,08-23 18:35:06.055  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-23 18:35:06.055  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-23 18:35:06.055  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:06.065  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:06.065  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:06.095   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 18:35:06.105  7284  7284 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-23 18:35:06.105  7284  7284 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-23 18:35:06.105  7284  7284 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-23 18:35:06.155  7284  7284 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-23 18:35:06.155   348   348 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7284
08-23 18:35:06.155   348   348 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,08-23 18:35:06.155  7284  7284 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-23 18:35:06.155  7284  7284 I wpa_supplicant: ssSupport state is = 1
08-23 18:35:06.155  7284  7284 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-23 18:35:06.155  7284  7284 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-23 18:35:06.155   348   348 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7284
08-23 18:35:06.155   348   348 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-23 18:35:06.195  1014  4757 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 18:35:06.205  1014  4757 W ActivityManager: userId = 0, bbcId = -10000,
08-23 18:35:06.205  1014  4757 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:06.205  1014  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-23 18:35:06.255  1014  1478 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 18:35:06.255  1014  1478 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 18:35:06.255  1014  1478 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 18:35:06.255  1014  1478 D BatteryService: stay LED for fully charged
08-23 18:35:06.255  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 18:35:06.265  1014  1014 I MotionRecognitionService: Plugged
08-23 18:35:06.265  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 18:35:06.265  1167  1167 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 18:35:06.265  1167  1167 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 18:35:06.265  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 18:35:06.265  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 18:35:06.265  7247  7247 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-23 18:35:06.295  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 18:35:06.295  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 18:35:06.295  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 18:35:06.295  7247  7247 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 6324-6327),
08-23 18:35:06.295  7247  7247 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-23 18:35:06.305  7247  7247 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {39daecce}
,08-23 18:35:06.305  7247  7247 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-23 18:35:06.305  7247  7247 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 18:35:06.325  7247  7247 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-23 18:35:06.325  7247  7247 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 18:35:06.335  7247  7247 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-23 18:35:06.345  7247  7247 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 18:35:06.345  7247  7247 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 18:35:06.345  7247  7247 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 18:35:06.345  7247  7247 I Adreno-EGL: Local Branch: 
08-23 18:35:06.345  7247  7247 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 18:35:06.345  7247  7247 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 18:35:06.345  7247  7247 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 18:35:06.375   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-23 18:35:06.375  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-23 18:35:06.415  7247  7247 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 18:35:06.415  7247  7312 W cr.media: Requires BLUETOOTH permission
,08-23 18:35:06.425  7247  7247 I NSApplication: Starting up...
,08-23 18:35:06.425  1014  1026 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 18:35:06.425  7284  7284 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-23 18:35:06.425  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-23 18:35:06.425  1014  1474 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 18:35:06.435  1014  4757 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-23 18:35:06.435  1014  4757 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:06.435  1014  4757 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:06.435  1014  4757 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:06.435  1014  4757 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:06.435  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-23 18:35:06.435   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7284
08-23 18:35:06.435   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-23 18:35:06.435  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-23 18:35:06.435  7284  7284 I wpa_supplicant: ssSupport state is = 1
08-23 18:35:06.435  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-23 18:35:06.445  7284  7284 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-23 18:35:06.445  7284  7284 E wpa_supplicant: SIM READ ERROR
08-23 18:35:06.445  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 18:35:06.445  7284  7284 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 18:35:06.445  7284  7284 E wpa_supplicant: SIM READ ERROR
,08-23 18:35:06.445  7284  7284 I wpa_supplicant: Blacklist: Clear (all) 
08-23 18:35:06.445  7284  7284 I wpa_supplicant: wpa_default_ap_write_once
08-23 18:35:06.445  7284  7284 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-23 18:35:06.445  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 18:35:06.445  7284  7284 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-23 18:35:06.445  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-23 18:35:06.445  7284  7284 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-23 18:35:06.445  7284  7284 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-23 18:35:06.445  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:06.445  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-23 18:35:06.455  1014  4757 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7318 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-23 18:35:06.455  7318  7318 E Zygote  : MountEmulatedStorage()
08-23 18:35:06.455  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:06.455  7318  7318 E Zygote  : v2
,08-23 18:35:06.455  7318  7318 I libpersona: KNOX_SDCARD checking this for 10117
08-23 18:35:06.455  7318  7318 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:06.455  1014  4757 I ActivityManager: Killing 6979:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-23 18:35:06.455  7318  7318 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:06.455  7318  7318 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:06.455  7318  7318 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 18:35:06.475   305   305 I art     : Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 633us total 28.623ms
,08-23 18:35:06.485  7318  7318 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:06.485  7318  7318 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:06.495   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 645us total 20.142ms
,08-23 18:35:06.505  7318  7318 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 18:35:06.515   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 17.362ms
,08-23 18:35:06.525  7284  7284 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-23 18:35:06.635  7284  7284 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-23 18:35:06.645  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-23 18:35:06.655  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-23 18:35:06.655   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7284
08-23 18:35:06.655   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-23 18:35:06.655  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-23 18:35:06.655  7284  7284 I wpa_supplicant: ssSupport state is = 1
,08-23 18:35:06.665  7284  7284 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-23 18:35:06.665  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-23 18:35:06.675  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-23 18:35:06.675   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7284
08-23 18:35:06.675   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-23 18:35:06.675  7284  7284 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-23 18:35:06.675  7284  7284 I wpa_supplicant: ssSupport state is = 1
08-23 18:35:06.675  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 18:35:06.675  7284  7284 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-23 18:35:06.675  7284  7284 E wpa_supplicant: SIM READ ERROR
08-23 18:35:06.675  7284  7284 I wpa_supplicant: wpa_default_ap_write_once
08-23 18:35:06.675  7284  7284 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-23 18:35:06.675  7284  7284 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-23 18:35:06.675  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 18:35:06.675  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 18:35:06.675  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-23 18:35:06.675  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 18:35:06.675  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 18:35:06.675  1014  1042 D Tethering: interfaceStatusChanged p2p0, false,
,08-23 18:35:06.765  7284  7284 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-23 18:35:06.765  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-23 18:35:06.825  7284  7284 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-23 18:35:06.825  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-23 18:35:06.825  7284  7284 I wpa_supplicant: Skip scan - bUseNetwork false
,08-23 18:35:06.845  1014  1467 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-23 18:35:06.845  1014  1467 I ActivityManager: Killing 6994:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-23 18:35:06.855  1014  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 18:35:06.855  1014  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:06.855  1014  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:06.855  1014  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:06.855  1014  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:06.855  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 18:35:06.855  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 18:35:06.855  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
08-23 18:35:06.855  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 18:35:06.855  1621  1621 I Hs20UtilService: Starting #12
,08-23 18:35:06.865  1621  1646 I Hs20UtilService: Message received 5011
,08-23 18:35:07.005  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-23 18:35:07.005  1014  1042 D Tethering: interfaceStatusChanged p2p0, false,
08-23 18:35:07.005  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 18:35:07.045  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-23 18:35:07.045  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-23 18:35:07.045  7284  7284 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-23 18:35:07.045  7284  7284 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 18:35:07.045  7284  7284 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 18:35:07.045  7284  7284 E wpa_supplicant: SIM READ ERROR
08-23 18:35:07.045  7284  7284 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 18:35:07.065  7284  7284 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-23 18:35:07.085  7284  7284 I wpa_supplicant: Skip scan - bUseNetwork false
,08-23 18:35:07.085  1014  1124 D WifiConfigStore: Loading config and enabling all networks 
08-23 18:35:07.085  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:07.085  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 18:35:07.085  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:07.085  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:07.085  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:07.085  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:07.085  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-23 18:35:07.095  1167  1167 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 18:35:07.085  1167  1167 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-23 18:35:07.085  1167  1167 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-23 18:35:07.095  1167  1167 D HotspotTile: onReceive : 3, 0
,08-23 18:35:07.095  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-23 18:35:07.105   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 18:35:07.105  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:07.105  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:07.105  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:07.105  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:07.105  1014  1124 E WifiConfigStore: Not a HS20
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:07.105  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:07.105  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:07.105  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:07.105  1014  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-23 18:35:07.105  1014  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-23 18:35:07.105  1014  1132 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 18:35:07.115  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 18:35:07.115  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:07.115  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:07.115  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:07.115  1621  1621 I Hs20UtilService: Starting #13
,08-23 18:35:07.115  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-23 18:35:07.115  7284  7284 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-23 18:35:07.115  7284  7284 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-23 18:35:07.115  7284  7284 I wpa_supplicant: reset timer : RESET_TIMER 0,
08-23 18:35:07.115  7284  7284 I wpa_supplicant: P2P: Current p2p state = IDLE
08-23 18:35:07.115  7284  7284 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-23 18:35:07.115  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-23 18:35:07.115  7284  7284 I wpa_supplicant: First Scan Start
08-23 18:35:07.115  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 18:35:07.115  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 18:35:07.115  7284  7284 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-23 18:35:07.115  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
08-23 18:35:07.115  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-23 18:35:07.125  1621  1646 I Hs20UtilService: Message received 5011
,08-23 18:35:07.125  1014  1124 D WifiNative-wlan0: Setting external_sim to 1
08-23 18:35:07.125  1014  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 18:35:07.125  1014  1124 I WifiNative-HAL: startHal
08-23 18:35:07.125  1014  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9cf9f88c
08-23 18:35:07.125  6953  6953 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:35:07.125  1014  1124 I WifiNative-HAL: Could not start hal
,08-23 18:35:07.125  1014  1124 E WifiNative-wlan0: do suspend true
,08-23 18:35:07.125  1014  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-23 18:35:07.125  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-23 18:35:07.135  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
08-23 18:35:07.135  1014  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:35:07.135  1014  1147 I WifiNative-HAL: startHal
08-23 18:35:07.135  1014  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9da359bc
08-23 18:35:07.135  1014  1147 I WifiNative-HAL: Could not start hal
08-23 18:35:07.135  1014  1147 E WifiScanningService: could not start HAL
08-23 18:35:07.135   276   972 D CommandListener: Setting iface cfg
08-23 18:35:07.135   276   972 D CommandListener: Trying to bring up p2p0
,08-23 18:35:07.135  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-23 18:35:07.135  1014  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-23 18:35:07.135  1014  1148 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:35:07.135  1014  1123 D WifiP2pService: P2pEnablingState
08-23 18:35:07.135  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-23 18:35:07.135  1014  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
08-23 18:35:07.135  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-23 18:35:07.135  1014  1123 D WifiP2pService: P2p socket connection successful
08-23 18:35:07.135  1014  1124 E WifiNative-wlan0: invaild command id : 215
08-23 18:35:07.135  1014  1123 D WifiP2pService: P2pEnabledState
08-23 18:35:07.135  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-23 18:35:07.135  1014  1126 E ConnectivityService: updateNetworkInfo()
,08-23 18:35:07.135  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-23 18:35:07.135  7284  7284 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-23 18:35:07.135  7284  7284 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-23 18:35:07.135  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
08-23 18:35:07.135  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-23 18:35:07.135  1014  1045 D WifiDisplayController: disconnect
08-23 18:35:07.135  1014  1045 D WifiDisplayController: updateConnection
08-23 18:35:07.145  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 18:35:07.145  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 18:35:07.145  7284  7284 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-23 18:35:07.145  1014  1124 E WifiStateMachine: Failed to set frequency band 0
,08-23 18:35:07.145  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-23 18:35:07.145  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-23 18:35:07.145  1014  1124 E WifiNative-wlan0: invaild command id : 215
08-23 18:35:07.145  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:07.145  1014  1124 D SecContentProvider2: mCursor = null
08-23 18:35:07.145  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress
08-23 18:35:07.145  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-23 18:35:07.145  1014  1123 D WifiP2pService: DeviceAddress: 0a:76:28
08-23 18:35:07.145  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:07.145  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:07.185  1014  1123 D WifiP2pService: sending p2p persistent groups changed broadcast,
08-23 18:35:07.185  1014  1123 D WifiP2pService: InactiveState
08-23 18:35:07.185  1014  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-23 18:35:07.185  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 18:35:07.185  7284  7284 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-23 18:35:07.185  1014  1123 D WifiP2pService: InactiveState{ what=143376 },
08-23 18:35:07.185  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 18:35:07.205  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 18:35:07.205  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-23 18:35:07.205  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 18:35:07.205  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null,
08-23 18:35:07.215  1167  1167 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-23 18:35:07.215  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  secondary type: null
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  wps: 0
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  grpcapab: 0
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  devcapab: 0
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  status: 3
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  wfdInfo: null
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  groupownerAddress: null
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  GOdeviceName: null
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  interfaceAddress: 
08-23 18:35:07.215  1014  1045 D WifiDisplayController:  SConnectInfo : null
,08-23 18:35:07.215  1014  1026 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 18:35:07.215  1167  1167 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-23 18:35:07.215  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 18:35:07.215  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 18:35:07.215  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 18:35:07.215  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 18:35:07.215  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 18:35:07.215  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 18:35:07.215  1303  2230 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 18:35:07.225  1014  4756 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-23 18:35:07.225  1014  4756 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:07.225  1014  4756 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:07.225  1014  4756 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:07.225  1014  4756 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:07.235  7348  7348 E Zygote  : MountEmulatedStorage(),
08-23 18:35:07.235  7348  7348 E Zygote  : v2
08-23 18:35:07.235  7348  7348 I libpersona: KNOX_SDCARD checking this for 10064
,08-23 18:35:07.235  7348  7348 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:07.235  1014  4756 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7348 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 18:35:07.235  7348  7348 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:07.235  7348  7348 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:07.245  7348  7348 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 18:35:07.255  7348  7348 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:07.265  7348  7348 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:07.275  7348  7348 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-23 18:35:07.285  7348  7348 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 18:35:07.285  7348  7348 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-23 18:35:07.315  7348  7348 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 18:35:07.315  1014  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-23 18:35:07.315  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:07.315  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:07.315  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:07.315  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:07.335  7363  7363 E Zygote  : MountEmulatedStorage(),
,08-23 18:35:07.335  7363  7363 E Zygote  : v2
08-23 18:35:07.335  7363  7363 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:07.335  1014  1477 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7363 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 18:35:07.335  7363  7363 I libpersona: KNOX_SDCARD checking this for 10065
08-23 18:35:07.335  7363  7363 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:07.335  1014  1477 I ActivityManager: Killing 6876:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-23 18:35:07.335  7363  7363 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:07.335  7363  7363 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 18:35:07.355  7363  7363 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:07.355  7363  7363 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:07.375  7363  7363 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 18:35:07.385  1014  1478 I ActivityManager: Killing 7010:com.android.bluetooth/1002 (adj 15): empty #21
,08-23 18:35:08.085   287   287 E SMD     : DCD OFF
,08-23 18:35:08.105   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 18:35:08.335  7284  7284 I wpa_supplicant: nl80211: Received scan results (31 BSSes),
08-23 18:35:08.335  7284  7284 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-23 18:35:08.335  7284  7284 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-23 18:35:08.335  7284  7284 I wpa_supplicant: Trying to associate with  'G700'
08-23 18:35:08.335  7284  7284 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-23 18:35:08.335  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-23 18:35:08.345  1014  7344 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-23 18:35:08.355  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:08.355  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:08.455  7284  7284 E wpa_supplicant: Cmd 35605 not handled
,08-23 18:35:08.455  7284  7284 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-23 18:35:08.455  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:08.455  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:08.455  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-23 18:35:08.455  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:08.455  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:08.455  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-23 18:35:08.455  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-23 18:35:08.465  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-23 18:35:08.455  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-23 18:35:08.455  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-23 18:35:08.455  1014  1127 E Tethering: No numeric data,
08-23 18:35:08.455  1014  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-23 18:35:08.455  1014  1127 D Tethering: clearTetheredNotification()
08-23 18:35:08.465  1167  1167 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 18:35:08.465  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-23 18:35:08.465  1167  1167 D HotspotTile: updateTetherState():false, false
08-23 18:35:08.465  7284  7284 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-23 18:35:08.465  1014  1121 V NetworkStats: performPollLocked() took 4ms
08-23 18:35:08.465  7284  7284 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-23 18:35:08.465  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-23 18:35:08.465  7284  7284 I wpa_supplicant: Associated with F4.99.3E
08-23 18:35:08.465  7284  7284 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-23 18:35:08.465  7284  7284 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-23 18:35:08.465  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-23 18:35:08.465  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 18:35:08.465  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 18:35:08.465  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:08.465  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:08.465  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:08.465  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:08.465  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:08.465  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-23 18:35:08.465  1014  1124 D SecContentProvider2: mCursor = null
08-23 18:35:08.465  7284  7284 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-23 18:35:08.475  7284  7284 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-23 18:35:08.475  7284  7284 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-23 18:35:08.475  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-23 18:35:08.475  7284  7284 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 18:35:08.475  7284  7284 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-23 18:35:08.475  7284  7284 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-23 18:35:08.475  7284  7284 I wpa_supplicant: Blacklist: Clear (temp) 
08-23 18:35:08.475  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-23 18:35:08.475  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-23 18:35:08.475  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-23 18:35:08.475  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-23 18:35:08.475  1014  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-23 18:35:08.475  1014  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-23 18:35:08.475  1014  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-23 18:35:08.475  1014  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-23 18:35:08.475  1014  1126 E ConnectivityService: updateNetworkInfo()
08-23 18:35:08.475  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-23 18:35:08.475  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:08.475  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:08.485  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.485  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:08.485  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.485  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:08.485  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 18:35:08.485  1014  1467 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 18:35:08.485  1014  1467 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:08.485  1014  1467 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:08.485  1014  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:08.485  1014  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:08.485  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 18:35:08.485  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 18:35:08.495  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 18:35:08.495  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 18:35:08.495  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 18:35:08.495  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 18:35:08.495  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 18:35:08.495  1303  2230 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-23 18:35:08.495  1621  1621 I Hs20UtilService: Starting #14
,08-23 18:35:08.495  1621  1646 I Hs20UtilService: Message received 5007
,08-23 18:35:08.505   276   972 D CommandListener: Setting iface cfg,
,08-23 18:35:08.505  1014  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,08-23 18:35:08.505  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:08.505  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:08.515  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 18:35:08.515  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 18:35:08.515  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:08.515  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:08.515  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.515  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:08.525  1014  1124 E WifiNative-wlan0: do suspend false
,08-23 18:35:08.525  1014  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-23 18:35:08.525  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:08.525  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:08.525  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 18:35:08.635  1014  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-23 18:35:08.635  1014  1026 D WifiService: setWifiEnabled: false pid=6794, uid=10171
08-23 18:35:08.635  1014  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 18:35:08.635  1014  1026 D SecContentProvider2: mCursor = null
08-23 18:35:08.635  1014  1026 D SettingsProvider: name = wifi_on
,08-23 18:35:08.645  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 18:35:08.655  1014  1124 E WifiNative-wlan0: do suspend true,
,08-23 18:35:08.685  1014  1123 D WifiP2pService: InactiveState{ what=143375 },
08-23 18:35:08.685  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 18:35:08.685  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:08.685  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:08.685   276   972 D CommandListener: Clearing all IP addresses on wlan0
08-23 18:35:08.685  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.685  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.685  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.685  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:08.685  1014  1126 E ConnectivityService: updateNetworkInfo(),
08-23 18:35:08.685  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:35:08.685   276   972 E Netd    : no such netId 503
08-23 18:35:08.685  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-23 18:35:08.695  1014  1126 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)',
,08-23 18:35:08.695  1014  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-23 18:35:08.695  1014  1126 V NetworkStats: updateIfacesLocked()
,08-23 18:35:08.695  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:08.695  1014  1126 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:08.695  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-23 18:35:08.695  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 18:35:08.705  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-23 18:35:08.715  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-23 18:35:08.715  1014  1126 V NetworkStats: performPollLocked() took 16ms
08-23 18:35:08.715  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 18:35:08.715  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.715  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.715  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-23 18:35:08.715  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.715  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-23 18:35:08.715  1014  1123 D WifiP2pService: InactiveState{ what=131204 },
,08-23 18:35:08.715  1014  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 18:35:08.715  1014  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
08-23 18:35:08.715  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-23 18:35:08.725  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,08-23 18:35:08.725  1014  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:35:08.725  1014  1014 D RttService: SCAN_AVAILABLE : 1
,08-23 18:35:08.725  1014  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:35:08.725  1014  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-23 18:35:08.725  1014  7379 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:35:08.725  1014  7379 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-23 18:35:08.725  1014  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-23 18:35:08.725  1014  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-23 18:35:08.725  1014  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-23 18:35:08.725  1014  1126 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-23 18:35:08.725  1014  1126 E ConnectivityService: updateNetworkInfo()
,08-23 18:35:08.725  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:08.725  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:08.735  1014  1126 E ConnectivityService: updateNetworkInfo()
08-23 18:35:08.735  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 18:35:08.735  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-23 18:35:08.735  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 18:35:08.735  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-23 18:35:08.735  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-23 18:35:08.735  1014  1123 D WifiP2pService: P2pDisablingState
,08-23 18:35:08.735  1014  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
08-23 18:35:08.745  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-23 18:35:08.745  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 18:35:08.745  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-23 18:35:08.745  1014  1045 D WifiDisplayController: disconnect
08-23 18:35:08.745  1014  1045 D WifiDisplayController: updateConnection
08-23 18:35:08.745  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 18:35:08.745  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 18:35:08.745  1014  1123 D WifiP2pService: p2p socket connection lost
,08-23 18:35:08.745  1014  1124 E WifiNative-wlan0: do suspend true
08-23 18:35:08.745  1014  1123 D WifiP2pService: P2pDisabledState
,08-23 18:35:08.745  1014  1474 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 18:35:08.745  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:08.755  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:08.755  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:08.755  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-23 18:35:08.755  1621  1621 I Hs20UtilService: Starting #15
08-23 18:35:08.755  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-23 18:35:08.755  1621  1646 I Hs20UtilService: Message received 5007
08-23 18:35:08.755  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-23 18:35:08.755  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 18:35:08.755  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-23 18:35:08.755  7382  7382 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-23 18:35:08.755  1167  1167 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-23 18:35:08.755  1014  1467 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 18:35:08.755  7382  7382 I dhcpcd  : version 5.5.6 starting
08-23 18:35:08.755  1167  1167 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-23 18:35:08.755  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 18:35:08.765  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 18:35:08.765  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 18:35:08.765  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 18:35:08.765  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-23 18:35:08.765  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 18:35:08.765  1303  2230 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 18:35:08.775  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-23 18:35:08.775  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 18:35:08.775  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 18:35:08.775  7382  7382 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-23 18:35:08.775  1014  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-23 18:35:08.775  1014  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-23 18:35:08.775   276   972 D CommandListener: Clearing all IP addresses on wlan0
08-23 18:35:08.785  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-23 18:35:08.785  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 18:35:08.785  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 18:35:08.785  1303  2230 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 18:35:08.785  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 18:35:08.785  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:08.785  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.785  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.785  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.785  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:08.785  7348  7348 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-23 18:35:08.795  7348  7348 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-23 18:35:08.795  7348  7348 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 18:35:08.795  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-23 18:35:08.795  7284  7284 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-23 18:35:08.795  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:08.795  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:08.795  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.795  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.795  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.795  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:08.815  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:08.815  1014  1124 D SecContentProvider2: mCursor = null
08-23 18:35:08.815  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:08.815  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
08-23 18:35:08.815  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.815  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-23 18:35:08.815  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.815  1167  1167 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:35:08.815  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.815  1167  1167 D HotspotTile: onReceive : 0, 0
08-23 18:35:08.815  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:08.815  1167  1167 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 18:35:08.815  1167  1167 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-23 18:35:08.815  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-23 18:35:08.825  7363  7363 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
08-23 18:35:08.825  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:08.825  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:08.825  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:08.825  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
08-23 18:35:08.825  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:08.825  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:08.825  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:08.835  1014  1467 W ActivityManager: userId = 0, bbcId = -10000,
08-23 18:35:08.835  1014  1467 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 18:35:08.835  1014  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:08.835  1014  1467 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 18:35:08.835  1014  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-23 18:35:08.835  1621  1621 I Hs20UtilService: Starting #16
,08-23 18:35:08.835  1621  1646 I Hs20UtilService: Message received 5007
,08-23 18:35:08.835  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 18:35:08.835  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 18:35:08.835  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-23 18:35:08.835  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 18:35:08.835  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 18:35:08.835  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 18:35:08.845  1303  2230 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 18:35:08.845  1014  1251 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-23 18:35:08.845  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:08.855  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:08.855  1014  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:08.855  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:08.855  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 18:35:08.855  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 18:35:08.855  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
08-23 18:35:08.855  1621  1621 I Hs20UtilService: Starting #17
08-23 18:35:08.855  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-23 18:35:08.855  1621  1646 I Hs20UtilService: Message received 5011,
08-23 18:35:08.855  7382  7382 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-23 18:35:08.855  7382  7382 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
08-23 18:35:08.855  7382  7382 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-23 18:35:08.865  7382  7382 I dhcpcd  : bssid match
08-23 18:35:08.865  7382  7382 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-23 18:35:08.955  7284  7284 I wpa_supplicant: Blacklist: Clear (all) ,
,08-23 18:35:08.965  7382  7382 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-23 18:35:09.045  7382  7382 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-23 18:35:09.045  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-23 18:35:09.045  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 18:35:09.045  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-23 18:35:09.045  7284  7284 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-23 18:35:09.075  7284  7284 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-23 18:35:09.075  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:09.075  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:09.075  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-23 18:35:09.075  1014  1127 D Tethering: InitialState.processMessage what=4
08-23 18:35:09.075  7284  7284 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-23 18:35:09.075  1014  1127 E Tethering: No numeric data
08-23 18:35:09.075  7284  7284 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-23 18:35:09.075  1014  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 18:35:09.075  1014  1127 D Tethering: clearTetheredNotification(),
08-23 18:35:09.075  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:09.075  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:09.075  1167  1167 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 18:35:09.075  1167  1167 D HotspotTile: updateTetherState():false, false
08-23 18:35:09.085  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 18:35:09.085  7284  7284 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-23 18:35:09.085  7284  7284 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-23 18:35:09.085  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 18:35:09.085  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:09.085  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:09.085  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-23 18:35:09.085  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 18:35:09.085  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-23 18:35:09.085  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:09.085  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:09.085  1014  1121 V NetworkStats: performPollLocked() took 9ms
,08-23 18:35:09.095  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:09.095  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:09.105   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-23 18:35:09.405  7284  7284 I wpa_supplicant: Blacklist: Clear (all) ,
,08-23 18:35:09.455  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-23 18:35:09.455  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-23 18:35:09.455  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 18:35:09.465  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:09.465  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:09.465  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-23 18:35:09.465  7284  7284 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-23 18:35:09.575  1014  4756 I ActivityManager: Killing 6899:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-23 18:35:09.575  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-23 18:35:09.575  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-23 18:35:09.575  6953  6953 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 18:35:09.585  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:09.585  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 18:35:09.585  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:09.585  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:09.585  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:09.585  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:09.585  1167  1167 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:35:09.585  1167  1167 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-23 18:35:09.585  1167  1167 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:35:09.595  2025  2219 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:35:09.595  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 18:35:09.595  1167  1167 D HotspotTile: onReceive : 1, 0
,08-23 18:35:09.595  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:35:09.595  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:09.595  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:09.605  1014  1319 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 18:35:09.605  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:09.605  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:09.605  1014  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:09.605  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:09.605  1621  1621 I Hs20UtilService: Starting #18
08-23 18:35:09.605  1621  1646 I Hs20UtilService: Message received 5011
,08-23 18:35:09.625  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-23 18:35:09.625  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-23 18:35:09.625  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
,08-23 18:35:09.625  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 18:35:10.295   276   965 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-23 18:35:10.295  1014  1042 D Tethering: interfaceRemoved wlan0
08-23 18:35:10.305  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-23 18:35:10.555  1014  1042 D Tethering: interfaceRemoved p2p0
,08-23 18:35:10.555  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-23 18:35:11.095   287   287 E SMD     : DCD OFF
,08-23 18:35:11.355  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-23 18:35:11.645  6794  6848 D BluetoothAdapter: enable()
,08-23 18:35:11.645  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-23 18:35:11.655  1014  1027 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-23 18:35:11.655  1014  1027 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 18:35:11.655  1014  1027 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 18:35:11.655  1014  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-23 18:35:11.655  1014  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-23 18:35:11.655  1014  1027 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-23 18:35:11.655  1014  1027 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 18:35:11.655  1014  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 18:35:11.655  1014  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 18:35:11.665  1014  1027 D SettingsProvider: name = bluetooth_on,
,08-23 18:35:11.665  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-23 18:35:11.665  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 18:35:11.665  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-23 18:35:11.665  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2,
,08-23 18:35:11.675  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:11.675  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:11.675  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:11.675  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:11.685  1014  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7412 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-23 18:35:11.695  7412  7412 E Zygote  : MountEmulatedStorage()
,08-23 18:35:11.695  7412  7412 E Zygote  : v2
08-23 18:35:11.695  7412  7412 I libpersona: KNOX_SDCARD checking this for 1002
,08-23 18:35:11.695  7412  7412 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:11.695  7412  7412 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 18:35:11.695  7412  7412 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 18:35:11.695  7412  7412 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 18:35:11.735  7412  7412 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:11.735  7412  7412 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:11.755  7412  7412 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-23 18:35:11.755  7412  7412 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 18:35:11.795  7412  7412 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding GattService
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding HeadsetService
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding A2dpService
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding HidService
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding HealthService
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding PanService
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding SapService
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding SapClientService
,08-23 18:35:11.835  7412  7412 D BtSettings.ProfileConfig: Adding HidDevService
,08-23 18:35:11.845  7412  7412 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-23 18:35:11.845  1014  1800 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-23 18:35:11.845  1014  1800 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 18:35:11.845  1014  1800 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:11.845  1014  1800 D SettingsProvider: selectionArgs: false
,08-23 18:35:11.845  1014  1800 D SettingsProvider: selectionArgs: 1002
08-23 18:35:11.845  1014  1800 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 18:35:11.845  1014  1800 D SettingsProvider: ret = -1
,08-23 18:35:11.845  1014  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-23 18:35:11.845  1014  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 18:35:11.845  1014  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:11.845  1014  1478 D SettingsProvider: selectionArgs: false
08-23 18:35:11.845  1014  1478 D SettingsProvider: selectionArgs: 1002
08-23 18:35:11.845  1014  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:11.845  1014  1478 D SettingsProvider: ret = -1
,08-23 18:35:11.845  1014  1132 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-23 18:35:11.845  1014  1132 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:11.845  1014  1132 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 18:35:11.845  1014  1132 D SettingsProvider: selectionArgs: false
08-23 18:35:11.845  1014  1132 D SettingsProvider: selectionArgs: 1002
,08-23 18:35:11.845  1014  1132 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 18:35:11.845  1014  1132 D SettingsProvider: ret = -1
,08-23 18:35:11.855  1014  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-23 18:35:11.855  1014  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:11.855  1014  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:11.855  1014  1474 D SettingsProvider: selectionArgs: false
08-23 18:35:11.855  1014  1474 D SettingsProvider: selectionArgs: 1002
08-23 18:35:11.855  1014  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:11.855  1014  1474 D SettingsProvider: ret = -1
,08-23 18:35:11.855  1014  1251 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-23 18:35:11.855  1014  1251 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:11.855  1014  1251 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:11.855  1014  1251 D SettingsProvider: selectionArgs: false
,08-23 18:35:11.855  1014  1251 D SettingsProvider: selectionArgs: 1002
08-23 18:35:11.855  1014  1251 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:11.855  1014  1251 D SettingsProvider: ret = -1
08-23 18:35:11.855  1014  4757 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-23 18:35:11.855  1014  4757 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 18:35:11.855  1014  4757 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:11.855  1014  4757 D SettingsProvider: selectionArgs: false
08-23 18:35:11.855  1014  4757 D SettingsProvider: selectionArgs: 1002
08-23 18:35:11.855  1014  4757 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:11.855  1014  4757 D SettingsProvider: ret = -1
08-23 18:35:11.855  1014  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:11.855  1014  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:11.855  1014  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:11.855  1014  1477 D SettingsProvider: selectionArgs: false
08-23 18:35:11.855  1014  1477 D SettingsProvider: selectionArgs: 1002
08-23 18:35:11.855  1014  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:11.855  1014  1477 D SettingsProvider: ret = -1
,08-23 18:35:11.855  1014  1026 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-23 18:35:11.855  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:11.855  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 18:35:11.855  1014  1026 D SettingsProvider: selectionArgs: false
08-23 18:35:11.855  1014  1026 D SettingsProvider: selectionArgs: 1002
08-23 18:35:11.855  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:11.855  1014  1026 D SettingsProvider: ret = -1
,08-23 18:35:11.855  1014  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-23 18:35:11.855  1014  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:11.855  1014  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:11.855  1014  1319 D SettingsProvider: selectionArgs: false,
08-23 18:35:11.855  1014  1319 D SettingsProvider: selectionArgs: 1002
08-23 18:35:11.855  1014  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:11.855  1014  1319 D SettingsProvider: ret = -1
08-23 18:35:11.855  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:11.855  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 18:35:11.855  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:11.855  1014  1027 D SettingsProvider: selectionArgs: false
08-23 18:35:11.855  1014  1027 D SettingsProvider: selectionArgs: 1002
,08-23 18:35:11.855  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:11.855  1014  1027 D SettingsProvider: ret = -1
08-23 18:35:11.855  1014  1467 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService,
08-23 18:35:11.855  1014  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:11.855  1014  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:11.855  1014  1467 D SettingsProvider: selectionArgs: false
,08-23 18:35:11.855  1014  1467 D SettingsProvider: selectionArgs: 1002
08-23 18:35:11.855  1014  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:11.855  1014  1467 D SettingsProvider: ret = -1
,08-23 18:35:11.855  1014  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-23 18:35:11.855  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 18:35:11.855  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:11.855  1014  1479 D SettingsProvider: selectionArgs: false
08-23 18:35:11.855  1014  1479 D SettingsProvider: selectionArgs: 1002
,08-23 18:35:11.855  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 18:35:11.855  1014  1479 D SettingsProvider: ret = -1
,08-23 18:35:11.885  7412  7412 D BluetoothAdapterState: make
,08-23 18:35:11.885  7412  7412 I bluedroid: init
,08-23 18:35:11.885  7412  7427 I BluetoothAdapterState: Entering OffState
,08-23 18:35:11.895  7412  7412 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,08-23 18:35:11.895  7412  7412 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 18:35:11.895  7412  7412 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-23 18:35:11.895  7412  7412 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-23 18:35:11.895  7412  7412 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-23 18:35:11.895  7412  7412 I bluedroid: get_profile_interface socket
08-23 18:35:11.895  7412  7412 I bluedroid: get_profile_interface map_client,
,08-23 18:35:11.895  7412  7412 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-23 18:35:11.905  7412  7430 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-23 18:35:11.905  7412  7430 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-23 18:35:11.905  7412  7430 E BluetoothServiceJni: populateRssiValuesNative
08-23 18:35:11.905  7412  7430 I bluedroid: getModelRssiValues
08-23 18:35:11.905  7412  7430 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-23 18:35:11.905  7412  7430 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-23 18:35:11.905  7412  7430 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-23 18:35:11.905  1014  1014 D SettingsProvider: name = bluetooth_name
,08-23 18:35:11.905  7412  7412 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:11.905  1014  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-23 18:35:11.915  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 18:35:11.915  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:11.915  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:11.915  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:11.915  7412  7423 I bluedroid: config_hci_snoop_log
,08-23 18:35:11.915  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-23 18:35:11.915  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-23 18:35:11.915  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-23 18:35:11.915  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-23 18:35:11.925  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-23 18:35:11.925  7412  7412 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-23 18:35:11.925  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 18:35:11.935  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 18:35:11.935  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-23 18:35:11.935  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-23 18:35:11.935  7412  7427 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-23 18:35:11.935  7412  7427 D BluetoothAdapterProperties: Setting state to 11
,08-23 18:35:11.935  7412  7427 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-23 18:35:11.935  7412  7427 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-23 18:35:11.935  7412  7427 D BluetoothAdapterService: updateAdapterState state is 11
,08-23 18:35:11.935  7412  7427 D BluetoothAdapterService: Autoconnection is available 
08-23 18:35:11.935  7412  7427 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-23 18:35:11.935  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:11.945  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-23 18:35:11.945  7412  7427 D BluetoothSecureManager: getInstant: null
08-23 18:35:11.945  7412  7427 D BluetoothSecureManager: calling getMethod for getService
,08-23 18:35:11.945  7412  7427 D BluetoothSecureManager: calling getService
,08-23 18:35:11.945  7412  7427 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@b951a27
08-23 18:35:11.945  1014  1474 D BluetoothSecureManagerService: isSecureModeEnabled
08-23 18:35:11.945  1014  1474 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-23 18:35:11.945  7412  7427 D BtConfig.SecureMode: isSecureModeOn:false
08-23 18:35:11.945  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-23 18:35:11.945  7412  7427 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-23 18:35:11.945  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-23 18:35:11.945  7412  7427 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-23 18:35:11.945  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-23 18:35:11.945  7412  7427 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-23 18:35:11.945  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-23 18:35:11.945  7412  7427 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-23 18:35:11.945  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-23 18:35:11.955  7412  7427 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-23 18:35:11.955  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-23 18:35:11.955  1167  1167 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-23 18:35:11.955  1167  1167 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:11.955  1167  1167 D BluetoothTile:  getBluetoothState : 11
,08-23 18:35:11.955  7412  7427 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-23 18:35:11.955  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:11.955  1872  1872 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 18:35:11.955  7412  7427 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-23 18:35:11.955  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-23 18:35:11.955  7412  7427 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-23 18:35:11.955  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 18:35:11.955  7412  7427 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 18:35:11.955  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-23 18:35:11.955  7412  7427 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:11.955  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-23 18:35:11.955  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
08-23 18:35:11.955  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-23 18:35:11.955  7412  7427 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-23 18:35:11.955  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 18:35:11.955  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:11.955  7412  7427 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-23 18:35:11.965  1014  1132 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 18:35:11.965  1014  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 18:35:11.965  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:11.965  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 18:35:11.965  1014  1467 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 18:35:11.965  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:11.965  7412  7427 D BluetoothBondStateMachine: make
08-23 18:35:11.965  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:11.965  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:11.965  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:11.975  1167  1167 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 18:35:11.975  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-23 18:35:11.975  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-23 18:35:11.975  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-23 18:35:11.975  7412  7431 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 18:35:11.975  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 18:35:11.975  1014  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:11.975  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-23 18:35:11.975  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:11.975  1167  1167 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:11.975  1167  1167 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-23 18:35:11.975  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:11.975  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:11.985  7412  7412 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 18:35:11.985  7412  7412 D BtGatt.GattService: Received start request. Starting profile...,
08-23 18:35:11.985  7412  7412 D BtGatt.GattService: start()
08-23 18:35:11.985  7412  7412 D BtGatt.GattService: start()
08-23 18:35:11.985  7412  7412 I bluedroid: get_profile_interface gatt
,08-23 18:35:11.985  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
08-23 18:35:11.985  7412  7412 D BtGatt.AdvertiseManager: advertise manager created
,08-23 18:35:11.985  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-23 18:35:11.985  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-23 18:35:11.985  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-23 18:35:11.985  1014  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:11.985  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-23 18:35:11.995  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:11.995  1014  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:11.995  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:11.995  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-23 18:35:11.995  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-23 18:35:11.995  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-23 18:35:11.995  1014  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-23 18:35:11.995  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:11.995  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:11.995  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:11.995  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:12.005  7434  7434 E Zygote  : MountEmulatedStorage()
,08-23 18:35:12.005  7434  7434 E Zygote  : v2
08-23 18:35:12.005  7434  7434 I libpersona: KNOX_SDCARD checking this for 10055
08-23 18:35:12.005  7434  7434 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:12.015  7434  7434 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:12.015  1014  1477 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7434 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-23 18:35:12.015  1014  1800 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:12.015  7434  7434 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 18:35:12.015  1014  1800 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.015  1014  1800 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.015  1014  1800 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.015  1014  1800 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:12.015  7434  7434 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 18:35:12.015  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-23 18:35:12.015  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 18:35:12.015  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-23 18:35:12.015  1014  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:12.015  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.025  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.025  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.025  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:12.025  7412  7412 D BtGatt.GattService: mStartError = false
08-23 18:35:12.025  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
08-23 18:35:12.025  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-23 18:35:12.025  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-23 18:35:12.025  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-23 18:35:12.025  1014  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:12.025  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.025  7412  7412 D HeadsetService: Received start request. Starting profile...
08-23 18:35:12.025  7412  7412 D HeadsetService: start()
,08-23 18:35:12.025  7412  7412 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-23 18:35:12.025  7412  7412 D HeadsetStateMachine: make
,08-23 18:35:12.025  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.025  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.025  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:12.035  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-23 18:35:12.035  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-23 18:35:12.035  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-23 18:35:12.035  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:12.035  7412  7412 E HeadsetStateMachine: # of Max HF connection is 2
08-23 18:35:12.035  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-23 18:35:12.035  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.035  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.035  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:12.035  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-23 18:35:12.035  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 18:35:12.035  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-23 18:35:12.045  1014  1132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:12.045  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.045  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.045  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.045  1014  4757 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-23 18:35:12.045  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 18:35:12.045  1014  4757 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.045  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-23 18:35:12.045  1014  4757 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.045  1014  4757 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.045  1014  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-23 18:35:12.045  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 18:35:12.045  7412  7427 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-23 18:35:12.045  1014  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:12.045  1014  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.045  1014  1467 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.045  7434  7434 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 18:35:12.045  1014  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.045  1014  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 18:35:12.045  7434  7434 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:12.055  1014  1474 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-23 18:35:12.055  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.055  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-23 18:35:12.055  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 18:35:12.055  7412  7427 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-23 18:35:12.055  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:12.055  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:12.055  7412  7427 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:12.055  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-23 18:35:12.055  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.055  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-23 18:35:12.055  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.055  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-23 18:35:12.055  7412  7427 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-23 18:35:12.055  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-23 18:35:12.055  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 18:35:12.055  7412  7427 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 18:35:12.055  7412  7427 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-23 18:35:12.055  7412  7412 I bluedroid: get_profile_interface handsfree
,08-23 18:35:12.075  7412  7412 I DualScoManager: Instantiating Dual Sco Manager
,08-23 18:35:12.075  7412  7412 I DualScoManager: Set HeadsetServiceHelper
,08-23 18:35:12.075  7434  7434 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-23 18:35:12.075  7412  7412 D BluetoothAtMessage: createCMTIContentObservers
,08-23 18:35:12.075  1014  4757 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-23 18:35:12.075  1014  4757 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:12.075  1014  4757 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:12.075  1014  4757 D SettingsProvider: selectionArgs: false,
08-23 18:35:12.075  1014  4757 D SettingsProvider: selectionArgs: 1002
08-23 18:35:12.075  1014  4757 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:12.075  1014  4757 D SettingsProvider: ret = -1
,08-23 18:35:12.075  7412  7444 D HeadsetStateMachine: Enter Disconnected: -2
,08-23 18:35:12.075  7412  7412 D HeadsetService: mStartError = false
08-23 18:35:12.075  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:12.085  7412  7412 D A2dpService: Received start request. Starting profile...
08-23 18:35:12.085  7412  7412 D A2dpService: start()
,08-23 18:35:12.085  7412  7412 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-23 18:35:12.085  7412  7412 I bluedroid: get_profile_interface avrcp
,08-23 18:35:12.085  7412  7444 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-23 18:35:12.085  7412  7444 D HeadsetStateMachine: map size, before remove : 0
,08-23 18:35:12.085  7412  7444 D HeadsetStateMachine: map size, after remove: 0
,08-23 18:35:12.095  7412  7412 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 18:35:12.095  7412  7412 D Avrcp   : Initialize Media Controller
,08-23 18:35:12.095  7412  7412 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-23 18:35:12.095  7412  7412 E Avrcp   : getActiveSessions
08-23 18:35:12.095  7412  7412 D Avrcp   : pick active media Controller
08-23 18:35:12.095  7412  7412 D Avrcp   : Get the active Media Controller 
,08-23 18:35:12.105  7434  7434 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-23 18:35:12.105  7434  7434 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-23 18:35:12.105  7434  7434 D UserAnalysis: Create SecureDbHelper
,08-23 18:35:12.105  7412  7412 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-23 18:35:12.115  7412  7454 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-23 18:35:12.115  7412  7412 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-23 18:35:12.115  7412  7412 D A2dpStateMachine: make
,08-23 18:35:12.115  7412  7412 I bluedroid: get_profile_interface a2dp
,08-23 18:35:12.115  7412  7456 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-23 18:35:12.115  7412  7412 E bt-btif : warning : media task started media_task_refcnt 1 
,08-23 18:35:12.115  7412  7412 D A2dpService: mStartError = false
08-23 18:35:12.115  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
08-23 18:35:12.115  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-23 18:35:12.115  7434  7434 D IntelligenceServiceApplication: onCreate()
,08-23 18:35:12.115  7412  7455 D A2dpStateMachine: Enter Disconnected: -2
08-23 18:35:12.115  7412  7412 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 18:35:12.125  7412  7412 D HidService: Received start request. Starting profile...
08-23 18:35:12.125  7412  7412 D HidService: start()
08-23 18:35:12.125  7412  7412 I bluedroid: get_profile_interface hidhost
08-23 18:35:12.125  7412  7412 D HidService: setHidService(): set to: null
08-23 18:35:12.125  7412  7412 D HidService: mStartError = false
08-23 18:35:12.125  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:12.125  7412  7412 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-23 18:35:12.125  7434  7434 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-23 18:35:12.125  7412  7412 D HealthService: Received start request. Starting profile...
08-23 18:35:12.125  7412  7412 D HealthService: start()
,08-23 18:35:12.135  1014  1479 I ActivityManager: Killing 7043:com.sec.pcw.device/1000 (adj 15): empty #21
08-23 18:35:12.135  7412  7412 I bluedroid: get_profile_interface health
08-23 18:35:12.135  7412  7412 D HealthService: mStartError = false
08-23 18:35:12.135  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:12.135  7412  7412 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-23 18:35:12.135  7412  7412 D PanService: Received start request. Starting profile...
08-23 18:35:12.135  7412  7412 D PanService: start()
08-23 18:35:12.135  7412  7412 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 18:35:12.135  7412  7412 I bluedroid: get_profile_interface pan
08-23 18:35:12.135  7412  7412 D PanService: mStartError = false
08-23 18:35:12.135  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:12.135  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-23 18:35:12.135  7434  7434 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-23 18:35:12.135  7412  7454 D BluetoothMediaBrowser: no now playing list
08-23 18:35:12.135  7412  7454 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-23 18:35:12.145  7412  7412 D BluetoothMapService: Received start request. Starting profile...
08-23 18:35:12.145  7412  7412 D BluetoothMapService: start()
,08-23 18:35:12.145  7412  7412 D BluetoothMapService: mStartError = false
08-23 18:35:12.145  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
08-23 18:35:12.145  7412  7412 D HeadsetStateMachine: Try to query the phonestate on bind
,08-23 18:35:12.145  1429  3267 I Telecom : BluetoothPhoneService: queryPhoneState
,08-23 18:35:12.145  7434  7434 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-23 18:35:12.145  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-23 18:35:12.145  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-23 18:35:12.145  1429  3267 I Telecom : BluetoothPhoneService: Result of Message : true
,08-23 18:35:12.145  7412  7412 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-23 18:35:12.155  7412  7412 D SapService: Received start request. Starting profile...
08-23 18:35:12.155  7412  7412 D SapService: start()
08-23 18:35:12.155  7412  7412 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-23 18:35:12.155  7412  7412 I bluedroid: get_profile_interface sap
08-23 18:35:12.155  7412  7412 D SapService: mStartError = false
08-23 18:35:12.155  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
08-23 18:35:12.155  7412  7412 D HeadsetStateMachine: Proxy object connected
08-23 18:35:12.155  7412  7412 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-23 18:35:12.155  7412  7412 D HeadsetPhoneState: sendDeviceDataStateChanged
08-23 18:35:12.155  7412  7444 D HeadsetStateMachine: Disconnected process message: 11
08-23 18:35:12.155  7412  7444 D HeadsetStateMachine: Disconnected process message: 18
08-23 18:35:12.155  7412  7412 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-23 18:35:12.155  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-23 18:35:12.155  7412  7412 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 18:35:12.155  7412  7412 D BluetoothA2dp: Proxy object connected
08-23 18:35:12.155  7412  7412 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-23 18:35:12.155  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-23 18:35:12.155  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-23 18:35:12.155  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-23 18:35:12.155  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-23 18:35:12.155  7412  7444 D HeadsetStateMachine: Disconnected process message: 10
08-23 18:35:12.155  7412  7444 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 18:35:12.155  7412  7444 D HeadsetStateMachine: Disconnected process message: 11
,08-23 18:35:12.155  1014  4756 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-23 18:35:12.165  1014  4756 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:12.165  1014  4756 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-23 18:35:12.165  1014  4756 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:12.165  1014  4756 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:12.175  7461  7461 E Zygote  : MountEmulatedStorage()
08-23 18:35:12.175  7461  7461 I libpersona: KNOX_SDCARD checking this for 10105
08-23 18:35:12.175  7461  7461 E Zygote  : v2
08-23 18:35:12.175  7461  7461 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:12.175  7461  7461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:12.175  1014  4756 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7461 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-23 18:35:12.185  7461  7461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:12.185  7461  7461 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 18:35:12.215  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-23 18:35:12.215  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-23 18:35:12.215  7412  7427 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-23 18:35:12.215  7412  7427 I bluedroid: enable
,08-23 18:35:12.215  7412  7473 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-23 18:35:12.215  7412  7427 I bt_hci_bdroid: init
,08-23 18:35:12.225  7412  7427 I bt_vendor: bt-vendor : init
08-23 18:35:12.225  7412  7427 I bt_vendor: bt-vendor : get_bt_soc_type
08-23 18:35:12.225  7412  7427 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-23 18:35:12.225  7412  7427 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-23 18:35:12.225  7412  7427 D bt_userial_mct: userial_init
08-23 18:35:12.225  7461  7461 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:12.225  7461  7461 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:12.225  7412  7427 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 18:35:12.225  7412  7427 I bt_vendor: Starting hciattach daemon
,08-23 18:35:12.225  7412  7427 I bt_vendor: try to set false
,08-23 18:35:12.225  7412  7427 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-23 18:35:12.225  7412  7427 I bt_vendor: Starting hciattach daemon
08-23 18:35:12.225  7412  7427 I bt_vendor: try to set true
,08-23 18:35:12.255  7481  7481 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-23 18:35:12.305  7487  7487 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-23 18:35:12.315  7488  7488 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-23 18:35:12.325  7492  7492 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-23 18:35:12.335  7493  7493 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-23 18:35:12.345  7494  7494 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-23 18:35:12.355  7495  7495 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-23 18:35:12.375   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-23 18:35:12.375   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 18:35:12.375  7461  7498 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 18:35:12.375   256   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-23 18:35:12.375   256   529 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 18:35:12.375  7461  7498 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 18:35:12.525  7461  7461 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:12.525  7461  7461 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:12.525  7461  7461 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:12.525  7461  7461 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:12.525  7461  7461 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.k.d(PG:583)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:12.525  7461  7461 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:12.525  7461  7461 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:12.525  7461  7461 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 18:35:12.525  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 18:35:12.535  1014  1026 I ActivityManager: Killing 7060:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
08-23 18:35:12.535  2025  2025 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-23 18:35:12.535  2025  2025 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 18:35:12.575  7510  7510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
08-23 18:35:12.575  7511  7511 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-23 18:35:12.595  7461  7505 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-23 18:35:12.635  7412  7427 I bt_vendor: bluetooth satus is on
,08-23 18:35:12.635  7412  7476 D bt_userial_mct: userial_open(port:0)
08-23 18:35:12.635  7412  7476 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-23 18:35:12.635  7412  7476 I bt_vendor: Done intiailizing UART
,08-23 18:35:12.645  7412  7476 I bt_vendor: Done intiailizing UART
,08-23 18:35:12.645  7412  7476 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-23 18:35:12.645  7412  7476 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-23 18:35:12.645  7412  7514 D bt_userial_mct: Entering userial_read_thread()
,08-23 18:35:12.755  1014  1479 I art     : Explicit concurrent mark sweep GC freed 68415(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.365ms total 141.682ms
08-23 18:35:12.755  1014  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 18:35:12.755  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.755  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:12.755  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_HCI
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_AVDT
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_SAP
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_BTIF
08-23 18:35:12.755  7412  7473 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-23 18:35:12.855  7412  7473 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-23 18:35:12.855  7412  7473 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41b8ed1 
,08-23 18:35:12.855  7412  7473 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41b8ed1 
,08-23 18:35:12.875  7412  7430 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-23 18:35:12.875  7412  7430 E bt-btif : Calling BTA_HhEnable
,08-23 18:35:12.875  7412  7430 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-23 18:35:12.875  7412  7430 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-23 18:35:12.885  7412  7430 E BluetoothServiceJni: populateRssiValuesNative
08-23 18:35:12.885  7412  7430 I bluedroid: getModelRssiValues
,08-23 18:35:12.885  7412  7430 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-23 18:35:12.885  7412  7430 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-23 18:35:12.885  1014  1014 D SettingsProvider: name = bluetooth_name
,08-23 18:35:12.885  7412  7430 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-23 18:35:12.895  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:12.895  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:12.895  7412  7430 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-23 18:35:12.895  7412  7430 D BluetoothAdapterProperties: Scan Mode:20
,08-23 18:35:12.895  7412  7430 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 18:35:12.895  7412  7430 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-23 18:35:12.895  7412  7430 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-23 18:35:12.895  7412  7430 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-23 18:35:12.905  7412  7430 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-23 18:35:12.905  7412  7430 E bt-btif : btif_sock_init: !vhci_init
,08-23 18:35:12.905  7412  7514 E bt_mct  : hci lib postload completed
08-23 18:35:12.905  7412  7430 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-23 18:35:12.905  7412  7430 D IOP_DB_BT: db_open: db_open : handle 3023806480l, read 13894 bytes onto local cache
,08-23 18:35:12.905  7412  7430 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-23 18:35:12.905  7412  7430 D IOP_DB_BT: db_query: result 1
,08-23 18:35:12.905  7412  7430 I         : iop_db_open: iop_db_open status 0
,08-23 18:35:12.905  7412  7430 D bte_conf: Device ID record 1 : primary
,08-23 18:35:12.905  7412  7430 D bte_conf:   vendorId            = 0075
,08-23 18:35:12.905  7412  7430 D bte_conf:   vendorIdSource      = 0001
08-23 18:35:12.905  7412  7430 D bte_conf:   product             = 0100
08-23 18:35:12.905  7412  7430 D bte_conf:   version             = 0200
08-23 18:35:12.905  7412  7430 D bte_conf:   clientExecutableURL = 
08-23 18:35:12.905  7412  7430 D bte_conf:   serviceDescription  = 
08-23 18:35:12.905  7412  7430 D bte_conf:   documentationURL    = 
08-23 18:35:12.905  7412  7430 D bte_conf: bte_load_did_conf no section named DID2.
,08-23 18:35:12.915  7412  7430 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 18:35:12.915  7412  7427 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-23 18:35:12.915  7412  7427 D BluetoothAdapterProperties: ScanMode =  20
,08-23 18:35:12.915  7412  7427 D BluetoothAdapterProperties: State =  11
,08-23 18:35:12.915  1014  4757 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 18:35:12.915  7412  7427 D BluetoothAdapterProperties: Setting state to 12
,08-23 18:35:12.915  7412  7427 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-23 18:35:12.925  7412  7430 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-23 18:35:12.925  7412  7430 D BluetoothAdapterProperties: Scan Mode:21
08-23 18:35:12.925  7412  7430 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 18:35:12.925  1014  1478 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-23 18:35:12.925  1014  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:12.925  1014  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 18:35:12.925  1014  1478 D SettingsProvider: selectionArgs: false
08-23 18:35:12.925  1014  1478 D SettingsProvider: selectionArgs: 1002
,08-23 18:35:12.925  1014  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 18:35:12.925  1014  1478 D SettingsProvider: ret = -1
,08-23 18:35:12.925  7412  7427 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-23 18:35:12.935  7412  7427 D BluetoothAdapterService: updateAdapterState state is 12
,08-23 18:35:12.935  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:12.935  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:12.935  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:12.935  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:12.935  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:12.935  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:12.935  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:12.935  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:12.935  1014  1800 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:12.935  1014  1800 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.935  1014  1800 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.935  1014  1800 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.935  1014  1800 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:12.935  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:12.935  7412  7427 D BluetoothAdapterService: Autoconnection is available 
08-23 18:35:12.935  7412  7427 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-23 18:35:12.935  7412  7427 D BluetoothAdapterService: starting service from this receiver
,08-23 18:35:12.945  1014  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:12.945  1014  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.945  1014  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:12.945  1014  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:12.945  1014  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:12.945  7412  7427 I BluetoothAdapterState: Entering On State from state = 11,
08-23 18:35:12.945  1429  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:12.955  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-23 18:35:12.955  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-23 18:35:12.955  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.955  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.955  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:12.955  1429  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 18:35:12.955  1303  1312 D Bluetoothsap: onBluetoothStateChange: up=true
,08-23 18:35:12.955  1303  1312 D Bluetoothsap: Binding service...
,08-23 18:35:12.965  7412  7412 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-23 18:35:12.965  1303  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 ,
,08-23 18:35:12.965  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-23 18:35:12.965  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.965  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.965  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.965  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:12.965  1303  1312 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-23 18:35:12.965  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:12.965  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:12.965  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:12.965  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:12.965  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:12.965  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:12.965  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:12.965  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:12.965  2025  2037 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 18:35:12.965  2025  2037 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:12.975  1303  6930 D BluetoothPan: Binding service...
,08-23 18:35:12.975  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:12.975  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-23 18:35:12.975  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.975  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:12.975  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.975  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:12.975  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 18:35:12.975  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:12.975  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-23 18:35:12.975  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.985  1014  1014 D BluetoothA2dp: Proxy object connected
,08-23 18:35:12.985  1303  1316 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 18:35:12.985  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-23 18:35:12.985  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 18:35:12.985  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.985  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.985  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:12.985  1303  1312 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 18:35:12.985  7412  7412 I BluetoothPbapService: Handler(): got msg=1
,08-23 18:35:12.985  1014  1026 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-23 18:35:12.985  1303  1312 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:12.995  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-23 18:35:12.995  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-23 18:35:12.995  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:12.995  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:12.995  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:12.995  1303  1303 D BluetoothA2dp: Proxy object connected
,08-23 18:35:12.995  7461  7470 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:12.995  7461  7470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 18:35:12.995  1303  1303 D A2dpProfile: Bluetooth service connected
,08-23 18:35:12.995  1456  2453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:12.995  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 18:35:12.995  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 18:35:13.005  7412  7521 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-23 18:35:13.005  1303  1303 D Bluetoothsap: BluetoothSAP Proxy object connected
08-23 18:35:13.005  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:13.005  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:13.005  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:13.005  1456  2453 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 18:35:13.005  1303  1303 D SapProfile: Bluetooth service connected
08-23 18:35:13.005  1303  1303 D Bluetoothsap: getConnectedDevices()
,08-23 18:35:13.005  1429  3267 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:13.005  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 18:35:13.005  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 18:35:13.005  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:13.005  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:13.005  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-23 18:35:13.005  7412  7521 D BluetoothSocket: bindListen(): myUserId = 0
08-23 18:35:13.005  7412  7521 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:35:13.005  1303  1303 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 18:35:13.005  1303  1303 D PanProfile: Bluetooth service connected
,08-23 18:35:13.005  1429  3267 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 18:35:13.005  1303  1316 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 18:35:13.015  7412  7521 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-23 18:35:13.015  7412  7521 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 18:35:13.015  7412  7521 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 18:35:13.015  7412  7521 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27ffabb8
,08-23 18:35:13.015  7412  7521 D BluetoothSocket: channel: 19
08-23 18:35:13.015  7412  7521 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-23 18:35:13.015  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-23 18:35:13.015  1303  1303 D BluetoothInputDevice: Proxy object connected
08-23 18:35:13.015  1303  1303 D HidProfile: Bluetooth service connected
,08-23 18:35:13.015  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 18:35:13.015  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:13.015  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:13.015  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:13.015  1303  1303 D BluetoothMap: Proxy object connected
08-23 18:35:13.015  1303  1303 D MapProfile: Bluetooth service connected
08-23 18:35:13.015  1303  1303 D BluetoothMap: getConnectedDevices()
,08-23 18:35:13.015  1303  1312 D BluetoothPbap: onBluetoothStateChange: up=true
,08-23 18:35:13.025  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-23 18:35:13.025  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 18:35:13.025  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:13.025  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:13.025  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:13.025  1303  1303 D BluetoothPbap: Proxy object connected
,08-23 18:35:13.025  1303  1303 D PbapServerProfile: Bluetooth service connected
,08-23 18:35:13.025  1303  6930 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:13.025  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-23 18:35:13.025  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 18:35:13.025  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:13.035  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:13.035  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:13.035  1303  1303 D HeadsetProfile: Bluetooth service connected
08-23 18:35:13.035  1303  6930 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 18:35:13.035  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:13.035  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:13.035  6794  6802 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:13.035  6794  6802 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:13.035  1429  1440 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:13.035  1429  1440 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:13.035  1303  1312 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 18:35:13.035  1303  1312 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:13.035  7412  7423 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 18:35:13.035  1456  1469 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 18:35:13.035  1456  1469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:13.035  1439  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 18:35:13.035  1439  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:13.045  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:13.045  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-23 18:35:13.045  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 18:35:13.045  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 18:35:13.045  1014  1044 D BluetoothPan: Binding service...
,08-23 18:35:13.045  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-23 18:35:13.045  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 18:35:13.045  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected,
08-23 18:35:13.045  1167  1821 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 18:35:13.045  1167  1821 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 18:35:13.045  7412  7423 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:13.045  7412  7423 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:13.045  1429  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:13.045  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 18:35:13.045  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 18:35:13.055  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:13.055  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:13.055  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:13.055  1429  1437 E BluetoothHeadset: BluetoothHeadset service is binded,
08-23 18:35:13.055  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-23 18:35:13.055  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-23 18:35:13.055  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-23 18:35:13.055  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-23 18:35:13.055  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-23 18:35:13.065  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@271cad34, true
08-23 18:35:13.065  1429  1429 D BluetoothHeadset: registerMessageListener
,08-23 18:35:13.065  1167  1167 D BluetoothTile:  onBluetoothStateChange:
,08-23 18:35:13.065  1167  1167 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 18:35:13.065  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 18:35:13.065  1167  1167 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:13.065  1167  1167 D BluetoothTile:  getBluetoothState : 12
,08-23 18:35:13.065  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 18:35:13.075  1014  1026 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
,08-23 18:35:13.075  1872  1872 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-23 18:35:13.075  1014  1479 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-23 18:35:13.075  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:13.075  1167  1167 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 18:35:13.075  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 18:35:13.085  1014  1132 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 18:35:13.085  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-23 18:35:13.085  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:13.085  7412  7423 D HeadsetService: registerMessageListener
08-23 18:35:13.085  7412  7423 D HeadsetService: registerMessageListener
,08-23 18:35:13.085  7412  7444 D HeadsetStateMachine: Disconnected process message: 70
08-23 18:35:13.085  7412  7444 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@367e5d91
,08-23 18:35:13.085  1014  1132 W ActivityManager: userId = 0, bbcId = -10000,
08-23 18:35:13.085  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-23 18:35:13.085  1014  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:13.085  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-23 18:35:13.085  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 18:35:13.085  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:13.085  7412  7523 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-23 18:35:13.085  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-23 18:35:13.085  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-23 18:35:13.085  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-23 18:35:13.085  7412  7523 D BluetoothSocket: bindListen(): myUserId = 0
08-23 18:35:13.085  7412  7523 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 18:35:13.095  1303  1303 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-23 18:35:13.095  1303  1303 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-23 18:35:13.095  7412  7523 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-23 18:35:13.095  7412  7523 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 18:35:13.095  7412  7523 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 18:35:13.095  7412  7523 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@237634f6
,08-23 18:35:13.095  7412  7523 D BluetoothSocket: channel: 5
08-23 18:35:13.095  1303  1303 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-23 18:35:13.095  7412  7444 D HeadsetStateMachine: Disconnected process message: 9
,08-23 18:35:13.095  7412  7444 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-23 18:35:13.095  1303  1303 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-23 18:35:13.105   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-23 18:35:13.105   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-23 18:35:13.105   282   282 V voice   : voice_set_parameters: exit with code(-2)
08-23 18:35:13.105   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-23 18:35:13.105   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-23 18:35:13.105   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-23 18:35:13.105   282   282 V audio_hw_primary: adev_set_parameters: exit
,08-23 18:35:13.105  7412  7444 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-23 18:35:13.115  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 18:35:13.115  1014  1027 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-23 18:35:13.115  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 18:35:13.115  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:13.115  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:13.115  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 18:35:13.125  1303  1303 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:35:13.125  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 18:35:13.125  1167  1167 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:13.125  1167  1167 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-23 18:35:13.135  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
08-23 18:35:13.135  7412  7412 D BtConfig.SecureMode: isSecureModeOn:false
,08-23 18:35:13.135  1014  1800 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:13.135  1014  1800 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-23 18:35:13.135  1014  1800 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:13.135  1014  1800 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:13.135  1014  1800 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:13.145  1014  3342 D SSRM:n  : SIOP:: AP = 340
,08-23 18:35:13.155  2025  2025 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:13.165  1014  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 18:35:13.165  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-23 18:35:13.165  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:13.165  1014  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 18:35:13.165  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:13.165  1014  1026 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-23 18:35:13.175  2025  7532 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-23 18:35:13.175  2025  2025 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 18:35:13.175  1014  4756 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 18:35:13.175  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:13.175  1014  4756 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:13.175  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:13.185  7412  7533 D BluetoothSocket: bindListen(): myUserId = 0
08-23 18:35:13.185  7412  7533 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 18:35:13.195  7412  7533 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-23 18:35:13.195  7412  7533 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 18:35:13.195  7412  7533 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 18:35:13.195  7412  7533 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@318039d0
,08-23 18:35:13.195  7412  7533 D BluetoothSocket: channel: 12
08-23 18:35:13.195  7412  7533 I BtOppRfcommListener: Accept thread started.
,08-23 18:35:13.195  1014  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 18:35:13.195  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:13.195  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:13.195  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:13.205  2025  7532 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-23 18:35:14.095   287   287 E SMD     : DCD OFF
,08-23 18:35:14.665  6794  6848 D BluetoothAdapter: disable()
,08-23 18:35:14.675  1014  1467 D SettingsProvider: name = bluetooth_on
,08-23 18:35:14.685  7412  7427 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-23 18:35:14.685  7412  7427 D BluetoothAdapterProperties: Setting state to 13
,08-23 18:35:14.685  7412  7427 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 18:35:14.685  7412  7427 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 18:35:14.685  7412  7427 D BluetoothAdapterService: updateAdapterState state is 13
,08-23 18:35:14.685  1014  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:14.685  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 18:35:14.685  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:14.685  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:14.685  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:14.685  7412  7412 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-23 18:35:14.685  7412  7412 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c162dc9, channel: 19, state: LISTENING
,08-23 18:35:14.685  7412  7427 D BluetoothAdapterService: Autoconnection is available 
08-23 18:35:14.685  7412  7427 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-23 18:35:14.685  7412  7427 D BluetoothAdapterService: terminating service from this receiver
,08-23 18:35:14.695  7412  7412 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c162dc9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27ffabb8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39daeccemSocket: android.net.LocalSocket@bb1c7ef impl:android.net.LocalSocketImpl@377722fc fd:FileDescriptor[74]
,08-23 18:35:14.695  7412  7412 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@bb1c7ef impl:android.net.LocalSocketImpl@377722fc fd:FileDescriptor[74]
08-23 18:35:14.695  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-23 18:35:14.695  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:14.695  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:14.695  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:14.695  7412  7427 D BluetoothAdapterProperties: onBluetoothDisable()
,08-23 18:35:14.695  7412  7427 D BluetoothAdapterProperties: mDiscovering is false
,08-23 18:35:14.695  1014  1251 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 18:35:14.705  7412  7427 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-23 18:35:14.705  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:14.705  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-23 18:35:14.705  1167  1167 D BluetoothTile:  onBluetoothStateChange:
,08-23 18:35:14.715  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
08-23 18:35:14.715  1167  1167 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 18:35:14.715  1167  1167 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:14.715  1167  1167 D BluetoothTile:  getBluetoothState : 13
,08-23 18:35:14.715  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 18:35:14.715  1872  1872 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 18:35:14.725  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:14.725  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-23 18:35:14.725  1014  1467 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-23 18:35:14.725  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:14.725  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:14.725  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:14.725  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:14.725  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:14.725  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:14.725  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:14.725  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:14.725  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:14.725  1014  1251 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 18:35:14.735  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:14.735  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:14.735  1167  1167 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 18:35:14.735  1167  1167 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 18:35:14.735  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:35:14.735  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:14.735  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:14.735  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:14.735  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:14.735  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:35:14.735  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:14.735  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:14.735  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:14.735  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 18:35:14.735  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:14.735  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 18:35:14.735  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 18:35:14.745  1014  1027 W ActivityManager: userId = 0, bbcId = -10000,
08-23 18:35:14.745  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:14.745  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 18:35:14.745  7412  7430 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-23 18:35:14.745  7412  7430 D BluetoothAdapterProperties: Scan Mode:20
,08-23 18:35:14.755  7412  7427 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-23 18:35:14.755  7412  7427 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-23 18:35:14.755  7412  7427 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-23 18:35:14.755  7412  7427 E bt-btif : cmd socket is not created
,08-23 18:35:14.755  7412  7427 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-23 18:35:14.755  7412  7473 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-23 18:35:14.755  7412  7473 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-23 18:35:14.755  7412  7473 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:35:14.755  7412  7473 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:35:14.755  7412  7473 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-23 18:35:14.765  7412  7533 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-23 18:35:14.765  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 18:35:14.765  1014  4756 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-23 18:35:14.765  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:14.765  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 18:35:14.765  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:14.765  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:14.765  1014  4756 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:14.765  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 18:35:14.775  1303  1303 D BluetoothPbap: Proxy object disconnected
,08-23 18:35:14.775  1303  1303 D PbapServerProfile: Bluetooth service disconnected
,08-23 18:35:14.785  7412  7412 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@354add85, channel: 5, state: LISTENING
08-23 18:35:14.785  7412  7412 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@354add85, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@237634f6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a3d07damSocket: android.net.LocalSocket@30fcf40b impl:android.net.LocalSocketImpl@399172e8 fd:FileDescriptor[76]
08-23 18:35:14.785  7412  7412 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@30fcf40b impl:android.net.LocalSocketImpl@399172e8 fd:FileDescriptor[76]
,08-23 18:35:14.785  7412  7412 I BtOppRfcommListener: stopping Accept Thread
08-23 18:35:14.785  7412  7412 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b60cd01, channel: 12, state: LISTENING
08-23 18:35:14.785  7412  7412 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b60cd01, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@318039d0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3673c7a6mSocket: android.net.LocalSocket@684c5e7 impl:android.net.LocalSocketImpl@327ed594 fd:FileDescriptor[80]
08-23 18:35:14.785  7412  7412 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@684c5e7 impl:android.net.LocalSocketImpl@327ed594 fd:FileDescriptor[80]
,08-23 18:35:14.785  7412  7533 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-23 18:35:14.795  7412  7412 V BluetoothOppManager: cleanUp...
,08-23 18:35:14.795  1303  1303 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:35:14.795  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 18:35:14.795  1167  1167 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:14.795  1167  1167 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-23 18:35:14.815  2025  2025 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:14.815  2025  2025 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 18:35:14.955  7412  7473 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-23 18:35:14.955  7412  7473 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-23 18:35:14.955  7412  7473 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:35:14.955  7412  7473 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:35:14.955  7412  7473 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-23 18:35:14.955  7412  7473 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:35:14.955  7412  7473 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:35:14.955  7412  7473 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:35:14.955  7412  7473 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
08-23 18:35:14.965  7412  7473 W bt-btif : ag scb idx 1 not allocated
,08-23 18:35:14.965  7412  7473 W bt-btif : ag scb idx 2 not allocated
08-23 18:35:14.965  7412  7473 E bt-btif : BTA AG is already disabled, ignoring ...
08-23 18:35:14.965  7412  7514 I bt_userial_mct: exiting userial_read_thread,
08-23 18:35:14.965  7412  7514 D bt_userial_mct: Leaving userial_evt_read_thread()
08-23 18:35:14.965  7412  7430 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0,
08-23 18:35:14.965  7412  7476 I bt_vendor: hw_epilog_process
08-23 18:35:14.965  7412  7430 D bt_userial_mct: userial_close
,08-23 18:35:14.965  7412  7430 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-23 18:35:16.315  7412  7430 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 18:35:16.315  7412  7430 I bt_vendor: bluetooth satus is on
08-23 18:35:16.315  7412  7430 I bt_vendor: bt-vendor : resetting BT status
08-23 18:35:16.315  7412  7430 I bt_vendor: Starting hciattach daemon
08-23 18:35:16.315  7412  7430 I bt_vendor: try to set false
08-23 18:35:16.315  7412  7430 I bt_vendor: Starting hciattach daemon
08-23 18:35:16.315  7412  7430 I bt_vendor: try to set false
08-23 18:35:16.315  7412  7430 I bt_vendor: cleanup
,08-23 18:35:16.315  7412  7473 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
08-23 18:35:16.315  7412  7430 I GKI_LINUX: GKI_exit_task 0 done
,08-23 18:35:16.315  1014  1132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-23 18:35:16.315  7412  7430 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-23 18:35:16.315  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-23 18:35:16.315  7412  7427 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-23 18:35:16.315  1014  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:16.315  7412  7427 D BtConfig.SecureMode: isSecureModeOn:false
08-23 18:35:16.315  1014  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-23 18:35:16.315  7412  7427 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-23 18:35:16.315  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-23 18:35:16.315  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-23 18:35:16.315  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-23 18:35:16.315  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:16.315  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:16.315  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 18:35:16.315  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-23 18:35:16.315  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService,
08-23 18:35:16.315  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-23 18:35:16.315  7412  7412 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 18:35:16.325  1014  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:16.325  1014  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:16.325  1014  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 18:35:16.325  7412  7412 D BtGatt.GattService: Received stop request...Stopping profile...,
08-23 18:35:16.325  7412  7412 D BtGatt.GattService: stop(),
08-23 18:35:16.325  7412  7412 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 18:35:16.325  1014  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:16.325  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-23 18:35:16.325  1014  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-23 18:35:16.325  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-23 18:35:16.325  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-23 18:35:16.325  1014  1467 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:16.325  1014  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:16.325  1014  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:16.335  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-23 18:35:16.335  1014  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:16.335  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 18:35:16.335  1014  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-23 18:35:16.335  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-23 18:35:16.335  1014  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:16.335  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
08-23 18:35:16.335  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-23 18:35:16.335  1014  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:16.335  1014  4757 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 18:35:16.335  1014  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:16.335  1014  4757 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 18:35:16.335  1014  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 18:35:16.335  1014  4757 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 18:35:16.335  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-23 18:35:16.335  1014  4757 D BatteryService: stay LED for fully charged
08-23 18:35:16.335  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-23 18:35:16.335  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-23 18:35:16.335  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 18:35:16.335  7412  7412 D HeadsetService: Received stop request...Stopping profile...
,08-23 18:35:16.345  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:16.345  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:16.345  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:16.345  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-23 18:35:16.345  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-23 18:35:16.345  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-23 18:35:16.345  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:16.355  1014  1014 I MotionRecognitionService: Plugged
,08-23 18:35:16.355  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 18:35:16.355  1167  1167 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 18:35:16.355  1167  1167 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 18:35:16.355  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 18:35:16.355  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 18:35:16.375  1014  1040 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{3a70228c u-1 android.intent.action.BATTERY_CHANGED} to ReceiverList{2565b88 7412 com.android.bluetooth/1002/u0 remote:3d79b2b}: filter unregistered
,08-23 18:35:16.375  1014  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:16.375  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 18:35:16.375  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:16.375  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:16.375  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:16.375  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:16.375  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:16.375  7412  7427 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:16.375  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-23 18:35:16.375  1303  1303 D HeadsetProfile: Bluetooth service disconnected
,08-23 18:35:16.385  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:16.385  7412  7412 D A2dpService: Received stop request...Stopping profile...
08-23 18:35:16.385  7412  7455 D A2dpStateMachine: Exit Disconnected: -1
08-23 18:35:16.385  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 18:35:16.385  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:16.385  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:16.385  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 18:35:16.385  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 18:35:16.385  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 18:35:16.385  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 18:35:16.385  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-23 18:35:16.385  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 18:35:16.385  7412  7427 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-23 18:35:16.385  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:16.385  1014  1132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:16.385  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 18:35:16.385  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:16.385  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:16.385  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:16.385  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-23 18:35:16.385  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 18:35:16.385  7412  7427 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-23 18:35:16.385  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:16.385  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:16.385  7412  7427 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:16.385  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-23 18:35:16.385  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-23 18:35:16.385  7412  7427 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-23 18:35:16.385  7412  7427 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-23 18:35:16.385  7412  7427 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 18:35:16.385  7412  7427 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 18:35:16.385  7412  7427 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-23 18:35:16.395  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-23 18:35:16.395  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-23 18:35:16.395  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-23 18:35:16.395  1303  1303 D BluetoothA2dp: Proxy object disconnected
08-23 18:35:16.395  1303  1303 D A2dpProfile: Bluetooth service disconnected
,08-23 18:35:16.395  7412  7412 D HidService: Received stop request...Stopping profile...
,08-23 18:35:16.395  7412  7412 D HidService: Stopping Bluetooth HidService
08-23 18:35:16.395  7412  7412 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-23 18:35:16.395  7412  7412 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-23 18:35:16.395  7412  7412 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-23 18:35:16.395  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:16.395  7412  7412 D HealthService: Received stop request...Stopping profile...
,08-23 18:35:16.395  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:16.395  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-23 18:35:16.395  7412  7412 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-23 18:35:16.395  7412  7412 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-23 18:35:16.405  7412  7412 D PanService: Received stop request...Stopping profile...
08-23 18:35:16.405  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:16.405  1303  1303 D BluetoothInputDevice: Proxy object disconnected
08-23 18:35:16.405  1303  1303 D HidProfile: Bluetooth service disconnected
,08-23 18:35:16.405  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-23 18:35:16.405  1303  1303 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-23 18:35:16.405  1303  1303 D PanProfile: Bluetooth service disconnected
,08-23 18:35:16.405  7412  7412 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 18:35:16.405  7412  7412 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-23 18:35:16.405  7412  7412 D BluetoothMapService: Received stop request...Stopping profile...
,08-23 18:35:16.405  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:16.405  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-23 18:35:16.405  7412  7412 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 18:35:16.405  7412  7412 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-23 18:35:16.415  1303  1303 D BluetoothMap: Proxy object disconnected
08-23 18:35:16.415  1303  1303 D MapProfile: Bluetooth service disconnected
,08-23 18:35:16.415  7412  7412 D SapService: Received stop request...Stopping profile...
08-23 18:35:16.415  7412  7412 D SapService: Stopping Bluetooth SapService
,08-23 18:35:16.415  7412  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@224d820e
,08-23 18:35:16.415  7412  7456 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-23 18:35:16.415  7412  7412 I GKI_LINUX: GKI_exit_task 2 done
08-23 18:35:16.415  7412  7412 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-23 18:35:16.415  7412  7412 D BluetoothA2dp: Proxy object disconnected
08-23 18:35:16.415  7412  7412 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-23 18:35:16.415  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-23 18:35:16.415  7412  7412 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 18:35:16.415  7412  7412 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:16.415  1303  1303 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-23 18:35:16.415  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-23 18:35:16.415  7412  7412 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 18:35:16.415  7412  7412 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-23 18:35:16.415  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-23 18:35:16.415  7412  7412 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 18:35:16.415  7412  7412 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-23 18:35:16.415  7412  7412 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 18:35:16.415  7412  7412 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-23 18:35:16.415  7412  7412 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 18:35:16.415  7412  7412 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 18:35:16.415  1303  1303 D SapProfile: Bluetooth service disconnected
,08-23 18:35:16.415  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-23 18:35:16.415  7412  7412 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 18:35:16.415  7412  7412 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-23 18:35:16.415  7412  7412 E BluetoothAdapterService(575504910): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-23 18:35:16.415  7412  7412 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-23 18:35:16.415  7412  7412 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-23 18:35:16.415  7412  7427 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-23 18:35:16.425  7412  7427 D BluetoothAdapterProperties: Setting state to 10
08-23 18:35:16.425  7412  7427 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-23 18:35:16.425  7412  7427 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-23 18:35:16.425  7412  7427 D BluetoothAdapterService: updateAdapterState state is 10
,08-23 18:35:16.425  7412  7427 D BluetoothAdapterService: Autoconnection is available 
,08-23 18:35:16.425  7412  7427 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-23 18:35:16.425  7412  7427 I BluetoothAdapterState: Entering OffState
,08-23 18:35:16.425  1303  1316 D Bluetoothsap: onBluetoothStateChange: up=false
,08-23 18:35:16.425  1303  1316 D Bluetoothsap: Unbinding service...
,08-23 18:35:16.425  2025  2036 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 18:35:16.425  2025  2036 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:16.425  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 18:35:16.425  1303  6930 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-23 18:35:16.435  1303  1316 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 18:35:16.435  7461  7469 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 18:35:16.435  7461  7469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:16.435  1303  1312 D BluetoothMap: onBluetoothStateChange: up=false
,08-23 18:35:16.435  1303  6930 D BluetoothPbap: onBluetoothStateChange: up=false
,08-23 18:35:16.435  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 18:35:16.435  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:16.435  6794  6802 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 18:35:16.435  6794  6802 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:16.435  6794  6802 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-23 18:35:16.435  6794  6802 D BluetoothLeAdvertiser: Exit stop advertising
,08-23 18:35:16.435  6794  6802 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-23 18:35:16.435  6794  6802 D BluetoothLeScanner: Exiting stopAllScan
,08-23 18:35:16.435  1429  1437 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 18:35:16.435  1429  1437 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:16.445  1303  1312 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 18:35:16.445  1303  1312 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:16.445  7412  7520 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 18:35:16.445  1456  2453 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 18:35:16.445  1456  2453 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:16.445  1439  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 18:35:16.445  1439  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:16.445  1167  2343 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 18:35:16.445  1167  2343 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:16.445  7412  7425 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 18:35:16.445  7412  7425 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 18:35:16.445  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-23 18:35:16.455  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-23 18:35:16.455  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:16.455  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
,08-23 18:35:16.455  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-23 18:35:16.465  1167  1167 D BluetoothAdapter: 120810158: getState() :  mService = null. Returning STATE_OFF
,08-23 18:35:16.465  1167  1167 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 18:35:16.465  1167  1745 D BluetoothAdapter: 120810158: getState() :  mService = null. Returning STATE_OFF
,08-23 18:35:16.465  1167  1167 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:16.465  7412  7430 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-23 18:35:16.465  1167  1167 D BluetoothTile:  getBluetoothState : 10
,08-23 18:35:16.465  1167  1745 D BluetoothAdapter: 120810158: getState() :  mService = null. Returning STATE_OFF
08-23 18:35:16.465  7412  7412 I GKI_LINUX: GKI_exit_task 1 done
08-23 18:35:16.465  7412  7412 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-23 18:35:16.465  1167  1167 D BluetoothAdapter: 120810158: getState() :  mService = null. Returning STATE_OFF
08-23 18:35:16.465  1167  1167 D BluetoothAdapter: 120810158: getState() :  mService = null. Returning STATE_OFF
,08-23 18:35:16.465  7412  7412 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-23 18:35:16.465  1014  4757 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 18:35:16.465  2025  2219 D BluetoothAdapter: 692429084: getState() :  mService = null. Returning STATE_OFF
08-23 18:35:16.465  2025  2219 D BluetoothAdapter: 692429084: getState() :  mService = null. Returning STATE_OFF
,08-23 18:35:16.465  1014  1467 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-23 18:35:16.465  1872  1872 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 18:35:16.465  1167  1167 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 18:35:16.475  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:16.475  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:16.475  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:16.475  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 18:35:16.475  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 18:35:16.475  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:16.475  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:16.475  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:16.475  7412  7412 I art     : System.exit called, status: 0
08-23 18:35:16.475  7412  7412 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 18:35:16.485  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 18:35:16.485  1014  1474 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-23 18:35:16.485  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 18:35:16.485  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:16.485  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:16.485  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 18:35:16.495  1303  1303 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:35:16.495  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 18:35:16.505  1167  1167 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:16.505  1167  1167 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-23 18:35:16.505  1014  1477 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 18:35:16.505  1014  1477 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 18:35:16.515  1014  1477 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-23 18:35:16.515  1014  1477 W BroadcastQueue: android.os.TransactionTooLargeException
08-23 18:35:16.515  1014  1477 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 18:35:16.515  1014  1477 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 18:35:16.515  1014  1477 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-23 18:35:16.515  1014  1477 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-23 18:35:16.515  1014  1477 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-23 18:35:16.515  1014  1477 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-23 18:35:16.515  1014  1477 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-23 18:35:16.515  1014  1477 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-23 18:35:16.515  1014  1477 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 18:35:16.515  1014  1477 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-23 18:35:16.515  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:16.515  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:16.515  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:16.515  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:16.525  1014  1477 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7550 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-23 18:35:16.525  7550  7550 E Zygote  : MountEmulatedStorage()
08-23 18:35:16.525  7550  7550 I libpersona: KNOX_SDCARD checking this for 1002
08-23 18:35:16.525  7550  7550 E Zygote  : v2
08-23 18:35:16.525  7550  7550 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:16.535  7550  7550 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:16.535  7550  7550 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:16.535  7550  7550 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 18:35:16.555  7550  7550 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:16.555  7550  7550 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:16.565  7550  7550 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-23 18:35:16.565  7550  7550 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 18:35:16.595  7550  7550 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-23 18:35:16.625  7550  7550 D BtSettings.ProfileConfig: Adding GattService
,08-23 18:35:16.625  7550  7550 D BtSettings.ProfileConfig: Adding HeadsetService
,08-23 18:35:16.625  7550  7550 D BtSettings.ProfileConfig: Adding A2dpService
08-23 18:35:16.625  7550  7550 D BtSettings.ProfileConfig: Adding HidService
08-23 18:35:16.625  7550  7550 D BtSettings.ProfileConfig: Adding HealthService
,08-23 18:35:16.625  7550  7550 D BtSettings.ProfileConfig: Adding PanService
08-23 18:35:16.625  7550  7550 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-23 18:35:16.625  7550  7550 D BtSettings.ProfileConfig: Adding SapService
,08-23 18:35:16.625  7550  7550 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-23 18:35:16.635  7550  7550 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-23 18:35:16.635  7550  7550 D BtSettings.ProfileConfig: Adding SapClientService
,08-23 18:35:16.635  7550  7550 D BtSettings.ProfileConfig: Adding HidDevService
08-23 18:35:16.635  7550  7550 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-23 18:35:16.635  1014  4757 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-23 18:35:16.635  1014  4757 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:16.635  1014  4757 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:16.635  1014  4757 D SettingsProvider: selectionArgs: false
08-23 18:35:16.635  1014  4757 D SettingsProvider: selectionArgs: 1002
08-23 18:35:16.635  1014  4757 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:16.635  1014  4757 D SettingsProvider: ret = -1
,08-23 18:35:16.635  1014  1132 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-23 18:35:16.635  1014  1132 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 18:35:16.635  1014  1132 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:16.635  1014  1132 D SettingsProvider: selectionArgs: false
08-23 18:35:16.635  1014  1132 D SettingsProvider: selectionArgs: 1002
08-23 18:35:16.635  1014  1132 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:16.635  1014  1132 D SettingsProvider: ret = -1
,08-23 18:35:16.635  1014  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-23 18:35:16.635  1014  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:16.635  1014  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 18:35:16.635  1014  1474 D SettingsProvider: selectionArgs: false
08-23 18:35:16.635  1014  1474 D SettingsProvider: selectionArgs: 1002
08-23 18:35:16.635  1014  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:16.635  1014  1474 D SettingsProvider: ret = -1
,08-23 18:35:16.635  1014  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-23 18:35:16.635  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:16.635  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 18:35:16.635  1014  1479 D SettingsProvider: selectionArgs: false
08-23 18:35:16.635  1014  1479 D SettingsProvider: selectionArgs: 1002
08-23 18:35:16.635  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:16.635  1014  1479 D SettingsProvider: ret = -1
,08-23 18:35:16.635  1014  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-23 18:35:16.635  1014  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:16.635  1014  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 18:35:16.635  1014  1319 D SettingsProvider: selectionArgs: false
08-23 18:35:16.635  1014  1319 D SettingsProvider: selectionArgs: 1002
08-23 18:35:16.635  1014  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:16.635  1014  1319 D SettingsProvider: ret = -1
,08-23 18:35:16.635  1014  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-23 18:35:16.635  1014  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:16.635  1014  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:16.635  1014  1478 D SettingsProvider: selectionArgs: false
,08-23 18:35:16.635  1014  1478 D SettingsProvider: selectionArgs: 1002
08-23 18:35:16.635  1014  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:16.635  1014  1478 D SettingsProvider: ret = -1
08-23 18:35:16.645  1014  1251 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:16.645  1014  1251 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:16.645  1014  1251 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:16.645  1014  1251 D SettingsProvider: selectionArgs: false
,08-23 18:35:16.645  1014  1251 D SettingsProvider: selectionArgs: 1002
08-23 18:35:16.645  1014  1251 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 18:35:16.645  1014  1251 D SettingsProvider: ret = -1
08-23 18:35:16.645  1014  1477 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-23 18:35:16.645  1014  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:16.645  1014  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:16.645  1014  1477 D SettingsProvider: selectionArgs: false
,08-23 18:35:16.645  1014  1477 D SettingsProvider: selectionArgs: 1002
,08-23 18:35:16.645  1014  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:16.645  1014  1477 D SettingsProvider: ret = -1
08-23 18:35:16.645  1014  1800 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-23 18:35:16.645  1014  1800 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 18:35:16.645  1014  1800 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:16.645  1014  1800 D SettingsProvider: selectionArgs: false
08-23 18:35:16.645  1014  1800 D SettingsProvider: selectionArgs: 1002
08-23 18:35:16.645  1014  1800 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-23 18:35:16.645  1014  1800 D SettingsProvider: ret = -1
08-23 18:35:16.645  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-23 18:35:16.645  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:16.645  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 18:35:16.645  1014  1026 D SettingsProvider: selectionArgs: false
08-23 18:35:16.645  1014  1026 D SettingsProvider: selectionArgs: 1002
08-23 18:35:16.645  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 18:35:16.645  1014  1026 D SettingsProvider: ret = -1
08-23 18:35:16.645  1014  4756 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-23 18:35:16.645  1014  4756 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:16.645  1014  4756 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:16.645  1014  4756 D SettingsProvider: selectionArgs: false
08-23 18:35:16.645  1014  4756 D SettingsProvider: selectionArgs: 1002
08-23 18:35:16.645  1014  4756 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:16.645  1014  4756 D SettingsProvider: ret = -1
08-23 18:35:16.645  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-23 18:35:16.645  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:16.645  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:16.645  1014  1027 D SettingsProvider: selectionArgs: false
08-23 18:35:16.645  1014  1027 D SettingsProvider: selectionArgs: 1002
08-23 18:35:16.645  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:16.645  1014  1027 D SettingsProvider: ret = -1
,08-23 18:35:16.655  2025  2025 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:16.665  1014  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 18:35:16.665  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-23 18:35:16.665  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:16.665  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:16.665  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:16.665  2025  7566 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-23 18:35:16.665  2025  2025 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 18:35:16.675  1014  1132 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 18:35:16.675  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:16.675  1014  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:16.675  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:16.685  2025  7566 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-23 18:35:17.095   287   287 E SMD     : DCD OFF
,08-23 18:35:17.685  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 18:35:17.685  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:17.905  1014  1047 I PowerManagerService: [PWL] Off : 75s ago
,08-23 18:35:17.905  1014  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-23 18:35:17.905  1014  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-23 18:35:17.905  1014  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=14908)
,08-23 18:35:18.355  1014  1314 E Watchdog: !@Sync 4,
,08-23 18:35:19.115   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 18:35:20.095   287   287 E SMD     : DCD OFF,
,08-23 18:35:20.105   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 18:35:20.685  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:35:20.685  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f02321b added. We now have 6 listener(s)
,08-23 18:35:20.685  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:20.685  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:35:20.685  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b15bfb8 added. We now have 7 listener(s)
,08-23 18:35:20.685  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:20.685  6794  6848 I System.out: IsBluetoothEnabled
,08-23 18:35:20.695  6794  6848 D BluetoothAdapter: disable()
,08-23 18:35:20.695  1014  4757 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-23 18:35:20.695  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:20.695  6794  6848 D BluetoothAdapter: enable()
,08-23 18:35:20.695  1014  1251 W ActivityManager: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-23 18:35:20.705  1014  1251 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-23 18:35:20.705  1014  1251 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 18:35:20.705  1014  1251 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 18:35:20.705  1014  1251 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-23 18:35:20.705  1014  1251 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-23 18:35:20.705  1014  1251 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-23 18:35:20.705  1014  1251 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 18:35:20.705  1014  1251 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 18:35:20.705  1014  1251 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 18:35:20.705  1014  1251 D SettingsProvider: name = bluetooth_on
,08-23 18:35:20.715  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-23 18:35:20.715  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 18:35:20.715  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-23 18:35:20.715  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-23 18:35:20.735  7550  7550 D BluetoothAdapterState: make
,08-23 18:35:20.735  7550  7550 I bluedroid: init
,08-23 18:35:20.745  7550  7571 I BluetoothAdapterState: Entering OffState
,08-23 18:35:20.745  7550  7550 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-23 18:35:20.745  7550  7550 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-23 18:35:20.745  7550  7550 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 18:35:20.745  7550  7550 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-23 18:35:20.745  7550  7550 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-23 18:35:20.745  7550  7550 I bluedroid: get_profile_interface socket
08-23 18:35:20.745  7550  7550 I bluedroid: get_profile_interface map_client
,08-23 18:35:20.745  7550  7574 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-23 18:35:20.745  7550  7550 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-23 18:35:20.755  7550  7574 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-23 18:35:20.755  7550  7574 E BluetoothServiceJni: populateRssiValuesNative
,08-23 18:35:20.755  7550  7574 I bluedroid: getModelRssiValues
,08-23 18:35:20.755  7550  7574 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-23 18:35:20.755  7550  7574 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-23 18:35:20.755  7550  7550 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:20.755  1014  1474 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-23 18:35:20.755  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 18:35:20.755  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:20.755  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:20.755  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:20.765  7550  7574 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-23 18:35:20.765  1014  1014 D SettingsProvider: name = bluetooth_name
,08-23 18:35:20.765  7550  7558 I bluedroid: config_hci_snoop_log
,08-23 18:35:20.765  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-23 18:35:20.765  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-23 18:35:20.765  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-23 18:35:20.765  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-23 18:35:20.765  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-23 18:35:20.775  7550  7550 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-23 18:35:20.785  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 18:35:20.785  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 18:35:20.785  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-23 18:35:20.785  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-23 18:35:20.785  7550  7571 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-23 18:35:20.785  7550  7571 D BluetoothAdapterProperties: Setting state to 11
08-23 18:35:20.785  7550  7571 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-23 18:35:20.785  7550  7571 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 18:35:20.785  7550  7571 D BluetoothAdapterService: updateAdapterState state is 11
08-23 18:35:20.785  7550  7571 D BluetoothAdapterService: Autoconnection is available 
,08-23 18:35:20.785  7550  7571 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-23 18:35:20.795  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-23 18:35:20.795  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-23 18:35:20.795  7550  7571 D BluetoothSecureManager: getInstant: null
08-23 18:35:20.795  7550  7571 D BluetoothSecureManager: calling getMethod for getService
08-23 18:35:20.795  7550  7571 D BluetoothSecureManager: calling getService
,08-23 18:35:20.795  7550  7571 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@206d467d
,08-23 18:35:20.795  1014  1026 D BluetoothSecureManagerService: isSecureModeEnabled
08-23 18:35:20.795  1014  1026 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-23 18:35:20.795  7550  7571 D BtConfig.SecureMode: isSecureModeOn:false
08-23 18:35:20.795  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-23 18:35:20.795  7550  7571 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-23 18:35:20.795  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-23 18:35:20.795  7550  7571 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-23 18:35:20.795  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-23 18:35:20.795  7550  7571 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-23 18:35:20.795  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-23 18:35:20.805  1167  1167 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-23 18:35:20.805  1167  1167 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:20.805  1167  1167 D BluetoothTile:  getBluetoothState : 11
,08-23 18:35:20.805  7550  7571 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-23 18:35:20.805  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-23 18:35:20.805  7550  7571 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-23 18:35:20.805  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-23 18:35:20.805  1872  1872 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 18:35:20.805  7550  7571 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-23 18:35:20.805  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:20.805  1014  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 18:35:20.805  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:20.805  1014  1478 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 18:35:20.805  1167  1167 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 18:35:20.815  7550  7571 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-23 18:35:20.815  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-23 18:35:20.815  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:20.815  7550  7571 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-23 18:35:20.815  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 18:35:20.815  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
08-23 18:35:20.815  7550  7571 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 18:35:20.815  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-23 18:35:20.815  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-23 18:35:20.815  7550  7571 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:20.815  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-23 18:35:20.815  7550  7571 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-23 18:35:20.815  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-23 18:35:20.815  7550  7571 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-23 18:35:20.815  7550  7571 D BluetoothBondStateMachine: make
,08-23 18:35:20.815  1014  4756 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 18:35:20.815  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 18:35:20.815  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:20.815  1014  4756 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 18:35:20.815  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:20.815  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-23 18:35:20.815  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-23 18:35:20.815  7550  7571 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-23 18:35:20.825  7550  7577 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 18:35:20.825  1014  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:20.825  1014  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-23 18:35:20.825  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
08-23 18:35:20.825  1014  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:20.825  1014  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:20.825  1014  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:20.825  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-23 18:35:20.825  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-23 18:35:20.825  7550  7571 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-23 18:35:20.825  7550  7550 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 18:35:20.825  7550  7550 D BtGatt.GattService: Received start request. Starting profile...
08-23 18:35:20.825  7550  7550 D BtGatt.GattService: start()
08-23 18:35:20.825  7550  7550 D BtGatt.GattService: start()
08-23 18:35:20.825  7550  7550 I bluedroid: get_profile_interface gatt
,08-23 18:35:20.835  7550  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ebeda3c
08-23 18:35:20.835  7550  7550 D BtGatt.AdvertiseManager: advertise manager created
,08-23 18:35:20.835  1167  1167 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:20.835  1167  1167 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-23 18:35:20.835  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:20.835  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-23 18:35:20.835  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:20.835  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:20.835  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:20.835  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-23 18:35:20.835  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-23 18:35:20.835  7550  7571 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-23 18:35:20.835  1014  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:20.835  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 18:35:20.845  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:20.845  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:20.845  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:20.845  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-23 18:35:20.845  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 18:35:20.845  7550  7571 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-23 18:35:20.845  1014  1800 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:20.845  1014  1800 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 18:35:20.845  1014  1800 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:20.855  1014  1800 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:20.855  1014  1800 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:20.855  7550  7550 D BtGatt.GattService: mStartError = false
,08-23 18:35:20.855  7550  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ebeda3c
,08-23 18:35:20.855  7550  7550 D HeadsetService: Received start request. Starting profile...
,08-23 18:35:20.855  7550  7550 D HeadsetService: start()
,08-23 18:35:20.855  7550  7550 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-23 18:35:20.855  7550  7550 D HeadsetStateMachine: make
,08-23 18:35:20.855  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-23 18:35:20.855  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-23 18:35:20.855  7550  7571 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-23 18:35:20.865  1014  4757 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:20.865  1014  4757 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-23 18:35:20.865  1014  4757 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:20.865  1014  4757 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:20.865  1014  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:20.865  7550  7550 E HeadsetStateMachine: # of Max HF connection is 2
,08-23 18:35:20.865  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-23 18:35:20.865  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-23 18:35:20.865  7550  7571 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-23 18:35:20.865  1014  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:20.865  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 18:35:20.865  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:20.865  1014  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:20.865  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:20.865  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:20.875  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 18:35:20.875  7550  7571 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-23 18:35:20.875  1014  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:20.875  1014  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 18:35:20.875  1014  1467 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:20.875  1014  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:20.875  1014  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:20.885  1014  1026 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-23 18:35:20.885  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-23 18:35:20.885  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:20.885  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:20.885  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-23 18:35:20.885  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-23 18:35:20.885  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-23 18:35:20.885  7550  7571 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-23 18:35:20.885  1014  1132 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-23 18:35:20.885  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-23 18:35:20.885  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:20.885  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:20.885  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-23 18:35:20.885  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 18:35:20.885  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 18:35:20.895  7550  7550 I bluedroid: get_profile_interface handsfree
,08-23 18:35:20.895  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:20.895  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:20.895  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:20.895  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 18:35:20.895  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 18:35:20.895  7550  7571 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 18:35:20.895  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:20.895  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:20.895  7550  7571 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-23 18:35:20.895  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,08-23 18:35:20.895  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-23 18:35:20.895  7550  7571 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-23 18:35:20.895  7550  7571 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-23 18:35:20.895  7550  7571 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 18:35:20.895  7550  7571 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 18:35:20.895  7550  7571 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-23 18:35:20.905  7550  7550 I DualScoManager: Instantiating Dual Sco Manager
,08-23 18:35:20.905  7550  7550 I DualScoManager: Set HeadsetServiceHelper
,08-23 18:35:20.905  7550  7550 D BluetoothAtMessage: createCMTIContentObservers
,08-23 18:35:20.905  1014  1479 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-23 18:35:20.905  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:20.905  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:20.905  1014  1479 D SettingsProvider: selectionArgs: false
08-23 18:35:20.905  1014  1479 D SettingsProvider: selectionArgs: 1002
08-23 18:35:20.905  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:20.905  1014  1479 D SettingsProvider: ret = -1
,08-23 18:35:20.915  7550  7581 D HeadsetStateMachine: Enter Disconnected: -2
,08-23 18:35:20.915  7550  7550 D HeadsetService: mStartError = false
08-23 18:35:20.915  7550  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ebeda3c
,08-23 18:35:20.915  7550  7581 D HeadsetStateMachine: Clear mHeadsetBrsf
08-23 18:35:20.915  7550  7581 D HeadsetStateMachine: map size, before remove : 0
08-23 18:35:20.915  7550  7581 D HeadsetStateMachine: map size, after remove: 0
,08-23 18:35:20.915  7550  7550 D A2dpService: Received start request. Starting profile...
08-23 18:35:20.915  7550  7550 D A2dpService: start()
,08-23 18:35:20.915  7550  7550 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-23 18:35:20.915  7550  7550 I bluedroid: get_profile_interface avrcp
,08-23 18:35:20.925  7550  7550 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 18:35:20.925  7550  7550 D Avrcp   : Initialize Media Controller
,08-23 18:35:20.925  7550  7550 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-23 18:35:20.925  7550  7550 E Avrcp   : getActiveSessions
,08-23 18:35:20.925  7550  7550 D Avrcp   : pick active media Controller
,08-23 18:35:20.925  7550  7550 D Avrcp   : Get the active Media Controller 
,08-23 18:35:20.945  7550  7550 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-23 18:35:20.945  7550  7585 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-23 18:35:20.945  7550  7550 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 18:35:20.945  7550  7550 D A2dpStateMachine: make
,08-23 18:35:20.945  7550  7550 I bluedroid: get_profile_interface a2dp
08-23 18:35:20.945  7550  7587 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-23 18:35:20.955  7550  7550 E bt-btif : warning : media task started media_task_refcnt 1 
,08-23 18:35:20.955  7550  7550 D A2dpService: mStartError = false
08-23 18:35:20.955  7550  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ebeda3c
,08-23 18:35:20.955  7550  7550 E BluetoothAdapterService(784259644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-23 18:35:20.955  7550  7586 D A2dpStateMachine: Enter Disconnected: -2
08-23 18:35:20.955  7550  7550 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 18:35:20.955  7550  7550 D HidService: Received start request. Starting profile...
08-23 18:35:20.955  7550  7550 D HidService: start()
08-23 18:35:20.955  7550  7550 I bluedroid: get_profile_interface hidhost
08-23 18:35:20.955  7550  7550 D HidService: setHidService(): set to: null
08-23 18:35:20.955  7550  7550 D HidService: mStartError = false
08-23 18:35:20.955  7550  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ebeda3c
,08-23 18:35:20.955  7550  7550 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-23 18:35:20.965  7550  7550 D HealthService: Received start request. Starting profile...
08-23 18:35:20.965  7550  7550 D HealthService: start()
,08-23 18:35:20.965  7550  7585 D BluetoothMediaBrowser: no now playing list
,08-23 18:35:20.965  7550  7585 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-23 18:35:20.965  7550  7550 I bluedroid: get_profile_interface health
08-23 18:35:20.965  7550  7550 D HealthService: mStartError = false
08-23 18:35:20.965  7550  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ebeda3c
,08-23 18:35:20.965  7550  7550 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-23 18:35:20.965  7550  7550 D PanService: Received start request. Starting profile...
,08-23 18:35:20.965  7550  7550 D PanService: start()
,08-23 18:35:20.965  7550  7550 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 18:35:20.965  7550  7550 I bluedroid: get_profile_interface pan
,08-23 18:35:20.965  7550  7550 D PanService: mStartError = false
,08-23 18:35:20.965  7550  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ebeda3c
,08-23 18:35:20.975  7550  7550 D BluetoothMapService: Received start request. Starting profile...
08-23 18:35:20.975  7550  7550 D BluetoothMapService: start()
,08-23 18:35:20.975  7550  7550 D BluetoothMapService: mStartError = false
08-23 18:35:20.975  7550  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ebeda3c
,08-23 18:35:20.975  7550  7550 D HeadsetStateMachine: Try to query the phonestate on bind
,08-23 18:35:20.975  1429  7543 I Telecom : BluetoothPhoneService: queryPhoneState
,08-23 18:35:20.975  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-23 18:35:20.975  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-23 18:35:20.975  1429  7543 I Telecom : BluetoothPhoneService: Result of Message : true
,08-23 18:35:20.975  7550  7550 D HeadsetStateMachine: Proxy object connected
,08-23 18:35:20.975  7550  7550 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-23 18:35:20.985  7550  7550 D SapService: Received start request. Starting profile...
08-23 18:35:20.985  7550  7550 D SapService: start()
08-23 18:35:20.985  7550  7550 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-23 18:35:20.985  7550  7550 I bluedroid: get_profile_interface sap
08-23 18:35:20.985  7550  7550 D SapService: mStartError = false
08-23 18:35:20.985  7550  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ebeda3c
08-23 18:35:20.985  7550  7550 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-23 18:35:20.985  7550  7550 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-23 18:35:20.985  7550  7550 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-23 18:35:20.985  7550  7550 E BluetoothAdapterService(784259644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-23 18:35:20.985  7550  7550 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 18:35:20.985  7550  7550 D BluetoothA2dp: Proxy object connected
08-23 18:35:20.985  7550  7550 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-23 18:35:20.985  7550  7550 E BluetoothAdapterService(784259644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-23 18:35:20.985  7550  7550 E BluetoothAdapterService(784259644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-23 18:35:20.985  7550  7581 D HeadsetStateMachine: Disconnected process message: 11
,08-23 18:35:20.985  7550  7550 E BluetoothAdapterService(784259644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-23 18:35:20.985  7550  7550 E BluetoothAdapterService(784259644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-23 18:35:20.985  7550  7581 D HeadsetStateMachine: Disconnected process message: 18
08-23 18:35:20.985  7550  7581 D HeadsetStateMachine: Disconnected process message: 10
,08-23 18:35:20.985  7550  7581 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 18:35:20.985  7550  7581 D HeadsetStateMachine: Disconnected process message: 11
,08-23 18:35:20.985  2025  2025 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:20.995  2025  2025 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 18:35:21.015  7550  7550 E BluetoothAdapterService(784259644): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-23 18:35:21.015  7550  7550 E BluetoothAdapterService(784259644): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-23 18:35:21.015  7550  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-23 18:35:21.015  7550  7571 I bluedroid: enable
,08-23 18:35:21.015  7550  7571 I bt_hci_bdroid: init
,08-23 18:35:21.025  7550  7592 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-23 18:35:21.025  7550  7571 I bt_vendor: bt-vendor : init
08-23 18:35:21.025  7550  7571 I bt_vendor: bt-vendor : get_bt_soc_type
,08-23 18:35:21.025  7550  7571 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-23 18:35:21.025  7550  7571 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-23 18:35:21.025  7550  7571 D bt_userial_mct: userial_init
08-23 18:35:21.025  7550  7571 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 18:35:21.025  7550  7571 I bt_vendor: Starting hciattach daemon
08-23 18:35:21.025  7550  7571 I bt_vendor: try to set false
,08-23 18:35:21.025  7550  7571 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-23 18:35:21.025  7550  7571 I bt_vendor: Starting hciattach daemon
08-23 18:35:21.025  7550  7571 I bt_vendor: try to set true
,08-23 18:35:21.045  7597  7597 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-23 18:35:21.095  7603  7603 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-23 18:35:21.105  7604  7604 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-23 18:35:21.105   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 18:35:21.115  7606  7606 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 18:35:21.125  7607  7607 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-23 18:35:21.135  7608  7608 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 18:35:21.135  7609  7609 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-23 18:35:21.415  7612  7612 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-23 18:35:21.425  7613  7613 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-23 18:35:21.485  1014  3364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 18:35:21.485  7550  7571 I bt_vendor: bluetooth satus is on,
08-23 18:35:21.485  7550  7594 D bt_userial_mct: userial_open(port:0)
08-23 18:35:21.485  7550  7594 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,08-23 18:35:21.485  7550  7594 I bt_vendor: Done intiailizing UART,
,08-23 18:35:21.485  7550  7594 I bt_vendor: Done intiailizing UART
,08-23 18:35:21.485  7550  7594 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-23 18:35:21.485  7550  7594 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-23 18:35:21.485  7550  7615 D bt_userial_mct: Entering userial_read_thread()
,08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_HCI
,08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_AVDT
08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_BTM
,08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_PAN
,08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_SAP
08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_SDP
,08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_SMP
,08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 18:35:21.495  7550  7592 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-23 18:35:21.595  7550  7592 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-23 18:35:21.595  7550  7592 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41b2ed1 
,08-23 18:35:21.595  7550  7592 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41b2ed1 
,08-23 18:35:21.615  7550  7574 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-23 18:35:21.615  7550  7574 E bt-btif : Calling BTA_HhEnable
,08-23 18:35:21.615  7550  7574 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-23 18:35:21.615  7550  7574 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-23 18:35:21.615  7550  7574 E BluetoothServiceJni: populateRssiValuesNative
08-23 18:35:21.615  7550  7574 I bluedroid: getModelRssiValues
,08-23 18:35:21.625  7550  7574 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-23 18:35:21.625  7550  7574 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-23 18:35:21.625  1014  1014 D SettingsProvider: name = bluetooth_name
,08-23 18:35:21.625  7550  7574 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-23 18:35:21.635  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:21.635  7550  7574 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-23 18:35:21.635  7550  7574 D BluetoothAdapterProperties: Scan Mode:20
,08-23 18:35:21.635  7550  7574 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 18:35:21.635  7550  7574 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-23 18:35:21.635  7550  7574 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-23 18:35:21.635  7550  7574 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-23 18:35:21.635  7550  7574 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-23 18:35:21.635  7550  7574 E bt-btif : btif_sock_init: !vhci_init,
08-23 18:35:21.635  7550  7574 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-23 18:35:21.645  7550  7615 E bt_mct  : hci lib postload completed
,08-23 18:35:21.645  7550  7574 D IOP_DB_BT: db_open: db_open : handle 3028197392l, read 13894 bytes onto local cache
,08-23 18:35:21.645  7550  7574 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-23 18:35:21.645  7550  7574 D IOP_DB_BT: db_query: result 1
,08-23 18:35:21.645  7550  7574 I         : iop_db_open: iop_db_open status 0
,08-23 18:35:21.645  7550  7574 D bte_conf: Device ID record 1 : primary
,08-23 18:35:21.645  7550  7574 D bte_conf:   vendorId            = 0075
,08-23 18:35:21.645  7550  7574 D bte_conf:   vendorIdSource      = 0001
08-23 18:35:21.645  7550  7574 D bte_conf:   product             = 0100
,08-23 18:35:21.645  7550  7574 D bte_conf:   version             = 0200
08-23 18:35:21.645  7550  7574 D bte_conf:   clientExecutableURL = 
08-23 18:35:21.645  7550  7574 D bte_conf:   serviceDescription  = 
08-23 18:35:21.645  7550  7574 D bte_conf:   documentationURL    = 
08-23 18:35:21.645  7550  7574 D bte_conf: bte_load_did_conf no section named DID2.
08-23 18:35:21.645  7550  7574 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-23 18:35:21.645  7550  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-23 18:35:21.645  7550  7571 D BluetoothAdapterProperties: ScanMode =  20
08-23 18:35:21.645  7550  7571 D BluetoothAdapterProperties: State =  11
,08-23 18:35:21.645  1014  1478 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 18:35:21.655  7550  7571 D BluetoothAdapterProperties: Setting state to 12
08-23 18:35:21.655  7550  7571 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-23 18:35:21.655  7550  7574 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-23 18:35:21.655  7550  7574 D BluetoothAdapterProperties: Scan Mode:21
08-23 18:35:21.655  7550  7574 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 18:35:21.665  1014  1319 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-23 18:35:21.665  1014  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:21.665  1014  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:21.665  1014  1319 D SettingsProvider: selectionArgs: false
08-23 18:35:21.665  1014  1319 D SettingsProvider: selectionArgs: 1002
08-23 18:35:21.665  1014  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:21.665  1014  1319 D SettingsProvider: ret = -1
,08-23 18:35:21.665  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:21.665  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:21.665  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:21.665  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:21.665  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:21.665  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:21.665  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:21.665  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:21.665  7550  7571 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 18:35:21.665  7550  7571 D BluetoothAdapterService: updateAdapterState state is 12
,08-23 18:35:21.665  1014  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:21.665  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 18:35:21.665  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:21.665  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:21.665  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.665  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:21.685  7550  7571 D BluetoothAdapterService: Autoconnection is available 
08-23 18:35:21.685  7550  7571 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-23 18:35:21.685  7550  7571 D BluetoothAdapterService: starting service from this receiver
,08-23 18:35:21.685  1014  4757 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:21.685  1429  3267 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
08-23 18:35:21.685  1014  4757 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-23 18:35:21.685  1014  4757 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.685  1014  4757 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.685  1014  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:21.685  7550  7571 I BluetoothAdapterState: Entering On State from state = 11
,08-23 18:35:21.685  7550  7550 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-23 18:35:21.695  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 18:35:21.695  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 18:35:21.695  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.695  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.695  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:21.695  1429  3267 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 18:35:21.695  1303  1312 D Bluetoothsap: onBluetoothStateChange: up=true
,08-23 18:35:21.695  1303  1312 D Bluetoothsap: Binding service...
,08-23 18:35:21.695  1303  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-23 18:35:21.705  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-23 18:35:21.705  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 18:35:21.705  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.705  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.705  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:21.705  1303  1312 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-23 18:35:21.705  2025  2036 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 18:35:21.705  2025  2036 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:21.705  7550  7550 I BluetoothPbapService: Handler(): got msg=1
,08-23 18:35:21.705  1014  1479 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-23 18:35:21.715  1303  6930 D BluetoothPan: Binding service...
,08-23 18:35:21.715  1303  1303 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-23 18:35:21.715  7550  7619 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-23 18:35:21.715  1303  1303 D SapProfile: Bluetooth service connected
08-23 18:35:21.715  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-23 18:35:21.715  1303  1303 D Bluetoothsap: getConnectedDevices()
08-23 18:35:21.715  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 18:35:21.715  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.715  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.715  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:21.725  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 18:35:21.725  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:21.725  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-23 18:35:21.725  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-23 18:35:21.725  7550  7619 D BluetoothSocket: bindListen(): myUserId = 0
08-23 18:35:21.725  1014  1014 D BluetoothA2dp: Proxy object connected
,08-23 18:35:21.725  7550  7619 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 18:35:21.725  1303  1316 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 18:35:21.725  7550  7619 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
,08-23 18:35:21.725  7550  7619 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 18:35:21.725  1303  1303 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 18:35:21.725  7550  7619 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 18:35:21.725  7550  7619 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@237634f6
08-23 18:35:21.725  7550  7619 D BluetoothSocket: channel: 19
08-23 18:35:21.725  7550  7619 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-23 18:35:21.725  1303  1303 D PanProfile: Bluetooth service connected
08-23 18:35:21.725  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:21.725  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:21.725  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:21.725  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:35:21.725  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:21.725  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:21.725  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:21.725  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:35:21.725  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-23 18:35:21.725  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 18:35:21.735  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:21.735  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:21.735  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38fce191 added. We now have 8 listener(s)
08-23 18:35:21.735  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:21.735  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.735  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.735  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:21.735  7550  7575 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 18:35:21.735  1303  1303 D BluetoothInputDevice: Proxy object connected
08-23 18:35:21.735  1303  1312 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 18:35:21.735  1303  1303 D HidProfile: Bluetooth service connected
,08-23 18:35:21.735  1014  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-23 18:35:21.735  1014  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 18:35:21.735  1014  1026 D SecContentProvider2: mCursor = null
,08-23 18:35:21.735  1303  1312 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:21.735  1014  1026 D WifiService: setWifiEnabled: false pid=6794, uid=10171
,08-23 18:35:21.735  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-23 18:35:21.735  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 18:35:21.745  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.745  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.745  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:21.745  1014  1026 D SettingsProvider: name = wifi_on
,08-23 18:35:21.745  7461  7470 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:21.745  7461  7470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:21.745  1303  1303 D BluetoothA2dp: Proxy object connected
,08-23 18:35:21.745  1303  1303 D A2dpProfile: Bluetooth service connected
,08-23 18:35:21.745  1456  2453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:21.745  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 18:35:21.745  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 18:35:21.745  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.745  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.745  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:21.745  1456  2453 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 18:35:21.755  1429  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:21.755  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:21.755  1014  1474 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-23 18:35:21.755  1014  1474 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-23 18:35:21.755  1014  1474 D SecContentProvider2: mCursor = null
,08-23 18:35:21.755  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 18:35:21.755  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.755  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-23 18:35:21.755  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.755  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-23 18:35:21.755  1429  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 18:35:21.755  1303  1316 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 18:35:21.755  1014  1474 D WifiService: setWifiEnabled: true pid=6794, uid=10171
,08-23 18:35:21.755  1014  1474 W ActivityManager: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-23 18:35:21.755  1014  1474 W WifiService: Failed getting userId using ActivityManagerNative
08-23 18:35:21.755  1014  1474 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 18:35:21.755  1014  1474 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 18:35:21.755  1014  1474 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-23 18:35:21.755  1014  1474 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-23 18:35:21.755  1014  1474 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-23 18:35:21.755  1014  1474 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 18:35:21.755  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-23 18:35:21.755  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 18:35:21.755  1014  1474 D SettingsProvider: name = wifi_on
08-23 18:35:21.755  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.755  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.755  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-23 18:35:21.755  1303  6930 D BluetoothPbap: onBluetoothStateChange: up=true
,08-23 18:35:21.775  1014  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-23 18:35:21.915  1014  1044 I art     : Explicit concurrent mark sweep GC freed 19729(1152KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.531ms total 152.574ms
08-23 18:35:21.915  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-23 18:35:21.915  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 18:35:21.915  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.915  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.915  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:21.915  1303  1312 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:21.915  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 18:35:21.915  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 18:35:21.915  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.915  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.915  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-23 18:35:21.915  1303  1303 D BluetoothMap: Proxy object connected
08-23 18:35:21.915  1303  1303 D MapProfile: Bluetooth service connected
08-23 18:35:21.915  1303  1303 D BluetoothMap: getConnectedDevices()
,08-23 18:35:21.915  1303  1312 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 18:35:21.925  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:21.925  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:21.925  6794  6806 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:21.925  6794  6806 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 18:35:21.925  1429  1440 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:21.925  1303  1303 D BluetoothPbap: Proxy object connected
08-23 18:35:21.925  1303  1303 D PbapServerProfile: Bluetooth service connected
08-23 18:35:21.925  1303  1303 D HeadsetProfile: Bluetooth service connected
,08-23 18:35:21.925  1429  1440 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:21.925  1303  6930 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:21.925  1303  6930 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 18:35:21.925  7550  7562 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:21.925  7550  7562 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:21.925  1456  1862 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 18:35:21.925  1456  1862 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 18:35:21.925  1439  1789 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:21.925  1439  1789 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:21.925  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 18:35:21.925  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 18:35:21.925  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-23 18:35:21.925  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
08-23 18:35:21.925  1014  1044 D BluetoothPan: Binding service...
08-23 18:35:21.925  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-23 18:35:21.925  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 18:35:21.925  1167  5633 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 18:35:21.925  1167  5633 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 18:35:21.925  1429  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
,08-23 18:35:21.935  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 18:35:21.935  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-23 18:35:21.935  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-23 18:35:21.935  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.935  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:21.935  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:21.935  1429  1437 E BluetoothHeadset: BluetoothHeadset service is binded
08-23 18:35:21.935  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-23 18:35:21.935  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-23 18:35:21.935  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:21.935  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-23 18:35:21.935  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-23 18:35:21.945  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@e33c75d, true
,08-23 18:35:21.945  1167  1167 D BluetoothTile:  onBluetoothStateChange:
,08-23 18:35:21.945  1429  1429 D BluetoothHeadset: registerMessageListener
,08-23 18:35:21.945  1167  1167 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-23 18:35:21.945  1167  1167 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:21.945  1167  1167 D BluetoothTile:  getBluetoothState : 12
,08-23 18:35:21.945  1872  1872 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 18:35:21.955  1303  1303 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:35:21.955  1014  1467 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 18:35:21.955  1014  1478 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-23 18:35:21.955  1014  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 18:35:21.955  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 18:35:21.955  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:21.955  1014  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:21.955  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:21.965  1167  1167 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-23 18:35:21.965  7550  7576 D HeadsetService: registerMessageListener
,08-23 18:35:21.965  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:21.965  7550  7576 D HeadsetService: registerMessageListener
,08-23 18:35:21.965  1303  1303 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-23 18:35:21.965  1303  1303 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-23 18:35:21.965  1303  1303 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-23 18:35:21.965  1303  1303 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-23 18:35:21.965  7550  7581 D HeadsetStateMachine: Disconnected process message: 70
08-23 18:35:21.965  7550  7581 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@9bbb0f7
,08-23 18:35:21.965  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-23 18:35:21.965  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-23 18:35:21.965  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 18:35:21.975  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-23 18:35:21.975  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-23 18:35:21.975  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-23 18:35:21.975  7550  7625 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-23 18:35:21.975  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 18:35:21.975  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 18:35:21.975  1167  1745 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 18:35:21.975  1014  4757 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-23 18:35:21.975  7550  7581 D HeadsetStateMachine: Disconnected process message: 9
,08-23 18:35:21.975  7550  7581 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-23 18:35:21.975  1014  4757 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-23 18:35:21.975  7550  7625 D BluetoothSocket: bindListen(): myUserId = 0
08-23 18:35:21.975  7550  7625 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 18:35:21.985  1014  4757 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:21.985  1014  4757 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:21.985  1014  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 18:35:21.985  7550  7625 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-23 18:35:21.985  7550  7625 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 18:35:21.985  7550  7625 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 18:35:21.985  7550  7625 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2adfcb64
,08-23 18:35:21.985  7550  7625 D BluetoothSocket: channel: 5
,08-23 18:35:21.995   282   682 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false,
08-23 18:35:21.995   282   682 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-23 18:35:21.995   282   682 V voice   : voice_set_parameters: exit with code(-2)
08-23 18:35:21.995   282   682 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-23 18:35:21.995   282   682 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-23 18:35:21.995   282   682 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-23 18:35:21.995   282   682 V audio_hw_primary: adev_set_parameters: exit
,08-23 18:35:21.995  7550  7581 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-23 18:35:21.995  1303  1303 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:35:22.005  1303  1303 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 18:35:22.005  1167  1167 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:35:22.005  1167  1167 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-23 18:35:22.015  7550  7550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ebeda3c
,08-23 18:35:22.015  7550  7550 D BtConfig.SecureMode: isSecureModeOn:false
,08-23 18:35:22.015  1014  4756 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 18:35:22.015  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-23 18:35:22.015  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:22.015  1014  4756 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:22.015  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 18:35:22.025  2025  2025 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 18:35:22.025  1014  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 18:35:22.025  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-23 18:35:22.025  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:22.025  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:22.025  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:22.035  2025  7638 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-23 18:35:22.035  2025  2025 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 18:35:22.045  1014  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 18:35:22.045  1014  1478 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-23 18:35:22.045  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:22.045  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:22.045  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:22.055  1014  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 18:35:22.055  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:22.055  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:22.055  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:22.055  7550  7641 D BluetoothSocket: bindListen(): myUserId = 0
,08-23 18:35:22.055  7550  7641 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 18:35:22.065  7550  7641 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-23 18:35:22.065  7550  7641 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 18:35:22.065  7550  7641 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 18:35:22.065  7550  7641 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@318039d0
08-23 18:35:22.065  7550  7641 D BluetoothSocket: channel: 12
08-23 18:35:22.065  7550  7641 I BtOppRfcommListener: Accept thread started.
,08-23 18:35:22.065  2025  7638 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-23 18:35:22.105  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 18:35:22.105  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:22.105  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-23 18:35:22.105  1014  1042 D Tethering: interfaceAdded wlan0
08-23 18:35:22.105   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 18:35:22.115  1014  1127 E Tethering: No numeric data
,08-23 18:35:22.115  1014  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-23 18:35:22.115  1014  1127 D Tethering: clearTetheredNotification()
,08-23 18:35:22.115  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:22.115  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:22.115  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 18:35:22.115  1167  1167 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 18:35:22.115  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 18:35:22.115  1167  1167 D HotspotTile: updateTetherState():false, false
,08-23 18:35:22.115  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 18:35:22.115  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-23 18:35:22.115  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 18:35:22.125  1014  1121 V NetworkStats: performPollLocked() took 8ms,
08-23 18:35:22.125  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:22.125   276   972 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-23 18:35:22.125   276   972 D SoftapController: Softap fwReload - Ok
,08-23 18:35:22.125  1014  1042 D Tethering: interfaceAdded p2p0,
08-23 18:35:22.125  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:22.125  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:22.125  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
08-23 18:35:22.125   276   972 D CommandListener: Setting iface cfg
08-23 18:35:22.125   276   972 D CommandListener: Trying to bring down wlan0
08-23 18:35:22.125   276   972 D CommandListener: Clearing all IP addresses on wlan0
,08-23 18:35:22.135  1014  1124 E WifiHW  : supplicant_name : p2p_supplicant,
,08-23 18:35:22.165  7644  7644 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-23 18:35:22.165  7644  7644 I wpa_supplicant: Successfully initialized wpa_supplicant
08-23 18:35:22.165  7644  7644 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-23 18:35:22.175  7644  7644 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-23 18:35:22.175   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7644
08-23 18:35:22.175   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-23 18:35:22.175  7644  7644 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-23 18:35:22.175  7644  7644 I wpa_supplicant: ssSupport state is = 1
,08-23 18:35:22.175  7644  7644 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-23 18:35:22.175  7644  7644 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-23 18:35:22.175   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7644,
08-23 18:35:22.175   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106,
,08-23 18:35:22.235  1014  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-23 18:35:22.235  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 18:35:22.235  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 18:35:22.235  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:22.235  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:22.235  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:22.235  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:22.235  1167  1167 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:35:22.235  1167  1167 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-23 18:35:22.235  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-23 18:35:22.245  1167  1167 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:35:22.245  1167  1167 D HotspotTile: onReceive : 2, 0
,08-23 18:35:22.245  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:35:22.245  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:22.255  1014  4756 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 18:35:22.255  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:22.255  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:22.255  1014  4756 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:22.255  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:22.255  1621  1621 I Hs20UtilService: Starting #19
,08-23 18:35:22.255  1621  1646 I Hs20UtilService: Message received 5011
08-23 18:35:22.255  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 18:35:22.255  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 18:35:22.255  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
08-23 18:35:22.255  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 18:35:22.355   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-23 18:35:22.355  7644  7644 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-23 18:35:22.405  7644  7644 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-23 18:35:22.405  7644  7644 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-23 18:35:22.415  7644  7644 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-23 18:35:22.415   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7644
08-23 18:35:22.415   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-23 18:35:22.415  7644  7644 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-23 18:35:22.415  7644  7644 I wpa_supplicant: ssSupport state is = 1
08-23 18:35:22.415  7644  7644 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 18:35:22.415  7644  7644 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 18:35:22.415  7644  7644 E wpa_supplicant: SIM READ ERROR
08-23 18:35:22.415  7644  7644 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 18:35:22.415  7644  7644 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 18:35:22.415  7644  7644 E wpa_supplicant: SIM READ ERROR
08-23 18:35:22.415  7644  7644 I wpa_supplicant: Blacklist: Clear (all) 
08-23 18:35:22.415  7644  7644 I wpa_supplicant: wpa_default_ap_write_once
08-23 18:35:22.415  7644  7644 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-23 18:35:22.415  7644  7644 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 18:35:22.415  7644  7644 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-23 18:35:22.415  7644  7644 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 18:35:22.415  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:22.415  7644  7644 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 18:35:22.415  7644  7644 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-23 18:35:22.415  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:22.415  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-23 18:35:22.415  1014  1127 D Tethering: InitialState.processMessage what=4
,08-23 18:35:22.425  1014  1127 E Tethering: No numeric data
08-23 18:35:22.425  1014  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 18:35:22.425  1014  1127 D Tethering: clearTetheredNotification()
08-23 18:35:22.425  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:22.425  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:22.425  1167  1167 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 18:35:22.425  1167  1167 D HotspotTile: updateTetherState():false, false
08-23 18:35:22.425  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 18:35:22.425  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 18:35:22.425  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:22.425  1014  1121 V NetworkStats: performPollLocked() took 4ms
,08-23 18:35:22.425  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:22.425  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:22.485  7644  7644 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-23 18:35:22.605  1014  2065 V SAMP_SPCM_test: CSC File load.. 
,08-23 18:35:22.615  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering,
08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
,08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-23 18:35:22.625  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-23 18:35:22.665  7644  7644 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-23 18:35:22.665  7644  7644 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account,
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location,
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings,
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall,
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-23 18:35:22.675  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments,
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage,
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize,
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation,
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts,
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-23 18:35:22.695  1014  2065 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application,
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-23 18:35:22.695  1014  2065 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-23 18:35:22.695  1014  2065 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-23 18:35:22.695  1014  2065 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-23 18:35:22.695  1014  2065 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
,08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-23 18:35:22.685  1014  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-23 18:35:22.695  7644  7644 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-23 18:35:22.695   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7644
08-23 18:35:22.695   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-23 18:35:22.695  7644  7644 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-23 18:35:22.695  7644  7644 I wpa_supplicant: ssSupport state is = 1
08-23 18:35:22.695  7644  7644 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-23 18:35:22.705  7644  7644 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-23 18:35:22.715  7649  7649 E Zygote  : MountEmulatedStorage()
,08-23 18:35:22.715  7649  7649 E Zygote  : v2
08-23 18:35:22.715  7644  7644 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-23 18:35:22.715  7649  7649 I libpersona: KNOX_SDCARD checking this for 1000
08-23 18:35:22.715  7649  7649 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:22.715   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7644
08-23 18:35:22.715   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-23 18:35:22.715  7644  7644 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-23 18:35:22.715  7644  7644 I wpa_supplicant: ssSupport state is = 1
08-23 18:35:22.715  7644  7644 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 18:35:22.715  7644  7644 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 18:35:22.715  7644  7644 E wpa_supplicant: SIM READ ERROR
08-23 18:35:22.715  7644  7644 I wpa_supplicant: wpa_default_ap_write_once
,08-23 18:35:22.715  7644  7644 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-23 18:35:22.715  7644  7644 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-23 18:35:22.715  7649  7649 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:22.715  1014  2065 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7649 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 18:35:22.725  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 18:35:22.725  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-23 18:35:22.725  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 18:35:22.725  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 18:35:22.725  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-23 18:35:22.725  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 18:35:22.725  7649  7649 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:22.725  7649  7649 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 18:35:22.745  7649  7649 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:22.745  7649  7649 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:22.765  7649  7649 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 18:35:22.805  1014  2065 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-23 18:35:22.815  7644  7644 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-23 18:35:22.815  7644  7644 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-23 18:35:22.865  7644  7644 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-23 18:35:22.865  7644  7644 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-23 18:35:22.865  7644  7644 I wpa_supplicant: Skip scan - bUseNetwork false
,08-23 18:35:22.875  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-23 18:35:22.875  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-23 18:35:22.875  7644  7644 I wpa_supplicant: HOTSPOT20_ENABLE called
08-23 18:35:22.875  7644  7644 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 18:35:22.875  7644  7644 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 18:35:22.875  7644  7644 E wpa_supplicant: SIM READ ERROR
08-23 18:35:22.875  7644  7644 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 18:35:22.895  7644  7644 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-23 18:35:22.905  7644  7644 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-23 18:35:22.905  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:22.905  1167  1745 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 18:35:22.905  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:22.905  1167  1167 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 18:35:22.905  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:22.905  1167  1167 D HotspotTile: onReceive : 3, 0
08-23 18:35:22.905  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:22.905  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:22.905  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:22.905  1167  1167 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 18:35:22.905  1167  1167 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-23 18:35:22.915  1014  1124 D WifiConfigStore: Loading config and enabling all networks 
08-23 18:35:22.915  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:35:22.915  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:22.915  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:22.915  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:22.915  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:22.915  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:22.915  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:22.915  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:22.915  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:22.925  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:22.925  1014  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 18:35:22.925  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:22.925  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:22.925  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:22.925  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-23 18:35:22.925  1014  1124 E WifiConfigStore: Not a HS20
,08-23 18:35:22.925  1014  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-23 18:35:22.935  1621  1621 I Hs20UtilService: Starting #20
,08-23 18:35:22.935  1014  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-23 18:35:22.935  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-23 18:35:22.935  7644  7644 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-23 18:35:22.935  7644  7644 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-23 18:35:22.935  7644  7644 I wpa_supplicant: reset timer : RESET_TIMER 0
08-23 18:35:22.935  7644  7644 I wpa_supplicant: P2P: Current p2p state = IDLE
08-23 18:35:22.935  7644  7644 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-23 18:35:22.935  7644  7644 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-23 18:35:22.935  7644  7644 I wpa_supplicant: First Scan Start
08-23 18:35:22.935  7644  7644 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-23 18:35:22.935  1621  1646 I Hs20UtilService: Message received 5011
,08-23 18:35:22.935  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-23 18:35:22.945  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 18:35:22.945  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
08-23 18:35:22.945  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 18:35:22.945  1014  1124 D WifiNative-wlan0: Setting external_sim to 1
,08-23 18:35:22.945  1014  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 18:35:22.945  1014  1124 I WifiNative-HAL: startHal
08-23 18:35:22.945  1014  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9cf9f88c
08-23 18:35:22.945  1014  1124 I WifiNative-HAL: Could not start hal
,08-23 18:35:22.945  6953  6953 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 18:35:22.955  1014  1124 E WifiNative-wlan0: do suspend true
,08-23 18:35:22.955  1014  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-23 18:35:22.955   276   972 D CommandListener: Setting iface cfg,
08-23 18:35:22.955   276   972 D CommandListener: Trying to bring up p2p0
,08-23 18:35:22.955  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-23 18:35:22.955  1014  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-23 18:35:22.955  1014  1123 D WifiP2pService: P2pEnablingState
08-23 18:35:22.955  1014  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-23 18:35:22.955  1014  1123 D WifiP2pService: P2p socket connection successful
,08-23 18:35:22.955  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-23 18:35:22.955  1014  1123 D WifiP2pService: P2pEnabledState
08-23 18:35:22.955  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,08-23 18:35:22.955  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-23 18:35:22.955  1014  1124 E WifiNative-wlan0: invaild command id : 215,
08-23 18:35:22.955  1014  1126 E ConnectivityService: updateNetworkInfo()
,08-23 18:35:22.965  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
08-23 18:35:22.965  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-23 18:35:22.965  1014  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:35:22.965  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 18:35:22.965  1014  1147 I WifiNative-HAL: startHal
08-23 18:35:22.965  1014  1045 D WifiDisplayController: disconnect
08-23 18:35:22.965  1014  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9da359bc
08-23 18:35:22.965  1014  1045 D WifiDisplayController: updateConnection
08-23 18:35:22.965  1014  1147 I WifiNative-HAL: Could not start hal
08-23 18:35:22.965  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 18:35:22.965  1014  1147 E WifiScanningService: could not start HAL
08-23 18:35:22.965  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 18:35:22.965  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-23 18:35:22.965  1014  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:35:22.965  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-23 18:35:22.965  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-23 18:35:22.965  1014  1124 E WifiNative-wlan0: invaild command id : 215
08-23 18:35:22.965  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-23 18:35:22.965  7644  7644 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-23 18:35:22.965  7644  7644 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-23 18:35:22.965  7644  7644 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands,
08-23 18:35:22.965  1014  1124 E WifiStateMachine: Failed to set frequency band 0
08-23 18:35:22.965  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:22.965  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:22.975  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress
,08-23 18:35:22.975  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 18:35:22.975  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-23 18:35:22.975  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:22.975  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:22.975  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 18:35:22.975  1014  1123 D WifiP2pService: DeviceAddress: 0a:76:28
,08-23 18:35:22.975  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 18:35:22.975  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 18:35:22.975  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-23 18:35:22.975  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 18:35:22.975  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-23 18:35:22.975  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  secondary type: null
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  wps: 0
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  grpcapab: 0
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  devcapab: 0
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  status: 3
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  wfdInfo: null
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  groupownerAddress: null
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  GOdeviceName: null
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  interfaceAddress: 
08-23 18:35:22.975  1014  1045 D WifiDisplayController:  SConnectInfo : null
,08-23 18:35:22.985  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 18:35:22.985  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 18:35:22.985  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 18:35:22.985  1303  2230 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 18:35:22.985  1167  1167 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-23 18:35:22.985  1014  1474 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 18:35:22.985  1167  1167 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-23 18:35:22.985  7348  7348 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 18:35:22.985  7348  7348 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-23 18:35:22.985  7348  7348 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 18:35:22.995  7363  7363 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 18:35:23.005  1014  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-23 18:35:23.005  1014  1123 D WifiP2pService: InactiveState
,08-23 18:35:23.005  1014  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-23 18:35:23.005  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 18:35:23.005  7644  7644 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-23 18:35:23.005  1014  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-23 18:35:23.005  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 18:35:23.095   287   287 E SMD     : DCD OFF,
,08-23 18:35:23.105  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-23 18:35:23.105  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-23 18:35:23.105  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 18:35:23.105   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 18:35:23.155  1014  3342 D SSRM:n  : SIOP:: AP = 320
,08-23 18:35:23.795  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:23.795  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:23.795  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:23.795  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:23.795  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:23.795  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:23.795  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:23.795  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:23.795  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:23.795  6794  6848 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-23 18:35:23.805  6794  6848 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-23 18:35:23.805  6794  6848 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@158b4a6c Bundle[{}]
,08-23 18:35:23.805  6794  6848 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 18:35:23.805  6794  6848 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 18:35:23.805  6794  6848 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-23 18:35:23.805  6794  6848 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-23 18:35:23.805  6794  6848 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 18:35:23.805  6794  6848 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 18:35:23.815  6794  6848 I System.out: Running OutgoingSocketThread
,08-23 18:35:23.815  6794  7668 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1339)
,08-23 18:35:23.815  6794  7668 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 51896
,08-23 18:35:23.815  6794  7668 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-23 18:35:24.105   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-23 18:35:24.185  7644  7644 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
08-23 18:35:24.185  7644  7644 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-23 18:35:24.185  7644  7644 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-23 18:35:24.185  7644  7644 I wpa_supplicant: Trying to associate with  'G700'
08-23 18:35:24.185  7644  7644 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-23 18:35:24.185  7644  7644 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-23 18:35:24.195  1014  7665 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-23 18:35:24.205  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:24.205  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:24.305  7644  7644 E wpa_supplicant: Cmd 35605 not handled,
08-23 18:35:24.305  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:24.305  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:24.305  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:24.305  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-23 18:35:24.305  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 18:35:24.305  7644  7644 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-23 18:35:24.305  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-23 18:35:24.305  7644  7644 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-23 18:35:24.305  7644  7644 I wpa_supplicant: Associated with F4.99.3E
,08-23 18:35:24.305  7644  7644 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-23 18:35:24.305  7644  7644 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-23 18:35:24.305  7644  7644 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-23 18:35:24.305  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 18:35:24.305  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-23 18:35:24.305  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 18:35:24.305  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-23 18:35:24.305  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-23 18:35:24.315  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:24.305  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-23 18:35:24.305  1014  1127 E Tethering: No numeric data
08-23 18:35:24.305  1014  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 18:35:24.305  1014  1127 D Tethering: clearTetheredNotification()
08-23 18:35:24.315  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:24.315  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 18:35:24.315  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 18:35:24.315  1014  1121 V NetworkStats: performPollLocked() took 5ms
,08-23 18:35:24.315  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:24.325  1167  1167 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-23 18:35:24.325  1167  1167 D HotspotTile: updateTetherState():false, false
,08-23 18:35:24.325  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:24.325  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:24.325  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:24.325  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:24.325  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-23 18:35:24.325  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:24.325  7644  7644 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-23 18:35:24.335  7644  7644 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-23 18:35:24.335  7644  7644 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-23 18:35:24.335  7644  7644 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
,08-23 18:35:24.335  7644  7644 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
08-23 18:35:24.335  7644  7644 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-23 18:35:24.335  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-23 18:35:24.335  7644  7644 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-23 18:35:24.335  7644  7644 I wpa_supplicant: Blacklist: Clear (temp) 
08-23 18:35:24.335  7644  7644 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030,
08-23 18:35:24.335  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,08-23 18:35:24.335  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-23 18:35:24.335  1014  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-23 18:35:24.345  1014  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-23 18:35:24.345  1014  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-23 18:35:24.345  1014  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-23 18:35:24.345  1014  1126 E ConnectivityService: updateNetworkInfo()
08-23 18:35:24.345  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-23 18:35:24.345  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 18:35:24.355  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 18:35:24.355  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:24.355  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:24.355  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:24.355  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:24.355  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 18:35:24.355  1014  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 18:35:24.355  1014  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:24.355  1014  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:24.355  1014  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:24.355  1014  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:24.365  1621  1621 I Hs20UtilService: Starting #21
,08-23 18:35:24.365  1621  1646 I Hs20UtilService: Message received 5007
,08-23 18:35:24.365  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 18:35:24.365  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 18:35:24.365  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 18:35:24.375  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 18:35:24.375  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 18:35:24.375  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-23 18:35:24.375  1303  1303 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 18:35:24.375  1303  2230 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 18:35:24.385   276   972 D CommandListener: Setting iface cfg,
08-23 18:35:24.385  1014  1124 E WifiStateMachine: Start Dhcp Watchdog 3,
08-23 18:35:24.385  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:24.385  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:24.395  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 18:35:24.395  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:24.395  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:24.395  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:24.395  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:24.395  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:24.405  1014  1124 E WifiNative-wlan0: do suspend false
,08-23 18:35:24.405  1014  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-23 18:35:24.405  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 18:35:24.405  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 18:35:24.405  1014  1124 D SecContentProvider2: mCursor = null
,08-23 18:35:24.615  7671  7671 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-23 18:35:24.625  7671  7671 I dhcpcd  : version 5.5.6 starting
,08-23 18:35:24.625  7671  7671 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-23 18:35:24.675  7671  7671 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-23 18:35:24.675  7671  7671 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-23 18:35:24.675  7671  7671 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-23 18:35:24.675  7671  7671 I dhcpcd  : bssid match
08-23 18:35:24.675  7671  7671 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-23 18:35:24.735  7671  7671 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-23 18:35:24.815  6794  6848 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1340)
08-23 18:35:24.815  6794  6848 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1340)
,08-23 18:35:24.815  6794  6848 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1345)
,08-23 18:35:24.825  6794  6848 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-23 18:35:24.825  6794  6848 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1346)
,08-23 18:35:24.825  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 18:35:24.825  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178c68f6 added. We now have 2 listener(s)
,08-23 18:35:24.825  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-23 18:35:24.825  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:24.825  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 18:35:24.825  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:24.825  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3307d4f7 added. We now have 9 listener(s)
08-23 18:35:24.825  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:24.825  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 18:35:24.835  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:24.835  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-23 18:35:24.835  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:24.835  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:24.835  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:24.835  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:24.835  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:24.835  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-23 18:35:24.835  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:24.845  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:24.845  6794  6848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:35:24.845  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:24.845  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:24.845  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 18:35:24.845  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a7d05cd added. We now have 3 listener(s)
,08-23 18:35:24.845  7671  7671 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-23 18:35:24.855  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-23 18:35:24.855  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:24.855  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:24.855  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:24.855  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@388e1e82 added. We now have 10 listener(s)
08-23 18:35:24.855  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:24.855  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:24.855  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:24.855  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:24.855  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:24.855  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:24.855  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:24.855  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:24.855  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178c68f6 removed from the list
08-23 18:35:24.855  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:24.855  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3307d4f7 removed from the list
08-23 18:35:24.855  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:24.855  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:24.855  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:24.855  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:24.865  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 18:35:24.865  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:24.865  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:24.865  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3307d4f7 not in the list
08-23 18:35:24.865  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:24.865  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:24.865  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:24.865  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-23 18:35:24.865  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-23 18:35:24.865  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@388e1e82 removed from the list
,08-23 18:35:24.865  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:24.865  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:24.865  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:24.865  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 18:35:24.865  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a7d05cd removed from the list
08-23 18:35:24.865  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 18:35:24.865  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c5ac993 added. We now have 2 listener(s)
,08-23 18:35:24.875  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-23 18:35:24.875  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:24.875  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:24.875  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:24.875  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16c4cdd0 added. We now have 9 listener(s)
,08-23 18:35:24.875  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:24.875  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 18:35:24.885  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:24.905  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:24.905  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:24.905  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:24.905  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:24.905  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-23 18:35:24.905  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:24.905  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:24.905  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:24.905  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:24.905  6794  6848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:35:24.905  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:24.905  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:24.905  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:24.905  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c03a0ce added. We now have 3 listener(s)
,08-23 18:35:24.915  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 18:35:24.915  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:24.915  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-23 18:35:24.915  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:24.915  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5de6bef added. We now have 10 listener(s)
08-23 18:35:24.915  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-23 18:35:24.915  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:24.915  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:35:24.915  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-23 18:35:24.915  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:24.915  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 18:35:24.925  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 18:35:24.925  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 18:35:24.935  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 18:35:24.935  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 18:35:24.935  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 18:35:24.935  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 18:35:24.945  7550  7575 D BtGatt.GattService: registerClient() - UUID=12ad119c-f036-4fbe-a983-6b759a849528,
,08-23 18:35:24.985  7550  7574 D BtGatt.GattService: onClientRegistered() - UUID=12ad119c-f036-4fbe-a983-6b759a849528, clientIf=6,
,08-23 18:35:24.995  6794  6806 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-23 18:35:24.995  7550  7558 D BtGatt.GattService: start scan with filters
,08-23 18:35:24.995  7550  7580 D BtGatt.ScanManager: handling starting scan
08-23 18:35:24.995  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 18:35:24.995  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 18:35:24.995  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 18:35:24.995  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 18:35:24.995  7550  7580 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ebeda3c
,08-23 18:35:24.995  7550  7574 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-23 18:35:24.995  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.005  7550  7580 D BtGatt.ScanManager: allow scan with filters
08-23 18:35:25.005  7550  7580 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 18:35:25.005  7550  7580 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-23 18:35:25.005  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 18:35:25.005  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 18:35:25.005  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 18:35:25.005  7550  7574 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 18:35:25.005  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.005  7550  7580 D BtGatt.ScanManager: Starting BLE batch scan
08-23 18:35:25.005  7550  7580 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 18:35:25.005  7550  7574 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-23 18:35:25.005  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.005  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:25.005  7550  7574 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-23 18:35:25.015  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.015  6794  6848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 18:35:25.015  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:25.015  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 18:35:25.015  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:25.015  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 18:35:25.015  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 18:35:25.015  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:35:25.015  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-23 18:35:25.015  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 18:35:25.015  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-23 18:35:25.015  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 18:35:25.015  7550  7624 D BtGatt.GattService: stopScan() - queue size =1
,08-23 18:35:25.025  7550  7575 D BtGatt.GattService: unregisterClient() - clientIf=6
08-23 18:35:25.025  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:35:25.025  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 18:35:25.025  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 18:35:25.025  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
08-23 18:35:25.025  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 18:35:25.025  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:25.025  7550  7580 D BtGatt.ScanManager: filter size is 1
,08-23 18:35:25.025  7550  7580 D BtGatt.ScanManager: delete FilterIndex - 3
08-23 18:35:25.025  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 18:35:25.025  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 18:35:25.025  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 18:35:25.025  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:25.025  7550  7574 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-23 18:35:25.025  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:25.025  7550  7580 D BtGatt.ScanManager: stopping BLe Batch
08-23 18:35:25.025  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:25.025  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:25.025  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:25.035  7550  7574 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-23 18:35:25.035  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:25.035  7550  7580 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-23 18:35:25.035  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:25.035  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 18:35:25.035  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:25.035  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:25.035  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:25.035  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:25.035  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:25.035  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c5ac993 removed from the list
,08-23 18:35:25.035  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:25.035  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16c4cdd0 removed from the list
08-23 18:35:25.035  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop,
08-23 18:35:25.035  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:25.035  7550  7574 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-23 18:35:25.035  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.035  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:25.035  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:25.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:25.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:25.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:25.045  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16c4cdd0 not in the list
,08-23 18:35:25.045  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:25.045  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:25.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:25.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:25.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:25.045  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5de6bef removed from the list
08-23 18:35:25.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:25.045  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:25.045  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:25.045  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 18:35:25.045  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c03a0ce removed from the list
,08-23 18:35:25.055  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:25.055  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4fd80b added. We now have 2 listener(s),
,08-23 18:35:25.055  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-23 18:35:25.055  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:25.055  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:25.055  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:25.055  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85486e8 added. We now have 9 listener(s)
08-23 18:35:25.055  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:25.055  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 18:35:25.065  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:25.075  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-23 18:35:25.075  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:25.075  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:25.075  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:25.075  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:25.075  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:25.075  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:25.075  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:25.085  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:35:25.085  6794  6848 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-23 18:35:25.085  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:25.085  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67efba6 added. We now have 3 listener(s)
08-23 18:35:25.085  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:35:25.085  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 18:35:25.085  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:25.085  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:25.085  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:25.085  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d21e9e7 added. We now have 10 listener(s),
08-23 18:35:25.085  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:25.085  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:25.085  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 18:35:25.085  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:35:25.085  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:35:25.085  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:25.085  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 18:35:25.085  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:25.085  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 18:35:25.095  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 18:35:25.095  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 18:35:25.095  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 18:35:25.095  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-23 18:35:25.105  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 18:35:25.105  7550  7558 D BtGatt.GattService: registerClient() - UUID=dd239d6c-3ddc-45aa-b770-349a1dbe7651
,08-23 18:35:25.145  7550  7574 D BtGatt.GattService: onClientRegistered() - UUID=dd239d6c-3ddc-45aa-b770-349a1dbe7651, clientIf=6
,08-23 18:35:25.145  6794  6806 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 18:35:25.145  7550  7562 D BtGatt.GattService: start scan with filters
,08-23 18:35:25.145  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 18:35:25.145  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 18:35:25.145  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 18:35:25.145  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 18:35:25.145  7550  7580 D BtGatt.ScanManager: handling starting scan
,08-23 18:35:25.155  7550  7574 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-23 18:35:25.155  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 18:35:25.155  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 18:35:25.155  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 18:35:25.155  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.155  7550  7580 D BtGatt.ScanManager: allow scan with filters
08-23 18:35:25.155  7550  7580 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 18:35:25.155  7550  7580 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-23 18:35:25.155  7550  7574 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 18:35:25.155  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.155  7550  7580 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 18:35:25.155  7550  7580 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 18:35:25.165  7550  7574 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-23 18:35:25.165  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.165  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:25.165  7550  7574 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-23 18:35:25.165  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.175  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 18:35:25.175  6794  6848 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 18:35:25.175  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 18:35:25.175  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 18:35:25.175  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 18:35:25.175  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 18:35:25.175  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:25.175  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 18:35:25.175  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 18:35:25.175  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4fd80b removed from the list
,08-23 18:35:25.175  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:25.175  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85486e8 removed from the list
08-23 18:35:25.175  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 18:35:25.175  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:25.185  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:25.185  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-23 18:35:25.185  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:25.185  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:25.185  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 18:35:25.185  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:25.185  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:35:25.185  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85486e8 not in the list
08-23 18:35:25.185  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-23 18:35:25.185  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:35:25.185  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 18:35:25.185  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-23 18:35:25.185  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 18:35:25.185  7550  7558 D BtGatt.GattService: stopScan() - queue size =1
,08-23 18:35:25.195  7550  7580 D BtGatt.ScanManager: filter size is 1,
08-23 18:35:25.195  7550  7562 D BtGatt.GattService: unregisterClient() - clientIf=6
08-23 18:35:25.195  7550  7580 D BtGatt.ScanManager: delete FilterIndex - 4
08-23 18:35:25.195  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-23 18:35:25.195  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 18:35:25.195  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 18:35:25.195  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-23 18:35:25.195  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 18:35:25.195  7550  7574 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-23 18:35:25.195  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:25.195  7550  7580 D BtGatt.ScanManager: stopping BLe Batch
08-23 18:35:25.195  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 18:35:25.195  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 18:35:25.195  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 18:35:25.195  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 18:35:25.195  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:25.205  7550  7574 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-23 18:35:25.205  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.205  7550  7580 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-23 18:35:25.205  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:25.205  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:25.205  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:25.205  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-23 18:35:25.205  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d21e9e7 removed from the list
08-23 18:35:25.205  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:25.205  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:25.205  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:25.205  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:25.205  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 18:35:25.205  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67efba6 removed from the list
08-23 18:35:25.205  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:25.205  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:25.205  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36193d83 added. We now have 2 listener(s),
08-23 18:35:25.205  7550  7574 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-23 18:35:25.205  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:25.205  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 18:35:25.205  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:25.205  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-23 18:35:25.205  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:25.205  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcf4b00 added. We now have 9 listener(s)
,08-23 18:35:25.205  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:25.205  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-23 18:35:25.215  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:25.215  1014  1124 E WifiNative-wlan0: do suspend true
,08-23 18:35:25.215  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:25.215  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:25.215  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:25.215  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:25.215  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:25.215  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:35:25.215  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:35:25.215  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:35:25.215  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:35:25.215  6794  6848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:35:25.215  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:25.215  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38ffd97e added. We now have 3 listener(s)
,08-23 18:35:25.225  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-23 18:35:25.225  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 18:35:25.225  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:25.225  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:25.225  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:25.225  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea82edf added. We now have 10 listener(s)
08-23 18:35:25.225  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:25.225  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:25.225  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:35:25.225  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:35:25.225  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:35:25.225  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 18:35:25.225  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:25.225  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 18:35:25.235  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 18:35:25.235  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 18:35:25.235  1014  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-23 18:35:25.245  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 18:35:25.245  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 18:35:25.245  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 18:35:25.245  6794  6848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 18:35:25.245  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 18:35:25.245  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 18:35:25.245  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:25.245  7550  7575 D BtGatt.GattService: registerClient() - UUID=3d3ad7c2-3b8a-4104-bcf9-d5923c93d59b
08-23 18:35:25.245  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.245  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:25.245  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:25.255  1014  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-23 18:35:25.255  1014  1124 E WifiStateMachine: VerifyingLinkState enter
,08-23 18:35:25.255  1014  1126 E ConnectivityService: updateNetworkInfo()
,08-23 18:35:25.255  1014  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-23 18:35:25.255  1014  1126 D ConnectivityService: Adding iface wlan0 to network 504
,08-23 18:35:25.265  1014  1141 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-23 18:35:25.265  1014  1141 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-23 18:35:25.265  1014  1141 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-23 18:35:25.265  1014  1141 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-23 18:35:25.265  1014  1141 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-23 18:35:25.275  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-23 18:35:25.275  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:25.275  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:25.275  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.275  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:25.275  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:25.275  1014  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-23 18:35:25.285  1014  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-23 18:35:25.285  1014  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504,
,08-23 18:35:25.285  1014  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-23 18:35:25.285  1014  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 18:35:25.285  1014  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-23 18:35:25.285  1014  1126 D ConnectivityService: LTETest block dns file not exists
,08-23 18:35:25.285  7550  7574 D BtGatt.GattService: onClientRegistered() - UUID=3d3ad7c2-3b8a-4104-bcf9-d5923c93d59b, clientIf=6
08-23 18:35:25.285  6794  6802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-23 18:35:25.285  7550  7576 D BtGatt.GattService: start scan with filters
,08-23 18:35:25.295  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 18:35:25.295  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 18:35:25.295  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 18:35:25.295  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 18:35:25.295  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-23 18:35:25.295  7550  7580 D BtGatt.ScanManager: handling starting scan
,08-23 18:35:25.295  7550  7574 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-23 18:35:25.295  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.295  7550  7580 D BtGatt.ScanManager: allow scan with filters
08-23 18:35:25.295  1167  1167 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:25.295  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 18:35:25.295  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.295  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.295  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:25.295  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.305  7550  7580 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 18:35:25.305  7550  7580 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-23 18:35:25.305  1014  1126 V NetworkStats: updateIfacesLocked()
08-23 18:35:25.305  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:25.305  1014  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-23 18:35:25.305  7550  7574 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 18:35:25.305  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.305  1014  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 18:35:25.305  1014  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-23 18:35:25.305  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 18:35:25.305  7550  7580 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 18:35:25.305  7550  7580 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-23 18:35:25.305  1014  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 18:35:25.315  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 18:35:25.315  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 18:35:25.315  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 18:35:25.315  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 18:35:25.315  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 18:35:25.315  1014  1126 V NetworkStats: performPollLocked() took 13ms
08-23 18:35:25.315  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:25.315  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:25.315  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 18:35:25.315  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:25.325  7550  7574 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-23 18:35:25.325  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.325  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-23 18:35:25.325  1621  1621 I Hs20UtilService: Starting #22
,08-23 18:35:25.325  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
,08-23 18:35:25.325  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
,08-23 18:35:25.325  7550  7574 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-23 18:35:25.325  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 18:35:25.325  1621  1646 I Hs20UtilService: Message received 5007
,08-23 18:35:25.335  1167  1167 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:25.335  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-23 18:35:25.335  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:25.335  1014  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-23 18:35:25.335  1014  1126 E ConnectivityService: updateNetworkInfo()
08-23 18:35:25.335  1014  1126 E ConnectivityService: updateNetworkInfo()
08-23 18:35:25.335  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:35:25.335  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:25.335  1014  1126 V NetworkStats: updateIfacesLocked()
08-23 18:35:25.335  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.335  1014  1126 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:25.335  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.335  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.335  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 18:35:25.335  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 18:35:25.335  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:25.335  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:25.335  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 18:35:25.345  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 18:35:25.345  1303  1303 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-23 18:35:25.345  1014  1126 V NetworkStats: performPollLocked() took 9ms
08-23 18:35:25.345  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:25.345  1014  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-23 18:35:25.345  1014  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-23 18:35:25.345  1014  7669 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:35:25.345  1014  7669 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-23 18:35:25.345  1014  7669 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:35:25.345  1014  7669 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-23 18:35:25.345  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:25.345  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:25.345  1014  7669 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 18:35:25.355  1014  1126 D ConnectivityService:    accepting network in place of null
,08-23 18:35:25.355  1014  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-23 18:35:25.355  1014  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-23 18:35:25.355  1014  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-23 18:35:25.355  1014  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-23 18:35:25.355  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-23 18:35:25.355  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 18:35:25.355  1456  1456 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:35:25.355   276   968 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 18:35:25.355   276   968 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-23 18:35:25.355  1014  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-23 18:35:25.355  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-23 18:35:25.355  1014  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-23 18:35:25.355  1014  1127 D Tethering: MasterInitialState.processMessage what=3
08-23 18:35:25.355  1167  1676 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 18:35:25.355  1014  1121 V NetworkStats: updateIfacesLocked(),
08-23 18:35:25.355  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-23 18:35:25.355  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-23 18:35:25.355  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:25.355  4776  6856 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 18:35:25.355  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:25.355  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 18:35:25.355  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:25.355  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:25.355  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:25.355  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 18:35:25.355  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 18:35:25.355  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:25.355  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36193d83 removed from the list
08-23 18:35:25.355  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:25.355  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcf4b00 removed from the list
08-23 18:35:25.355  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 18:35:25.355  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:25.365  1014  1121 V NetworkStats: performPollLocked() took 3ms
08-23 18:35:25.355  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 18:35:25.355  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:25.355  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-23 18:35:25.355  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 18:35:25.355  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 18:35:25.355  1167  1167 D StatusBar.NetworkController: EthernetConnected: false
08-23 18:35:25.355  1167  1167 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-23 18:35:25.355  1167  1167 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-23 18:35:25.355  1167  1167 D StatusBar.NetworkController: updateDataNetType()
08-23 18:35:25.355  1167  1167 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-23 18:35:25.365  1014  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-23 18:35:25.355  1167  1167 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-23 18:35:25.365  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:25.365  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:25.365  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:25.365  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:25.365  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcf4b00 not in the list
08-23 18:35:25.365  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-23 18:35:25.365  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:35:25.365  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 18:35:25.365  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 18:35:25.365  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 18:35:25.365  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:25.365  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:25.365  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:25.365  1014  4756 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 18:35:25.365  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:25.365  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:25.365  1167  1167 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-23 18:35:25.365  1167  1167 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-23 18:35:25.365  1167  1167 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-23 18:35:25.365  1167  1167 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:25.365  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-23 18:35:25.365  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.365  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.365  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.365  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.365  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:25.365  1014  4756 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:25.365  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 18:35:25.375  7550  7624 D BtGatt.GattService: stopScan() - queue size =1
08-23 18:35:25.375  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:25.375  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:25.375  7550  7580 D BtGatt.ScanManager: filter size is 1
08-23 18:35:25.375  7550  7580 D BtGatt.ScanManager: delete FilterIndex - 5
08-23 18:35:25.375  7550  7562 D BtGatt.GattService: unregisterClient() - clientIf=6
08-23 18:35:25.375  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:35:25.375  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
08-23 18:35:25.375  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 18:35:25.375  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 18:35:25.375  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 18:35:25.375  7550  7574 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-23 18:35:25.375  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:25.375  7550  7580 D BtGatt.ScanManager: stopping BLe Batch
,08-23 18:35:25.375  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-23 18:35:25.375  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-23 18:35:25.375  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:25.375  7550  7574 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-23 18:35:25.375  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:25.375  7550  7580 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-23 18:35:25.375  1621  1621 I Hs20UtilService: Starting #23
,08-23 18:35:25.375  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-23 18:35:25.375  1621  1646 I Hs20UtilService: Message received 5007
08-23 18:35:25.375  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 18:35:25.375  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-23 18:35:25.375  1303  1303 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-23 18:35:25.375  7550  7574 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-23 18:35:25.375  7550  7574 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 18:35:25.375  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 18:35:25.375  6794  6848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 18:35:25.375  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 18:35:25.385  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:25.385  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:25.385  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:25.385  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:25.385  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:25.385  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea82edf removed from the list
08-23 18:35:25.385  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:25.385  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:25.385  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:25.385  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:35:25.385  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:25.385  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:35:25.385  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38ffd97e removed from the list
,08-23 18:35:25.385  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:25.385  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0ad9fb added. We now have 2 listener(s)
,08-23 18:35:25.385  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 18:35:25.385  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 18:35:25.385  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 18:35:25.385  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:25.395  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:25.395  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:25.395  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:25.395  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:25.395  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-23 18:35:25.395  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@282b7a18 added. We now have 9 listener(s)
08-23 18:35:25.395  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:35:25.395  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 18:35:25.395  1621  1621 I Hs20UtilService: Starting #24
,08-23 18:35:25.395  1621  1646 I Hs20UtilService: Message received 5007
,08-23 18:35:25.395  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 18:35:25.395  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 18:35:25.395  1303  1303 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-23 18:35:25.395  6794  6848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:35:25.395  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:25.395  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:25.395  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:25.395  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:25.395  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:25.395  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:25.395  6794  6848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:25.405  6794  6848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:35:25.405  6794  6848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:35:25.405  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:35:25.405  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28539a56 added. We now have 3 listener(s)
,08-23 18:35:25.405  1014  4757 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-23 18:35:25.405  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:25.405  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:35:25.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 18:35:25.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:35:25.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:35:25.405  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:35:25.405  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19231ad7 added. We now have 10 listener(s)
08-23 18:35:25.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:35:25.405  6794  6848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:35:25.405  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:25.405  6794  6848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:35:25.405  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:35:25.405  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:25.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:35:25.405  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:25.405  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0ad9fb removed from the list
08-23 18:35:25.405  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:25.405  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@282b7a18 removed from the list
08-23 18:35:25.405  6794  6848 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:35:25.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:35:25.405  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:25.405  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:25.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:25.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:35:25.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:25.415  6794  6848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@282b7a18 not in the list
08-23 18:35:25.415  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:25.415  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:35:25.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:35:25.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:35:25.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:35:25.415  6794  6848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19231ad7 removed from the list
08-23 18:35:25.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 18:35:25.415  6794  6848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:35:25.415  6794  6848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-23 18:35:25.415  6794  6848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:35:25.415  6794  6848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28539a56 removed from the list
,08-23 18:35:25.415  1014  1132 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-23 18:35:25.415  1014  1132 D SecContentProvider2: mCursor = null
08-23 18:35:25.415  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-23 18:35:25.415  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-23 18:35:25.415  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-23 18:35:25.415  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:35:25.415  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-23 18:35:25.415  6794  6848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 18:35:25.415  1014  1479 D SecContentProvider2: uri = 15 selection = getToastGravity
08-23 18:35:25.415  1014  1479 D SecContentProvider2: mCursor = null
,08-23 18:35:25.415  1014  1027 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-23 18:35:25.415  1014  1027 D SecContentProvider2: mCursor = null
,08-23 18:35:25.425  6794  7707 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1353, name: My test thread name)
,08-23 18:35:25.425  6794  7707 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1353, thread name: My test thread name)
08-23 18:35:25.425  6794  7707 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1353, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 18:35:25.425  1014  4756 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-23 18:35:25.425  1014  4756 D SecContentProvider2: mCursor = null
,08-23 18:35:25.425  6794  7708 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1355, name: My test thread name)
08-23 18:35:25.425  6794  7708 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1355, thread name: My test thread name)
08-23 18:35:25.425  6794  7708 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1355, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-23 18:35:25.425  1014  1474 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
08-23 18:35:25.425  1014  1474 D SecContentProvider2: mCursor = null
08-23 18:35:25.425  6794  6848 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-23 18:35:25.425  6794  6848 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-23 18:35:25.425  6794  6848 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-23 18:35:25.425  6794  6848 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-23 18:35:25.425  6794  6848 D com.test.thalitest.ThaliTestRunner: Total duration: 23424 ms
08-23 18:35:25.425  6794  6848 I jxcore-log: Total number of executed tests:  80
08-23 18:35:25.425  6794  6848 I jxcore-log: 
,08-23 18:35:25.425  6794  6848 I jxcore-log: Number of passed tests:  80
08-23 18:35:25.425  6794  6848 I jxcore-log: 
08-23 18:35:25.425  6794  6848 I jxcore-log: Number of failed tests:  0
08-23 18:35:25.425  6794  6848 I jxcore-log: 
08-23 18:35:25.425  6794  6848 I jxcore-log: Number of ignored tests:  0
,08-23 18:35:25.425  6794  6848 I jxcore-log: 
08-23 18:35:25.425  6794  6848 I jxcore-log: Total duration:  23424
08-23 18:35:25.425  6794  6848 I jxcore-log: 
08-23 18:35:25.425  6794  6848 I jxcore-log: Is Android:  true
08-23 18:35:25.425  6794  6848 I jxcore-log: 
,08-23 18:35:25.425  6794  6848 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-23 18:35:25.425  6794  6848 I jxcore-log: 
,08-23 18:35:25.435  1014  1477 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-23 18:35:25.435  1014  1477 D SecContentProvider2: mCursor = null
08-23 18:35:25.435  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:25.435  6794  6848 I jxcore-log: 
08-23 18:35:25.435  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:25.435  6794  6848 I jxcore-log: 
08-23 18:35:25.435  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:25.435  6794  6848 I jxcore-log: 
08-23 18:35:25.435  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:25.435  6794  6848 I jxcore-log: 
08-23 18:35:25.435  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:25.435  6794  6848 I jxcore-log: 
08-23 18:35:25.435  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:25.435  6794  6848 I jxcore-log: 
08-23 18:35:25.445  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:25.445  6794  6848 I jxcore-log: 
08-23 18:35:25.445  6794  6794 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-23 18:35:25.445  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 18:35:25.445  6794  6848 I jxcore-log: 
08-23 18:35:25.445  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:25.445  6794  6848 I jxcore-log: 
08-23 18:35:25.445  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:25.445  6794  6848 I jxcore-log: 
08-23 18:35:25.445  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 18:35:25.445  6794  6848 I jxcore-log: 
08-23 18:35:25.445  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 18:35:25.445  6794  6848 I jxcore-log: 
08-23 18:35:25.445  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:25.445  6794  6848 I jxcore-log: 
08-23 18:35:25.445  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:25.445  6794  6848 I jxcore-log: 
08-23 18:35:25.445  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:35:25.445  6794  6848 I jxcore-log: 
08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:35:25.455  6794  6848 I jxcore-log: 
,08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:25.455  6794  6848 I jxcore-log: 
08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:35:25.455  6794  6848 I jxcore-log: 
08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:35:25.455  6794  6848 I jxcore-log: 
,08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:35:25.455  6794  6848 I jxcore-log: 
08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,08-23 18:35:25.455  6794  6848 I jxcore-log: 
08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 18:35:25.455  6794  6848 I jxcore-log: 
,08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 18:35:25.455  6794  6848 I jxcore-log: 
08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,08-23 18:35:25.455  6794  6848 I jxcore-log: 
08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 18:35:25.455  6794  6848 I jxcore-log: 
08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 18:35:25.455  6794  6848 I jxcore-log: 
,08-23 18:35:25.455  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:25.455  6794  6848 I jxcore-log: 
,08-23 18:35:25.455   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-23 18:35:25.485  1014  1479 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,08-23 18:35:25.485  1167  1167 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 18:35:25.525  6794  6794 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 18:35:25.535  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 18:35:25.535  6794  6848 I jxcore-log: 
,08-23 18:35:25.555  1014  7669 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 18:35:25.655  1014  7669 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 16:35:25 GMT], X-Android-Received-Millis=[1471970125670], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471970125597]},
08-23 18:35:25.655  1014  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504],
,08-23 18:35:25.655  1014  7669 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-23 18:35:25.655  1014  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-23 18:35:25.655  1014  7669 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-23 18:35:25.655  1014  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-23 18:35:25.655  1167  1676 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
08-23 18:35:25.655  1014  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-23 18:35:25.655  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
08-23 18:35:25.665  4776  6856 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: EthernetConnected: false
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: updateDataNetType()
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: NoService, mRoamingIconId = 0,
08-23 18:35:25.665  1167  1167 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 18:35:25.665  1167  1167 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 18:35:25.665  1167  1167 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 18:35:25.705  6794  6794 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 18:35:25.705  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 18:35:25.705  6794  6848 I jxcore-log: 
,08-23 18:35:25.745  7710  7710 D AndroidRuntime: 
08-23 18:35:25.745  7710  7710 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 18:35:25.745  7710  7710 D AndroidRuntime: CheckJNI is OFF,
08-23 18:35:25.745  7710  7710 D AndroidRuntime: readGMSProperty: start
08-23 18:35:25.745  7710  7710 D AndroidRuntime: readGMSProperty: already setted!!
08-23 18:35:25.745  7710  7710 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,08-23 18:35:25.745  7710  7710 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 18:35:25.745  7710  7710 D AndroidRuntime: readGMSProperty: end
08-23 18:35:25.745  7710  7710 D AndroidRuntime: addProductProperty: start
,08-23 18:35:25.855  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-23 18:35:25.865  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:25.875  7710  7710 E AffinityControl: AffinityControl: registerfunction enter
,08-23 18:35:25.885  6794  6794 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 18:35:25.885  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 18:35:25.885  6794  6848 I jxcore-log: 
,08-23 18:35:25.895  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-23 18:35:25.895  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:25.895  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:25.895  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:25.895  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:25.895  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:35:25.895  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:35:25.895  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 18:35:25.895  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:35:25.895  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:35:25.895  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:25.895  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:35:25.895  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:35:25.905  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:35:25.905  7718  7718 E Zygote  : MountEmulatedStorage()
08-23 18:35:25.905  7718  7718 I libpersona: KNOX_SDCARD checking this for 1000
08-23 18:35:25.905  7718  7718 E Zygote  : v2
08-23 18:35:25.905  7718  7718 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:25.905  6794  6848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:35:25.905  6794  6848 I jxcore-log: 
08-23 18:35:25.905  7710  7710 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 18:35:25.915  7718  7718 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 18:35:25.915  7718  7718 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 18:35:25.915  1014  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7718 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 18:35:25.915  7718  7718 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 18:35:25.935  1014  1467 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 18:35:25.935  1014  1467 D PackageManager: START PACKAGE DELETE: observer{690139770}
08-23 18:35:25.935  1014  1467 D PackageManager: pkg{<packageName>}
,08-23 18:35:25.935  1014  1467 D PackageManager: user{0}
08-23 18:35:25.935  1014  1467 D PackageManager: caller{2000}
08-23 18:35:25.935  1014  1467 D PackageManager: flags{2}
08-23 18:35:25.935  1014  1467 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 18:35:25.935  1014  1467 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-23 18:35:25.935  1014  1467 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 18:35:25.935  1014  1467 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-23 18:35:25.935  1014  1800 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-23 18:35:25.935  1014  1800 D SecContentProvider2: mCursor = null
,08-23 18:35:25.945  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 18:35:25.945  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 18:35:25.945  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 18:35:25.945  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 18:35:25.945  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-23 18:35:25.955  7718  7718 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:25.955  7718  7718 D ActivityThread: Added TimaKeyStore provider
08-23 18:35:25.955  1014  1054 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-23 18:35:25.975  1014  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-23 18:35:25.975  1014  1040 I ActivityManager: Killing 6794:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-23 18:35:26.065  1014  1054 W PackageSettings: Skipping PackageSetting{264210bf com.example.hello/10168} due to missing metadata
,08-23 18:35:26.085  1014  1040 I ActivityManager:   Force finishing activity ActivityRecord{38d08f7 u0 com.test.thalitest/.MainActivity t2}
,08-23 18:35:26.095  1014  1040 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 18:35:26.095   287   287 E SMD     : DCD OFF,
,08-23 18:35:26.105  7718  7718 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-23 18:35:26.105  7718  7718 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-23 18:35:26.105  7718  7718 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-23 18:35:26.105  1014  1040 D InputDispatcher: Focus left window: 6794
,08-23 18:35:26.105   257   445 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-23 18:35:26.115   257   447 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-23 18:35:26.125  1014  1040 D InputDispatcher: Focused application released
,08-23 18:35:26.125  1014  1045 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 18:35:26.125  1014  1040 D FocusedStackFrame: Set to : 0
,08-23 18:35:26.135  1014  1040 W ActivityManager: mDVFSHelper.acquire(),
,08-23 18:35:26.135  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 18:35:26.135  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 18:35:26.135  1014  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-23 18:35:26.145  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-23 18:35:26.165  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-23 18:35:26.165  7718  7718 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
08-23 18:35:26.165  7718  7718 I PCWCLIENTTRACE_PushUtil: sales region : global
08-23 18:35:26.165  7718  7718 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-23 18:35:26.165  7718  7718 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:26.175  1480  1480 D Launcher: onRestart, Launcher: 560181530
,08-23 18:35:26.195  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 18:35:26.205  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,08-23 18:35:26.205  1872  1872 E SamsungIME: mOCRHelper is null
,08-23 18:35:26.215  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-23 18:35:26.215  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-23 18:35:26.215  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-23 18:35:26.215  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-23 18:35:26.215  2639  2639 I art     : Explicit concurrent mark sweep GC freed 19506(1113KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 900us total 40.637ms
,08-23 18:35:26.225  1014  1479 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-23 18:35:26.225  1014  1479 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-23 18:35:26.225  1014  1479 I ActivityManager: Killing 7074:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-23 18:35:26.225  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,08-23 18:35:26.235  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-23 18:35:26.245  4776  4776 I art     : Explicit concurrent mark sweep GC freed 9624(509KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/21MB, paused 1.546ms total 82.217ms
,08-23 18:35:26.245  1480  1480 D Launcher: onStart, Launcher: 560181530
,08-23 18:35:26.245  1480  1480 D Launcher.HomeView: onStart
,08-23 18:35:26.245  1480  1480 D Launcher: onResume, Launcher: 560181530
,08-23 18:35:26.255  1014  1800 D SettingsProvider: name = kids_home_mode
,08-23 18:35:26.255  1014  1800 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 18:35:26.255  1014  1800 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 18:35:26.255  1014  1800 D SettingsProvider: selectionArgs: false
08-23 18:35:26.255  1014  1800 D SettingsProvider: selectionArgs: 10006
08-23 18:35:26.255  1014  1800 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 18:35:26.255  1014  1800 D SettingsProvider: ret = -1
,08-23 18:35:26.255  1480  1480 D Launcher.HomeView: onResume
,08-23 18:35:26.255  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,08-23 18:35:26.265  1014  1040 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 18:35:26.265  1014  1040 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.sconnect/com.samsung.android.sconnect.periph.PeriphStartReceiver}
08-23 18:35:26.265  1014  1040 W BroadcastQueue: android.os.TransactionTooLargeException
08-23 18:35:26.265  1014  1040 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 18:35:26.265  1014  1040 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 18:35:26.265  1014  1040 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-23 18:35:26.265  1014  1040 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-23 18:35:26.265  1014  1040 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-23 18:35:26.265  1014  1040 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:195)
08-23 18:35:26.265  1014  1040 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:35:26.265  1014  1040 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
08-23 18:35:26.265  1014  1040 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 18:35:26.265  1014  1040 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 18:35:26.265  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-23 18:35:26.265  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 18:35:26.265  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:26.265  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:26.265  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:26.265  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:26.275  1678  1678 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-23 18:35:26.275  7739  7739 E Zygote  : MountEmulatedStorage()
08-23 18:35:26.275  7739  7739 E Zygote  : v2
08-23 18:35:26.275  7739  7739 I libpersona: KNOX_SDCARD checking this for 10121
08-23 18:35:26.275  7739  7739 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:26.285  7739  7739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 18:35:26.285  1014  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7739 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-23 18:35:26.285  7739  7739 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 18:35:26.285  7739  7739 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 18:35:26.305  7739  7739 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:26.305  7739  7739 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:26.315  1014  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
08-23 18:35:26.315  1014  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-23 18:35:26.315  1014  1039 W TextServicesManagerService: no available spell checker services found
,08-23 18:35:26.325  1014  4756 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-23 18:35:26.325  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-23 18:35:26.325  1014  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-23 18:35:26.325  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:26.325  1014  1121 V NetworkStats: performPollLocked(flags=0x3)
,08-23 18:35:26.325  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-23 18:35:26.325  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 18:35:26.345  1014  1121 V NetworkStats: performPollLocked() took 20ms
,08-23 18:35:26.345  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 18:35:26.355  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:26.355  1014  4756 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:26.355  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-23 18:35:26.355  1439  1439 D RegisteredServicesCache: empty dynamic service
,08-23 18:35:26.355  1014  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-23 18:35:26.355  1480  1480 D MenuAppsGridFragment: onResume
,08-23 18:35:26.365  1480  1480 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-23 18:35:26.365  1480  1480 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-23 18:35:26.365  2470  2478 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,08-23 18:35:26.365  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.375  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.375  1014  1467 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-23 18:35:26.375  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:26.375  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 18:35:26.385  1014  1467 D SecContentProvider2: mCursor = null
,08-23 18:35:26.395  1014  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 18:35:26.395  1014  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 18:35:26.395  1014  1319 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-23 18:35:26.395  1014  1319 D BatteryService: stay LED for fully charged
,08-23 18:35:26.395  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.395  1678  1678 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-23 18:35:26.395  1678  1678 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-23 18:35:26.405  1678  1678 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-23 18:35:26.405  1678  1678 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-23 18:35:26.405  1014  1474 D ActivityManager: handle home activity for 0
,08-23 18:35:26.405  1014  1474 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-23 18:35:26.405  1014  1474 D KnoxTimeoutHandler: post home show event for user 0
,08-23 18:35:26.405  1014  1474 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-23 18:35:26.405  1014  1474 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-23 18:35:26.405  1014  1474 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 18:35:26.405  1480  1480 D Launcher.HomeView: onPause
,08-23 18:35:26.405  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 18:35:26.415  7739  7739 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 18:35:26.415  7739  7739 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 18:35:26.415  7739  7739 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 18:35:26.425  1678  1678 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-23 18:35:26.435  1678  1678 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-23 18:35:26.435  7739  7739 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:26.445  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-23 18:35:26.445  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 18:35:26.445  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.445  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-23 18:35:26.445  1014  1014 V EnterpriseBillingPolicy: uID is 10171
08-23 18:35:26.445  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 18:35:26.445  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-23 18:35:26.445  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 18:35:26.445  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 18:35:26.445  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 18:35:26.445  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-23 18:35:26.455  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 18:35:26.455   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-23 18:35:26.455  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 18:35:26.455  1014  1014 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-23 18:35:26.455  7739  7739 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-23 18:35:26.465  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 18:35:26.465  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-23 18:35:26.465  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 18:35:26.475  2025  2208 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 18:35:26.475  1014  1800 D InputDispatcher: Focus entered window: 1480
,08-23 18:35:26.475  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 18:35:26.475  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 18:35:26.475  1480  1480 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 18:35:26.485  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
,08-23 18:35:26.485  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,08-23 18:35:26.485  1014  1467 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
08-23 18:35:26.485  1014  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-23 18:35:26.485  1014  1467 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:26.485  1014  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:26.485  1014  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-23 18:35:26.505  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-23 18:35:26.505  1014  3342 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-23 18:35:26.505  1014  1014 V EnterpriseBillingPolicy: uID is 10171
,08-23 18:35:26.505  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
,08-23 18:35:26.505  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-23 18:35:26.505  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-23 18:35:26.505  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,08-23 18:35:26.505  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{22696388 token=android.os.BinderProxy@34b5d5b2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-23 18:35:26.505  1480  1480 D Launcher.HomeView: onStop
,08-23 18:35:26.515  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 18:35:26.515  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-23 18:35:26.515  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 18:35:26.515  1014  1467 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 18:35:26.525  7739  7739 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-23 18:35:26.525  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-23 18:35:26.525  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 18:35:26.525  1014  7756 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 18:35:26.525  1014  1467 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6794 uid 10171
,08-23 18:35:26.535  1014  1014 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-23 18:35:26.535  1014  1014 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-23 18:35:26.535  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 18:35:26.535  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-23 18:35:26.535  2757  7757 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-23 18:35:26.535  2757  7757 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-23 18:35:26.535  2757  7757 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-23 18:35:26.535  1167  1167 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 18:35:26.535  1167  1167 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 18:35:26.545  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 18:35:26.545  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 18:35:26.545  1872  1872 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-23 18:35:26.555  1014  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-23 18:35:26.575  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.575  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.585  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 18:35:26.585  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 18:35:26.585  1167  1167 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 18:35:26.595  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.595  7550  7550 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 18:35:26.595  7550  7581 D HeadsetStateMachine: Disconnected process message: 10
,08-23 18:35:26.595  1014  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-23 18:35:26.595  1014  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 18:35:26.595  1014  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 18:35:26.605  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.605  1014  1800 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 18:35:26.615  7137  7137 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
08-23 18:35:26.615  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-23 18:35:26.615  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:26.615  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:26.615  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:26.615  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:26.615  1014  4757 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 18:35:26.625  1014  1054 I art     : Explicit concurrent mark sweep GC freed 86071(5MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 24MB/36MB, paused 5.996ms total 337.483ms
,08-23 18:35:26.625  2757  7757 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-23 18:35:26.625  2757  7757 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-23 18:35:26.625  2757  7757 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-23 18:35:26.625  7761  7761 I libpersona: KNOX_SDCARD checking this for 10001
08-23 18:35:26.625  7761  7761 E Zygote  : MountEmulatedStorage()
08-23 18:35:26.625  7761  7761 I libpersona: KNOX_SDCARD not a persona
08-23 18:35:26.625  7761  7761 E Zygote  : v2
08-23 18:35:26.625  1014  1040 W ActivityManager: mDVFSHelper.release()
08-23 18:35:26.625  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.625  2757  7757 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
08-23 18:35:26.625  7761  7761 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 18:35:26.635  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7761 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 18:35:26.635  2757  7757 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
08-23 18:35:26.635  7761  7761 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:26.635  7761  7761 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 18:35:26.635  2757  7757 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-23 18:35:26.635  2757  7757 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-23 18:35:26.635  2757  7757 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-23 18:35:26.635  1014  1014 I MotionRecognitionService: Plugged
08-23 18:35:26.635  1167  1167 I StatusBar: Icon Only
08-23 18:35:26.635  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
08-23 18:35:26.635  1167  1167 D PanelView: There is/are notification(s) 
,08-23 18:35:26.665  2757  7757 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-23 18:35:26.665  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{200be597 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:146692
,08-23 18:35:26.665  7761  7761 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 18:35:26.665  7761  7761 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:26.665  1014  4757 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-23 18:35:26.665  1014  4757 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-23 18:35:26.665  1014  4757 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:26.665  1014  4757 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:26.665  1014  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-23 18:35:26.675  7176  7176 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-23 18:35:26.675  7176  7176 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-23 18:35:26.675  7176  7176 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-23 18:35:26.685  7176  7176 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-23 18:35:26.685  7176  7176 I SA      : [OR] == isSIMCardReady false ==
,08-23 18:35:26.685  7176  7176 I SA      : [SCU] == networkStateCheck == true
08-23 18:35:26.685  2757  7757 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-23 18:35:26.685  7176  7176 I SA      : [DM] getCountryCodeFromCSC : PL
08-23 18:35:26.685  7176  7176 I SA      : isChinaCountryCode : false
08-23 18:35:26.685  7176  7176 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-23 18:35:26.685  7176  7176 I SA      : [OR] == networkStateCheck true ==
,08-23 18:35:26.695  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.695  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 18:35:26.695  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 18:35:26.705  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.705  7176  7176 I SA      : [OR] GetMyCountryZoneTask
,08-23 18:35:26.705  7176  7176 I SA      : [OR] onReceive END
,08-23 18:35:26.705  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 18:35:26.705  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 18:35:26.705  6953  7776 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-23 18:35:26.705  6953  7776 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 18:35:26.705  6953  7776 I System.out: (HTTPLog)-Static: isShipBuild true
08-23 18:35:26.705  6953  7776 I System.out: (HTTPLog)-Thread-1245-434797657: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-23 18:35:26.705  6953  7776 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 18:35:26.705   276   968 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 18:35:26.705   276   968 D Netd    : getNetworkForDns: using netid 504 for uid 10102
08-23 18:35:26.705  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 18:35:26.705  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 18:35:26.715  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 18:35:26.715  1014  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-23 18:35:26.715  1222  1222 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:26.715  7230  7230 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-23 18:35:26.725  1014  1027 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-23 18:35:26.725  1014  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-23 18:35:26.725  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-23 18:35:26.725  1014  1039 W libprocessgroup: failed to open /acct/uid_10121/pid_7074/cgroup.procs: No such file or directory
,08-23 18:35:26.725  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:26.725  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:26.725  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-23 18:35:26.745  6953  7776 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 18:35:26.745  1014  1054 D PackageManager: delete codoeFile: 
,08-23 18:35:26.745  1014  1474 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-23 18:35:26.745  1014  1474 D SecContentProvider2: mCursor = null
,08-23 18:35:26.755  7176  7777 I SA      : [SRS] prepareGetMyCountryZone
,08-23 18:35:26.755  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-23 18:35:26.755  1014  1054 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-23 18:35:26.755  1014  1054 D PackageManager: result of delete: 1{690139770}
,08-23 18:35:26.765  7176  7777 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-23 18:35:26.765  7176  7777 I SA      : [SSP] query invoked
,08-23 18:35:26.765  7710  7710 D AndroidRuntime: Shutting down VM
,08-23 18:35:26.775  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 18:35:26.775  1014  1054 D PackageManager: userId{-1}
08-23 18:35:26.775  1014  1054 D PackageManager: andCode{true}
,08-23 18:35:26.775  7153  7153 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:35:26.775  7153  7153 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-23 18:35:26.775  7153  7153 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-23 18:35:26.775  7153  7153 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
08-23 18:35:26.775  7176  7777 I SA      : [TPMU] GetMccFromDB : null
08-23 18:35:26.785  7176  7777 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-23 18:35:26.785  7176  7777 I SA      : [LBE] isSupportCheckDomainRegion : false
08-23 18:35:26.785  7176  7777 I SA      : [TPM] isNoProxy(default) : true
,08-23 18:35:26.785  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-23 18:35:26.785  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:26.785  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:26.785  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:26.785  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:26.795  7787  7787 E Zygote  : MountEmulatedStorage()
08-23 18:35:26.795  7787  7787 E Zygote  : v2
08-23 18:35:26.795  7787  7787 I libpersona: KNOX_SDCARD checking this for 10003
08-23 18:35:26.795  7787  7787 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:26.795  7787  7787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:26.795  7787  7787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 18:35:26.805  7787  7787 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 18:35:26.805  7176  7777 E File    : fail readDirectory() errno=2
,08-23 18:35:26.815  1014  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7787 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-23 18:35:26.815  6953  7776 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-23 18:35:26.825  7787  7787 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:26.825   305   305 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 23.002ms
08-23 18:35:26.825  7787  7787 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:26.845   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 767us total 18.346ms
,08-23 18:35:26.865   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 19.543ms
,08-23 18:35:26.895  1014  1251 I ActivityManager: Killing 7195:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-23 18:35:26.955  7215  7215 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-23 18:35:26.955  7215  7215 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-23 18:35:26.955  1480  1480 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@34b5d5b2 time:146988
,08-23 18:35:26.965  7215  7215 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-23 18:35:26.965  1014  4757 D PersonaManager: isKioskContainerExistOnDevice
,08-23 18:35:26.975  7215  7215 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-23 18:35:26.975  1014  1319 I ActivityManager: Killing 4297:com.google.process.gapps/u0a11 (adj 15): empty #21
,08-23 18:35:26.975  7710  7710 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 18:35:26.985  2817  2817 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 18:35:26 GMT+02:00 2016
,08-23 18:35:26.985  1014  4756 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-23 18:35:26.985  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-23 18:35:26.985  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:26.985  1014  4756 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 18:35:26.985  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 18:35:26.995  2817  2817 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-23 18:35:26.995  2817  2817 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-23 18:35:26.995  2817  2817 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 18:35:26.995  2817  2817 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 18:35:27.005  2817  7806 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-23 18:35:27.005  2817  7806 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-23 18:35:27.005  2817  7806 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-23 18:35:27.005  2817  7806 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-23 18:35:27.005  2817  7806 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-23 18:35:27.015  2817  7806 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-23 18:35:27.015  2817  7806 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-23 18:35:27.025  2817  2817 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-23 18:35:27.075  1014  1026 I ActivityManager: Killing 7434:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-23 18:35:27.095  1014  1478 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-23 18:35:27.105  1014  1478 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-23 18:35:27.105  1014  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-23 18:35:27.105  1014  1478 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-23 18:35:27.105  1014  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-23 18:35:27.115  1014  4756 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 18:35:27.115  1014  4756 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-23 18:35:27.115  1014  4756 W ActivityManager: userId = 0, bbcId = -10000
08-23 18:35:27.115  1014  4756 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 18:35:27.115  1014  4756 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 18:35:27.125   276   968 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 18:35:27.125   276   968 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-23 18:35:27.125  4776  4776 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-23 18:35:27.135  4776  7266 I iu.UploadsManager: num queued entries: 0
,08-23 18:35:27.145  4776  7266 I iu.UploadsManager: num updated entries: 0
,08-23 18:35:27.145  4776  7266 I iu.SyncManager: NEXT; no task
,08-23 18:35:27.145  7230  7230 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-23 18:35:27.155  7230  7230 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
08-23 18:35:27.155  7230  7230 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
08-23 18:35:27.155  7230  7230 D InitializeManagerStateMachine: exit::IDLE
08-23 18:35:27.155  7230  7230 D InitializeManagerStateMachine: entry::NETWORK_CHECK
08-23 18:35:27.155  7230  7230 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-23 18:35:27.155  7230  7230 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-23 18:35:27.155  7230  7230 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-23 18:35:27.155  7230  7230 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-23 18:35:27.155  7230  7230 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-23 18:35:27.155  7230  7230 D InitializeManagerStateMachine: entry::SUCCESS
08-23 18:35:27.155  7230  7230 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-23 18:35:27.165  1014  1026 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gsf
08-23 18:35:27.165  7230  7230 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-23 18:35:27.165  7230  7230 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-23 18:35:27.165  7230  7230 D InitializeManagerStateMachine: exit::SUCCESS
08-23 18:35:27.165  7230  7230 D InitializeManagerStateMachine: entry::IDLE
,08-23 18:35:27.165  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:27.165  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:27.165  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 18:35:27.165  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 18:35:27.175  7810  7810 E Zygote  : MountEmulatedStorage(),
08-23 18:35:27.175  7810  7810 E Zygote  : v2
,08-23 18:35:27.175  7810  7810 I libpersona: KNOX_SDCARD checking this for 10011
,08-23 18:35:27.175  7810  7810 I libpersona: KNOX_SDCARD not a persona
,08-23 18:35:27.185  1014  1026 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7810 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-23 18:35:27.185  7810  7810 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 18:35:27.185  7810  7810 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 18:35:27.185  7810  7810 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-23 18:35:27.205  7810  7810 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 18:35:27.205  7810  7810 D ActivityThread: Added TimaKeyStore provider
,08-23 18:35:27.235  7810  7810 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-23 18:35:27.245  7810  7810 E SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gsf/databases/gservices.db" with flag (131138) and mode_t (0) due to error (30),

```
