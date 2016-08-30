#### Test 83243049e1001da_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system,
08-30 12:37:29.850  1016  1738 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 12:37:29.850  1016  1738 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 12:37:29.850  1016  1738 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 12:37:29.850  1016  1738 D BatteryService: stay LED for fully charged
08-30 12:37:29.850  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-30 12:37:29.850  1016  1016 I MotionRecognitionService: Plugged
08-30 12:37:29.850  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
08-30 12:37:29.860  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 12:37:29.860  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
08-30 12:37:29.860  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 12:37:29.860  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-30 12:37:29.870  3161  3161 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 12:37:29.870  3161  3265 D HeadsetStateMachine: Disconnected process message: 10
08-30 12:37:29.880  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 12:37:29.880  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 12:37:29.880  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 12:37:30.120  6806  6806 D AndroidRuntime: 
08-30 12:37:30.120  6806  6806 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 12:37:30.120  6806  6806 D AndroidRuntime: CheckJNI is OFF
08-30 12:37:30.120  6806  6806 D AndroidRuntime: readGMSProperty: start
08-30 12:37:30.120  6806  6806 D AndroidRuntime: readGMSProperty: already setted!!
08-30 12:37:30.120  6806  6806 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 12:37:30.120  6806  6806 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 12:37:30.120  6806  6806 D AndroidRuntime: readGMSProperty: end
08-30 12:37:30.120  6806  6806 D AndroidRuntime: addProductProperty: start
08-30 12:37:30.280  6806  6806 E AffinityControl: AffinityControl: registerfunction enter
08-30 12:37:30.310  6806  6806 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 12:37:30.330  1016  1323 E PersonaManagerService: inState():  stateMachine is null !!
08-30 12:37:30.330  1016  1323 I PersonaManagerService: PersonaId don't exist
08-30 12:37:30.330  1016  1323 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-30 12:37:30.330  1016  1323 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 12:37:30.350  1016  1323 W ActivityManager: mDVFSHelper.acquire()
08-30 12:37:30.350   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-30 12:37:30.350   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-30 12:37:30.360  1016  1323 D FocusedStackFrame: Set to : 0
08-30 12:37:30.360  1016  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:30.360  1016  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:30.360  1016  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:30.360  1016  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:30.370  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 12:37:30.370  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-30 12:37:30.380  6817  6817 E Zygote  : MountEmulatedStorage()
08-30 12:37:30.380  6817  6817 E Zygote  : v2
08-30 12:37:30.380  6817  6817 I libpersona: KNOX_SDCARD checking this for 10171
08-30 12:37:30.380  6817  6817 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:30.380  6817  6817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:30.380  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 12:37:30.380  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 12:37:30.380  1016  1323 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6817 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 12:37:30.380  1016  1323 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-30 12:37:30.380  1016  1323 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 12:37:30.380   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-30 12:37:30.380  6817  6817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:30.390  6817  6817 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-30 12:37:30.390  1016  1323 D InputDispatcher: Focused application set to: xxxx
08-30 12:37:30.390  1016  1323 D InputDispatcher: Focus left window: 1480
08-30 12:37:30.390  6806  6806 D AndroidRuntime: Shutting down VM
08-30 12:37:30.390  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 12:37:30.390  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 12:37:30.410  6817  6817 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:30.410  6817  6817 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:30.410  1016  1738 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-30 12:37:30.410  1016  1016 V ActivityManager: Display changed displayId=0
08-30 12:37:30.430  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 12:37:30.440  1016  1738 D PersonaManager: isKioskContainerExistOnDevice
08-30 12:37:30.460  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-30 12:37:30.490   258   447 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-30 12:37:30.490   258  2619 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-30 12:37:30.490  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{fdca52a token=android.os.BinderProxy@2a985af3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-30 12:37:30.490  1480  1480 D Launcher: onTrimMemory. Level: 20
08-30 12:37:30.550  6817  6817 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-30 12:37:30.550   288   288 E SMD     : DCD OFF
08-30 12:37:30.570  6817  6817 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6884-6886)
08-30 12:37:30.570  6817  6817 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-30 12:37:30.600  6806  6806 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-30 12:37:30.600  6817  6817 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {313734be}
,08-30 12:37:30.600  6817  6817 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-30 12:37:30.610  6817  6817 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0,
,08-30 12:37:30.650  6817  6817 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-30 12:37:30.660  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:37:30.660  6817  6817 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 12:37:30.710  6817  6817 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 12:37:30.710  6817  6817 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 12:37:30.710  6817  6817 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 12:37:30.710  6817  6817 I Adreno-EGL: Local Branch: 
08-30 12:37:30.710  6817  6817 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 12:37:30.710  6817  6817 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 12:37:30.710  6817  6817 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 12:37:30.790  6817  6817 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 12:37:30.820  6817  6817 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-30 12:37:30.820  6817  6817 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-30 12:37:30.830  6817  6817 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-30 12:37:30.830  6817  6817 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-30 12:37:30.940  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:37:30.950  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{d5e5aff u0 com.test.thalitest/.MainActivity t2}
,08-30 12:37:30.950  6817  6817 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 12:37:30.960  6817  6817 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-30 12:37:30.960  6817  6817 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-30 12:37:30.970  6817  6817 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 12:37:30.980  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:37:30.980  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:37:31.110  6817  6857 D OpenGLRenderer: Render dirty regions requested: true
,08-30 12:37:31.110  1016  1739 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 12:37:31.110  1016  1739 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 12:37:31.110  1016  1739 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 12:37:31.110  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 12:37:31.110  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 12:37:31.120  6817  6844 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-30 12:37:31.130  6817  6817 V ActivityThread: updateVisibility : ActivityRecord{253fea1e token=android.os.BinderProxy@20660fa3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 12:37:31.130  6817  6817 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-30 12:37:31.130  6817  6817 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-30 12:37:31.140   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-30 12:37:31.150  1016  1135 D InputDispatcher: Focus entered window: 6817
,08-30 12:37:31.150  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 12:37:31.150  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 12:37:31.160  6817  6817 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-30 12:37:31.160  6817  6857 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 12:37:31.160  6817  6857 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-30 12:37:31.160  6817  6857 D OpenGLRenderer: Enabling debug mode 0
,08-30 12:37:31.190  1016  1029 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 12:37:31.190  1172  1172 I StatusBar: Icon Only
,08-30 12:37:31.190  1172  1172 D PanelView: There is/are notification(s) 
,08-30 12:37:31.190  1016  6862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 12:37:31.200  1016  1046 I ActivityManager: Displayed Component not be shown by security: +754ms (total +842ms)
,08-30 12:37:31.200  1016  1046 W ActivityManager: mDVFSHelper.release()
08-30 12:37:31.200  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d5e5aff u0 com.test.thalitest/.MainActivity t2} time:107519
,08-30 12:37:31.210   258  2619 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-30 12:37:31.210   258   440 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-30 12:37:31.220  6817  6817 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-30 12:37:31.220  6817  6817 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20660fa3 time:107530
,08-30 12:37:31.230  1882  1882 I SamsungIME: getCurrentCandidateView
,08-30 12:37:31.250  6817  6817 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6817
,08-30 12:37:31.340  1882  1882 D SamsungIME: Dismiss ExpandCandiate
,08-30 12:37:31.500  1882  1882 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 12:37:31.540  1882  1882 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 12:37:31.540  6817  6817 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 12:37:31.550  1882  1882 I SamsungIME: KeybaordView init() : load resources
,08-30 12:37:31.570  1882  1882 I SamsungIME: getCurrentKeyboard
08-30 12:37:31.570  1882  1882 I SamsungIME: getTextKeyboard
,08-30 12:37:31.590  1882  1882 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 12:37:31.610  1016  1319 E Watchdog: !@Sync 3
,08-30 12:37:31.630  6817  6861 D jxcore_app_log: JniHelper::setJavaVM(0xb88682b0), pthread_self() = -1193345232
,08-30 12:37:31.640  6817  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:37:31.640  6817  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:37:31.640  6817  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:37:31.640  6817  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:37:31.640  6817  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 12:37:31.640  6817  6861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@254dc564 added. We now have 1 listener(s)
,08-30 12:37:31.640  6817  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-30 12:37:31.640  6817  6861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-30 12:37:31.640  6817  6861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 12:37:31.640  6817  6861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 12:37:31.650  6817  6861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ca2793 added. We now have 1 listener(s)
,08-30 12:37:31.650  6817  6861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:37:31.660  6817  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:37:31.660  6817  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 12:37:31.660  6817  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 12:37:31.660  6817  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 12:37:31.660  6817  6861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 12:37:31.660  6817  6861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:37:31.670  6817  6861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-30 12:37:31.670  6817  6861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 12:37:31.670  6817  6861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:37:31.670  6817  6861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:37:31.670  6817  6861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:37:31.670  6817  6861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:37:31.670  6817  6861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:37:31.670  6817  6861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:37:31.670  6817  6861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:37:31.670  6817  6861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:37:31.670  6817  6861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 12:37:31.670  6817  6861 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:37:31.680  6817  6861 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 12:37:31.680  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:37:31.680  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:37:31.710  6817  6817 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 12:37:32.300  6817  6870 W jxcore-log: Initializing JXcore engine
08-30 12:37:32.300  6817  6870 W jxcore-log: JXcore engine is ready
,08-30 12:37:32.350  2015  2015 E audit   : type=1400 msg=audit(1472553452.350:205): avc:  denied  { ioctl } for  pid=6870 comm="Thread-1265" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
08-30 12:37:32.350  2015  2015 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:32.350  2015  2015 E audit   : type=1300 msg=audit(1472553452.350:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e1038f8 items=0 ppid=305 ppcomm=main pid=6870 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1265" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-30 12:37:32.350  2015  2015 E audit   : type=1320 msg=audit(1472553452.350:205): 
,08-30 12:37:32.360  6817  6870 W jxcore-log: Starting JXcore engine,
,08-30 12:37:32.470  6817  6870 W jxcore-log: Platform android
08-30 12:37:32.470  6817  6870 W jxcore-log: 
08-30 12:37:32.470  6817  6870 W jxcore-log: Process ARCH arm
08-30 12:37:32.470  6817  6870 W jxcore-log: 
,08-30 12:37:32.600  1016  1485 I art     : Explicit concurrent mark sweep GC freed 25997(1434KB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 2.419ms total 148.582ms
,08-30 12:37:32.600   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-30 12:37:32.600   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-30 12:37:32.680  6817  6870 I jxcore-log: JXcore Cordova bridge is ready!
08-30 12:37:32.680  6817  6870 I jxcore-log: 
,08-30 12:37:32.680  6817  6870 W jxcore-log: JXcore engine is started
,08-30 12:37:32.690  6817  6861 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 12:37:32.690  6817  6817 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 12:37:33.560   288   288 E SMD     : DCD OFF,
,08-30 12:37:36.560   288   288 E SMD     : DCD OFF,
,08-30 12:37:36.830  1016  1048 I PowerManagerService: [PWL] Off : 50s ago,
,08-30 12:37:36.880  1016  3344 D SSRM:n  : SIOP:: AP = 350,
,08-30 12:37:37.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 12:37:38.060  5633  5633 D FactoryTest: Not factory mode
,08-30 12:37:38.060  5633  5633 D FactoryTest: Not factory mode. isFactoryMode() returend false
08-30 12:37:38.070  5633  5633 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-30 12:37:38.070  5633  5633 D MTPRx   : still no open session command from host, so toast
08-30 12:37:38.070  5633  5633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-30 12:37:38.070  5633  5633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-30 12:37:38.070  5633  5633 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114384
,08-30 12:37:38.070  1016  1218 E PersonaManagerService: inState():  stateMachine is null !!
,08-30 12:37:38.070  1016  1218 I PersonaManagerService: PersonaId don't exist
08-30 12:37:38.070  1016  1218 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-30 12:37:38.080  1016  1218 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
08-30 12:37:38.080  1016  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:38.080  1016  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:38.080  1016  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-30 12:37:38.080  1016  1218 W ActivityManager: mDVFSHelper.acquire()
,08-30 12:37:38.110  1016  1218 D PersonaManager: isKioskContainerExistOnDevice
,08-30 12:37:38.110  1016  1218 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 12:37:38.110  1016  1218 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 12:37:38.110  1016  1218 D InputDispatcher: Focused application set to: xxxx
08-30 12:37:38.110  1016  1218 D InputDispatcher: Focus left window: 6817
,08-30 12:37:38.110  5633  5633 E MTPRx   : started activity for popup
,08-30 12:37:38.120  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 12:37:38.120  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 12:37:38.140  5633  5633 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-30 12:37:38.150  5633  5633 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-30 12:37:38.150  5633  5633 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 12:37:38.150  5633  5633 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:37:38.150  5633  5633 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 12:37:38.150  5633  5633 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 12:37:38.170  5633  5633 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-30 12:37:38.170  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 12:37:38.170  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 12:37:38.170  1016  1029 D InputDispatcher: Focused application set to: xxxx
,08-30 12:37:38.170  1016  1029 D InputDispatcher: Focus entered window: 6817
,08-30 12:37:38.180  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 12:37:38.180  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 12:37:38.180  1016  1485 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 12:37:38.180  1016  1485 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3ae6cc2e attribute=null, token = android.os.BinderProxy@110b877e
,08-30 12:37:38.220  5633  5633 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-30 12:37:38.230  5633  5633 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-30 12:37:38.230  5633  5633 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-30 12:37:38.250  6817  6817 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 12:37:38.250  6817  6817 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-30 12:37:38.250  6817  6817 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 12:37:38.250  6817  6817 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-30 12:37:38.260  1016  1739 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 12:37:38.260  1016  1739 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 12:37:38.260  1016  1739 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 12:37:38.260  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-30 12:37:38.260  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 12:37:38.270  6817  6817 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 12:37:38.270  6817  6817 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 12:37:38.270  6817  6817 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d2af80f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f909a13, 16908290=android.view.AbsSavedState$1@f909a13}, android:focusedViewId=100}]}]
08-30 12:37:38.270  6817  6817 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 12:37:38.270  6817  6817 V ActivityThread: updateVisibility : ActivityRecord{253fea1e token=android.os.BinderProxy@20660fa3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 12:37:38.270  6817  6817 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 12:37:38.270  6817  6817 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 12:37:38.270  6817  6817 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20660fa3 time:114589
,08-30 12:37:38.290  1016  1028 D PersonaManager: isKioskContainerExistOnDevice
,08-30 12:37:38.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 12:37:39.560   288   288 E SMD     : DCD OFF
,08-30 12:37:39.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 12:37:39.900  1016  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 12:37:39.900  1016  1485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 12:37:39.900  1016  1485 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 12:37:39.900  1016  1485 D BatteryService: stay LED for fully charged
08-30 12:37:39.910  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 12:37:39.910  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 12:37:39.910  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 12:37:39.910  1016  1016 I MotionRecognitionService: Plugged
,08-30 12:37:39.910  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 12:37:39.910  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 12:37:39.910  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 12:37:39.930  3161  3161 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 12:37:39.930  3161  3265 D HeadsetStateMachine: Disconnected process message: 10
,08-30 12:37:39.940  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 12:37:39.940  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 12:37:39.940  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 12:37:40.410  1016  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 12:37:40.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 12:37:41.080  1016  1041 W ActivityManager: mDVFSHelper.release(),
,08-30 12:37:41.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 12:37:42.560   288   288 E SMD     : DCD OFF
,08-30 12:37:42.600   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-30 12:37:43.690  1016  1095 V AlarmManager: waitForAlarm result :4
,08-30 12:37:43.690  1016  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-30 12:37:43.710  1988  1988 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-30 12:37:43.750  1016  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 12:37:43.750  1016  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-30 12:37:43.750  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:43.750  1016  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:43.750  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:43.850  4688  4688 D ConnectivityManager: CallingUid : 10011, CallingPid : 4688
,08-30 12:37:43.850  1016  1738 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 12:37:43.850  1016  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-30 12:37:43.850  1016  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,08-30 12:37:43.850  1016  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-30 12:37:43.860  4688  6878 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
,08-30 12:37:43.910  4688  6879 W DriveInitializer: Background init thread started
,08-30 12:37:43.940   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-30 12:37:43.940   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 12:37:43.940  4688  6879 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-30 12:37:43.970  1988  1988 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-30 12:37:44.020  1016  1736 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 12:37:44.020  1016  1736 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,08-30 12:37:44.030  1016  1736 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:44.030  1016  1736 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:44.030  1016  1736 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:44.050  1016  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 12:37:44.060  1016  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-30 12:37:44.060  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:44.060  1016  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:44.060  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:44.070  4688  6879 W DriveInitializer: Background init thread ended
,08-30 12:37:44.080  1016  1470 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-30 12:37:44.080  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-30 12:37:44.160  1016  1738 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:44.160  1016  1738 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:44.160  1016  1738 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:44.160  1016  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:44.160  1016  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:44.170  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:44.170  1016  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:44.170  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:44.190  1988  1999 I art     : Explicit concurrent mark sweep GC freed 60241(3MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 10MB/17MB, paused 1.313ms total 81.699ms
,08-30 12:37:44.200  1988  1988 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 12:37:44.210  1988  1988 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 12:37:44.240  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:44.240  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:44.240  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:44.330  1016  1028 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 12:37:44.330  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 12:37:44.330  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:44.330  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:44.330  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:44.340  1988  1988 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 12:37:44.340  1988  1988 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 12:37:44.360  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:44.360  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:44.360  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:44.360  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:44.460  1016  1470 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 12:37:44.460  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-30 12:37:44.460  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:44.460  1016  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:44.460  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:44.480  1988  6887 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-30 12:37:44.480  1988  6887 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:44.490  1988  6887 I System.out: (HTTPLog)-Static: isShipBuild true
,08-30 12:37:44.490  1988  6887 I System.out: (HTTPLog)-Thread-266-354877078: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-30 12:37:44.490  1988  6887 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:44.490   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 12:37:44.490   278  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 12:37:44.490  1988  6887 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 12:37:44.500  1988  6887 I qtaguid : Tagging socket 58 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1988, getuid(): 10011
,08-30 12:37:44.540  1988  6887 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1988, getuid(): 10011
,08-30 12:37:44.750  1016  1470 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 12:37:44.750  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-30 12:37:44.750  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:44.750  1016  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:44.750  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:44.780  4688  6891 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-30 12:37:44.780  4688  6891 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 12:37:44.820  1988  6887 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:44.820   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 12:37:44.820   278  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 12:37:44.860  1988  6887 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 12:37:44.860  1988  6887 I qtaguid : Tagging socket 63 with tag 1000120300000000{268440067,0} for uid -1, pid: 1988, getuid(): 10011
,08-30 12:37:44.910  1988  6887 I qtaguid : Tagging socket 66 with tag 1000120300000000{268440067,0} for uid -1, pid: 1988, getuid(): 10011
,08-30 12:37:45.150  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 12:37:45.150  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-30 12:37:45.150  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:45.150  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 12:37:45.150  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:45.160  1988  6887 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:45.160  1988  6887 I qtaguid : Tagging socket 63 with tag 1000120300000000{268440067,0} for uid -1, pid: 1988, getuid(): 10011
,08-30 12:37:45.210  1016  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:45.210  1016  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:45.210  1016  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:45.210  1016  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:45.250  1016  1323 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:45.250  1016  1323 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:45.260  1016  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:45.260  1016  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:45.280  1016  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-30 12:37:45.280  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:45.280  1016  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 12:37:45.280  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:45.280  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:45.280  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:45.280  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:45.280  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:45.300  6896  6896 E Zygote  : MountEmulatedStorage(),
08-30 12:37:45.300  6896  6896 E Zygote  : v2
08-30 12:37:45.300  6896  6896 I libpersona: KNOX_SDCARD checking this for 10011
08-30 12:37:45.300  6896  6896 I libpersona: KNOX_SDCARD not a persona,
,08-30 12:37:45.300  6896  6896 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-30 12:37:45.300  1016  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 12:37:45.300  1016  1471 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6896 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
08-30 12:37:45.300  1016  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:45.300  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:45.300  1016  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:45.300  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:45.310  6896  6896 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:45.310  6896  6896 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 12:37:45.330  6896  6896 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:45.330  6896  6896 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:45.340  1988  6887 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-30 12:37:45.340  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:45.340  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:45.340  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:45.340  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:45.350  6896  6896 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-30 12:37:45.350  6896  6896 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 12:37:45.360  1988  6887 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,08-30 12:37:45.380  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:45.380  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 12:37:45.380  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:45.400  6896  6896 I MultiDex: VM with version 2.1.0 has multidex support
08-30 12:37:45.400  6896  6896 I MultiDex: install
08-30 12:37:45.400  6896  6896 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 12:37:45.450  6896  6896 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 12:37:45.510  6896  6896 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-30 12:37:45.510  6896  6896 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@18e3d1da: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-30 12:37:45.510  6896  6896 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 12:37:45.530  6896  6896 D ChimeraCfgMgr: Reading stored module config
,08-30 12:37:45.560   288   288 E SMD     : DCD OFF
,08-30 12:37:45.590  6896  6910 I art     : Background sticky concurrent mark sweep GC freed 24570(1161KB) AllocSpace objects, 2(32KB) LOS objects, 1% free, 7MB/7MB, paused 7.665ms total 48.588ms
,08-30 12:37:45.620  6896  6896 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 12:37:45.620  6896  6896 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 12:37:45.630  6896  6913 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0,
,08-30 12:37:45.720   283   684 D WVCdm   : Instantiating CDM.
,08-30 12:37:45.720   283   677 I WVCdm   : CdmEngine::OpenSession
,08-30 12:37:45.720   283   677 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-30 12:37:45.750   283   677 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-30 12:37:45.770   283   677 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-30 12:37:45.830   283   677 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 12:37:45.830   283   684 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 12:37:45.830   283   684 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 12:37:45.830   283   684 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-30 12:37:45.830   283   684 D WVCdm   : PrepareKeyRequest: nonce=1995427982
,08-30 12:37:45.840  4344  4356 I art     : Explicit concurrent mark sweep GC freed 1519(52KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 723us total 22.917ms
,08-30 12:37:45.860  6896  6906 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-30 12:37:45.860  6896  6906 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 12:37:45.860  6896  6906 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 12:37:45.860  6896  6906 I System.out: (HTTPLog)-Thread-1245-167439583: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-30 12:37:45.860  6896  6906 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:45.860   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 12:37:45.860   278  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 12:37:45.860  6896  6906 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 12:37:45.870  6896  6906 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6896, getuid(): 10011
,08-30 12:37:46.180  6896  6906 I qtaguid : Untagging socket 30
,08-30 12:37:46.500  6922  6922 I dex2oat : ----------------------------------------------------
,08-30 12:37:46.500  6922  6922 I dex2oat : <SS>: S T A R T I N G . . .
08-30 12:37:46.500  6922  6922 I dex2oat : <SS>: Zip is absent. Canceled.
08-30 12:37:46.500  6922  6922 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 12:37:46.550  6922  6922 I dex2oat : dex2oat took 47.842ms (threads: 4)
,08-30 12:37:46.560  6896  6906 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 12:37:46.560  6896  6906 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 12:37:46.560  6896  6906 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 12:37:46.560  6896  6906 I Adreno-EGL: Local Branch: 
08-30 12:37:46.560  6896  6906 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 12:37:46.560  6896  6906 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 12:37:46.560  6896  6906 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 12:37:46.900  1016  3344 D SSRM:n  : SIOP:: AP = 380
,08-30 12:37:47.020  6896  6906 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 12:37:47.020  6896  6906 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 12:37:47.020  6896  6906 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 12:37:47.020  6896  6906 I Adreno-EGL: Local Branch: 
08-30 12:37:47.020  6896  6906 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 12:37:47.020  6896  6906 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 12:37:47.020  6896  6906 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 12:37:47.060  6896  6906 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 12:37:47.060  6896  6906 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 12:37:47.060  6896  6906 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 12:37:47.060  6896  6906 I Adreno-EGL: Local Branch: 
08-30 12:37:47.060  6896  6906 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 12:37:47.060  6896  6906 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 12:37:47.060  6896  6906 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 12:37:47.140  1988  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:47.150   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 12:37:47.150   278  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 12:37:47.150  1988  6894 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 12:37:47.150  1988  6894 I qtaguid : Tagging socket 59 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1988, getuid(): 10011
,08-30 12:37:47.190  1988  6894 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1988, getuid(): 10011
,08-30 12:37:47.350  1016  1537 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 12:37:47.350  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-30 12:37:47.350  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:47.360  1016  1537 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:47.360  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:47.380   283   283 I WVCdm   : CdmEngine::CloseSession
,08-30 12:37:47.390   283   283 I WVCdm   : L3 Terminate.
,08-30 12:37:47.410  1016  1466 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:47.410  1016  1466 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:47.410  1016  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:47.410  1016  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:47.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 12:37:47.710  1016  1736 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-30 12:37:47.710  1016  1470 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:47.710  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:47.710  1016  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:47.710  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:47.730  1016  1738 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:47.730  1016  1738 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:47.730  1016  1738 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:47.730  1016  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:47.770  1016  1323 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 12:37:47.770  1016  1323 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 12:37:47.770  1016  1323 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:47.770  1988  1988 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=c56714c5-502c-43ad-8c1c-cb0290a8e792
,08-30 12:37:47.770  1016  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:47.770  1016  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:47.920  1988  2153 W GCoreFlp: No location to return for getLastLocation()
,08-30 12:37:47.950  4688  6929 D UdcContextInitService: registered all accounts: true
,08-30 12:37:47.960  1988  2156 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 12:37:47.970  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:47.970  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:47.970  1988  2171 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
08-30 12:37:47.970  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:47.970  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:47.980  1016  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:47.980  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:47.980  1016  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:47.980  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:47.980  1016  1470 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:47.990  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:47.990  1016  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:47.990  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:48.080  1016  1470 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 12:37:48.080  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-30 12:37:48.080  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:48.080  1988  2171 I art     : Explicit concurrent mark sweep GC freed 81025(4MB) AllocSpace objects, 22(948KB) LOS objects, 39% free, 11MB/19MB, paused 1.889ms total 80.527ms
08-30 12:37:48.080  1016  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:48.080  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:48.210  1016  1323 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:48.210  1016  1323 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:48.210  1016  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:48.210  1016  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:48.250  1016  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:48.250  1016  1135 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:48.250  1016  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:48.250  1016  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:48.250  1988  6937 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 12:37:48.250  1988  6935 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 12:37:48.250  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:48.250  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:48.250  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 12:37:48.250  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:48.280  1988  2171 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 12:37:48.280  1988  2171 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-30 12:37:48.290  1016  1537 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:48.290  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:48.290  1016  1537 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:48.290  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:48.290  1988  6937 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 12:37:48.290  1988  6935 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 12:37:48.290  1016  1218 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:48.290  1016  1218 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:48.290  1016  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:48.290  1016  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:48.300  1988  6942 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:48.300   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 12:37:48.300   278  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 12:37:48.310  1988  6942 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 12:37:48.310  1988  6942 I qtaguid : Tagging socket 80 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1988, getuid(): 10011
,08-30 12:37:48.320  1016  1537 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:48.320  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:48.320  1016  1537 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:48.320  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:48.320  1988  6937 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 12:37:48.320  1988  6935 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 12:37:48.320  1988  6935 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-30 12:37:48.330  1988  6935 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 12:37:48.350  1988  6942 I qtaguid : Tagging socket 82 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1988, getuid(): 10011
,08-30 12:37:48.370  1016  1321 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 12:37:48.500  1016  1739 I art     : Explicit concurrent mark sweep GC freed 32023(1748KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 24MB/36MB, paused 2.460ms total 154.389ms
,08-30 12:37:48.500  1016  1739 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-30 12:37:48.550  4344  4356 I art     : Explicit concurrent mark sweep GC freed 2522(100KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 683us total 19.505ms
,08-30 12:37:48.560   288   288 E SMD     : DCD OFF
,08-30 12:37:48.570  1988  6935 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:48.570   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 12:37:48.570   278  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 12:37:48.580  1988  6935 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 12:37:48.580  1988  6935 I qtaguid : Tagging socket 85 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1988, getuid(): 10011
,08-30 12:37:48.600  1988  6942 I qtaguid : Untagging socket 80
,08-30 12:37:48.600  1988  2171 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-30 12:37:48.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 12:37:48.610  1988  6935 I qtaguid : Tagging socket 88 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1988, getuid(): 10011
,08-30 12:37:48.880  1016  1135 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 12:37:48.890  1988  6935 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:48.890  1988  6935 I qtaguid : Tagging socket 85 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1988, getuid(): 10011
,08-30 12:37:49.030  1016  1738 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 12:37:49.030  1988  6935 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:49.030  1988  6935 I qtaguid : Tagging socket 85 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1988, getuid(): 10011
,08-30 12:37:49.200  1016  1323 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 12:37:49.200  1988  6935 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:49.200  1988  6935 I qtaguid : Tagging socket 85 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1988, getuid(): 10011
,08-30 12:37:49.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 12:37:49.970  1016  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 12:37:49.970  1016  1135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 12:37:49.970  1016  1135 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 12:37:49.970  1016  1135 D BatteryService: stay LED for fully charged
08-30 12:37:49.970  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-30 12:37:49.970  1016  1016 I MotionRecognitionService: Plugged
08-30 12:37:49.970  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 12:37:49.980  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 12:37:49.980  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 12:37:49.980  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 12:37:49.980  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 12:37:50.000  3161  3161 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 12:37:50.000  3161  3265 D HeadsetStateMachine: Disconnected process message: 10
,08-30 12:37:50.010  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 12:37:50.010  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 12:37:50.010  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 12:37:50.400  1988  6941 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 12:37:50.400  1988  6941 I qtaguid : Tagging socket 80 with tag 1000310200000000{268448002,0} for uid 10011, pid: 1988, getuid(): 10011
,08-30 12:37:50.590  1988  6941 I qtaguid : Untagging socket 80
,08-30 12:37:50.590  1988  2171 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-30 12:37:50.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 12:37:50.620  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-30 12:37:51.200  6817  6870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 12:37:51.200  6817  6870 I jxcore-log: 
,08-30 12:37:51.200  6817  6870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 12:37:51.200  6817  6870 I jxcore-log: 
,08-30 12:37:51.200  6817  6870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:37:51.200  6817  6870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:37:51.200  6817  6870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:37:51.200  6817  6870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:37:51.200  6817  6870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:37:51.200  6817  6870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:37:51.200  6817  6870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:37:51.200  6817  6870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:37:51.210  6817  6870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:37:51.210  6817  6870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 12:37:51.210  6817  6870 I jxcore-log: 
,08-30 12:37:51.210  6817  6870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 12:37:51.210  6817  6870 I jxcore-log: 
,08-30 12:37:51.560   288   288 E SMD     : DCD OFF,
,08-30 12:37:51.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 12:37:51.650  6817  6870 I jxcore-log: Running unit tests,
08-30 12:37:51.650  6817  6870 I jxcore-log: 
08-30 12:37:51.650  6817  6870 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 12:37:51.650  6817  6870 I jxcore-log: Failed to execute UT.,
08-30 12:37:51.650  6817  6870 I jxcore-log: 
,08-30 12:37:51.650  6817  6870 I jxcore-log: Unit Test app is loaded,
08-30 12:37:51.650  6817  6870 I jxcore-log: 
,08-30 12:37:51.660  6817  6870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:37:51.660  6817  6870 I jxcore-log: 
,08-30 12:37:51.660  6817  6817 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 12:37:51.670  6817  6870 I jxcore-log: My device name is: samsung-SM-A300FU
08-30 12:37:51.670  6817  6870 I jxcore-log: 
,08-30 12:37:52.120  1016  1739 I ActivityManager: Killing 6408:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-30 12:37:52.610   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 12:37:54.560   288   288 E SMD     : DCD OFF,
,08-30 12:37:54.880  6817  6870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
08-30 12:37:54.880  6817  6870 I jxcore-log: 
,08-30 12:37:55.460  6817  6870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 12:37:55.460  6817  6870 I jxcore-log: 
,08-30 12:37:55.490  6817  6870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 12:37:55.490  6817  6870 I jxcore-log: 
,08-30 12:37:56.930  1016  3344 D SSRM:n  : SIOP:: AP = 380
,08-30 12:37:57.250  6817  6870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 12:37:57.250  6817  6870 I jxcore-log: 
,08-30 12:37:57.550  6817  6870 I jxcore-log: ERROR runTests: 
08-30 12:37:57.550  6817  6870 I jxcore-log: 
,08-30 12:37:57.550  6817  6870 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:37:57.550  6817  6870 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 12:37:57.570  6817  6870 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _functionName: 'loadFile',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _lineNumber: '26',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _columnNumber: '11',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 12:37:57.570  6817  6870 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _functionName: '',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _lineNumber: '38',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _columnNumber: '7',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 12:37:57.570  6817  6870 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _functionName: '',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _lineNumber: '35',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _columnNumber: '3',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 12:37:57.570  6817  6870 I jxcore-log:   { _fileName: 'module.js',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _lineNumber: '621',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _columnNumber: '8',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 12:37:57.570  6817  6870 I jxcore-log:   { _fileName: 'module.js',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _lineNumber: '651',
08-30 12:37:57.570  6817  6870 I jxcore-log:     _columnNumber: '1',
08-30 12:37:57.570  6817  6870 I jxcore-log:    
08-30 12:37:57.570  6817  6870 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 12:37:57.570  6817  6870 I jxcore-log: 
,08-30 12:37:57.570   288   288 E SMD     : DCD OFF
08-30 12:37:57.570  6817  6870 E jxcore-log: Error: 
08-30 12:37:57.570  6817  6870 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:37:57.570  6817  6870 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 12:37:57.570  6817  6870 E jxcore-log: 
,08-30 12:37:57.870  6952  6952 D AndroidRuntime: ,
08-30 12:37:57.870  6952  6952 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 12:37:57.880  6952  6952 D AndroidRuntime: CheckJNI is OFF,
08-30 12:37:57.880  6952  6952 D AndroidRuntime: readGMSProperty: start
08-30 12:37:57.880  6952  6952 D AndroidRuntime: readGMSProperty: already setted!!
08-30 12:37:57.880  6952  6952 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 12:37:57.880  6952  6952 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 12:37:57.880  6952  6952 D AndroidRuntime: readGMSProperty: end
08-30 12:37:57.880  6952  6952 D AndroidRuntime: addProductProperty: start,
,08-30 12:37:58.000  6952  6952 E AffinityControl: AffinityControl: registerfunction enter,
,08-30 12:37:58.030  6952  6952 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-30 12:37:58.040  1016  1738 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-30 12:37:58.040  1016  1738 D PackageManager: START PACKAGE DELETE: observer{1002617974}
08-30 12:37:58.040  1016  1738 D PackageManager: pkg{<packageName>}
08-30 12:37:58.040  1016  1738 D PackageManager: user{0}
08-30 12:37:58.040  1016  1738 D PackageManager: caller{2000}
08-30 12:37:58.040  1016  1738 D PackageManager: flags{2}
08-30 12:37:58.040  1016  1738 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
08-30 12:37:58.040  1016  1738 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 12:37:58.040  1016  1738 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 12:37:58.040  1016  1738 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 12:37:58.050  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-30 12:37:58.050  1016  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 12:37:58.050  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 12:37:58.050  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 12:37:58.050  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true,
,08-30 12:37:58.050  1016  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg,
,08-30 12:37:58.080  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-30 12:37:58.080  1016  1041 I ActivityManager: Killing 6817:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 12:37:58.140  1016  1056 W PackageSettings: Skipping PackageSetting{3c249d8e com.example.hello/10168} due to missing metadata,
,08-30 12:37:58.160  1016  1041 I ActivityManager:   Force finishing activity ActivityRecord{d5e5aff u0 com.test.thalitest/.MainActivity t2}
,08-30 12:37:58.160  1016  1041 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 12:37:58.180  1016  1041 D InputDispatcher: Focus left window: 6817
,08-30 12:37:58.180   258   440 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-30 12:37:58.180   258  1151 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-30 12:37:58.190  1016  1041 D InputDispatcher: Focused application released
,08-30 12:37:58.190  1016  1046 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 12:37:58.200  1016  1041 D FocusedStackFrame: Set to : 0
,08-30 12:37:58.200  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 12:37:58.210  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 12:37:58.210  1016  1041 W ActivityManager: mDVFSHelper.acquire()
,08-30 12:37:58.210  1016  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-30 12:37:58.220  1016  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-30 12:37:58.230  1016  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-30 12:37:58.260  1480  1480 D Launcher: onRestart, Launcher: 1049492021
,08-30 12:37:58.260  1480  1480 D Launcher: onStart, Launcher: 1049492021
08-30 12:37:58.260  1480  1480 D Launcher.HomeView: onStart
,08-30 12:37:58.270  1480  1480 D Launcher: onResume, Launcher: 1049492021
,08-30 12:37:58.270  1016  1218 D SettingsProvider: name = kids_home_mode
,08-30 12:37:58.270  1016  1218 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 12:37:58.270  1016  1218 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 12:37:58.270  1016  1218 D SettingsProvider: selectionArgs: false
08-30 12:37:58.270  1016  1218 D SettingsProvider: selectionArgs: 10006
,08-30 12:37:58.270  1016  1218 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 12:37:58.270  1016  1218 D SettingsProvider: ret = -1
,08-30 12:37:58.270  2643  2643 I art     : Explicit concurrent mark sweep GC freed 19469(1111KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 914us total 39.287ms
,08-30 12:37:58.270  1480  1480 D Launcher.HomeView: onResume
,08-30 12:37:58.280  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-30 12:37:58.290  1016  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 12:37:58.310  1882  1882 E SamsungIME: mOCRHelper is null
,08-30 12:37:58.310  1988  2156 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 12:37:58.330  2909  2909 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 12:37:58 GMT+02:00 2016
,08-30 12:37:58.330  1016  1739 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-30 12:37:58.330  1016  1739 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 12:37:58.330  1016  1739 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:58.330  1016  1739 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:58.330  1016  1739 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 12:37:58.340  4688  4688 I art     : Explicit concurrent mark sweep GC freed 20772(1273KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 12MB/16MB, paused 1.342ms total 115.026ms
,08-30 12:37:58.340  1480  1480 D MenuAppsGridFragment: onResume
,08-30 12:37:58.350  1480  1480 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-30 12:37:58.350  1480  1480 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-30 12:37:58.350  2909  2909 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-30 12:37:58.360  1016  1466 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,08-30 12:37:58.360  1016  1466 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-30 12:37:58.370  1436  1436 D PersonaManager: isKioskContainerExistOnDevice
,08-30 12:37:58.370  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-30 12:37:58.370  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.370  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.370  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.370  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.380  6713  6713 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-30 12:37:58.390  1016  1471 I TactileAssist: enable value -1
08-30 12:37:58.390  1016  1471 I TactileAssist: internal enable value -1
08-30 12:37:58.390  1016  1471 I TactileAssist: intensity value -1
08-30 12:37:58.390  1016  1471 I TactileAssist: saveAppList value true
,08-30 12:37:58.390  2909  2909 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-30 12:37:58.390  6966  6966 E Zygote  : MountEmulatedStorage()
08-30 12:37:58.390  6966  6966 E Zygote  : v2,
08-30 12:37:58.390  6966  6966 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:58.390  6966  6966 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:58.390  1016  1471 I TactileAssist: List of disabled apps :
08-30 12:37:58.390  6966  6966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:58.390  2909  2909 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 12:37:58.400  6966  6966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:37:58.400  6966  6966 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:37:58.400  1016  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6966 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 12:37:58.400  2909  2909 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 12:37:58.400  1016  1537 D ActivityManager: handle home activity for 0
,08-30 12:37:58.400  1436  1436 D RegisteredServicesCache: empty dynamic service
08-30 12:37:58.400  1016  1537 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-30 12:37:58.400  1016  1537 D KnoxTimeoutHandler: post home show event for user 0
08-30 12:37:58.400  2909  6964 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 12:37:58.410  1016  1537 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 12:37:58.410  1016  1537 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 12:37:58.410  1016  1537 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 12:37:58.410  1480  1480 D Launcher.HomeView: onPause
08-30 12:37:58.410  1016  1466 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-30 12:37:58.410  1016  1466 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-30 12:37:58.410  1016  1466 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:58.410  1016  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:58.410  1016  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-30 12:37:58.410  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-30 12:37:58.410  2909  6964 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-30 12:37:58.410  2909  6964 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-30 12:37:58.410  2909  6964 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-30 12:37:58.410  6713  6713 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-30 12:37:58.410  6713  6713 D elm:15121: ElmAgentService : onCreate()
,08-30 12:37:58.420  6713  6973 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-30 12:37:58.420  6713  6973 D elm:15121: MainReceiver.listeningToPackageRemoved()
,08-30 12:37:58.420  6713  6973 D elm:15121: MDMBridge.getInstance()
,08-30 12:37:58.420  1016  1016 I art     : Explicit concurrent mark sweep GC freed 20549(1483KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 24MB/36MB, paused 2.915ms total 184.507ms
,08-30 12:37:58.420  6713  6973 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 12:37:58.440  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-30 12:37:58.440  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.440  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.440  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.440  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.440  6713  6973 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 12:37:58.440  6966  6966 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:58.450  6966  6966 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:58.450  1016  1738 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-30 12:37:58.450  1016  1738 D SecContentProvider2: mCursor = null
,08-30 12:37:58.450  6982  6982 E Zygote  : MountEmulatedStorage()
08-30 12:37:58.450  6982  6982 E Zygote  : v2
08-30 12:37:58.450  6982  6982 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:58.460  6982  6982 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:58.460  6982  6982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:58.460  6982  6982 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:58.460  1016  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6982 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 12:37:58.460  6982  6982 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:37:58.480  6982  6982 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:58.480  6982  6982 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:58.490  6713  6713 D elm:15121: ElmAgentService : onDestroy().
,08-30 12:37:58.500  1016  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
,08-30 12:37:58.500  1016  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-30 12:37:58.500  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 12:37:58.510  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 12:37:58.510  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 12:37:58.510  2909  6964 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-30 12:37:58.520  1016  1122 V NetworkStats: performPollLocked() took 20ms
,08-30 12:37:58.520  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 12:37:58.520  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 12:37:58.530  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 12:37:58.530  2909  6964 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-30 12:37:58.530  2909  6964 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-30 12:37:58.540  1436  1436 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 12:37:58.540  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-30 12:37:58.540  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-30 12:37:58.550  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-30 12:37:58.550  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-30 12:37:58.550  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-30 12:37:58.550  6982  6982 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-30 12:37:58.560  1436  1436 D PersonaManager: isKioskContainerExistOnDevice
,08-30 12:37:58.560  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-30 12:37:58.560   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-30 12:37:58.560  2909  2909 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-30 12:37:58.560  1016  1466 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-30 12:37:58.560  1016  1466 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-30 12:37:58.570  1016  1466 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:58.570  1016  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:58.570  1016  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-30 12:37:58.570  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 12:37:58.580  1016  1135 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-30 12:37:58.580  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 12:37:58.580  1016  1470 D SecContentProvider2: uri = -1 selection = getSealedState
08-30 12:37:58.580  1016  1470 D SecContentProvider2: mCursor = null
,08-30 12:37:58.580  6982  6982 I PopupuiReceiver_KNOX: getSealedState : true
,08-30 12:37:58.590  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.590  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.590  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.590  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.590  1016  1738 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
,08-30 12:37:58.590  1016  1738 D SecContentProvider2: mCursor = null
,08-30 12:37:58.590  1016  1218 D InputDispatcher: Focus entered window: 1480
,08-30 12:37:58.600  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-30 12:37:58.600  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 12:37:58.600  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 12:37:58.600  6982  6982 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-30 12:37:58.600  1016  1736 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-30 12:37:58.600  1016  1736 D SecContentProvider2: mCursor = null
,08-30 12:37:58.600  6982  6982 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-30 12:37:58.600  6982  6982 D PopupuiReceiver: Action package removed
08-30 12:37:58.600  6998  6998 E Zygote  : MountEmulatedStorage()
08-30 12:37:58.600  6998  6998 I libpersona: KNOX_SDCARD checking this for 10048
08-30 12:37:58.600  6998  6998 E Zygote  : v2
08-30 12:37:58.600  6998  6998 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:58.600  6998  6998 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:58.600  1480  1480 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,08-30 12:37:58.610  1016  1135 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6998 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
08-30 12:37:58.610  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-30 12:37:58.610  6998  6998 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:37:58.610  1016  1135 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-30 12:37:58.610  6998  6998 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 12:37:58.620  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.620  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.620  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.620  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.630  7007  7007 E Zygote  : MountEmulatedStorage()
08-30 12:37:58.630  7007  7007 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:58.630  7007  7007 E Zygote  : v2
08-30 12:37:58.630  7007  7007 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:58.630  7007  7007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:58.630  1016  1135 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7007 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 12:37:58.640  7007  7007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:58.640  7007  7007 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:37:58.640  1480  1480 D Launcher.HomeView: onStop
08-30 12:37:58.640  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{fdca52a token=android.os.BinderProxy@2a985af3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-30 12:37:58.640  1016  1135 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 12:37:58.650  1016  1135 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6817 uid 10171
,08-30 12:37:58.660  1016  1471 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-30 12:37:58.660  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.660  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.660  6998  6998 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:58.660  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.660  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.660  6998  6998 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:58.670  1882  1882 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-30 12:37:58.670  1016  7017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 12:37:58.680  7031  7031 E Zygote  : MountEmulatedStorage()
,08-30 12:37:58.680  7031  7031 E Zygote  : v2
08-30 12:37:58.680  7031  7031 I libpersona: KNOX_SDCARD checking this for 10145
08-30 12:37:58.680  7031  7031 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:58.680  7031  7031 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:58.680  7007  7007 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:58.680  7007  7007 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:58.690  7031  7031 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:37:58.690  7031  7031 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 12:37:58.690  1016  1056 I art     : Explicit concurrent mark sweep GC freed 10568(1049KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 4.761ms total 269.338ms
,08-30 12:37:58.690  1016  1471 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7031 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:37:58.700  1016  1471 I ActivityManager: Killing 6538:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-30 12:37:58.700  1016  1041 W ActivityManager: mDVFSHelper.release()
,08-30 12:37:58.720   305   305 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 611us total 25.111ms
,08-30 12:37:58.720  1016  1471 I ActivityManager: Killing 6547:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-30 12:37:58.740  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{13c808ab u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:135052
,08-30 12:37:58.740   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 21.591ms
08-30 12:37:58.740  7031  7031 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:58.750  7031  7031 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:58.760   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 17.010ms
,08-30 12:37:58.760  7007  7007 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 12:37:58.770  1016  1470 D PersonaManager: isKioskContainerExistOnDevice
,08-30 12:37:58.790  1016  1056 D PackageManager: delete codoeFile: 
,08-30 12:37:58.790  7007  7007 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-30 12:37:58.800  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 12:37:58.800  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 12:37:58.800  6998  6998 D Compatibility: onReceive() it will make start service
,08-30 12:37:58.800  1016  1323 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-30 12:37:58.800  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-30 12:37:58.800  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-30 12:37:58.800  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 12:37:58.800  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-30 12:37:58.800  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 12:37:58.800  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 12:37:58.800  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 12:37:58.800  1016  1323 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
08-30 12:37:58.800  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-30 12:37:58.810  1016  1323 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:58.810  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-30 12:37:58.810  1016  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:58.810  1016  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-30 12:37:58.810  1016  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-30 12:37:58.810  1016  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-30 12:37:58.810  1016  1321 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-30 12:37:58.810  1016  1056 D PackageManager: result of delete: 1{1002617974}
,08-30 12:37:58.820  1016  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.820  1016  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.820  1016  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.820  1016  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.820  6952  6952 D AndroidRuntime: Shutting down VM
,08-30 12:37:58.830  1016  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 12:37:58.830  1016  1056 D PackageManager: userId{-1}
08-30 12:37:58.830  1016  1056 D PackageManager: andCode{true}
,08-30 12:37:58.830  6998  7046 D Compatibility: onHandleIntent()
,08-30 12:37:58.830  1016  1471 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-30 12:37:58.830  1016  1471 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-30 12:37:58.830  6998  7046 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-30 12:37:58.830  7047  7047 E Zygote  : MountEmulatedStorage()
08-30 12:37:58.830  7047  7047 E Zygote  : v2
,08-30 12:37:58.830  7047  7047 I libpersona: KNOX_SDCARD checking this for 10052
08-30 12:37:58.830  7047  7047 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:58.830  7047  7047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:58.830  6998  7046 D Compatibility: found: 2
,08-30 12:37:58.830  1016  1321 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7047 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-30 12:37:58.830  7047  7047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:37:58.840  7047  7047 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 12:37:58.840  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-30 12:37:58.840  6998  7046 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-30 12:37:58.840  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.840  6998  7046 D Compatibility: skipping ResolveInfo{3c74aed4 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-30 12:37:58.840  6998  7046 D Compatibility: considering ResolveInfo{16eb387d com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-30 12:37:58.840  6998  7046 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-30 12:37:58.840  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.840  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.840  6998  7046 D Compatibility: enabling receiver ResolveInfo{1b0b5372 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-30 12:37:58.840  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.840  7031  7031 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-30 12:37:58.840  7031  7031 D ThemeInfoUtil: isCurrentFestival = false
,08-30 12:37:58.850  6998  7046 D Compatibility: enabling receiver ResolveInfo{336b73c3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000},
,08-30 12:37:58.860  6998  7046 D Compatibility: enabling receiver ResolveInfo{2dd7e440 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-30 12:37:58.860  7060  7060 E Zygote  : MountEmulatedStorage()
08-30 12:37:58.860  7060  7060 E Zygote  : v2
08-30 12:37:58.860  7060  7060 I libpersona: KNOX_SDCARD checking this for 10087
08-30 12:37:58.860  7047  7047 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:58.860  7060  7060 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:58.860  7060  7060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:58.860  6998  7046 D Compatibility: enabling receiver ResolveInfo{15f7df79 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000},
,08-30 12:37:58.860  7060  7060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 12:37:58.860  7047  7047 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:58.870  1016  1029 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7060 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-30 12:37:58.870  7060  7060 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 12:37:58.870  1016  1029 I ActivityManager: Killing 6584:com.samsung.android.sm/1000 (adj 15): empty #21
,08-30 12:37:58.870  6998  7046 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
08-30 12:37:58.870  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 12:37:58.870  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-30 12:37:58.870  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-30 12:37:58.870  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-30 12:37:58.870  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 12:37:58.870  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 12:37:58.870  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 12:37:58.870  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 12:37:58.870  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 12:37:58.870  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 12:37:58.870  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-30 12:37:58.870  1016  3344 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-30 12:37:58.870  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-30 12:37:58.870  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-30 12:37:58.870  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-30 12:37:58.870  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-30 12:37:58.870  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-30 12:37:58.890  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-30 12:37:58.890  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.890  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.890  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.900  7060  7060 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:58.890  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.900  7060  7060 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:58.910  7079  7079 E Zygote  : MountEmulatedStorage(),
08-30 12:37:58.910  7079  7079 I libpersona: KNOX_SDCARD checking this for 10148
08-30 12:37:58.910  7079  7079 E Zygote  : v2
08-30 12:37:58.910  7079  7079 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:58.910  7079  7079 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:58.910  7079  7079 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:58.910  1016  1029 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7079 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,08-30 12:37:58.910  1016  1161 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-30 12:37:58.910  7079  7079 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 12:37:58.910  1016  1739 I ActivityManager: Killing 6606:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-30 12:37:58.920  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 12:37:58.920  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.920  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.920  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:58.920  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:58.940  7079  7079 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:58.940  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 12:37:58.940  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-30 12:37:58.940  1016  1040 W TextServicesManagerService: no available spell checker services found
,08-30 12:37:58.940  7079  7079 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:58.940  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 12:37:58.950  7095  7095 E Zygote  : MountEmulatedStorage()
08-30 12:37:58.950  7095  7095 E Zygote  : v2
08-30 12:37:58.950  7095  7095 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:58.950  7095  7095 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:58.950  7095  7095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-30 12:37:58.950  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-30 12:37:58.950  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-30 12:37:58.950  1016  1016 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7095 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 12:37:58.950  1016  1016 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-30 12:37:58.950  7095  7095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:37:58.960  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 12:37:58.960  7095  7095 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:37:58.980  1016  1471 I ActivityManager: Killing 6619:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-30 12:37:58.990  7095  7095 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:58.990  7095  7095 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:59.000  1016  1471 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-30 12:37:59.010  1172  1172 I StatusBar: Icon Only
,08-30 12:37:59.010  1172  1172 D PanelView: There is/are notification(s) 
,08-30 12:37:59.010  1016  1135 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-30 12:37:59.030  6952  6952 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 12:37:59.030  7095  7095 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-30 12:37:59.030  7095  7095 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 12:37:59.030  7095  7095 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 12:37:59.040  7079  7079 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-30 12:37:59.050  1016  1323 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-30 12:37:59.050  1016  1323 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-30 12:37:59.050  1016  1323 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:59.050  1016  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 12:37:59.050  1016  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-30 12:37:59.060  1016  1471 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-30 12:37:59.060  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:59.060  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:59.060  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:59.060  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:59.060  7095  7095 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-30 12:37:59.060  7095  7095 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 12:37:59.060  7095  7095 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 12:37:59.060  7095  7095 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-30 12:37:59.070  7112  7112 E Zygote  : MountEmulatedStorage()
08-30 12:37:59.070  7112  7112 E Zygote  : v2
08-30 12:37:59.070  7112  7112 I libpersona: KNOX_SDCARD checking this for 10152
08-30 12:37:59.070  7112  7112 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:59.070  7112  7112 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:59.080  1016  1471 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7112 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-30 12:37:59.080  7112  7112 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 12:37:59.080  1016  1471 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast,
,08-30 12:37:59.080  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-30 12:37:59.080  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:59.080  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:59.080  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:59.080  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:59.080  7112  7112 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:37:59.090  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:37:59.090  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-30 12:37:59.090  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-30 12:37:59.100  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
08-30 12:37:59.100  7122  7122 E Zygote  : MountEmulatedStorage(),
08-30 12:37:59.100  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:37:59.100  7122  7122 E Zygote  : v2,
08-30 12:37:59.100  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 12:37:59.100  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 12:37:59.100  1016  1471 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7122 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
08-30 12:37:59.100  7122  7122 I libpersona: KNOX_SDCARD checking this for 10029,
08-30 12:37:59.100  7122  7122 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:59.110  1016  1471 I ActivityManager: Killing 6653:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-30 12:37:59.110  7122  7122 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:59.110  7122  7122 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:37:59.110  7122  7122 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:37:59.120  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:37:59.120  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:37:59.120  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:37:59.120  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 12:37:59.130  7112  7112 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:59.130  7112  7112 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:59.130  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:37:59.130  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 12:37:59.130  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 12:37:59.130  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 12:37:59.130  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 12:37:59.140  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:37:59.140  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-30 12:37:59.140  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-30 12:37:59.150  1016  1135 I ActivityManager: Killing 6670:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-30 12:37:59.170  7122  7122 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:59.170  7122  7122 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:59.180  1016  1739 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-30 12:37:59.180  1016  1739 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-30 12:37:59.190  1016  1739 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:59.190  1016  1739 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:59.190  1016  1739 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-30 12:37:59.190  1480  1480 I Choreographer: Skipped 30 frames!  The application may be doing too much work on its main thread.
,08-30 12:37:59.190  1480  1480 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a985af3 time:135503
,08-30 12:37:59.190  1016  1470 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-30 12:37:59.190  7112  7112 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-30 12:37:59.190  7112  7112 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
08-30 12:37:59.190  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-30 12:37:59.200  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:59.200  1016  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:59.200  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-30 12:37:59.200  1016  1466 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-30 12:37:59.200  7112  7112 I TapandpayWidget:Utils: Clear T&P info.
,08-30 12:37:59.200  1016  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:59.200  1016  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:59.200  1016  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:59.200  1016  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:59.210  7112  7112 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-30 12:37:59.220  7146  7146 E Zygote  : MountEmulatedStorage()
08-30 12:37:59.220  7146  7146 E Zygote  : v2
08-30 12:37:59.220  7146  7146 I libpersona: KNOX_SDCARD checking this for 10055
08-30 12:37:59.220  7146  7146 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:59.220  1016  1466 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7146 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-30 12:37:59.220  7146  7146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:59.230  1016  1471 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
08-30 12:37:59.230  7146  7146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:59.230  7146  7146 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 12:37:59.230  1016  1466 I ActivityManager: Killing 6692:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-30 12:37:59.240  7122  7153 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-30 12:37:59.250  1016  1466 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-30 12:37:59.250  1016  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:59.250  1016  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:59.250  1016  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:59.250  1016  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:59.260  7146  7146 D TimaKeyStoreProvider: TimaSignature is unavailable

```
