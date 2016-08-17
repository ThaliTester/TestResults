#### Test 808075730b836a0_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
08-17 15:35:30.880   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 15:35:31.130  6783  6783 D AndroidRuntime: 
08-17 15:35:31.130  6783  6783 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 15:35:31.140  6783  6783 D AndroidRuntime: CheckJNI is OFF
08-17 15:35:31.140  6783  6783 D AndroidRuntime: readGMSProperty: start
08-17 15:35:31.140  6783  6783 D AndroidRuntime: readGMSProperty: already setted!!
08-17 15:35:31.140  6783  6783 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 15:35:31.140  6783  6783 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 15:35:31.140  6783  6783 D AndroidRuntime: readGMSProperty: end
08-17 15:35:31.140  6783  6783 D AndroidRuntime: addProductProperty: start
08-17 15:35:31.260  6783  6783 E AffinityControl: AffinityControl: registerfunction enter
08-17 15:35:31.280  6783  6783 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-17 15:35:31.290  1015  1441 E PersonaManagerService: inState():  stateMachine is null !!
08-17 15:35:31.290  1015  1441 I PersonaManagerService: PersonaId don't exist
08-17 15:35:31.290  1015  1441 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-17 15:35:31.290  1015  1441 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-17 15:35:31.310  1015  1441 W ActivityManager: mDVFSHelper.acquire()
08-17 15:35:31.310  1015  1441 D FocusedStackFrame: Set to : 0
08-17 15:35:31.310  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 15:35:31.310  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-17 15:35:31.320  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:31.320  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:31.320  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:31.320  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:31.330  6794  6794 E Zygote  : MountEmulatedStorage()
08-17 15:35:31.330  1015  1441 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6794 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 15:35:31.330  1015  1441 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-17 15:35:31.330  1015  1441 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 15:35:31.330  6794  6794 E Zygote  : v2
08-17 15:35:31.330  6794  6794 I libpersona: KNOX_SDCARD checking this for 10171
08-17 15:35:31.330  1015  1441 D InputDispatcher: Focused application set to: xxxx
08-17 15:35:31.330  6794  6794 I libpersona: KNOX_SDCARD not a persona
08-17 15:35:31.330  1015  1441 D InputDispatcher: Focus left window: 1495
08-17 15:35:31.330  6783  6783 D AndroidRuntime: Shutting down VM
08-17 15:35:31.330  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 15:35:31.330  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 15:35:31.330  6794  6794 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 15:35:31.340   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-17 15:35:31.340  6794  6794 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:31.340  6794  6794 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-17 15:35:31.350  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 15:35:31.350  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 15:35:31.360  6794  6794 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 15:35:31.360  6794  6794 D ActivityThread: Added TimaKeyStore provider
08-17 15:35:31.360  1015  1216 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-17 15:35:31.370  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-17 15:35:31.390  1015  1216 D PersonaManager: isKioskContainerExistOnDevice
08-17 15:35:31.400   259  1037 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-17 15:35:31.400   259   436 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-17 15:35:31.400  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{394a5198 token=android.os.BinderProxy@9a331d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-17 15:35:31.400  1495  1495 D Launcher: onTrimMemory. Level: 20
08-17 15:35:31.520  6794  6794 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-17 15:35:31.540  6783  6783 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-17 15:35:31.560  6794  6794 I cr.library_loader: Time to load native libraries: 13 ms (timestamps 7522-7535)
08-17 15:35:31.560  6794  6794 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-17 15:35:31.580  6794  6794 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7ee8569}
08-17 15:35:31.580  6794  6794 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-17 15:35:31.590  6794  6794 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 15:35:31.630  6794  6794 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-17 15:35:31.630  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 15:35:31.630  6794  6794 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 15:35:31.670  6794  6794 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 15:35:31.670  6794  6794 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 15:35:31.670  6794  6794 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 15:35:31.670  6794  6794 I Adreno-EGL: Local Branch: 
08-17 15:35:31.670  6794  6794 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 15:35:31.670  6794  6794 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 15:35:31.670  6794  6794 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-17 15:35:31.750  6794  6794 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 15:35:31.760  6794  6794 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-17 15:35:31.760  6794  6794 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-17 15:35:31.770  6794  6794 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-17 15:35:31.770  6794  6794 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-17 15:35:31.870   317   317 I ServiceManager: Waiting for service AtCmdFwd...
08-17 15:35:31.900  1015  1041 W ActivityManager: Activity pause timeout for ActivityRecord{36f2d8bb u0 com.test.thalitest/.MainActivity t3}
08-17 15:35:31.900  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 15:35:31.930  6794  6794 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-17 15:35:31.940  6794  6794 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 15:35:31.940  6794  6794 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-17 15:35:31.950  6794  6794 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-17 15:35:31.950  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 15:35:31.950  6794  6794 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 15:35:31.990  6794  6832 D OpenGLRenderer: Render dirty regions requested: true
08-17 15:35:31.990  1015  1134 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-17 15:35:31.990  1015  1134 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 15:35:32.000  1015  1134 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-17 15:35:32.000  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-17 15:35:32.000  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-17 15:35:32.000  6794  6821 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-17 15:35:32.000  6794  6794 V ActivityThread: updateVisibility : ActivityRecord{1a6ec49 token=android.os.BinderProxy@3c53ff02 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-17 15:35:32.010  6794  6794 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 15:35:32.010  6794  6794 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 15:35:32.020   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-17 15:35:32.030  1015  1027 D InputDispatcher: Focus entered window: 6794
08-17 15:35:32.030  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 15:35:32.030  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 15:35:32.030  6794  6794 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-17 15:35:32.030  6794  6832 I OpenGLRenderer: Initialized EGL, version 1.4
08-17 15:35:32.040  6794  6832 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-17 15:35:32.040  6794  6832 D OpenGLRenderer: Enabling debug mode 0
08-17 15:35:32.060  1015  3782 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-17 15:35:32.060  1172  1172 I StatusBar: Icon Only
08-17 15:35:32.060  1172  1172 D PanelView: There is/are notification(s) 
08-17 15:35:32.070  1015  6838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-17 15:35:32.080  1015  1046 I ActivityManager: Displayed Component not be shown by security: +682ms (total +4s658ms)
08-17 15:35:32.080  1015  1046 W ActivityManager: mDVFSHelper.release()
08-17 15:35:32.080  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36f2d8bb u0 com.test.thalitest/.MainActivity t3} time:118054
08-17 15:35:32.080  6794  6794 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-17 15:35:32.080  6794  6794 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3c53ff02 time:118059
08-17 15:35:32.090   259   433 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-17 15:35:32.090   259   436 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-17 15:35:32.100  1861  1861 I SamsungIME: getCurrentCandidateView
08-17 15:35:32.240  6794  6794 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6794
08-17 15:35:32.250  1861  1861 D SamsungIME: Dismiss ExpandCandiate
,08-17 15:35:32.410  1861  1861 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 15:35:32.440  6794  6794 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 15:35:32.450  1861  1861 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 15:35:32.460  1861  1861 I SamsungIME: KeybaordView init() : load resources
,08-17 15:35:32.490  1861  1861 I SamsungIME: getCurrentKeyboard
,08-17 15:35:32.490  1861  1861 I SamsungIME: getTextKeyboard
,08-17 15:35:32.520  1861  1861 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-17 15:35:32.530  6794  6840 D jxcore_app_log: JniHelper::setJavaVM(0xb85b92b0), pthread_self() = -1196137848
,08-17 15:35:32.530  6794  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 15:35:32.530  6794  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 15:35:32.530  6794  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 15:35:32.530  6794  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 15:35:32.530  6794  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 15:35:32.530  6794  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cedb867 added. We now have 1 listener(s)
,08-17 15:35:32.540  6794  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-17 15:35:32.540  6794  6840 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 15:35:32.540  6794  6840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 15:35:32.540  6794  6840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-17 15:35:32.550  6794  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28ce2cb2 added. We now have 1 listener(s)
,08-17 15:35:32.550  6794  6840 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:35:32.550  6794  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:35:32.550  6794  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-17 15:35:32.550  6794  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 15:35:32.550  6794  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 15:35:32.550  6794  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 15:35:32.550  6794  6840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:35:32.560  6794  6840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-17 15:35:32.560  6794  6840 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 15:35:32.560  6794  6840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:32.560  6794  6840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:32.560  6794  6840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:32.560  6794  6840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:32.560  6794  6840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:32.560  6794  6840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:32.560  6794  6840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:32.560  6794  6840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:32.560  6794  6840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 15:35:32.560  6794  6840 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:35:32.570  6794  6840 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 15:35:32.570  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:32.570  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:32.600  6794  6794 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 15:35:32.870   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-17 15:35:32.910   289   289 E SMD     : DCD OFF
,08-17 15:35:33.380  6794  6847 W jxcore-log: Initializing JXcore engine
08-17 15:35:33.380  6794  6847 W jxcore-log: JXcore engine is ready
,08-17 15:35:33.440  2025  2025 E audit   : type=1400 msg=audit(1471440933.440:205): avc:  denied  { ioctl } for  pid=6847 comm="Thread-1265" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-17 15:35:33.440  2025  2025 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:33.440  2025  2025 E audit   : type=1300 msg=audit(1471440933.440:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9df878f8 items=0 ppid=308 ppcomm=main pid=6847 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1265" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-17 15:35:33.440  2025  2025 E audit   : type=1320 msg=audit(1471440933.440:205): 
,08-17 15:35:33.460  6794  6847 W jxcore-log: Starting JXcore engine
,08-17 15:35:33.560  6794  6847 W jxcore-log: Platform android
08-17 15:35:33.560  6794  6847 W jxcore-log: 
08-17 15:35:33.560  6794  6847 W jxcore-log: Process ARCH arm
08-17 15:35:33.560  6794  6847 W jxcore-log: 
,08-17 15:35:33.830  6794  6847 I jxcore-log: JXcore Cordova bridge is ready!
08-17 15:35:33.830  6794  6847 I jxcore-log: 
,08-17 15:35:33.830  6794  6847 W jxcore-log: JXcore engine is started
,08-17 15:35:33.830  6794  6840 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 15:35:33.840  6794  6794 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 15:35:34.520  1015  1094 V AlarmManager: waitForAlarm result :4,
08-17 15:35:34.520  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-17 15:35:34.570  2038  2038 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-17 15:35:34.600  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 15:35:34.600  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-17 15:35:34.600  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:34.600  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:34.600  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:34.630  4773  4773 D ConnectivityManager: CallingUid : 10011, CallingPid : 4773,
,08-17 15:35:34.630  1015  1511 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
08-17 15:35:34.630  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-17 15:35:34.630  1015  1126 D ConnectivityService: apparently satisfied.  currentScore=60
08-17 15:35:34.630  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-17 15:35:34.630  4773  6849 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 15:35:34.690  4773  6850 W DriveInitializer: Background init thread started
,08-17 15:35:34.710   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-17 15:35:34.710   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 15:35:34.710  4773  6850 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-17 15:35:34.750  2038  2038 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-17 15:35:34.790  4773  6850 W DriveInitializer: Background init thread ended
,08-17 15:35:34.800  1015  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 15:35:34.800  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.net.NetworkReportService; callingUser = 0; userId(target) = 0
,08-17 15:35:34.800  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:34.800  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:34.800  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:34.830  4773  5054 D NetworkUsageDbReporter: Started reporting usage
,08-17 15:35:34.830  1015  4287 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-17 15:35:34.830  1015  4287 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,08-17 15:35:34.840  1015  4287 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:34.840  1015  4287 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:34.840  1015  4287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 15:35:34.840  1015  1465 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 15:35:34.840  1015  1465 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-17 15:35:34.850  1015  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:34.850  1015  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:34.850  1015  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:34.870  1015  3782 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-17 15:35:34.870  1015  3782 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-17 15:35:34.910  2038  2038 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 15:35:34.920  4773  5054 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1487
08-17 15:35:34.920  4773  5054 D NetworkUsageDbReporter: keeping row: 1012
,08-17 15:35:34.920  4773  5054 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 3420
08-17 15:35:34.920  4773  5054 D NetworkUsageDbReporter: keeping row: 1011
08-17 15:35:34.920  4773  5054 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2055
08-17 15:35:34.920  4773  5054 D NetworkUsageDbReporter: keeping row: 1010
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 9256
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: keeping row: 1009
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 6087
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: keeping row: 1008
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2286
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: keeping row: 1007
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 104691
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: keeping row: 1006
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 76302
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: keeping row: 1005
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 289267
08-17 15:35:34.930  4773  5054 D NetworkUsageDbReporter: keeping row: 1004
,08-17 15:35:34.940  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:34.940  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:34.940  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:34.940  4773  5054 D NetworkUsageDbReporter: Finished reporting usage.
,08-17 15:35:35.080  1015  3356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-17 15:35:35.920   289   289 E SMD     : DCD OFF
,08-17 15:35:36.830  1015  3322 D SSRM:n  : SIOP:: AP = 330
,08-17 15:35:37.880   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 15:35:38.880   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 15:35:38.920   289   289 E SMD     : DCD OFF,
,08-17 15:35:39.880   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 15:35:40.290  1015  1442 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 15:35:40.290  1015  1442 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 15:35:40.290  1015  1442 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 15:35:40.290  1015  1442 D BatteryService: stay LED for fully charged
08-17 15:35:40.290  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 15:35:40.300  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 15:35:40.300  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 15:35:40.300  1015  1015 I MotionRecognitionService: Plugged
08-17 15:35:40.300  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 15:35:40.300  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-17 15:35:40.310  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 15:35:40.320  3122  3122 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 15:35:40.320  3122  3226 D HeadsetStateMachine: Disconnected process message: 10
,08-17 15:35:40.330  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 15:35:40.330  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 15:35:40.330  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 15:35:40.880   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 15:35:41.370  1015  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-17 15:35:41.880   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 15:35:41.920   289   289 E SMD     : DCD OFF,
,08-17 15:35:42.880   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-17 15:35:44.920   289   289 E SMD     : DCD OFF,
,08-17 15:35:46.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-17 15:35:46.830  6794  6847 I jxcore-log: 
,08-17 15:35:46.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-17 15:35:46.830  6794  6847 I jxcore-log: 
,08-17 15:35:46.840  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-17 15:35:46.840  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:46.840  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:46.840  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:46.840  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:46.840  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:46.840  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-17 15:35:46.840  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:35:46.840  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-17 15:35:46.840  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-17 15:35:46.840  6794  6847 I jxcore-log: 
,08-17 15:35:46.850  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-17 15:35:46.850  6794  6847 I jxcore-log: 
,08-17 15:35:46.880  1015  3322 D SSRM:n  : SIOP:: AP = 350
,08-17 15:35:47.290  6794  6847 D ExecuteNativeTests: Running unit tests,
,08-17 15:35:47.370  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-17 15:35:47.370  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d added. We now have 2 listener(s)
08-17 15:35:47.370  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 15:35:47.370  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:35:47.370  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:35:47.370  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:35:47.370  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 added. We now have 2 listener(s)
08-17 15:35:47.370  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:35:47.370  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:35:47.370  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:35:47.370  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:47.370  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:47.370  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:47.370  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:47.370  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:47.370  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:47.370  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:47.370  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:35:47.380  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:35:47.380  6794  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:35:47.380  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:47.380  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 15:35:47.380  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:35:47.380  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 15:35:47.380  6794  6847 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-17 15:35:47.380  6794  6847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 15:35:47.380  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:35:47.380  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:35:47.380  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 15:35:47.380  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:47.380  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:35:47.380  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.380  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.380  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.380  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.380  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:35:47.380  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:35:47.380  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d removed from the list
08-17 15:35:47.380  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.380  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 removed from the list
08-17 15:35:47.380  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.380  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.390  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.390  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-17 15:35:47.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.390  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
,08-17 15:35:47.390  6794  6847 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-17 15:35:47.390  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.390  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.390  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.390  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.390  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.390  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.390  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.390  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.390  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.390  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.390  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.390  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:35:47.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.390  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 15:35:47.400  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.400  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.400  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.400  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.400  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.400  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.400  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.400  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.400  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.400  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.400  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.400  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.400  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.400  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.400  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.400  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.400  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.400  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.400  6794  6847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 15:35:47.400  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:47.400  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:47.400  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:47.400  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:47.400  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:47.400  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:47.400  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:47.400  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:47.400  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:47.410  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:47.410  6794  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:35:47.410  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:35:47.410  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:35:47.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:35:47.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:47.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:35:47.410  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:47.410  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:35:47.410  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:47.420  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:35:47.430  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 15:35:47.430  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-17 15:35:47.430  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 15:35:47.430  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 15:35:47.430  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:35:47.430  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 15:35:47.450  3122  5089 D BtGatt.GattService: registerClient() - UUID=6fd1e327-5c29-4004-a3d0-ff0e89cd02c7
,08-17 15:35:47.500  3122  3220 D BtGatt.GattService: onClientRegistered() - UUID=6fd1e327-5c29-4004-a3d0-ff0e89cd02c7, clientIf=6
,08-17 15:35:47.500  6794  6806 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 15:35:47.500  3122  3144 D BtGatt.GattService: start scan with filters
,08-17 15:35:47.500  3122  3224 D BtGatt.ScanManager: handling starting scan
,08-17 15:35:47.500  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 15:35:47.500  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 15:35:47.500  3122  3224 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:35:47.500  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 15:35:47.500  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:35:47.510  3122  3220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 15:35:47.510  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:35:47.510  3122  3224 D BtGatt.ScanManager: allow scan with filters
08-17 15:35:47.510  3122  3224 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 15:35:47.510  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:35:47.510  3122  3224 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6,
08-17 15:35:47.510  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 15:35:47.510  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:35:47.510  3122  3220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 15:35:47.510  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.510  3122  3224 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:35:47.510  3122  3224 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 15:35:47.520  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:35:47.520  3122  3220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 15:35:47.520  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.530  6794  6847 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 15:35:47.530  3122  3220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 15:35:47.530  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.530  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:35:47.540  6794  6847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 15:35:47.540  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:35:47.540  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:35:47.540  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:35:47.540  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:35:47.540  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 15:35:47.540  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:35:47.540  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 15:35:47.540  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 15:35:47.540  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 15:35:47.540  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:35:47.540  3122  3140 D BtGatt.GattService: stopScan() - queue size =1
,08-17 15:35:47.540  3122  3224 D BtGatt.ScanManager: filter size is 1
,08-17 15:35:47.550  3122  3224 D BtGatt.ScanManager: delete FilterIndex - 3
,08-17 15:35:47.550  3122  5089 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 15:35:47.550  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:47.550  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:35:47.550  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 15:35:47.550  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:35:47.550  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:35:47.550  3122  3220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-17 15:35:47.550  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.550  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:35:47.550  3122  3224 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:35:47.550  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:35:47.550  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:35:47.550  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 15:35:47.550  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:35:47.560  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:35:47.560  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:35:47.560  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:35:47.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.560  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.560  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:35:47.560  3122  3220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 15:35:47.560  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:35:47.560  3122  3224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 15:35:47.560  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.560  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.560  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.560  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.560  6794  6847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 15:35:47.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:35:47.560  3122  3220 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 15:35:47.570  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.570  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:47.570  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:47.570  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:47.570  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:47.570  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:47.570  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:47.570  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:47.570  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:35:47.570  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:47.570  6794  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:35:47.570  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:47.580  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:35:47.580  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:35:47.580  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:35:47.580  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:47.580  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:35:47.580  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:47.580  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:35:47.590  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 15:35:47.590  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 15:35:47.590  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 15:35:47.590  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:35:47.590  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 15:35:47.590  3122  5089 D BtGatt.GattService: registerClient() - UUID=e7cb9b27-638b-41ef-97f2-2d99e41c4b35
,08-17 15:35:47.640  3122  3220 D BtGatt.GattService: onClientRegistered() - UUID=e7cb9b27-638b-41ef-97f2-2d99e41c4b35, clientIf=6
08-17 15:35:47.640  6794  6806 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-17 15:35:47.640  3122  3144 D BtGatt.GattService: start scan with filters
,08-17 15:35:47.640  3122  3224 D BtGatt.ScanManager: handling starting scan
08-17 15:35:47.640  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 15:35:47.640  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 15:35:47.640  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:35:47.640  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:35:47.640  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:35:47.640  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 15:35:47.640  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:35:47.640  3122  3220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 15:35:47.640  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:35:47.640  3122  3224 D BtGatt.ScanManager: allow scan with filters
08-17 15:35:47.640  3122  3224 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 15:35:47.640  3122  3224 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-17 15:35:47.650  3122  3220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 15:35:47.650  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:35:47.650  3122  3224 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 15:35:47.650  3122  3224 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 15:35:47.650  3122  3220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 15:35:47.650  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.650  3122  3220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 15:35:47.650  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.660  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:35:47.660  6794  6847 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 15:35:47.660  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:35:47.660  6794  6847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 15:35:47.660  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.660  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:35:47.660  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:35:47.660  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:35:47.660  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:35:47.660  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 15:35:47.670  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:35:47.670  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:35:47.670  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:35:47.670  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:35:47.670  3122  3140 D BtGatt.GattService: stopScan() - queue size =1
,08-17 15:35:47.670  3122  3224 D BtGatt.ScanManager: filter size is 1
,08-17 15:35:47.670  3122  3224 D BtGatt.ScanManager: delete FilterIndex - 4
,08-17 15:35:47.670  3122  3220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-17 15:35:47.670  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:35:47.670  3122  3224 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:35:47.670  3122  5089 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 15:35:47.670  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:47.670  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:35:47.670  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 15:35:47.670  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:35:47.670  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:35:47.670  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:35:47.670  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:35:47.670  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:35:47.670  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 15:35:47.680  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:35:47.680  3122  3220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 15:35:47.680  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:35:47.680  3122  3224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 15:35:47.680  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:35:47.680  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.680  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:35:47.680  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.680  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:35:47.680  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.680  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.680  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.680  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:35:47.680  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:35:47.680  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:35:47.680  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.680  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.680  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:35:47.680  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.680  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.680  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.680  6794  6847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 15:35:47.680  3122  3220 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 15:35:47.680  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.680  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:35:47.690  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:47.690  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:47.690  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:47.690  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:47.690  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:47.690  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:47.690  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:47.690  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:35:47.690  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:35:47.690  6794  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:35:47.690  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:47.700  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:47.700  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:35:47.700  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:35:47.700  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:35:47.700  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:47.700  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 15:35:47.700  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 15:35:47.700  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:35:47.700  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:35:47.710  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 15:35:47.710  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:35:47.710  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 15:35:47.710  3122  3144 D BtGatt.GattService: registerClient() - UUID=376f5737-d4b3-4793-9e2f-6ca86446ef21
,08-17 15:35:47.750  3122  3220 D BtGatt.GattService: onClientRegistered() - UUID=376f5737-d4b3-4793-9e2f-6ca86446ef21, clientIf=6
,08-17 15:35:47.750  6794  6802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 15:35:47.750  3122  3221 D BtGatt.GattService: start scan with filters
,08-17 15:35:47.760  3122  3224 D BtGatt.ScanManager: handling starting scan
,08-17 15:35:47.760  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 15:35:47.760  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 15:35:47.760  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:35:47.760  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:35:47.760  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:35:47.760  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:35:47.760  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 15:35:47.760  3122  3220 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 15:35:47.760  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.760  3122  3224 D BtGatt.ScanManager: allow scan with filters
,08-17 15:35:47.760  3122  3224 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 15:35:47.760  3122  3224 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-17 15:35:47.770  3122  3220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 15:35:47.770  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:35:47.770  3122  3224 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 15:35:47.770  3122  3224 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 15:35:47.770  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:35:47.770  3122  3220 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 15:35:47.770  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.770  3122  3220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 15:35:47.770  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.780  6794  6847 I io.jxcore.node.ConnectionHelper: start: OK
08-17 15:35:47.780  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.780  6794  6847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 15:35:47.780  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.780  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:35:47.780  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:35:47.780  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:35:47.780  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:35:47.780  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:35:47.780  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:35:47.780  3122  3144 D BtGatt.GattService: stopScan() - queue size =1
,08-17 15:35:47.780  3122  3224 D BtGatt.ScanManager: filter size is 1
08-17 15:35:47.780  3122  3224 D BtGatt.ScanManager: delete FilterIndex - 5
,08-17 15:35:47.780  3122  3221 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 15:35:47.780  3122  3220 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 15:35:47.780  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:35:47.780  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:35:47.780  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:35:47.780  3122  3224 D BtGatt.ScanManager: stopping BLe Batch
08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:35:47.780  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:35:47.780  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:35:47.780  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:35:47.780  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:35:47.780  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.780  6794  6847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 15:35:47.780  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.780  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.780  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.780  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:35:47.780  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.780  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.780  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.780  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.790  3122  3220 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 15:35:47.790  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:35:47.790  3122  3224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 15:35:47.790  3122  3220 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 15:35:47.790  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.790  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.790  3122  3220 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.790  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
,08-17 15:35:47.790  6794  6847 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-17 15:35:47.790  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.790  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.790  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.790  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.790  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.790  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.790  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.790  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.790  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.790  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.790  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.790  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.790  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
,08-17 15:35:47.790  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 15:35:47.790  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.790  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.790  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.790  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.790  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.790  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.790  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.790  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.790  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.790  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.790  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.790  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.790  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.790  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
,08-17 15:35:47.800  6794  6847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 15:35:47.800  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.800  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.800  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.800  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.800  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.800  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.800  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.800  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.800  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.800  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.800  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.800  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.800  6794  6847 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-17 15:35:47.800  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.800  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.800  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.800  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.800  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.800  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.800  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.800  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:35:47.800  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.800  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:35:47.800  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.800  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 15:35:47.800  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:35:47.800  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 15:35:47.800  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:35:47.800  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.800  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.800  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.800  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.800  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.800  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
,08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.800  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.800  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.800  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.800  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.800  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:35:47.800  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.800  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.800  6794  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:35:47.800  6794  6847 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 15:35:47.800  6794  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:35:47.800  6794  6847 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-17 15:35:47.800  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 15:35:47.800  6794  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 15:35:47.800  6794  6847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:35:47.810  6794  6847 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 15:35:47.810  6794  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:35:47.810  6794  6847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:35:47.810  6794  6847 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-17 15:35:47.810  6794  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:35:47.810  6794  6847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 15:35:47.810  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 15:35:47.810  6794  6847 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 15:35:47.810  6794  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:35:47.810  6794  6847 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 15:35:47.810  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:35:47.810  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.810  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.810  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.810  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.810  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-17 15:35:47.810  6794  6870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1329)
,08-17 15:35:47.810  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.810  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.810  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.810  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.810  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.810  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.810  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.810  6794  6871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1329
08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.810  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.810  6794  6847 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-17 15:35:47.810  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.810  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.810  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.810  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.810  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.810  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.810  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.810  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.810  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.810  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.810  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.810  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.810  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.820  6794  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 15:35:47.820  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:35:47.820  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.820  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.820  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
,08-17 15:35:47.820  6794  6847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 15:35:47.820  6794  6847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 15:35:47.820  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:35:47.820  6794  6847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 15:35:47.820  6794  6847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 15:35:47.820  6794  6847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 15:35:47.820  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-17 15:35:47.820  6794  6847 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 15:35:47.820  6794  6847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 15:35:47.820  6794  6847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 15:35:47.820  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:35:47.820  6794  6847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 15:35:47.820  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.820  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.820  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.820  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.820  6794  6870 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
,08-17 15:35:47.820  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.820  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.820  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.820  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.820  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.820  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.820  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.820  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:35:47.820  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.830  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.830  6794  6870 D BluetoothSocket: connect(): myUserId = 0
08-17 15:35:47.830  6794  6870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 15:35:47.830  3122  5089 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 15:35:47.830  6794  6794 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 15:35:47.830  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:35:47.830  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.830  6794  6794 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-17 15:35:47.830  6794  6872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 15:35:47.830  6794  6870 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
08-17 15:35:47.830  6794  6872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:35:47.830  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.830  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:35:47.830  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.830  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.830  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.830  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.830  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.830  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.830  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.830  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.830  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.830  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.830  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.840  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
,08-17 15:35:47.840  6794  6847 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 15:35:47.840  6794  6847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:35:47.840  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:35:47.840  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.840  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.840  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.840  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.840  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.840  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.840  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.840  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.840  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.840  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.840  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.840  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.840  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.840  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:35:47.840  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:35:47.840  6794  6794 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-17 15:35:47.840  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.840  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.840  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.840  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.840  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.840  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.840  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.840  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.840  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.840  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.840  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.840  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.840  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
,08-17 15:35:47.840  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:47.840  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:47.840  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:47.840  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.840  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.840  6794  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3096237d not in the list
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.840  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
08-17 15:35:47.840  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:47.840  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.840  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:47.840  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:47.840  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:47.840  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:47.850  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6b6272 not in the list
,08-17 15:35:47.850  6794  6847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-17 15:35:47.850  6794  6847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:35:47.850  6794  6847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 15:35:47.850  6794  6847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 15:35:47.850  6794  6847 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 15:35:47.850  6794  6847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 15:35:47.850  6794  6847 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 15:35:47.850  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:35:47.850  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d8eec04 added. We now have 2 listener(s),
08-17 15:35:47.850  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:35:47.850  6794  6847 D BluetoothAdapter: enable()
,08-17 15:35:47.850  6794  6847 D BluetoothAdapter: enable(): BT is already enabled..!
,08-17 15:35:47.870  1015  1442 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 15:35:47.870  1015  1442 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 15:35:47.870  1015  1442 D SecContentProvider2: mCursor = null
,08-17 15:35:47.870  1015  1442 D WifiService: setWifiEnabled: true pid=6794, uid=10171
,08-17 15:35:47.880  1015  1442 W ActivityManager: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 15:35:47.880  1015  1442 W WifiService: Failed getting userId using ActivityManagerNative
08-17 15:35:47.880  1015  1442 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 15:35:47.880  1015  1442 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 15:35:47.880  1015  1442 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 15:35:47.880  1015  1442 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 15:35:47.880  1015  1442 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 15:35:47.880  1015  1442 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 15:35:47.880  1015  1442 D SettingsProvider: name = wifi_on
,08-17 15:35:47.880  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:35:47.880  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30dbe5ed added. We now have 3 listener(s)
08-17 15:35:47.880  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:35:47.890  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:35:47.890  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ffd4c22 added. We now have 4 listener(s)
08-17 15:35:47.890  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:35:47.890  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:35:47.890  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@57f6b3 added. We now have 5 listener(s)
08-17 15:35:47.890  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:35:47.890  1015  1216 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 15:35:47.890  1015  1216 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 15:35:47.890  1015  1216 D SecContentProvider2: mCursor = null
,08-17 15:35:47.900  1015  1216 D WifiService: setWifiEnabled: false pid=6794, uid=10171
,08-17 15:35:47.900  1015  1216 D SettingsProvider: name = wifi_on
,08-17 15:35:47.900  1015  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 15:35:47.900  1378  1378 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 15:35:47.900  1378  1378 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-17 15:35:47.910  1378  1378 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-17 15:35:47.910  6794  6847 D BluetoothAdapter: disable()
08-17 15:35:47.910  1378  1378 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 15:35:47.910  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-17 15:35:47.920  1015  1134 D SettingsProvider: name = bluetooth_on,
,08-17 15:35:47.920   289   289 E SMD     : DCD OFF,
,08-17 15:35:47.920  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:35:47.930  3122  3216 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-17 15:35:47.930  3122  3216 D BluetoothAdapterProperties: Setting state to 13
08-17 15:35:47.930  3122  3216 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 15:35:47.930  3122  3216 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 15:35:47.930  3122  3216 D BluetoothAdapterService: updateAdapterState state is 13
08-17 15:35:47.930  1015  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:35:47.930  1378  1378 I wpa_supplicant: Scan aborted because the firmware maybe busy.
08-17 15:35:47.930  1378  1378 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-17 15:35:47.930  1378  1378 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
08-17 15:35:47.930  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-17 15:35:47.930  1015  1124 E WifiNative-wlan0: do suspend true
,08-17 15:35:47.930  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:35:47.930  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:47.930  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:47.930  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:47.930  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:47.930  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:47.930  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:47.930  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:47.930  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:47.930  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:47.930  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:47.930  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 15:35:47.930  3122  3122 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13,
08-17 15:35:47.930  3122  3216 D BluetoothAdapterService: Autoconnection is available 
08-17 15:35:47.930  3122  3216 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-17 15:35:47.930  3122  3216 D BluetoothAdapterService: terminating service from this receiver
08-17 15:35:47.930  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 15:35:47.930  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:47.930  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:47.930  6794  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:35:47.930  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:47.930  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:47.930  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 15:35:47.930  3122  3122 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e4963f3, channel: 19, state: LISTENING
,08-17 15:35:47.930  3122  3122 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e4963f3, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d11be98, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@12a5c8b0mSocket: android.net.LocalSocket@1bdc4329 impl:android.net.LocalSocketImpl@13f546ae fd:FileDescriptor[76]
08-17 15:35:47.930  3122  3216 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 15:35:47.930  3122  3216 D BluetoothAdapterProperties: mDiscovering is false
08-17 15:35:47.930  3122  3122 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1bdc4329 impl:android.net.LocalSocketImpl@13f546ae fd:FileDescriptor[76]
08-17 15:35:47.930  1015  1465 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 15:35:47.940  3122  3216 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 15:35:47.940  3269  3269 D BluetoothPbap: Proxy object disconnected
,08-17 15:35:47.940  3269  3269 D PbapServerProfile: Bluetooth service disconnected
,08-17 15:35:47.940  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:35:47.940  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:47.940  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:47.940  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:47.940  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:47.940  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:47.940  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:47.940  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:47.940  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:35:47.940  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:47.940  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:35:47.940  3122  3220 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 15:35:47.940  3122  3220 D BluetoothAdapterProperties: Scan Mode:20
,08-17 15:35:47.950  3122  3216 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 15:35:47.950  3122  3216 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-17 15:35:47.950  3122  3216 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-17 15:35:47.950  3122  3216 E bt-btif : cmd socket is not created
,08-17 15:35:47.950  6794  6870 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@259df3e9, channel: -1, state: INIT
08-17 15:35:47.950  6794  6870 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@259df3e9, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33c8086e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31d14b0fmSocket: android.net.LocalSocket@1795b79c impl:android.net.LocalSocketImpl@758e5a5 fd:FileDescriptor[105]
08-17 15:35:47.950  3122  5094 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 15:35:47.950  6794  6870 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1795b79c impl:android.net.LocalSocketImpl@758e5a5 fd:FileDescriptor[105]
08-17 15:35:47.950  6794  6870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1329)
08-17 15:35:47.950  3122  3216 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 15:35:47.950  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:47.950  3122  3244 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-17 15:35:47.950  3122  3244 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-17 15:35:47.960  3122  3244 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 15:35:47.960  3122  3244 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:35:47.960  3122  3244 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:35:47.960  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:47.960  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:47.960  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:47.960  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:47.960  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:47.960  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:47.960  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:47.960  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:47.960  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:35:47.960  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:35:47.960  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:35:47.970  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:47.980  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:35:47.980  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-17 15:35:47.990  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-17 15:35:47.990  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 15:35:47.990  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 15:35:47.990  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 15:35:47.990  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:47.990  1172  1172 D BluetoothTile:  getBluetoothState : 13
,08-17 15:35:47.990  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 15:35:47.990  1861  1861 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 15:35:48.000  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 15:35:48.000  3122  3122 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2616bfdc, channel: 5, state: LISTENING
08-17 15:35:48.000  3122  3122 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2616bfdc, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a45607b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@264ce8e5mSocket: android.net.LocalSocket@3d31fba impl:android.net.LocalSocketImpl@386b5e6b fd:FileDescriptor[74]
08-17 15:35:48.000  3122  3122 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d31fba impl:android.net.LocalSocketImpl@386b5e6b fd:FileDescriptor[74]
,08-17 15:35:48.020  1015  3782 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 15:35:48.020  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 15:35:48.020  3269  3269 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:35:48.020  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:48.030  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:48.040  3122  3122 I BtOppRfcommListener: stopping Accept Thread
,08-17 15:35:48.040  3122  3122 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e3dfdc8, channel: 12, state: LISTENING
,08-17 15:35:48.040  3122  3122 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e3dfdc8, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c72662, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24682e61mSocket: android.net.LocalSocket@3e837d86 impl:android.net.LocalSocketImpl@9df7647 fd:FileDescriptor[80]
,08-17 15:35:48.040  3122  3122 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e837d86 impl:android.net.LocalSocketImpl@9df7647 fd:FileDescriptor[80]
,08-17 15:35:48.040  3122  5094 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 15:35:48.090  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-17 15:35:48.090  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 15:35:48.090  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 15:35:48.090  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-17 15:35:48.100  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.100  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.100  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.100  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.100   279   971 D CommandListener: Clearing all IP addresses on wlan0
,08-17 15:35:48.100  2038  3007 V NativeCrypto: Read error: ssl=0xb8a999a8: I/O error during system call, Connection timed out
08-17 15:35:48.110  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 15:35:48.110  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:35:48.110  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-17 15:35:48.110  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3,
,08-17 15:35:48.110  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 15:35:48.110  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-17 15:35:48.110  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 15:35:48.120  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
08-17 15:35:48.120  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.120  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
08-17 15:35:48.120  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.120  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.120  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:48.120  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 15:35:48.120  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:48.120  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 15:35:48.120  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-17 15:35:48.120  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:35:48.130  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-17 15:35:48.130  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 15:35:48.130  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-17 15:35:48.130  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 15:35:48.130  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 15:35:48.140  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer,
,08-17 15:35:48.140  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 15:35:48.140  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 15:35:48.140  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 15:35:48.140  1015  1046 D WifiDisplayController: disconnect
08-17 15:35:48.140  1015  1046 D WifiDisplayController: updateConnection
08-17 15:35:48.140  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 15:35:48.140  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 15:35:48.140  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-17 15:35:48.140  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 15:35:48.140  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 15:35:48.140  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 15:35:48.140  1015  1123 D WifiP2pService: P2pDisablingState
08-17 15:35:48.140  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-17 15:35:48.140  1015  1442 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 15:35:48.150  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0,
08-17 15:35:48.150  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 },
08-17 15:35:48.150  1015  1124 E WifiNative-wlan0: do suspend true
08-17 15:35:48.150  1015  1123 D WifiP2pService: p2p socket connection lost
08-17 15:35:48.150  1015  1123 D WifiP2pService: P2pDisabledState
,08-17 15:35:48.150  3122  3244 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:35:48.150  3122  3244 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:35:48.160  3122  3244 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
,08-17 15:35:48.160  3122  3244 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:35:48.160  3122  3244 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:35:48.160  3122  3244 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:35:48.160  3122  3244 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 15:35:48.160  3122  3244 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:35:48.160  3122  3244 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:35:48.160  3122  3244 W bt-btif : ag scb idx 1 not allocated
08-17 15:35:48.160  3122  3244 W bt-btif : ag scb idx 2 not allocated
08-17 15:35:48.160  3122  3244 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 15:35:48.160  3122  3304 I bt_userial_mct: exiting userial_read_thread
,08-17 15:35:48.160  3122  3304 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 15:35:48.160  3122  3220 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 15:35:48.160  3122  3246 I bt_vendor: hw_epilog_process
08-17 15:35:48.160  3122  3220 D bt_userial_mct: userial_close
08-17 15:35:48.160  3122  3220 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-17 15:35:48.190  1015  1491 I art     : Explicit concurrent mark sweep GC freed 40516(2MB) AllocSpace objects, 22(352KB) LOS objects, 33% free, 24MB/36MB, paused 2.542ms total 198.225ms
,08-17 15:35:48.190  1015  3781 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 15:35:48.190  1015  3781 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 15:35:48.200  3269  3269 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:35:48.200  1015  3781 W ActivityManager: userId = 0, bbcId = -10000,
08-17 15:35:48.200  1015  3781 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:48.200  1015  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 15:35:48.200  2038  3007 V NativeCrypto: SSL shutdown failed: ssl=0xb8a999a8: I/O error during system call, Broken pipe
,08-17 15:35:48.200  2038  3007 E GCM     : Wifi connection closed with errorCode 20
,08-17 15:35:48.210  1015  1216 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 15:35:48.210  3122  3122 V BluetoothOppManager: cleanUp...
08-17 15:35:48.210  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 15:35:48.210  1015  3782 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-17 15:35:48.210  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.210  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:48.210  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 15:35:48.220  1015  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-5ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:35:48.220  1015  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-7ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:48.220  1015  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 15:35:48.220  1015  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:48.220  1015  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-17 15:35:48.220  1015  1761 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 15:35:48.220  1015  1761 I qtaguid : Tagging socket 372 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
,08-17 15:35:48.220  3269  3269 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:35:48.230  3269  3269 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 15:35:48.230  1015  1761 I qtaguid : Untagging socket 372
,08-17 15:35:48.230  1015  1761 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 15:35:48.230  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:48.230  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 15:35:48.230  1015  1501 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 15:35:48.240  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:48.240  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:48.240  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:48.240  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:48.250  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-17 15:35:48.250  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-17 15:35:48.270  1015  1501 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6884 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-17 15:35:48.270  6884  6884 E Zygote  : MountEmulatedStorage()
08-17 15:35:48.270  6884  6884 E Zygote  : v2
08-17 15:35:48.270  6884  6884 I libpersona: KNOX_SDCARD checking this for 10055
08-17 15:35:48.270  6884  6884 I libpersona: KNOX_SDCARD not a persona
08-17 15:35:48.270  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-17 15:35:48.270  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.270  1015  1126 V NetworkStats: updateIfacesLocked()
08-17 15:35:48.270   279   967 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 15:35:48.270  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 15:35:48.270   279   967 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-17 15:35:48.270  6884  6884 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:48.270   279   971 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:35:48.270  6884  6884 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:48.270  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 15:35:48.270  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 15:35:48.270  1015  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-17 15:35:48.270  1015  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-17 15:35:48.270  6884  6884 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:35:48.280  1015  1126 V NetworkStats: performPollLocked() took 8ms
08-17 15:35:48.280  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:35:48.280  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:35:48.280  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:35:48.280  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.280  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.280  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.280  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:48.280  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 15:35:48.280  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-17 15:35:48.280  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.280  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:35:48.280  1378  1378 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-17 15:35:48.280  1172  1722 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-17 15:35:48.290  1015  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler },
08-17 15:35:48.290  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 15:35:48.290  4773  6849 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 15:35:48.290  1015  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:35:48.290  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 15:35:48.290  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-17 15:35:48.290  1015  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-17 15:35:48.290  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 15:35:48.290  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:35:48.290  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:35:48.290  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.290  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.290  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.290  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.290  1464  1464 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 15:35:48.290  1464  1464 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 15:35:48.290  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-17 15:35:48.290  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 15:35:48.290  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:35:48.300  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 15:35:48.300  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 15:35:48.300  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 15:35:48.300  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.300  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.300  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.300  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.300  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 15:35:48.300  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-17 15:35:48.300  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:35:48.300  1172  1172 D HotspotTile: onReceive : 0, 0
08-17 15:35:48.300  3269  3269 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:35:48.310  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-17 15:35:48.310  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,08-17 15:35:48.310  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:48.310  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:48.310  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:48.310  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:48.310  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:35:48.310  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:48.310  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:48.310  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:48.310  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:35:48.310  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.310  1015  1121 V NetworkStats: updateIfacesLocked()
08-17 15:35:48.310  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-17 15:35:48.310  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:35:48.310  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:35:48.310  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
08-17 15:35:48.310  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 15:35:48.310  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 15:35:48.310  1172  1172 D StatusBar.NetworkController: updateDataNetType()
08-17 15:35:48.310  1172  1172 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 15:35:48.310  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-17 15:35:48.310  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 15:35:48.310  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 15:35:48.320  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:48.320  1015  1121 V NetworkStats: performPollLocked() took 8ms
08-17 15:35:48.320  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:35:48.320  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:48.320  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:48.320  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:48.320  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:35:48.320  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:48.320  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:48.320  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:48.320  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:48.320  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:48.320  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:35:48.320  3122  3220 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
08-17 15:35:48.320  3122  3220 I bt_vendor: bluetooth satus is on
08-17 15:35:48.320  3122  3220 I bt_vendor: bt-vendor : resetting BT status
08-17 15:35:48.320  3122  3220 I bt_vendor: Starting hciattach daemon
,08-17 15:35:48.320  3122  3220 I bt_vendor: try to set false
08-17 15:35:48.320  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.320  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.320  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.320  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-17 15:35:48.320  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.320  3122  3220 I bt_vendor: Starting hciattach daemon
,08-17 15:35:48.320  3122  3220 I bt_vendor: try to set false
08-17 15:35:48.320  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 15:35:48.320  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-17 15:35:48.320  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 15:35:48.320  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:35:48.320  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 15:35:48.320  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:48.320  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.320  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.320  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.320  3122  3220 I bt_vendor: cleanup
,08-17 15:35:48.330  3122  3244 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 15:35:48.330  3122  3220 I GKI_LINUX: GKI_exit_task 0 done
08-17 15:35:48.330  3122  3220 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-17 15:35:48.330  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 15:35:48.330  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 15:35:48.330  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 15:35:48.330  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:35:48.330  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-17 15:35:48.330  3122  3216 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-17 15:35:48.330  3122  3216 D BtConfig.SecureMode: isSecureModeOn:false
08-17 15:35:48.330  3122  3216 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-17 15:35:48.330  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 15:35:48.330  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 15:35:48.330  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 15:35:48.330  3122  3216 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-17 15:35:48.330  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.330  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.330  1015  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:48.330  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 15:35:48.330  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.330  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:48.330  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:48.330  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 15:35:48.330  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 15:35:48.330  3122  3122 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 15:35:48.330  3122  3216 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 15:35:48.330  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:48.330  3122  3122 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 15:35:48.330  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-17 15:35:48.330  3122  3122 D BtGatt.GattService: stop()
08-17 15:35:48.330  3122  3122 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 15:35:48.340  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.340  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:48.340  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:48.340  6884  6884 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 15:35:48.340  1378  1378 I wpa_supplicant: Blacklist: Clear (all) 
08-17 15:35:48.340  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 15:35:48.340  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 15:35:48.340  6884  6884 D ActivityThread: Added TimaKeyStore provider
08-17 15:35:48.340  3122  3216 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-17 15:35:48.340  3122  3122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:35:48.340  6794  6794 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:35:48.340  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:48.340  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 15:35:48.340  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.340  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:48.340  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:48.340  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 15:35:48.340  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 15:35:48.340  3122  3122 D HeadsetService: Received stop request...Stopping profile...
,08-17 15:35:48.340  3122  3216 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 15:35:48.350  1015  3782 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:48.350  1015  3782 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 15:35:48.350  3122  3122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:35:48.350  1015  3782 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.350  1015  3782 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:48.350  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:48.350  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 15:35:48.350  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 15:35:48.350  3122  3216 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 15:35:48.360  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-17 15:35:48.360  3269  3269 D HeadsetProfile: Bluetooth service disconnected
,08-17 15:35:48.360  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:48.360  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 15:35:48.360  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.360  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:48.360  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:48.360  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 15:35:48.360  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 15:35:48.370  3122  3216 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 15:35:48.370  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:48.370  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 15:35:48.370  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.370  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:48.370  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:48.370  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 15:35:48.370  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 15:35:48.370  3122  3216 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 15:35:48.370  1015  1442 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:48.370  1015  1442 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 15:35:48.370  1015  1442 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.370  1015  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:48.370  1015  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:48.380  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 15:35:48.380  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 15:35:48.380  3122  3216 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 15:35:48.380  1015  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:48.380  6884  6884 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-17 15:35:48.380  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-17 15:35:48.380  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.380  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:48.380  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:48.380  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:35:48.380  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:35:48.380  3122  3216 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:35:48.380  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:35:48.380  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:35:48.380  3122  3216 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:35:48.380  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 15:35:48.380  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 15:35:48.380  3122  3216 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-17 15:35:48.380  3122  3216 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 15:35:48.380  3122  3216 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 15:35:48.380  3122  3216 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 15:35:48.390  3122  3216 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 15:35:48.390  3122  3122 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-17 15:35:48.390  3122  3122 D A2dpService: Received stop request...Stopping profile...
08-17 15:35:48.390  3122  3233 D A2dpStateMachine: Exit Disconnected: -1
08-17 15:35:48.390  3122  3122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:35:48.390  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-17 15:35:48.390  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-17 15:35:48.390  3269  3269 D BluetoothA2dp: Proxy object disconnected
08-17 15:35:48.390  3269  3269 D A2dpProfile: Bluetooth service disconnected
08-17 15:35:48.390  3122  3122 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 15:35:48.390  3122  3122 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 15:35:48.390  3122  3122 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 15:35:48.390  3122  3122 D HidService: Received stop request...Stopping profile...
08-17 15:35:48.390  3122  3122 D HidService: Stopping Bluetooth HidService
08-17 15:35:48.390  3122  3122 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 15:35:48.390  3122  3122 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 15:35:48.390  3122  3122 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 15:35:48.390  3122  3122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:35:48.400  3269  3269 D BluetoothInputDevice: Proxy object disconnected
,08-17 15:35:48.400  3269  3269 D HidProfile: Bluetooth service disconnected
,08-17 15:35:48.410  1378  1378 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-17 15:35:48.410  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 15:35:48.410  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-17 15:35:48.410  6884  6884 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-17 15:35:48.410  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 15:35:48.410  3122  3122 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 15:35:48.410  3122  3122 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:35:48.410  6884  6884 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-17 15:35:48.410  6884  6884 D UserAnalysis: Create SecureDbHelper
08-17 15:35:48.410  3122  3122 D HealthService: Received stop request...Stopping profile...
08-17 15:35:48.410  3122  3122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:35:48.420  3122  3122 D PanService: Received stop request...Stopping profile...
08-17 15:35:48.420  3122  3122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:35:48.420  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 15:35:48.420  3122  3122 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 15:35:48.430  6884  6884 D IntelligenceServiceApplication: onCreate(),
,08-17 15:35:48.430  3122  3122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:35:48.430  1378  1378 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-17 15:35:48.430  1378  1378 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 15:35:48.430  1378  1378 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-17 15:35:48.430  1378  1378 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 15:35:48.430  1378  1378 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 15:35:48.440  3269  3269 D BluetoothPan: BluetoothPAN Proxy object disconnected,
,08-17 15:35:48.440  3269  3269 D PanProfile: Bluetooth service disconnected
08-17 15:35:48.440  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:35:48.440  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:48.440  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-17 15:35:48.440  1015  1129 D Tethering: InitialState.processMessage what=4
08-17 15:35:48.440  6884  6884 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-17 15:35:48.440  1015  1129 E Tethering: No numeric data
08-17 15:35:48.440  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:48.440  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-17 15:35:48.440  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:35:48.440  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:48.440  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 15:35:48.440  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-17 15:35:48.440  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:48.440  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-17 15:35:48.450  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:35:48.450  1015  4287 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-17 15:35:48.450  3122  3122 D SapService: Received stop request...Stopping profile...
08-17 15:35:48.450  3122  3122 D SapService: Stopping Bluetooth SapService
08-17 15:35:48.450  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:35:48.450  3122  3122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:35:48.450  1015  1129 D Tethering: clearTetheredNotification()
,08-17 15:35:48.450  3269  3269 D BluetoothMap: Proxy object disconnected
08-17 15:35:48.450  3269  3269 D MapProfile: Bluetooth service disconnected
,08-17 15:35:48.450  3122  3122 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-17 15:35:48.450  3122  3122 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 15:35:48.450  3122  3122 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 15:35:48.450  3122  3122 D BluetoothA2dp: Proxy object disconnected
08-17 15:35:48.450  3122  3122 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-17 15:35:48.450  3122  3234 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-17 15:35:48.450  3122  3122 I GKI_LINUX: GKI_exit_task 2 done
08-17 15:35:48.450  3122  3122 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 15:35:48.450  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.450  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-17 15:35:48.450  6884  6884 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-17 15:35:48.450  3122  3122 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 15:35:48.450  3122  3122 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 15:35:48.450  3122  3122 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 15:35:48.450  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 15:35:48.450  3122  3122 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 15:35:48.450  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 15:35:48.450  3122  3122 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 15:35:48.450  3122  3122 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 15:35:48.450  3122  3122 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 15:35:48.450  3122  3122 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:35:48.460  3269  3269 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 15:35:48.460  3269  3269 D SapProfile: Bluetooth service disconnected
08-17 15:35:48.460  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 15:35:48.460  1172  1172 D HotspotTile: updateTetherState():false, false
08-17 15:35:48.460  3122  3122 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 15:35:48.460  3122  3122 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 15:35:48.460  3122  3122 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-17 15:35:48.460  3122  3122 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 15:35:48.460  3122  3122 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 15:35:48.460  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.460  1015  1121 V NetworkStats: performPollLocked() took 5ms
,08-17 15:35:48.460  3122  3122 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-17 15:35:48.460  3122  3122 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 15:35:48.460  3122  3122 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-17 15:35:48.460  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:48.460  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:35:48.460  3122  3122 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-17 15:35:48.460  3122  3122 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 15:35:48.460  3122  3122 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 15:35:48.460  3122  3216 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-17 15:35:48.460  3122  3216 D BluetoothAdapterProperties: Setting state to 10
08-17 15:35:48.460  3122  3216 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 15:35:48.460  3122  3216 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 15:35:48.460  3122  3216 D BluetoothAdapterService: updateAdapterState state is 10
,08-17 15:35:48.460  3122  3216 D BluetoothAdapterService: Autoconnection is available 
08-17 15:35:48.460  3122  3216 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 15:35:48.460  6794  6806 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:35:48.460  6794  6806 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:35:48.460  3122  3216 I BluetoothAdapterState: Entering OffState
,08-17 15:35:48.470  6794  6806 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-17 15:35:48.470  6794  6806 D BluetoothLeAdvertiser: Exit stop advertising
08-17 15:35:48.470  6794  6806 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-17 15:35:48.470  6794  6806 D BluetoothLeScanner: Exiting stopAllScan
,08-17 15:35:48.470  6884  6884 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,08-17 15:35:48.470  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-17 15:35:48.480  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:48.480  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:48.480  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:48.480  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:48.480  2038  6882 I art     : Explicit concurrent mark sweep GC freed 62780(3MB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 10MB/17MB, paused 1.328ms total 92.877ms,
,08-17 15:35:48.490   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb78ea7c8
08-17 15:35:48.490  6901  6901 I libpersona: KNOX_SDCARD checking this for 10105
,08-17 15:35:48.490   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-17 15:35:48.490  6901  6901 I libpersona: KNOX_SDCARD not a persona
08-17 15:35:48.490  6901  6901 E Zygote  : MountEmulatedStorage()
08-17 15:35:48.490  1015  1027 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6901 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-17 15:35:48.490  6901  6901 E Zygote  : v2
08-17 15:35:48.510  1015  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 15:35:48.490   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-17 15:35:48.510  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
08-17 15:35:48.490   273   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1215387512)
08-17 15:35:48.500  6901  6901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 15:35:48.500  6901  6901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:48.500  6901  6901 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 15:35:48.510  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.510  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:48.510  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:48.520  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:35:48.520  3269  3278 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 15:35:48.520  3122  3140 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 15:35:48.530  2038  2066 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:35:48.530  2038  2066 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 15:35:48.530  1435  1475 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:35:48.530  1435  1475 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 15:35:48.530  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 15:35:48.530  3269  3277 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 15:35:48.540  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 15:35:48.540  1464  2453 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:35:48.540  1464  2453 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:35:48.540  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 15:35:48.540  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:35:48.540  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:35:48.540  3269  3277 D Bluetoothsap: onBluetoothStateChange: up=false
08-17 15:35:48.540  3269  3277 D Bluetoothsap: Unbinding service...
,08-17 15:35:48.540  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 15:35:48.540  1446  1486 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:35:48.540  1446  1486 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:35:48.540  1172  1809 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:35:48.540  1172  1809 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 15:35:48.540  3269  3278 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:35:48.540  3269  3278 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:35:48.540  3122  3144 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:35:48.540  3122  3144 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:35:48.540  3269  3277 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 15:35:48.540  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 15:35:48.540  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 15:35:48.540  3269  3278 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 15:35:48.550  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 15:35:48.550  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 15:35:48.550   273   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-17 15:35:48.550   273   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-17 15:35:48.550   273   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1215387512) wakelock released: 1, error no: 0
08-17 15:35:48.550   273   346 I rmt_storage: 
,08-17 15:35:48.550  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-17 15:35:48.550   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb78ea7c8
08-17 15:35:48.550  6901  6901 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 15:35:48.550  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 15:35:48.550  6901  6901 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:48.550  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 15:35:48.550  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 15:35:48.550  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 15:35:48.560  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 15:35:48.560  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 15:35:48.560  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 15:35:48.560  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 15:35:48.560  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:48.560  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-17 15:35:48.560  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 15:35:48.570  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 15:35:48.570  1172  1172 D BluetoothAdapter: 704121744: getState() :  mService = null. Returning STATE_OFF
08-17 15:35:48.570  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 15:35:48.570  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 15:35:48.570  1172  1172 D BluetoothTile:  getBluetoothState : 10
08-17 15:35:48.570  1172  1755 D BluetoothAdapter: 704121744: getState() :  mService = null. Returning STATE_OFF
08-17 15:35:48.570  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:48.570  1172  1172 D BluetoothAdapter: 704121744: getState() :  mService = null. Returning STATE_OFF
08-17 15:35:48.570  1172  1172 D BluetoothAdapter: 704121744: getState() :  mService = null. Returning STATE_OFF
,08-17 15:35:48.570  1015  1134 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 15:35:48.570  1861  1861 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 15:35:48.580  2038  2220 D BluetoothAdapter: 782673457: getState() :  mService = null. Returning STATE_OFF
08-17 15:35:48.580  2038  2220 D BluetoothAdapter: 782673457: getState() :  mService = null. Returning STATE_OFF
08-17 15:35:48.580  3269  3269 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:48.580  1172  1755 D BluetoothAdapter: 704121744: getState() :  mService = null. Returning STATE_OFF
08-17 15:35:48.580  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 15:35:48.580  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 15:35:48.580  1015  4287 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 15:35:48.580  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:35:48.580  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 15:35:48.580  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:48.580  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:35:48.580  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 15:35:48.580  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 15:35:48.590  3122  3220 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 15:35:48.590  3122  3122 I GKI_LINUX: GKI_exit_task 1 done
08-17 15:35:48.590  3122  3122 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-17 15:35:48.590  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 15:35:48.590  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 15:35:48.590  3122  3122 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 15:35:48.590  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 15:35:48.590  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 15:35:48.590  1378  1378 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 15:35:48.590  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 15:35:48.600  1015  1511 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 15:35:48.600  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 15:35:48.600  1015  1511 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 15:35:48.600  1015  1511 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.600  1015  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:48.600  1015  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 15:35:48.600  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 15:35:48.600  1464  1464 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 15:35:48.600  3122  3122 I art     : System.exit called, status: 0
08-17 15:35:48.600  3122  3122 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 15:35:48.600  1464  1464 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 15:35:48.630  1378  1378 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-17 15:35:48.630  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:48.630  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:35:48.630  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-17 15:35:48.640  1015  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:35:48.650  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.650  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:48.650  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:48.660  1015  1442 I ActivityManager: Process com.android.bluetooth (pid 3122)(adj 0) has died(27,722)
,08-17 15:35:48.700   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 15:35:48.700   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 15:35:48.710  6901  6943 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 15:35:48.710   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 15:35:48.710   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 15:35:48.710  6901  6943 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 15:35:48.730  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-17 15:35:48.730  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 15:35:48.740  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 15:35:48.740  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 15:35:48.740  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.740  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:48.740  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.740  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:48.740  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:35:48.740  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-17 15:35:48.740  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 15:35:48.750  2038  2220 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:35:48.750  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:35:48.750  1172  1172 D HotspotTile: onReceive : 1, 0
08-17 15:35:48.750  3269  3269 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:35:48.750  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:48.760  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:48.800  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:35:48.810  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-17 15:35:48.810  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:35:48.830  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:48.830  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:48.930  6901  6901 D StrictMode: StrictMode policy violation; ~duration=226 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:48.930  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:48.940  6901  6901 D StrictMode: StrictMode policy violation; ~duration=225 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:48.940  6901  6901 D StrictMode: StrictMode policy violation; ~duration=224 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:48.940  6901  6901 D StrictMode: StrictMode policy violation; ~duration=223 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:48.940  6901  6901 D StrictMode: StrictMode policy violation; ~duration=219 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.k.d(PG:583)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:48.940  6901  6901 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:48.940  6901  6901 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:48.940  6901  6901 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:48.940  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:48.950  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 15:35:48.960  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-17 15:35:48.970  1015  1442 I ActivityManager: Killing 6367:com.wsomacp/u0a23 (adj 15): empty #21
08-17 15:35:48.970  1015  3782 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 15:35:48.970  1015  3782 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:35:48.970  1015  3782 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:48.970  1015  3782 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:48.970  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 15:35:48.980  1615  1615 I Hs20UtilService: Starting #8
08-17 15:35:48.980  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 15:35:48.980  1615  1649 I Hs20UtilService: Message received 5007
08-17 15:35:48.990  3269  3269 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 15:35:49.000  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 15:35:49.000  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
08-17 15:35:49.000  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 15:35:49.000  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 15:35:49.010  1015  1442 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 15:35:49.010  1015  1442 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.010  1015  1442 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:49.010  1015  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 15:35:49.010  3269  3269 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 15:35:49.010  3269  3802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 15:35:49.020  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 15:35:49.030  3269  3269 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 15:35:49.030  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 15:35:49.030  6901  6944 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 15:35:49.030  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 15:35:49.030  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 15:35:49.030  3269  3269 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 15:35:49.030  3269  3802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 15:35:49.030  1015  1441 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-17 15:35:49.040  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:49.040  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:49.040  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:49.040  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:49.050  6957  6957 E Zygote  : MountEmulatedStorage(),
08-17 15:35:49.050  6957  6957 I libpersona: KNOX_SDCARD checking this for 10064
08-17 15:35:49.050  6957  6957 E Zygote  : v2,
08-17 15:35:49.050  6957  6957 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:49.050  6957  6957 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 15:35:49.050  6957  6957 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:49.060  6957  6957 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 15:35:49.060  1015  1441 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6957 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 15:35:49.060  1015  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:35:49.060  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.060  1015  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:49.060  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 15:35:49.070  1015  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:35:49.070  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.070  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 15:35:49.070  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:49.080  6957  6957 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:49.080  6957  6957 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:49.100  6957  6957 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 15:35:49.110  2038  2038 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=816c23fa-fa8b-429b-9007-fdb37ff66e0a
08-17 15:35:49.110  6957  6957 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 15:35:49.110  6957  6957 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 15:35:49.130  1015  1216 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-17 15:35:49.130  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-17 15:35:49.130  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.130  1015  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 15:35:49.130  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:49.140  2038  2038 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 15:35:49.140  2038  2038 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 15:35:49.150  6957  6957 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 15:35:49.150  1015  3782 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-17 15:35:49.150  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:49.150  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:49.150  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:49.150  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:49.160  6973  6973 E Zygote  : MountEmulatedStorage(),
,08-17 15:35:49.160  6973  6973 E Zygote  : v2
08-17 15:35:49.160  6973  6973 I libpersona: KNOX_SDCARD checking this for 10065
08-17 15:35:49.160  6973  6973 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:49.170  6973  6973 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:49.170  6973  6973 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:49.170  1015  3782 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6973 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 15:35:49.170  6973  6973 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 15:35:49.170  1015  1511 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:35:49.170  1015  1511 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.170  1015  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 15:35:49.170  1015  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:49.180  1015  1134 I ActivityManager: Killing 6383:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-17 15:35:49.190  6973  6973 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:49.200  6973  6973 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:49.220  6973  6973 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 15:35:49.240  1015  1442 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:49.240  1015  1442 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:49.240  1015  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-17 15:35:49.240  1015  1442 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-17 15:35:49.240  1015  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:49.240  1015  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:49.240  1015  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:49.240  1015  1442 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:49.250  1015  1043 D Tethering: interfaceRemoved wlan0,
08-17 15:35:49.250  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 15:35:49.270  6990  6990 E Zygote  : MountEmulatedStorage()
08-17 15:35:49.270  6990  6990 E Zygote  : v2
08-17 15:35:49.270  6990  6990 I libpersona: KNOX_SDCARD checking this for 10102
08-17 15:35:49.270  6990  6990 I libpersona: KNOX_SDCARD not a persona
08-17 15:35:49.270  1015  1442 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6990 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-17 15:35:49.270  6990  6990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:49.270  1015  1442 I ActivityManager: Killing 6361:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-17 15:35:49.280  6990  6990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:49.280  6990  6990 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 15:35:49.300  6990  6990 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:49.300  6990  6990 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:49.320  6990  6990 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 15:35:49.350  2038  2205 W GCoreFlp: No location to return for getLastLocation()
,08-17 15:35:49.380  1015  3782 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:35:49.380  1015  3782 W ActivityManager: userId = 0, bbcId = -10000,
08-17 15:35:49.380  1015  3782 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-17 15:35:49.380  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-17 15:35:49.380  1015  1441 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 15:35:49.390  1015  1441 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.390  1015  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:49.390  1015  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:49.390  1015  4287 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:35:49.390  1015  4287 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.390  1015  4287 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:49.390  1015  4287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:49.410  4773  6910 D UdcContextInitService: registered all accounts: true
,08-17 15:35:49.410  2038  2209 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 15:35:49.430  2038  2222 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-17 15:35:49.430  1015  1043 D Tethering: interfaceRemoved p2p0
,08-17 15:35:49.430  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 15:35:49.470  2038  2222 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-17 15:35:49.480  1015  1465 I ActivityManager: Killing 6406:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,08-17 15:35:49.540  2038  2222 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,08-17 15:35:49.550  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-17 15:35:49.570  6990  7012 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-17 15:35:49.580  6990  7012 I Babel_SMS: MmsConfig.loadMmsSettings
,08-17 15:35:49.580  6990  7012 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-17 15:35:49.580  6990  7012 I Babel_SMS: MmsConfig.loadFromDatabase
,08-17 15:35:49.590  6990  7012 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-17 15:35:49.590  6990  7012 I Babel_SMS: MmsConfig.loadFromResources
,08-17 15:35:49.590  6990  7012 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-17 15:35:49.590  6990  7012 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-17 15:35:49.610  1015  1134 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-17 15:35:49.610  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-17 15:35:49.610  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:49.610  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:49.610  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 15:35:49.630  6990  6990 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:35:49.640  6990  6990 I Babel_Crash: startup - clean
,08-17 15:35:49.660  1015  3782 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 15:35:49.660  1015  3782 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:35:49.660  1015  3782 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:49.660  1015  3782 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.660  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:35:49.670  1615  1615 I Hs20UtilService: Starting #9
,08-17 15:35:49.670  1615  1649 I Hs20UtilService: Message received 5007
,08-17 15:35:49.670  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 15:35:49.670  3269  3269 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 15:35:49.670  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 15:35:49.680  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 15:35:49.680  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 15:35:49.680  3269  3269 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 15:35:49.680  3269  3802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 15:35:49.680  6990  6990 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 15:35:49.680  6990  6990 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 15:35:49.680  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 15:35:49.680  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:35:49.680  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:49.680  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.680  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:35:49.690  6990  6990 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 15:35:49.690  1615  1615 I Hs20UtilService: Starting #10
,08-17 15:35:49.690  1015  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-17 15:35:49.690  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:49.690  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:49.690  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:49.690  1015  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:49.690  6990  6990 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-17 15:35:49.700  7015  7015 I libpersona: KNOX_SDCARD checking this for 1000
08-17 15:35:49.700  1615  1649 I Hs20UtilService: Message received 5011
08-17 15:35:49.700  7015  7015 I libpersona: KNOX_SDCARD not a persona
08-17 15:35:49.700  6990  6990 W AudioCapabilities: Unsupported mime audio/mpeg-L2
08-17 15:35:49.700  7015  7015 E Zygote  : MountEmulatedStorage()
08-17 15:35:49.710  1015  1491 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7015 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 15:35:49.700  7015  7015 E Zygote  : v2
08-17 15:35:49.700  7015  7015 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 15:35:49.700  7015  7015 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:49.700  7015  7015 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:35:49.710  6990  6990 W AudioCapabilities: Unsupported mime audio/x-ms-wma,
,08-17 15:35:49.730   308   308 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 25.984ms
,08-17 15:35:49.730  6990  6990 W AudioCapabilities: Unsupported mime audio/x-ima
,08-17 15:35:49.730  6990  6990 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 15:35:49.730  7015  7015 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 15:35:49.730  7015  7015 D ActivityThread: Added TimaKeyStore provider
08-17 15:35:49.730  6990  6990 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 15:35:49.750  6990  6990 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 15:35:49.750   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.673ms
,08-17 15:35:49.750  6990  6990 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 15:35:49.760  6990  6990 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
08-17 15:35:49.760  6990  6990 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 15:35:49.760  6990  6990 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 15:35:49.760  6990  6990 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
08-17 15:35:49.760  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 15:35:49.760  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 15:35:49.760  7015  7015 D SecurityLogAgent: StateMachine : Current State = 1
08-17 15:35:49.770  6990  6990 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-17 15:35:49.770   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 672us total 17.703ms
,08-17 15:35:49.770  7015  7015 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 15:35:49.770  6990  6990 W VideoCapabilities: Unsupported mime video/mp43
,08-17 15:35:49.770  1015  3782 I ActivityManager: Killing 6440:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-17 15:35:49.770  6990  6990 W VideoCapabilities: Unsupported mime video/sorenson
,08-17 15:35:49.780  1015  1441 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.780  1015  1441 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.780  1015  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.780  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.780  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.780  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.780  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.780  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.780  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.790  6990  6990 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-17 15:35:49.790  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.790  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.790  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.790  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.790  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.790  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.790  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:49.790  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.790  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.800  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:49.800  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.800  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.800  6990  6990 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 15:35:49.800  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:49.800  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.800  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.810  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.810  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.810  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.810  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:49.810  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.810  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.810  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.810  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.810  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.810  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.810  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.810  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.820  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.820  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.820  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.820  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.820  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.820  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.820  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:49.820  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.820  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 15:35:49.830  3269  3269 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:35:49.830  1015  4287 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 15:35:49.830  1015  4287 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 15:35:49.830  6990  6990 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 15:35:49.830  1015  4287 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:49.830  1015  4287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:49.830  6990  6990 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-17 15:35:49.830  1015  4287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 15:35:49.830  6990  6990 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 15:35:49.840  3269  3269 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:35:49.840  6990  6990 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 15:35:49.840  3269  3269 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 15:35:49.840  1015  1491 I ActivityManager: Killing 6422:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-17 15:35:49.850  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:35:49.850  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 15:35:49.850  6990  6990 I vclib   : onServiceConnected
,08-17 15:35:49.850  1015  3782 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-17 15:35:49.850  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:49.850  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:49.860  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:49.860  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:49.870  7032  7032 E Zygote  : MountEmulatedStorage()
,08-17 15:35:49.870  7032  7032 E Zygote  : v2
08-17 15:35:49.870  7032  7032 I libpersona: KNOX_SDCARD checking this for 1002
08-17 15:35:49.870  7032  7032 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:49.870  7032  7032 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:49.870  1015  3782 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7032 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-17 15:35:49.870  7032  7032 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:49.870  7032  7032 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-17 15:35:49.890  7032  7032 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:49.890  7032  7032 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:49.900  7032  7032 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-17 15:35:49.900  7032  7032 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 15:35:49.930  7032  7032 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 15:35:49.970  7032  7032 D BtSettings.ProfileConfig: Adding GattService
,08-17 15:35:49.970  7032  7032 D BtSettings.ProfileConfig: Adding HeadsetService
,08-17 15:35:49.970  7032  7032 D BtSettings.ProfileConfig: Adding A2dpService
,08-17 15:35:49.970  7032  7032 D BtSettings.ProfileConfig: Adding HidService
,08-17 15:35:49.970  7032  7032 D BtSettings.ProfileConfig: Adding HealthService
,08-17 15:35:49.970  7032  7032 D BtSettings.ProfileConfig: Adding PanService
,08-17 15:35:49.970  7032  7032 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-17 15:35:49.970  7032  7032 D BtSettings.ProfileConfig: Adding SapService
,08-17 15:35:49.970  7032  7032 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-17 15:35:49.970  7032  7032 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-17 15:35:49.970  7032  7032 D BtSettings.ProfileConfig: Adding SapClientService
,08-17 15:35:49.980  7032  7032 D BtSettings.ProfileConfig: Adding HidDevService
,08-17 15:35:49.980  7032  7032 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 15:35:49.980  1015  1442 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 15:35:49.980  1015  1442 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.980  1015  1442 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:49.980  1015  1442 D SettingsProvider: selectionArgs: false
08-17 15:35:49.980  1015  1442 D SettingsProvider: selectionArgs: 1002
08-17 15:35:49.980  1015  1442 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:49.980  1015  1442 D SettingsProvider: ret = -1
08-17 15:35:49.980  1015  3782 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-17 15:35:49.980  1015  3782 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.980  1015  3782 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:49.980  1015  3782 D SettingsProvider: selectionArgs: false
08-17 15:35:49.980  1015  3782 D SettingsProvider: selectionArgs: 1002
08-17 15:35:49.980  1015  3782 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:49.980  1015  3782 D SettingsProvider: ret = -1
,08-17 15:35:49.980  1015  1441 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-17 15:35:49.980  1015  1441 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.980  1015  1441 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 15:35:49.980  1015  1441 D SettingsProvider: selectionArgs: false
08-17 15:35:49.980  1015  1441 D SettingsProvider: selectionArgs: 1002
,08-17 15:35:49.980  1015  1441 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:49.980  1015  1441 D SettingsProvider: ret = -1
,08-17 15:35:49.980  1015  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-17 15:35:49.980  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.980  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:49.980  1015  1134 D SettingsProvider: selectionArgs: false
08-17 15:35:49.980  1015  1134 D SettingsProvider: selectionArgs: 1002
08-17 15:35:49.980  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:49.980  1015  1134 D SettingsProvider: ret = -1
,08-17 15:35:49.980  1015  4287 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-17 15:35:49.980  1015  4287 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.980  1015  4287 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 15:35:49.980  1015  4287 D SettingsProvider: selectionArgs: false
08-17 15:35:49.980  1015  4287 D SettingsProvider: selectionArgs: 1002
,08-17 15:35:49.980  1015  4287 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:49.990  1015  4287 D SettingsProvider: ret = -1
,08-17 15:35:49.990  1015  1511 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-17 15:35:49.990  1015  1511 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.990  1015  1511 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:49.990  1015  1511 D SettingsProvider: selectionArgs: false
08-17 15:35:49.990  1015  1511 D SettingsProvider: selectionArgs: 1002
08-17 15:35:49.990  1015  1511 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:49.990  1015  1511 D SettingsProvider: ret = -1
,08-17 15:35:49.990  1015  1490 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 15:35:49.990  1015  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.990  1015  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:49.990  1015  1490 D SettingsProvider: selectionArgs: false
08-17 15:35:49.990  1015  1490 D SettingsProvider: selectionArgs: 1002
08-17 15:35:49.990  1015  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:49.990  1015  1490 D SettingsProvider: ret = -1
,08-17 15:35:49.990  1015  1465 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 15:35:49.990  1015  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.990  1015  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:49.990  1015  1465 D SettingsProvider: selectionArgs: false
,08-17 15:35:49.990  1015  1465 D SettingsProvider: selectionArgs: 1002
08-17 15:35:49.990  1015  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:49.990  1015  1465 D SettingsProvider: ret = -1
,08-17 15:35:49.990  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:35:49.990  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.990  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 15:35:49.990  1015  1028 D SettingsProvider: selectionArgs: false
08-17 15:35:49.990  1015  1028 D SettingsProvider: selectionArgs: 1002
08-17 15:35:49.990  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:49.990  1015  1028 D SettingsProvider: ret = -1
,08-17 15:35:49.990  1015  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-17 15:35:49.990  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.990  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:49.990  1015  1216 D SettingsProvider: selectionArgs: false
08-17 15:35:49.990  1015  1216 D SettingsProvider: selectionArgs: 1002,
08-17 15:35:49.990  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:49.990  1015  1216 D SettingsProvider: ret = -1
,08-17 15:35:49.990  1015  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 15:35:49.990  1015  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.990  1015  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 15:35:49.990  1015  1491 D SettingsProvider: selectionArgs: false
08-17 15:35:49.990  1015  1491 D SettingsProvider: selectionArgs: 1002
08-17 15:35:49.990  1015  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:49.990  1015  1491 D SettingsProvider: ret = -1
08-17 15:35:49.990  1015  3781 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-17 15:35:49.990  1015  3781 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:49.990  1015  3781 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:49.990  1015  3781 D SettingsProvider: selectionArgs: false
08-17 15:35:49.990  1015  3781 D SettingsProvider: selectionArgs: 1002
08-17 15:35:49.990  1015  3781 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-17 15:35:49.990  1015  3781 D SettingsProvider: ret = -1
,08-17 15:35:50.000  1015  1501 I ActivityManager: Killing 6455:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-17 15:35:50.000  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 15:35:50.000  1015  1511 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 15:35:50.000  1015  1511 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 15:35:50.010  1015  1511 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:50.010  1015  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:50.010  1015  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:50.010  2038  7048 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 15:35:50.010  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 15:35:50.020  1015  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 15:35:50.020  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:35:50.020  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:50.020  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:50.020  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:35:50.020  1015  1511 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:35:50.020  1615  1615 I Hs20UtilService: Starting #11
,08-17 15:35:50.020  1615  1649 I Hs20UtilService: Message received 5011
,08-17 15:35:50.020  1015  1511 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:50.020  1015  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:50.030  1015  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:50.030  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 15:35:50.030  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 15:35:50.030  7015  7015 D SecurityLogAgent: StateMachine : Current State = 1
08-17 15:35:50.030  7015  7015 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 15:35:50.040  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:35:50.040  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:50.040  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:50.040  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:50.050  1015  1501 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-17 15:35:50.050  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.050  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.050  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.050  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.060  7049  7049 E Zygote  : MountEmulatedStorage()
,08-17 15:35:50.060  7049  7049 E Zygote  : v2
08-17 15:35:50.060  7049  7049 I libpersona: KNOX_SDCARD checking this for 1000
08-17 15:35:50.060  7049  7049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:50.060  7049  7049 I libpersona: KNOX_SDCARD not a persona
08-17 15:35:50.070  2038  7048 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 15:35:50.070  1015  1501 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 15:35:50.070  7049  7049 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:50.070  7049  7049 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:35:50.080  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-17 15:35:50.080  7049  7049 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:50.090  7049  7049 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:50.100  7049  7049 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-17 15:35:50.100  7049  7049 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-17 15:35:50.100  7049  7049 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-17 15:35:50.120  7049  7049 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-17 15:35:50.120  7049  7049 I PCWCLIENTTRACE_PushUtil: sales region : global
08-17 15:35:50.120  7049  7049 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 15:35:50.120  7049  7049 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:35:50.130  7049  7064 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-17 15:35:50.130  1015  1465 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-17 15:35:50.130  1015  1465 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-17 15:35:50.140  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-17 15:35:50.140  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.140  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.140  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.140  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.150  7066  7066 E Zygote  : MountEmulatedStorage(),
,08-17 15:35:50.160  7066  7066 E Zygote  : v2
08-17 15:35:50.160  7066  7066 I libpersona: KNOX_SDCARD checking this for 10001
08-17 15:35:50.160  7066  7066 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:50.160  7066  7066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 15:35:50.160  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7066 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-17 15:35:50.160  1015  3781 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast,
,08-17 15:35:50.170  7066  7066 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:50.170  1015  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.170  1015  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.170  1015  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.170  1015  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.170  7066  7066 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:35:50.190  7078  7078 E Zygote  : MountEmulatedStorage(),
08-17 15:35:50.190  7078  7078 E Zygote  : v2
08-17 15:35:50.190  7078  7078 I libpersona: KNOX_SDCARD checking this for 10031
,08-17 15:35:50.190  7078  7078 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:50.190  7078  7078 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 15:35:50.190  1015  3781 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7078 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-17 15:35:50.200  7078  7078 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:50.200  7078  7078 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:35:50.210  1780  1780 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-17 15:35:50.210  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-17 15:35:50.210  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.210  7066  7066 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 15:35:50.210  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.210  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.210  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.210  7066  7066 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:50.230  7078  7078 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:50.230  7078  7078 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:50.230  7096  7096 E Zygote  : MountEmulatedStorage()
08-17 15:35:50.230  7096  7096 E Zygote  : v2
08-17 15:35:50.230  7096  7096 I libpersona: KNOX_SDCARD checking this for 10121
08-17 15:35:50.230  7096  7096 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:50.230  7096  7096 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:50.240  1015  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7096 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-17 15:35:50.240  7096  7096 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 15:35:50.240  7096  7096 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:35:50.260  1820  2604 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,08-17 15:35:50.260  1780  1780 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-17 15:35:50.260  1780  1780 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-17 15:35:50.260  7096  7096 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 15:35:50.260  1780  1780 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-17 15:35:50.260  1780  1780 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-17 15:35:50.260  7096  7096 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:50.280  1780  1780 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-17 15:35:50.280  1780  1780 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-17 15:35:50.280  1015  1511 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-17 15:35:50.280  1015  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.280  1015  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.280  1015  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.280  1015  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.300  7111  7111 E Zygote  : MountEmulatedStorage()
08-17 15:35:50.300  7111  7111 I libpersona: KNOX_SDCARD checking this for 10077
08-17 15:35:50.300  7111  7111 E Zygote  : v2
08-17 15:35:50.300  7111  7111 I libpersona: KNOX_SDCARD not a persona
08-17 15:35:50.300  7111  7111 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 15:35:50.300  7096  7096 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:35:50.300  7111  7111 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:50.300  7096  7096 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 15:35:50.300  7111  7111 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
08-17 15:35:50.300  7096  7096 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-17 15:35:50.300  1015  1511 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7111 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 15:35:50.310  7078  7078 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-17 15:35:50.310  1015  1490 I ActivityManager: Killing 6469:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-17 15:35:50.330  7096  7096 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:35:50.330  7096  7096 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service,
,08-17 15:35:50.330  7111  7111 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 15:35:50.330  7111  7111 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:50.340  7096  7096 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-17 15:35:50.340  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-17 15:35:50.340  2766  7126 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-17 15:35:50.340  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.340  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.340  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.340  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.350  2766  7126 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
08-17 15:35:50.350  2766  7126 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-17 15:35:50.350  2766  7126 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-17 15:35:50.350  2766  7126 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-17 15:35:50.360  1015  4287 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-17 15:35:50.360  1015  4287 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-17 15:35:50.360  1015  4287 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 15:35:50.360  1015  4287 D BatteryService: stay LED for fully charged
08-17 15:35:50.360  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 15:35:50.370  7127  7127 E Zygote  : MountEmulatedStorage(),
,08-17 15:35:50.370  7127  7127 E Zygote  : v2
08-17 15:35:50.370  7127  7127 I libpersona: KNOX_SDCARD checking this for 10032
,08-17 15:35:50.370  7127  7127 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:50.370  1015  1027 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7127 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 15:35:50.380  7127  7127 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:50.380  7127  7127 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 15:35:50.380  7127  7127 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-17 15:35:50.380  1015  1015 I MotionRecognitionService: Plugged
,08-17 15:35:50.380  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 15:35:50.390  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-17 15:35:50.390  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 15:35:50.390  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 15:35:50.390  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 15:35:50.400  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-17 15:35:50.400  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.400  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.400  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.400  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.410  7127  7127 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 15:35:50.410  7127  7127 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:50.410  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 15:35:50.410  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 15:35:50.410  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 15:35:50.420  7142  7142 E Zygote  : MountEmulatedStorage()
,08-17 15:35:50.420  7142  7142 E Zygote  : v2
,08-17 15:35:50.420  7142  7142 I libpersona: KNOX_SDCARD checking this for 10141
,08-17 15:35:50.420  7142  7142 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:50.420  7142  7142 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:50.420  1015  1027 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7142 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-17 15:35:50.420  1015  1027 I ActivityManager: Killing 6491:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-17 15:35:50.420  7142  7142 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:50.430  7142  7142 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:35:50.450  7142  7142 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:50.450  7142  7142 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:50.460  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-17 15:35:50.460  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.460  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.460  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.460  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.470  7142  7142 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-17 15:35:50.470  7142  7142 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:35:50.470  7142  7142 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 15:35:50.470  7142  7142 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 15:35:50.480  7159  7159 E Zygote  : MountEmulatedStorage()
08-17 15:35:50.480  7159  7159 E Zygote  : v2
08-17 15:35:50.480  7159  7159 I libpersona: KNOX_SDCARD checking this for 1000
08-17 15:35:50.480  7159  7159 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:50.480  7159  7159 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 15:35:50.480  1015  1134 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7159 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 15:35:50.480  7159  7159 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:50.480  1015  1134 I ActivityManager: Killing 6585:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
08-17 15:35:50.480  7159  7159 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:35:50.500  7127  7173 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-17 15:35:50.500  7159  7159 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:50.510  7159  7159 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:50.510  7127  7173 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-17 15:35:50.510  7127  7173 D SPPClientService: PushLog.txt file is not deleted.
,08-17 15:35:50.520  7127  7173 D SPPClientService: PushLog.txt file is not deleted.
,08-17 15:35:50.520  7127  7173 D SPPClientService: ============PushLog. stop!
,08-17 15:35:50.530  7127  7127 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-17 15:35:50.530  1015  1441 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-17 15:35:50.530  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.530  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.530  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.530  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.540  1015  1490 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 15:35:50.550  1015  1441 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7176 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-17 15:35:50.550  7176  7176 E Zygote  : MountEmulatedStorage()
,08-17 15:35:50.550  7176  7176 E Zygote  : v2
08-17 15:35:50.550  7176  7176 I libpersona: KNOX_SDCARD checking this for 10036
08-17 15:35:50.550  7176  7176 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:50.550  7176  7176 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 15:35:50.550  1015  1441 I ActivityManager: Killing 6602:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-17 15:35:50.550  7176  7176 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:50.550  7176  7176 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-17 15:35:50.550  1015  3781 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-17 15:35:50.550  1015  3781 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-17 15:35:50.560  1015  3781 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:50.560  1015  3781 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-17 15:35:50.560  1015  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-17 15:35:50.560  1015  1442 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 15:35:50.560  7159  7159 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-17 15:35:50.580  7176  7176 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:50.580  7176  7176 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:50.640  7127  7186 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-17 15:35:50.650  7176  7176 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@399de131
,08-17 15:35:50.650  1015  1134 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 15:35:50.660  7176  7176 I SA      : [SSP] onCreated
,08-17 15:35:50.660  1015  3782 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 15:35:50.680  7176  7176 I SA      : [TPM] There is no property file
,08-17 15:35:50.680  7176  7176 I SA      : [SCU] isHaveSA() - false
,08-17 15:35:50.680  7176  7176 I SA      : [TPM] getModelProperty : null
08-17 15:35:50.680  7176  7176 I SA      : [TPM] getCSCProperty : null
,08-17 15:35:50.680  7176  7176 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-17 15:35:50.680  7176  7176 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-17 15:35:50.680  7176  7176 I SA      : [DM] TFT FEATURE: false
,08-17 15:35:50.690  7176  7176 I SA      : [DM] init START
,08-17 15:35:50.700  7159  7159 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-17 15:35:50.700  7176  7176 I SA      : [DM] This device is not a Vodafone
,08-17 15:35:50.700  1015  1490 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-17 15:35:50.700  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-17 15:35:50.700  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:50.700  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:50.700  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 15:35:50.710  1015  1441 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-17 15:35:50.710  7159  7159 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-17 15:35:50.710  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.710  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.710  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.710  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.710  7159  7159 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:35:50.710  7159  7159 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-17 15:35:50.710  7159  7159 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-17 15:35:50.710  7159  7159 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-17 15:35:50.720  7207  7207 E Zygote  : MountEmulatedStorage()
,08-17 15:35:50.720  7207  7207 E Zygote  : v2
08-17 15:35:50.720  7207  7207 I libpersona: KNOX_SDCARD checking this for 10110
08-17 15:35:50.720  7207  7207 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:50.720  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 15:35:50.730  1015  1441 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7207 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 15:35:50.730  1015  1501 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
08-17 15:35:50.730  1015  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-17 15:35:50.730  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:50.730  1015  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:50.730  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 15:35:50.730  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:50.730  7176  7176 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-17 15:35:50.730  7176  7176 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-17 15:35:50.730  7176  7176 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-17 15:35:50.730  1015  1441 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-17 15:35:50.730  7176  7176 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-17 15:35:50.740  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.740  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.740  7176  7176 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:35:50.740  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.740  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-17 15:35:50.740  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75),
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75),
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75),
08-17 15:35:50.740  6990  7205 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75),
08-17 15:35:50.740  7176  7176 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75),
08-17 15:35:50.750  7176  7176 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-17 15:35:50.750  7176  7176 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-17 15:35:50.750   308   308 I art     : Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 900us total 33.377ms
08-17 15:35:50.750  7176  7176 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-17 15:35:50.760  7176  7176 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-17 15:35:50.760  7176  7176 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-17 15:35:50.760  7176  7176 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-17 15:35:50.770  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 15:35:50.770  7207  7207 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:50.780  7176  7176 I SA      : [SCU] isHaveSA() - false
08-17 15:35:50.780  7176  7176 I SA      : support phone number id : false
08-17 15:35:50.780  7176  7176 I SA      : [DM] Supports Ref Jpn : true
,08-17 15:35:50.780  7176  7176 I SA      : [DM] init END
08-17 15:35:50.780  7176  7176 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-17 15:35:50.780   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 665us total 26.251ms
,08-17 15:35:50.780  7176  7176 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-17 15:35:50.780  7176  7176 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-17 15:35:50.790  1015  3782 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 15:35:50.790  1015  4287 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 15:35:50.790  7176  7176 I SA      : [SLFUCHKMGR] constructor called
,08-17 15:35:50.800  7176  7176 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-17 15:35:50.800  7176  7176 I SA      : [OR] == isSIMCardReady false ==
,08-17 15:35:50.800   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 18.312ms
,08-17 15:35:50.800  7176  7176 I SA      : [SCU] == networkStateCheck == false,
08-17 15:35:50.800  7176  7176 I SA      : [OR] onReceive END
,08-17 15:35:50.810  7226  7226 E Zygote  : MountEmulatedStorage(),
08-17 15:35:50.810  7226  7226 I libpersona: KNOX_SDCARD checking this for 10008
08-17 15:35:50.810  7226  7226 E Zygote  : v2
08-17 15:35:50.810  7226  7226 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:50.810  7226  7226 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:50.820  7226  7226 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:50.820  7226  7226 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-17 15:35:50.820  1015  1441 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7226 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 15:35:50.820  1015  1441 I ActivityManager: Killing 6621:com.samsung.helphub/1000 (adj 15): empty #21
,08-17 15:35:50.830  1015  1501 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-17 15:35:50.830  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.830  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.830  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:50.830  1015  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:50.840  7241  7241 E Zygote  : MountEmulatedStorage()
,08-17 15:35:50.840  7241  7241 E Zygote  : v2
08-17 15:35:50.840  7241  7241 I libpersona: KNOX_SDCARD checking this for 10068
08-17 15:35:50.840  7241  7241 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:50.840  7241  7241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:50.850  7226  7226 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:50.850  7226  7226 D ActivityThread: Added TimaKeyStore provider
08-17 15:35:50.850  1015  1501 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7241 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-17 15:35:50.850  7241  7241 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:50.850  1015  1465 I ActivityManager: Killing 6653:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-17 15:35:50.850  7241  7241 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 15:35:50.860  1222  1222 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:35:50.860  1015  4287 I ActivityManager: Killing 6676:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-17 15:35:50.870  7241  7241 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:50.880  7241  7241 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:50.900  7241  7241 D BadgeProvider: onCreate
08-17 15:35:50.900  7241  7241 D BadgeProvider: DatabaseHelper
,08-17 15:35:50.920  7241  7249 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-17 15:35:50.920   289   289 E SMD     : DCD OFF
,08-17 15:35:50.940  1015  1511 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 15:35:50.940  1015  1511 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 15:35:50.940  1015  1511 D SecContentProvider2: mCursor = null
08-17 15:35:50.940  1015  1511 D WifiService: setWifiEnabled: true pid=6794, uid=10171
08-17 15:35:50.940  1015  1511 W WifiService: Failed getting userId using ActivityManagerNative
08-17 15:35:50.940  1015  1511 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 15:35:50.940  1015  1511 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 15:35:50.940  1015  1511 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 15:35:50.940  1015  1511 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 15:35:50.940  1015  1511 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 15:35:50.940  1015  1511 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 15:35:50.940  1015  1511 W ActivityManager: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 15:35:50.940  1015  1511 D SettingsProvider: name = wifi_on
,08-17 15:35:50.960  1015  1442 I ActivityManager: Killing 6691:com.android.calendar/u0a131 (adj 15): empty #21
,08-17 15:35:50.960  7241  7249 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-17 15:35:50.960  7241  7249 D BadgeProvider: sendNotify, [notify] : null
08-17 15:35:50.960  7241  7249 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-17 15:35:50.960  7241  7249 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-17 15:35:50.960  7241  7249 D BadgeProvider: update, [UpdateCount] : 1
,08-17 15:35:50.960  1495  1495 D Launcher.Model: reloadBadges entered.
,08-17 15:35:51.030  1015  1465 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 15:35:51.050  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 15:35:51.050  2897  2897 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 15:35:50 GMT+02:00 2016
,08-17 15:35:51.050  1015  1491 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-17 15:35:51.050  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-17 15:35:51.050  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:51.050  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:51.050  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 15:35:51.060  2897  2897 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-17 15:35:51.060  2897  2897 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-17 15:35:51.060  2897  2897 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 15:35:51.060  1015  1441 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 15:35:51.070  1015  1465 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-17 15:35:51.070  1015  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:51.070  1015  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:51.070  1015  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:51.070  1015  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:51.070  2897  2897 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 15:35:51.080  2897  7258 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-17 15:35:51.080  2897  7258 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
08-17 15:35:51.080  7259  7259 E Zygote  : MountEmulatedStorage()
,08-17 15:35:51.080  7259  7259 E Zygote  : v2
08-17 15:35:51.080  7259  7259 I libpersona: KNOX_SDCARD checking this for 10009
08-17 15:35:51.080  7259  7259 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:51.080  7259  7259 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:51.090  1015  1465 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7259 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-17 15:35:51.090  1015  1465 I ActivityManager: Killing 6718:com.google.android.gms:car/u0a11 (adj 15): empty #21
08-17 15:35:51.090  7259  7259 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:51.090  7259  7259 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-17 15:35:51.090  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-17 15:35:51.090  1015  1216 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-17 15:35:51.090  2897  7258 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
08-17 15:35:51.090  1015  1511 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-17 15:35:51.100  2897  7258 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-17 15:35:51.100  1015  4287 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-17 15:35:51.110  2897  2897 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-17 15:35:51.120  7259  7259 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:51.120  7259  7259 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:51.130  1015  1491 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 15:35:51.190  1015  4287 I ActivityManager: Killing 5794:com.android.vending/u0a26 (adj 15): empty #21
,08-17 15:35:51.200  1015  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 15:35:51.200  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-17 15:35:51.200  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:51.200  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:51.200  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:51.200  1015  1028 I art     : Explicit concurrent mark sweep GC freed 45304(2MB) AllocSpace objects, 1(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.547ms total 240.799ms
,08-17 15:35:51.220  4773  7275 I iu.SyncManager: SYNC; picasa accounts
,08-17 15:35:51.230  4773  4773 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-17 15:35:51.230  1015  1491 I ActivityManager: Killing 6750:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-17 15:35:51.300   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 15:35:51.300   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 15:35:51.300  7207  7279 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 15:35:51.310   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 15:35:51.310   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 15:35:51.310  7207  7279 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 15:35:51.320   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 15:35:51.320   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 15:35:51.320  7207  7286 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 15:35:51.330   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 15:35:51.330   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 15:35:51.330  7207  7286 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 15:35:51.340  7207  7207 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 15:35:51.340  7207  7207 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 15:35:51.340  7207  7207 I GAv4    :   adb logcat -s GAv4
,08-17 15:35:51.360  7207  7207 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 15:35:51.360  1015  1442 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 15:35:51.370  7207  7207 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 15:35:51.370  7207  7288 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 15:35:51.440  1015  1043 D Tethering: interfaceAdded wlan0
,08-17 15:35:51.450  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:51.450  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-17 15:35:51.460  1015  1129 E Tethering: No numeric data
,08-17 15:35:51.460  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:35:51.460  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 15:35:51.460  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 15:35:51.460  1015  1129 D Tethering: clearTetheredNotification()
08-17 15:35:51.460  1015  1129 D Tethering: InitialState.processMessage what=4
,08-17 15:35:51.460  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:51.460  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 15:35:51.460  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 15:35:51.460  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 15:35:51.460  1172  1172 D HotspotTile: updateTetherState():false, false
08-17 15:35:51.460  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 15:35:51.460  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-17 15:35:51.460   279   971 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-17 15:35:51.460  1015  1121 V NetworkStats: performPollLocked() took 5ms
08-17 15:35:51.460  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 15:35:51.470   279   971 D SoftapController: Softap fwReload - Ok
,08-17 15:35:51.470  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 15:35:51.470  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:35:51.470  1015  1129 E Tethering: No numeric data
08-17 15:35:51.470  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:35:51.470  1015  1129 D Tethering: clearTetheredNotification()
08-17 15:35:51.470  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 15:35:51.470   279   971 D CommandListener: Setting iface cfg
,08-17 15:35:51.470   279   971 D CommandListener: Trying to bring down wlan0
,08-17 15:35:51.470  1015  1043 D Tethering: interfaceAdded p2p0
08-17 15:35:51.470   279   971 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:35:51.470  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-17 15:35:51.470  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:51.470  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-17 15:35:51.470  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-17 15:35:51.470  1015  1048 I PowerManagerService: [PWL] Off : 75s ago
08-17 15:35:51.470  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 15:35:51.470  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-17 15:35:51.470  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-17 15:35:51.470  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 15:35:51.470  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=3146)
08-17 15:35:51.470  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'NetworkStats' (uid=1000, pid=1015, ws=null) (elapsedTime=2)
08-17 15:35:51.470  1172  1172 D HotspotTile: updateTetherState():false, false
08-17 15:35:51.480  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
,08-17 15:35:51.480  1015  1121 V NetworkStats: performPollLocked() took 6ms
08-17 15:35:51.480  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 15:35:51.480  1015  1124 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-17 15:35:51.480  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-17 15:35:51.480  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:35:51.480  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 15:35:51.480  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:51.480  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:51.480  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:51.480  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:51.490  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 15:35:51.490  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-17 15:35:51.490  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 15:35:51.490  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 15:35:51.490  1172  1172 D HotspotTile: onReceive : 2, 0
,08-17 15:35:51.490  3269  3269 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:35:51.490  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:51.490  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:51.500  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:51.500  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:35:51.540  7291  7291 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-17 15:35:51.540  7291  7291 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 15:35:51.540  7291  7291 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 15:35:51.550  7291  7291 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-17 15:35:51.560   387   387 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7291
,08-17 15:35:51.560   387   387 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-17 15:35:51.560  7291  7291 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 15:35:51.560  7291  7291 I wpa_supplicant: ssSupport state is = 1
08-17 15:35:51.560  7291  7291 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 15:35:51.560  7291  7291 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-17 15:35:51.560   387   387 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7291
08-17 15:35:51.560   387   387 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-17 15:35:51.570  2038  2222 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-17 15:35:51.570  2038  2222 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-17 15:35:51.630  1015  1442 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:35:51.630  1015  1442 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:51.640  1015  1442 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:51.640  1015  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-17 15:35:51.660  7207  7207 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-17 15:35:51.680  7207  7207 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7653-7655)
,08-17 15:35:51.680  7207  7207 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 15:35:51.690  7207  7207 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12a5c8b0}
,08-17 15:35:51.690  7207  7207 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 15:35:51.690  7207  7207 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 15:35:51.710  7207  7207 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-17 15:35:51.710  7207  7207 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 15:35:51.720  7207  7207 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 15:35:51.730  7207  7207 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 15:35:51.730  7207  7207 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 15:35:51.730  7207  7207 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 15:35:51.730  7207  7207 I Adreno-EGL: Local Branch: 
08-17 15:35:51.730  7207  7207 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 15:35:51.730  7207  7207 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 15:35:51.730  7207  7207 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 15:35:51.740   387   387 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-17 15:35:51.750  7291  7291 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-17 15:35:51.790  7207  7319 W cr.media: Requires BLUETOOTH permission
,08-17 15:35:51.790  7207  7207 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 15:35:51.800  7291  7291 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 15:35:51.800  7291  7291 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 15:35:51.800  7207  7207 I NSApplication: Starting up...
08-17 15:35:51.800  1015  1501 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 15:35:51.810  7291  7291 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-17 15:35:51.810   387   387 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7291
,08-17 15:35:51.810   387   387 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-17 15:35:51.810  7291  7291 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 15:35:51.810  7291  7291 I wpa_supplicant: ssSupport state is = 1
08-17 15:35:51.810  7291  7291 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 15:35:51.810  7291  7291 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 15:35:51.810  7291  7291 E wpa_supplicant: SIM READ ERROR,
08-17 15:35:51.810  7291  7291 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 15:35:51.810  7291  7291 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 15:35:51.810  7291  7291 E wpa_supplicant: SIM READ ERROR
08-17 15:35:51.810  7291  7291 I wpa_supplicant: Blacklist: Clear (all) 
08-17 15:35:51.810  7291  7291 I wpa_supplicant: wpa_default_ap_write_once,
08-17 15:35:51.810  7291  7291 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 15:35:51.810  7291  7291 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 15:35:51.810  7291  7291 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 15:35:51.810  7291  7291 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 15:35:51.810  7291  7291 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-17 15:35:51.810  1015  1465 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 15:35:51.820  7291  7291 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
08-17 15:35:51.820  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-17 15:35:51.820  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:51.820  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:51.820  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:51.820  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:51.820  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:51.820  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-17 15:35:51.820  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:35:51.830  7325  7325 E Zygote  : MountEmulatedStorage(),
08-17 15:35:51.830  1015  1027 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7325 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-17 15:35:51.830  7325  7325 E Zygote  : v2
08-17 15:35:51.830  7325  7325 I libpersona: KNOX_SDCARD checking this for 10117
08-17 15:35:51.830  7325  7325 I libpersona: KNOX_SDCARD not a persona
08-17 15:35:51.840  7325  7325 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 15:35:51.840  1015  1027 I ActivityManager: Killing 6957:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-17 15:35:51.840  7325  7325 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:51.840  7325  7325 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 15:35:51.860  7325  7325 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:51.860  7325  7325 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:51.870  7325  7325 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 15:35:51.880  1015  1321 E Watchdog: !@Sync 4
,08-17 15:35:51.890  7291  7291 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-17 15:35:52.000  7291  7291 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-17 15:35:52.000  7291  7291 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-17 15:35:52.010  7291  7291 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-17 15:35:52.010   387   387 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7291
08-17 15:35:52.010   387   387 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-17 15:35:52.010  7291  7291 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 15:35:52.010  7291  7291 I wpa_supplicant: ssSupport state is = 1,
,08-17 15:35:52.010  7291  7291 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 15:35:52.010  7291  7291 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 15:35:52.030  7291  7291 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-17 15:35:52.030   387   387 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7291
08-17 15:35:52.030   387   387 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 15:35:52.030  7291  7291 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 15:35:52.030  7291  7291 I wpa_supplicant: ssSupport state is = 1
08-17 15:35:52.030  7291  7291 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-17 15:35:52.030  7291  7291 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 15:35:52.030  7291  7291 E wpa_supplicant: SIM READ ERROR
08-17 15:35:52.030  7291  7291 I wpa_supplicant: wpa_default_ap_write_once,
08-17 15:35:52.030  7291  7291 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 15:35:52.030  7291  7291 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 15:35:52.030  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 15:35:52.030  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-17 15:35:52.030  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-17 15:35:52.030  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 15:35:52.030  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 15:35:52.030  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-17 15:35:52.130  7291  7291 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-17 15:35:52.130  7291  7291 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 15:35:52.200  7291  7291 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-17 15:35:52.200  7291  7291 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-17 15:35:52.200  7291  7291 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 15:35:52.230  1015  1491 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-17 15:35:52.230  1015  1491 I ActivityManager: Killing 6973:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-17 15:35:52.240  1015  1442 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 15:35:52.240  1015  1442 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 15:35:52.240  1015  1442 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:52.240  1015  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:52.240  1015  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:35:52.240  1615  1615 I Hs20UtilService: Starting #12
,08-17 15:35:52.240  1615  1649 I Hs20UtilService: Message received 5011
,08-17 15:35:52.250  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 15:35:52.250  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 15:35:52.250  7015  7015 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 15:35:52.250  7015  7015 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 15:35:52.450  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 15:35:52.450  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-17 15:35:52.450  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 15:35:52.480  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-17 15:35:52.490  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 15:35:52.490  7291  7291 I wpa_supplicant: HOTSPOT20_ENABLE called
08-17 15:35:52.490  7291  7291 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-17 15:35:52.490  7291  7291 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 15:35:52.490  7291  7291 E wpa_supplicant: SIM READ ERROR,
08-17 15:35:52.490  7291  7291 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 15:35:52.500  7291  7291 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-17 15:35:52.510  7291  7291 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 15:35:52.510  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
,08-17 15:35:52.520  1015  1124 E WifiConfigStore: Not a HS20
,08-17 15:35:52.520  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 15:35:52.520  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-17 15:35:52.520  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-17 15:35:52.520  7291  7291 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 15:35:52.520  7291  7291 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 15:35:52.520  7291  7291 I wpa_supplicant: reset timer : RESET_TIMER 0
,08-17 15:35:52.520  7291  7291 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 15:35:52.520  7291  7291 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 15:35:52.520  7291  7291 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 15:35:52.520  7291  7291 I wpa_supplicant: First Scan Start
08-17 15:35:52.520  7291  7291 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 15:35:52.520  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
08-17 15:35:52.520  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 15:35:52.520  1015  1124 I WifiNative-HAL: startHal
08-17 15:35:52.520  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d57d88c
08-17 15:35:52.520  1015  1124 I WifiNative-HAL: Could not start hal
,08-17 15:35:52.530  1015  1124 E WifiNative-wlan0: do suspend true
,08-17 15:35:52.530  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-17 15:35:52.530  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-17 15:35:52.530   279   971 D CommandListener: Setting iface cfg
08-17 15:35:52.530   279   971 D CommandListener: Trying to bring up p2p0
,08-17 15:35:52.530  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 15:35:52.540  7291  7291 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 15:35:52.540  1015  1123 D WifiP2pService: P2pEnablingState
,08-17 15:35:52.540  7291  7291 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 15:35:52.540  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-17 15:35:52.540  1015  1123 D WifiP2pService: P2p socket connection successful
08-17 15:35:52.540  7291  7291 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-17 15:35:52.540  1015  1123 D WifiP2pService: P2pEnabledState
08-17 15:35:52.540  1015  1124 E WifiStateMachine: Failed to set frequency band 0,
08-17 15:35:52.540  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 15:35:52.540  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-17 15:35:52.540  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 15:35:52.540  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:35:52.540  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 15:35:52.540  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:35:52.540  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
,08-17 15:35:52.550  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-17 15:35:52.550  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
,08-17 15:35:52.570  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-17 15:35:52.570  1015  1123 D WifiP2pService: InactiveState
08-17 15:35:52.570  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-17 15:35:52.570  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 15:35:52.570  7291  7291 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 15:35:52.570  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-17 15:35:52.570  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 15:35:52.590  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 15:35:52.590  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 15:35:52.590  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:52.590  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:52.590  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:52.590  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:52.590  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 15:35:52.590  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-17 15:35:52.590  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:35:52.590  3269  3269 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-17 15:35:52.590  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 15:35:52.590  1172  1172 D HotspotTile: onReceive : 3, 0
,08-17 15:35:52.590  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:35:52.600  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:52.600  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:35:52.600  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-17 15:35:52.600  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:52.600  1015  1148 I WifiNative-HAL: startHal
08-17 15:35:52.600  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9ea3b9bc
08-17 15:35:52.600  1015  1148 I WifiNative-HAL: Could not start hal
08-17 15:35:52.600  1015  1148 E WifiScanningService: could not start HAL
08-17 15:35:52.600  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:52.600  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:35:52.600  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:52.600  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:35:52.600  6990  6990 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:35:52.600  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 15:35:52.600  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 15:35:52.600  1015  1124 E WifiNative-wlan0: invaild command id : 215
,08-17 15:35:52.600  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-17 15:35:52.600  1015  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:35:52.600  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 15:35:52.600  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-17 15:35:52.600  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 15:35:52.600  1015  1046 D WifiDisplayController: disconnect
,08-17 15:35:52.600  1015  1046 D WifiDisplayController: updateConnection
08-17 15:35:52.600  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 15:35:52.600  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 15:35:52.610  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:35:52.610  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-17 15:35:52.610  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 15:35:52.610  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 15:35:52.610  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  secondary type: null
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  wps: 0
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  grpcapab: 0
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  devcapab: 0
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  status: 3
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  wfdInfo: null
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-17 15:35:52.610  1015  1046 D WifiDisplayController:  SConnectInfo : null
,08-17 15:35:52.610  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 15:35:52.610  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 15:35:52.610  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 15:35:52.610  1015  1441 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 15:35:52.610  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-17 15:35:52.610  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:52.610  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:52.610  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:35:52.620  1615  1615 I Hs20UtilService: Starting #13
,08-17 15:35:52.620  1615  1649 I Hs20UtilService: Message received 5011
08-17 15:35:52.620  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 15:35:52.620  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 15:35:52.620  7015  7015 D SecurityLogAgent: StateMachine : Current State = 1
08-17 15:35:52.620  7015  7015 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 15:35:52.620  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 15:35:52.620  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 15:35:52.620  1015  1124 E WifiNative-wlan0: invaild command id : 215
,08-17 15:35:52.620  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 15:35:52.630  3269  3269 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 15:35:52.630  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 15:35:52.630  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 15:35:52.630  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 15:35:52.630  3269  3269 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 15:35:52.630  3269  3802 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 15:35:52.630  1015  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-17 15:35:52.630  1015  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:52.630  1015  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:52.630  1015  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:52.630  1015  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:52.640  7353  7353 E Zygote  : MountEmulatedStorage()
,08-17 15:35:52.640  7353  7353 E Zygote  : v2,
08-17 15:35:52.640  7353  7353 I libpersona: KNOX_SDCARD checking this for 10064
08-17 15:35:52.640  7353  7353 I libpersona: KNOX_SDCARD not a persona
08-17 15:35:52.640  1015  1490 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7353 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 15:35:52.650  7353  7353 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:52.650  7353  7353 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 15:35:52.650  7353  7353 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:35:52.670  7353  7353 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:52.670  7353  7353 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:52.680  7353  7353 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 15:35:52.690  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 15:35:52.700  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 15:35:52.720  7353  7353 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 15:35:52.720  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-17 15:35:52.720  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:52.720  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:52.720  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:52.720  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:52.740  7368  7368 E Zygote  : MountEmulatedStorage(),
08-17 15:35:52.740  7368  7368 E Zygote  : v2
08-17 15:35:52.740  7368  7368 I libpersona: KNOX_SDCARD checking this for 10065
08-17 15:35:52.740  7368  7368 I libpersona: KNOX_SDCARD not a persona,
,08-17 15:35:52.740  7368  7368 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:52.740  7368  7368 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:52.740  1015  1134 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7368 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 15:35:52.740  7368  7368 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 15:35:52.740  1015  1134 I ActivityManager: Killing 6884:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-17 15:35:52.760  7368  7368 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:52.760  7368  7368 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:52.780  7368  7368 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 15:35:52.780  1015  1491 I ActivityManager: Killing 7032:com.android.bluetooth/1002 (adj 15): empty #21
,08-17 15:35:52.880   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 15:35:53.720  7291  7291 I wpa_supplicant: nl80211: Received scan results (25 BSSes)
08-17 15:35:53.720  7291  7291 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 15:35:53.720  7291  7291 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-17 15:35:53.720  7291  7291 I wpa_supplicant: Trying to associate with  'G700'
08-17 15:35:53.720  7291  7291 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-17 15:35:53.720  1015  7350 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-17 15:35:53.720  7291  7291 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-17 15:35:53.740  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 15:35:53.740  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:35:53.840  7291  7291 E wpa_supplicant: Cmd 35605 not handled
,08-17 15:35:53.840  7291  7291 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 15:35:53.840  7291  7291 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-17 15:35:53.840  7291  7291 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 15:35:53.840  7291  7291 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 15:35:53.840  7291  7291 I wpa_supplicant: Associated with F4.99.3E
08-17 15:35:53.840  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 15:35:53.840  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:53.840  7291  7291 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 15:35:53.840  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-17 15:35:53.840  7291  7291 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-17 15:35:53.840  7291  7291 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-17 15:35:53.840  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 15:35:53.840  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-17 15:35:53.840  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:35:53.850  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:53.850  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-17 15:35:53.850  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:35:53.850  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 15:35:53.850  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 15:35:53.850  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-17 15:35:53.850  1015  1129 E Tethering: No numeric data
,08-17 15:35:53.850  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 15:35:53.850  1015  1129 D Tethering: clearTetheredNotification()
,08-17 15:35:53.850  7291  7291 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-17 15:35:53.850  7291  7291 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-17 15:35:53.850  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:53.850  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-17 15:35:53.860  7291  7291 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-17 15:35:53.860  7291  7291 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
08-17 15:35:53.860  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-17 15:35:53.860  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 15:35:53.860  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 15:35:53.860  1172  1172 D HotspotTile: updateTetherState():false, false
08-17 15:35:53.860  7291  7291 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:35:53.860  7291  7291 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-17 15:35:53.860  7291  7291 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-17 15:35:53.860  7291  7291 I wpa_supplicant: Blacklist: Clear (temp) 
08-17 15:35:53.860  1015  1121 V NetworkStats: performPollLocked() took 7ms
08-17 15:35:53.860  7291  7291 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-17 15:35:53.860  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:53.860  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 15:35:53.860  1015  1124 D SecContentProvider2: mCursor = null
08-17 15:35:53.860  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 15:35:53.860  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-17 15:35:53.860  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 15:35:53.860  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:53.860  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:35:53.870  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-17 15:35:53.880  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 15:35:53.880  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:35:53.880  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:35:53.880  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:53.880  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:53.880  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:53.880  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:53.880  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-17 15:35:53.880  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 15:35:53.880  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 15:35:53.880  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 15:35:53.880  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:35:53.880   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 15:35:53.880  1015  1465 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 15:35:53.880  1015  1465 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:35:53.880  1015  1465 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:53.880  1015  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 15:35:53.890  1015  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-17 15:35:53.890  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:35:53.890  1615  1615 I Hs20UtilService: Starting #14
,08-17 15:35:53.890  1615  1649 I Hs20UtilService: Message received 5007
,08-17 15:35:53.900  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 15:35:53.900  3269  3269 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 15:35:53.900  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 15:35:53.900   279   971 D CommandListener: Setting iface cfg
,08-17 15:35:53.900  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 15:35:53.900  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 15:35:53.900  3269  3269 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 15:35:53.900  3269  3802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 15:35:53.910  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,08-17 15:35:53.910  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 15:35:53.910  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:35:53.910  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 15:35:53.910  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:35:53.920  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:35:53.920  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:35:53.920   289   289 E SMD     : DCD OFF
08-17 15:35:53.920  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:53.920  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:53.920  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:53.920  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:53.930  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 15:35:53.930  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:35:53.940  1015  1124 E WifiNative-wlan0: do suspend false
,08-17 15:35:53.940  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-17 15:35:53.940  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 15:35:54.050  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 15:35:54.050  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 15:35:54.050  1015  1028 D SecContentProvider2: mCursor = null
,08-17 15:35:54.050  1015  1028 D WifiService: setWifiEnabled: false pid=6794, uid=10171
,08-17 15:35:54.050  1015  1028 D SettingsProvider: name = wifi_on
,08-17 15:35:54.060  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:35:54.070  1015  1124 E WifiNative-wlan0: do suspend true,
,08-17 15:35:54.090  1015  1123 D WifiP2pService: InactiveState{ what=143375 },
08-17 15:35:54.090  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 15:35:54.100   279   971 D CommandListener: Clearing all IP addresses on wlan0
,08-17 15:35:54.100  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 15:35:54.100  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 15:35:54.100  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:54.100  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.100  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.100  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:54.100  1015  1126 E ConnectivityService: updateNetworkInfo(),
08-17 15:35:54.100  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 15:35:54.100  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-17 15:35:54.110   279   971 E Netd    : no such netId 503,
,08-17 15:35:54.110  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-17 15:35:54.110  1015  1126 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-17 15:35:54.110  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:35:54.110  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-17 15:35:54.110  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 15:35:54.110  1015  1126 V NetworkStats: updateIfacesLocked()
08-17 15:35:54.110  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-17 15:35:54.110  1015  1126 V NetworkStats: performPollLocked(flags=0x1),
,08-17 15:35:54.120  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:35:54.120  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:35:54.120  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.120  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.120  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:54.120  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:54.120  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
08-17 15:35:54.120  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
08-17 15:35:54.120  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 15:35:54.120  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:54.120  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-17 15:35:54.120  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:35:54.130  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:54.130  1015  1126 V NetworkStats: performPollLocked() took 16ms
08-17 15:35:54.130  1015  4287 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 15:35:54.130  1015  4287 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 15:35:54.130  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-17 15:35:54.130  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 15:35:54.130  1015  4287 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:54.130  1015  4287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:54.130  1015  4287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:35:54.130  1615  1615 I Hs20UtilService: Starting #15
,08-17 15:35:54.130  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-17 15:35:54.130  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-17 15:35:54.130  1015  7384 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:54.130  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 15:35:54.130  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 15:35:54.130  1015  7384 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-17 15:35:54.140  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:35:54.140  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 15:35:54.140  1015  1126 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-17 15:35:54.140  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-17 15:35:54.140  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 15:35:54.140  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 15:35:54.140  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:54.140  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:35:54.140  1615  1649 I Hs20UtilService: Message received 5007,
08-17 15:35:54.140  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
,08-17 15:35:54.140  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 15:35:54.150  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-17 15:35:54.150  1015  1124 E WifiNative-wlan0: do suspend true
,08-17 15:35:54.150  1015  1123 D WifiP2pService: P2pDisablingState
08-17 15:35:54.150  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-17 15:35:54.150  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
08-17 15:35:54.150  1015  1123 D WifiP2pService: p2p socket connection lost
08-17 15:35:54.160  3269  3269 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 15:35:54.150  1015  1123 D WifiP2pService: P2pDisabledState
,08-17 15:35:54.160  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 15:35:54.150  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 15:35:54.150  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 15:35:54.150  1015  1046 D WifiDisplayController: disconnect
08-17 15:35:54.150  1015  1046 D WifiDisplayController: updateConnection
08-17 15:35:54.150  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 15:35:54.150  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 15:35:54.160  7387  7387 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-17 15:35:54.160  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 15:35:54.160  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-17 15:35:54.160  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 15:35:54.160  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 15:35:54.160  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
08-17 15:35:54.160  7387  7387 I dhcpcd  : version 5.5.6 starting
,08-17 15:35:54.160  1015  3781 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-17 15:35:54.160  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0,
08-17 15:35:54.160  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-17 15:35:54.160  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 15:35:54.160  3269  3269 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 15:35:54.160  3269  3802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 15:35:54.170  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 15:35:54.170  3269  3269 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 15:35:54.170  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 15:35:54.180  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 15:35:54.180  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 15:35:54.180  3269  3269 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 15:35:54.180  3269  3802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 15:35:54.180  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 15:35:54.180  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 15:35:54.180  7353  7353 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 15:35:54.180  7387  7387 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-17 15:35:54.180  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
08-17 15:35:54.180  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-17 15:35:54.190  7368  7368 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-17 15:35:54.190   279   971 D CommandListener: Clearing all IP addresses on wlan0
,08-17 15:35:54.190  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:35:54.190  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 15:35:54.190  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.200  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.200  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.200  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:54.200  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 15:35:54.200  7291  7291 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-17 15:35:54.200  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 15:35:54.200  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:35:54.200  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.200  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.200  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.200  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:35:54.210  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 15:35:54.210  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:35:54.210  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 15:35:54.210  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:35:54.220  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:54.220  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:54.220  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:35:54.220  1615  1615 I Hs20UtilService: Starting #16
,08-17 15:35:54.220  1615  1649 I Hs20UtilService: Message received 5007
,08-17 15:35:54.230  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:35:54.230  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 15:35:54.230  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.230  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.230  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.230  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:54.230  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 15:35:54.230  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-17 15:35:54.230  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 15:35:54.230  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:35:54.230  1172  1172 D HotspotTile: onReceive : 0, 0
,08-17 15:35:54.230  3269  3269 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-17 15:35:54.230  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:54.230  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:54.230  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:54.230  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:54.230  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:35:54.230  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:54.230  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:54.230  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:54.230  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
08-17 15:35:54.230  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:54.230  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:35:54.240  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:54.240  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:54.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:54.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-17 15:35:54.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:35:54.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:54.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:54.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:54.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:35:54.240  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:54.240  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:35:54.240  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 15:35:54.240  3269  3269 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 15:35:54.240  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 15:35:54.240  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 15:35:54.240  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 15:35:54.240  3269  3269 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 15:35:54.250  3269  3802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 15:35:54.260  1015  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 15:35:54.260  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:35:54.260  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:54.260  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:54.260  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:35:54.260  1615  1615 I Hs20UtilService: Starting #17,
,08-17 15:35:54.260  1615  1649 I Hs20UtilService: Message received 5011
08-17 15:35:54.260  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 15:35:54.260  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 15:35:54.260  7015  7015 D SecurityLogAgent: StateMachine : Current State = 1
08-17 15:35:54.260  7015  7015 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 15:35:54.270  7387  7387 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-17 15:35:54.270  7387  7387 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 15:35:54.270  7387  7387 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-17 15:35:54.270  7387  7387 I dhcpcd  : bssid match
,08-17 15:35:54.270  7387  7387 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-17 15:35:54.310  7291  7291 I wpa_supplicant: Blacklist: Clear (all) ,
,08-17 15:35:54.330  7387  7387 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-17 15:35:54.380  7387  7387 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
08-17 15:35:54.380  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 15:35:54.380  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 15:35:54.380  1015  1043 D Tethering: interfaceStatusChanged p2p0, false,
08-17 15:35:54.380  7291  7291 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-17 15:35:54.410  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:54.410  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-17 15:35:54.410  1015  1129 D Tethering: InitialState.processMessage what=4
08-17 15:35:54.410  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-17 15:35:54.410  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 15:35:54.410  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-17 15:35:54.410  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-17 15:35:54.410  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 15:35:54.410  1015  1129 E Tethering: No numeric data
08-17 15:35:54.410  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:35:54.410  1015  1129 D Tethering: clearTetheredNotification()
,08-17 15:35:54.410  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:54.420  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 15:35:54.410  7291  7291 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-17 15:35:54.420  1172  1172 D HotspotTile: updateTetherState():false, false
08-17 15:35:54.410  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 15:35:54.420  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 15:35:54.410  7291  7291 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 15:35:54.420  1015  1121 V NetworkStats: performPollLocked() took 7ms
08-17 15:35:54.410  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 15:35:54.410  7291  7291 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-17 15:35:54.420  7291  7291 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 15:35:54.420  7291  7291 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 15:35:54.420  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:54.420  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-17 15:35:54.420  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:35:54.420  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:35:54.420  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:35:54.840  7291  7291 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 15:35:54.840  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:35:54.840  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-17 15:35:54.840  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:35:54.890   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 15:35:54.890  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-17 15:35:54.890  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 15:35:54.890  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-17 15:35:54.890  7291  7291 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-17 15:35:55.000  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-17 15:35:55.000  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 15:35:55.000  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 15:35:55.010  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 15:35:55.010  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:55.010  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:55.010  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:55.010  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:35:55.010  6990  6990 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:35:55.010  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 15:35:55.010  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-17 15:35:55.010  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:35:55.010  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 15:35:55.010  1172  1172 D HotspotTile: onReceive : 1, 0
,08-17 15:35:55.010  2038  2220 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:35:55.020  3269  3269 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:35:55.020  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:55.020  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:55.020  1015  1441 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 15:35:55.020  1015  1441 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:35:55.030  1015  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:55.030  1015  1441 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 15:35:55.030  1015  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:35:55.030  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 15:35:55.030  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-17 15:35:55.030  1615  1615 I Hs20UtilService: Starting #18
,08-17 15:35:55.040  7015  7015 D SecurityLogAgent: StateMachine : Current State = 1,
08-17 15:35:55.040  7015  7015 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-17 15:35:55.040  1615  1649 I Hs20UtilService: Message received 5011
,08-17 15:35:55.070  1015  1027 I ActivityManager: Killing 6901:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-17 15:35:55.080  1015  3356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 15:35:55.680   279   965 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-17 15:35:55.680  1015  1043 D Tethering: interfaceRemoved wlan0
,08-17 15:35:55.680  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 15:35:55.820  1015  1043 D Tethering: interfaceRemoved p2p0
,08-17 15:35:55.820  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 15:35:55.890   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 15:35:56.390  1015  2087 V SAMP_SPCM_test: CSC File load.. 
,08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-17 15:35:56.400  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-17 15:35:56.410  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-17 15:35:56.410  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-17 15:35:56.410  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-17 15:35:56.410  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-17 15:35:56.410  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-17 15:35:56.410  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-17 15:35:56.410  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-17 15:35:56.410  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-17 15:35:56.410  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
,08-17 15:35:56.450  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-17 15:35:56.460  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-17 15:35:56.460  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,08-17 15:35:56.460  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-17 15:35:56.460  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-17 15:35:56.460  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-17 15:35:56.460  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages,
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm,
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth,
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory,
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi,
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-17 15:35:56.480  1015  2087 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-17 15:35:56.480  1015  2087 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-17 15:35:56.480  1015  2087 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-17 15:35:56.480  1015  2087 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-17 15:35:56.480  1015  2087 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
,08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 15:35:56.470  1015  2087 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-17 15:35:56.490  7417  7417 E Zygote  : MountEmulatedStorage()
08-17 15:35:56.490  7417  7417 E Zygote  : v2
08-17 15:35:56.490  7417  7417 I libpersona: KNOX_SDCARD checking this for 1000
,08-17 15:35:56.490  7417  7417 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:56.500  7417  7417 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:56.500  1015  2087 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7417 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 15:35:56.500  7417  7417 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:56.500  7417  7417 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:35:56.530  7417  7417 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:56.530  7417  7417 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:56.540  7417  7417 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 15:35:56.570  1015  2087 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-17 15:35:56.580  1015  1015 I ActivityManager: Killing 7049:com.sec.pcw.device/1000 (adj 15): empty #21
,08-17 15:35:56.670  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-17 15:35:56.890   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 15:35:56.910  1015  3322 D SSRM:n  : SIOP:: AP = 350
,08-17 15:35:56.930   289   289 E SMD     : DCD OFF
,08-17 15:35:57.060  6794  6847 D BluetoothAdapter: enable()
,08-17 15:35:57.060  1015  1490 W ActivityManager: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 15:35:57.070  1015  1490 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-17 15:35:57.070  1015  1490 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 15:35:57.070  1015  1490 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 15:35:57.070  1015  1490 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-17 15:35:57.070  1015  1490 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-17 15:35:57.070  1015  1490 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-17 15:35:57.070  1015  1490 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 15:35:57.070  1015  1490 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 15:35:57.070  1015  1490 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 15:35:57.070  1015  1490 D SettingsProvider: name = bluetooth_on
,08-17 15:35:57.080  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 15:35:57.080  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 15:35:57.080  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-17 15:35:57.080  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-17 15:35:57.080  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:57.080  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:57.080  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:57.080  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:57.100  7434  7434 E Zygote  : MountEmulatedStorage(),
,08-17 15:35:57.100  7434  7434 E Zygote  : v2,
08-17 15:35:57.100  7434  7434 I libpersona: KNOX_SDCARD checking this for 1002
08-17 15:35:57.100  7434  7434 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:57.100  7434  7434 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:57.110  1015  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7434 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-17 15:35:57.110  7434  7434 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:57.110  7434  7434 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:35:57.140  7434  7434 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:57.140  7434  7434 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:57.150  7434  7434 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 15:35:57.150  7434  7434 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 15:35:57.180  7434  7434 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 15:35:57.210  7434  7434 D BtSettings.ProfileConfig: Adding GattService
,08-17 15:35:57.220  7434  7434 D BtSettings.ProfileConfig: Adding HeadsetService
08-17 15:35:57.220  7434  7434 D BtSettings.ProfileConfig: Adding A2dpService
,08-17 15:35:57.220  7434  7434 D BtSettings.ProfileConfig: Adding HidService
08-17 15:35:57.220  7434  7434 D BtSettings.ProfileConfig: Adding HealthService
08-17 15:35:57.220  7434  7434 D BtSettings.ProfileConfig: Adding PanService
,08-17 15:35:57.220  7434  7434 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-17 15:35:57.220  7434  7434 D BtSettings.ProfileConfig: Adding SapService
08-17 15:35:57.220  7434  7434 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-17 15:35:57.220  7434  7434 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-17 15:35:57.220  7434  7434 D BtSettings.ProfileConfig: Adding SapClientService
08-17 15:35:57.220  7434  7434 D BtSettings.ProfileConfig: Adding HidDevService
,08-17 15:35:57.220  7434  7434 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 15:35:57.220  1015  4287 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 15:35:57.220  1015  4287 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:57.220  1015  4287 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.220  1015  4287 D SettingsProvider: selectionArgs: false,
08-17 15:35:57.220  1015  4287 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.220  1015  4287 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.220  1015  4287 D SettingsProvider: ret = -1
08-17 15:35:57.220  1015  3782 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-17 15:35:57.220  1015  3782 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:57.220  1015  3782 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.220  1015  3782 D SettingsProvider: selectionArgs: false
08-17 15:35:57.220  1015  3782 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.220  1015  3782 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.220  1015  3782 D SettingsProvider: ret = -1
08-17 15:35:57.220  1015  1441 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-17 15:35:57.220  1015  1441 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:57.220  1015  1441 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.220  1015  1441 D SettingsProvider: selectionArgs: false
,08-17 15:35:57.220  1015  1441 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.220  1015  1441 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.220  1015  1441 D SettingsProvider: ret = -1
08-17 15:35:57.220  1015  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-17 15:35:57.220  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:57.220  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.220  1015  1134 D SettingsProvider: selectionArgs: false
08-17 15:35:57.220  1015  1134 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.220  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.220  1015  1134 D SettingsProvider: ret = -1
08-17 15:35:57.220  1015  1442 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 15:35:57.220  1015  1442 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:57.220  1015  1442 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.220  1015  1442 D SettingsProvider: selectionArgs: false,
08-17 15:35:57.220  1015  1442 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.220  1015  1442 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.220  1015  1442 D SettingsProvider: ret = -1
,08-17 15:35:57.220  1015  1511 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 15:35:57.220  1015  1511 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:57.220  1015  1511 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.220  1015  1511 D SettingsProvider: selectionArgs: false
08-17 15:35:57.220  1015  1511 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.220  1015  1511 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.220  1015  1511 D SettingsProvider: ret = -1
08-17 15:35:57.220  1015  1465 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 15:35:57.220  1015  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:57.220  1015  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.220  1015  1465 D SettingsProvider: selectionArgs: false
08-17 15:35:57.220  1015  1465 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.220  1015  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-17 15:35:57.220  1015  1465 D SettingsProvider: ret = -1
08-17 15:35:57.220  1015  1216 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 15:35:57.220  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:57.220  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 15:35:57.220  1015  1216 D SettingsProvider: selectionArgs: false
08-17 15:35:57.220  1015  1216 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.220  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.230  1015  1216 D SettingsProvider: ret = -1
,08-17 15:35:57.230  1015  3781 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:35:57.230  1015  3781 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 15:35:57.230  1015  3781 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.230  1015  3781 D SettingsProvider: selectionArgs: false
,08-17 15:35:57.230  1015  3781 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.230  1015  3781 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.230  1015  3781 D SettingsProvider: ret = -1
08-17 15:35:57.230  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-17 15:35:57.230  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:57.230  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.230  1015  1027 D SettingsProvider: selectionArgs: false
08-17 15:35:57.230  1015  1027 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.230  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.230  1015  1027 D SettingsProvider: ret = -1
,08-17 15:35:57.230  1015  1501 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 15:35:57.230  1015  1501 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:57.230  1015  1501 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.230  1015  1501 D SettingsProvider: selectionArgs: false
08-17 15:35:57.230  1015  1501 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.230  1015  1501 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.230  1015  1501 D SettingsProvider: ret = -1
08-17 15:35:57.230  1015  1490 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 15:35:57.230  1015  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 15:35:57.230  1015  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.230  1015  1490 D SettingsProvider: selectionArgs: false
08-17 15:35:57.230  1015  1490 D SettingsProvider: selectionArgs: 1002
08-17 15:35:57.230  1015  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.230  1015  1490 D SettingsProvider: ret = -1
,08-17 15:35:57.240  7434  7434 D BluetoothAdapterState: make,
,08-17 15:35:57.250  7434  7434 I bluedroid: init
,08-17 15:35:57.250  7434  7449 I BluetoothAdapterState: Entering OffState
,08-17 15:35:57.250  7434  7434 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-17 15:35:57.250  7434  7434 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 15:35:57.250  7434  7434 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 15:35:57.250  7434  7434 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 15:35:57.250  7434  7434 E bt-btif : btif_fetch_local_ble_random_bdaddr,
08-17 15:35:57.250  7434  7434 I bluedroid: get_profile_interface socket
08-17 15:35:57.250  7434  7434 I bluedroid: get_profile_interface map_client
08-17 15:35:57.250  7434  7452 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 15:35:57.260  7434  7434 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
08-17 15:35:57.260  7434  7452 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-17 15:35:57.260  7434  7452 E BluetoothServiceJni: populateRssiValuesNative
08-17 15:35:57.260  7434  7452 I bluedroid: getModelRssiValues
08-17 15:35:57.260  7434  7452 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-17 15:35:57.260  7434  7452 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 15:35:57.260  1015  1015 D SettingsProvider: name = bluetooth_name
,08-17 15:35:57.260  7434  7452 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 15:35:57.260  7434  7434 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:35:57.260  1015  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 15:35:57.260  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 15:35:57.270  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:57.270  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:57.270  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:57.270  7434  7442 I bluedroid: config_hci_snoop_log
,08-17 15:35:57.270  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-17 15:35:57.270  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-17 15:35:57.270  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 15:35:57.270  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 15:35:57.270  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 15:35:57.280  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 15:35:57.280  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 15:35:57.280  7434  7434 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-17 15:35:57.280  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 15:35:57.280  7434  7449 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 15:35:57.280  7434  7449 D BluetoothAdapterProperties: Setting state to 11
08-17 15:35:57.280  7434  7449 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 15:35:57.280  7434  7449 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 15:35:57.280  7434  7449 D BluetoothAdapterService: updateAdapterState state is 11
08-17 15:35:57.280  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 15:35:57.290  7434  7449 D BluetoothAdapterService: Autoconnection is available 
,08-17 15:35:57.290  7434  7449 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 15:35:57.290  7434  7449 D BluetoothSecureManager: getInstant: null
,08-17 15:35:57.290  7434  7449 D BluetoothSecureManager: calling getMethod for getService
08-17 15:35:57.290  7434  7449 D BluetoothSecureManager: calling getService
,08-17 15:35:57.290  7434  7449 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2bb878a1
,08-17 15:35:57.290  1015  1442 D BluetoothSecureManagerService: isSecureModeEnabled
08-17 15:35:57.290  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:57.290  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
08-17 15:35:57.290  1015  1442 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-17 15:35:57.290  7434  7449 D BtConfig.SecureMode: isSecureModeOn:false
08-17 15:35:57.290  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 15:35:57.290  7434  7449 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-17 15:35:57.290  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 15:35:57.290  7434  7449 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-17 15:35:57.290  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 15:35:57.290  7434  7449 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-17 15:35:57.290  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 15:35:57.290  7434  7449 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-17 15:35:57.290  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 15:35:57.290  7434  7449 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 15:35:57.290  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 15:35:57.300  7434  7449 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-17 15:35:57.300  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 15:35:57.300  7434  7449 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,08-17 15:35:57.300  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 15:35:57.300  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 15:35:57.300  7434  7449 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-17 15:35:57.300  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 15:35:57.300  7434  7449 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:35:57.300  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 15:35:57.310  7434  7449 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:35:57.310  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-17 15:35:57.310  7434  7449 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 15:35:57.310  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 15:35:57.310  7434  7449 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-17 15:35:57.310  1861  1861 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 15:35:57.320  3269  3269 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:57.320  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:57.320  1172  1172 D BluetoothTile:  getBluetoothState : 11
,08-17 15:35:57.320  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:57.320  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 15:35:57.320  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 15:35:57.320  7434  7449 D BluetoothBondStateMachine: make
,08-17 15:35:57.320  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:57.320  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:57.320  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:57.320  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:57.320  1015  1501 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 15:35:57.320  1015  1490 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 15:35:57.330  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 15:35:57.330  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 15:35:57.330  7434  7454 I BluetoothBondStateMachine: StableState(): Entering Off State
08-17 15:35:57.330  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 15:35:57.330  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 15:35:57.330  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
08-17 15:35:57.330  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 15:35:57.330  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 15:35:57.330  1015  4287 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:35:57.330  1015  4287 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 15:35:57.330  3269  3269 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 15:35:57.340  1015  4287 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:57.340  1015  4287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:57.340  1015  4287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 15:35:57.340  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 15:35:57.340  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 15:35:57.340  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 15:35:57.340  7434  7434 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 15:35:57.340  7434  7434 D BtGatt.GattService: Received start request. Starting profile...
08-17 15:35:57.340  7434  7434 D BtGatt.GattService: start()
08-17 15:35:57.340  7434  7434 D BtGatt.GattService: start()
08-17 15:35:57.340  7434  7434 I bluedroid: get_profile_interface gatt
,08-17 15:35:57.340  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:35:57.340  7434  7434 D BtGatt.AdvertiseManager: advertise manager created
,08-17 15:35:57.350  1015  1465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:35:57.350  1015  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 15:35:57.350  1015  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:57.350  1015  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:57.350  1015  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:57.350  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 15:35:57.350  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 15:35:57.350  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 15:35:57.350  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:57.350  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 15:35:57.350  1015  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:35:57.350  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 15:35:57.360  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:57.360  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:57.360  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:57.360  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 15:35:57.360  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 15:35:57.360  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 15:35:57.360  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 15:35:57.360  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:57.360  7434  7434 D BtGatt.GattService: mStartError = false
08-17 15:35:57.360  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:35:57.360  7434  7434 D HeadsetService: Received start request. Starting profile...
,08-17 15:35:57.370  7434  7434 D HeadsetService: start()
08-17 15:35:57.370  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:57.370  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:57.370  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:57.370  7434  7434 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:35:57.370  7434  7434 D HeadsetStateMachine: make
,08-17 15:35:57.370  7434  7434 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 15:35:57.380  7459  7459 E Zygote  : MountEmulatedStorage(),
08-17 15:35:57.380  7459  7459 E Zygote  : v2
08-17 15:35:57.380  7459  7459 I libpersona: KNOX_SDCARD checking this for 10055
08-17 15:35:57.380  7459  7459 I libpersona: KNOX_SDCARD not a persona
,08-17 15:35:57.380  7459  7459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:57.380  7459  7459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:35:57.380  1015  1134 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7459 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-17 15:35:57.380  7459  7459 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 15:35:57.380  1015  1501 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone,
08-17 15:35:57.380  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:57.380  1015  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-17 15:35:57.380  1015  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:57.380  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 15:35:57.390  1015  1442 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-17 15:35:57.390  1015  1442 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:57.390  1015  1442 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-17 15:35:57.390  1015  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:57.390  1015  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:57.390  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 15:35:57.390  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 15:35:57.390  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-17 15:35:57.390  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:57.390  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 15:35:57.390  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:57.390  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:57.390  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:57.390  1015  3782 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-17 15:35:57.390  1015  3782 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-17 15:35:57.400  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 15:35:57.400  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 15:35:57.400  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 15:35:57.400  1015  3782 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:57.400  1015  3782 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:57.400  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 15:35:57.400  7434  7434 I bluedroid: get_profile_interface handsfree
,08-17 15:35:57.400  1015  1441 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:35:57.400  1015  1441 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 15:35:57.400  1015  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:57.400  1015  1441 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 15:35:57.400  1015  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:57.410  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 15:35:57.410  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 15:35:57.410  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 15:35:57.410  1015  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:57.410  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 15:35:57.410  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:57.410  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:57.410  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:57.410  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 15:35:57.410  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 15:35:57.410  7434  7449 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 15:35:57.410  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:57.410  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 15:35:57.410  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:57.410  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:57.420  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:57.420  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:35:57.420  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:35:57.420  7434  7449 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:35:57.420  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:35:57.420  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:35:57.420  7434  7449 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:35:57.420  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 15:35:57.420  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 15:35:57.420  7434  7449 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 15:35:57.420  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 15:35:57.420  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 15:35:57.420  7434  7449 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 15:35:57.420  7434  7449 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 15:35:57.420  7434  7434 I DualScoManager: Instantiating Dual Sco Manager
08-17 15:35:57.420  7434  7434 I DualScoManager: Set HeadsetServiceHelper
,08-17 15:35:57.430  7434  7434 D BluetoothAtMessage: createCMTIContentObservers
,08-17 15:35:57.430  7459  7459 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:57.430  1015  3782 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-17 15:35:57.430  7459  7459 D ActivityThread: Added TimaKeyStore provider
08-17 15:35:57.430  1015  3782 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:57.430  1015  3782 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:57.430  1015  3782 D SettingsProvider: selectionArgs: false
,08-17 15:35:57.430  1015  3782 D SettingsProvider: selectionArgs: 1002
,08-17 15:35:57.430  1015  3782 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:57.430  1015  3782 D SettingsProvider: ret = -1
,08-17 15:35:57.430  7434  7458 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 15:35:57.430  7434  7434 D HeadsetService: mStartError = false
,08-17 15:35:57.440  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:35:57.440  7434  7458 D HeadsetStateMachine: Clear mHeadsetBrsf
08-17 15:35:57.440  7434  7458 D HeadsetStateMachine: map size, before remove : 0
08-17 15:35:57.440  7434  7458 D HeadsetStateMachine: map size, after remove: 0
,08-17 15:35:57.440  7434  7434 D A2dpService: Received start request. Starting profile...
,08-17 15:35:57.440  7434  7434 D A2dpService: start()
,08-17 15:35:57.440  7434  7434 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 15:35:57.440  7434  7434 I bluedroid: get_profile_interface avrcp
,08-17 15:35:57.450  7434  7434 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 15:35:57.450  7434  7434 D Avrcp   : Initialize Media Controller
08-17 15:35:57.450  7434  7434 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-17 15:35:57.450  7434  7434 E Avrcp   : getActiveSessions
08-17 15:35:57.450  7434  7434 D Avrcp   : pick active media Controller
08-17 15:35:57.450  7434  7434 D Avrcp   : Get the active Media Controller 
,08-17 15:35:57.460  7459  7459 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-17 15:35:57.470  7434  7434 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 15:35:57.470  7434  7477 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-17 15:35:57.470  7434  7434 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:35:57.470  7434  7434 D A2dpStateMachine: make
,08-17 15:35:57.470  7434  7434 I bluedroid: get_profile_interface a2dp
,08-17 15:35:57.480  7434  7479 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-17 15:35:57.480  7434  7434 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 15:35:57.480  7434  7477 D BluetoothMediaBrowser: no now playing list
,08-17 15:35:57.480  7434  7477 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 15:35:57.480  7434  7434 D A2dpService: mStartError = false
,08-17 15:35:57.480  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:35:57.480  7434  7478 D A2dpStateMachine: Enter Disconnected: -2
08-17 15:35:57.480  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-17 15:35:57.480  7434  7434 D HeadsetStateMachine: Try to query the phonestate on bind
,08-17 15:35:57.480  1435  1475 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 15:35:57.480  1435  1435 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-17 15:35:57.480  1435  1435 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 15:35:57.490  1435  1475 I Telecom : BluetoothPhoneService: Result of Message : true
,08-17 15:35:57.490  7434  7434 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 15:35:57.490  7434  7434 D HidService: Received start request. Starting profile...
,08-17 15:35:57.490  7434  7434 D HidService: start()
,08-17 15:35:57.490  7434  7434 I bluedroid: get_profile_interface hidhost
08-17 15:35:57.490  7434  7434 D HidService: setHidService(): set to: null
,08-17 15:35:57.490  7434  7434 D HidService: mStartError = false
08-17 15:35:57.490  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:35:57.490  7434  7434 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 15:35:57.490  7459  7459 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-17 15:35:57.490  7459  7459 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-17 15:35:57.490  7459  7459 D UserAnalysis: Create SecureDbHelper
,08-17 15:35:57.490  7434  7434 D HealthService: Received start request. Starting profile...
,08-17 15:35:57.500  7434  7434 D HealthService: start()
,08-17 15:35:57.500  7434  7434 I bluedroid: get_profile_interface health
,08-17 15:35:57.500  7434  7434 D HealthService: mStartError = false
08-17 15:35:57.500  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:35:57.500  7459  7459 D IntelligenceServiceApplication: onCreate()
08-17 15:35:57.500  7434  7434 D HeadsetStateMachine: Proxy object connected
,08-17 15:35:57.500  7434  7434 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-17 15:35:57.500  7434  7458 D HeadsetStateMachine: Disconnected process message: 11
,08-17 15:35:57.500  7434  7434 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 15:35:57.510  7434  7434 D PanService: Received start request. Starting profile...
08-17 15:35:57.510  7434  7434 D PanService: start()
08-17 15:35:57.510  7434  7434 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 15:35:57.510  7434  7434 I bluedroid: get_profile_interface pan
,08-17 15:35:57.510  1015  1511 I ActivityManager: Killing 7066:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-17 15:35:57.510  7434  7434 D PanService: mStartError = false
08-17 15:35:57.510  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:35:57.510  7434  7434 D BluetoothMapService: Received start request. Starting profile...
08-17 15:35:57.510  7434  7434 D BluetoothMapService: start()
,08-17 15:35:57.510  7459  7459 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-17 15:35:57.510  7434  7434 D BluetoothMapService: mStartError = false
,08-17 15:35:57.510  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:35:57.510  7434  7434 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 15:35:57.510  7434  7434 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-17 15:35:57.510  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-17 15:35:57.510  7434  7434 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-17 15:35:57.510  7434  7458 D HeadsetStateMachine: Disconnected process message: 18
,08-17 15:35:57.510  7459  7459 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-17 15:35:57.520  7434  7434 D SapService: Received start request. Starting profile...
08-17 15:35:57.520  7434  7434 D SapService: start()
08-17 15:35:57.520  7434  7434 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 15:35:57.520  7434  7434 I bluedroid: get_profile_interface sap
08-17 15:35:57.520  7434  7434 D SapService: mStartError = false
08-17 15:35:57.520  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:35:57.520  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-17 15:35:57.520  7434  7434 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 15:35:57.520  7434  7434 D BluetoothA2dp: Proxy object connected
08-17 15:35:57.520  7434  7434 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-17 15:35:57.520  7434  7458 D HeadsetStateMachine: Disconnected process message: 10
08-17 15:35:57.520  7434  7458 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 15:35:57.520  7434  7458 D HeadsetStateMachine: Disconnected process message: 11
,08-17 15:35:57.520  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 15:35:57.520  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-17 15:35:57.520  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 15:35:57.520  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 15:35:57.520  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-17 15:35:57.520  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:57.520  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:57.520  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:35:57.520  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:35:57.520  7459  7459 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-17 15:35:57.540  7484  7484 E Zygote  : MountEmulatedStorage()
,08-17 15:35:57.540  7484  7484 E Zygote  : v2
08-17 15:35:57.540  7484  7484 I libpersona: KNOX_SDCARD checking this for 10105
08-17 15:35:57.540  7484  7484 I libpersona: KNOX_SDCARD not a persona
08-17 15:35:57.540  1015  1028 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7484 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
08-17 15:35:57.540  7484  7484 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:35:57.540  7484  7484 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:35:57.540  7484  7484 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 15:35:57.560  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-17 15:35:57.560  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 15:35:57.560  7434  7449 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-17 15:35:57.560  7434  7449 I bluedroid: enable
,08-17 15:35:57.560  7434  7449 I bt_hci_bdroid: init
08-17 15:35:57.560  7434  7498 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-17 15:35:57.570  7484  7484 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:35:57.570  7484  7484 D ActivityThread: Added TimaKeyStore provider
,08-17 15:35:57.570  7434  7449 I bt_vendor: bt-vendor : init
,08-17 15:35:57.570  7434  7449 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 15:35:57.570  7434  7449 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 15:35:57.570  7434  7449 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-17 15:35:57.570  7434  7449 D bt_userial_mct: userial_init
,08-17 15:35:57.570  7434  7449 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 15:35:57.570  7434  7449 I bt_vendor: Starting hciattach daemon
08-17 15:35:57.570  7434  7449 I bt_vendor: try to set false
,08-17 15:35:57.570  7434  7449 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 15:35:57.570  7434  7449 I bt_vendor: Starting hciattach daemon
08-17 15:35:57.570  7434  7449 I bt_vendor: try to set true
,08-17 15:35:57.590  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-17 15:35:57.640  7509  7509 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-17 15:35:57.650  7510  7510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 15:35:57.670  7514  7514 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 15:35:57.670  7515  7515 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 15:35:57.680  7516  7516 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 15:35:57.690  7517  7517 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-17 15:35:57.730   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 15:35:57.730   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 15:35:57.730  7484  7521 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 15:35:57.730   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 15:35:57.740   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 15:35:57.740  7484  7521 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 15:35:57.870  7484  7484 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-17 15:35:57.870  7484  7484 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:57.870  7484  7484 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:57.870  7484  7484 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:57.870  7484  7484 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.k.d(PG:583)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:57.870  7484  7484 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:57.870  7484  7484 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:57.870  1015  1490 I ActivityManager: Killing 7078:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-17 15:35:57.870  7484  7484 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:35:57.870  7484  7484 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:35:57.880  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 15:35:57.880  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-17 15:35:57.890   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-17 15:35:57.930  7484  7527 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-17 15:35:57.950  1015  4287 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 15:35:57.950  1015  4287 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:57.950  1015  4287 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:57.950  1015  4287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 15:35:57.970  7534  7534 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-17 15:35:57.980  7535  7535 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 15:35:58.030  7434  7449 I bt_vendor: bluetooth satus is on
08-17 15:35:58.030  7434  7501 D bt_userial_mct: userial_open(port:0)
,08-17 15:35:58.030  7434  7501 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 15:35:58.030  7434  7501 I bt_vendor: Done intiailizing UART
,08-17 15:35:58.030  7434  7501 I bt_vendor: Done intiailizing UART
08-17 15:35:58.030  7434  7501 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-17 15:35:58.030  7434  7501 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 15:35:58.030  7434  7537 D bt_userial_mct: Entering userial_read_thread()
,08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_BTM
,08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_PAN
,08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_SAP
08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_GATT
,08-17 15:35:58.040  7434  7498 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 15:35:58.050  7434  7498 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-17 15:35:58.050  7434  7498 I         : BTE_InitTraceLevels -- TRC_BTIF,
08-17 15:35:58.050  7434  7498 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-17 15:35:58.140  7434  7498 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 15:35:58.140  7434  7498 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4262ed1 
,08-17 15:35:58.140  7434  7498 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4262ed1 
,08-17 15:35:58.160  7434  7452 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 15:35:58.160  7434  7452 E bt-btif : Calling BTA_HhEnable
,08-17 15:35:58.160  7434  7452 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-17 15:35:58.160  7434  7452 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-17 15:35:58.160  7434  7452 E BluetoothServiceJni: populateRssiValuesNative
08-17 15:35:58.160  7434  7452 I bluedroid: getModelRssiValues
,08-17 15:35:58.160  7434  7452 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 15:35:58.160  7434  7452 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 15:35:58.170  7434  7452 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 15:35:58.170  1015  1015 D SettingsProvider: name = bluetooth_name
,08-17 15:35:58.170  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:58.180  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:58.180  7434  7452 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 15:35:58.180  7434  7452 D BluetoothAdapterProperties: Scan Mode:20
,08-17 15:35:58.180  7434  7452 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 15:35:58.180  7434  7452 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-17 15:35:58.180  7434  7452 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-17 15:35:58.180  7434  7537 E bt_mct  : hci lib postload completed
,08-17 15:35:58.180  7434  7452 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-17 15:35:58.190  7434  7452 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-17 15:35:58.190  7434  7452 E bt-btif : btif_sock_init: !vhci_init
,08-17 15:35:58.190  7434  7452 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-17 15:35:58.190  7434  7452 D IOP_DB_BT: db_open: db_open : handle 3027951632l, read 13894 bytes onto local cache
,08-17 15:35:58.190  7434  7452 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-17 15:35:58.190  7434  7452 D IOP_DB_BT: db_query: result 1
08-17 15:35:58.190  7434  7452 I         : iop_db_open: iop_db_open status 0
,08-17 15:35:58.190  7434  7452 D bte_conf: Device ID record 1 : primary
,08-17 15:35:58.190  7434  7452 D bte_conf:   vendorId            = 0075
08-17 15:35:58.190  7434  7452 D bte_conf:   vendorIdSource      = 0001
08-17 15:35:58.190  7434  7452 D bte_conf:   product             = 0100
,08-17 15:35:58.190  7434  7452 D bte_conf:   version             = 0200
,08-17 15:35:58.190  7434  7452 D bte_conf:   clientExecutableURL = 
08-17 15:35:58.190  7434  7452 D bte_conf:   serviceDescription  = 
08-17 15:35:58.190  7434  7452 D bte_conf:   documentationURL    = 
08-17 15:35:58.190  7434  7452 D bte_conf: bte_load_did_conf no section named DID2.
,08-17 15:35:58.190  7434  7452 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 15:35:58.200  7434  7449 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-17 15:35:58.200  7434  7449 D BluetoothAdapterProperties: ScanMode =  20
08-17 15:35:58.200  7434  7449 D BluetoothAdapterProperties: State =  11
08-17 15:35:58.200  1015  1442 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-17 15:35:58.200  7434  7449 D BluetoothAdapterProperties: Setting state to 12
08-17 15:35:58.200  7434  7449 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 15:35:58.200  7434  7452 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 15:35:58.200  7434  7452 D BluetoothAdapterProperties: Scan Mode:21
08-17 15:35:58.200  7434  7452 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:35:58.200  1015  3782 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-17 15:35:58.200  1015  3782 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:35:58.200  1015  3782 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:35:58.200  1015  3782 D SettingsProvider: selectionArgs: false
08-17 15:35:58.200  1015  3782 D SettingsProvider: selectionArgs: 1002
08-17 15:35:58.200  1015  3782 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:35:58.200  1015  3782 D SettingsProvider: ret = -1
,08-17 15:35:58.200  7434  7449 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 15:35:58.200  7434  7449 D BluetoothAdapterService: updateAdapterState state is 12
,08-17 15:35:58.210  1015  1511 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:58.210  1015  1511 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.210  1015  1511 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:58.210  1015  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.210  1015  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:58.210  6794  6802 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:35:58.210  6794  6802 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 15:35:58.210  7434  7449 D BluetoothAdapterService: Autoconnection is available 
08-17 15:35:58.210  7434  7449 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 15:35:58.210  7434  7449 D BluetoothAdapterService: starting service from this receiver
08-17 15:35:58.210  1015  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:35:58.210  1015  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-17 15:35:58.220  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-17 15:35:58.220  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:58.220  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:58.220  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:35:58.220  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:58.220  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:58.220  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:58.220  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:35:58.220  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.220  1015  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.220  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 15:35:58.220  1464  1660 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:35:58.220  7434  7449 I BluetoothAdapterState: Entering On State from state = 11
08-17 15:35:58.220  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 15:35:58.220  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 15:35:58.220  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.220  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.220  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:58.220  1464  1660 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 15:35:58.220  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:35:58.230  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 15:35:58.230  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 15:35:58.230  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:35:58.230  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 15:35:58.230  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:35:58.230  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:35:58.230  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 15:35:58.230  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.230  1015  1015 D BluetoothA2dp: Proxy object connected
,08-17 15:35:58.230  3269  3277 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:35:58.240  3269  3277 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:35:58.240  7434  7434 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-17 15:35:58.240  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 15:35:58.240  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.240  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.240  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.240  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:58.240  3269  3269 D BluetoothA2dp: Proxy object connected
,08-17 15:35:58.240  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:58.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:58.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:35:58.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:35:58.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:58.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:58.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:58.240  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:35:58.240  3269  3269 D A2dpProfile: Bluetooth service connected
,08-17 15:35:58.240  7434  7442 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:35:58.250  1435  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:35:58.250  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 15:35:58.250  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 15:35:58.250  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.250  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.250  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:58.250  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:35:58.250  1435  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 15:35:58.250  2038  2066 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:35:58.250  2038  2066 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:35:58.250  1435  1475 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:35:58.250  1435  1475 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:35:58.250  7434  7434 I BluetoothPbapService: Handler(): got msg=1
08-17 15:35:58.250  3269  3278 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 15:35:58.250  1015  1442 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 15:35:58.260  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-17 15:35:58.260  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.260  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.260  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.260  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:58.260  3269  3277 D BluetoothPan: Binding service...,
08-17 15:35:58.260  3269  3269 D BluetoothMap: Proxy object connected
08-17 15:35:58.260  3269  3269 D MapProfile: Bluetooth service connected
08-17 15:35:58.260  3269  3269 D BluetoothMap: getConnectedDevices()
,08-17 15:35:58.260  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 15:35:58.260  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-17 15:35:58.260  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.260  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.260  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:58.260  7434  7543 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-17 15:35:58.260  1464  1660 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 15:35:58.260  1464  1660 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 15:35:58.260  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:35:58.260  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:35:58.270  3269  3278 D Bluetoothsap: onBluetoothStateChange: up=true
08-17 15:35:58.270  3269  3278 D Bluetoothsap: Binding service...
,08-17 15:35:58.270  3269  3269 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 15:35:58.270  3269  3269 D PanProfile: Bluetooth service connected
08-17 15:35:58.270  7434  7543 D BluetoothSocket: bindListen(): myUserId = 0
08-17 15:35:58.270  7434  7543 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:35:58.270  7434  7543 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-17 15:35:58.270  7434  7543 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 15:35:58.270  7434  7543 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 15:35:58.270  7434  7543 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c4aa00a
08-17 15:35:58.270  7434  7543 D BluetoothSocket: channel: 19
08-17 15:35:58.270  7434  7543 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 15:35:58.270  3269  3278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 15:35:58.270  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-17 15:35:58.270  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.270  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.270  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 15:35:58.270  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:58.280  3269  3278 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-17 15:35:58.280  3269  3269 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-17 15:35:58.280  3269  3269 D SapProfile: Bluetooth service connected
08-17 15:35:58.280  3269  3269 D Bluetoothsap: getConnectedDevices()
08-17 15:35:58.280  1435  1475 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:35:58.280  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 15:35:58.280  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 15:35:58.280  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:58.280  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.280  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-17 15:35:58.280  1435  1475 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 15:35:58.280  7434  7444 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:35:58.280  7434  7444 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:35:58.280  1446  1486 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:35:58.280  1446  1486 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:35:58.280  1172  1196 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 15:35:58.280  1172  1196 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:35:58.280  3269  3278 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 15:35:58.280  3269  3278 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:35:58.280  7484  7493 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 15:35:58.280  7484  7493 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 15:35:58.290  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 15:35:58.280  1015  1045 D BluetoothPan: Binding service...
08-17 15:35:58.290  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.290  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:35:58.290  3269  3277 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 15:35:58.290  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-17 15:35:58.290  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.290  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:58.290  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.290  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:58.290  3269  3269 D BluetoothInputDevice: Proxy object connected
,08-17 15:35:58.290  3269  3269 D HidProfile: Bluetooth service connected
,08-17 15:35:58.290  1435  1475 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:35:58.290  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 15:35:58.300  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 15:35:58.300  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.300  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.300  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:58.300  1435  1475 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 15:35:58.300  3269  3278 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 15:35:58.300  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-17 15:35:58.300  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.300  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:58.300  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.300  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:58.300  3269  7541 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:35:58.300  3269  3269 D BluetoothPbap: Proxy object connected
08-17 15:35:58.300  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 15:35:58.300  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 15:35:58.300  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.300  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.300  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-17 15:35:58.300  3269  3269 D PbapServerProfile: Bluetooth service connected
,08-17 15:35:58.300  3269  7541 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 15:35:58.300  3269  3269 D HeadsetProfile: Bluetooth service connected
08-17 15:35:58.300  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 15:35:58.300  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 15:35:58.310  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:35:58.310  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-17 15:35:58.310  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 15:35:58.310  1435  1435 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@12f6f426, true
,08-17 15:35:58.310  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-17 15:35:58.310  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:58.310  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 15:35:58.310  1172  1172 D BluetoothTile:  getBluetoothState : 12
,08-17 15:35:58.320  1435  1435 D BluetoothHeadset: registerMessageListener
08-17 15:35:58.320  1861  1861 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 15:35:58.320  1015  1441 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 15:35:58.320  1015  3781 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-17 15:35:58.320  1015  1442 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 15:35:58.320  1015  1442 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.320  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:58.320  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 15:35:58.320  7434  7453 D HeadsetService: registerMessageListener
,08-17 15:35:58.320  1015  1442 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.320  7434  7453 D HeadsetService: registerMessageListener
,08-17 15:35:58.320  1015  1442 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:58.320  7434  7458 D HeadsetStateMachine: Disconnected process message: 70
08-17 15:35:58.320  1015  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 15:35:58.320  7434  7458 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2a45607b
,08-17 15:35:58.330  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 15:35:58.330  1435  1435 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-17 15:35:58.330  1435  1435 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 15:35:58.330  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:58.330  3269  3269 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:35:58.330  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 15:35:58.330  7434  7546 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-17 15:35:58.330  1435  1435 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-17 15:35:58.330  1435  1435 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-17 15:35:58.330  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 15:35:58.330  1435  1435 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-17 15:35:58.340  3269  3269 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-17 15:35:58.340  3269  3269 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 15:35:58.340  3269  3269 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-17 15:35:58.340  3269  3269 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-17 15:35:58.340  7434  7458 D HeadsetStateMachine: Disconnected process message: 9
,08-17 15:35:58.340  7434  7458 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-17 15:35:58.340  7434  7546 D BluetoothSocket: bindListen(): myUserId = 0,
08-17 15:35:58.340  7434  7546 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:35:58.340  7434  7546 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
,08-17 15:35:58.340  7434  7546 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 15:35:58.340  7434  7546 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 15:35:58.340  7434  7546 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d11be98
08-17 15:35:58.340  7434  7546 D BluetoothSocket: channel: 5
,08-17 15:35:58.350  3269  3269 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:35:58.350  1015  1216 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 15:35:58.350  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.350  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.350  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.350  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 15:35:58.360   284  1347 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-17 15:35:58.360   284  1347 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 15:35:58.360   284  1347 V voice   : voice_set_parameters: exit with code(-2)
08-17 15:35:58.360   284  1347 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 15:35:58.360   284  1347 V msm8974_platform: platform_set_parameters: exit with code(-2)
,08-17 15:35:58.360   284  1347 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 15:35:58.360   284  1347 V audio_hw_primary: adev_set_parameters: exit
,08-17 15:35:58.360  7434  7458 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-17 15:35:58.360  3269  3269 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:35:58.360  3269  3269 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 15:35:58.370  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:58.370  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 15:35:58.370  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:35:58.370  7434  7434 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 15:35:58.380  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-17 15:35:58.380  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.380  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.380  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:35:58.380  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:35:58.390  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 15:35:58.390  1015  1441 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 15:35:58.390  1015  1441 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 15:35:58.390  1015  1441 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.390  1015  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:58.390  1015  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:58.410  1015  1465 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 15:35:58.410  2038  7553 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-17 15:35:58.410  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 15:35:58.430  7434  7556 D BluetoothSocket: bindListen(): myUserId = 0
08-17 15:35:58.430  7434  7556 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:35:58.430  7434  7556 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-17 15:35:58.430  7434  7556 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 15:35:58.430  7434  7556 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 15:35:58.430  7434  7556 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c72662
08-17 15:35:58.430  7434  7556 D BluetoothSocket: channel: 12
08-17 15:35:58.430  7434  7556 I BtOppRfcommListener: Accept thread started.
,08-17 15:35:58.570  1015  1490 I art     : Explicit concurrent mark sweep GC freed 70377(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.252ms total 154.675ms
08-17 15:35:58.570  1015  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:35:58.580  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:35:58.580  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:58.580  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:58.590  1015  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:35:58.590  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:35:58.590  1015  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:35:58.590  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:35:58.600  2038  7553 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-17 15:35:59.930   289   289 E SMD     : DCD OFF,
,08-17 15:35:59.990  1015  1094 V AlarmManager: waitForAlarm result :8
,08-17 15:36:00.080  6794  6847 D BluetoothAdapter: disable()
,08-17 15:36:00.080  1015  1441 D SettingsProvider: name = bluetooth_on
,08-17 15:36:00.100  7434  7449 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-17 15:36:00.100  7434  7449 D BluetoothAdapterProperties: Setting state to 13
08-17 15:36:00.100  1015  4287 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:36:00.100  7434  7449 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 15:36:00.100  1015  4287 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-17 15:36:00.100  7434  7449 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 15:36:00.100  7434  7449 D BluetoothAdapterService: updateAdapterState state is 13
,08-17 15:36:00.110  1015  4287 W ActivityManager: userId = 0, bbcId = -10000,
08-17 15:36:00.110  1015  4287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:00.110  1015  4287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:00.110  7434  7434 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-17 15:36:00.110  7434  7449 D BluetoothAdapterService: Autoconnection is available 
08-17 15:36:00.110  7434  7449 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-17 15:36:00.110  7434  7449 D BluetoothAdapterService: terminating service from this receiver
,08-17 15:36:00.110  7434  7434 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e4963f3, channel: 19, state: LISTENING
08-17 15:36:00.110  7434  7434 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e4963f3, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c4aa00a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@12a5c8b0mSocket: android.net.LocalSocket@1bdc4329 impl:android.net.LocalSocketImpl@13f546ae fd:FileDescriptor[74]
,08-17 15:36:00.110  1015  3782 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-17 15:36:00.110  7434  7434 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1bdc4329 impl:android.net.LocalSocketImpl@13f546ae fd:FileDescriptor[74]
08-17 15:36:00.110  1015  3782 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:00.110  1015  3782 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:00.110  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:00.120  7434  7449 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 15:36:00.120  7434  7449 D BluetoothAdapterProperties: mDiscovering is false
,08-17 15:36:00.120  1015  3781 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 15:36:00.120  7434  7449 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 15:36:00.120  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:00.120  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-17 15:36:00.130  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-17 15:36:00.130  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 15:36:00.130  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 15:36:00.130  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 15:36:00.140  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:00.140  1172  1172 D BluetoothTile:  getBluetoothState : 13
,08-17 15:36:00.140  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 15:36:00.140  1861  1861 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 15:36:00.140  3269  3269 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:00.150  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 15:36:00.150  1015  1441 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 15:36:00.150  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 15:36:00.150  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:00.150  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:00.150  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:00.150  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:36:00.150  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:00.150  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:36:00.150  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:00.150  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:00.150  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:36:00.160  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:36:00.160  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:00.160  1015  4287 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 15:36:00.160  1015  4287 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 15:36:00.160  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:36:00.160  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:00.160  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:00.160  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:36:00.160  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:00.160  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:36:00.160  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:00.160  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:00.160  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:00.160  1015  4287 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:00.160  1015  4287 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:36:00.160  1015  4287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:36:00.160  6794  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:36:00.160  7434  7452 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 15:36:00.160  7434  7452 D BluetoothAdapterProperties: Scan Mode:20
,08-17 15:36:00.170  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:36:00.170  7434  7449 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-17 15:36:00.170  7434  7449 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-17 15:36:00.170  7434  7449 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-17 15:36:00.170  7434  7449 E bt-btif : cmd socket is not created
08-17 15:36:00.170  7434  7556 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 15:36:00.170  7434  7498 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-17 15:36:00.170  7434  7498 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-17 15:36:00.170  7434  7449 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 15:36:00.170  7434  7498 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:36:00.170  7434  7498 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:36:00.170  7434  7498 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 15:36:00.170  3269  3269 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:36:00.170  1015  1441 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 15:36:00.170  1015  1441 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 15:36:00.180  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:00.180  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:00.180  1015  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:00.190  1015  1441 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 15:36:00.190  1015  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 15:36:00.190  7434  7434 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@138c4c4f, channel: 5, state: LISTENING
08-17 15:36:00.190  7434  7434 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@138c4c4f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d11be98, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2616bfdcmSocket: android.net.LocalSocket@264ce8e5 impl:android.net.LocalSocketImpl@3d31fba fd:FileDescriptor[76]
08-17 15:36:00.190  7434  7434 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@264ce8e5 impl:android.net.LocalSocketImpl@3d31fba fd:FileDescriptor[76]
,08-17 15:36:00.190  7434  7434 I BtOppRfcommListener: stopping Accept Thread
08-17 15:36:00.190  7434  7434 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@386b5e6b, channel: 12, state: LISTENING
08-17 15:36:00.190  7434  7434 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@386b5e6b, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c72662, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2e3dfdc8mSocket: android.net.LocalSocket@24682e61 impl:android.net.LocalSocketImpl@3e837d86 fd:FileDescriptor[80]
08-17 15:36:00.190  7434  7434 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@24682e61 impl:android.net.LocalSocketImpl@3e837d86 fd:FileDescriptor[80]
08-17 15:36:00.190  7434  7556 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 15:36:00.200  3269  3269 D BluetoothPbap: Proxy object disconnected
,08-17 15:36:00.200  3269  3269 D PbapServerProfile: Bluetooth service disconnected
,08-17 15:36:00.210  7434  7434 V BluetoothOppManager: cleanUp...
,08-17 15:36:00.220  3269  3269 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:36:00.220  3269  3269 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 15:36:00.220  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:00.220  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 15:36:00.240  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 15:36:00.240  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 15:36:00.370  7434  7498 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:36:00.370  7434  7498 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:36:00.370  7434  7498 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:36:00.370  7434  7498 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:36:00.370  7434  7498 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:36:00.370  7434  7498 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:36:00.370  7434  7498 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:36:00.370  7434  7498 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:36:00.370  7434  7498 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:36:00.370  7434  7498 W bt-btif : ag scb idx 1 not allocated
08-17 15:36:00.370  7434  7498 W bt-btif : ag scb idx 2 not allocated
08-17 15:36:00.370  7434  7498 E bt-btif : BTA AG is already disabled, ignoring ...
,08-17 15:36:00.370  7434  7537 I bt_userial_mct: exiting userial_read_thread
08-17 15:36:00.370  7434  7537 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 15:36:00.370  7434  7452 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 15:36:00.370  7434  7501 I bt_vendor: hw_epilog_process
,08-17 15:36:00.370  7434  7452 D bt_userial_mct: userial_close
08-17 15:36:00.370  7434  7452 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-17 15:36:00.430  1015  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 15:36:00.430  1015  1501 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-17 15:36:00.430  1015  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 15:36:00.430  1015  1501 D BatteryService: stay LED for fully charged
08-17 15:36:00.430  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 15:36:00.440  1015  1015 I MotionRecognitionService: Plugged
,08-17 15:36:00.440  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 15:36:00.440  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 15:36:00.440  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 15:36:00.440  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 15:36:00.440  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 15:36:00.460  7434  7434 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 15:36:00.460  7434  7458 D HeadsetStateMachine: Disconnected process message: 10
,08-17 15:36:00.470  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 15:36:00.470  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 15:36:00.470  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 15:36:01.460  7434  7452 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-17 15:36:01.460  7434  7452 I bt_vendor: bluetooth satus is on
08-17 15:36:01.460  7434  7452 I bt_vendor: bt-vendor : resetting BT status
08-17 15:36:01.460  7434  7452 I bt_vendor: Starting hciattach daemon
08-17 15:36:01.460  7434  7452 I bt_vendor: try to set false
,08-17 15:36:01.460  7434  7452 I bt_vendor: Starting hciattach daemon
08-17 15:36:01.460  7434  7452 I bt_vendor: try to set false
,08-17 15:36:01.460  7434  7452 I bt_vendor: cleanup
,08-17 15:36:01.460  7434  7498 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-17 15:36:01.460  7434  7452 I GKI_LINUX: GKI_exit_task 0 done
,08-17 15:36:01.460  1015  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:36:01.460  7434  7452 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-17 15:36:01.460  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
08-17 15:36:01.460  7434  7449 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-17 15:36:01.470  1015  1441 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-17 15:36:01.460  7434  7449 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 15:36:01.470  1015  1441 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 15:36:01.460  7434  7449 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-17 15:36:01.470  1015  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:36:01.460  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
08-17 15:36:01.470  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 15:36:01.460  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 15:36:01.460  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-17 15:36:01.470  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:36:01.460  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:01.470  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 15:36:01.460  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-17 15:36:01.460  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-17 15:36:01.460  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-17 15:36:01.480  1015  4287 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-17 15:36:01.460  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 15:36:01.480  1015  4287 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-17 15:36:01.460  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 15:36:01.470  7434  7434 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 15:36:01.470  7434  7434 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 15:36:01.470  7434  7434 D BtGatt.GattService: stop()
08-17 15:36:01.470  7434  7434 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 15:36:01.470  1015  1441 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:01.470  1015  1441 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:01.480  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:36:01.470  1015  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 15:36:01.480  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 15:36:01.470  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:36:01.470  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 15:36:01.470  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 15:36:01.470  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-17 15:36:01.470  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:01.470  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 15:36:01.470  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 15:36:01.470  7434  7434 D HeadsetService: Received stop request...Stopping profile...
08-17 15:36:01.470  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 15:36:01.470  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 15:36:01.470  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-17 15:36:01.470  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:01.470  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:01.470  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 15:36:01.480  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 15:36:01.480  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 15:36:01.480  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-17 15:36:01.480  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:36:01.480  1015  4287 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:01.480  1015  4287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:01.480  1015  4287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 15:36:01.480  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 15:36:01.480  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 15:36:01.480  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-17 15:36:01.490  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 15:36:01.490  3269  3269 D HeadsetProfile: Bluetooth service disconnected
08-17 15:36:01.490  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:01.490  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:01.490  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 15:36:01.490  1015  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:36:01.490  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 15:36:01.490  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-17 15:36:01.490  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:01.490  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:01.490  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 15:36:01.490  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-17 15:36:01.490  1015  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:36:01.490  1015  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 15:36:01.490  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:01.490  1015  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:01.490  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:36:01.490  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:36:01.490  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 15:36:01.490  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 15:36:01.490  7434  7449 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 15:36:01.490  7434  7449 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 15:36:01.490  7434  7449 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 15:36:01.490  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-17 15:36:01.500  7434  7434 D A2dpService: Received stop request...Stopping profile...
08-17 15:36:01.500  7434  7478 D A2dpStateMachine: Exit Disconnected: -1
,08-17 15:36:01.500  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:36:01.500  7434  7434 D HidService: Received stop request...Stopping profile...
08-17 15:36:01.500  7434  7434 D HidService: Stopping Bluetooth HidService
08-17 15:36:01.500  7434  7434 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 15:36:01.500  3269  3269 D BluetoothA2dp: Proxy object disconnected
08-17 15:36:01.500  3269  3269 D A2dpProfile: Bluetooth service disconnected
08-17 15:36:01.500  7434  7434 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 15:36:01.500  7434  7434 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 15:36:01.500  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:36:01.500  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-17 15:36:01.500  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 15:36:01.500  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 15:36:01.500  7434  7434 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 15:36:01.500  7434  7434 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 15:36:01.500  7434  7434 D HealthService: Received stop request...Stopping profile...
08-17 15:36:01.500  3269  3269 D BluetoothInputDevice: Proxy object disconnected
08-17 15:36:01.500  3269  3269 D HidProfile: Bluetooth service disconnected
08-17 15:36:01.500  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:36:01.510  7434  7434 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 15:36:01.510  7434  7434 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:36:01.510  7434  7434 D PanService: Received stop request...Stopping profile...
08-17 15:36:01.510  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
08-17 15:36:01.510  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 15:36:01.510  3269  3269 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 15:36:01.510  3269  3269 D PanProfile: Bluetooth service disconnected
,08-17 15:36:01.510  7434  7434 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 15:36:01.510  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:36:01.510  7434  7434 D SapService: Received stop request...Stopping profile...
08-17 15:36:01.520  7434  7434 D SapService: Stopping Bluetooth SapService
08-17 15:36:01.520  7434  7434 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18eaabf0
,08-17 15:36:01.520  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true,
08-17 15:36:01.520  7434  7434 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 15:36:01.520  7434  7434 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 15:36:01.520  7434  7434 D BluetoothA2dp: Proxy object disconnected
08-17 15:36:01.520  7434  7434 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-17 15:36:01.520  3269  3269 D BluetoothMap: Proxy object disconnected
08-17 15:36:01.520  3269  3269 D MapProfile: Bluetooth service disconnected
08-17 15:36:01.520  3269  3269 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 15:36:01.520  3269  3269 D SapProfile: Bluetooth service disconnected
08-17 15:36:01.520  7434  7479 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 15:36:01.520  7434  7434 I GKI_LINUX: GKI_exit_task 2 done
08-17 15:36:01.520  7434  7434 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 15:36:01.520  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 15:36:01.520  7434  7434 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 15:36:01.520  7434  7434 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService,
08-17 15:36:01.520  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 15:36:01.520  7434  7434 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 15:36:01.520  7434  7434 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 15:36:01.520  7434  7434 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 15:36:01.520  7434  7434 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:36:01.520  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 15:36:01.520  7434  7434 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 15:36:01.520  7434  7434 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 15:36:01.520  7434  7434 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 15:36:01.520  7434  7434 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 15:36:01.520  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-17 15:36:01.520  7434  7434 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 15:36:01.520  7434  7434 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-17 15:36:01.520  7434  7434 E BluetoothAdapterService(418032624): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-17 15:36:01.520  7434  7434 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 15:36:01.520  7434  7434 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 15:36:01.520  7434  7449 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-17 15:36:01.520  7434  7449 D BluetoothAdapterProperties: Setting state to 10
,08-17 15:36:01.520  7434  7449 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 15:36:01.520  7434  7449 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 15:36:01.520  7434  7449 D BluetoothAdapterService: updateAdapterState state is 10
08-17 15:36:01.530  6794  6802 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 15:36:01.530  6794  6802 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:36:01.530  6794  6802 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-17 15:36:01.530  6794  6802 D BluetoothLeAdvertiser: Exit stop advertising
08-17 15:36:01.530  6794  6802 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-17 15:36:01.530  6794  6802 D BluetoothLeScanner: Exiting stopAllScan
,08-17 15:36:01.530  7434  7449 D BluetoothAdapterService: Autoconnection is available 
08-17 15:36:01.530  7434  7449 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 15:36:01.530  7434  7449 I BluetoothAdapterState: Entering OffState
08-17 15:36:01.530  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false,
08-17 15:36:01.530  3269  3277 D BluetoothA2dp: onBluetoothStateChange: up=false,
08-17 15:36:01.530  7434  7453 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:36:01.530  2038  2051 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 15:36:01.530  2038  2051 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 15:36:01.530  1435  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:36:01.530  1435  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 15:36:01.530  3269  3278 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 15:36:01.530  1464  1660 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:36:01.530  1464  1660 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:36:01.530  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:36:01.530  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:36:01.530  3269  3277 D Bluetoothsap: onBluetoothStateChange: up=false
08-17 15:36:01.530  3269  3277 D Bluetoothsap: Unbinding service...
,08-17 15:36:01.540  7434  7444 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:36:01.540  7434  7444 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:36:01.540  1446  1486 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:36:01.540  1446  1486 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 15:36:01.540  1172  2341 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:36:01.540  1172  2341 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:36:01.540  3269  3278 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:36:01.540  3269  3278 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:36:01.540  7484  7496 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 15:36:01.540  7484  7496 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 15:36:01.540  3269  7541 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 15:36:01.540  3269  3277 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 15:36:01.540  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 15:36:01.540  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 15:36:01.550  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:01.550  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-17 15:36:01.550  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 15:36:01.550  1172  1172 D BluetoothAdapter: 704121744: getState() :  mService = null. Returning STATE_OFF
08-17 15:36:01.550  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 15:36:01.550  1172  1755 D BluetoothAdapter: 704121744: getState() :  mService = null. Returning STATE_OFF
,08-17 15:36:01.550  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:01.550  1172  1172 D BluetoothTile:  getBluetoothState : 10
08-17 15:36:01.550  1172  1755 D BluetoothAdapter: 704121744: getState() :  mService = null. Returning STATE_OFF
,08-17 15:36:01.560  1172  1172 D BluetoothAdapter: 704121744: getState() :  mService = null. Returning STATE_OFF
08-17 15:36:01.560  1172  1172 D BluetoothAdapter: 704121744: getState() :  mService = null. Returning STATE_OFF
,08-17 15:36:01.560  1015  1442 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 15:36:01.560  1861  1861 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 15:36:01.560  1015  3781 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 15:36:01.560  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 15:36:01.560  2038  2220 D BluetoothAdapter: 782673457: getState() :  mService = null. Returning STATE_OFF
08-17 15:36:01.560  2038  2220 D BluetoothAdapter: 782673457: getState() :  mService = null. Returning STATE_OFF
,08-17 15:36:01.560  7434  7452 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 15:36:01.560  7434  7434 I GKI_LINUX: GKI_exit_task 1 done
08-17 15:36:01.560  7434  7434 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 15:36:01.560  7434  7434 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 15:36:01.560  3269  3269 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:01.560  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:01.560  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:01.560  1015  3782 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 15:36:01.560  1015  3782 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 15:36:01.570  1015  3782 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:01.570  1015  3782 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 15:36:01.570  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 15:36:01.570  3269  3269 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 15:36:01.570  7434  7434 I art     : System.exit called, status: 0
08-17 15:36:01.570  7434  7434 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 15:36:01.570  1015  1442 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 15:36:01.570  1015  1442 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 15:36:01.570  1015  1442 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:01.570  1015  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:01.570  1015  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 15:36:01.580  3269  3269 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:36:01.580  3269  3269 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 15:36:01.590  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:01.590  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 15:36:01.610  1015  4287 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-17 15:36:01.610  1015  4287 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-17 15:36:01.620  1015  4287 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-17 15:36:01.620  1015  4287 W BroadcastQueue: android.os.TransactionTooLargeException
08-17 15:36:01.620  1015  4287 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 15:36:01.620  1015  4287 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 15:36:01.620  1015  4287 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-17 15:36:01.620  1015  4287 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-17 15:36:01.620  1015  4287 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-17 15:36:01.620  1015  4287 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-17 15:36:01.620  1015  4287 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-17 15:36:01.620  1015  4287 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-17 15:36:01.620  1015  4287 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 15:36:01.620  1015  4287 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-17 15:36:01.620  1015  4287 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:01.620  1015  4287 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:01.620  1015  4287 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:01.620  1015  4287 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:01.640  7574  7574 E Zygote  : MountEmulatedStorage()
08-17 15:36:01.640  7574  7574 I libpersona: KNOX_SDCARD checking this for 1002
08-17 15:36:01.640  7574  7574 E Zygote  : v2
08-17 15:36:01.640  7574  7574 I libpersona: KNOX_SDCARD not a persona
,08-17 15:36:01.650  1015  4287 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7574 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-17 15:36:01.650  7574  7574 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:36:01.650  7574  7574 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 15:36:01.650  7574  7574 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:36:01.660   308   308 I art     : Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 20.414ms
,08-17 15:36:01.670  7574  7574 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:01.670  7574  7574 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:01.680   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.461ms
,08-17 15:36:01.690  7574  7574 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 15:36:01.690  7574  7574 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 15:36:01.700   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 16.598ms
,08-17 15:36:01.710  7574  7574 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding GattService
,08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding HeadsetService
,08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding A2dpService
08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding HidService
,08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding HealthService
08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding PanService
08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding SapService
08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding SapClientService
08-17 15:36:01.740  7574  7574 D BtSettings.ProfileConfig: Adding HidDevService
,08-17 15:36:01.740  7574  7574 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 15:36:01.750  1015  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 15:36:01.750  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:01.750  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:01.750  1015  1134 D SettingsProvider: selectionArgs: false
08-17 15:36:01.750  1015  1134 D SettingsProvider: selectionArgs: 1002
08-17 15:36:01.750  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:01.750  1015  1134 D SettingsProvider: ret = -1
,08-17 15:36:01.750  1015  1465 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-17 15:36:01.750  1015  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:01.750  1015  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:01.750  1015  1465 D SettingsProvider: selectionArgs: false
08-17 15:36:01.750  1015  1465 D SettingsProvider: selectionArgs: 1002
08-17 15:36:01.750  1015  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:01.750  1015  1465 D SettingsProvider: ret = -1
,08-17 15:36:01.750  1015  3781 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-17 15:36:01.750  1015  3781 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:01.750  1015  3781 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:01.750  1015  3781 D SettingsProvider: selectionArgs: false
08-17 15:36:01.750  1015  3781 D SettingsProvider: selectionArgs: 1002
08-17 15:36:01.750  1015  3781 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:01.750  1015  3781 D SettingsProvider: ret = -1
,08-17 15:36:01.750  1015  3782 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-17 15:36:01.750  1015  3782 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 15:36:01.750  1015  3782 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:01.750  1015  3782 D SettingsProvider: selectionArgs: false
08-17 15:36:01.750  1015  3782 D SettingsProvider: selectionArgs: 1002
08-17 15:36:01.750  1015  3782 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:01.750  1015  3782 D SettingsProvider: ret = -1
,08-17 15:36:01.750  1015  1442 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 15:36:01.750  1015  1442 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:01.750  1015  1442 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:01.750  1015  1442 D SettingsProvider: selectionArgs: false
08-17 15:36:01.750  1015  1442 D SettingsProvider: selectionArgs: 1002
08-17 15:36:01.750  1015  1442 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:01.750  1015  1442 D SettingsProvider: ret = -1
,08-17 15:36:01.750  1015  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 15:36:01.750  1015  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:01.750  1015  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:01.750  1015  1491 D SettingsProvider: selectionArgs: false
08-17 15:36:01.750  1015  1491 D SettingsProvider: selectionArgs: 1002
08-17 15:36:01.750  1015  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:01.750  1015  1491 D SettingsProvider: ret = -1
,08-17 15:36:01.750  1015  1511 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-17 15:36:01.750  1015  1511 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:01.750  1015  1511 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:01.750  1015  1511 D SettingsProvider: selectionArgs: false
,08-17 15:36:01.750  1015  1511 D SettingsProvider: selectionArgs: 1002
08-17 15:36:01.750  1015  1511 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 15:36:01.760  1015  1511 D SettingsProvider: ret = -1
,08-17 15:36:01.760  1015  1490 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 15:36:01.760  1015  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:01.760  1015  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:01.760  1015  1490 D SettingsProvider: selectionArgs: false
08-17 15:36:01.760  1015  1490 D SettingsProvider: selectionArgs: 1002
08-17 15:36:01.760  1015  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:01.760  1015  1490 D SettingsProvider: ret = -1
,08-17 15:36:01.760  1015  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:36:01.760  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:01.760  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 15:36:01.760  1015  1216 D SettingsProvider: selectionArgs: false
08-17 15:36:01.760  1015  1216 D SettingsProvider: selectionArgs: 1002
08-17 15:36:01.760  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:01.760  1015  1216 D SettingsProvider: ret = -1
,08-17 15:36:01.760  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:36:01.760  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:01.760  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:01.760  1015  1027 D SettingsProvider: selectionArgs: false
08-17 15:36:01.760  1015  1027 D SettingsProvider: selectionArgs: 1002
,08-17 15:36:01.760  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:01.760  1015  1027 D SettingsProvider: ret = -1
,08-17 15:36:01.760  1015  4287 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-17 15:36:01.760  1015  4287 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:01.760  1015  4287 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:01.760  1015  4287 D SettingsProvider: selectionArgs: false
,08-17 15:36:01.760  1015  4287 D SettingsProvider: selectionArgs: 1002
08-17 15:36:01.760  1015  4287 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 15:36:01.760  1015  4287 D SettingsProvider: ret = -1
,08-17 15:36:01.760  1015  1441 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 15:36:01.760  1015  1441 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 15:36:01.760  1015  1441 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:01.760  1015  1441 D SettingsProvider: selectionArgs: false
08-17 15:36:01.760  1015  1441 D SettingsProvider: selectionArgs: 1002
,08-17 15:36:01.760  1015  1441 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:01.760  1015  1441 D SettingsProvider: ret = -1
,08-17 15:36:01.780  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 15:36:01.780  1015  3782 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 15:36:01.780  1015  3782 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 15:36:01.780  1015  3782 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:01.780  1015  3782 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:36:01.780  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:36:01.790  2038  7590 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 15:36:01.790  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 15:36:01.790  1015  3782 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:36:01.800  1015  3782 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:01.800  1015  3782 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:36:01.800  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:36:01.800  2038  7590 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 15:36:02.930   289   289 E SMD     : DCD OFF,
,08-17 15:36:03.100  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop,
08-17 15:36:03.100  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-17 15:36:05.930   289   289 E SMD     : DCD OFF,
,08-17 15:36:06.110  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:06.110  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39703d7a added. We now have 6 listener(s)
08-17 15:36:06.110  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:36:06.110  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:06.110  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2de1892b added. We now have 7 listener(s)
08-17 15:36:06.110  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:06.110  6794  6847 I System.out: IsBluetoothEnabled
,08-17 15:36:06.110  6794  6847 D BluetoothAdapter: disable()
08-17 15:36:06.110  1015  1501 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-17 15:36:06.110  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 15:36:06.110  6794  6847 D BluetoothAdapter: enable()
,08-17 15:36:06.110  1015  4287 W ActivityManager: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 15:36:06.120  1015  4287 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-17 15:36:06.120  1015  4287 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 15:36:06.120  1015  4287 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 15:36:06.120  1015  4287 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-17 15:36:06.120  1015  4287 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
,08-17 15:36:06.120  1015  4287 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-17 15:36:06.120  1015  4287 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 15:36:06.120  1015  4287 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 15:36:06.120  1015  4287 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 15:36:06.120  1015  4287 D SettingsProvider: name = bluetooth_on,
,08-17 15:36:06.120  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 15:36:06.120  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 15:36:06.120  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-17 15:36:06.120  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-17 15:36:06.140  7574  7574 D BluetoothAdapterState: make
,08-17 15:36:06.150  7574  7574 I bluedroid: init
,08-17 15:36:06.150  7574  7574 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-17 15:36:06.150  7574  7574 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 15:36:06.150  7574  7574 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 15:36:06.150  7574  7574 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 15:36:06.150  7574  7596 I BluetoothAdapterState: Entering OffState
,08-17 15:36:06.160  7574  7574 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-17 15:36:06.160  7574  7574 I bluedroid: get_profile_interface socket
,08-17 15:36:06.160  7574  7574 I bluedroid: get_profile_interface map_client
,08-17 15:36:06.160  7574  7574 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-17 15:36:06.160  7574  7599 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-17 15:36:06.160  7574  7599 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-17 15:36:06.160  7574  7599 E BluetoothServiceJni: populateRssiValuesNative
,08-17 15:36:06.160  7574  7599 I bluedroid: getModelRssiValues
,08-17 15:36:06.160  7574  7599 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 15:36:06.170  7574  7599 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 15:36:06.170  7574  7574 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:36:06.170  1015  1015 D SettingsProvider: name = bluetooth_name
,08-17 15:36:06.170  7574  7599 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 15:36:06.170  1015  1216 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 15:36:06.170  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:06.170  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.170  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:06.170  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:06.170  7574  7583 I bluedroid: config_hci_snoop_log
08-17 15:36:06.170  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 15:36:06.180  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-17 15:36:06.180  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 15:36:06.180  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-17 15:36:06.180  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 15:36:06.180  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 15:36:06.180  7574  7574 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-17 15:36:06.180  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 15:36:06.180  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 15:36:06.190  7574  7596 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 15:36:06.190  7574  7596 D BluetoothAdapterProperties: Setting state to 11
,08-17 15:36:06.190  7574  7596 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 15:36:06.190  7574  7596 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 15:36:06.190  7574  7596 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 15:36:06.190  7574  7596 D BluetoothAdapterService: Autoconnection is available 
08-17 15:36:06.190  7574  7596 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 15:36:06.190  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:06.190  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-17 15:36:06.200  7574  7596 D BluetoothSecureManager: getInstant: null
08-17 15:36:06.200  7574  7596 D BluetoothSecureManager: calling getMethod for getService
08-17 15:36:06.200  7574  7596 D BluetoothSecureManager: calling getService
,08-17 15:36:06.200  7574  7596 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@12f86a87
,08-17 15:36:06.200  1015  3782 D BluetoothSecureManagerService: isSecureModeEnabled
08-17 15:36:06.200  1015  3782 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-17 15:36:06.200  7574  7596 D BtConfig.SecureMode: isSecureModeOn:false
08-17 15:36:06.200  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 15:36:06.200  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 15:36:06.200  7574  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-17 15:36:06.200  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 15:36:06.200  7574  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-17 15:36:06.200  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 15:36:06.200  7574  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-17 15:36:06.200  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 15:36:06.210  7574  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-17 15:36:06.210  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 15:36:06.210  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:06.210  1172  1172 D BluetoothTile:  getBluetoothState : 11
,08-17 15:36:06.210  1861  1861 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 15:36:06.210  7574  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 15:36:06.210  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 15:36:06.210  7574  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-17 15:36:06.210  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 15:36:06.210  7574  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-17 15:36:06.210  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 15:36:06.210  7574  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-17 15:36:06.210  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:36:06.210  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 15:36:06.210  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-17 15:36:06.210  7574  7596 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:36:06.210  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 15:36:06.210  3269  3269 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-17 15:36:06.210  7574  7596 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:36:06.210  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 15:36:06.210  7574  7596 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-17 15:36:06.210  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 15:36:06.210  7574  7596 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-17 15:36:06.210  7574  7596 D BluetoothBondStateMachine: make
,08-17 15:36:06.210  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:06.220  1015  1442 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 15:36:06.220  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 15:36:06.220  1015  1465 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 15:36:06.220  1015  1465 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.220  1015  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:06.220  1015  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:36:06.220  1015  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 15:36:06.220  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 15:36:06.220  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 15:36:06.220  7574  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 15:36:06.220  1015  1491 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 15:36:06.220  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 15:36:06.220  7574  7601 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 15:36:06.230  1015  1511 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:36:06.230  1015  1511 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.230  1015  1511 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:06.230  1015  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:06.230  1015  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:06.230  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 15:36:06.230  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 15:36:06.230  7574  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-17 15:36:06.230  3269  3269 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 15:36:06.230  7574  7574 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 15:36:06.230  7574  7574 D BtGatt.GattService: Received start request. Starting profile...
08-17 15:36:06.230  7574  7574 D BtGatt.GattService: start()
08-17 15:36:06.230  7574  7574 D BtGatt.GattService: start()
08-17 15:36:06.230  7574  7574 I bluedroid: get_profile_interface gatt
,08-17 15:36:06.230  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@256afbee
,08-17 15:36:06.230  7574  7574 D BtGatt.AdvertiseManager: advertise manager created
,08-17 15:36:06.230  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:36:06.240  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.240  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:06.240  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 15:36:06.240  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:06.240  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:06.240  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:06.240  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 15:36:06.240  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 15:36:06.240  7574  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 15:36:06.250  1015  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:36:06.250  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.250  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:06.250  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:06.250  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:06.250  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 15:36:06.250  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 15:36:06.250  7574  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 15:36:06.250  7574  7574 D BtGatt.GattService: mStartError = false
,08-17 15:36:06.250  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@256afbee
,08-17 15:36:06.250  7574  7574 D HeadsetService: Received start request. Starting profile...
,08-17 15:36:06.250  7574  7574 D HeadsetService: start()
08-17 15:36:06.250  1015  3782 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:36:06.260  1015  3782 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.260  7574  7574 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 15:36:06.260  7574  7574 D HeadsetStateMachine: make
,08-17 15:36:06.260  1015  3782 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:06.260  1015  3782 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:06.260  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:06.260  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-17 15:36:06.260  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 15:36:06.260  7574  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 15:36:06.260  1015  1442 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:36:06.260  1015  1442 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.270  1015  1442 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:06.270  1015  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:06.270  1015  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:06.270  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-17 15:36:06.270  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 15:36:06.270  7574  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-17 15:36:06.270  1015  1511 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:36:06.270  1015  1511 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.270  7574  7574 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 15:36:06.270  1015  1511 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:06.270  1015  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:06.270  1015  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:06.270  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 15:36:06.280  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 15:36:06.280  7574  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 15:36:06.280  1015  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:36:06.280  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.280  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:06.280  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:06.280  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:06.280  1015  1216 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-17 15:36:06.280  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.290  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 15:36:06.290  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 15:36:06.290  7574  7596 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 15:36:06.290  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:06.290  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:06.290  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-17 15:36:06.290  1015  3782 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:36:06.290  1015  3782 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.290  1015  3782 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:06.290  1015  3782 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:06.290  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:06.290  1015  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-17 15:36:06.290  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-17 15:36:06.290  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:06.290  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:06.290  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 15:36:06.300  7574  7574 I bluedroid: get_profile_interface handsfree
,08-17 15:36:06.300  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:36:06.300  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:36:06.300  7574  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 15:36:06.300  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:36:06.300  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:36:06.300  7574  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 15:36:06.300  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 15:36:06.300  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 15:36:06.300  7574  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 15:36:06.300  7574  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 15:36:06.300  7574  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 15:36:06.300  7574  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 15:36:06.300  7574  7596 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 15:36:06.310  7574  7574 I DualScoManager: Instantiating Dual Sco Manager
08-17 15:36:06.310  7574  7574 I DualScoManager: Set HeadsetServiceHelper
08-17 15:36:06.310  7574  7574 D BluetoothAtMessage: createCMTIContentObservers
,08-17 15:36:06.310  1015  1465 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-17 15:36:06.310  1015  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:06.310  1015  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:06.310  1015  1465 D SettingsProvider: selectionArgs: false
08-17 15:36:06.310  1015  1465 D SettingsProvider: selectionArgs: 1002
08-17 15:36:06.310  1015  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:06.310  1015  1465 D SettingsProvider: ret = -1
,08-17 15:36:06.310  7574  7605 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 15:36:06.310  7574  7574 D HeadsetService: mStartError = false
08-17 15:36:06.310  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@256afbee
,08-17 15:36:06.320  7574  7605 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-17 15:36:06.320  7574  7605 D HeadsetStateMachine: map size, before remove : 0
08-17 15:36:06.320  7574  7605 D HeadsetStateMachine: map size, after remove: 0
,08-17 15:36:06.320  7574  7574 D A2dpService: Received start request. Starting profile...
,08-17 15:36:06.320  7574  7574 D A2dpService: start()
,08-17 15:36:06.320  7574  7574 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 15:36:06.320  7574  7574 I bluedroid: get_profile_interface avrcp
,08-17 15:36:06.330  7574  7574 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 15:36:06.330  7574  7574 D Avrcp   : Initialize Media Controller
,08-17 15:36:06.330  7574  7574 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-17 15:36:06.330  7574  7574 E Avrcp   : getActiveSessions
,08-17 15:36:06.330  7574  7574 D Avrcp   : pick active media Controller
08-17 15:36:06.330  7574  7574 D Avrcp   : Get the active Media Controller 
,08-17 15:36:06.350  7574  7574 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 15:36:06.350  7574  7609 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
08-17 15:36:06.350  7574  7574 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:36:06.350  7574  7574 D A2dpStateMachine: make,
,08-17 15:36:06.350  7574  7574 I bluedroid: get_profile_interface a2dp
,08-17 15:36:06.350  7574  7611 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-17 15:36:06.350  7574  7574 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 15:36:06.360  7574  7574 D A2dpService: mStartError = false
08-17 15:36:06.360  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@256afbee
,08-17 15:36:06.360  7574  7574 E BluetoothAdapterService(627768302): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-17 15:36:06.360  7574  7574 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 15:36:06.360  7574  7610 D A2dpStateMachine: Enter Disconnected: -2
08-17 15:36:06.360  7574  7609 D BluetoothMediaBrowser: no now playing list
08-17 15:36:06.360  7574  7609 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 15:36:06.360  7574  7574 D HidService: Received start request. Starting profile...
08-17 15:36:06.360  7574  7574 D HidService: start()
08-17 15:36:06.360  7574  7574 I bluedroid: get_profile_interface hidhost
08-17 15:36:06.360  7574  7574 D HidService: setHidService(): set to: null
08-17 15:36:06.360  7574  7574 D HidService: mStartError = false
08-17 15:36:06.360  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@256afbee
,08-17 15:36:06.360  7574  7574 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 15:36:06.370  7574  7574 D HealthService: Received start request. Starting profile...
08-17 15:36:06.370  7574  7574 D HealthService: start()
,08-17 15:36:06.370  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 15:36:06.370  7574  7574 I bluedroid: get_profile_interface health
,08-17 15:36:06.370  7574  7574 D HealthService: mStartError = false
08-17 15:36:06.370  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@256afbee
,08-17 15:36:06.370  7574  7574 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 15:36:06.370  7574  7574 D PanService: Received start request. Starting profile...
,08-17 15:36:06.370  7574  7574 D PanService: start()
08-17 15:36:06.370  7574  7574 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 15:36:06.370  7574  7574 I bluedroid: get_profile_interface pan
,08-17 15:36:06.370  7574  7574 D PanService: mStartError = false,
08-17 15:36:06.370  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@256afbee
,08-17 15:36:06.380  7574  7574 D BluetoothMapService: Received start request. Starting profile...
08-17 15:36:06.380  7574  7574 D BluetoothMapService: start()
,08-17 15:36:06.380  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 15:36:06.380  7574  7574 D BluetoothMapService: mStartError = false
,08-17 15:36:06.380  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@256afbee
08-17 15:36:06.380  7574  7574 D HeadsetStateMachine: Try to query the phonestate on bind
,08-17 15:36:06.380  1435  7544 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 15:36:06.380  1435  1435 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-17 15:36:06.380  1435  1435 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 15:36:06.380  1435  7544 I Telecom : BluetoothPhoneService: Result of Message : true
,08-17 15:36:06.380  7574  7574 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-17 15:36:06.380  7574  7574 D SapService: Received start request. Starting profile...
08-17 15:36:06.380  7574  7574 D SapService: start()
08-17 15:36:06.380  7574  7574 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 15:36:06.380  7574  7574 I bluedroid: get_profile_interface sap
08-17 15:36:06.380  7574  7574 D SapService: mStartError = false
08-17 15:36:06.380  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@256afbee
08-17 15:36:06.390  7574  7574 D HeadsetStateMachine: Proxy object connected
,08-17 15:36:06.390  7574  7574 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-17 15:36:06.390  7574  7574 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-17 15:36:06.390  7574  7574 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-17 15:36:06.390  7574  7605 D HeadsetStateMachine: Disconnected process message: 11
08-17 15:36:06.390  7574  7574 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 15:36:06.390  7574  7574 E BluetoothAdapterService(627768302): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-17 15:36:06.390  7574  7574 D BluetoothA2dp: Proxy object connected
08-17 15:36:06.390  7574  7574 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-17 15:36:06.390  7574  7574 E BluetoothAdapterService(627768302): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 15:36:06.390  7574  7605 D HeadsetStateMachine: Disconnected process message: 18
08-17 15:36:06.390  7574  7605 D HeadsetStateMachine: Disconnected process message: 10
,08-17 15:36:06.390  7574  7605 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 15:36:06.390  7574  7605 D HeadsetStateMachine: Disconnected process message: 11
,08-17 15:36:06.390  7574  7574 E BluetoothAdapterService(627768302): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-17 15:36:06.390  7574  7574 E BluetoothAdapterService(627768302): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 15:36:06.390  7574  7574 E BluetoothAdapterService(627768302): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 15:36:06.410  7574  7574 E BluetoothAdapterService(627768302): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-17 15:36:06.410  7574  7574 E BluetoothAdapterService(627768302): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 15:36:06.420  7574  7596 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-17 15:36:06.420  7574  7596 I bluedroid: enable
,08-17 15:36:06.420  7574  7596 I bt_hci_bdroid: init
,08-17 15:36:06.420  7574  7616 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-17 15:36:06.420  7574  7596 I bt_vendor: bt-vendor : init
,08-17 15:36:06.420  7574  7596 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 15:36:06.420  7574  7596 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-17 15:36:06.420  7574  7596 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-17 15:36:06.420  7574  7596 D bt_userial_mct: userial_init
,08-17 15:36:06.420  7574  7596 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 15:36:06.420  7574  7596 I bt_vendor: Starting hciattach daemon
08-17 15:36:06.420  7574  7596 I bt_vendor: try to set false
,08-17 15:36:06.420  7574  7596 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
08-17 15:36:06.420  7574  7596 I bt_vendor: Starting hciattach daemon
08-17 15:36:06.420  7574  7596 I bt_vendor: try to set true
,08-17 15:36:06.440  7620  7620 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-17 15:36:06.480  7626  7626 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-17 15:36:06.490  7627  7627 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 15:36:06.510  7629  7629 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 15:36:06.520  7630  7630 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 15:36:06.530  7631  7631 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 15:36:06.540  7632  7632 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-17 15:36:06.820  7635  7635 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-17 15:36:06.830  7636  7636 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 15:36:06.880  7574  7596 I bt_vendor: bluetooth satus is on,
08-17 15:36:06.880  7574  7618 D bt_userial_mct: userial_open(port:0)
08-17 15:36:06.880  7574  7618 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 15:36:06.880  7574  7618 I bt_vendor: Done intiailizing UART
,08-17 15:36:06.880  7574  7618 I bt_vendor: Done intiailizing UART
08-17 15:36:06.880  7574  7618 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 15:36:06.880  7574  7618 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 15:36:06.880  7574  7638 D bt_userial_mct: Entering userial_read_thread()
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_SAP
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 15:36:06.890  7574  7616 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-17 15:36:06.950  1015  3322 D SSRM:n  : SIOP:: AP = 330
,08-17 15:36:06.980  7574  7616 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 15:36:06.980  7574  7616 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4262ed1 
,08-17 15:36:06.980  7574  7616 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4262ed1 
,08-17 15:36:07.000  7574  7599 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 15:36:07.000  7574  7599 E bt-btif : Calling BTA_HhEnable
,08-17 15:36:07.000  7574  7599 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-17 15:36:07.000  7574  7599 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-17 15:36:07.010  7574  7599 E BluetoothServiceJni: populateRssiValuesNative
,08-17 15:36:07.010  7574  7599 I bluedroid: getModelRssiValues
08-17 15:36:07.010  7574  7599 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-17 15:36:07.010  7574  7599 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 15:36:07.010  1015  1015 D SettingsProvider: name = bluetooth_name
,08-17 15:36:07.010  7574  7599 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 15:36:07.020  7574  7599 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 15:36:07.020  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:07.020  7574  7599 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:36:07.020  7574  7599 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 15:36:07.020  7574  7599 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-17 15:36:07.020  7574  7599 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-17 15:36:07.020  7574  7599 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-17 15:36:07.020  7574  7599 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-17 15:36:07.020  7574  7599 E bt-btif : btif_sock_init: !vhci_init
,08-17 15:36:07.020  7574  7599 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-17 15:36:07.020  7574  7599 D IOP_DB_BT: db_open: db_open : handle 3027845136l, read 13894 bytes onto local cache
,08-17 15:36:07.020  7574  7599 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-17 15:36:07.030  7574  7599 D IOP_DB_BT: db_query: result 1
,08-17 15:36:07.030  7574  7599 I         : iop_db_open: iop_db_open status 0
,08-17 15:36:07.030  7574  7638 E bt_mct  : hci lib postload completed
,08-17 15:36:07.030  7574  7599 D bte_conf: Device ID record 1 : primary
,08-17 15:36:07.030  7574  7599 D bte_conf:   vendorId            = 0075
08-17 15:36:07.030  7574  7599 D bte_conf:   vendorIdSource      = 0001
,08-17 15:36:07.030  7574  7599 D bte_conf:   product             = 0100
08-17 15:36:07.030  7574  7599 D bte_conf:   version             = 0200
08-17 15:36:07.030  7574  7599 D bte_conf:   clientExecutableURL = 
08-17 15:36:07.030  7574  7599 D bte_conf:   serviceDescription  = 
08-17 15:36:07.030  7574  7599 D bte_conf:   documentationURL    = 
08-17 15:36:07.030  7574  7599 D bte_conf: bte_load_did_conf no section named DID2.
08-17 15:36:07.030  7574  7599 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 15:36:07.030  7574  7596 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-17 15:36:07.030  7574  7596 D BluetoothAdapterProperties: ScanMode =  20
,08-17 15:36:07.030  7574  7596 D BluetoothAdapterProperties: State =  11
,08-17 15:36:07.040  1015  1134 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 15:36:07.040  7574  7596 D BluetoothAdapterProperties: Setting state to 12
,08-17 15:36:07.040  7574  7596 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 15:36:07.040  7574  7599 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 15:36:07.040  7574  7599 D BluetoothAdapterProperties: Scan Mode:21
08-17 15:36:07.040  7574  7599 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 15:36:07.040  1015  1491 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-17 15:36:07.040  1015  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:07.040  1015  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:07.040  1015  1491 D SettingsProvider: selectionArgs: false
08-17 15:36:07.040  1015  1491 D SettingsProvider: selectionArgs: 1002
08-17 15:36:07.040  1015  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:07.040  1015  1491 D SettingsProvider: ret = -1
,08-17 15:36:07.040  7574  7596 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 15:36:07.040  7574  7596 D BluetoothAdapterService: updateAdapterState state is 12
,08-17 15:36:07.050  1015  1511 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:36:07.050  1015  1511 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.050  1015  1511 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:07.050  1015  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 15:36:07.050  1015  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.060  7574  7596 D BluetoothAdapterService: Autoconnection is available 
,08-17 15:36:07.060  7574  7596 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 15:36:07.060  7574  7596 D BluetoothAdapterService: starting service from this receiver
,08-17 15:36:07.060  6794  6806 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 15:36:07.060  6794  6806 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 15:36:07.060  1015  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 15:36:07.060  1015  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.060  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:07.060  1015  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 15:36:07.060  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.070  7574  7596 I BluetoothAdapterState: Entering On State from state = 11
,08-17 15:36:07.070  1464  1493 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:36:07.070  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 15:36:07.070  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 15:36:07.070  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:07.070  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:07.070  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:36:07.070  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:07.070  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:07.070  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:07.070  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:07.070  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:36:07.070  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:07.070  7574  7574 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-17 15:36:07.070  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 15:36:07.080  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:36:07.080  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.080  1464  1493 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 15:36:07.080  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:36:07.080  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 15:36:07.080  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 15:36:07.080  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 15:36:07.080  7574  7583 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:36:07.080  7574  7583 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 15:36:07.080  7574  7600 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:36:07.080  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:36:07.080  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:36:07.090  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 15:36:07.090  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.090  3269  3278 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:36:07.090  1015  1015 D BluetoothA2dp: Proxy object connected
,08-17 15:36:07.090  7574  7574 I BluetoothPbapService: Handler(): got msg=1
,08-17 15:36:07.090  1015  1490 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 15:36:07.090  3269  3278 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:36:07.090  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 15:36:07.090  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-17 15:36:07.100  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.100  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.100  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.100  3269  3269 D BluetoothA2dp: Proxy object connected
08-17 15:36:07.100  3269  3269 D A2dpProfile: Bluetooth service connected
,08-17 15:36:07.100  7574  7642 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-17 15:36:07.100  1435  1475 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:36:07.100  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 15:36:07.100  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 15:36:07.100  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.100  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.100  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.100  1435  1475 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 15:36:07.100  2038  2051 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 15:36:07.100  2038  2051 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:36:07.100  1435  7544 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:36:07.100  1435  7544 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:36:07.100  3269  3278 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 15:36:07.110  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-17 15:36:07.110  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.110  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.110  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.110  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.110  7574  7642 D BluetoothSocket: bindListen(): myUserId = 0
08-17 15:36:07.110  3269  3277 D BluetoothPan: Binding service...
,08-17 15:36:07.110  7574  7642 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:36:07.110  3269  3269 D BluetoothMap: Proxy object connected
,08-17 15:36:07.110  3269  3269 D MapProfile: Bluetooth service connected
08-17 15:36:07.110  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 15:36:07.110  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.110  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.110  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.110  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.110  3269  3269 D BluetoothMap: getConnectedDevices()
08-17 15:36:07.110  1464  1488 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:36:07.110  1464  1488 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:36:07.110  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:36:07.110  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:36:07.110  3269  3278 D Bluetoothsap: onBluetoothStateChange: up=true
08-17 15:36:07.110  3269  3278 D Bluetoothsap: Binding service...
08-17 15:36:07.110  7574  7642 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-17 15:36:07.110  7574  7642 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 15:36:07.110  7574  7642 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 15:36:07.110  7574  7642 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d11be98
08-17 15:36:07.110  7574  7642 D BluetoothSocket: channel: 19
08-17 15:36:07.110  7574  7642 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 15:36:07.110  3269  3278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 15:36:07.120  3269  3269 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:36:07.120  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-17 15:36:07.120  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.120  3269  3269 D PanProfile: Bluetooth service connected
08-17 15:36:07.120  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.120  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.120  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.120  3269  3278 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-17 15:36:07.120  1435  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:36:07.120  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 15:36:07.120  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 15:36:07.120  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.120  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.120  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.120  1435  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 15:36:07.120  1446  1471 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:36:07.120  1446  1471 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:36:07.120  1172  2341 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 15:36:07.120  1172  2341 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 15:36:07.130  3269  3269 D Bluetoothsap: BluetoothSAP Proxy object connected
08-17 15:36:07.130  3269  3269 D SapProfile: Bluetooth service connected
08-17 15:36:07.130  3269  3269 D Bluetoothsap: getConnectedDevices()
,08-17 15:36:07.130  3269  7541 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:36:07.130  3269  7541 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 15:36:07.130  7484  7493 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 15:36:07.130  7484  7493 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 15:36:07.130  1015  1045 D BluetoothPan: Binding service...
,08-17 15:36:07.130  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 15:36:07.130  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.130  3269  3278 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 15:36:07.130  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 15:36:07.130  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 15:36:07.130  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.130  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.130  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.130  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.130  1435  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:36:07.130  3269  3269 D BluetoothInputDevice: Proxy object connected
08-17 15:36:07.130  3269  3269 D HidProfile: Bluetooth service connected
08-17 15:36:07.130  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 15:36:07.130  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 15:36:07.130  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.130  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.130  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-17 15:36:07.130  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:07.130  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:07.130  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:36:07.130  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:07.130  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:07.130  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:07.130  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:07.130  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:36:07.130  1435  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 15:36:07.140  3269  7541 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 15:36:07.140  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-17 15:36:07.140  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.140  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:36:07.140  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.140  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.140  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.140  3269  3278 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 15:36:07.140  3269  3269 D BluetoothPbap: Proxy object connected
08-17 15:36:07.140  3269  3269 D PbapServerProfile: Bluetooth service connected
08-17 15:36:07.140  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:36:07.140  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@314b188 added. We now have 8 listener(s)
08-17 15:36:07.140  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 15:36:07.140  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 15:36:07.140  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:36:07.140  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.140  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.140  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-17 15:36:07.140  3269  3278 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 15:36:07.140  3269  3269 D HeadsetProfile: Bluetooth service connected
,08-17 15:36:07.140  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 15:36:07.140  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 15:36:07.150  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:07.150  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-17 15:36:07.150  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 15:36:07.150  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-17 15:36:07.150  1435  1435 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@cedb867, true
,08-17 15:36:07.150  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 15:36:07.150  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:07.150  1172  1172 D BluetoothTile:  getBluetoothState : 12
,08-17 15:36:07.150  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 15:36:07.150  1435  1435 D BluetoothHeadset: registerMessageListener
,08-17 15:36:07.160  1015  4287 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 15:36:07.160  1015  4287 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 15:36:07.160  1015  4287 D SecContentProvider2: mCursor = null
,08-17 15:36:07.160  1861  1861 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 15:36:07.160  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 15:36:07.160  1015  4287 D WifiService: setWifiEnabled: false pid=6794, uid=10171
08-17 15:36:07.160  1015  4287 D SettingsProvider: name = wifi_on
,08-17 15:36:07.160  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:07.160  1015  3782 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 15:36:07.160  1015  3781 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-17 15:36:07.160  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 15:36:07.170  7574  7643 D HeadsetService: registerMessageListener
08-17 15:36:07.170  1015  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 15:36:07.170  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.170  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:07.170  7574  7643 D HeadsetService: registerMessageListener
,08-17 15:36:07.170  7574  7605 D HeadsetStateMachine: Disconnected process message: 70
08-17 15:36:07.170  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.170  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:36:07.170  1015  1442 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 15:36:07.170  7574  7605 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2a30a6f1
08-17 15:36:07.170  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 15:36:07.170  1015  1442 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 15:36:07.170  1015  1442 D SecContentProvider2: mCursor = null
,08-17 15:36:07.170  1015  1442 D WifiService: setWifiEnabled: true pid=6794, uid=10171
08-17 15:36:07.170  1015  1442 W ActivityManager: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 15:36:07.170  1015  1442 W WifiService: Failed getting userId using ActivityManagerNative
08-17 15:36:07.170  1015  1442 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6794, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 15:36:07.170  1015  1442 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 15:36:07.170  1015  1442 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 15:36:07.170  1015  1442 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 15:36:07.170  1015  1442 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 15:36:07.170  1015  1442 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 15:36:07.170  1015  1442 D SettingsProvider: name = wifi_on
,08-17 15:36:07.170  3269  3269 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:07.170  1435  1435 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-17 15:36:07.170  7574  7646 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-17 15:36:07.170  1435  1435 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 15:36:07.170  1172  1755 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 15:36:07.180  1435  1435 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-17 15:36:07.180  1435  1435 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-17 15:36:07.180  1435  1435 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-17 15:36:07.180  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 15:36:07.180  7574  7646 D BluetoothSocket: bindListen(): myUserId = 0
08-17 15:36:07.180  7574  7646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:36:07.180  7574  7646 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-17 15:36:07.180  7574  7646 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 15:36:07.180  7574  7646 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 15:36:07.180  7574  7646 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18fab2d6
,08-17 15:36:07.180  7574  7646 D BluetoothSocket: channel: 5
,08-17 15:36:07.190  7574  7605 D HeadsetStateMachine: Disconnected process message: 9
,08-17 15:36:07.190  3269  3269 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-17 15:36:07.190  7574  7605 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-17 15:36:07.190  3269  3269 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 15:36:07.190  3269  3269 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 15:36:07.190  3269  3269 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-17 15:36:07.190   284   284 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-17 15:36:07.190   284   284 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 15:36:07.190   284   284 V voice   : voice_set_parameters: exit with code(-2)
08-17 15:36:07.190   284   284 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 15:36:07.190   284   284 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 15:36:07.190   284   284 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 15:36:07.190   284   284 V audio_hw_primary: adev_set_parameters: exit
,08-17 15:36:07.200  3269  3269 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:36:07.200  7574  7605 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-17 15:36:07.200  1015  1134 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 15:36:07.200  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.200  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.200  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.200  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 15:36:07.220  3269  3269 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:36:07.220  3269  3269 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 15:36:07.220  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:07.220  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 15:36:07.230  7574  7574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@256afbee
,08-17 15:36:07.230  7574  7574 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 15:36:07.230  1015  1511 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 15:36:07.230  1015  1511 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.230  1015  1511 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:07.230  1015  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.230  1015  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 15:36:07.250  2038  2038 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 15:36:07.250  1015  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 15:36:07.250  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 15:36:07.250  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:07.250  1015  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:36:07.250  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:36:07.260  1015  1501 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 15:36:07.270  2038  2038 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 15:36:07.270  2038  7657 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 15:36:07.270  1015  4287 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:36:07.270  7574  7658 D BluetoothSocket: bindListen(): myUserId = 0
08-17 15:36:07.270  7574  7658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
08-17 15:36:07.270  1015  4287 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.270  1015  4287 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:36:07.270  1015  4287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:36:07.280  7574  7658 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-17 15:36:07.280  7574  7658 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 15:36:07.280  7574  7658 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 15:36:07.280  7574  7658 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c72662
,08-17 15:36:07.280  7574  7658 D BluetoothSocket: channel: 12
08-17 15:36:07.280  7574  7658 I BtOppRfcommListener: Accept thread started.
,08-17 15:36:07.290  1015  3781 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 15:36:07.290  1015  3781 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:07.290  1015  3781 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:36:07.290  1015  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 15:36:07.300  2038  7657 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-17 15:36:07.520  1015  1043 D Tethering: interfaceAdded wlan0
,08-17 15:36:07.530  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:36:07.530  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-17 15:36:07.530  1015  1129 E Tethering: No numeric data
08-17 15:36:07.530  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 15:36:07.530  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:07.530  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 15:36:07.530  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 15:36:07.530  1172  1172 D HotspotTile: updateTetherState():false, false
08-17 15:36:07.530  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 15:36:07.530  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 15:36:07.530  1015  1129 D Tethering: clearTetheredNotification()
08-17 15:36:07.540  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:36:07.540  1015  1129 D Tethering: InitialState.processMessage what=4
08-17 15:36:07.540  1015  1043 D Tethering: interfaceAdded p2p0
08-17 15:36:07.540  1015  1121 V NetworkStats: performPollLocked() took 10ms
08-17 15:36:07.540  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:07.540  1015  1129 E Tethering: No numeric data
,08-17 15:36:07.550  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:07.550  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:07.550  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:36:07.550  1015  1129 D Tethering: clearTetheredNotification()
08-17 15:36:07.550  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
08-17 15:36:07.550   279   971 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-17 15:36:07.550   279   971 D SoftapController: Softap fwReload - Ok,
,08-17 15:36:07.550   279   971 D CommandListener: Setting iface cfg,
08-17 15:36:07.550   279   971 D CommandListener: Trying to bring down wlan0
,08-17 15:36:07.560   279   971 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:36:07.560  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 15:36:07.560  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 15:36:07.560  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 15:36:07.560  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-17 15:36:07.560  1172  1172 D HotspotTile: updateTetherState():false, false,
08-17 15:36:07.560  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:07.560  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 15:36:07.560  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 15:36:07.560  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 15:36:07.570  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
08-17 15:36:07.570  1015  1121 V NetworkStats: performPollLocked() took 6ms
08-17 15:36:07.570  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:07.570  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:07.570  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:07.570  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-17 15:36:07.580  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 15:36:07.580  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 15:36:07.580  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:07.580  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:07.580  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:07.580  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:07.590  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:36:07.590  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-17 15:36:07.590  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 15:36:07.590  3269  3269 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-17 15:36:07.590  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 15:36:07.590  1172  1172 D HotspotTile: onReceive : 2, 0
,08-17 15:36:07.600  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:07.600  1015  1216 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 15:36:07.600  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:36:07.600  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:07.600  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:07.600  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:36:07.600  1615  1615 I Hs20UtilService: Starting #19
,08-17 15:36:07.600  1615  1649 I Hs20UtilService: Message received 5011
,08-17 15:36:07.610  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 15:36:07.610  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 15:36:07.610  7015  7015 D SecurityLogAgent: StateMachine : Current State = 1
08-17 15:36:07.610  7015  7015 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 15:36:07.630  7666  7666 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-17 15:36:07.630  7666  7666 I wpa_supplicant: Successfully initialized wpa_supplicant
08-17 15:36:07.630  7666  7666 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 15:36:07.640  7666  7666 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-17 15:36:07.640   387   387 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7666
08-17 15:36:07.640   387   387 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 15:36:07.640  7666  7666 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 15:36:07.640  7666  7666 I wpa_supplicant: ssSupport state is = 1
08-17 15:36:07.640  7666  7666 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 15:36:07.640  7666  7666 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-17 15:36:07.650   387   387 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7666
08-17 15:36:07.650   387   387 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-17 15:36:07.780   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-17 15:36:07.780  7666  7666 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-17 15:36:07.830  7666  7666 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 15:36:07.830  7666  7666 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 15:36:07.840  7666  7666 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-17 15:36:07.840   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7666
,08-17 15:36:07.840   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-17 15:36:07.840  7666  7666 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 15:36:07.840  7666  7666 I wpa_supplicant: ssSupport state is = 1
08-17 15:36:07.840  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 15:36:07.840  7666  7666 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 15:36:07.840  7666  7666 E wpa_supplicant: SIM READ ERROR
,08-17 15:36:07.840  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 15:36:07.840  7666  7666 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 15:36:07.840  7666  7666 E wpa_supplicant: SIM READ ERROR
08-17 15:36:07.840  7666  7666 I wpa_supplicant: Blacklist: Clear (all) 
08-17 15:36:07.840  7666  7666 I wpa_supplicant: wpa_default_ap_write_once
08-17 15:36:07.840  7666  7666 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-17 15:36:07.840  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 15:36:07.840  7666  7666 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 15:36:07.840  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 15:36:07.840  7666  7666 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-17 15:36:07.840  7666  7666 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 15:36:07.850  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 15:36:07.850  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 15:36:07.850  1015  1043 D Tethering: interfaceStatusChanged wlan0, false,
,08-17 15:36:07.890  7666  7666 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-17 15:36:08.330  7666  7666 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 15:36:08.330  7666  7666 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-17 15:36:08.340  7666  7666 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-17 15:36:08.340   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7666
08-17 15:36:08.340   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-17 15:36:08.340  7666  7666 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 15:36:08.340  7666  7666 I wpa_supplicant: ssSupport state is = 1
08-17 15:36:08.340  7666  7666 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 15:36:08.340  7666  7666 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 15:36:08.360  7666  7666 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-17 15:36:08.360   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7666
08-17 15:36:08.360   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-17 15:36:08.360  7666  7666 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 15:36:08.360  7666  7666 I wpa_supplicant: ssSupport state is = 1
,08-17 15:36:08.360  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 15:36:08.360  7666  7666 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-17 15:36:08.360  7666  7666 E wpa_supplicant: SIM READ ERROR
,08-17 15:36:08.360  7666  7666 I wpa_supplicant: wpa_default_ap_write_once
08-17 15:36:08.360  7666  7666 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 15:36:08.360  7666  7666 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 15:36:08.360  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 15:36:08.370  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-17 15:36:08.370  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 15:36:08.370  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 15:36:08.370  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 15:36:08.370  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-17 15:36:08.450  7666  7666 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-17 15:36:08.450  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 15:36:08.530  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 15:36:08.530  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 15:36:08.530  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-17 15:36:08.660  7666  7666 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-17 15:36:08.660  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-17 15:36:08.660  7666  7666 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 15:36:08.670  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-17 15:36:08.670  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 15:36:08.670  7666  7666 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-17 15:36:08.670  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 15:36:08.670  7666  7666 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 15:36:08.670  7666  7666 E wpa_supplicant: SIM READ ERROR
08-17 15:36:08.670  7666  7666 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 15:36:08.690  7666  7666 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-17 15:36:08.700  7666  7666 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 15:36:08.700  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
,08-17 15:36:08.700  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:36:08.700  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:36:08.700  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:08.700  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:08.700  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:08.700  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:08.710  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 15:36:08.710  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-17 15:36:08.710  1172  1755 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 15:36:08.710  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-17 15:36:08.710  1172  1172 D HotspotTile: onReceive : 3, 0
,08-17 15:36:08.710  3269  3269 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-17 15:36:08.720  1015  1124 E WifiConfigStore: Not a HS20
,08-17 15:36:08.720  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 15:36:08.730  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:08.730  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:08.730  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:36:08.730  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:08.730  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:08.730  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:08.730  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:08.730  6794  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:08.730  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-17 15:36:08.730  1015  3782 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 15:36:08.730  1015  3782 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:36:08.730  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-17 15:36:08.730  7666  7666 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 15:36:08.730  7666  7666 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-17 15:36:08.730  7666  7666 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 15:36:08.730  7666  7666 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 15:36:08.730  7666  7666 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 15:36:08.730  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 15:36:08.730  7666  7666 I wpa_supplicant: First Scan Start
08-17 15:36:08.730  7666  7666 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 15:36:08.730  6794  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:08.730  1015  3782 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:08.730  1015  3782 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:08.730  1015  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:36:08.740  1615  1615 I Hs20UtilService: Starting #20
,08-17 15:36:08.740  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
,08-17 15:36:08.740  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 15:36:08.740  1015  1124 I WifiNative-HAL: startHal
08-17 15:36:08.740  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d57d88c
08-17 15:36:08.740  1015  1124 I WifiNative-HAL: Could not start hal
,08-17 15:36:08.740  6990  6990 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:36:08.740  1615  1649 I Hs20UtilService: Message received 5011
,08-17 15:36:08.740  1015  1124 E WifiNative-wlan0: do suspend true
,08-17 15:36:08.750  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-17 15:36:08.750  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 15:36:08.750  7015  7015 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 15:36:08.750  7015  7015 D SecurityLogAgent: StateMachine : Current State = 1
08-17 15:36:08.750  7015  7015 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 15:36:08.750  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-17 15:36:08.750  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-17 15:36:08.750   279   971 D CommandListener: Setting iface cfg
08-17 15:36:08.750   279   971 D CommandListener: Trying to bring up p2p0
08-17 15:36:08.760  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 15:36:08.760  1015  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:08.760  1015  1148 I WifiNative-HAL: startHal
08-17 15:36:08.760  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9ea3b9bc
08-17 15:36:08.760  1015  1123 D WifiP2pService: P2pEnablingState
08-17 15:36:08.760  1015  1148 I WifiNative-HAL: Could not start hal
08-17 15:36:08.760  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
08-17 15:36:08.760  1015  1148 E WifiScanningService: could not start HAL,
08-17 15:36:08.760  1015  1123 D WifiP2pService: P2p socket connection successful
08-17 15:36:08.760  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-17 15:36:08.760  1015  1123 D WifiP2pService: P2pEnabledState,
08-17 15:36:08.760  1015  1149 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:08.760  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 15:36:08.760  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 15:36:08.760  1015  1124 E WifiNative-wlan0: invaild command id : 215
,08-17 15:36:08.760  7666  7666 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 15:36:08.760  7666  7666 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 15:36:08.770  7666  7666 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-17 15:36:08.770  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,08-17 15:36:08.770  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 15:36:08.770  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 15:36:08.770  1015  1124 E WifiNative-wlan0: invaild command id : 215
08-17 15:36:08.770  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 15:36:08.770  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:36:08.770  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 15:36:08.770  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-17 15:36:08.770  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-17 15:36:08.770  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-17 15:36:08.770  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 15:36:08.770  1015  1046 D WifiDisplayController: disconnect
08-17 15:36:08.770  1015  1046 D WifiDisplayController: updateConnection
08-17 15:36:08.770  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 15:36:08.770  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 15:36:08.770  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 15:36:08.770  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:36:08.780  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 15:36:08.780  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-17 15:36:08.780  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 15:36:08.780  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 15:36:08.780  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
,08-17 15:36:08.780  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-17 15:36:08.780  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 15:36:08.780  1015  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 15:36:08.780  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 15:36:08.780  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
,08-17 15:36:08.780  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  secondary type: null
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  wps: 0
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  grpcapab: 0
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  devcapab: 0
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  status: 3
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  wfdInfo: null
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-17 15:36:08.780  1015  1046 D WifiDisplayController:  SConnectInfo : null
,08-17 15:36:08.780  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 15:36:08.790  3269  3269 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 15:36:08.790  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 15:36:08.790  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 15:36:08.790  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 15:36:08.790  3269  3269 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 15:36:08.790  3269  3802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 15:36:08.790  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 15:36:08.790  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 15:36:08.800  7353  7353 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 15:36:08.800  7368  7368 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 15:36:08.810  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-17 15:36:08.810  1015  1123 D WifiP2pService: InactiveState
,08-17 15:36:08.810  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-17 15:36:08.810  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 15:36:08.810  7666  7666 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 15:36:08.810  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-17 15:36:08.810  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 15:36:08.930   289   289 E SMD     : DCD OFF
,08-17 15:36:09.190  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:09.190  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:09.190  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:36:09.190  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:09.190  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:09.190  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:09.190  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:09.190  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:36:09.190  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-17 15:36:09.200  6794  6847 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 15:36:09.200  6794  6847 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 15:36:09.200  6794  6847 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@33043c9e Bundle[{}]
,08-17 15:36:09.200  6794  6847 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 15:36:09.200  6794  6847 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-17 15:36:09.200  6794  6847 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-17 15:36:09.210  6794  6847 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 15:36:09.210  6794  6847 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 15:36:09.210  6794  6847 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 15:36:09.210  6794  6847 I System.out: Running OutgoingSocketThread
,08-17 15:36:09.210  6794  7675 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1359)
,08-17 15:36:09.220  6794  7675 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47346
,08-17 15:36:09.220  6794  7675 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 15:36:09.870  7666  7666 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
08-17 15:36:09.870  7666  7666 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 15:36:09.870  7666  7666 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-17 15:36:09.870  7666  7666 I wpa_supplicant: Trying to associate with  'G700'
08-17 15:36:09.870  7666  7666 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-17 15:36:09.870  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-17 15:36:09.870  1015  7672 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-17 15:36:09.890  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 15:36:09.890  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:36:09.990  7666  7666 E wpa_supplicant: Cmd 35605 not handled
,08-17 15:36:09.990  7666  7666 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 15:36:09.990  7666  7666 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-17 15:36:09.990  7666  7666 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 15:36:09.990  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 15:36:09.990  7666  7666 I wpa_supplicant: Associated with F4.99.3E
08-17 15:36:09.990  7666  7666 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 15:36:09.990  7666  7666 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-17 15:36:09.990  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-17 15:36:09.990  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 15:36:09.990  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-17 15:36:09.990  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 15:36:09.990  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 15:36:09.990  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-17 15:36:09.990  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:36:09.990  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 15:36:10.000  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-17 15:36:10.000  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 15:36:10.000  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true,
08-17 15:36:10.000  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-17 15:36:10.000  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-17 15:36:10.000  7666  7666 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 15:36:10.000  7666  7666 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-17 15:36:10.000  1015  1129 E Tethering: No numeric data
08-17 15:36:10.000  7666  7666 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-17 15:36:10.000  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-17 15:36:10.000  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 15:36:10.000  1015  1129 D Tethering: clearTetheredNotification()
08-17 15:36:10.000  7666  7666 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:36:10.000  7666  7666 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-17 15:36:10.000  7666  7666 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-17 15:36:10.000  7666  7666 I wpa_supplicant: Blacklist: Clear (temp) 
08-17 15:36:10.000  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-17 15:36:10.010  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 15:36:10.010  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:36:10.010  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 15:36:10.010  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-17 15:36:10.010  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-17 15:36:10.010  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-17 15:36:10.010  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:36:10.010  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 15:36:10.010  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 15:36:10.010  1015  1121 V NetworkStats: performPollLocked() took 4ms
,08-17 15:36:10.010  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:36:10.020  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 15:36:10.020  1172  1172 D HotspotTile: updateTetherState():false, false
,08-17 15:36:10.020  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:10.020  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:36:10.020  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-17 15:36:10.030  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 15:36:10.030  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 15:36:10.030  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:36:10.030  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.030  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.030  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.030  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.030  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 15:36:10.030  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-17 15:36:10.030  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 15:36:10.030  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 15:36:10.030  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-17 15:36:10.030  1015  1465 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 15:36:10.030  1015  1465 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:36:10.040  1015  1465 W ActivityManager: userId = 0, bbcId = -10000,
08-17 15:36:10.040  1015  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:10.040  1015  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 15:36:10.040  1615  1615 I Hs20UtilService: Starting #21
,08-17 15:36:10.040  1615  1649 I Hs20UtilService: Message received 5007
,08-17 15:36:10.040  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,08-17 15:36:10.040  3269  3269 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 15:36:10.050  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:36:10.050  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 15:36:10.050  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 15:36:10.050  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-17 15:36:10.050  3269  3269 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 15:36:10.050  3269  3802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 15:36:10.060   279   971 D CommandListener: Setting iface cfg
,08-17 15:36:10.060  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 3
,08-17 15:36:10.060  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 15:36:10.060  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:36:10.070  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 15:36:10.070  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:36:10.080  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 15:36:10.080  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:36:10.080  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.080  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.080  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.080  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:10.080  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 15:36:10.080  1015  1124 D SecContentProvider2: mCursor = null
,08-17 15:36:10.090  1015  1124 E WifiNative-wlan0: do suspend false
,08-17 15:36:10.090  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-17 15:36:10.090  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 15:36:10.210  6794  6847 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1360),
08-17 15:36:10.210  6794  6847 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1360)
,08-17 15:36:10.220  6794  6847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1365)
,08-17 15:36:10.220  6794  6847 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-17 15:36:10.220  6794  6847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1366)
,08-17 15:36:10.220  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:36:10.230  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35173721 added. We now have 2 listener(s)
,08-17 15:36:10.230  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 15:36:10.230  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 15:36:10.230  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 15:36:10.230  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:36:10.230  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3234b746 added. We now have 9 listener(s)
08-17 15:36:10.230  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:36:10.230  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:36:10.240  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:36:10.240  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:36:10.240  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:10.240  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:36:10.240  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:10.240  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:10.240  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:10.240  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:10.240  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:36:10.240  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:36:10.250  6794  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:36:10.250  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:10.250  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:10.250  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:36:10.250  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28075e34 added. We now have 3 listener(s)
,08-17 15:36:10.250  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 15:36:10.250  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 15:36:10.260  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 15:36:10.260  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:10.260  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a0f245d added. We now have 10 listener(s)
,08-17 15:36:10.260  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:10.260  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:36:10.260  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,08-17 15:36:10.260  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:36:10.260  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:10.260  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.260  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:10.260  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 15:36:10.260  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35173721 removed from the list
08-17 15:36:10.260  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:10.260  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3234b746 removed from the list
08-17 15:36:10.260  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop,
08-17 15:36:10.260  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:10.260  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.260  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:10.260  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:10.260  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:36:10.260  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:10.260  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3234b746 not in the list
08-17 15:36:10.260  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.260  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:10.260  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:36:10.260  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:36:10.260  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:10.260  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a0f245d removed from the list
,08-17 15:36:10.260  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:36:10.260  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.270  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:10.270  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 15:36:10.270  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28075e34 removed from the list
,08-17 15:36:10.270  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:36:10.270  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@327501d2 added. We now have 2 listener(s)
,08-17 15:36:10.270  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 15:36:10.270  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 15:36:10.270  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 15:36:10.270  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:36:10.270  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ccbf2a3 added. We now have 9 listener(s)
,08-17 15:36:10.270  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:36:10.280  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:36:10.280  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:36:10.290  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:36:10.290  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:10.290  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:36:10.290  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:10.290  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:10.290  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:10.290  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:10.290  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:36:10.290  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:10.290  6794  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:36:10.290  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:10.290  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@249ea959 added. We now have 3 listener(s)
08-17 15:36:10.290  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:10.290  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:10.290  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 15:36:10.300  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-17 15:36:10.300  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:10.300  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-17 15:36:10.300  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fd691e added. We now have 10 listener(s)
08-17 15:36:10.300  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:10.300  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-17 15:36:10.300  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:36:10.300  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:36:10.300  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:36:10.300  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 15:36:10.300  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 15:36:10.310  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:36:10.310  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:36:10.310  7680  7680 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 15:36:10.320  7680  7680 I dhcpcd  : version 5.5.6 starting
,08-17 15:36:10.320  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 15:36:10.320  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:36:10.320  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-17 15:36:10.320  7680  7680 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-17 15:36:10.320  7574  7643 D BtGatt.GattService: registerClient() - UUID=b04a39e0-e3b3-4ab7-9067-015b8733f513
,08-17 15:36:10.360  7574  7599 D BtGatt.GattService: onClientRegistered() - UUID=b04a39e0-e3b3-4ab7-9067-015b8733f513, clientIf=6
,08-17 15:36:10.370  6794  6802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-17 15:36:10.370  7574  7582 D BtGatt.GattService: start scan with filters
,08-17 15:36:10.370  7680  7680 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-17 15:36:10.370  7680  7680 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 15:36:10.370  7680  7680 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-17 15:36:10.370  7680  7680 I dhcpcd  : bssid match
08-17 15:36:10.370  7680  7680 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
08-17 15:36:10.370  7574  7604 D BtGatt.ScanManager: handling starting scan
08-17 15:36:10.370  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 15:36:10.370  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 15:36:10.370  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:36:10.370  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:36:10.370  7574  7604 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@256afbee
08-17 15:36:10.370  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:36:10.370  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 15:36:10.370  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:36:10.370  7574  7599 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 15:36:10.370  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.380  7574  7604 D BtGatt.ScanManager: allow scan with filters
,08-17 15:36:10.380  7574  7604 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 15:36:10.380  7574  7604 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-17 15:36:10.380  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-17 15:36:10.380  7574  7599 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 15:36:10.380  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:36:10.380  7574  7604 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 15:36:10.380  7574  7604 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-17 15:36:10.380  7574  7599 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 15:36:10.380  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.380  6794  6847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 15:36:10.380  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:36:10.390  7574  7599 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 15:36:10.390  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.390  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:36:10.390  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.390  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:36:10.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:36:10.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 15:36:10.390  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:36:10.390  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:36:10.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:36:10.390  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:36:10.390  7574  7645 D BtGatt.GattService: stopScan() - queue size =1
,08-17 15:36:10.390  7574  7604 D BtGatt.ScanManager: filter size is 1
,08-17 15:36:10.390  7574  7604 D BtGatt.ScanManager: delete FilterIndex - 3
,08-17 15:36:10.400  7574  7600 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-17 15:36:10.400  7574  7599 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 15:36:10.400  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-17 15:36:10.400  7574  7604 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:36:10.400  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:36:10.400  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:36:10.400  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 15:36:10.400  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:36:10.400  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:36:10.400  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:36:10.400  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:36:10.400  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:36:10.400  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 15:36:10.400  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:10.400  7574  7599 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 15:36:10.400  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:36:10.400  7574  7604 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 15:36:10.400  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:36:10.400  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:36:10.400  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:36:10.410  7574  7599 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 15:36:10.410  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.410  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:36:10.410  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:36:10.410  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:36:10.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:10.410  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.410  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:10.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:10.410  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@327501d2 removed from the list
08-17 15:36:10.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:10.410  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ccbf2a3 removed from the list
08-17 15:36:10.410  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:36:10.410  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:10.410  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.410  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:10.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-17 15:36:10.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:10.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:10.410  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ccbf2a3 not in the list
08-17 15:36:10.410  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.410  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:10.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:36:10.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:10.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:10.410  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fd691e removed from the list
08-17 15:36:10.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:10.410  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.410  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:10.410  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:10.410  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@249ea959 removed from the list
08-17 15:36:10.410  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:10.410  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b12f92a added. We now have 2 listener(s)
,08-17 15:36:10.410  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 15:36:10.420  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:10.420  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:10.420  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:36:10.420  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f7b131b added. We now have 9 listener(s)
08-17 15:36:10.420  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:10.420  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:36:10.420  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:36:10.420  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:36:10.420  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:10.420  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:36:10.420  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:10.420  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:10.420  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:10.420  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:10.420  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:36:10.450  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:36:10.450  6794  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:36:10.450  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:10.450  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23eb2a91 added. We now have 3 listener(s)
,08-17 15:36:10.450  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:10.450  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:10.450  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 15:36:10.450  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:10.450  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:10.450  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:36:10.450  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f3f7df6 added. We now have 10 listener(s)
08-17 15:36:10.450  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:10.450  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:36:10.450  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 15:36:10.450  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:36:10.450  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 15:36:10.450  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-17 15:36:10.450  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 15:36:10.460  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 15:36:10.460  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:36:10.460  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:36:10.480  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 15:36:10.480  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:36:10.480  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 15:36:10.480  7680  7680 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-17 15:36:10.480  7574  7600 D BtGatt.GattService: registerClient() - UUID=65c8ca2b-ecc9-4811-a20b-85c8a575a52b
,08-17 15:36:10.490  1015  3781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 15:36:10.490  1015  3781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 15:36:10.490  1015  3781 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 15:36:10.490  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 15:36:10.490  1015  3781 D BatteryService: stay LED for fully charged
,08-17 15:36:10.500  1015  1015 I MotionRecognitionService: Plugged
,08-17 15:36:10.500  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 15:36:10.500  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 15:36:10.500  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 15:36:10.500  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 15:36:10.500  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 15:36:10.510  7574  7574 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 15:36:10.520  7574  7605 D HeadsetStateMachine: Disconnected process message: 10
,08-17 15:36:10.520  7574  7599 D BtGatt.GattService: onClientRegistered() - UUID=65c8ca2b-ecc9-4811-a20b-85c8a575a52b, clientIf=6
,08-17 15:36:10.520  6794  6802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 15:36:10.520  7574  7582 D BtGatt.GattService: start scan with filters
,08-17 15:36:10.520  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 15:36:10.520  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 15:36:10.520  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 15:36:10.530  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:36:10.530  7574  7604 D BtGatt.ScanManager: handling starting scan
08-17 15:36:10.530  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 15:36:10.530  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 15:36:10.530  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 15:36:10.530  7574  7599 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 15:36:10.530  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.530  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:36:10.530  7574  7604 D BtGatt.ScanManager: allow scan with filters
,08-17 15:36:10.530  7574  7604 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 15:36:10.530  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 15:36:10.530  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:36:10.530  7574  7604 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-17 15:36:10.540  7680  7680 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
08-17 15:36:10.540  7574  7599 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 15:36:10.540  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:36:10.540  7574  7604 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:36:10.540  7574  7604 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-17 15:36:10.540  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:36:10.540  7574  7599 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 15:36:10.540  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.540  7574  7599 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 15:36:10.540  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.550  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:36:10.550  6794  6847 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 15:36:10.550  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:36:10.550  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-17 15:36:10.550  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:36:10.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:10.560  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:36:10.560  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:36:10.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:10.560  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b12f92a removed from the list
08-17 15:36:10.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:10.560  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f7b131b removed from the list
08-17 15:36:10.560  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:36:10.560  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:10.560  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.560  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 15:36:10.560  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.560  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:10.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:10.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:10.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:10.560  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f7b131b not in the list
,08-17 15:36:10.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:36:10.560  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:36:10.560  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:36:10.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:36:10.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:36:10.560  7574  7600 D BtGatt.GattService: stopScan() - queue size =1,
08-17 15:36:10.560  7574  7582 D BtGatt.GattService: unregisterClient() - clientIf=6
08-17 15:36:10.560  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 15:36:10.560  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:36:10.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 15:36:10.560  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:36:10.560  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:36:10.560  7574  7604 D BtGatt.ScanManager: filter size is 1
08-17 15:36:10.560  7574  7604 D BtGatt.ScanManager: delete FilterIndex - 4
,08-17 15:36:10.570  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:36:10.570  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:36:10.570  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:36:10.570  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:36:10.570  7574  7599 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 15:36:10.570  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:36:10.570  7574  7604 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:36:10.570  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:10.570  7574  7599 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 15:36:10.570  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.570  7574  7604 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 15:36:10.570  7574  7599 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 15:36:10.570  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:36:10.570  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:10.570  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:10.570  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:10.570  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f3f7df6 removed from the list
08-17 15:36:10.570  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:10.570  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.570  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:10.570  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:10.570  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23eb2a91 removed from the list
,08-17 15:36:10.570  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:10.570  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20dd8382 added. We now have 2 listener(s)
08-17 15:36:10.570  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:36:10.570  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:36:10.570  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:36:10.580  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 15:36:10.580  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:10.580  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:10.580  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:10.580  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34eeca93 added. We now have 9 listener(s)
08-17 15:36:10.580  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:10.580  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:36:10.590  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:36:10.600  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-17 15:36:10.600  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:10.600  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:36:10.600  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:10.600  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:10.600  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:10.600  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
08-17 15:36:10.600  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:10.600  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:10.600  6794  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:36:10.610  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-17 15:36:10.610  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6af9ac9 added. We now have 3 listener(s)
,08-17 15:36:10.610  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-17 15:36:10.610  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:10.610  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:10.610  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-17 15:36:10.610  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a6455ce added. We now have 10 listener(s)
08-17 15:36:10.610  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:10.610  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-17 15:36:10.610  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:36:10.610  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:36:10.610  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-17 15:36:10.610  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:36:10.610  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:10.610  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:10.630  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-17 15:36:10.640  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:36:10.640  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:36:10.650  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-17 15:36:10.650  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 15:36:10.650  6794  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 15:36:10.660  7574  7643 D BtGatt.GattService: registerClient() - UUID=eec441a7-6306-4997-9461-8584c43a7271
,08-17 15:36:10.710  7574  7599 D BtGatt.GattService: onClientRegistered() - UUID=eec441a7-6306-4997-9461-8584c43a7271, clientIf=6
08-17 15:36:10.710  6794  6806 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-17 15:36:10.710  7574  7583 D BtGatt.GattService: start scan with filters,
08-17 15:36:10.710  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-17 15:36:10.710  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-17 15:36:10.710  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:36:10.710  7574  7604 D BtGatt.ScanManager: handling starting scan
08-17 15:36:10.710  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:36:10.710  7574  7599 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 15:36:10.710  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.710  7574  7604 D BtGatt.ScanManager: allow scan with filters
08-17 15:36:10.710  7574  7604 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
08-17 15:36:10.710  7574  7604 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-17 15:36:10.710  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-17 15:36:10.710  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:36:10.710  7574  7599 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 15:36:10.710  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:36:10.720  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 15:36:10.720  7574  7604 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:36:10.720  7574  7604 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 15:36:10.720  7574  7599 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-17 15:36:10.720  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.720  7574  7599 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 15:36:10.720  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.720  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:36:10.730  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 15:36:10.730  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:36:10.730  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:36:10.730  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:10.730  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.730  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:36:10.730  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-17 15:36:10.730  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20dd8382 removed from the list
08-17 15:36:10.730  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:10.730  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34eeca93 removed from the list,
08-17 15:36:10.730  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:36:10.730  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:10.730  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
,08-17 15:36:10.730  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 15:36:10.730  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:36:10.730  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:36:10.740  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:10.740  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:10.740  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-17 15:36:10.740  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34eeca93 not in the list
,08-17 15:36:10.740  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:36:10.740  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:36:10.740  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 15:36:10.740  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:36:10.740  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:36:10.740  7574  7600 D BtGatt.GattService: stopScan() - queue size =1
,08-17 15:36:10.740  7574  7582 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 15:36:10.740  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:36:10.740  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:36:10.740  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 15:36:10.740  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:36:10.740  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:36:10.740  7574  7604 D BtGatt.ScanManager: filter size is 1
08-17 15:36:10.740  7574  7604 D BtGatt.ScanManager: delete FilterIndex - 5
,08-17 15:36:10.740  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:36:10.740  7574  7599 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 15:36:10.740  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 15:36:10.750  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:36:10.750  6794  6847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 15:36:10.750  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:36:10.750  7574  7604 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:36:10.750  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:10.750  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:36:10.750  6794  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:36:10.750  6794  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:36:10.750  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:10.750  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:10.750  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:36:10.750  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a6455ce removed from the list
08-17 15:36:10.750  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:10.750  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.750  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:10.750  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:10.750  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6af9ac9 removed from the list
08-17 15:36:10.750  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:36:10.750  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247400da added. We now have 2 listener(s)
,08-17 15:36:10.750  7574  7599 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 15:36:10.750  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:36:10.750  7574  7604 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,08-17 15:36:10.750  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-17 15:36:10.750  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:10.750  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 15:36:10.750  7574  7599 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 15:36:10.750  7574  7599 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 15:36:10.750  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:10.750  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2042f90b added. We now have 9 listener(s)
,08-17 15:36:10.750  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:10.750  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:36:10.760  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:36:10.760  6794  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:36:10.760  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:10.760  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:36:10.760  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:10.760  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:10.760  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:10.760  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:10.760  6794  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:36:10.760  6794  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:36:10.760  6794  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:36:10.760  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:10.760  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:10.760  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@81ada01 added. We now have 3 listener(s)
,08-17 15:36:10.770  6794  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:10.770  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 15:36:10.770  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:10.770  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:10.770  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:10.770  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fa150a6 added. We now have 10 listener(s)
08-17 15:36:10.770  6794  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:36:10.770  6794  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:36:10.770  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:36:10.770  6794  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:36:10.770  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:10.770  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.770  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:10.770  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 15:36:10.770  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247400da removed from the list
08-17 15:36:10.770  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:10.770  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2042f90b removed from the list
08-17 15:36:10.770  6794  6847 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:36:10.770  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:10.770  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.770  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:10.770  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:36:10.770  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:10.770  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:36:10.770  6794  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2042f90b not in the list
08-17 15:36:10.770  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:36:10.770  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:10.770  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:36:10.770  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:10.770  6794  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:36:10.780  6794  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fa150a6 removed from the list
08-17 15:36:10.780  6794  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:10.780  6794  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:10.780  6794  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-17 15:36:10.780  6794  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:10.780  6794  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@81ada01 removed from the list
,08-17 15:36:10.780  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-17 15:36:10.780  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 15:36:10.780  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-17 15:36:10.780  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:36:10.780  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 15:36:10.780  6794  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:36:10.790  6794  7711 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1373, name: My test thread name)
,08-17 15:36:10.790  6794  7711 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1373, thread name: My test thread name)
,08-17 15:36:10.790  6794  7711 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1373, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 15:36:10.790  6794  7712 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1375, name: My test thread name)
,08-17 15:36:10.790  6794  7712 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1375, thread name: My test thread name)
,08-17 15:36:10.790  6794  7712 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1375, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 15:36:10.790  6794  6847 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-17 15:36:10.790  6794  6847 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 15:36:10.790  6794  6847 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 15:36:10.790  6794  6847 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 15:36:10.790  6794  6847 D com.test.thalitest.ThaliTestRunner: Total duration: 23431 ms
,08-17 15:36:10.800  6794  6847 I jxcore-log: Total number of executed tests:  80
08-17 15:36:10.800  6794  6847 I jxcore-log: 
,08-17 15:36:10.800  6794  6847 I jxcore-log: Number of passed tests:  80
08-17 15:36:10.800  6794  6847 I jxcore-log: 
,08-17 15:36:10.800  6794  6847 I jxcore-log: Number of failed tests:  0
08-17 15:36:10.800  6794  6847 I jxcore-log: 
,08-17 15:36:10.800  6794  6847 I jxcore-log: Number of ignored tests:  0
08-17 15:36:10.800  6794  6847 I jxcore-log: 
,08-17 15:36:10.800  6794  6847 I jxcore-log: Total duration:  23431
08-17 15:36:10.800  6794  6847 I jxcore-log: 
08-17 15:36:10.800  6794  6847 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 15:36:10.800  6794  6847 I jxcore-log: 
08-17 15:36:10.800  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:10.800  6794  6847 I jxcore-log: 
,08-17 15:36:10.810  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:10.810  6794  6847 I jxcore-log: 
08-17 15:36:10.810  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:10.810  6794  6847 I jxcore-log: 
08-17 15:36:10.810  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:10.810  6794  6847 I jxcore-log: 
08-17 15:36:10.810  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:10.810  6794  6847 I jxcore-log: 
08-17 15:36:10.810  6794  6794 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 15:36:10.810  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:10.810  6794  6847 I jxcore-log: 
08-17 15:36:10.820  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:10.820  6794  6847 I jxcore-log: 
08-17 15:36:10.820  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:10.820  6794  6847 I jxcore-log: 
08-17 15:36:10.820  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:36:10.820  6794  6847 I jxcore-log: 
08-17 15:36:10.820  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:36:10.820  6794  6847 I jxcore-log: 
08-17 15:36:10.820  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:36:10.820  6794  6847 I jxcore-log: 
08-17 15:36:10.820  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:36:10.820  6794  6847 I jxcore-log: 
08-17 15:36:10.820  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:36:10.820  6794  6847 I jxcore-log: 
08-17 15:36:10.820  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:36:10.820  6794  6847 I jxcore-log: 
08-17 15:36:10.820  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:36:10.820  6794  6847 I jxcore-log: 
08-17 15:36:10.820  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:36:10.820  6794  6847 I jxcore-log: 
08-17 15:36:10.820  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:36:10.820  6794  6847 I jxcore-log: 
08-17 15:36:10.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:36:10.830  6794  6847 I jxcore-log: 
08-17 15:36:10.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:36:10.830  6794  6847 I jxcore-log: 
08-17 15:36:10.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:36:10.830  6794  6847 I jxcore-log: 
08-17 15:36:10.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:36:10.830  6794  6847 I jxcore-log: 
08-17 15:36:10.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:36:10.830  6794  6847 I jxcore-log: 
08-17 15:36:10.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:36:10.830  6794  6847 I jxcore-log: 
08-17 15:36:10.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:36:10.830  6794  6847 I jxcore-log: 
08-17 15:36:10.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:36:10.830  6794  6847 I jxcore-log: 
08-17 15:36:10.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:36:10.830  6794  6847 I jxcore-log: 
08-17 15:36:10.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:36:10.830  6794  6847 I jxcore-log: 
08-17 15:36:10.830  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:36:10.830  6794  6847 I jxcore-log: 
,08-17 15:36:10.900  6794  6794 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:36:10.910  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:36:10.910  6794  6847 I jxcore-log: 
,08-17 15:36:10.910  1015  1124 E WifiNative-wlan0: do suspend true
,08-17 15:36:10.940  1015  1123 D WifiP2pService: InactiveState{ what=143375 },
08-17 15:36:10.940  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 15:36:10.940  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 15:36:10.940  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:36:10.940  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:10.940  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:10.940  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.940  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.940  1015  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 15:36:10.940  1015  1124 E WifiStateMachine: VerifyingLinkState enter
08-17 15:36:10.950  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 15:36:10.950  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-17 15:36:10.950  1015  1126 D ConnectivityService: Adding iface wlan0 to network 504
,08-17 15:36:10.960  1015  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-17 15:36:10.960  1015  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 15:36:10.960  1015  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 15:36:10.960  1015  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 15:36:10.960  1015  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 15:36:10.970  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:36:10.970  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:36:10.970  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.970  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.970  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:10.970  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:10.970  1015  1442 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 15:36:10.970  1015  1442 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 15:36:10.970  1015  1442 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:10.970  1015  1442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:10.970  1015  1442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:36:10.970  1015  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-17 15:36:10.970  1615  1615 I Hs20UtilService: Starting #22
,08-17 15:36:10.980  1615  1649 I Hs20UtilService: Message received 5007,
,08-17 15:36:10.990  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 15:36:10.990  3269  3269 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-17 15:36:11.000  1015  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-17 15:36:11.000  1015  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-17 15:36:11.000  1015  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-17 15:36:11.000  1015  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 15:36:11.000  1015  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-17 15:36:11.000  1015  1126 D ConnectivityService: LTETest block dns file not exists
08-17 15:36:11.000  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.000  1015  1126 V NetworkStats: updateIfacesLocked()
08-17 15:36:11.000  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 15:36:11.000  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 15:36:11.000  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 15:36:11.000  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 15:36:11.000  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 15:36:11.010  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.010  1015  1126 V NetworkStats: performPollLocked() took 8ms
,08-17 15:36:11.020  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 15:36:11.030  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:36:11.030  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 15:36:11.030  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:11.030  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:11.030  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:11.030  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:11.030  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 15:36:11.030  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-17 15:36:11.030  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-17 15:36:11.030  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 15:36:11.030  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-17 15:36:11.040  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:11.040  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:11.040  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:11.040  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:11.040  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 15:36:11.040  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-17 15:36:11.040  1015  1126 E ConnectivityService: updateNetworkInfo()
08-17 15:36:11.040  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:36:11.040  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.040  1015  1441 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 15:36:11.040  1015  1441 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 15:36:11.040  1015  1126 V NetworkStats: updateIfacesLocked()
08-17 15:36:11.040  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-17 15:36:11.040  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 15:36:11.040  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 15:36:11.040  1015  1441 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:11.040  1015  1441 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:11.040  1015  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 15:36:11.050  1615  1615 I Hs20UtilService: Starting #23
08-17 15:36:11.050  1015  1126 V NetworkStats: performPollLocked() took 6ms
08-17 15:36:11.050  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.050  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.050  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.050  1615  1649 I Hs20UtilService: Message received 5007
,08-17 15:36:11.050  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 15:36:11.050  3269  3269 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 15:36:11.050  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 15:36:11.050  1015  7676 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:11.050  1015  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-17 15:36:11.050  1015  7676 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-17 15:36:11.050  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 15:36:11.050  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.050  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.050  1015  7676 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:11.050  1015  7676 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-17 15:36:11.060  1015  7676 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 15:36:11.060  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 15:36:11.060  3269  3269 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 15:36:11.060  3269  3269 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 15:36:11.060  3269  3802 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 15:36:11.060   279   967 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 15:36:11.060   279   967 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-17 15:36:11.060  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 15:36:11.060  1015  1126 D ConnectivityService:    accepting network in place of null
08-17 15:36:11.060  1464  1464 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 15:36:11.060  1464  1464 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:11.060  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-17 15:36:11.060  1015  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 15:36:11.060  1015  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-17 15:36:11.060  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-17 15:36:11.070  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-17 15:36:11.070  1015  1129 D Tethering: MasterInitialState.processMessage what=3
08-17 15:36:11.070  1015  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-17 15:36:11.070  1015  1121 V NetworkStats: updateIfacesLocked()
08-17 15:36:11.070  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.070  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-17 15:36:11.070  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 15:36:11.070  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 15:36:11.070  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-17 15:36:11.070  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
08-17 15:36:11.070  1015  1501 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 15:36:11.070  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 15:36:11.070  1015  1501 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 15:36:11.070  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 15:36:11.070  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-17 15:36:11.070  1172  1172 D StatusBar.NetworkController: updateDataNetType()
08-17 15:36:11.070  1015  1121 V NetworkStats: performPollLocked() took 5ms
08-17 15:36:11.070  1172  1172 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 15:36:11.070  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-17 15:36:11.070  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.070  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.070  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.070  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.070  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-17 15:36:11.070  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.070  1172  1722 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 15:36:11.070  1015  1501 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:11.070  1015  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:11.070  1015  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 15:36:11.070  4773  6849 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 15:36:11.080  6794  6794 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 15:36:11.080  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:36:11.080  6794  6847 I jxcore-log: 
,08-17 15:36:11.080  1615  1615 I Hs20UtilService: Starting #24
08-17 15:36:11.080  1615  1649 I Hs20UtilService: Message received 5007
,08-17 15:36:11.080  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.080  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.080  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 15:36:11.080  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-17 15:36:11.080  3269  3269 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 15:36:11.080  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 15:36:11.080  3269  3269 I NearbySettings: MountReceiver.onReceive - Keep current state
08-17 15:36:11.080  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:36:11.080  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 15:36:11.080  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:11.080  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:11.080  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:11.080  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:11.090  1015  1491 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-17 15:36:11.090  1015  1027 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-17 15:36:11.090  1015  1027 D SecContentProvider2: mCursor = null
08-17 15:36:11.090  1015  1134 D SecContentProvider2: uri = 15 selection = getToastGravity,
08-17 15:36:11.090  1015  1134 D SecContentProvider2: mCursor = null
08-17 15:36:11.090  1015  1501 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-17 15:36:11.090  1015  1501 D SecContentProvider2: mCursor = null
08-17 15:36:11.090  1015  1441 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-17 15:36:11.090  1015  1441 D SecContentProvider2: mCursor = null
,08-17 15:36:11.100  1015  3782 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-17 15:36:11.100  1015  3782 D SecContentProvider2: mCursor = null
08-17 15:36:11.100  1015  1442 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
08-17 15:36:11.100  1015  1442 D SecContentProvider2: mCursor = null
,08-17 15:36:11.130   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-17 15:36:11.130  1015  1491 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,08-17 15:36:11.140  1172  1172 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 15:36:11.140  7713  7713 D AndroidRuntime: 
08-17 15:36:11.140  7713  7713 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-17 15:36:11.140  7713  7713 D AndroidRuntime: CheckJNI is OFF
,08-17 15:36:11.140  7713  7713 D AndroidRuntime: readGMSProperty: start
08-17 15:36:11.140  7713  7713 D AndroidRuntime: readGMSProperty: already setted!!
08-17 15:36:11.140  7713  7713 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 15:36:11.140  7713  7713 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 15:36:11.140  7713  7713 D AndroidRuntime: readGMSProperty: end
08-17 15:36:11.140  7713  7713 D AndroidRuntime: addProductProperty: start
,08-17 15:36:11.150  1015  7676 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 15:36:11.220  1015  7676 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 13:36:11 GMT], X-Android-Received-Millis=[1471440971225], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471440971198]}
08-17 15:36:11.220  1015  7676 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 15:36:11.220  1015  7676 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-17 15:36:11.220  1015  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-17 15:36:11.220  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 15:36:11.220  1015  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-17 15:36:11.220  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-17 15:36:11.220  1172  1722 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 15:36:11.220  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 15:36:11.220  4773  6849 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 15:36:11.250  6794  6794 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:36:11.250  6794  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:36:11.250  6794  6847 I jxcore-log: 
,08-17 15:36:11.290  7713  7713 E AffinityControl: AffinityControl: registerfunction enter
,08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
,08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: updateDataNetType()
08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 15:36:11.300  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 15:36:11.300  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:11.300  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 15:36:11.320  7713  7713 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 15:36:11.330  1015  3781 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-17 15:36:11.330  1015  3781 D PackageManager: START PACKAGE DELETE: observer{602776541}
08-17 15:36:11.330  1015  3781 D PackageManager: pkg{<packageName>}
08-17 15:36:11.330  1015  3781 D PackageManager: user{0}
08-17 15:36:11.330  1015  3781 D PackageManager: caller{2000}
08-17 15:36:11.330  1015  3781 D PackageManager: flags{2}
08-17 15:36:11.330  1015  3781 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-17 15:36:11.330  1015  3781 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-17 15:36:11.330  1015  3781 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-17 15:36:11.330  1015  3781 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-17 15:36:11.340  1015  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-17 15:36:11.340  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-17 15:36:11.340  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-17 15:36:11.340  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-17 15:36:11.340  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-17 15:36:11.340  1015  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-17 15:36:11.340  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-17 15:36:11.340  1015  1041 I ActivityManager: Killing 6794:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-17 15:36:11.350  1015  1041 I ActivityManager:   Force finishing activity ActivityRecord{36f2d8bb u0 com.test.thalitest/.MainActivity t3}
,08-17 15:36:11.360  1015  1041 D InputDispatcher: Focus left window: 6794
,08-17 15:36:11.360   259  1037 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-17 15:36:11.360   259   436 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-17 15:36:11.360  1015  1041 D InputDispatcher: Focused application released
08-17 15:36:11.360  1015  1041 D FocusedStackFrame: Set to : 0
08-17 15:36:11.360  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 15:36:11.360  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 15:36:11.370  1015  1041 W ActivityManager: mDVFSHelper.acquire()
,08-17 15:36:11.430  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 15:36:11.430  1015  1126 V NetworkStats: updateIfacesLocked()
,08-17 15:36:11.430  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 15:36:11.430  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:36:11.430  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 15:36:11.430  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 15:36:11.440  1015  1126 V NetworkStats: performPollLocked() took 6ms
,08-17 15:36:11.440  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:36:11.450  1015  1056 W PackageSettings: Skipping PackageSetting{20eb5379 com.example.hello/10168} due to missing metadata
,08-17 15:36:11.490  1015  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-17 15:36:11.500  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 15:36:11.500  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 15:36:11.500  4773  6849 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 15:36:11.500  1172  1722 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-17 15:36:11.510  1172  1722 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 15:36:11.510  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.510  4773  6849 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-17 15:36:11.510  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:36:11.510  1015  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-17 15:36:11.520  1495  1495 D Launcher: onRestart, Launcher: 283547420
,08-17 15:36:11.530  1015  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-17 15:36:11.560  2648  2648 I art     : Explicit concurrent mark sweep GC freed 19576(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 805us total 33.608ms
,08-17 15:36:11.570  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:11.580  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 15:36:11.580  1861  1861 E SamsungIME: mOCRHelper is null
,08-17 15:36:11.610  4773  4773 I art     : Explicit concurrent mark sweep GC freed 24200(1456KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 12MB/21MB, paused 1.344ms total 90.282ms
,08-17 15:36:11.620  1446  1446 D PersonaManager: isKioskContainerExistOnDevice
,08-17 15:36:11.620  2897  2897 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 15:36:11 GMT+02:00 2016
,08-17 15:36:11.630  1495  1495 D Launcher: onStart, Launcher: 283547420
08-17 15:36:11.630  1495  1495 D Launcher.HomeView: onStart
,08-17 15:36:11.640  1446  1446 D RegisteredServicesCache: empty dynamic service
,08-17 15:36:11.640  1495  1495 D Launcher: onResume, Launcher: 283547420
,08-17 15:36:11.640  1015  1216 D SettingsProvider: name = kids_home_mode
08-17 15:36:11.640  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 15:36:11.640  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 15:36:11.640  1015  1216 D SettingsProvider: selectionArgs: false
08-17 15:36:11.640  1015  1216 D SettingsProvider: selectionArgs: 10006
08-17 15:36:11.640  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 15:36:11.640  1015  1216 D SettingsProvider: ret = -1
,08-17 15:36:11.640  1495  1495 D Launcher.HomeView: onResume
,08-17 15:36:11.650  1015  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-17 15:36:11.650  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.650  1015  1121 V NetworkStats: performPollLocked(flags=0x3)
,08-17 15:36:11.650  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 15:36:11.650  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 15:36:11.650  1015  1121 V NetworkStats: performPollLocked() took 6ms
08-17 15:36:11.650  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:36:11.690  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 15:36:11.690  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 15:36:11.690  1446  1446 D RegisteredComponentCache: Collect Tech packages for Knox
,08-17 15:36:11.690  1446  1446 D PersonaManager: isKioskContainerExistOnDevice
,08-17 15:36:11.730  1015  1015 I art     : Explicit concurrent mark sweep GC freed 81843(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 24MB/37MB, paused 7.406ms total 204.165ms
,08-17 15:36:11.730  1015  1501 I art     : WaitForGcToComplete blocked for 154.679ms for cause Explicit
,08-17 15:36:11.780  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-17 15:36:11.780  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-17 15:36:11.780  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-17 15:36:11.780  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-17 15:36:11.780  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-17 15:36:11.790  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-17 15:36:11.790  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-17 15:36:11.850  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-17 15:36:11.850  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-17 15:36:11.850  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest,
08-17 15:36:11.850  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 15:36:11.850  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 15:36:11.860  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 15:36:11.860  1015  3322 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-17 15:36:11.860  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null,
08-17 15:36:11.860  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 15:36:11.860  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-17 15:36:11.860  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-17 15:36:11.860  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-17 15:36:11.860  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=3_task.xml
,08-17 15:36:11.870  1015  1041 W ActivityManager: mDVFSHelper.release()
,08-17 15:36:11.890  1015  1501 I art     : Explicit concurrent mark sweep GC freed 12194(1014KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 2.890ms total 162.235ms
,08-17 15:36:11.890  1015  1056 I art     : WaitForGcToComplete blocked for 260.213ms for cause Explicit
,08-17 15:36:11.900  1015  1511 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-17 15:36:11.900  1015  1511 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-17 15:36:11.900  1015  3782 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-17 15:36:11.900  1015  3782 D SecContentProvider2: mCursor = null
,08-17 15:36:11.900  1015  1511 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:11.900  2038  2209 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 15:36:11.900  1015  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:11.900  1015  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 15:36:11.900  1495  1495 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-17 15:36:11.920  1495  1495 D MenuAppsGridFragment: onResume
,08-17 15:36:11.920  1495  1495 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-17 15:36:11.930  2897  2897 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-17 15:36:11.930  1495  1495 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-17 15:36:11.930  1015  3782 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-17 15:36:11.930  1015  3782 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-17 15:36:11.930  1015  3782 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-17 15:36:11.930  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:11.930  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:11.930  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:11.930  1015  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:11.930   289   289 E SMD     : DCD OFF
,08-17 15:36:11.940  2897  2897 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-17 15:36:11.940  1015  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-17 15:36:11.940  1015  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-17 15:36:11.940  1015  1040 W TextServicesManagerService: no available spell checker services found
,08-17 15:36:11.950  7732  7732 E Zygote  : MountEmulatedStorage(),
08-17 15:36:11.950  7732  7732 E Zygote  : v2
08-17 15:36:11.950  7732  7732 I libpersona: KNOX_SDCARD checking this for 10090,
08-17 15:36:11.950  7732  7732 I libpersona: KNOX_SDCARD not a persona
,08-17 15:36:11.950  7732  7732 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:36:11.950  7732  7732 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 15:36:11.950  7732  7732 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 15:36:11.950  1015  3782 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7732 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-17 15:36:11.960  2897  2897 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 15:36:11.960  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-17 15:36:11.960  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:11.960  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:11.960  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:11.960  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 15:36:11.960  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:11.970  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 15:36:11.980  2897  2897 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 15:36:11.980  1015  3782 I TactileAssist: enable value -1
08-17 15:36:11.980  1015  3782 I TactileAssist: internal enable value -1
08-17 15:36:11.980  1015  3782 I TactileAssist: intensity value -1
08-17 15:36:11.980  1015  3782 I TactileAssist: saveAppList value true
,08-17 15:36:11.980  7747  7747 E Zygote  : MountEmulatedStorage(),
08-17 15:36:11.980  7747  7747 E Zygote  : v2
08-17 15:36:11.980  7747  7747 I libpersona: KNOX_SDCARD checking this for 1000
08-17 15:36:11.980  7747  7747 I libpersona: KNOX_SDCARD not a persona
,08-17 15:36:11.980  7747  7747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:36:11.980  1015  3782 I TactileAssist: List of disabled apps :,
08-17 15:36:11.980  1015  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7747 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 15:36:11.990  7747  7747 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:36:11.990  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-17 15:36:11.990  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:11.990  7747  7747 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 15:36:11.990  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:11.990  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:11.990  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:11.990  7732  7732 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:11.990  2897  7731 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-17 15:36:11.990  7732  7732 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:11.990  2897  7731 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-17 15:36:12.000  2897  7731 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-17 15:36:12.000  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 15:36:12.000  2897  7731 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-17 15:36:12.000  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 15:36:12.010  1015  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7760 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 15:36:12.010  1015  1041 W ActivityManager: Activity pause timeout for ActivityRecord{1fe527cc u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1}
,08-17 15:36:12.020  7760  7760 E Zygote  : MountEmulatedStorage()
08-17 15:36:12.020  7760  7760 I libpersona: KNOX_SDCARD checking this for 1000
08-17 15:36:12.020  7760  7760 E Zygote  : v2
08-17 15:36:12.020  7760  7760 I libpersona: KNOX_SDCARD not a persona
08-17 15:36:12.020  7760  7760 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 15:36:12.030  7760  7760 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:36:12.030  1015  1027 D ActivityManager: handle home activity for 0
08-17 15:36:12.030  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!,
08-17 15:36:12.030  1015  1027 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-17 15:36:12.030  1015  1027 D KnoxTimeoutHandler: post home show event for user 0
08-17 15:36:12.030  1015  1027 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-17 15:36:12.030  1015  1027 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 15:36:12.030  1015  1027 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-17 15:36:12.030  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-17 15:36:12.030  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,08-17 15:36:12.030  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-17 15:36:12.030  1495  1495 D Launcher.HomeView: onPause
08-17 15:36:12.030  1495  1495 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-17 15:36:12.030  7760  7760 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:36:12.040  7747  7747 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 15:36:12.040  7747  7747 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:12.040  1495  1495 I Choreographer: Skipped 30 frames!  The application may be doing too much work on its main thread.
,08-17 15:36:12.060   259   259 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-17 15:36:12.060  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-17 15:36:12.070  7760  7760 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:12.070  7760  7760 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:12.080  1015  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-17 15:36:12.090  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-17 15:36:12.090  1015  1501 D InputDispatcher: Focus entered window: 1495
,08-17 15:36:12.090  1015  1511 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-17 15:36:12.100  1495  1495 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 15:36:12.100  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-17 15:36:12.100  1015  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.100  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 15:36:12.100  1015  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.100  1015  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.100  1015  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:12.110  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{394a5198 token=android.os.BinderProxy@9a331d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-17 15:36:12.110  1495  1495 D Launcher.HomeView: onStop
,08-17 15:36:12.120  1015  1490 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-17 15:36:12.120  2897  7731 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-17 15:36:12.120  1015  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-17 15:36:12.130  1015  7778 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 15:36:12.130  7779  7779 E Zygote  : MountEmulatedStorage(),
08-17 15:36:12.130  7779  7779 I libpersona: KNOX_SDCARD checking this for 10048
08-17 15:36:12.130  7779  7779 E Zygote  : v2
08-17 15:36:12.130  7779  7779 I libpersona: KNOX_SDCARD not a persona
08-17 15:36:12.130  7779  7779 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:36:12.130  7779  7779 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:36:12.130  1015  1511 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7779 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-17 15:36:12.130  7779  7779 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 15:36:12.140  1015  1490 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6794 uid 10171
,08-17 15:36:12.140  1172  1172 I StatusBar: Icon Only
,08-17 15:36:12.140  1172  1172 D PanelView: There is/are notification(s) 
,08-17 15:36:12.140  1861  1861 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-17 15:36:12.150  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 15:36:12.150  7747  7747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-17 15:36:12.160  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 15:36:12.160  1015  1511 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-17 15:36:12.160  1015  1511 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-17 15:36:12.160  7760  7760 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-17 15:36:12.160  1015  1056 I art     : Explicit concurrent mark sweep GC freed 7214(491KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 17.075ms total 265.166ms
,08-17 15:36:12.160  1015  1511 W ActivityManager: userId = 0, bbcId = -10000
,08-17 15:36:12.160  2897  7731 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-17 15:36:12.160  7732  7732 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-17 15:36:12.160  1015  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 15:36:12.170  7732  7732 D elm:15121: ELMEngine.ELMEngine( context ).
,08-17 15:36:12.170  1015  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
08-17 15:36:12.170  7732  7732 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-17 15:36:12.170  2897  7731 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-17 15:36:12.170  7779  7779 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:12.180  7779  7779 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:12.180  1015  1441 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-17 15:36:12.180  1015  1441 D SecContentProvider2: mCursor = null
,08-17 15:36:12.180  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-17 15:36:12.180  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.180  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.180  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.180  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:12.200  7796  7796 E Zygote  : MountEmulatedStorage()
08-17 15:36:12.200  7796  7796 I libpersona: KNOX_SDCARD checking this for 1000
08-17 15:36:12.200  7796  7796 E Zygote  : v2
08-17 15:36:12.200  7796  7796 I libpersona: KNOX_SDCARD not a persona
08-17 15:36:12.200  7796  7796 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:36:12.200  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 15:36:12.210  1015  1028 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7796 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 15:36:12.210  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:12.210  1015  1216 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-17 15:36:12.210  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:12.210  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-17 15:36:12.210  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-17 15:36:12.210  7796  7796 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:36:12.210  7796  7796 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:36:12.240  7796  7796 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:12.240  7796  7796 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:12.240  7732  7732 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-17 15:36:12.240  7732  7732 D elm:15121: ElmAgentService : onCreate()
,08-17 15:36:12.250  7732  7812 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-17 15:36:12.250  7732  7812 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-17 15:36:12.250  7732  7812 D elm:15121: MDMBridge.getInstance()
08-17 15:36:12.250  7732  7812 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-17 15:36:12.250  1015  1501 D SecContentProvider2: uri = -1 selection = getSealedState
08-17 15:36:12.250  1015  1501 D SecContentProvider2: mCursor = null
,08-17 15:36:12.250  7760  7760 I PopupuiReceiver_KNOX: getSealedState : true
,08-17 15:36:12.250  1015  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 15:36:12.250  1015  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:36:12.250  1015  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 15:36:12.250  2897  2897 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-17 15:36:12.250  1015  1465 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-17 15:36:12.250  1015  1465 D SecContentProvider2: mCursor = null
,08-17 15:36:12.250  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 15:36:12.250  7760  7760 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-17 15:36:12.250  1015  1442 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
,08-17 15:36:12.260  1015  1442 D SecContentProvider2: mCursor = null
,08-17 15:36:12.260  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1fe527cc u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:158234
,08-17 15:36:12.260  1015  1056 D PackageManager: delete codoeFile: 
,08-17 15:36:12.270  7760  7760 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-17 15:36:12.270  7760  7760 D PopupuiReceiver: Action package removed
,08-17 15:36:12.270  7732  7812 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-17 15:36:12.270  1015  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-17 15:36:12.270  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-17 15:36:12.270  1015  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-17 15:36:12.270  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.270  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.270  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.270  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.270  1015  1056 D PackageManager: result of delete: 1{602776541}
,08-17 15:36:12.280  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-17 15:36:12.280  7796  7796 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 15:36:12.280  7713  7713 D AndroidRuntime: Shutting down VM
08-17 15:36:12.290  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 15:36:12.290  7779  7779 D Compatibility: onReceive() it will make start service
08-17 15:36:12.290  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 15:36:12.290  7814  7814 E Zygote  : MountEmulatedStorage()
08-17 15:36:12.290  7814  7814 I libpersona: KNOX_SDCARD checking this for 1000
08-17 15:36:12.290  7814  7814 E Zygote  : v2
08-17 15:36:12.290  7814  7814 I libpersona: KNOX_SDCARD not a persona
08-17 15:36:12.290  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-17 15:36:12.290  7814  7814 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 15:36:12.290  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 15:36:12.300  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7814 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 15:36:12.300  7814  7814 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:36:12.300  7814  7814 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:36:12.300  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 15:36:12.300  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 15:36:12.300  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 15:36:12.310  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 15:36:12.310  1015  1028 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-17 15:36:12.310  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-17 15:36:12.310  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:12.310  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 15:36:12.310  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:12.310  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-17 15:36:12.310  7732  7732 D elm:15121: ElmAgentService : onDestroy().
,08-17 15:36:12.320  1015  7802 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-17 15:36:12.320  7796  7796 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-17 15:36:12.320  1015  7802 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.320  1015  7802 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.320  1015  7802 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.320  1015  7802 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:12.320  7779  7825 D Compatibility: onHandleIntent()
,08-17 15:36:12.320  7779  7825 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-17 15:36:12.330  7779  7825 D Compatibility: found: 2
,08-17 15:36:12.330  1015  1442 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-17 15:36:12.330  1015  1442 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-17 15:36:12.330  7814  7814 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:12.330  7814  7814 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:12.330  7831  7831 E Zygote  : MountEmulatedStorage()
08-17 15:36:12.330  7831  7831 E Zygote  : v2
08-17 15:36:12.330  7831  7831 I libpersona: KNOX_SDCARD checking this for 10145
08-17 15:36:12.330  7831  7831 I libpersona: KNOX_SDCARD not a persona
08-17 15:36:12.330  7831  7831 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:36:12.340  7779  7825 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-17 15:36:12.340  7831  7831 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:36:12.340  7831  7831 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 15:36:12.340  1015  7802 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7831 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 15:36:12.340  7779  7825 D Compatibility: skipping ResolveInfo{1216ed97 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-17 15:36:12.340  7779  7825 D Compatibility: considering ResolveInfo{9f15b84 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-17 15:36:12.340  1015  7802 I ActivityManager: Killing 7096:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-17 15:36:12.340  7779  7825 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-17 15:36:12.340  7779  7825 D Compatibility: enabling receiver ResolveInfo{11be5f6d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-17 15:36:12.340  1015  1216 I ActivityManager: Killing 7159:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-17 15:36:12.350  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-17 15:36:12.350  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.350  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.350  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.350  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:12.350  7779  7825 D Compatibility: enabling receiver ResolveInfo{a7007a2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-17 15:36:12.360  7845  7845 E Zygote  : MountEmulatedStorage()
08-17 15:36:12.360  7845  7845 I libpersona: KNOX_SDCARD checking this for 10052
08-17 15:36:12.360  7845  7845 E Zygote  : v2
08-17 15:36:12.360  7845  7845 I libpersona: KNOX_SDCARD not a persona
08-17 15:36:12.360  7845  7845 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:36:12.370  7845  7845 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:36:12.370  7779  7825 D Compatibility: enabling receiver ResolveInfo{1d52cc33 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-17 15:36:12.370  1015  1216 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7845 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-17 15:36:12.370  7845  7845 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 15:36:12.380  7831  7831 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:12.380  7831  7831 D ActivityThread: Added TimaKeyStore provider
08-17 15:36:12.380  7779  7825 D Compatibility: enabling receiver ResolveInfo{18eaabf0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-17 15:36:12.380  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-17 15:36:12.380  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.380  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.380  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.380  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:12.380  1015  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-17 15:36:12.390  1015  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-17 15:36:12.390  7779  7825 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-17 15:36:12.390  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:12.400  7858  7858 E Zygote  : MountEmulatedStorage()
08-17 15:36:12.400  7858  7858 E Zygote  : v2
08-17 15:36:12.400  7858  7858 I libpersona: KNOX_SDCARD checking this for 10087
08-17 15:36:12.400  7858  7858 I libpersona: KNOX_SDCARD not a persona
,08-17 15:36:12.400  7858  7858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:36:12.400  7858  7858 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 15:36:12.400  1015  1134 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7858 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-17 15:36:12.400  7858  7858 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 15:36:12.400  7814  7814 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-17 15:36:12.400  1015  1134 I ActivityManager: Killing 7127:com.sec.spp.push/u0a32 (adj 15): empty #21
08-17 15:36:12.400  7814  7814 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-17 15:36:12.400  7814  7814 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-17 15:36:12.420  1015  4287 I ActivityManager: Killing 7176:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-17 15:36:12.420  7845  7845 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:12.420  7845  7845 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:12.430  7858  7858 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:12.430  7814  7814 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-17 15:36:12.430  7814  7814 I PCWCLIENTTRACE_PushUtil: sales region : global
08-17 15:36:12.430  7858  7858 D ActivityThread: Added TimaKeyStore provider
08-17 15:36:12.430  7814  7814 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 15:36:12.430  7814  7814 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-17 15:36:12.440  1015  1465 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-17 15:36:12.440  1015  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.440  1015  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.440  1015  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.440  1015  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:12.450  7876  7876 E Zygote  : MountEmulatedStorage()
,08-17 15:36:12.450  7876  7876 I libpersona: KNOX_SDCARD checking this for 10029
08-17 15:36:12.450  7876  7876 E Zygote  : v2
08-17 15:36:12.450  7876  7876 I libpersona: KNOX_SDCARD not a persona
08-17 15:36:12.450  7876  7876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:36:12.460  7876  7876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 15:36:12.460  1015  1465 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7876 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-17 15:36:12.460  7876  7876 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 15:36:12.460  1015  1465 I ActivityManager: Killing 7111:com.android.chrome/u0a77 (adj 15): empty #21
,08-17 15:36:12.460  7831  7831 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-17 15:36:12.460  7831  7831 D ThemeInfoUtil: isCurrentFestival = false
,08-17 15:36:12.470  1015  1511 D PersonaManager: isKioskContainerExistOnDevice
,08-17 15:36:12.480  1015  4287 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-17 15:36:12.480  1015  4287 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.480  1015  4287 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.480  1015  4287 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.480  1015  4287 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:12.490  7876  7876 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-17 15:36:12.490  7876  7876 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:12.500  7891  7891 E Zygote  : MountEmulatedStorage(),
08-17 15:36:12.500  7891  7891 E Zygote  : v2
08-17 15:36:12.500  7891  7891 I libpersona: KNOX_SDCARD checking this for 10148,
08-17 15:36:12.500  7891  7891 I libpersona: KNOX_SDCARD not a persona
,08-17 15:36:12.500  7891  7891 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-17 15:36:12.500  7713  7713 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-17 15:36:12.510  1015  4287 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7891 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,08-17 15:36:12.510  1015  4287 I ActivityManager: Killing 6990:com.google.android.talk/u0a102 (adj 15): empty #21
,08-17 15:36:12.510  7891  7891 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:36:12.510  7891  7891 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:36:12.530   308   308 I art     : Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 27.286ms
,08-17 15:36:12.530  1015  3781 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-17 15:36:12.530  1015  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-17 15:36:12.530  1015  1056 D PackageManager: userId{-1}
08-17 15:36:12.530  1015  1056 D PackageManager: andCode{true}
,08-17 15:36:12.550   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 17.653ms
08-17 15:36:12.550  1015  4287 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-17 15:36:12.550  1015  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-17 15:36:12.560  7891  7891 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:12.560  7891  7891 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:12.560  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.560  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.560  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.560  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:12.570   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 17.833ms
,08-17 15:36:12.580  7907  7907 E Zygote  : MountEmulatedStorage()
,08-17 15:36:12.590  7907  7907 E Zygote  : v2
08-17 15:36:12.590  7907  7907 I libpersona: KNOX_SDCARD checking this for 10003
,08-17 15:36:12.590  7907  7907 I libpersona: KNOX_SDCARD not a persona
,08-17 15:36:12.590  7907  7907 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:36:12.590  1015  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7907 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-17 15:36:12.590  7907  7907 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:36:12.590  7907  7907 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:36:12.600  1015  1442 I ActivityManager: Killing 7207:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
08-17 15:36:12.600  1015  1134 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,08-17 15:36:12.610  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-17 15:36:12.610  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0,
,08-17 15:36:12.610  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:12.610  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:36:12.610  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-17 15:36:12.620  7876  7918 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-17 15:36:12.620  1015  1441 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-17 15:36:12.620  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.620  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.620  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.620  1015  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:12.620  7907  7907 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:12.620  7907  7907 D ActivityThread: Added TimaKeyStore provider,
,08-17 15:36:12.640  7925  7925 E Zygote  : MountEmulatedStorage()
08-17 15:36:12.640  7925  7925 E Zygote  : v2,
08-17 15:36:12.640  7891  7891 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
08-17 15:36:12.640  1015  1441 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7925 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 15:36:12.640  1015  1441 I ActivityManager: Killing 7241:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-17 15:36:12.640  7925  7925 I libpersona: KNOX_SDCARD checking this for 10032
08-17 15:36:12.640  1015  1465 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-17 15:36:12.640  1015  1465 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-17 15:36:12.640  7925  7925 I libpersona: KNOX_SDCARD not a persona
,08-17 15:36:12.650  1015  1465 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:12.650  1015  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 15:36:12.650  1015  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-17 15:36:12.650  7925  7925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 15:36:12.650  7925  7925 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:36:12.650  7925  7925 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-17 15:36:12.670  7876  7918 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-17 15:36:12.670  7876  7918 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:36:12.670  7876  7918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 15:36:12.670  7876  7918 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-17 15:36:12.670  7876  7918 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-17 15:36:12.670  1015  1491 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-17 15:36:12.670  1015  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
08-17 15:36:12.670  1015  1491 W ActivityManager: userId = 0, bbcId = -10000
08-17 15:36:12.670  1015  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 15:36:12.670  1015  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-17 15:36:12.680  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-17 15:36:12.680  7459  7459 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
08-17 15:36:12.680  7876  7918 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-17 15:36:12.680  7876  7918 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-17 15:36:12.680  7876  7918 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 15:36:12.680  7876  7918 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:36:12.680  7876  7918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 15:36:12.680  7876  7918 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 15:36:12.680  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.680  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.680  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 15:36:12.680  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 15:36:12.710  7459  7459 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850,
08-17 15:36:12.710  7459  7459 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM place_privacy WHERE package_name = ?] disk I/O error
,08-17 15:36:12.710  7941  7941 E Zygote  : MountEmulatedStorage()
08-17 15:36:12.710  7941  7941 E Zygote  : v2
08-17 15:36:12.710  7941  7941 I libpersona: KNOX_SDCARD checking this for 10152
08-17 15:36:12.710  7941  7941 I libpersona: KNOX_SDCARD not a persona
,08-17 15:36:12.710  7941  7941 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-17 15:36:12.720  7459  7459 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/predictor.db" with flag (131138) and mode_t (0) due to error (30),
08-17 15:36:12.720  1015  1027 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7941 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-17 15:36:12.730  7876  7918 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-17 15:36:12.730  7876  7918 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:36:12.730  7876  7918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 15:36:12.740  7941  7941 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 15:36:12.740  7941  7941 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 15:36:12.750  7925  7925 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 15:36:12.750  7925  7925 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:12.760  7459  7459 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/predictor.db'.
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:65)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:36:12.760  7459  7459 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:36:12.760  7459  7459 D AndroidRuntime: Shutting down VM
08-17 15:36:12.760  7459  7459 E AndroidRuntime: FATAL EXCEPTION: main
08-17 15:36:12.760  7459  7459 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 7459
08-17 15:36:12.760  7459  7459 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at ,android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:65)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:36:12.760  7459  7459 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:36:12.760  1495  1495 I Choreographer: Skipped 36 frames!  The application may be doing too much work on its main thread.
08-17 15:36:12.770  1495  1495 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9a331d time:158742
,08-17 15:36:12.770  7941  7941 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 15:36:12.780  7941  7941 D ActivityThread: Added TimaKeyStore provider
,08-17 15:36:12.780  7876  7918 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-17 15:36:12.780  7876  7918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 15:36:12.780  7876  7918 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-17 15:36:12.790  1015  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
,08-17 15:36:12.790  7417  7417 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
,08-17 15:36:12.800  7417  7417 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.android.sm/databases/history.db'.
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:36:12.800  7417  7417 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-17 15:36:12.800  7417  7417 D AndroidRuntime: Shutting down VM
,08-17 15:36:12.800  7417  7417 E AndroidRuntime: FATAL EXCEPTION: main
08-17 15:36:12.800  7417  7417 E AndroidRuntime: Process: com.samsung.android.sm, PID: 7417
08-17 15:36:12.800  7417  7417 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125),
08-17 15:36:12.800  7417  7417 E AndroidRuntime: 	... 9 more
,08-17 15:36:12.810  7459  7459 I Process : Sending signal. PID: 7459 SIG: 9

```
