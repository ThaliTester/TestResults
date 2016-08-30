#### Test 83268893a5a5a53_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
08-30 15:44:25.250   288   288 E SMD     : DCD OFF
,08-30 15:44:25.880  6604  6604 D AndroidRuntime: 
08-30 15:44:25.880  6604  6604 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 15:44:25.890  6604  6604 D AndroidRuntime: CheckJNI is OFF
08-30 15:44:25.890  6604  6604 D AndroidRuntime: readGMSProperty: start
08-30 15:44:25.890  6604  6604 D AndroidRuntime: readGMSProperty: already setted!!
08-30 15:44:25.890  6604  6604 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 15:44:25.890  6604  6604 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 15:44:25.890  6604  6604 D AndroidRuntime: readGMSProperty: end
08-30 15:44:25.890  6604  6604 D AndroidRuntime: addProductProperty: start
08-30 15:44:26.010  6604  6604 E AffinityControl: AffinityControl: registerfunction enter
08-30 15:44:26.040  6604  6604 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 15:44:26.050  1015  1477 E PersonaManagerService: inState():  stateMachine is null !!
08-30 15:44:26.050  1015  1477 I PersonaManagerService: PersonaId don't exist
08-30 15:44:26.050  1015  1477 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-30 15:44:26.050  1015  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-30 15:44:26.070  1015  1477 W ActivityManager: mDVFSHelper.acquire()
08-30 15:44:26.070   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-30 15:44:26.070   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-30 15:44:26.080  1015  1477 D FocusedStackFrame: Set to : 0
08-30 15:44:26.090  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 15:44:26.090  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-30 15:44:26.090  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:26.090  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:26.090  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:26.090  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:26.100  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 15:44:26.100  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 15:44:26.100  6615  6615 E Zygote  : MountEmulatedStorage()
08-30 15:44:26.100  6615  6615 E Zygote  : v2
08-30 15:44:26.100  6615  6615 I libpersona: KNOX_SDCARD checking this for 10171
08-30 15:44:26.100  6615  6615 I libpersona: KNOX_SDCARD not a persona
08-30 15:44:26.110  6615  6615 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 15:44:26.110  1015  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-30 15:44:26.110  1015  1477 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6615 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 15:44:26.110  1015  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 15:44:26.110  1015  1477 D InputDispatcher: Focused application set to: xxxx
08-30 15:44:26.110  1015  1477 D InputDispatcher: Focus left window: 1481
08-30 15:44:26.110   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-30 15:44:26.110  6604  6604 D AndroidRuntime: Shutting down VM
08-30 15:44:26.120  6615  6615 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 15:44:26.120  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 15:44:26.120  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 15:44:26.120  6615  6615 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-30 15:44:26.130  6615  6615 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 15:44:26.140  6615  6615 D ActivityThread: Added TimaKeyStore provider
08-30 15:44:26.140  1015  1480 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-30 15:44:26.150  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 15:44:26.150  1015  1015 V ActivityManager: Display changed displayId=0
08-30 15:44:26.160  1015  1480 D PersonaManager: isKioskContainerExistOnDevice
08-30 15:44:26.170  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-30 15:44:26.200   258  1095 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-30 15:44:26.200   258   440 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-30 15:44:26.210  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{b5fc488 token=android.os.BinderProxy@2d5ef611 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-30 15:44:26.210  1481  1481 D Launcher: onTrimMemory. Level: 20
08-30 15:44:26.270  6615  6615 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-30 15:44:26.290  6615  6615 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5192-5194)
08-30 15:44:26.290  6615  6615 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-30 15:44:26.310  6615  6615 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a04d29d}
08-30 15:44:26.310  6615  6615 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-30 15:44:26.310  6615  6615 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 15:44:26.320  6604  6604 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 15:44:26.340  6615  6615 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-30 15:44:26.340  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:44:26.350  6615  6615 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 15:44:26.360  6615  6615 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 15:44:26.360  6615  6615 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 15:44:26.360  6615  6615 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 15:44:26.360  6615  6615 I Adreno-EGL: Local Branch: 
08-30 15:44:26.360  6615  6615 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 15:44:26.360  6615  6615 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 15:44:26.360  6615  6615 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 15:44:26.420  6615  6615 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 15:44:26.440  6615  6615 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-30 15:44:26.440  6615  6615 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-30 15:44:26.450  6615  6615 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-30 15:44:26.450  6615  6615 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-30 15:44:26.560  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:44:26.570  6615  6615 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 15:44:26.580  6615  6615 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-30 15:44:26.580  6615  6615 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-30 15:44:26.580  6615  6615 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung,
,08-30 15:44:26.590  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:44:26.590  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:44:26.630  6615  6654 D OpenGLRenderer: Render dirty regions requested: true
,08-30 15:44:26.630  1015  1479 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 15:44:26.630  1015  1479 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 15:44:26.630  1015  1479 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 15:44:26.630  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 15:44:26.630  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 15:44:26.640  6615  6642 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-30 15:44:26.650  6615  6615 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 15:44:26.650  6615  6615 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-30 15:44:26.660   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-30 15:44:26.670  1015  1462 D InputDispatcher: Focus entered window: 6615
,08-30 15:44:26.680  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 15:44:26.680  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 15:44:26.680  6615  6615 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 15:44:26.680  6615  6654 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 15:44:26.680  6615  6654 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-30 15:44:26.680  6615  6654 D OpenGLRenderer: Enabling debug mode 0
,08-30 15:44:26.700  6615  6615 V ActivityThread: updateVisibility : ActivityRecord{23e62272 token=android.os.BinderProxy@9c70de6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
,08-30 15:44:26.770  1015  1479 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 15:44:26.780  1175  1175 I StatusBar: Icon Only
,08-30 15:44:26.780  1175  1175 D PanelView: There is/are notification(s) 
,08-30 15:44:26.780  1015  6659 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 15:44:26.790  6615  6615 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-30 15:44:26.790  6615  6615 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9c70de6 time:105694
,08-30 15:44:26.790  1015  1045 I ActivityManager: Displayed Component not be shown by security: +625ms (total +703ms)
,08-30 15:44:26.790  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{25fabded u0 com.test.thalitest/.MainActivity t2} time:105699
08-30 15:44:26.790  1015  1045 W ActivityManager: mDVFSHelper.release()
,08-30 15:44:26.800   258   442 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-30 15:44:26.800   258   442 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-30 15:44:26.820  1794  1794 I SamsungIME: getCurrentCandidateView
,08-30 15:44:26.900  6615  6615 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6615
,08-30 15:44:26.920  1794  1794 D SamsungIME: Dismiss ExpandCandiate
,08-30 15:44:27.070  1794  1794 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 15:44:27.090  6615  6615 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 15:44:27.110  1794  1794 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 15:44:27.130  1794  1794 I SamsungIME: KeybaordView init() : load resources
,08-30 15:44:27.150  1794  1794 I SamsungIME: getCurrentKeyboard
,08-30 15:44:27.150  1794  1794 I SamsungIME: getTextKeyboard
,08-30 15:44:27.170  1794  1794 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 15:44:27.180  6615  6661 D jxcore_app_log: JniHelper::setJavaVM(0xb89392b0), pthread_self() = -1192421104
,08-30 15:44:27.190  6615  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 15:44:27.190  6615  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 15:44:27.190  6615  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 15:44:27.190  6615  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 15:44:27.190  6615  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 15:44:27.190  6615  6661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f631b3b added. We now have 1 listener(s)
,08-30 15:44:27.190  6615  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-30 15:44:27.190  6615  6661 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-30 15:44:27.190  6615  6661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 15:44:27.190  6615  6661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 15:44:27.200  6615  6661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be4bc96 added. We now have 1 listener(s)
08-30 15:44:27.200  6615  6661 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:44:27.210  6615  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:44:27.210  6615  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 15:44:27.210  6615  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 15:44:27.210  6615  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 15:44:27.210  6615  6661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 15:44:27.210  6615  6661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:44:27.220  6615  6661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-30 15:44:27.220  6615  6661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 15:44:27.220  6615  6661 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:27.220  6615  6661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:27.220  6615  6661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:27.220  6615  6661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:27.220  6615  6661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:27.220  6615  6661 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:27.220  6615  6661 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:27.220  6615  6661 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:27.220  6615  6661 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 15:44:27.220  6615  6661 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:44:27.220  6615  6661 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 15:44:27.230  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 15:44:27.230  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:27.260  6615  6615 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 15:44:27.260  1015  1504 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 15:44:27.260  1015  1504 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 15:44:27.260  1015  1504 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 15:44:27.260  1015  1504 D BatteryService: stay LED for fully charged
08-30 15:44:27.260  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 15:44:27.260  1015  1015 I MotionRecognitionService: Plugged
,08-30 15:44:27.270  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 15:44:27.270  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 15:44:27.270  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 15:44:27.270  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-30 15:44:27.270  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 15:44:27.270  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 15:44:27.280  2739  2739 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 15:44:27.280  2739  2847 D HeadsetStateMachine: Disconnected process message: 10
,08-30 15:44:27.290  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 15:44:27.290  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 15:44:27.290  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-30 15:44:27.290  1175  1175 D SViewCoverView: level :100 plugged : 2
,08-30 15:44:27.750  6615  6668 W jxcore-log: Initializing JXcore engine
08-30 15:44:27.750  6615  6668 W jxcore-log: JXcore engine is ready
,08-30 15:44:27.810  1928  1928 E audit   : type=1400 msg=audit(1472564667.810:205): avc:  denied  { ioctl } for  pid=6668 comm="Thread-1210" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
08-30 15:44:27.810  1928  1928 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-30 15:44:27.810  1928  1928 E audit   : type=1300 msg=audit(1472564667.810:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9defb8f8 items=0 ppid=307 ppcomm=main pid=6668 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1210" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-30 15:44:27.810  1928  1928 E audit   : type=1320 msg=audit(1472564667.810:205): 
,08-30 15:44:27.820  6615  6668 W jxcore-log: Starting JXcore engine
,08-30 15:44:27.930  6615  6668 W jxcore-log: Platform android
08-30 15:44:27.930  6615  6668 W jxcore-log: 
08-30 15:44:27.930  6615  6668 W jxcore-log: Process ARCH arm
08-30 15:44:27.930  6615  6668 W jxcore-log: 
,08-30 15:44:28.140  6615  6668 I jxcore-log: JXcore Cordova bridge is ready!
08-30 15:44:28.140  6615  6668 I jxcore-log: 
,08-30 15:44:28.140  6615  6668 W jxcore-log: JXcore engine is started
,08-30 15:44:28.140  6615  6661 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 15:44:28.150  6615  6615 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 15:44:28.240   288   288 E SMD     : DCD OFF
,08-30 15:44:28.700  1015  1047 I PowerManagerService: [PWL] Off : 30s ago
,08-30 15:44:28.820  1015  1093 V AlarmManager: waitForAlarm result :4
,08-30 15:44:28.880  1015  2844 D SSRM:n  : SIOP:: AP = 340
,08-30 15:44:29.260  1015  1678 I art     : Explicit concurrent mark sweep GC freed 31646(1826KB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 24MB/36MB, paused 2.484ms total 141.997ms
,08-30 15:44:29.560  1015  1325 E Watchdog: !@Sync 3
,08-30 15:44:30.220   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-30 15:44:30.220   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-30 15:44:31.240   288   288 E SMD     : DCD OFF
,08-30 15:44:34.250   288   288 E SMD     : DCD OFF,
,08-30 15:44:35.220   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 15:44:36.140  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-30 15:44:36.220   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 15:44:36.320  5494  5494 D FactoryTest: Not factory mode
,08-30 15:44:36.330  5494  5494 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-30 15:44:36.330  5494  5494 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-30 15:44:36.330  5494  5494 D MTPRx   : still no open session command from host, so toast
,08-30 15:44:36.330  5494  5494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-30 15:44:36.330  5494  5494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-30 15:44:36.330  5494  5494 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115236
,08-30 15:44:36.330  1015  1477 E PersonaManagerService: inState():  stateMachine is null !!
,08-30 15:44:36.330  1015  1477 I PersonaManagerService: PersonaId don't exist
08-30 15:44:36.330  1015  1477 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-30 15:44:36.340  1015  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 15:44:36.340  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:36.340  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:36.340  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-30 15:44:36.350  1015  1477 W ActivityManager: mDVFSHelper.acquire()
,08-30 15:44:36.370  1015  1477 D PersonaManager: isKioskContainerExistOnDevice
,08-30 15:44:36.370  1015  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 15:44:36.370  1015  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 15:44:36.370  1015  1477 D InputDispatcher: Focused application set to: xxxx
08-30 15:44:36.370  1015  1477 D InputDispatcher: Focus left window: 6615
,08-30 15:44:36.380  5494  5494 E MTPRx   : started activity for popup
,08-30 15:44:36.380  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 15:44:36.380  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 15:44:36.400  5494  5494 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-30 15:44:36.400  5494  5494 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 15:44:36.400  5494  5494 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 15:44:36.400  5494  5494 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 15:44:36.400  5494  5494 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 15:44:36.400  5494  5494 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 15:44:36.430  5494  5494 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true,
,08-30 15:44:36.430  1015  1678 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
08-30 15:44:36.430  1015  1678 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 15:44:36.430  1015  1678 D InputDispatcher: Focused application set to: xxxx
08-30 15:44:36.430  1015  1678 D InputDispatcher: Focus entered window: 6615
,08-30 15:44:36.440  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 15:44:36.440  1015  1477 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 15:44:36.440  1015  1477 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@362aed3d attribute=null, token = android.os.BinderProxy@2fc7f464
,08-30 15:44:36.440  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 15:44:36.480  5494  5494 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-30 15:44:36.490  5494  5494 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-30 15:44:36.490  5494  5494 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-30 15:44:36.510  6615  6615 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 15:44:36.510  6615  6615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED,
08-30 15:44:36.510  6615  6615 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
08-30 15:44:36.510  6615  6615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-30 15:44:36.510  1015  1480 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 15:44:36.510  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-30 15:44:36.510  1015  1480 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-30 15:44:36.510  1015  1480 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-30 15:44:36.510  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-30 15:44:36.540  6615  6615 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
08-30 15:44:36.540  6615  6615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 15:44:36.540  6615  6615 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9c70de6 time:115445
08-30 15:44:36.540  6615  6615 V ActivityThread: updateVisibility : ActivityRecord{23e62272 token=android.os.BinderProxy@9c70de6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
,08-30 15:44:36.540  6615  6615 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@28bf04c2 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@322eb75b, 16908290=android.view.AbsSavedState$1@322eb75b}, android:focusedViewId=100}]}]
08-30 15:44:36.540  6615  6615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 15:44:36.540  6615  6615 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 15:44:36.540  6615  6615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 15:44:36.550  1015  1477 D PersonaManager: isKioskContainerExistOnDevice
,08-30 15:44:37.220   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 15:44:37.250   288   288 E SMD     : DCD OFF,
,08-30 15:44:37.320  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 15:44:37.320  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 15:44:37.320  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 15:44:37.320  1015  1028 D BatteryService: stay LED for fully charged
,08-30 15:44:37.320  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 15:44:37.320  1015  1015 I MotionRecognitionService: Plugged
,08-30 15:44:37.320  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 15:44:37.330  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 15:44:37.330  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 15:44:37.330  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 15:44:37.330  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 15:44:37.340  2739  2739 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 15:44:37.340  2739  2847 D HeadsetStateMachine: Disconnected process message: 10
,08-30 15:44:37.350  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 15:44:37.350  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 15:44:37.350  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 15:44:37.350  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-30 15:44:37.350  1175  1175 D SViewCoverView: level :100 plugged : 2
,08-30 15:44:38.220   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 15:44:38.230  1015  2894 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-30 15:44:38.900  1015  2844 D SSRM:n  : SIOP:: AP = 350,
,08-30 15:44:39.220   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 15:44:39.350  1015  1040 W ActivityManager: mDVFSHelper.release()
,08-30 15:44:40.220   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-30 15:44:40.250   288   288 E SMD     : DCD OFF
,08-30 15:44:40.400  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-30 15:44:40.400  6615  6668 I jxcore-log: 
,08-30 15:44:40.400  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-30 15:44:40.400  6615  6668 I jxcore-log: 
,08-30 15:44:40.410  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:40.410  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:40.410  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:40.410  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:40.410  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:40.410  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:40.410  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:40.410  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:44:40.410  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:44:40.410  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 15:44:40.410  6615  6668 I jxcore-log: 
,08-30 15:44:40.410  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 15:44:40.410  6615  6668 I jxcore-log: 
,08-30 15:44:41.080  6615  6668 D executeNativeTests: Running unit tests
,08-30 15:44:41.100  1015  1093 V AlarmManager: waitForAlarm result :4
,08-30 15:44:41.110  1015  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-30 15:44:41.140  1905  1905 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-30 15:44:41.190  1015  1464 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:44:41.190  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-30 15:44:41.190  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:41.190  1015  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:41.190  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:41.190  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:44:41.190  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 added. We now have 2 listener(s)
,08-30 15:44:41.200  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 15:44:41.200  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:44:41.200  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:44:41.200  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:44:41.200  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 added. We now have 2 listener(s)
08-30 15:44:41.200  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:44:41.200  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:44:41.200  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:44:41.210  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:41.210  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:41.210  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:41.210  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:41.210  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:41.210  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:41.210  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:41.210  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:44:41.210  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:44:41.210  6615  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:44:41.210  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:41.210  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:44:41.210  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:44:41.210  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 15:44:41.220  6615  6668 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 15:44:41.220  6615  6668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 15:44:41.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:44:41.220  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:44:41.220  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:44:41.220  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.220  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.220  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.220  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.220  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:44:41.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:44:41.220  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 removed from the list
08-30 15:44:41.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.220  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 removed from the list
08-30 15:44:41.220  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:41.220  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.220  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.220  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.220  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.230  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.230  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.230  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.230  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.230  6615  6668 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 15:44:41.230  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.230  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.230  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.230  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.230  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.230  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.230  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.230  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.230  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.230  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.230  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.230  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.230  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.230  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.240  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.240  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.240  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.240  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 15:44:41.240  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.240  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.240  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.240  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.240  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.240  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.240  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.240  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.240  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.240  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.240  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.240  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.240  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.240  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.240  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.240  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.240  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.240  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.240  6615  6668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 15:44:41.240  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:41.250  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:41.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:41.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:41.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:41.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:41.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:41.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:41.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:41.250  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:41.250  6615  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:44:41.250  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:44:41.250  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:44:41.250  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:44:41.250  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:41.250  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:44:41.260  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:44:41.260  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:41.260  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:41.270  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 15:44:41.270  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:44:41.280  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-30 15:44:41.280  4352  4352 D ConnectivityManager: CallingUid : 10011, CallingPid : 4352
08-30 15:44:41.280  1015  2020 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:44:41.280  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-30 15:44:41.280  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-30 15:44:41.280  1015  1127 D ConnectivityService: apparently satisfied.  currentScore=60
08-30 15:44:41.280  4352  6679 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 15:44:41.290  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 15:44:41.290  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 15:44:41.290  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:44:41.290  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 15:44:41.310  2739  3032 D BtGatt.GattService: registerClient() - UUID=66f35a9f-aa21-4b92-9f96-62acd156ccf9
,08-30 15:44:41.350  4352  6681 W DriveInitializer: Background init thread started
,08-30 15:44:41.360  2739  2836 D BtGatt.GattService: onClientRegistered() - UUID=66f35a9f-aa21-4b92-9f96-62acd156ccf9, clientIf=6
,08-30 15:44:41.360  6615  6623 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 15:44:41.360  2739  3030 D BtGatt.GattService: start scan with filters
,08-30 15:44:41.370  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 15:44:41.370  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:44:41.370  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:44:41.370  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:44:41.370  2739  2845 D BtGatt.ScanManager: handling starting scan
,08-30 15:44:41.370  2739  2845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:41.370  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:44:41.370  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 15:44:41.370  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:44:41.380  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:44:41.380  2739  2836 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 15:44:41.380  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.380  2739  2845 D BtGatt.ScanManager: allow scan with filters
,08-30 15:44:41.380  2739  2845 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 15:44:41.380  2739  2845 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-30 15:44:41.380   257   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
,08-30 15:44:41.380   257   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 15:44:41.380  4352  6681 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-30 15:44:41.390  6615  6668 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 15:44:41.390  2739  2836 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 15:44:41.390  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:44:41.390  2739  2845 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 15:44:41.390  2739  2845 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 15:44:41.390  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:44:41.390  6615  6668 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 15:44:41.390  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.390  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:44:41.390  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.390  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:44:41.390  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:44:41.390  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:44:41.390  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:44:41.390  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:44:41.400  2739  2836 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 15:44:41.400  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:44:41.400  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:44:41.400  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 15:44:41.400  2739  2751 D BtGatt.GattService: stopScan() - queue size =1
,08-30 15:44:41.400  2739  3032 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 15:44:41.400  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:41.400  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 15:44:41.400  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:44:41.400  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:44:41.400  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 15:44:41.400  2739  2836 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 15:44:41.400  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.410  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:44:41.410  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 15:44:41.410  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:44:41.410  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:44:41.410  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:44:41.410  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.410  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:44:41.410  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:44:41.410  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:44:41.410  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.410  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:44:41.410  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.410  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.410  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.410  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.410  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.410  6615  6668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 15:44:41.410  2739  2845 D BtGatt.ScanManager: filter size is 1
08-30 15:44:41.410  2739  2845 D BtGatt.ScanManager: delete FilterIndex - 3
08-30 15:44:41.410  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:44:41.420  2739  2836 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 15:44:41.420  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:44:41.420  2739  2845 D BtGatt.ScanManager: stopping BLe Batch
,08-30 15:44:41.420  2739  2836 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 15:44:41.430  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.430  2739  2845 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 15:44:41.430  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:41.430  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:41.430  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:41.430  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:41.430  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:41.430  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:41.430  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:41.430  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:44:41.430  2739  2836 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 15:44:41.430  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.430  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:44:41.430  6615  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:44:41.440  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:44:41.440  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:44:41.440  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:44:41.440  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:41.440  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 15:44:41.440  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:44:41.440  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:41.440  1015  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:44:41.440  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-30 15:44:41.440  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:41.440  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:41.440  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:41.440  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:41.450  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:44:41.460  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:44:41.460  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 15:44:41.460  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:44:41.460  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 15:44:41.460  1015  1678 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-30 15:44:41.460  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-30 15:44:41.470  2739  2748 D BtGatt.GattService: registerClient() - UUID=07241dee-2d07-4ef8-b427-d8653a491567
,08-30 15:44:41.480  4352  6681 W DriveInitializer: Background init thread ended
,08-30 15:44:41.490  1015  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:44:41.490  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-30 15:44:41.490  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:41.490  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:41.490  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:41.510  2739  2836 D BtGatt.GattService: onClientRegistered() - UUID=07241dee-2d07-4ef8-b427-d8653a491567, clientIf=6
,08-30 15:44:41.510  6615  6624 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 15:44:41.510  2739  3030 D BtGatt.GattService: start scan with filters
,08-30 15:44:41.510  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:44:41.510  2739  2845 D BtGatt.ScanManager: handling starting scan
08-30 15:44:41.510  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:44:41.510  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:44:41.510  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:44:41.520  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:44:41.520  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 15:44:41.520  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:44:41.520  2739  2836 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 15:44:41.520  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:44:41.520  2739  2845 D BtGatt.ScanManager: allow scan with filters
08-30 15:44:41.520  2739  2845 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 15:44:41.520  2739  2845 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-30 15:44:41.520  4352  6690 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-30 15:44:41.520  4352  6690 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 15:44:41.520  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:44:41.530  2739  2836 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 15:44:41.530  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.530  2739  2845 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:44:41.530  2739  2845 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 15:44:41.530  6615  6668 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 15:44:41.530  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.530  6615  6668 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 15:44:41.530  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.530  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:44:41.530  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.530  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:44:41.530  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:44:41.530  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:44:41.530  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:44:41.530  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:44:41.530  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:44:41.530  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 15:44:41.540  2739  3032 D BtGatt.GattService: stopScan() - queue size =1
,08-30 15:44:41.540  2739  2836 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 15:44:41.540  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.540  2739  2748 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 15:44:41.540  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:41.540  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 15:44:41.540  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:44:41.540  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:44:41.540  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 15:44:41.540  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:44:41.540  2739  2836 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 15:44:41.540  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.540  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:44:41.540  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:44:41.540  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 15:44:41.540  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:44:41.540  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:44:41.540  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:44:41.540  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:44:41.540  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.540  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.540  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:44:41.540  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.540  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.540  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.540  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.540  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.550  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.550  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.550  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.550  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.550  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.550  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.550  6615  6668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 15:44:41.550  2739  2845 D BtGatt.ScanManager: filter size is 1
,08-30 15:44:41.550  2739  2845 D BtGatt.ScanManager: delete FilterIndex - 4
,08-30 15:44:41.550  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:44:41.550  1905  1905 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 15:44:41.560  2739  2836 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 15:44:41.560  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.560  2739  2845 D BtGatt.ScanManager: stopping BLe Batch
,08-30 15:44:41.560  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:41.560  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:41.560  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:41.560  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:41.560  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:41.560  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:41.560  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:41.560  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:44:41.560  2739  2836 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 15:44:41.570  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.570  2739  2845 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 15:44:41.570  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:44:41.570  6615  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:44:41.570  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:44:41.570  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:44:41.570  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:44:41.570  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:44:41.570  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 15:44:41.570  2739  2836 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 15:44:41.570  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.580  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:41.580  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:41.580  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:44:41.590  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:44:41.590  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:44:41.590  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 15:44:41.590  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:44:41.590  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 15:44:41.600  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:41.600  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:41.600  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:41.600  2739  3030 D BtGatt.GattService: registerClient() - UUID=f2147e94-c778-4610-8b64-838f6691d743
,08-30 15:44:41.640  2739  2836 D BtGatt.GattService: onClientRegistered() - UUID=f2147e94-c778-4610-8b64-838f6691d743, clientIf=6
,08-30 15:44:41.640  6615  6623 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 15:44:41.640  2739  2751 D BtGatt.GattService: start scan with filters
,08-30 15:44:41.640  2739  2845 D BtGatt.ScanManager: handling starting scan
,08-30 15:44:41.650  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:44:41.650  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:44:41.650  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 15:44:41.650  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:44:41.650  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:44:41.650  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:44:41.650  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 15:44:41.650  2739  2836 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 15:44:41.650  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.660  2739  2845 D BtGatt.ScanManager: allow scan with filters
08-30 15:44:41.660  2739  2845 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 15:44:41.660  2739  2845 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-30 15:44:41.660  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:44:41.660  2739  2836 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 15:44:41.660  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:44:41.660  2739  2845 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 15:44:41.660  2739  2845 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 15:44:41.660  6615  6668 I io.jxcore.node.ConnectionHelper: start: OK
08-30 15:44:41.660  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.660  6615  6668 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 15:44:41.660  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.660  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:44:41.660  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.660  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:44:41.660  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:44:41.660  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:44:41.660  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:44:41.660  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:44:41.660  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:44:41.660  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 15:44:41.670  2739  3030 D BtGatt.GattService: stopScan() - queue size =1
,08-30 15:44:41.670  2739  2751 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 15:44:41.670  2739  2836 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 15:44:41.670  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:44:41.670  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 15:44:41.670  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 15:44:41.670  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:44:41.670  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 15:44:41.680  2739  2836 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 15:44:41.680  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:44:41.680  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 15:44:41.680  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:44:41.680  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:44:41.680  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:44:41.680  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:44:41.680  1015  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:44:41.680  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-30 15:44:41.680  2739  2845 D BtGatt.ScanManager: filter size is 1
,08-30 15:44:41.680  2739  2845 D BtGatt.ScanManager: delete FilterIndex - 5
08-30 15:44:41.680  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:41.680  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:41.680  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:41.680  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:44:41.680  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:44:41.690  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:44:41.690  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:44:41.690  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:44:41.690  6615  6668 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 15:44:41.690  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.690  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.690  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.690  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:44:41.690  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.690  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.690  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.690  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.690  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.690  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.690  2739  2836 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 15:44:41.690  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:44:41.690  2739  2845 D BtGatt.ScanManager: stopping BLe Batch
,08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.690  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.690  6615  6668 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 15:44:41.690  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.690  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.690  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.690  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.690  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.690  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.690  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.690  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.690  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.690  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.690  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.690  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.690  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.690  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 15:44:41.690  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.690  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.690  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.690  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.690  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.690  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.690  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.690  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.690  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.690  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.690  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.690  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.690  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.700  2739  2836 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 15:44:41.700  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:44:41.700  2739  2845 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.700  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.700  6615  6668 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 15:44:41.700  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.700  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.700  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.700  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.700  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.700  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.700  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.700  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.700  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.700  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.700  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.700  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:44:41.700  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.700  2739  2836 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-30 15:44:41.700  2739  2836 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:44:41.700  6615  6668 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 15:44:41.700  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.700  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.700  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.700  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.700  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.700  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.700  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.700  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.700  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:44:41.700  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.700  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.700  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.700  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 15:44:41.700  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.710  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 15:44:41.710  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:44:41.710  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:44:41.710  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:44:41.710  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:44:41.710  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:44:41.710  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.710  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.710  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.710  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.710  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.710  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.710  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.710  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.710  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.710  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.710  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.710  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.710  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.710  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.710  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.710  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.710  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.710  6615  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:44:41.710  6615  6668 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 15:44:41.710  6615  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:44:41.710  6615  6668 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 15:44:41.710  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 15:44:41.710  6615  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 15:44:41.710  6615  6668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:44:41.710  6615  6668 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 15:44:41.710  6615  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:44:41.710  6615  6668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:44:41.710  6615  6668 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 15:44:41.710  6615  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:44:41.710  6615  6668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:44:41.710  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-30 15:44:41.710  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 15:44:41.720  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-30 15:44:41.720  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 15:44:41.720  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 15:44:41.720  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-30 15:44:41.720  6615  6668 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 15:44:41.720  6615  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:44:41.720  6615  6668 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 15:44:41.720  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.720  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:44:41.720  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.720  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.720  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.720  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.720  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-30 15:44:41.720  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.720  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.720  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.720  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.720  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.720  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.720  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.720  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.720  6615  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1274)
,08-30 15:44:41.720  6615  6693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1274
08-30 15:44:41.720  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.720  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.720  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.720  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.720  6615  6668 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-30 15:44:41.720  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.720  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.720  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.720  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.720  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.720  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.720  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.720  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.720  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.720  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.720  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.720  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.720  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.720  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.730  6615  6668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-30 15:44:41.730  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.730  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.730  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:44:41.730  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.730  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:44:41.730  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.730  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.730  6615  6668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 15:44:41.730  6615  6668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 15:44:41.730  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:44:41.730  6615  6668 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 15:44:41.730  6615  6668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 15:44:41.730  6615  6668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 15:44:41.730  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 15:44:41.730  6615  6668 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 15:44:41.730  6615  6668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 15:44:41.730  6615  6668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 15:44:41.730  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 15:44:41.730  6615  6668 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 15:44:41.730  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.730  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.730  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.730  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.730  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.730  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.730  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: ,release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.730  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.730  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.730  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.730  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.730  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.730  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.730  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.730  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.730  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.730  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.7,30  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.730  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.730  6615  6692 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.730  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.730  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 15:44:41.740  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:41.740  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 15:44:41.740  6615  6692 D BluetoothSocket: connect(): myUserId = 0
08-30 15:44:41.740  6615  6692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 15:44:41.740  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 15:44:41.740  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:44:41.740  6615  6615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 15:44:41.740  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.740  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 15:44:41.740  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 15:44:41.740  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.740  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.740  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:44:41.740  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.740  6615  6615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 15:44:41.740  2739  2748 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:44:41.740  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.740  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.740  6615  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 15:44:41.740  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:44:41.740  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.740  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.740  6615  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 15:44:41.740  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.740  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:44:41.740  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.740  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:44:41.740  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.740  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.740  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.740  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.740  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.740  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.740  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.740  6615  6615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 15:44:41.740  6615  6692 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[108]}
,08-30 15:44:41.740  1015  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:44:41.740  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-30 15:44:41.750  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.750  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.750  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.750  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.750  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:41.750  6615  6668 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 15:44:41.750  6615  6668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 15:44:41.750  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:44:41.750  1015  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:41.750  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 15:44:41.750  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:44:41.750  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.750  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.750  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.750  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.750  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.750  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.750  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.750  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.750  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.750  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.750  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.750  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.750  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.750  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.750  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.750  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.750  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.750  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.760  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:44:41.760  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.760  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.760  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.760  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.760  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.760  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.760  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.760  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.760  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.760  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.760  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.760  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.760  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.760  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.760  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.760  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.760  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.760  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:41.760  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:41.760  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:41.760  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:41.760  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.760  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.760  6615  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d8a5328 not in the list
08-30 15:44:41.760  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.760  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
08-30 15:44:41.760  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:41.760  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.760  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:41.760  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:41.760  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:41.760  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:41.760  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:41.760  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:41.760  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bc841 not in the list
,08-30 15:44:41.770  6615  6668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:44:41.770  6615  6668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:44:41.770  6615  6668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-30 15:44:41.770  6615  6668 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 15:44:41.770  6615  6668 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 15:44:41.770  6615  6668 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 15:44:41.770  6615  6668 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 15:44:41.770  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:44:41.770  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f62ff3b added. We now have 2 listener(s)
08-30 15:44:41.770  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:44:41.770  6615  6668 D BluetoothAdapter: enable()
,08-30 15:44:41.770  6615  6668 D BluetoothAdapter: enable(): BT is already enabled..!
,08-30 15:44:41.780  1015  1477 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 15:44:41.780  1015  1477 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 15:44:41.780  1015  1477 D SecContentProvider2: mCursor = null
,08-30 15:44:41.780  1015  1477 D WifiService: setWifiEnabled: true pid=6615, uid=10171
,08-30 15:44:41.780  1015  1477 W ActivityManager: Permission Denial: getCurrentUser() from pid=6615, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-30 15:44:41.790  1015  1477 W WifiService: Failed getting userId using ActivityManagerNative
08-30 15:44:41.790  1015  1477 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6615, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-30 15:44:41.790  1015  1477 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 15:44:41.790  1015  1477 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 15:44:41.790  1015  1477 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 15:44:41.790  1015  1477 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 15:44:41.790  1015  1477 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 15:44:41.800  1015  1477 D SettingsProvider: name = wifi_on
,08-30 15:44:41.800  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:44:41.800  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@398cd658 added. We now have 3 listener(s)
08-30 15:44:41.800  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:44:41.800  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:44:41.800  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a5643b1 added. We now have 4 listener(s)
08-30 15:44:41.800  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:44:41.810  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:44:41.810  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b40f096 added. We now have 5 listener(s)
08-30 15:44:41.810  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:44:41.810  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 15:44:41.810  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-30 15:44:41.810  1015  1028 D SecContentProvider2: mCursor = null
,08-30 15:44:41.810  1015  1028 D SettingsProvider: name = wifi_on,
08-30 15:44:41.810  1015  1028 D WifiService: setWifiEnabled: false pid=6615, uid=10171
,08-30 15:44:41.820  6615  6668 D BluetoothAdapter: disable()
,08-30 15:44:41.820  1015  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 15:44:41.820  1349  1349 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 15:44:41.820  1349  1349 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-30 15:44:41.820  1015  1464 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 15:44:41.820  1349  1349 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 15:44:41.820  1349  1349 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 15:44:41.820  1015  1464 W ActivityManager: userId = 0, bbcId = -10000,
08-30 15:44:41.820  1015  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:41.820  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:41.830  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:44:41.830  1015  1409 D SettingsProvider: name = bluetooth_on
,08-30 15:44:41.840  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:44:41.850  2739  2831 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-30 15:44:41.850  2739  2831 D BluetoothAdapterProperties: Setting state to 13
08-30 15:44:41.850  2739  2831 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 15:44:41.850  2739  2831 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 15:44:41.850  2739  2831 D BluetoothAdapterService: updateAdapterState state is 13
,08-30 15:44:41.850  1015  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:41.850  1015  1125 E WifiNative-wlan0: do suspend true
08-30 15:44:41.850  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 15:44:41.850  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:41.850  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:41.850  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:41.850  2739  2739 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-30 15:44:41.850  2739  2739 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8554d07, channel: 19, state: LISTENING
,08-30 15:44:41.850  2739  2739 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@8554d07, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35810b0f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24341e34mSocket: android.net.LocalSocket@1b9ce45d impl:android.net.LocalSocketImpl@c4fc1d2 fd:FileDescriptor[74]
08-30 15:44:41.850  2739  2831 D BluetoothAdapterService: Autoconnection is available 
08-30 15:44:41.850  2739  2739 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1b9ce45d impl:android.net.LocalSocketImpl@c4fc1d2 fd:FileDescriptor[74]
08-30 15:44:41.850  2739  2831 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-30 15:44:41.850  2739  2831 D BluetoothAdapterService: terminating service from this receiver
,08-30 15:44:41.850  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:41.850  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
08-30 15:44:41.860  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:41.860  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:41.860  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:41.860  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:41.860  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:41.860  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:41.860  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:41.860  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:41.860  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:44:41.860  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:44:41.860  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:44:41.860  6615  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:44:41.860  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:41.870  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:41.870  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-30 15:44:41.870  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 15:44:41.870  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 15:44:41.870  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 15:44:41.870  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:41.870  1175  1175 D BluetoothTile:  getBluetoothState : 13
08-30 15:44:41.870  1794  1794 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0,
,08-30 15:44:41.880  1015  1462 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 15:44:41.880  1015  1215 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 15:44:41.880  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-30 15:44:41.880  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 15:44:41.880  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:41.880  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 15:44:41.880  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:41.880  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:41.880  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:41.890  2739  2831 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 15:44:41.890  2739  2831 D BluetoothAdapterProperties: mDiscovering is false
,08-30 15:44:41.890  1015  2020 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 15:44:41.890  2739  2831 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 15:44:41.890  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:44:41.890  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:41.890  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:41.890  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:41.890  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:41.890  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:41.890  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:41.890  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:41.890  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:44:41.890  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:41.890  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:44:41.900  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:41.900  2739  2836 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 15:44:41.900  2739  2836 D BluetoothAdapterProperties: Scan Mode:20
,08-30 15:44:41.900  2739  2739 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@56fb2a3, channel: 5, state: LISTENING
08-30 15:44:41.900  2739  2739 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@56fb2a3, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ea779c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@260ee9a0mSocket: android.net.LocalSocket@11486959 impl:android.net.LocalSocketImpl@3fc4291e fd:FileDescriptor[76]
08-30 15:44:41.900  2739  2739 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@11486959 impl:android.net.LocalSocketImpl@3fc4291e fd:FileDescriptor[76]
,08-30 15:44:41.900  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:41.900  2739  2739 I BtOppRfcommListener: stopping Accept Thread
08-30 15:44:41.900  2739  2739 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1640d5ff, channel: 12, state: LISTENING
08-30 15:44:41.900  2739  2739 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1640d5ff, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3fe37746, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d08ffccmSocket: android.net.LocalSocket@1e8d4215 impl:android.net.LocalSocketImpl@3d85b92a fd:FileDescriptor[80]
08-30 15:44:41.900  2739  2739 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e8d4215 impl:android.net.LocalSocketImpl@3d85b92a fd:FileDescriptor[80]
,08-30 15:44:41.900  2739  5040 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:44:41.900  2739  5040 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 15:44:41.910  2739  2831 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 15:44:41.910  2739  2831 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-30 15:44:41.910  2739  2831 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-30 15:44:41.910  2739  2831 E bt-btif : cmd socket is not created
08-30 15:44:41.910  2739  2739 V BluetoothOppManager: cleanUp...
,08-30 15:44:41.910  2739  2896 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-30 15:44:41.910  2739  2896 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 15:44:41.910  2739  2831 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 15:44:41.910  6615  6692 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1d250004, channel: -1, state: INIT
,08-30 15:44:41.910  6615  6692 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1d250004, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35da69ed, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14938022mSocket: android.net.LocalSocket@30241ab3 impl:android.net.LocalSocketImpl@18f41870 fd:FileDescriptor[108]
08-30 15:44:41.910  6615  6692 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@30241ab3 impl:android.net.LocalSocketImpl@18f41870 fd:FileDescriptor[108]
08-30 15:44:41.910  6615  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1274)
,08-30 15:44:41.910  2739  2896 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:44:41.910  2739  2896 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:44:41.910  2739  2896 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 15:44:41.910  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:41.920  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:44:41.920  1015  1464 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 15:44:41.920  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 15:44:41.920  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:41.920  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:41.920  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 15:44:41.920  1296  1296 D BluetoothPbap: Proxy object disconnected
08-30 15:44:41.920  1296  1296 D PbapServerProfile: Bluetooth service disconnected
,08-30 15:44:41.930  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:44:41.930  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 15:44:41.930  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:41.930  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 15:44:41.940  1015  1464 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-30 15:44:41.940  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:41.940  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:41.940  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:41.940  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:41.950  6702  6702 E Zygote  : MountEmulatedStorage()
08-30 15:44:41.950  6702  6702 E Zygote  : v2
08-30 15:44:41.950  6702  6702 I libpersona: KNOX_SDCARD checking this for 10055
08-30 15:44:41.950  6702  6702 I libpersona: KNOX_SDCARD not a persona
08-30 15:44:41.950  1015  1464 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6702 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-30 15:44:41.960  6702  6702 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 15:44:41.960  6702  6702 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:44:41.960  6702  6702 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-30 15:44:41.960  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:44:41.960  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:41.960  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-30 15:44:41.960  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:41.960  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:41.980  1015  1678 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:41.980  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:41.980  1015  1678 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:41.980  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:41.990  1349  1349 I wpa_supplicant: nl80211: Received scan results (8 BSSes)
,08-30 15:44:41.990   278   894 D CommandListener: Clearing all IP addresses on wlan0
,08-30 15:44:41.990  1015  1124 D WifiP2pService: InactiveState{ what=147461 }
,08-30 15:44:41.990  1015  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-30 15:44:41.990  1015  1124 D WifiP2pService: DefaultState{ what=147461 }
08-30 15:44:41.990  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:41.990  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 15:44:41.990  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:41.990  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:41.990  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:41.990  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:41.990  1905  4817 V NativeCrypto: Read error: ssl=0xb8eb2878: I/O error during system call, Connection timed out
08-30 15:44:41.990  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
08-30 15:44:41.990  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 15:44:42.000  1905  4817 V NativeCrypto: SSL shutdown failed: ssl=0xb8eb2878: I/O error during system call, Broken pipe,
08-30 15:44:42.000  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 15:44:42.000  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:44:42.000  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 15:44:42.000  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-30 15:44:42.000  1905  4817 E GCM     : Wifi connection closed with errorCode 20
,08-30 15:44:42.010  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 15:44:42.010  1015  1479 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-30 15:44:42.010  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:42.010  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:44:42.010  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.010  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.010  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.010  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:42.010  1015  2114 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:42.010  1015  2114 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:42.010  1015  2114 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 15:44:42.020  6702  6702 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:42.020  6702  6702 D ActivityThread: Added TimaKeyStore provider
08-30 15:44:42.020  1015  2114 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:42.020  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
08-30 15:44:42.020  1015  2114 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-30 15:44:42.020  1015  2114 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 15:44:42.020  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-30 15:44:42.020  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 15:44:42.020  1015  2114 I qtaguid : Tagging socket 351 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
08-30 15:44:42.020  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:42.020  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-30 15:44:42.020  1015  1149 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 15:44:42.020  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-30 15:44:42.030  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
08-30 15:44:42.030  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-30 15:44:42.030  1015  2114 I qtaguid : Untagging socket 351
08-30 15:44:42.030  1015  1124 D WifiP2pService: P2pDisablingState
08-30 15:44:42.030  1015  2114 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 15:44:42.030  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-30 15:44:42.030  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-30 15:44:42.040  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 15:44:42.060  6702  6702 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 15:44:42.070  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-30 15:44:42.070  1015  1124 D WifiP2pService: p2p socket connection lost
,08-30 15:44:42.070  1015  1125 E WifiNative-wlan0: do suspend true
08-30 15:44:42.070  1015  1124 D WifiP2pService: P2pDisabledState
,08-30 15:44:42.070  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-30 15:44:42.070  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-30 15:44:42.070  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 15:44:42.070  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:44:42.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:42.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:42.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:42.080  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-30 15:44:42.080  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 15:44:42.080  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-30 15:44:42.080  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 15:44:42.080  1015  1045 D WifiDisplayController: disconnect
08-30 15:44:42.080  1015  1045 D WifiDisplayController: updateConnection
08-30 15:44:42.080  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 15:44:42.080  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 15:44:42.090  6702  6702 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,08-30 15:44:42.090  6702  6702 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-30 15:44:42.090  6702  6702 D UserAnalysis: Create SecureDbHelper
08-30 15:44:42.090  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 15:44:42.100  6702  6702 D IntelligenceServiceApplication: onCreate()
,08-30 15:44:42.100  1015  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 15:44:42.100  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 15:44:42.110  6702  6702 D IntelligenceServiceApplication: no applications having user consent for prediction
08-30 15:44:42.110  2739  2896 W bt-l2cap: btif_mce_execute_service enable:0
,08-30 15:44:42.110  2739  2896 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:44:42.110  2739  2896 W bt-l2cap: HC lib lpm enable=0 return 0
08-30 15:44:42.110  2739  2896 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:44:42.110  1015  1409 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-30 15:44:42.110  2739  2896 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:44:42.110  2739  2896 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:44:42.110  2739  2896 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:44:42.110  2739  2896 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-30 15:44:42.110  2739  2896 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:44:42.110  2739  2896 W bt-btif : ag scb idx 1 not allocated
08-30 15:44:42.110  2739  2896 W bt-btif : ag scb idx 2 not allocated
08-30 15:44:42.110  2739  2896 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 15:44:42.110  2739  3006 I bt_userial_mct: exiting userial_read_thread
08-30 15:44:42.110  2739  3006 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 15:44:42.110  2739  2836 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 15:44:42.110  2739  2898 I bt_vendor: hw_epilog_process
,08-30 15:44:42.110  2739  2836 D bt_userial_mct: userial_close
08-30 15:44:42.110  2739  2836 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 15:44:42.110  1015  1409 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:42.110  1015  1409 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:42.110  1015  1409 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:42.110  1015  1409 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:42.130   278   894 D CommandListener: Clearing all IP addresses on wlan0,
08-30 15:44:42.130  1015  1409 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6726 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-30 15:44:42.130   278   887 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 15:44:42.130   278   887 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-30 15:44:42.130  6726  6726 E Zygote  : MountEmulatedStorage()
08-30 15:44:42.130  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-30 15:44:42.130  6726  6726 E Zygote  : v2
08-30 15:44:42.130  6726  6726 I libpersona: KNOX_SDCARD checking this for 10105
08-30 15:44:42.130  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.130  6726  6726 I libpersona: KNOX_SDCARD not a persona
08-30 15:44:42.130  6702  6702 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-30 15:44:42.130  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-30 15:44:42.130  1015  1127 V NetworkStats: updateIfacesLocked()
08-30 15:44:42.140  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:44:42.130  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-30 15:44:42.140  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 15:44:42.140  6726  6726 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:42.140  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.140  1015  1127 V NetworkStats: performPollLocked() took 4ms
08-30 15:44:42.140  1349  1349 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-30 15:44:42.140  6702  6702 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-30 15:44:42.140  6726  6726 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 15:44:42.140  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 15:44:42.140  6726  6726 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 15:44:42.150  1015  2114 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-30 15:44:42.150  1015  2114 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated,
08-30 15:44:42.150  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:42.150  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-30 15:44:42.150  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:44:42.150  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.150  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.150  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.150  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.150  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 15:44:42.150  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:44:42.150  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.150  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:42.150  1175  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 15:44:42.160  1015  2114 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:42.160  4352  6679 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-30 15:44:42.160  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-30 15:44:42.160  1015  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:44:42.160  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 15:44:42.160  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-30 15:44:42.160  1015  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-30 15:44:42.160  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-30 15:44:42.170  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-30 15:44:42.170  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:42.170  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 15:44:42.170  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.170  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.170  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.170  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.170  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 15:44:42.170  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 15:44:42.170  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-30 15:44:42.170  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 15:44:42.170  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 15:44:42.170  1455  1455 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 15:44:42.180  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-30 15:44:42.180  1175  1175 D HotspotTile: onReceive : 0, 0
,08-30 15:44:42.190  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE,
08-30 15:44:42.190  1015  1128 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:44:42.190  6726  6726 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 15:44:42.190  1015  1122 V NetworkStats: updateIfacesLocked()
08-30 15:44:42.190  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.190  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-30 15:44:42.190  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:44:42.190  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-30 15:44:42.190  6726  6726 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:42.200  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:42.200  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:42.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:42.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:42.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:42.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:42.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:42.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:42.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:44:42.200  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:42.200  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:44:42.210  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.210  1015  1122 V NetworkStats: performPollLocked() took 15ms
08-30 15:44:42.210  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
,08-30 15:44:42.210  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 15:44:42.210  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 15:44:42.210  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-30 15:44:42.210  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 15:44:42.210  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 15:44:42.210  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:42.210  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:42.210  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:42.210  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:42.210  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:42.210  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:42.210  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:42.210  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:42.210  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:42.210  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:42.210  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-30 15:44:42.210  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:44:42.210  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.210  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.210  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.210  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:42.220  1349  1349 I wpa_supplicant: Blacklist: Clear (all) 
08-30 15:44:42.220  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:44:42.220  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 15:44:42.220  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-30 15:44:42.220  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 15:44:42.220  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 15:44:42.220  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-30 15:44:42.220  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 15:44:42.220  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-30 15:44:42.220  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-30 15:44:42.220  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:42.220  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 15:44:42.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.220  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:42.220  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:42.240  1349  1349 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 15:44:42.240  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 15:44:42.240  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 15:44:42.240  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 15:44:42.240  6615  6615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:44:42.260  1015  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:42.260  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:42.260  1349  1349 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-30 15:44:42.260  1349  1349 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 15:44:42.260  1349  1349 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-30 15:44:42.260  1349  1349 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-30 15:44:42.260  1349  1349 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-30 15:44:42.260  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:42.260  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 15:44:42.260  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:44:42.260  1015  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:42.260  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
08-30 15:44:42.260  1015  1128 D Tethering: InitialState.processMessage what=4
,08-30 15:44:42.270  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:42.270  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 15:44:42.270  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:42.270  1015  1128 E Tethering: No numeric data
08-30 15:44:42.270  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:42.270  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:42.270  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:42.270  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:42.270  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 15:44:42.270  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
08-30 15:44:42.270  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 15:44:42.280  6746  6746 E Zygote  : MountEmulatedStorage(),
,08-30 15:44:42.280  6746  6746 E Zygote  : v2,
08-30 15:44:42.280  6746  6746 I libpersona: KNOX_SDCARD checking this for 10011
08-30 15:44:42.280  6746  6746 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:42.280  1015  1477 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6746 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,08-30 15:44:42.290  6746  6746 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 15:44:42.290  6746  6746 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 15:44:42.290  6746  6746 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 15:44:42.290  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 15:44:42.290  1015  1128 D Tethering: clearTetheredNotification()
,08-30 15:44:42.300  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.300  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-30 15:44:42.300  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:44:42.300  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 15:44:42.300  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 15:44:42.300  1175  1175 D HotspotTile: updateTetherState():false, false
,08-30 15:44:42.300  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.300  1015  1122 V NetworkStats: performPollLocked() took 5ms
,08-30 15:44:42.310  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:42.310  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:42.310  6746  6746 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:42.320  6746  6746 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:42.320   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb88c97c8
08-30 15:44:42.320   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,08-30 15:44:42.320   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-30 15:44:42.320   273   319 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1198745464)
,08-30 15:44:42.340  2739  2836 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
08-30 15:44:42.340  2739  2836 I bt_vendor: bluetooth satus is on
08-30 15:44:42.340  2739  2836 I bt_vendor: bt-vendor : resetting BT status
08-30 15:44:42.340  2739  2836 I bt_vendor: Starting hciattach daemon
08-30 15:44:42.340  2739  2836 I bt_vendor: try to set false
08-30 15:44:42.340  2739  2836 I bt_vendor: Starting hciattach daemon
08-30 15:44:42.340  2739  2836 I bt_vendor: try to set false
08-30 15:44:42.340  2739  2836 I bt_vendor: cleanup
08-30 15:44:42.340  2739  2896 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 15:44:42.340  2739  2836 I GKI_LINUX: GKI_exit_task 0 done,
08-30 15:44:42.340  2739  2836 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 15:44:42.340  2739  2831 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 15:44:42.340  2739  2831 D BtConfig.SecureMode: isSecureModeOn:false
08-30 15:44:42.340  2739  2831 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-30 15:44:42.340  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-30 15:44:42.340  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 15:44:42.350  6746  6746 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 15:44:42.350  6746  6746 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-30 15:44:42.350  2739  2831 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 15:44:42.360  1015  1409 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:42.360  1015  1409 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-30 15:44:42.360  1015  1409 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:42.360  1015  1409 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:42.360  1015  1409 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 15:44:42.360  2739  2739 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 15:44:42.360  2739  2739 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 15:44:42.360  2739  2739 D BtGatt.GattService: stop()
08-30 15:44:42.360  2739  2739 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 15:44:42.360  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 15:44:42.360  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 15:44:42.370  2739  2831 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 15:44:42.370  1015  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:42.370  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-30 15:44:42.370  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:42.370  1015  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:42.370  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 15:44:42.370  2739  2739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
08-30 15:44:42.370  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 15:44:42.370  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 15:44:42.380  2739  2831 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-30 15:44:42.390  1015  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:42.390  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 15:44:42.390  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:42.390  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:42.390  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 15:44:42.390  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 15:44:42.390  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 15:44:42.390  2739  2831 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-30 15:44:42.390  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 15:44:42.390  1015  1464 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:42.390  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-30 15:44:42.390  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:42.390  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:42.390  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 15:44:42.400  1349  1349 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 15:44:42.400  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 15:44:42.400  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 15:44:42.400  2739  2831 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-30 15:44:42.400  1015  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:42.400  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-30 15:44:42.400  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:42.400  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:42.400  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:42.400   273   319 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-30 15:44:42.400   273   319 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,08-30 15:44:42.400   273   319 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1198745464) wakelock released: 1, error no: 0
08-30 15:44:42.400   273   319 I rmt_storage: 
08-30 15:44:42.400  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 15:44:42.400  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 15:44:42.400   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb88c97c8
08-30 15:44:42.400  6746  6746 I MultiDex: VM with version 2.1.0 has multidex support
08-30 15:44:42.400  6746  6746 I MultiDex: install
08-30 15:44:42.400  6746  6746 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 15:44:42.400  2739  2831 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-30 15:44:42.400  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:42.400  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 15:44:42.400  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 15:44:42.410  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:42.410  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:42.410  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 15:44:42.410  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.410  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 15:44:42.410  1015  2020 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 15:44:42.410  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:42.410  1015  2020 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-30 15:44:42.410  2739  2831 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-30 15:44:42.410  1015  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:42.410  1015  2020 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:42.410  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-30 15:44:42.410  1015  2020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:42.410  1015  2020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 15:44:42.410  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 15:44:42.410  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 15:44:42.410  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 15:44:42.410  2739  2831 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-30 15:44:42.410  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:42.410  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:42.410  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 15:44:42.410  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:44:42.410  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:44:42.410  2739  2831 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:44:42.410  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:42.410  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:42.410  2739  2831 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:42.410  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 15:44:42.410  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 15:44:42.410  2739  2831 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 15:44:42.410  2739  2831 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 15:44:42.410  2739  2831 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 15:44:42.420  2739  2831 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 15:44:42.420  2739  2831 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 15:44:42.420  2739  2739 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-30 15:44:42.420  2739  2739 D HeadsetService: Received stop request...Stopping profile...
08-30 15:44:42.420  2739  2739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
08-30 15:44:42.420  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 15:44:42.420  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 15:44:42.420  2739  2739 D A2dpService: Received stop request...Stopping profile...
08-30 15:44:42.420  2739  2853 D A2dpStateMachine: Exit Disconnected: -1
08-30 15:44:42.420  1296  1296 D HeadsetProfile: Bluetooth service disconnected
,08-30 15:44:42.420  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 15:44:42.420  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.430  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 15:44:42.430  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.430  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 15:44:42.430  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.430  2739  2739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:42.430  1296  1296 D BluetoothA2dp: Proxy object disconnected
08-30 15:44:42.430  1296  1296 D A2dpProfile: Bluetooth service disconnected
08-30 15:44:42.430  2739  2739 D HidService: Received stop request...Stopping profile...
08-30 15:44:42.430  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-30 15:44:42.430  2739  2739 D HidService: Stopping Bluetooth HidService
08-30 15:44:42.430  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 15:44:42.430  2739  2739 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-30 15:44:42.440  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:42.440  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:44:42.440  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 15:44:42.440  1349  1349 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 15:44:42.440  2739  2739 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 15:44:42.440  2739  2739 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 15:44:42.440  2739  2739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:42.450  2739  2739 D HealthService: Received stop request...Stopping profile...
,08-30 15:44:42.450  2739  2739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
08-30 15:44:42.450  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 15:44:42.450  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.450  2739  2739 D PanService: Received stop request...Stopping profile...
08-30 15:44:42.450  2739  2739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
08-30 15:44:42.450  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 15:44:42.450  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 15:44:42.450  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 15:44:42.450  2739  2739 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 15:44:42.460  6746  6746 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 15:44:42.460  2739  2739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
08-30 15:44:42.460  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 15:44:42.460  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.460  1296  1296 D BluetoothInputDevice: Proxy object disconnected
08-30 15:44:42.460  1296  1296 D HidProfile: Bluetooth service disconnected
,08-30 15:44:42.460  2739  2739 D SapService: Received stop request...Stopping profile...
08-30 15:44:42.460  2739  2739 D SapService: Stopping Bluetooth SapService
08-30 15:44:42.460  2739  2739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:42.460  1296  1296 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 15:44:42.460  1296  1296 D PanProfile: Bluetooth service disconnected
08-30 15:44:42.460  1296  1296 D BluetoothMap: Proxy object disconnected
08-30 15:44:42.460  1296  1296 D MapProfile: Bluetooth service disconnected
,08-30 15:44:42.470  2739  2739 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-30 15:44:42.470  2739  2739 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 15:44:42.470  2739  2739 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 15:44:42.470  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 15:44:42.470  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.470  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 15:44:42.470  1296  1296 D SapProfile: Bluetooth service disconnected
08-30 15:44:42.470  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 15:44:42.470  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.470  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 15:44:42.470  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.480  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 15:44:42.480  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.480  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 15:44:42.480  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.480  2739  2739 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 15:44:42.480  2739  2739 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 15:44:42.480  2739  2739 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-30 15:44:42.480  2739  2739 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 15:44:42.480  2739  2739 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 15:44:42.480  2739  2854 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-30 15:44:42.480  2739  2739 I GKI_LINUX: GKI_exit_task 2 done
08-30 15:44:42.480  2739  2739 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 15:44:42.480  2739  2739 D BluetoothA2dp: Proxy object disconnected
08-30 15:44:42.480  2739  2739 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-30 15:44:42.480  2739  2739 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-30 15:44:42.490  2739  2739 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:42.490  2739  2739 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:42.490  2739  2739 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 15:44:42.490  2739  2739 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:42.490  2739  2739 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-30 15:44:42.490  2739  2739 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 15:44:42.490  2739  2739 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:44:42.490  2739  2739 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-30 15:44:42.490  2739  2739 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:42.490  2739  2739 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:42.490  2739  2739 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 15:44:42.490  2739  2739 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 15:44:42.490   257   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 15:44:42.490   257   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 15:44:42.490  6726  6772 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 15:44:42.510  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 15:44:42.510  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 15:44:42.520  2739  2739 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-30 15:44:42.520  2739  2739 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 15:44:42.520  2739  2739 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-30 15:44:42.520  2739  2739 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-30 15:44:42.520  2739  2739 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 15:44:42.520  2739  2739 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-30 15:44:42.520  2739  2831 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-30 15:44:42.520  2739  2831 D BluetoothAdapterProperties: Setting state to 10
08-30 15:44:42.520  2739  2831 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 15:44:42.520  2739  2831 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 15:44:42.520  2739  2831 D BluetoothAdapterService: updateAdapterState state is 10
08-30 15:44:42.520  2739  2831 D BluetoothAdapterService: Autoconnection is available 
08-30 15:44:42.520  2739  2831 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 15:44:42.520  2739  2831 I BluetoothAdapterState: Entering OffState
08-30 15:44:42.520  1426  1446 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:42.520  1426  1446 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:42.520  1296  1306 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:42.520  1296  1306 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:42.520  1455  1476 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:42.520  1455  1476 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:42.520  1440  1461 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:42.520  1440  1461 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:42.520  2739  3030 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:44:42.520  1296  1314 D BluetoothMap: onBluetoothStateChange: up=false
08-30 15:44:42.530   257   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 15:44:42.530   257   540 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 15:44:42.530  1296  1306 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 15:44:42.530  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 15:44:42.530  6615  6624 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:42.530  6615  6624 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:42.530  6615  6624 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 15:44:42.530  6726  6772 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
08-30 15:44:42.530  6615  6624 D BluetoothLeAdvertiser: Exit stop advertising
08-30 15:44:42.530  6615  6624 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 15:44:42.530  6615  6624 D BluetoothLeScanner: Exiting stopAllScan
08-30 15:44:42.530  1905  1916 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:42.530  1905  1916 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 15:44:42.540  1296  6698 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 15:44:42.540  6746  6746 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-30 15:44:42.540  2739  2751 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:42.540  2739  2751 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:42.540  6746  6746 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1057b3e9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-30 15:44:42.540  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:42.540  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:42.540  1296  1314 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:44:42.540  6746  6746 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 15:44:42.540  1175  1195 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:42.540  1175  1195 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:42.540  1296  6698 D Bluetoothsap: onBluetoothStateChange: up=false
08-30 15:44:42.540  1296  6698 D Bluetoothsap: Unbinding service...
,08-30 15:44:42.550  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:44:42.550  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-30 15:44:42.550  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 15:44:42.550  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 15:44:42.560  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 15:44:42.560  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:42.560  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 15:44:42.560  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.560  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.560  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:42.560  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:42.560  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 15:44:42.560  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 15:44:42.560  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-30 15:44:42.560  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 15:44:42.560  1905  2121 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:44:42.560  1175  1175 D HotspotTile: onReceive : 1, 0
,08-30 15:44:42.570  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:42.580  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:44:42.580  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:42.580  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:44:42.580  1015  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:42.590  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:42.590  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:42.590  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:42.590  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-30 15:44:42.590  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:42.590  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-30 15:44:42.590  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-30 15:44:42.590  6746  6746 D ChimeraCfgMgr: Reading stored module config
,08-30 15:44:42.600  1175  1175 D BluetoothAdapter: 357474663: getState() :  mService = null. Returning STATE_OFF
08-30 15:44:42.600  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 15:44:42.600  1175  1717 D BluetoothAdapter: 357474663: getState() :  mService = null. Returning STATE_OFF
,08-30 15:44:42.600  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:42.600  1175  1175 D BluetoothTile:  getBluetoothState : 10
08-30 15:44:42.600  1175  1717 D BluetoothAdapter: 357474663: getState() :  mService = null. Returning STATE_OFF
08-30 15:44:42.600  1175  1175 D BluetoothAdapter: 357474663: getState() :  mService = null. Returning STATE_OFF
08-30 15:44:42.600  1175  1175 D BluetoothAdapter: 357474663: getState() :  mService = null. Returning STATE_OFF
,08-30 15:44:42.600  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 15:44:42.600  1015  1479 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-30 15:44:42.610  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 15:44:42.610  1794  1794 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 15:44:42.610  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:42.610  1905  2121 D BluetoothAdapter: 415431216: getState() :  mService = null. Returning STATE_OFF
08-30 15:44:42.610  1905  2121 D BluetoothAdapter: 415431216: getState() :  mService = null. Returning STATE_OFF
,08-30 15:44:42.610  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:42.620  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:42.620  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 15:44:42.630  2739  2836 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 15:44:42.630  1015  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:42.630  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:42.640  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:42.640  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 15:44:42.640  2739  2739 I GKI_LINUX: GKI_exit_task 1 done
08-30 15:44:42.640  2739  2739 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-30 15:44:42.640  2739  2739 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 15:44:42.650  2739  2739 I art     : System.exit called, status: 0
08-30 15:44:42.650  2739  2739 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 15:44:42.690  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:44:42.700  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:44:42.700  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:42.700  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-30 15:44:42.700  6746  6788 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-30 15:44:42.710  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:42.730  1905  1905 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=51bb2d94-3549-4e4e-8b0c-baf7bf2ad2c8
,08-30 15:44:42.730  1015  1464 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:44:42.730  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 15:44:42.730  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:42.730  1015  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:42.730  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:42.740  6746  6746 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 15:44:42.740  1015  1678 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-30 15:44:42.740  6746  6746 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 15:44:42.740  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 15:44:42.740  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:42.740  1015  1678 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:42.740  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:42.760  1015  1027 I ActivityManager: Process com.android.bluetooth (pid 2739)(adj 0) has died(34,716)
,08-30 15:44:42.760  1905  1905 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 15:44:42.760  1905  1905 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 15:44:42.800  1015  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:42.800  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:42.800  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:42.800  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:42.850   283   283 D WVCdm   : Instantiating CDM.
,08-30 15:44:42.850   283   827 I WVCdm   : CdmEngine::OpenSession
,08-30 15:44:42.850   283   827 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-30 15:44:42.860  2623  2884 I art     : Explicit concurrent mark sweep GC freed 1407(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 719us total 31.438ms
,08-30 15:44:42.870   283   827 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-30 15:44:42.890   283   827 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-30 15:44:42.940  6726  6726 D StrictMode: StrictMode policy violation; ~duration=451 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:42.940  6726  6726 D StrictMode: StrictMode policy violation; ~duration=450 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:42.940  6726  6726 D StrictMode: StrictMode policy violation; ~duration=449 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:42.940  6726  6726 D StrictMode: StrictMode policy violation; ~duration=437 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:42.940  6726  6726 D StrictMode: StrictMode policy violation; ~duration=436 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.k.d(PG:583)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:42.940  6726  6726 D StrictMode: StrictMode policy violation; ~duration=389 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:42.940  6726  6726 D StrictMode: StrictMode policy violation; ~duration=388 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:42.940  6726  6726 D StrictMode: StrictMode policy violation; ~duration=387 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:42.940  6726  6726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:42.950  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-30 15:44:42.960  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-30 15:44:42.960   283   827 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-30 15:44:42.970   283   283 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 15:44:42.970   283   283 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 15:44:42.970   283   283 I WVCdm   : CdmEngine::GenerateKeyRequest
08-30 15:44:42.970   283   283 D WVCdm   : PrepareKeyRequest: nonce=508984636
08-30 15:44:42.980  6746  6755 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-30 15:44:42.980  6746  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 15:44:42.980  6746  6755 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 15:44:42.980  6746  6755 I System.out: (HTTPLog)-Thread-1194-206553554: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-30 15:44:42.980  6746  6755 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 15:44:42.980   278   887 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 15:44:42.980   278   887 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-30 15:44:42.980  1015  1215 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 15:44:42.980  1015  1215 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 15:44:42.980  1015  1215 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:42.980  1015  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:42.980  1015  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 15:44:42.980  1640  1640 I Hs20UtilService: Starting #8
08-30 15:44:42.980  1640  1699 I Hs20UtilService: Message received 5007
08-30 15:44:42.990  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 15:44:42.990  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 15:44:42.990  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 15:44:42.990  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 15:44:42.990  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 15:44:43.000  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 15:44:43.000  1015  1215 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:43.000  1015  1215 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:43.000  1015  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-30 15:44:43.000  1015  1215 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-30 15:44:43.000  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:43.000  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:43.000  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:43.000  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:43.010  1015  1215 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6808 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-30 15:44:43.020  1296  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 15:44:43.020  6808  6808 E Zygote  : MountEmulatedStorage()
,08-30 15:44:43.020  6808  6808 E Zygote  : v2,
08-30 15:44:43.020  6808  6808 I libpersona: KNOX_SDCARD checking this for 10102
08-30 15:44:43.020  6808  6808 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:43.020  6808  6808 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:43.030  6808  6808 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:44:43.030  6808  6808 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 15:44:43.030  1015  1042 D Tethering: interfaceRemoved wlan0
08-30 15:44:43.030  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 15:44:43.040  1015  1215 I ActivityManager: Killing 6349:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
,08-30 15:44:43.050  6808  6808 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:43.050  6808  6808 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:43.080  6808  6808 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 15:44:43.090  6726  6803 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 15:44:43.120  6823  6823 I dex2oat : ----------------------------------------------------
,08-30 15:44:43.120  6823  6823 I dex2oat : <SS>: S T A R T I N G . . .
08-30 15:44:43.120  6823  6823 I dex2oat : <SS>: Zip is absent. Canceled.
,08-30 15:44:43.120  6823  6823 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 15:44:43.120  1015  1462 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:43.120  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.120  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:43.120  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-30 15:44:43.130  1015  1042 D Tethering: interfaceRemoved p2p0
,08-30 15:44:43.130  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 15:44:43.190  6823  6823 I dex2oat : dex2oat took 68.786ms (threads: 4)
,08-30 15:44:43.200  1905  2108 W GCoreFlp: No location to return for getLastLocation()
,08-30 15:44:43.200  6746  6755 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 15:44:43.200  6746  6755 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 15:44:43.200  6746  6755 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 15:44:43.200  6746  6755 I Adreno-EGL: Local Branch: 
08-30 15:44:43.200  6746  6755 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 15:44:43.200  6746  6755 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 15:44:43.200  6746  6755 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 15:44:43.250   288   288 E SMD     : DCD OFF
,08-30 15:44:43.290   283   827 I WVCdm   : CdmEngine::OpenSession
,08-30 15:44:43.300  1905  2108 I art     : Explicit concurrent mark sweep GC freed 63424(3MB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 11MB/19MB, paused 1.430ms total 98.884ms
,08-30 15:44:43.340  4352  6695 D UdcContextInitService: registered all accounts: true
,08-30 15:44:43.350  1015  2020 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:43.350  1015  2020 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.350  1015  2020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:43.350  1015  2020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:43.360  1905  2115 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 15:44:43.360  1015  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:43.360  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:43.360  1015  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:43.360  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:43.360  1015  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:43.360  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.370  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 15:44:43.370  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:43.380  6808  6838 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-30 15:44:43.380  6808  6838 I Babel_SMS: MmsConfig.loadMmsSettings
,08-30 15:44:43.380  6808  6838 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-30 15:44:43.380  6808  6838 I Babel_SMS: MmsConfig.loadFromDatabase
,08-30 15:44:43.390  1905  2122 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-30 15:44:43.410  6808  6838 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-30 15:44:43.410  6808  6838 I Babel_SMS: MmsConfig.loadFromResources
,08-30 15:44:43.410  6808  6838 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-30 15:44:43.410  6808  6838 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-30 15:44:43.440  1015  1678 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-30 15:44:43.440  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-30 15:44:43.440  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.440  1015  1678 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:43.440  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 15:44:43.480  6808  6808 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:44:43.490  6808  6808 I Babel_Crash: startup - clean
,08-30 15:44:43.520  1015  1504 I ActivityManager: Killing 6207:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-30 15:44:43.540  6808  6808 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 15:44:43.540  6808  6808 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 15:44:43.560  6808  6808 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 15:44:43.560  6808  6808 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-30 15:44:43.560  6808  6808 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-30 15:44:43.570  6808  6808 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-30 15:44:43.570  6808  6808 W AudioCapabilities: Unsupported mime audio/x-ima
,08-30 15:44:43.570  6808  6808 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 15:44:43.570  6808  6808 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 15:44:43.580  6808  6808 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 15:44:43.580  6808  6808 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 15:44:43.590  6808  6808 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-30 15:44:43.590  6808  6808 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 15:44:43.590  6808  6808 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 15:44:43.610  6808  6808 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-30 15:44:43.610  6808  6808 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-30 15:44:43.610  6808  6808 W VideoCapabilities: Unsupported mime video/mp43
,08-30 15:44:43.610  6808  6808 W VideoCapabilities: Unsupported mime video/sorenson
,08-30 15:44:43.620  6808  6808 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 15:44:43.630  6808  6808 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 15:44:43.660  6808  6808 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 15:44:43.660  6808  6808 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 15:44:43.660  6808  6808 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 15:44:43.670  1015  1028 I art     : Explicit concurrent mark sweep GC freed 52259(2MB) AllocSpace objects, 8(176KB) LOS objects, 33% free, 24MB/36MB, paused 2.407ms total 154.095ms
,08-30 15:44:43.670  6808  6808 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 15:44:43.670  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 15:44:43.670  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 15:44:43.670  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 15:44:43.680  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 15:44:43.680  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 15:44:43.680  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 15:44:43.680  6808  6808 I vclib   : onServiceConnected
,08-30 15:44:43.680  1015  2020 I ActivityManager: Killing 6364:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-30 15:44:43.680  1015  2020 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-30 15:44:43.680  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:43.680  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:43.680  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:43.680  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:43.690  1296  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 15:44:43.700  6843  6843 E Zygote  : MountEmulatedStorage()
08-30 15:44:43.700  6843  6843 E Zygote  : v2
08-30 15:44:43.700  6843  6843 I libpersona: KNOX_SDCARD checking this for 10064
08-30 15:44:43.700  6843  6843 I libpersona: KNOX_SDCARD not a persona
08-30 15:44:43.700  6843  6843 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 15:44:43.700  1015  2020 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6843 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:44:43.700  6843  6843 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 15:44:43.700  6843  6843 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:43.720  1905  2122 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-30 15:44:43.720  6843  6843 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:43.720  6843  6843 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:43.740  6843  6843 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 15:44:43.750  6843  6843 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 15:44:43.750  6843  6843 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 15:44:43.760  1905  2122 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,08-30 15:44:43.770  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-30 15:44:43.780  6843  6843 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 15:44:43.790  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-30 15:44:43.790  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:43.790  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:43.790  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:43.790  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:43.800  6859  6859 E Zygote  : MountEmulatedStorage()
,08-30 15:44:43.800  6859  6859 E Zygote  : v2
08-30 15:44:43.800  1015  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6859 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:44:43.800  6859  6859 I libpersona: KNOX_SDCARD checking this for 10065
08-30 15:44:43.800  6859  6859 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:43.800  6859  6859 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:43.810  6859  6859 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 15:44:43.810  6859  6859 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 15:44:43.810  1015  1477 I ActivityManager: Killing 5854:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-30 15:44:43.820   307   307 I art     : Explicit concurrent mark sweep GC freed 8681(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 23.322ms
,08-30 15:44:43.830  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-30 15:44:43.830  6859  6859 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:43.830  6859  6859 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:43.840   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 17.262ms
,08-30 15:44:43.850  6859  6859 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 15:44:43.860   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 16.985ms
,08-30 15:44:43.860  1015  1462 I ActivityManager: Killing 5641:com.android.vending/u0a26 (adj 15): empty #21
,08-30 15:44:43.870  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 15:44:43.870  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 15:44:43.870  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:43.870  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.870  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 15:44:43.870  1640  1640 I Hs20UtilService: Starting #9
,08-30 15:44:43.870  1640  1699 I Hs20UtilService: Message received 5007
,08-30 15:44:43.870  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 15:44:43.880  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 15:44:43.880  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 15:44:43.880  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 15:44:43.880  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 15:44:43.880  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 15:44:43.880  1296  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 15:44:43.880  1015  1678 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 15:44:43.880  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 15:44:43.880  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:43.880  1015  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.880  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 15:44:43.880  1640  1640 I Hs20UtilService: Starting #10
08-30 15:44:43.880  1640  1699 I Hs20UtilService: Message received 5011
,08-30 15:44:43.890  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 15:44:43.890  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 15:44:43.890  6484  6484 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 15:44:43.890  6484  6484 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 15:44:43.900  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.900  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.900  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.900  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.900  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.900  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.910  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.910  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.910  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.910  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.910  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.910  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.910  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:43.910  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.910  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.920  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:43.920  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.920  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.920  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.920  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.920  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.920  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.920  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.920  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.930  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.930  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.930  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.930  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.930  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.930  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.930  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.930  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.930  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.930  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.930  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.930  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.940  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.940  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.940  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.940  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:43.940  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.940  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.940  1015  1015 W ActivityManager: userId = 0, bbcId = -10000,
08-30 15:44:43.940  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.940  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 15:44:43.950  1015  1678 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 15:44:43.950  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 15:44:43.950  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.950  1015  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.950  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 15:44:43.950  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 15:44:43.950  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 15:44:43.950  6484  6484 D SecurityLogAgent: StateMachine : Current State = 1
08-30 15:44:43.950  6484  6484 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 15:44:43.950  1640  1640 I Hs20UtilService: Starting #11
,08-30 15:44:43.950  1640  1699 I Hs20UtilService: Message received 5011
,08-30 15:44:43.970  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:44:43.970  1015  1504 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 15:44:43.970  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 15:44:43.970  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:43.970  1015  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:43.970  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 15:44:43.980  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:44:43.980  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 15:44:43.980  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:43.980  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 15:44:43.990  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-30 15:44:43.990  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:43.990  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:43.990  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:43.990  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.010  6875  6875 E Zygote  : MountEmulatedStorage()
,08-30 15:44:44.010  6875  6875 E Zygote  : v2
08-30 15:44:44.010  6875  6875 I libpersona: KNOX_SDCARD checking this for 1002
08-30 15:44:44.010  6875  6875 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:44.010  6875  6875 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:44.010  1015  1027 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6875 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-30 15:44:44.010  6875  6875 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 15:44:44.010  6875  6875 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:44.030  6875  6875 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:44.030  6875  6875 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:44.050  6875  6875 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 15:44:44.050  6875  6875 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 15:44:44.070  6875  6875 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 15:44:44.100  6875  6875 D BtSettings.ProfileConfig: Adding GattService
,08-30 15:44:44.110  6875  6875 D BtSettings.ProfileConfig: Adding HeadsetService
,08-30 15:44:44.110  6875  6875 D BtSettings.ProfileConfig: Adding A2dpService
08-30 15:44:44.110  6875  6875 D BtSettings.ProfileConfig: Adding HidService
,08-30 15:44:44.110  6875  6875 D BtSettings.ProfileConfig: Adding HealthService
,08-30 15:44:44.110  6875  6875 D BtSettings.ProfileConfig: Adding PanService
08-30 15:44:44.110  6875  6875 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-30 15:44:44.110  6875  6875 D BtSettings.ProfileConfig: Adding SapService
08-30 15:44:44.110  6875  6875 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-30 15:44:44.110  6875  6875 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-30 15:44:44.110  6875  6875 D BtSettings.ProfileConfig: Adding SapClientService
08-30 15:44:44.110  6875  6875 D BtSettings.ProfileConfig: Adding HidDevService
,08-30 15:44:44.110  6875  6875 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-30 15:44:44.110  1015  1464 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-30 15:44:44.110  1015  1464 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:44.110  1015  1464 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:44.110  1015  1464 D SettingsProvider: selectionArgs: false
08-30 15:44:44.110  1015  1464 D SettingsProvider: selectionArgs: 1002
08-30 15:44:44.110  1015  1464 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:44.110  1015  1464 D SettingsProvider: ret = -1
,08-30 15:44:44.110  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-30 15:44:44.110  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:44.110  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:44.110  1015  1133 D SettingsProvider: selectionArgs: false
08-30 15:44:44.110  1015  1133 D SettingsProvider: selectionArgs: 1002
08-30 15:44:44.110  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:44.110  1015  1133 D SettingsProvider: ret = -1
,08-30 15:44:44.110  1015  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-30 15:44:44.110  1015  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:44.110  1015  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:44.110  1015  1477 D SettingsProvider: selectionArgs: false
08-30 15:44:44.110  1015  1477 D SettingsProvider: selectionArgs: 1002
08-30 15:44:44.110  1015  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:44.110  1015  1477 D SettingsProvider: ret = -1
,08-30 15:44:44.120  1015  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-30 15:44:44.120  1015  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:44.120  1015  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:44.120  1015  1480 D SettingsProvider: selectionArgs: false
08-30 15:44:44.120  1015  1480 D SettingsProvider: selectionArgs: 1002
08-30 15:44:44.120  1015  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:44.120  1015  1480 D SettingsProvider: ret = -1
,08-30 15:44:44.120  1015  1504 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-30 15:44:44.120  1015  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:44.120  1015  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:44.120  1015  1504 D SettingsProvider: selectionArgs: false
08-30 15:44:44.120  1015  1504 D SettingsProvider: selectionArgs: 1002
08-30 15:44:44.120  1015  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:44.120  1015  1504 D SettingsProvider: ret = -1
,08-30 15:44:44.120  1015  2020 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-30 15:44:44.120  1015  2020 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 15:44:44.120  1015  2020 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:44.120  1015  2020 D SettingsProvider: selectionArgs: false
08-30 15:44:44.120  1015  2020 D SettingsProvider: selectionArgs: 1002
,08-30 15:44:44.120  1015  2020 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:44.120  1015  2020 D SettingsProvider: ret = -1
,08-30 15:44:44.120  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-30 15:44:44.120  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:44.120  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:44.120  1015  1028 D SettingsProvider: selectionArgs: false
08-30 15:44:44.120  1015  1028 D SettingsProvider: selectionArgs: 1002
08-30 15:44:44.120  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:44.120  1015  1028 D SettingsProvider: ret = -1
,08-30 15:44:44.120  1015  1027 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-30 15:44:44.120  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:44.120  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 15:44:44.120  1015  1027 D SettingsProvider: selectionArgs: false
08-30 15:44:44.120  1015  1027 D SettingsProvider: selectionArgs: 1002
08-30 15:44:44.120  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:44.120  1015  1027 D SettingsProvider: ret = -1
,08-30 15:44:44.120  1015  1462 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:44:44.120  1015  1462 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:44.120  1015  1462 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:44.120  1015  1462 D SettingsProvider: selectionArgs: false
08-30 15:44:44.120  1015  1462 D SettingsProvider: selectionArgs: 1002
08-30 15:44:44.120  1015  1462 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:44.120  1015  1462 D SettingsProvider: ret = -1
,08-30 15:44:44.120  1015  1409 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:44.120  1015  1409 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:44.120  1015  1409 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 15:44:44.120  1015  1409 D SettingsProvider: selectionArgs: false
08-30 15:44:44.120  1015  1409 D SettingsProvider: selectionArgs: 1002
08-30 15:44:44.120  1015  1409 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:44.120  1015  1409 D SettingsProvider: ret = -1
,08-30 15:44:44.120  1015  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-30 15:44:44.120  1015  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:44.120  1015  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 15:44:44.120  1015  1479 D SettingsProvider: selectionArgs: false
08-30 15:44:44.120  1015  1479 D SettingsProvider: selectionArgs: 1002
08-30 15:44:44.120  1015  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 15:44:44.130  1015  1479 D SettingsProvider: ret = -1
,08-30 15:44:44.130  1015  1215 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-30 15:44:44.130  1015  1215 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:44.130  1015  1215 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:44.130  1015  1215 D SettingsProvider: selectionArgs: false
08-30 15:44:44.130  1015  1215 D SettingsProvider: selectionArgs: 1002
08-30 15:44:44.130  1015  1215 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:44.130  1015  1215 D SettingsProvider: ret = -1
,08-30 15:44:44.140  1015  1678 I ActivityManager: Killing 6403:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-30 15:44:44.140  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 15:44:44.140  1015  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 15:44:44.140  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 15:44:44.140  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:44.140  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 15:44:44.140  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:44.150  1905  6891 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 15:44:44.150  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 15:44:44.150  1015  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 15:44:44.150  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.150  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.150  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.150  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.170  6892  6892 E Zygote  : MountEmulatedStorage(),
08-30 15:44:44.170  6892  6892 E Zygote  : v2
08-30 15:44:44.170  6892  6892 I libpersona: KNOX_SDCARD checking this for 1000
08-30 15:44:44.170  6892  6892 I libpersona: KNOX_SDCARD not a persona,
08-30 15:44:44.170  6892  6892 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:44.170  6892  6892 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 15:44:44.170  6892  6892 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-30 15:44:44.170  1015  1479 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6892 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 15:44:44.170  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:44.170  1015  1462 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 15:44:44.170  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:44.170  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:44.180  1015  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-30 15:44:44.190  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:44.190  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:44.190  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:44.190  1905  6891 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-30 15:44:44.210  6892  6892 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:44.210  6892  6892 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:44.230  6892  6892 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-30 15:44:44.230  6892  6892 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 15:44:44.230  6892  6892 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 15:44:44.240  6892  6892 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-30 15:44:44.240  6892  6892 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 15:44:44.240  6892  6892 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 15:44:44.240  6892  6892 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:44:44.250  1015  1133 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29,
08-30 15:44:44.250  6892  6907 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-30 15:44:44.250  1015  1133 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-30 15:44:44.260  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-30 15:44:44.260  1924  1924 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 15:44:44.260  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.260  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.260  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.260  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.270  6909  6909 E Zygote  : MountEmulatedStorage(),
08-30 15:44:44.270  6909  6909 E Zygote  : v2
08-30 15:44:44.270  6909  6909 I libpersona: KNOX_SDCARD checking this for 10121
,08-30 15:44:44.270  6909  6909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 15:44:44.270  6909  6909 I libpersona: KNOX_SDCARD not a persona
08-30 15:44:44.280  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6909 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,08-30 15:44:44.280  1015  1678 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-30 15:44:44.280  6909  6909 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 15:44:44.280  1015  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.280  1015  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.280  1015  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.280  1015  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.280  6909  6909 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:44.290  6922  6922 E Zygote  : MountEmulatedStorage(),
08-30 15:44:44.290  6922  6922 E Zygote  : v2
08-30 15:44:44.290  6922  6922 I libpersona: KNOX_SDCARD checking this for 10031
08-30 15:44:44.290  6922  6922 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:44.300  6909  6909 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 15:44:44.300  6922  6922 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 15:44:44.300  6909  6909 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:44.300  1015  1678 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6922 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-30 15:44:44.300  6922  6922 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:44:44.300  6922  6922 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:44.300  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
08-30 15:44:44.300  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.300  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.300  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.300  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.310  2648  2660 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-30 15:44:44.320  6937  6937 E Zygote  : MountEmulatedStorage()
08-30 15:44:44.320  6937  6937 I libpersona: KNOX_SDCARD checking this for 10001
08-30 15:44:44.320  6937  6937 E Zygote  : v2
08-30 15:44:44.320  6937  6937 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:44.320  6937  6937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:44.320  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6937 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 15:44:44.320  6922  6922 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:44.320  6922  6922 D ActivityThread: Added TimaKeyStore provider
08-30 15:44:44.320  6937  6937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:44:44.330  6937  6937 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:44.330  1924  1924 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-30 15:44:44.330  1924  1924 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-30 15:44:44.330  1924  1924 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-30 15:44:44.330  1924  1924 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-30 15:44:44.340  6909  6909 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:44:44.340  6909  6909 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 15:44:44.340  6909  6909 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 15:44:44.350  1924  1924 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 15:44:44.350  6937  6937 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:44.350  1924  1924 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
08-30 15:44:44.350  6937  6937 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:44.350  1015  1462 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-30 15:44:44.360  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.360  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.360  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.360  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.370  6909  6909 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
08-30 15:44:44.370  1015  1462 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6954 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 15:44:44.370  6954  6954 E Zygote  : MountEmulatedStorage()
08-30 15:44:44.370  6954  6954 I libpersona: KNOX_SDCARD checking this for 10077
08-30 15:44:44.370  6954  6954 E Zygote  : v2
08-30 15:44:44.370  6954  6954 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:44.370  6954  6954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:44.370  6954  6954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:44:44.380  6954  6954 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-30 15:44:44.380  6909  6909 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-30 15:44:44.380  6922  6922 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-30 15:44:44.390  6909  6909 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-30 15:44:44.390  1015  1133 I ActivityManager: Killing 5931:com.samsung.android.sm/1000 (adj 15): empty #21
,08-30 15:44:44.390  1015  1133 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-30 15:44:44.390  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.390  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.390  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.390  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.400  6954  6954 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:44.410  6954  6954 D ActivityThread: Added TimaKeyStore provider
08-30 15:44:44.410  6969  6969 I libpersona: KNOX_SDCARD checking this for 10141
08-30 15:44:44.410  6969  6969 E Zygote  : MountEmulatedStorage()
08-30 15:44:44.410  6969  6969 I libpersona: KNOX_SDCARD not a persona
08-30 15:44:44.410  6969  6969 E Zygote  : v2
,08-30 15:44:44.410  6969  6969 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:44.410  6969  6969 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 15:44:44.410  1015  1133 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6969 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-30 15:44:44.410  6969  6969 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:44.410  1015  1133 I ActivityManager: Killing 6431:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-30 15:44:44.420  1015  1678 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-30 15:44:44.420  1015  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.420  1015  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.420  1015  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.420  1015  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.440  6985  6985 E Zygote  : MountEmulatedStorage(),
08-30 15:44:44.440  1015  1678 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6985 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 15:44:44.440  6985  6985 E Zygote  : v2,
08-30 15:44:44.440  6985  6985 I libpersona: KNOX_SDCARD checking this for 10032,
08-30 15:44:44.440  6985  6985 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 15:44:44.440  6985  6985 I libpersona: KNOX_SDCARD not a persona,
08-30 15:44:44.440  3464  6977 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
08-30 15:44:44.440  6969  6969 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:44.440  3464  6977 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
08-30 15:44:44.440  6969  6969 D ActivityThread: Added TimaKeyStore provider
08-30 15:44:44.440  3464  6977 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-30 15:44:44.450  3464  6977 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-30 15:44:44.450  6985  6985 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:44:44.450  3464  6977 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-30 15:44:44.450  6985  6985 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-30 15:44:44.480  6985  6985 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:44.490  6985  6985 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:44.490  6969  6969 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-30 15:44:44.490  6969  6969 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 15:44:44.490  6969  6969 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 15:44:44.490  6969  6969 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 15:44:44.510  1015  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-30 15:44:44.520  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.520  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.520  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.520  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.530  1015  1480 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7003 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-30 15:44:44.530  1015  1480 I ActivityManager: Killing 6453:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21,
08-30 15:44:44.530  7003  7003 E Zygote  : MountEmulatedStorage(),
08-30 15:44:44.530  7003  7003 E Zygote  : v2
08-30 15:44:44.530  7003  7003 I libpersona: KNOX_SDCARD checking this for 1000
08-30 15:44:44.530  7003  7003 I libpersona: KNOX_SDCARD not a persona,
,08-30 15:44:44.540  7003  7003 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 15:44:44.540  7003  7003 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 15:44:44.540  7003  7003 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:44.550  1015  1479 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 15:44:44.560  7003  7003 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:44.560  7003  7003 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:44.570  1015  1464 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 15:44:44.590  6985  7021 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-30 15:44:44.590  6985  7021 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-30 15:44:44.600  6985  6985 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-30 15:44:44.600  1015  1479 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-30 15:44:44.600  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-30 15:44:44.600  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:44.610  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:44.610  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 15:44:44.610  6985  7021 D SPPClientService: PushLog.txt file is not deleted.
08-30 15:44:44.610  6985  7021 D SPPClientService: PushLog.txt file is not deleted.
08-30 15:44:44.610  6985  7021 D SPPClientService: ============PushLog. stop!
,08-30 15:44:44.610  1015  2020 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-30 15:44:44.610  1015  2020 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-30 15:44:44.610  1015  2020 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:44.610  1015  2020 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-30 15:44:44.610  1015  2020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-30 15:44:44.610   283  6841 I WVCdm   : CdmEngine::CloseSession
,08-30 15:44:44.620  1015  1462 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-30 15:44:44.620  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.620  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.620  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.620  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.630  6503  6503 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-30 15:44:44.630  6503  6503 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-30 15:44:44.630  6503  6503 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-30 15:44:44.630  1015  1479 D RCPManagerService: exchangeData() failure , invalid userId,
08-30 15:44:44.630  7003  7003 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-30 15:44:44.630  6503  6503 I SA      : [SLFUCHKMGR] constructor called,
,08-30 15:44:44.650  7031  7031 E Zygote  : MountEmulatedStorage(),
08-30 15:44:44.650  7031  7031 E Zygote  : v2
08-30 15:44:44.650  7031  7031 I libpersona: KNOX_SDCARD checking this for 10110
08-30 15:44:44.650  7031  7031 I libpersona: KNOX_SDCARD not a persona
08-30 15:44:44.650  7031  7031 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 15:44:44.650  1015  1462 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7031 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:44:44.650  7031  7031 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 15:44:44.650  7031  7031 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 15:44:44.660  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-30 15:44:44.660  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-30 15:44:44.660  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:44.660  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:44.660  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 15:44:44.660  6808  7026 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-30 15:44:44.670  6503  6503 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-30 15:44:44.670  6503  6503 I SA      : [OR] == isSIMCardReady false ==
,08-30 15:44:44.670  6985  7025 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-30 15:44:44.670  6503  6503 I SA      : [SCU] == networkStateCheck == false
,08-30 15:44:44.680  1015  1464 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 15:44:44.680  7031  7031 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:44.680  7031  7031 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:44.680  6503  6503 I SA      : [OR] onReceive END
,08-30 15:44:44.690   283   827 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 15:44:44.690   283   827 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 15:44:44.690   283   827 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 15:44:44.690   283   827 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-30 15:44:44.690  1015  1504 I ActivityManager: Killing 6520:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-30 15:44:44.700  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:44:44.710  1015  1215 I ActivityManager: Killing 6471:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-30 15:44:44.710   283   827 D WVCdm   : PrepareKeyRequest: nonce=2217937145
,08-30 15:44:44.750  1015  1480 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-30 15:44:44.750  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.750  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.750  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.750  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.770  7049  7049 E Zygote  : MountEmulatedStorage(),
08-30 15:44:44.770  7049  7049 E Zygote  : v2
08-30 15:44:44.770  7049  7049 I libpersona: KNOX_SDCARD checking this for 10068,
08-30 15:44:44.770  7049  7049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 15:44:44.770  7049  7049 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:44.770  7049  7049 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 15:44:44.770  1015  1480 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7049 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
08-30 15:44:44.770  7049  7049 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-30 15:44:44.770  7003  7003 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,08-30 15:44:44.780  7003  7003 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,08-30 15:44:44.790  7049  7049 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:44.790  7003  7003 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
08-30 15:44:44.790  7049  7049 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:44.790  7003  7003 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
08-30 15:44:44.790  7003  7003 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
08-30 15:44:44.790  7003  7003 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-30 15:44:44.800  1015  1464 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-30 15:44:44.800  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.800  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.800  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.800  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.800   307   307 I art     : Explicit concurrent mark sweep GC freed 8711(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 673us total 30.258ms
,08-30 15:44:44.820  1015  1504 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 15:44:44.820   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 742us total 17.107ms
,08-30 15:44:44.820  1015  1477 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 15:44:44.830  1015  1027 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 15:44:44.830  7049  7049 D BadgeProvider: onCreate
,08-30 15:44:44.830  7049  7049 D BadgeProvider: DatabaseHelper
,08-30 15:44:44.840   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 18.228ms
,08-30 15:44:44.850  7065  7065 E Zygote  : MountEmulatedStorage(),
08-30 15:44:44.850  7065  7065 E Zygote  : v2
08-30 15:44:44.850  7065  7065 I libpersona: KNOX_SDCARD checking this for 10008
,08-30 15:44:44.850  7065  7065 I libpersona: KNOX_SDCARD not a persona
08-30 15:44:44.850  7065  7065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-30 15:44:44.850  1015  1464 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7065 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:44:44.850  7065  7065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 15:44:44.850  1015  1464 I ActivityManager: Killing 6542:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-30 15:44:44.850  7065  7065 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 15:44:44.870  1015  1678 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 15:44:44.870  1015  1678 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-30 15:44:44.870  1015  1678 D SecContentProvider2: mCursor = null
,08-30 15:44:44.870  1015  1678 D WifiService: setWifiEnabled: true pid=6615, uid=10171
,08-30 15:44:44.870  1015  1678 W ActivityManager: Permission Denial: getCurrentUser() from pid=6615, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-30 15:44:44.870  1015  1678 W WifiService: Failed getting userId using ActivityManagerNative
08-30 15:44:44.870  1015  1678 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6615, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-30 15:44:44.870  1015  1678 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 15:44:44.870  1015  1678 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 15:44:44.870  1015  1678 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 15:44:44.870  1015  1678 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 15:44:44.870  1015  1678 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 15:44:44.870  7049  7058 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-30 15:44:44.870  1015  1678 D SettingsProvider: name = wifi_on
,08-30 15:44:44.880  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 15:44:44.890  7065  7065 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:44.890  7065  7065 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:44.910  1015  1462 D RCPManagerService: exchangeData() failure , invalid userId,
,08-30 15:44:44.920  1015  1464 D RCPManagerService: exchangeData() failure , invalid userId,
08-30 15:44:44.920  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-30 15:44:44.930  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.930  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.930  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:44.930  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:44.930  7049  7058 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1,
08-30 15:44:44.930  7049  7058 D BadgeProvider: sendNotify, [notify] : null
08-30 15:44:44.930  7049  7058 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,08-30 15:44:44.930  7049  7058 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-30 15:44:44.930  7049  7058 D BadgeProvider: update, [UpdateCount] : 1
,08-30 15:44:44.940  1481  1481 D Launcher.Model: reloadBadges entered.
,08-30 15:44:44.960  1015  1028 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7081 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,08-30 15:44:44.960  1015  1028 I ActivityManager: Killing 6561:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-30 15:44:44.960  1015  1028 I ActivityManager: Killing 5919:com.android.mms/u0a41 (adj 15): empty #22
,08-30 15:44:44.960  7081  7081 E Zygote  : MountEmulatedStorage(),
08-30 15:44:44.960  7081  7081 E Zygote  : v2
08-30 15:44:44.960  7081  7081 I libpersona: KNOX_SDCARD checking this for 10009
08-30 15:44:44.960  7081  7081 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:44.960  7081  7081 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:44.970  7081  7081 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 15:44:44.970  7081  7081 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-30 15:44:45.010  7081  7081 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:45.010  7081  7081 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:45.040  1015  1464 D CountryDetector: No listener is left
,08-30 15:44:45.110  1015  1464 I ActivityManager: Killing 6579:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-30 15:44:45.120  1015  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 15:44:45.120  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-30 15:44:45.120  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:45.120  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:45.120  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:45.130  4352  4352 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 15:44:45.130  4352  4805 I iu.UploadsManager: num queued entries: 0
,08-30 15:44:45.130  4352  4805 I iu.UploadsManager: num updated entries: 0
,08-30 15:44:45.130  4352  4805 I iu.SyncManager: NEXT; no task
,08-30 15:44:45.160  1015  1028 I ActivityManager: Killing 6413:com.android.calendar/u0a131 (adj 15): empty #21
,08-30 15:44:45.160  3927  3927 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 15:44:45 GMT+02:00 2016
,08-30 15:44:45.170  1015  1462 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 15:44:45.170  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 15:44:45.170  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:45.170  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:45.170  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 15:44:45.170   257   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 15:44:45.180   257   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 15:44:45.180  7031  7101 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 15:44:45.180   257   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 15:44:45.180   257   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 15:44:45.180  7031  7101 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-30 15:44:45.180  3927  3927 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-30 15:44:45.190  7031  7031 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 15:44:45.190  7031  7031 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 15:44:45.190  7031  7031 I GAv4    :   adb logcat -s GAv4
,08-30 15:44:45.200  3927  3927 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-30 15:44:45.200  3927  3927 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 15:44:45.210   257   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 15:44:45.210   257   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 15:44:45.210  7031  7110 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 15:44:45.210  3927  3927 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 15:44:45.210  3927  7109 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 15:44:45.210   257   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 15:44:45.210   257   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 15:44:45.220  7031  7110 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-30 15:44:45.220  3927  7109 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-30 15:44:45.220  1015  2020 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-30 15:44:45.220  1015  2020 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-30 15:44:45.220  7031  7031 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 15:44:45.220  1015  1480 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
08-30 15:44:45.220  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-30 15:44:45.220  3927  7109 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-30 15:44:45.220  1015  2020 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-30 15:44:45.220   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 15:44:45.230  3927  7109 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-30 15:44:45.230  3927  3927 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-30 15:44:45.230  7031  7031 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 15:44:45.240  7031  7112 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 15:44:45.310  1015  1042 D Tethering: interfaceAdded wlan0
,08-30 15:44:45.320  1015  1128 E Tethering: No numeric data
,08-30 15:44:45.320  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 15:44:45.320  1015  1128 D Tethering: clearTetheredNotification()
,08-30 15:44:45.320  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-30 15:44:45.320  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:45.320  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:44:45.330  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 15:44:45.320  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 15:44:45.330  1175  1175 D HotspotTile: updateTetherState():false, false
08-30 15:44:45.330  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:45.330  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:44:45.330  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 15:44:45.330  1015  1122 V NetworkStats: performPollLocked() took 5ms
08-30 15:44:45.330  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:45.330  1015  1128 D Tethering: InitialState.processMessage what=4
,08-30 15:44:45.330  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:45.330  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:45.330  1015  1128 E Tethering: No numeric data
,08-30 15:44:45.330  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 15:44:45.330  1015  1128 D Tethering: clearTetheredNotification()
,08-30 15:44:45.330  1015  1042 D Tethering: interfaceAdded p2p0
,08-30 15:44:45.340  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:45.340  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-30 15:44:45.340  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-30 15:44:45.340   278   894 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-30 15:44:45.340  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:44:45.340  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 15:44:45.340   278   894 D SoftapController: Softap fwReload - Ok
,08-30 15:44:45.340  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 15:44:45.340  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 15:44:45.340  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 15:44:45.340  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 15:44:45.340  1175  1175 D HotspotTile: updateTetherState():false, false
,08-30 15:44:45.340   278   894 D CommandListener: Setting iface cfg
08-30 15:44:45.340   278   894 D CommandListener: Trying to bring down wlan0
,08-30 15:44:45.340  1015  1122 V NetworkStats: performPollLocked() took 5ms
08-30 15:44:45.340  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:45.340   278   894 D CommandListener: Clearing all IP addresses on wlan0
,08-30 15:44:45.340  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:45.340  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:45.350  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-30 15:44:45.390  7126  7126 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-30 15:44:45.390  7126  7126 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 15:44:45.390  7126  7126 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 15:44:45.410  7126  7126 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-30 15:44:45.410   377   377 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7126,
08-30 15:44:45.410   377   377 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-30 15:44:45.410  7126  7126 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-30 15:44:45.410  7126  7126 I wpa_supplicant: ssSupport state is = 1
08-30 15:44:45.410  7126  7126 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
08-30 15:44:45.410  7126  7126 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-30 15:44:45.410   377   377 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7126,
08-30 15:44:45.410   377   377 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-30 15:44:45.440  1015  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
08-30 15:44:45.440  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:45.440  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:45.440  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-30 15:44:45.450  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 15:44:45.460  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 15:44:45.460  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 15:44:45.460  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:45.460  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:45.460  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:45.460  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:45.460  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 15:44:45.460  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-30 15:44:45.460  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:45.460  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 15:44:45.460  1175  1175 D HotspotTile: onReceive : 2, 0
,08-30 15:44:45.470  7031  7031 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-30 15:44:45.470  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:45.470  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:45.470  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:45.490  7031  7031 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 4392-4394),
08-30 15:44:45.490  7031  7031 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-30 15:44:45.500  7031  7031 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {24341e34}
,08-30 15:44:45.500  7031  7031 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-30 15:44:45.500  7031  7031 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 15:44:45.520  7031  7031 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-30 15:44:45.520  7031  7031 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:44:45.530  7031  7031 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 15:44:45.540  7031  7031 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 15:44:45.540  7031  7031 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 15:44:45.540  7031  7031 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 15:44:45.540  7031  7031 I Adreno-EGL: Local Branch: 
08-30 15:44:45.540  7031  7031 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 15:44:45.540  7031  7031 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 15:44:45.540  7031  7031 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 15:44:45.600   377   377 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-30 15:44:45.600  7126  7126 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-30 15:44:45.630  7031  7143 W cr.media: Requires BLUETOOTH permission
,08-30 15:44:45.630  7031  7031 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 15:44:45.640  7031  7031 I NSApplication: Starting up...
,08-30 15:44:45.640  1015  1462 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 15:44:45.650  7126  7126 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 15:44:45.650  7126  7126 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-30 15:44:45.650  1015  1215 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 15:44:45.660  1015  1462 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-30 15:44:45.660  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:45.660  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:45.660  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:45.660  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:45.660  7126  7126 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-30 15:44:45.660   377   377 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7126
08-30 15:44:45.660   377   377 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-30 15:44:45.660  7126  7126 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-30 15:44:45.660  7126  7126 I wpa_supplicant: ssSupport state is = 1
,08-30 15:44:45.660  7126  7126 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 15:44:45.670  7126  7126 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 15:44:45.670  7126  7126 E wpa_supplicant: SIM READ ERROR,
08-30 15:44:45.670  7126  7126 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 15:44:45.670  7126  7126 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 15:44:45.670  7126  7126 E wpa_supplicant: SIM READ ERROR
08-30 15:44:45.670  7126  7126 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 15:44:45.670  7126  7126 I wpa_supplicant: wpa_default_ap_write_once
08-30 15:44:45.670  7126  7126 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 15:44:45.670  7126  7126 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 15:44:45.670  7126  7126 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 15:44:45.670  7126  7126 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-30 15:44:45.670  7126  7126 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 15:44:45.670  7126  7126 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 15:44:45.670  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:45.670  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 15:44:45.670  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:44:45.670  7149  7149 E Zygote  : MountEmulatedStorage()
08-30 15:44:45.670  7149  7149 E Zygote  : v2
08-30 15:44:45.670  7149  7149 I libpersona: KNOX_SDCARD checking this for 10117
08-30 15:44:45.670  7149  7149 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:45.670  7149  7149 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:45.670  1015  1462 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7149 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,08-30 15:44:45.680  7149  7149 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 15:44:45.680  1015  1462 I ActivityManager: Killing 6843:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
08-30 15:44:45.680  7149  7149 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 15:44:45.700  7149  7149 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:45.700  7149  7149 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:45.710  7149  7149 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 15:44:45.720  7126  7126 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-30 15:44:45.800  1905  2122 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-30 15:44:45.800  1905  2122 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-30 15:44:45.880  7126  7126 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-30 15:44:45.880  7126  7126 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-30 15:44:45.900  7126  7126 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-30 15:44:45.900   377   377 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7126
08-30 15:44:45.900   377   377 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-30 15:44:45.900  7126  7126 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-30 15:44:45.900  7126  7126 I wpa_supplicant: ssSupport state is = 1
,08-30 15:44:45.900  7126  7126 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-30 15:44:45.900  7126  7126 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-30 15:44:45.910  7126  7126 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-30 15:44:45.910   377   377 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7126
08-30 15:44:45.910   377   377 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-30 15:44:45.910  7126  7126 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-30 15:44:45.910  7126  7126 I wpa_supplicant: ssSupport state is = 1
08-30 15:44:45.910  7126  7126 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-30 15:44:45.910  7126  7126 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 15:44:45.910  7126  7126 E wpa_supplicant: SIM READ ERROR
08-30 15:44:45.910  7126  7126 I wpa_supplicant: wpa_default_ap_write_once
08-30 15:44:45.910  7126  7126 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-30 15:44:45.910  7126  7126 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 15:44:45.910  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 15:44:45.910  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 15:44:45.910  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 15:44:45.920  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 15:44:45.920  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 15:44:45.920  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 15:44:46.000  7126  7126 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-30 15:44:46.000  7126  7126 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 15:44:46.060  1015  2020 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-30 15:44:46.060  1015  2020 I ActivityManager: Killing 6859:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-30 15:44:46.070  1015  1678 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 15:44:46.070  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 15:44:46.070  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:46.070  1015  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 15:44:46.070  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 15:44:46.070  1640  1640 I Hs20UtilService: Starting #12
,08-30 15:44:46.070  1640  1699 I Hs20UtilService: Message received 5011
,08-30 15:44:46.070  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 15:44:46.070  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 15:44:46.070  6484  6484 D SecurityLogAgent: StateMachine : Current State = 1
08-30 15:44:46.070  6484  6484 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 15:44:46.080  7126  7126 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-30 15:44:46.080  7126  7126 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-30 15:44:46.080  7126  7126 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 15:44:46.090  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-30 15:44:46.090  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-30 15:44:46.100  7126  7126 I wpa_supplicant: HOTSPOT20_ENABLE called
08-30 15:44:46.100  7126  7126 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 15:44:46.100  7126  7126 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 15:44:46.100  7126  7126 E wpa_supplicant: SIM READ ERROR
08-30 15:44:46.100  7126  7126 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 15:44:46.110  7126  7126 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-30 15:44:46.120  7126  7126 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 15:44:46.120  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
,08-30 15:44:46.120  1015  1125 E WifiConfigStore: Not a HS20
,08-30 15:44:46.120  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 15:44:46.130  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 15:44:46.130  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 15:44:46.130  7126  7126 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 15:44:46.130  7126  7126 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-30 15:44:46.130  7126  7126 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 15:44:46.130  7126  7126 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 15:44:46.130  7126  7126 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 15:44:46.130  7126  7126 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 15:44:46.130  7126  7126 I wpa_supplicant: First Scan Start
08-30 15:44:46.130  7126  7126 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 15:44:46.130  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-30 15:44:46.130  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
,08-30 15:44:46.130  1015  1125 I WifiNative-HAL: startHal
08-30 15:44:46.130  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d55788c
08-30 15:44:46.130  1015  1125 I WifiNative-HAL: Could not start hal
,08-30 15:44:46.140  1015  1125 E WifiNative-wlan0: do suspend true
,08-30 15:44:46.140  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-30 15:44:46.140  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-30 15:44:46.140   278   894 D CommandListener: Setting iface cfg
08-30 15:44:46.140   278   894 D CommandListener: Trying to bring up p2p0
,08-30 15:44:46.140  7126  7126 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 15:44:46.140  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 15:44:46.140  7126  7126 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 15:44:46.140  1015  1124 D WifiP2pService: P2pEnablingState
,08-30 15:44:46.150  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 },
08-30 15:44:46.150  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 15:44:46.150  1015  1124 D WifiP2pService: P2p socket connection successful
08-30 15:44:46.150  1015  1124 D WifiP2pService: P2pEnabledState
08-30 15:44:46.150  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 15:44:46.150  7126  7126 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-30 15:44:46.150  1015  1125 E WifiStateMachine: Failed to set frequency band 0
,08-30 15:44:46.150  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 15:44:46.150  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:44:46.150  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-30 15:44:46.150  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-30 15:44:46.150  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 15:44:46.150  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:44:46.150  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,08-30 15:44:46.170  1015  1040 W ProcessCpuTracker: Skipping unknown process pid 6859,
,08-30 15:44:46.190  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:46.190  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:44:46.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:46.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:46.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:46.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:46.190  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-30 15:44:46.190  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:46.190  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-30 15:44:46.190  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:46.190  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 15:44:46.190  1175  1175 D HotspotTile: onReceive : 3, 0
,08-30 15:44:46.190  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:46.190  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:44:46.190  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:46.190  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:46.190  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:46.190  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:46.190  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:46.190  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:46.190  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:46.190  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:44:46.190  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:46.190  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:44:46.200  6808  6808 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:46.200  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-30 15:44:46.200  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 15:44:46.200  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 15:44:46.200  1015  1125 E WifiNative-wlan0: invaild command id : 215
08-30 15:44:46.200  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:46.200  1015  1148 I WifiNative-HAL: startHal
08-30 15:44:46.200  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e0f19bc
08-30 15:44:46.200  1015  1148 I WifiNative-HAL: Could not start hal
08-30 15:44:46.200  1015  1148 E WifiScanningService: could not start HAL
,08-30 15:44:46.200  1015  1015 D RttService: SCAN_AVAILABLE : 3
,08-30 15:44:46.200  1015  1149 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:46.200  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:46.200  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:46.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:46.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:46.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:46.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:46.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:46.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:46.200  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:44:46.200  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:46.200  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:44:46.200  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 15:44:46.200  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-30 15:44:46.200  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-30 15:44:46.200  1015  1045 D WifiDisplayController: disconnect
08-30 15:44:46.200  1015  1045 D WifiDisplayController: updateConnection
08-30 15:44:46.200  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 15:44:46.200  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 15:44:46.210  1015  1124 D WifiP2pService: InactiveState
08-30 15:44:46.210  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:46.210  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-30 15:44:46.210  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 15:44:46.210  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 15:44:46.210  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-30 15:44:46.210  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  secondary type: null
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  wps: 0
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  grpcapab: 0
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  devcapab: 0
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  status: 3
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  wfdInfo: null
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-30 15:44:46.210  1015  1045 D WifiDisplayController:  SConnectInfo : null
08-30 15:44:46.210  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 15:44:46.210  7126  7126 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 15:44:46.210  1015  1464 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 15:44:46.210  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-30 15:44:46.210  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 15:44:46.210  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
08-30 15:44:46.210  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-30 15:44:46.210  1015  1504 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 15:44:46.210  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:46.210  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:46.210  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 15:44:46.210  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 15:44:46.210  1640  1640 I Hs20UtilService: Starting #13
,08-30 15:44:46.210  1640  1699 I Hs20UtilService: Message received 5011
,08-30 15:44:46.210  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 15:44:46.210  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 15:44:46.210  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-30 15:44:46.220  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 15:44:46.220  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 15:44:46.220  6484  6484 D SecurityLogAgent: StateMachine : Current State = 1
08-30 15:44:46.220  6484  6484 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 15:44:46.230   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 15:44:46.230  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 15:44:46.230  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 15:44:46.230  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 15:44:46.230  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 15:44:46.230  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 15:44:46.230  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 15:44:46.230  1296  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 15:44:46.230  1015  2020 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-30 15:44:46.240  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:46.240  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:46.240  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:46.240  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:46.250  1015  2020 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7176 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 15:44:46.250  7176  7176 E Zygote  : MountEmulatedStorage()
08-30 15:44:46.250  7176  7176 I libpersona: KNOX_SDCARD checking this for 10064
,08-30 15:44:46.250  7176  7176 E Zygote  : v2
08-30 15:44:46.250  7176  7176 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:46.250  7176  7176 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 15:44:46.250   288   288 E SMD     : DCD OFF,
,08-30 15:44:46.250  7176  7176 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:44:46.260  7176  7176 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:46.270  7176  7176 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:46.270  7176  7176 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:46.290  7176  7176 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 15:44:46.300   283   810 I WVCdm   : CdmEngine::CloseSession
08-30 15:44:46.300  7176  7176 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 15:44:46.300   283   810 I WVCdm   : L3 Terminate.
,08-30 15:44:46.310  7176  7176 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 15:44:46.320  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 15:44:46.320  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 15:44:46.320  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 15:44:46.330  7176  7176 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 15:44:46.330  1015  1462 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-30 15:44:46.340  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:46.340  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:46.340  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:46.340  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:46.350  7191  7191 E Zygote  : MountEmulatedStorage(),
,08-30 15:44:46.350  7191  7191 E Zygote  : v2
08-30 15:44:46.350  1015  1462 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7191 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:44:46.350  1015  1462 I ActivityManager: Killing 6702:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
08-30 15:44:46.350  7191  7191 I libpersona: KNOX_SDCARD checking this for 10065
08-30 15:44:46.350  7191  7191 I libpersona: KNOX_SDCARD not a persona
08-30 15:44:46.350  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-30 15:44:46.350  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-30 15:44:46.350  7191  7191 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 15:44:46.350  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:46.350  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:46.350  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:46.360  7191  7191 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:44:46.360  7191  7191 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:46.360  1905  6706 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 15:44:46.360   278   887 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 15:44:46.360   278   887 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-30 15:44:46.370  1905  6706 W GLSUser : [AppCertManager] IOException while requesting key: 
,08-30 15:44:46.380  7191  7191 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:46.380  7191  7191 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:46.410  7191  7191 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 15:44:46.420  1015  1678 I ActivityManager: Killing 6875:com.android.bluetooth/1002 (adj 15): empty #21
,08-30 15:44:47.230   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 15:44:47.380  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-30 15:44:47.380  1015  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 15:44:47.380  1015  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-30 15:44:47.380  1015  1479 D BatteryService: stay LED for fully charged
08-30 15:44:47.380  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-30 15:44:47.380  1015  1015 I MotionRecognitionService: Plugged
,08-30 15:44:47.380  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 15:44:47.390  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 15:44:47.390  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 15:44:47.390  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 15:44:47.390  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 15:44:47.420  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 15:44:47.420  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 15:44:47.420  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-30 15:44:47.420  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-30 15:44:47.420  1175  1175 D SViewCoverView: level :100 plugged : 2
,08-30 15:44:47.420  7126  7126 I wpa_supplicant: nl80211: Received scan results (21 BSSes),
,08-30 15:44:47.430  7126  7126 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-30 15:44:47.430  7126  7126 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-30 15:44:47.430  7126  7126 I wpa_supplicant: Trying to associate with  'G700'
,08-30 15:44:47.430  7126  7126 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-30 15:44:47.430  7126  7126 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-30 15:44:47.430  1015  7172 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-30 15:44:47.440  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 15:44:47.440  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:44:47.560  7126  7126 E wpa_supplicant: Cmd 35605 not handled
,08-30 15:44:47.560  7126  7126 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 15:44:47.560  7126  7126 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00),
08-30 15:44:47.560  7126  7126 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-30 15:44:47.560  7126  7126 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 15:44:47.560  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:47.560  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
08-30 15:44:47.560  7126  7126 I wpa_supplicant: Associated with F4.99.3E
08-30 15:44:47.560  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-30 15:44:47.560  7126  7126 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 15:44:47.560  7126  7126 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 15:44:47.560  7126  7126 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030,
,08-30 15:44:47.560  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:47.560  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-30 15:44:47.560  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 15:44:47.560  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:47.560  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 15:44:47.560  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 15:44:47.560  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 15:44:47.560  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-30 15:44:47.560  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-30 15:44:47.560  7126  7126 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 15:44:47.560  7126  7126 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-30 15:44:47.570  7126  7126 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-30 15:44:47.570  1015  1128 E Tethering: No numeric data
08-30 15:44:47.570  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 15:44:47.570  1015  1125 D SecContentProvider2: mCursor = null
08-30 15:44:47.570  7126  7126 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-30 15:44:47.570  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 15:44:47.570  1015  1128 D Tethering: clearTetheredNotification()
08-30 15:44:47.570  7126  7126 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:44:47.570  7126  7126 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-30 15:44:47.570  7126  7126 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-30 15:44:47.570  7126  7126 I wpa_supplicant: Blacklist: Clear (temp) 
,08-30 15:44:47.570  7126  7126 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-30 15:44:47.570  1015  1122 V NetworkStats: performPollLocked(flags=0x1),
08-30 15:44:47.570  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:47.570  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
,08-30 15:44:47.570  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 15:44:47.570  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
08-30 15:44:47.580  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:44:47.580  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 15:44:47.580  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 15:44:47.580  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:47.580  1175  1175 D HotspotTile: updateTetherState():false, false
08-30 15:44:47.580  1015  1122 V NetworkStats: performPollLocked() took 6ms
,08-30 15:44:47.580  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-30 15:44:47.580  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:44:47.580  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:47.580  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:47.590  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 15:44:47.590  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 15:44:47.600  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 15:44:47.600  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 15:44:47.600  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 15:44:47.600  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:44:47.600  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 15:44:47.600  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:47.600  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 15:44:47.600  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:47.600  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:47.600  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:47.600  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:44:47.600  1015  1678 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 15:44:47.600  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 15:44:47.600  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:47.600  1015  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-30 15:44:47.600  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 15:44:47.600  1640  1640 I Hs20UtilService: Starting #14
,08-30 15:44:47.610  1640  1699 I Hs20UtilService: Message received 5007
,08-30 15:44:47.610  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 15:44:47.610  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 15:44:47.610  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 15:44:47.610  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 15:44:47.610  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 15:44:47.610  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 15:44:47.620  1296  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 15:44:47.620  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:44:47.630   278   894 D CommandListener: Setting iface cfg,
,08-30 15:44:47.630  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,08-30 15:44:47.630  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 15:44:47.630  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:44:47.640  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 15:44:47.640  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:44:47.640  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:47.640  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:47.640  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:47.640  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:47.650  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 15:44:47.650  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:44:47.660  1015  1125 E WifiNative-wlan0: do suspend false
,08-30 15:44:47.660  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-30 15:44:47.660  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 15:44:47.880  7211  7211 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-30 15:44:47.880  1015  1462 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 15:44:47.880  1015  1462 D WifiService: setWifiEnabled: false pid=6615, uid=10171
08-30 15:44:47.880  1015  1462 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 15:44:47.880  1015  1462 D SecContentProvider2: mCursor = null
08-30 15:44:47.880  1015  1462 D SettingsProvider: name = wifi_on
,08-30 15:44:47.890  7211  7211 I dhcpcd  : version 5.5.6 starting
,08-30 15:44:47.900  7211  7211 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 15:44:47.900  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-30 15:44:47.930  1015  1125 E WifiNative-wlan0: do suspend true,
,08-30 15:44:47.950  1015  1124 D WifiP2pService: InactiveState{ what=143375 },
08-30 15:44:47.950  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
08-30 15:44:47.950  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:47.950  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:44:47.950  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:47.950  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:47.950  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:47.950  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:47.960   278   894 D CommandListener: Clearing all IP addresses on wlan0
,08-30 15:44:47.960  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 15:44:47.960  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 15:44:47.960   278   894 E Netd    : no such netId 503
08-30 15:44:47.960  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-30 15:44:47.960  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 15:44:47.970  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:47.970  1015  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
08-30 15:44:47.970  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:44:47.970  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-30 15:44:47.970  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 15:44:47.970  1015  1127 V NetworkStats: updateIfacesLocked()
08-30 15:44:47.970  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-30 15:44:47.970  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:47.970  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:44:47.970  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:47.970  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:47.970  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:47.970  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:47.980  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
08-30 15:44:47.980  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-30 15:44:47.980  1015  1127 V NetworkStats: performPollLocked() took 6ms
08-30 15:44:47.980  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:47.980  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-30 15:44:47.980  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 15:44:47.980  7211  7211 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-30 15:44:47.980  7211  7211 E dhcpcd  : wlan0: sendmsg: Network is unreachable
08-30 15:44:47.980  7211  7211 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-30 15:44:47.980  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 15:44:47.980  7211  7211 I dhcpcd  : bssid match
08-30 15:44:47.980  1015  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:47.980  1015  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 15:44:47.980  7211  7211 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
08-30 15:44:47.980  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 15:44:47.980  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-30 15:44:47.980  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:47.980  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-30 15:44:47.980  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 15:44:47.980  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 15:44:47.980  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-30 15:44:47.980  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:47.980  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 15:44:47.980  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 15:44:47.980  1015  1127 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 15:44:47.980  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 15:44:47.980  1640  1640 I Hs20UtilService: Starting #15
,08-30 15:44:47.980  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:47.980  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:47.980  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:47.980  1640  1699 I Hs20UtilService: Message received 5007
08-30 15:44:47.980  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-30 15:44:47.980  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 15:44:47.980  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 15:44:47.990  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 15:44:47.990  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 15:44:47.990  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 15:44:47.990  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-30 15:44:47.990  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 15:44:47.990  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: FAILED
08-30 15:44:47.990  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 15:44:47.990  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 15:44:47.990  1296  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 15:44:47.990  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 15:44:47.990  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-30 15:44:47.990  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 15:44:47.990  1015  1045 D WifiDisplayController: disconnect
08-30 15:44:47.990  1015  1045 D WifiDisplayController: updateConnection
08-30 15:44:47.990  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 15:44:47.990  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 15:44:47.990  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 15:44:47.990  1015  1479 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 15:44:47.990  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 15:44:48.000  1015  1124 D WifiP2pService: P2pDisablingState
08-30 15:44:48.000  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-30 15:44:48.000  1015  1124 D WifiP2pService: p2p socket connection lost
,08-30 15:44:48.000  1015  1124 D WifiP2pService: P2pDisabledState
,08-30 15:44:48.000  1015  1125 E WifiNative-wlan0: do suspend true
08-30 15:44:48.000  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 15:44:48.000  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-30 15:44:48.000  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 15:44:48.000  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 15:44:48.000  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 15:44:48.000  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 15:44:48.000  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 15:44:48.000  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 15:44:48.000  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 15:44:48.000  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 15:44:48.010  1296  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 15:44:48.010  7176  7176 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 15:44:48.010  7176  7176 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-30 15:44:48.010  7176  7176 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 15:44:48.010  7191  7191 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 15:44:48.040  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-30 15:44:48.040  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-30 15:44:48.040   278   894 D CommandListener: Clearing all IP addresses on wlan0
,08-30 15:44:48.040  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:48.040  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:44:48.040  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:48.040  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:48.040  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:48.040  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:48.040  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 15:44:48.040  7126  7126 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-30 15:44:48.050  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:48.050  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:44:48.050  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:48.050  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:48.050  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:48.050  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:48.050  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 15:44:48.050  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:44:48.060  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:44:48.060  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 15:44:48.060  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:48.060  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:48.060  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:48.060  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:48.060  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 15:44:48.060  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-30 15:44:48.060  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 15:44:48.060  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:48.060  1175  1175 D HotspotTile: onReceive : 0, 0
,08-30 15:44:48.070  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:48.070  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-30 15:44:48.070  1015  1409 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:44:48.070  1015  1409 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 15:44:48.070  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:48.070  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:44:48.070  1015  1409 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:48.070  1015  1409 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:48.070  1015  1409 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 15:44:48.070  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:48.070  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:44:48.070  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:48.070  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:44:48.070  1640  1640 I Hs20UtilService: Starting #16
,08-30 15:44:48.080  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 15:44:48.080  1640  1699 I Hs20UtilService: Message received 5007
,08-30 15:44:48.080  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 15:44:48.080  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 15:44:48.080  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 15:44:48.080  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 15:44:48.080  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 15:44:48.080  1296  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 15:44:48.090  1015  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 15:44:48.090  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 15:44:48.100  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:48.100  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:48.100  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 15:44:48.100  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 15:44:48.100  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 15:44:48.100  6484  6484 D SecurityLogAgent: StateMachine : Current State = 1
08-30 15:44:48.100  6484  6484 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 15:44:48.110  1640  1640 I Hs20UtilService: Starting #17
,08-30 15:44:48.110  1640  1699 I Hs20UtilService: Message received 5011
,08-30 15:44:48.130  7211  7211 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-30 15:44:48.180  7126  7126 I wpa_supplicant: Blacklist: Clear (all) 
08-30 15:44:48.180  7211  7211 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-30 15:44:48.230   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 15:44:48.320  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 15:44:48.320  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-30 15:44:48.320  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 15:44:48.320  7126  7126 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 15:44:48.340  7126  7126 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-30 15:44:48.340  7126  7126 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 15:44:48.340  7126  7126 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-30 15:44:48.340  7126  7126 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-30 15:44:48.340  7126  7126 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-30 15:44:48.350  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:44:48.340  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:48.340  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 15:44:48.350  1015  1128 D Tethering: InitialState.processMessage what=4
08-30 15:44:48.350  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:48.350  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 15:44:48.350  1015  1128 E Tethering: No numeric data,
08-30 15:44:48.350  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-30 15:44:48.350  1015  1128 D Tethering: clearTetheredNotification()
08-30 15:44:48.350  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:44:48.350  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:48.350  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-30 15:44:48.360  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:44:48.360  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 15:44:48.360  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:48.360  1015  1122 V NetworkStats: performPollLocked() took 3ms
08-30 15:44:48.360  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 15:44:48.360  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:44:48.360  1175  1175 D HotspotTile: updateTetherState():false, false
08-30 15:44:48.360  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:44:48.360  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:44:48.360  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:44:48.360  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 15:44:48.550  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 15:44:48.550  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:44:48.550  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 15:44:48.690  7126  7126 I wpa_supplicant: Blacklist: Clear (all) ,
,08-30 15:44:48.710  1015  1047 I PowerManagerService: [PWL] Off : 50s ago,
08-30 15:44:48.710  1015  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-30 15:44:48.710  1015  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-30 15:44:48.710  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=6489)
,08-30 15:44:48.810  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 15:44:48.810  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:44:48.810  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 15:44:48.810  7126  7126 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-30 15:44:48.910  1015  2844 D SSRM:n  : SIOP:: AP = 380
,08-30 15:44:48.920  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-30 15:44:48.920  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-30 15:44:48.920  6808  6808 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:44:48.920  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 15:44:48.930  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 15:44:48.930  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:48.930  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:48.930  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:44:48.930  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:44:48.930  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:48.930  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-30 15:44:48.930  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:48.930  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 15:44:48.940  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:48.940  1905  2121 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:48.940  1175  1175 D HotspotTile: onReceive : 1, 0
,08-30 15:44:48.940  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-30 15:44:48.940  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:48.950  1015  2020 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 15:44:48.950  1015  2020 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 15:44:48.950  1015  2020 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:48.950  1015  2020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:48.950  1015  2020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 15:44:48.950  1640  1640 I Hs20UtilService: Starting #18
,08-30 15:44:48.950  1640  1699 I Hs20UtilService: Message received 5011
,08-30 15:44:48.950  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 15:44:48.960  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 15:44:48.960  6484  6484 D SecurityLogAgent: StateMachine : Current State = 1
08-30 15:44:48.960  6484  6484 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 15:44:49.200  1015  1215 I ActivityManager: Killing 6726:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-30 15:44:49.230   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 15:44:49.260   288   288 E SMD     : DCD OFF
,08-30 15:44:49.610   278   884 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-30 15:44:49.610  1015  1042 D Tethering: interfaceRemoved wlan0
,08-30 15:44:49.610  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 15:44:49.770  1015  1042 D Tethering: interfaceRemoved p2p0
,08-30 15:44:49.770  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 15:44:50.240   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 15:44:50.580  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-30 15:44:50.900  6615  6668 D BluetoothAdapter: enable()
,08-30 15:44:50.900  1015  1479 W ActivityManager: Permission Denial: getCurrentUser() from pid=6615, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-30 15:44:50.900  1015  1479 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-30 15:44:50.900  1015  1479 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6615, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-30 15:44:50.900  1015  1479 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 15:44:50.900  1015  1479 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-30 15:44:50.900  1015  1479 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-30 15:44:50.900  1015  1479 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-30 15:44:50.900  1015  1479 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 15:44:50.900  1015  1479 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-30 15:44:50.900  1015  1479 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 15:44:50.910  1015  1479 D SettingsProvider: name = bluetooth_on,
,08-30 15:44:50.910  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 15:44:50.910  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 15:44:50.910  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-30 15:44:50.920  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-30 15:44:50.920  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:50.920  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:50.920  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:50.920  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:50.930  7243  7243 E Zygote  : MountEmulatedStorage(),
08-30 15:44:50.930  7243  7243 I libpersona: KNOX_SDCARD checking this for 1002
08-30 15:44:50.930  7243  7243 E Zygote  : v2
,08-30 15:44:50.930  7243  7243 I libpersona: KNOX_SDCARD not a persona
08-30 15:44:50.930  1015  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7243 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-30 15:44:50.940  7243  7243 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:50.940  7243  7243 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 15:44:50.940  7243  7243 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:50.970  7243  7243 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:50.970  7243  7243 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:50.990  7243  7243 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 15:44:50.990  7243  7243 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 15:44:51.020  7243  7243 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding GattService
,08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding HeadsetService
,08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding A2dpService
08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding HidService
,08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding HealthService
08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding PanService
,08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding SapService
08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding SapClientService
08-30 15:44:51.060  7243  7243 D BtSettings.ProfileConfig: Adding HidDevService
,08-30 15:44:51.060  7243  7243 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-30 15:44:51.060  1015  1464 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService,
08-30 15:44:51.060  1015  1464 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:51.060  1015  1464 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.060  1015  1464 D SettingsProvider: selectionArgs: false
08-30 15:44:51.060  1015  1464 D SettingsProvider: selectionArgs: 1002
08-30 15:44:51.060  1015  1464 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 15:44:51.060  1015  1464 D SettingsProvider: ret = -1
08-30 15:44:51.060  1015  1678 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-30 15:44:51.060  1015  1678 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:51.060  1015  1678 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.060  1015  1678 D SettingsProvider: selectionArgs: false
08-30 15:44:51.060  1015  1678 D SettingsProvider: selectionArgs: 1002
,08-30 15:44:51.060  1015  1678 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:51.060  1015  1678 D SettingsProvider: ret = -1
08-30 15:44:51.060  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-30 15:44:51.060  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 15:44:51.060  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.060  1015  1133 D SettingsProvider: selectionArgs: false
08-30 15:44:51.060  1015  1133 D SettingsProvider: selectionArgs: 1002
08-30 15:44:51.060  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:51.060  1015  1133 D SettingsProvider: ret = -1
08-30 15:44:51.060  1015  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-30 15:44:51.070  1015  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 15:44:51.070  1015  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.070  1015  1480 D SettingsProvider: selectionArgs: false
08-30 15:44:51.070  1015  1480 D SettingsProvider: selectionArgs: 1002
08-30 15:44:51.070  1015  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:51.070  1015  1480 D SettingsProvider: ret = -1
,08-30 15:44:51.070  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-30 15:44:51.070  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:51.070  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.070  1015  1027 D SettingsProvider: selectionArgs: false
08-30 15:44:51.070  1015  1027 D SettingsProvider: selectionArgs: 1002
08-30 15:44:51.070  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 15:44:51.070  1015  1027 D SettingsProvider: ret = -1
,08-30 15:44:51.070  1015  1215 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-30 15:44:51.070  1015  1215 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:51.070  1015  1215 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.070  1015  1215 D SettingsProvider: selectionArgs: false
08-30 15:44:51.070  1015  1215 D SettingsProvider: selectionArgs: 1002
08-30 15:44:51.070  1015  1215 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:51.070  1015  1215 D SettingsProvider: ret = -1
08-30 15:44:51.070  1015  1504 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-30 15:44:51.070  1015  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:51.070  1015  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.070  1015  1504 D SettingsProvider: selectionArgs: false
08-30 15:44:51.070  1015  1504 D SettingsProvider: selectionArgs: 1002
08-30 15:44:51.070  1015  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:51.070  1015  1504 D SettingsProvider: ret = -1
08-30 15:44:51.070  1015  1409 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-30 15:44:51.070  1015  1409 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:51.070  1015  1409 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.070  1015  1409 D SettingsProvider: selectionArgs: false
08-30 15:44:51.070  1015  1409 D SettingsProvider: selectionArgs: 1002
08-30 15:44:51.070  1015  1409 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:51.070  1015  1409 D SettingsProvider: ret = -1
08-30 15:44:51.070  1015  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:44:51.070  1015  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:51.070  1015  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.070  1015  1477 D SettingsProvider: selectionArgs: false
08-30 15:44:51.070  1015  1477 D SettingsProvider: selectionArgs: 1002
08-30 15:44:51.070  1015  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:51.070  1015  1477 D SettingsProvider: ret = -1
08-30 15:44:51.070  1015  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:51.070  1015  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:51.070  1015  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.070  1015  1479 D SettingsProvider: selectionArgs: false
08-30 15:44:51.070  1015  1479 D SettingsProvider: selectionArgs: 1002
08-30 15:44:51.070  1015  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:51.070  1015  1479 D SettingsProvider: ret = -1
08-30 15:44:51.070  1015  2020 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-30 15:44:51.070  1015  2020 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:51.070  1015  2020 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.070  1015  2020 D SettingsProvider: selectionArgs: false
,08-30 15:44:51.070  1015  2020 D SettingsProvider: selectionArgs: 1002
08-30 15:44:51.070  1015  2020 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:51.070  1015  2020 D SettingsProvider: ret = -1
08-30 15:44:51.070  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-30 15:44:51.070  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-30 15:44:51.070  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.070  1015  1028 D SettingsProvider: selectionArgs: false
08-30 15:44:51.070  1015  1028 D SettingsProvider: selectionArgs: 1002
,08-30 15:44:51.070  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:51.070  1015  1028 D SettingsProvider: ret = -1
,08-30 15:44:51.090  7243  7243 D BluetoothAdapterState: make
,08-30 15:44:51.090  7243  7243 I bluedroid: init
,08-30 15:44:51.090  7243  7258 I BluetoothAdapterState: Entering OffState,
,08-30 15:44:51.100  7243  7243 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-30 15:44:51.100  7243  7243 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 15:44:51.100  7243  7243 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory,
08-30 15:44:51.100  7243  7243 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 15:44:51.100  7243  7243 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-30 15:44:51.100  7243  7243 I bluedroid: get_profile_interface socket
08-30 15:44:51.100  7243  7243 I bluedroid: get_profile_interface map_client
08-30 15:44:51.100  7243  7261 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 15:44:51.100  7243  7261 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-30 15:44:51.100  7243  7261 E BluetoothServiceJni: populateRssiValuesNative
08-30 15:44:51.100  7243  7261 I bluedroid: getModelRssiValues
,08-30 15:44:51.100  7243  7261 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 15:44:51.100  7243  7261 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 15:44:51.100  7243  7243 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-30 15:44:51.100  7243  7261 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-30 15:44:51.100  1015  1015 D SettingsProvider: name = bluetooth_name
,08-30 15:44:51.110  7243  7243 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
,08-30 15:44:51.110  1015  1479 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 15:44:51.110  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 15:44:51.110  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:51.110  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:51.110  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:51.110  7243  7251 I bluedroid: config_hci_snoop_log
,08-30 15:44:51.120  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
08-30 15:44:51.120  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-30 15:44:51.120  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
08-30 15:44:51.120  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-30 15:44:51.120  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-30 15:44:51.120  7243  7243 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-30 15:44:51.120  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 15:44:51.120  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 15:44:51.130  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 15:44:51.130  7243  7258 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-30 15:44:51.130  7243  7258 D BluetoothAdapterProperties: Setting state to 11
08-30 15:44:51.130  7243  7258 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 15:44:51.130  7243  7258 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 15:44:51.130  7243  7258 D BluetoothAdapterService: updateAdapterState state is 11
08-30 15:44:51.130  7243  7258 D BluetoothAdapterService: Autoconnection is available 
08-30 15:44:51.130  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 15:44:51.130  7243  7258 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-30 15:44:51.130  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:51.130  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-30 15:44:51.130  7243  7258 D BluetoothSecureManager: getInstant: null
08-30 15:44:51.130  7243  7258 D BluetoothSecureManager: calling getMethod for getService
,08-30 15:44:51.130  7243  7258 D BluetoothSecureManager: calling getService
,08-30 15:44:51.140  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 15:44:51.140  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:51.140  1175  1175 D BluetoothTile:  getBluetoothState : 11
,08-30 15:44:51.140  7243  7258 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3a42926a
,08-30 15:44:51.150  1794  1794 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-30 15:44:51.150  1015  1215 D BluetoothSecureManagerService: isSecureModeEnabled
08-30 15:44:51.150  1015  1215 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-30 15:44:51.150  7243  7258 D BtConfig.SecureMode: isSecureModeOn:false
08-30 15:44:51.150  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 15:44:51.150  7243  7258 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-30 15:44:51.150  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 15:44:51.150  7243  7258 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-30 15:44:51.150  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 15:44:51.150  7243  7258 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,08-30 15:44:51.150  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 15:44:51.150  7243  7258 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,08-30 15:44:51.150  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
08-30 15:44:51.150  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 15:44:51.150  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-30 15:44:51.150  7243  7258 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-30 15:44:51.150  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 15:44:51.150  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:51.150  7243  7258 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-30 15:44:51.150  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:51.150  7243  7258 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-30 15:44:51.150  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 15:44:51.150  7243  7258 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-30 15:44:51.150  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 15:44:51.160  1015  2020 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 15:44:51.160  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:51.160  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:51.160  7243  7258 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:44:51.160  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 15:44:51.160  1015  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-30 15:44:51.160  7243  7258 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:51.160  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 15:44:51.160  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-30 15:44:51.160  7243  7258 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 15:44:51.160  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 15:44:51.170  7243  7258 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-30 15:44:51.170  7243  7258 D BluetoothBondStateMachine: make
,08-30 15:44:51.180  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-30 15:44:51.180  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 15:44:51.180  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 15:44:51.180  7243  7263 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 15:44:51.310  1015  1477 I art     : Explicit concurrent mark sweep GC freed 69990(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.536ms total 158.160ms
,08-30 15:44:51.310  1015  1678 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:44:51.310  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 15:44:51.310  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:51.310  1015  1678 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:51.310  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:51.320  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 15:44:51.320  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:51.320  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 15:44:51.320  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:51.320  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:51.320  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:51.320  7243  7243 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 15:44:51.320  7243  7243 D BtGatt.GattService: Received start request. Starting profile...
08-30 15:44:51.320  7243  7243 D BtGatt.GattService: start()
08-30 15:44:51.320  7243  7243 D BtGatt.GattService: start()
08-30 15:44:51.320  7243  7243 I bluedroid: get_profile_interface gatt
,08-30 15:44:51.320  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
08-30 15:44:51.320  7243  7243 D BtGatt.AdvertiseManager: advertise manager created
,08-30 15:44:51.320  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 15:44:51.320  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 15:44:51.320  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 15:44:51.330  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:51.330  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-30 15:44:51.330  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:51.330  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 15:44:51.330  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:51.330  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:51.330  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:51.340  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-30 15:44:51.340  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 15:44:51.340  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 15:44:51.340  1015  1678 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 15:44:51.340  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 15:44:51.340  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:51.340  1015  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:51.340  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:51.340  1015  1215 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-30 15:44:51.340  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:51.340  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:51.350  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:51.350  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 15:44:51.350  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 15:44:51.350  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 15:44:51.350  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:51.360  7243  7243 D BtGatt.GattService: mStartError = false,
08-30 15:44:51.360  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:51.360  7243  7243 D HeadsetService: Received start request. Starting profile...
08-30 15:44:51.360  7243  7243 D HeadsetService: start()
08-30 15:44:51.360  1015  1215 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7267 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-30 15:44:51.360  7267  7267 E Zygote  : MountEmulatedStorage()
08-30 15:44:51.360  7243  7243 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 15:44:51.360  7243  7243 D HeadsetStateMachine: make
,08-30 15:44:51.360  1015  1464 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-30 15:44:51.360  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:51.360  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-30 15:44:51.360  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 15:44:51.360  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 15:44:51.370  7267  7267 E Zygote  : v2
08-30 15:44:51.370  7267  7267 I libpersona: KNOX_SDCARD checking this for 10055
08-30 15:44:51.370  7243  7243 E HeadsetStateMachine: # of Max HF connection is 2
08-30 15:44:51.370  7267  7267 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:51.370  7267  7267 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:51.370  7267  7267 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:44:51.370  7267  7267 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:51.370  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 15:44:51.370  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 15:44:51.370  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-30 15:44:51.370  1015  2020 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:51.370  1015  2020 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 15:44:51.380  1015  2020 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:51.380  1015  2020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:51.380  1015  2020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:51.380  1015  1480 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-30 15:44:51.380  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-30 15:44:51.380  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:51.380  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:51.380  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-30 15:44:51.380  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 15:44:51.380  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 15:44:51.380  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-30 15:44:51.380  1015  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-30 15:44:51.380  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 15:44:51.380  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:51.380  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:51.380  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 15:44:51.390  7243  7243 I bluedroid: get_profile_interface handsfree
08-30 15:44:51.390  1015  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:51.390  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 15:44:51.390  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:51.390  1015  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:51.390  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:51.390  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 15:44:51.390  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:51.390  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 15:44:51.390  1015  1678 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:51.390  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 15:44:51.390  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:51.390  1015  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:51.390  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:51.390  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 15:44:51.400  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 15:44:51.400  7243  7258 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 15:44:51.400  1015  1464 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 15:44:51.400  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 15:44:51.400  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:51.400  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:51.400  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:51.410  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 15:44:51.410  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 15:44:51.410  7243  7258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:44:51.410  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:51.410  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:51.410  7243  7258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:51.410  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 15:44:51.410  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 15:44:51.410  7243  7258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 15:44:51.410  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 15:44:51.410  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 15:44:51.410  7243  7258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 15:44:51.410  7243  7258 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 15:44:51.410  1015  1028 I ActivityManager: Killing 6892:com.sec.pcw.device/1000 (adj 15): empty #21
,08-30 15:44:51.420  7243  7243 I DualScoManager: Instantiating Dual Sco Manager
,08-30 15:44:51.420  7243  7243 I DualScoManager: Set HeadsetServiceHelper
,08-30 15:44:51.420  7243  7243 D BluetoothAtMessage: createCMTIContentObservers
,08-30 15:44:51.420  1015  1464 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-30 15:44:51.420  1015  1464 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:51.420  1015  1464 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:51.420  1015  1464 D SettingsProvider: selectionArgs: false
08-30 15:44:51.420  1015  1464 D SettingsProvider: selectionArgs: 1002
08-30 15:44:51.420  1015  1464 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:51.420  1015  1464 D SettingsProvider: ret = -1
,08-30 15:44:51.420  7267  7267 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 15:44:51.420  7243  7273 D HeadsetStateMachine: Enter Disconnected: -2
,08-30 15:44:51.420  7267  7267 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:51.420  7243  7243 D HeadsetService: mStartError = false
08-30 15:44:51.420  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:51.430  7243  7273 D HeadsetStateMachine: Clear mHeadsetBrsf
08-30 15:44:51.430  7243  7273 D HeadsetStateMachine: map size, before remove : 0
08-30 15:44:51.430  7243  7273 D HeadsetStateMachine: map size, after remove: 0
,08-30 15:44:51.430  7243  7243 D A2dpService: Received start request. Starting profile...
08-30 15:44:51.430  7243  7243 D A2dpService: start()
,08-30 15:44:51.430  7243  7243 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 15:44:51.430  7243  7243 I bluedroid: get_profile_interface avrcp
,08-30 15:44:51.440  7243  7243 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 15:44:51.450  7243  7243 D Avrcp   : Initialize Media Controller
08-30 15:44:51.450  7243  7243 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-30 15:44:51.450  7243  7243 E Avrcp   : getActiveSessions
08-30 15:44:51.450  7243  7243 D Avrcp   : pick active media Controller
,08-30 15:44:51.450  7243  7243 D Avrcp   : Get the active Media Controller 
,08-30 15:44:51.460  7267  7267 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 15:44:51.460  7243  7243 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 15:44:51.460  7243  7286 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-30 15:44:51.470  7243  7243 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:44:51.470  7243  7243 D A2dpStateMachine: make
,08-30 15:44:51.470  7243  7243 I bluedroid: get_profile_interface a2dp
,08-30 15:44:51.470  7243  7288 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 15:44:51.470  7243  7243 E bt-btif : warning : media task started media_task_refcnt 1 
08-30 15:44:51.470  7243  7243 D A2dpService: mStartError = false
08-30 15:44:51.470  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
08-30 15:44:51.470  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-30 15:44:51.470  7243  7287 D A2dpStateMachine: Enter Disconnected: -2
,08-30 15:44:51.470  7243  7243 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 15:44:51.480  7243  7243 D HidService: Received start request. Starting profile...
08-30 15:44:51.480  7243  7243 D HidService: start()
08-30 15:44:51.480  7243  7243 I bluedroid: get_profile_interface hidhost
08-30 15:44:51.480  7243  7243 D HidService: setHidService(): set to: null
08-30 15:44:51.480  7243  7243 D HidService: mStartError = false
08-30 15:44:51.480  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:51.480  7243  7243 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 15:44:51.480  7243  7243 D HealthService: Received start request. Starting profile...
08-30 15:44:51.480  7243  7243 D HealthService: start()
,08-30 15:44:51.480  7243  7286 D BluetoothMediaBrowser: no now playing list
,08-30 15:44:51.480  7243  7286 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 15:44:51.480  7243  7243 I bluedroid: get_profile_interface health
,08-30 15:44:51.480  7243  7243 D HealthService: mStartError = false
08-30 15:44:51.480  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:51.480  7243  7243 D HeadsetStateMachine: Try to query the phonestate on bind
,08-30 15:44:51.490  1426  1446 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 15:44:51.490  1426  1426 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-30 15:44:51.490  1426  1426 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 15:44:51.490  1426  1446 I Telecom : BluetoothPhoneService: Result of Message : true
,08-30 15:44:51.490  7243  7243 D HeadsetStateMachine: Proxy object connected
,08-30 15:44:51.490  7243  7243 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 15:44:51.490  7267  7267 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-30 15:44:51.490  7243  7243 D PanService: Received start request. Starting profile...
,08-30 15:44:51.490  7267  7267 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-30 15:44:51.490  7243  7243 D PanService: start()
08-30 15:44:51.490  7267  7267 D UserAnalysis: Create SecureDbHelper
08-30 15:44:51.490  7243  7243 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 15:44:51.490  7243  7243 I bluedroid: get_profile_interface pan
,08-30 15:44:51.500  7243  7243 D PanService: mStartError = false
,08-30 15:44:51.500  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:51.500  7243  7243 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-30 15:44:51.500  7243  7273 D HeadsetStateMachine: Disconnected process message: 11
,08-30 15:44:51.500  7243  7243 D BluetoothMapService: Received start request. Starting profile...
,08-30 15:44:51.500  7243  7243 D BluetoothMapService: start()
,08-30 15:44:51.500  7243  7243 D BluetoothMapService: mStartError = false,
,08-30 15:44:51.500  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
08-30 15:44:51.500  7243  7243 D HeadsetPhoneState: sendDeviceDataStateChanged,
08-30 15:44:51.500  7243  7273 D HeadsetStateMachine: Disconnected process message: 18
,08-30 15:44:51.500  7243  7243 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-30 15:44:51.500  7243  7243 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-30 15:44:51.500  7267  7267 D IntelligenceServiceApplication: onCreate()
,08-30 15:44:51.510  7243  7243 D SapService: Received start request. Starting profile...
08-30 15:44:51.510  7243  7243 D SapService: start()
08-30 15:44:51.510  7243  7243 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 15:44:51.510  7243  7243 I bluedroid: get_profile_interface sap
08-30 15:44:51.510  7243  7243 D SapService: mStartError = false
08-30 15:44:51.510  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
08-30 15:44:51.510  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-30 15:44:51.510  7243  7243 D BluetoothA2dp: Proxy object connected
08-30 15:44:51.510  7243  7243 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-30 15:44:51.510  7243  7243 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 15:44:51.510  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 15:44:51.510  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-30 15:44:51.510  7243  7273 D HeadsetStateMachine: Disconnected process message: 10
08-30 15:44:51.510  7243  7273 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 15:44:51.510  7243  7273 D HeadsetStateMachine: Disconnected process message: 11
,08-30 15:44:51.510  1015  1462 I ActivityManager: Killing 6909:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-30 15:44:51.510  7267  7267 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-30 15:44:51.520  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-30 15:44:51.520  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-30 15:44:51.520  1015  1409 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-30 15:44:51.520  7267  7267 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-30 15:44:51.530  7267  7267 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-30 15:44:51.540  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-30 15:44:51.550  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 15:44:51.550  1015  1409 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-30 15:44:51.550  1015  1409 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:51.550  1015  1409 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:51.550  1015  1409 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:51.550  1015  1409 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:51.560  7293  7293 E Zygote  : MountEmulatedStorage(),
08-30 15:44:51.560  7293  7293 E Zygote  : v2
08-30 15:44:51.560  7293  7293 I libpersona: KNOX_SDCARD checking this for 10105
08-30 15:44:51.560  7293  7293 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:51.560  7293  7293 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 15:44:51.560  1015  1409 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7293 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-30 15:44:51.570  7243  7258 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false,
08-30 15:44:51.570  7243  7258 I bluedroid: enable
,08-30 15:44:51.570  7243  7258 I bt_hci_bdroid: init
,08-30 15:44:51.570  7293  7293 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 15:44:51.570  7243  7299 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-30 15:44:51.570  7243  7258 I bt_vendor: bt-vendor : init
08-30 15:44:51.570  7243  7258 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 15:44:51.570  7243  7258 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 15:44:51.570  7243  7258 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-30 15:44:51.570  7243  7258 D bt_userial_mct: userial_init
08-30 15:44:51.570  7243  7258 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 15:44:51.570  7243  7258 I bt_vendor: Starting hciattach daemon
08-30 15:44:51.570  7243  7258 I bt_vendor: try to set false
,08-30 15:44:51.570  7293  7293 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-30 15:44:51.570  7243  7258 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 15:44:51.570  7243  7258 I bt_vendor: Starting hciattach daemon
08-30 15:44:51.570  7243  7258 I bt_vendor: try to set true
,08-30 15:44:51.590  7306  7306 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-30 15:44:51.590  7293  7293 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 15:44:51.590  7293  7293 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:51.640  7318  7318 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 15:44:51.650  7319  7319 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 15:44:51.670  7321  7321 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 15:44:51.680  7322  7322 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-30 15:44:51.690  7323  7323 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 15:44:51.690  7324  7324 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-30 15:44:51.740   257   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 15:44:51.740   257   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 15:44:51.740  7293  7330 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 15:44:51.740   257   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 15:44:51.740   257   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 15:44:51.750  7293  7330 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 15:44:51.840  7341  7341 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-30 15:44:51.850  7342  7342 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 15:44:51.880  7243  7258 I bt_vendor: bluetooth satus is on
,08-30 15:44:51.880  7243  7301 D bt_userial_mct: userial_open(port:0)
08-30 15:44:51.880  7243  7301 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 15:44:51.880  7243  7301 I bt_vendor: Done intiailizing UART
,08-30 15:44:51.880  7243  7301 I bt_vendor: Done intiailizing UART
,08-30 15:44:51.880  7243  7301 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-30 15:44:51.880  7243  7301 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-30 15:44:51.890  7243  7344 D bt_userial_mct: Entering userial_read_thread()
,08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_SAP
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 15:44:51.890  7243  7299 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-30 15:44:51.900  7293  7293 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:51.900  7293  7293 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:51.900  7293  7293 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:51.900  7293  7293 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:51.900  7293  7293 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.k.d(PG:583)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:51.900  7293  7293 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:51.900  7293  7293 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:51.900  7293  7293 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:44:51.900  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:44:51.910  1015  1133 I ActivityManager: Killing 6922:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-30 15:44:51.910  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-30 15:44:51.910  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 15:44:51.970  7293  7340 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 15:44:51.980  7243  7299 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-30 15:44:51.990  7243  7299 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4191ed1 
08-30 15:44:51.990  7243  7299 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4191ed1 
,08-30 15:44:51.990  1015  1678 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:52.000  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:52.000  1015  1678 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:52.000  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-30 15:44:52.000  7243  7261 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-30 15:44:52.010  7243  7261 E bt-btif : Calling BTA_HhEnable
,08-30 15:44:52.010  7243  7261 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 15:44:52.010  7243  7261 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-30 15:44:52.010  7243  7261 E BluetoothServiceJni: populateRssiValuesNative
08-30 15:44:52.010  7243  7261 I bluedroid: getModelRssiValues
08-30 15:44:52.010  7243  7261 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 15:44:52.010  7243  7261 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 15:44:52.010  7243  7261 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-30 15:44:52.010  1015  1015 D SettingsProvider: name = bluetooth_name
,08-30 15:44:52.020  7243  7261 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 15:44:52.020  7243  7261 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:44:52.020  7243  7261 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 15:44:52.020  7243  7261 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-30 15:44:52.020  7243  7261 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-30 15:44:52.020  7243  7261 E bt-btif : HC lpm_result_cb 1
08-30 15:44:52.020  7243  7261 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-30 15:44:52.020  7243  7261 E bt-btif : btif_sock_init: !vhci_init
08-30 15:44:52.020  7243  7261 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-30 15:44:52.020  7243  7261 D IOP_DB_BT: db_open: db_open : handle 3028168720l, read 13894 bytes onto local cache
08-30 15:44:52.020  7243  7261 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-30 15:44:52.020  7243  7261 D IOP_DB_BT: db_query: result 1
08-30 15:44:52.020  7243  7261 I         : iop_db_open: iop_db_open status 0
,08-30 15:44:52.020  7243  7261 D bte_conf: Device ID record 1 : primary
08-30 15:44:52.020  7243  7261 D bte_conf:   vendorId            = 0075
08-30 15:44:52.020  7243  7261 D bte_conf:   vendorIdSource      = 0001
08-30 15:44:52.020  7243  7261 D bte_conf:   product             = 0100
08-30 15:44:52.020  7243  7261 D bte_conf:   version             = 0200
08-30 15:44:52.020  7243  7261 D bte_conf:   clientExecutableURL = 
08-30 15:44:52.020  7243  7261 D bte_conf:   serviceDescription  = 
08-30 15:44:52.020  7243  7261 D bte_conf:   documentationURL    = 
08-30 15:44:52.020  7243  7261 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 15:44:52.020  7243  7261 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 15:44:52.020  7243  7344 E bt_mct  : hci lib postload completed
,08-30 15:44:52.020  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:52.030  7243  7258 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 15:44:52.030  7243  7258 D BluetoothAdapterProperties: ScanMode =  20
08-30 15:44:52.030  7243  7258 D BluetoothAdapterProperties: State =  11
,08-30 15:44:52.030  1015  1477 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 15:44:52.030  7243  7258 D BluetoothAdapterProperties: Setting state to 12
,08-30 15:44:52.030  7243  7258 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 15:44:52.030  1015  1133 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-30 15:44:52.030  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:52.030  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 15:44:52.030  1015  1133 D SettingsProvider: selectionArgs: false
,08-30 15:44:52.030  1015  1133 D SettingsProvider: selectionArgs: 1002
08-30 15:44:52.030  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 15:44:52.030  1015  1133 D SettingsProvider: ret = -1
08-30 15:44:52.030  7243  7258 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 15:44:52.030  7243  7258 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 15:44:52.040  7243  7261 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 15:44:52.040  7243  7261 D BluetoothAdapterProperties: Scan Mode:21
08-30 15:44:52.040  7243  7261 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 15:44:52.040  1015  1464 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 15:44:52.040  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-30 15:44:52.040  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:52.040  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:52.040  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:52.040  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:52.040  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:52.040  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:52.040  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:52.040  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:44:52.040  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:52.040  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:44:52.040  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 15:44:52.040  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.050  7243  7258 D BluetoothAdapterService: Autoconnection is available 
08-30 15:44:52.050  7243  7258 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 15:44:52.050  7243  7258 D BluetoothAdapterService: starting service from this receiver
,08-30 15:44:52.050  1015  1678 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:52.050  1426  2846 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:44:52.050  1426  2846 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:44:52.050  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:52.050  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:52.050  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:52.050  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:52.050  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:52.050  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:52.050  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:52.050  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:44:52.050  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 15:44:52.050  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:52.050  1015  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.050  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.050  7243  7258 I BluetoothAdapterState: Entering On State from state = 11
,08-30 15:44:52.060  7243  7262 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 15:44:52.060  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:44:52.060  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:44:52.060  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 15:44:52.060  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 15:44:52.060  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:52.060  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 15:44:52.060  1296  6698 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:44:52.060  1296  6698 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:44:52.060  1426  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:44:52.060  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 15:44:52.060  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 15:44:52.070  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:52.070  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.070  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.070  1426  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 15:44:52.070  1296  1306 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:44:52.070  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 15:44:52.070  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 15:44:52.070  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:52.070  7243  7243 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-30 15:44:52.070  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.070  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.070  1296  1306 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 15:44:52.070  1455  2451 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 15:44:52.080  1455  2451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:44:52.080  1440  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:44:52.080  1440  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:44:52.080  7293  7307 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 15:44:52.080  7293  7307 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:44:52.080  1296  1314 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 15:44:52.080  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-30 15:44:52.080  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 15:44:52.080  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:52.080  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.080  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.080  7243  7243 I BluetoothPbapService: Handler(): got msg=1
,08-30 15:44:52.090  1426  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:44:52.090  1015  1464 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 15:44:52.090  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 15:44:52.090  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-30 15:44:52.090  1296  1296 D HeadsetProfile: Bluetooth service connected
,08-30 15:44:52.090  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:52.090  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.090  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.090  1426  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 15:44:52.090  1426  2846 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:44:52.090  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 15:44:52.090  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 15:44:52.090  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:52.090  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.090  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.090  1426  2846 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 15:44:52.090  1296  1306 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 15:44:52.100  7243  7350 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-30 15:44:52.100  1296  1296 D BluetoothMap: Proxy object connected
,08-30 15:44:52.100  1296  1296 D MapProfile: Bluetooth service connected
08-30 15:44:52.100  1296  1296 D BluetoothMap: getConnectedDevices()
,08-30 15:44:52.100  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-30 15:44:52.100  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-30 15:44:52.100  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:52.100  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.100  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.100  1296  1296 D BluetoothInputDevice: Proxy object connected
08-30 15:44:52.100  1296  1296 D HidProfile: Bluetooth service connected
08-30 15:44:52.100  6615  6623 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:44:52.100  6615  6623 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:44:52.100  7243  7350 D BluetoothSocket: bindListen(): myUserId = 0
08-30 15:44:52.100  7243  7350 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:44:52.100  1905  1913 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:44:52.100  1905  1913 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:44:52.100  1455  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:44:52.100  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 15:44:52.100  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 15:44:52.100  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:52.100  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.100  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.110  1455  1476 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 15:44:52.110  1015  1044 D BluetoothPan: Binding service...
,08-30 15:44:52.110  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 15:44:52.110  7243  7350 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-30 15:44:52.110  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 15:44:52.110  7243  7350 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 15:44:52.110  7243  7350 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 15:44:52.110  7243  7350 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d5ec86e
,08-30 15:44:52.110  1296  1314 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 15:44:52.110  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 15:44:52.110  7243  7350 D BluetoothSocket: channel: 19
08-30 15:44:52.110  7243  7350 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 15:44:52.110  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 15:44:52.110  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 15:44:52.110  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:52.110  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.110  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.110  1296  1296 D BluetoothPbap: Proxy object connected
,08-30 15:44:52.110  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:44:52.110  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 15:44:52.110  1296  1296 D PbapServerProfile: Bluetooth service connected
08-30 15:44:52.110  1296  1306 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 15:44:52.110  1296  1306 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:44:52.110  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 15:44:52.110  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 15:44:52.120  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:52.120  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.120  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.120  1296  1296 D BluetoothA2dp: Proxy object connected
08-30 15:44:52.120  1296  1296 D A2dpProfile: Bluetooth service connected
,08-30 15:44:52.120  1175  1890 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:44:52.120  1175  1890 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 15:44:52.120  1296  6698 D BluetoothPan: Binding service...
,08-30 15:44:52.120  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 15:44:52.120  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 15:44:52.120  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:52.120  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.120  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.120  1296  1314 D Bluetoothsap: onBluetoothStateChange: up=true
,08-30 15:44:52.120  1296  1314 D Bluetoothsap: Binding service...
,08-30 15:44:52.120  1296  1296 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 15:44:52.120  1296  1296 D PanProfile: Bluetooth service connected
,08-30 15:44:52.120  1296  1314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-30 15:44:52.130  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-30 15:44:52.130  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 15:44:52.130  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:52.130  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.130  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.130  1296  1314 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 15:44:52.130  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-30 15:44:52.130  7243  7262 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:44:52.130  7243  7262 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:44:52.130  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 15:44:52.130  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-30 15:44:52.130  1296  1296 D SapProfile: Bluetooth service connected
,08-30 15:44:52.130  1296  1296 D Bluetoothsap: getConnectedDevices()
08-30 15:44:52.130  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 15:44:52.130  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 15:44:52.130  1015  1015 D BluetoothA2dp: Proxy object connected
08-30 15:44:52.130  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 15:44:52.130  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 15:44:52.140  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-30 15:44:52.140  1426  1426 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@10338dca, true
08-30 15:44:52.140  1426  1426 D BluetoothHeadset: registerMessageListener
08-30 15:44:52.140  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 15:44:52.140  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:52.140  1175  1175 D BluetoothTile:  getBluetoothState : 12
,08-30 15:44:52.140  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 15:44:52.150  1794  1794 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 15:44:52.150  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:52.150  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 15:44:52.150  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:52.160  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:52.160  1015  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:44:52.160  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 15:44:52.160  7243  7252 D HeadsetService: registerMessageListener
08-30 15:44:52.160  7243  7354 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-30 15:44:52.160  1015  1504 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 15:44:52.160  7243  7252 D HeadsetService: registerMessageListener
,08-30 15:44:52.160  7243  7273 D HeadsetStateMachine: Disconnected process message: 70
08-30 15:44:52.160  7243  7273 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@35810b0f
,08-30 15:44:52.160  1426  1426 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 15:44:52.160  1426  1426 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 15:44:52.160  1015  1464 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-30 15:44:52.160  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 15:44:52.160  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:52.160  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:52.160  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:52.170  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:52.170  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-30 15:44:52.170  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 15:44:52.170  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 15:44:52.170  1426  1426 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-30 15:44:52.170  1426  1426 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-30 15:44:52.170  1426  1426 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-30 15:44:52.170  7243  7273 D HeadsetStateMachine: Disconnected process message: 9
08-30 15:44:52.170  1296  1296 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-30 15:44:52.170  1296  1296 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-30 15:44:52.170  1296  1296 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 15:44:52.170  1296  1296 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-30 15:44:52.170  7243  7354 D BluetoothSocket: bindListen(): myUserId = 0
08-30 15:44:52.170  7243  7354 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:44:52.170  7243  7273 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-30 15:44:52.170  7243  7354 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-30 15:44:52.170  7243  7354 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 15:44:52.170  7243  7354 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 15:44:52.170  7243  7354 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ea779c
,08-30 15:44:52.170  7243  7354 D BluetoothSocket: channel: 5
,08-30 15:44:52.180   283  6841 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-30 15:44:52.180   283  6841 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 15:44:52.180   283  6841 V voice   : voice_set_parameters: exit with code(-2)
08-30 15:44:52.180   283  6841 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-30 15:44:52.180   283  6841 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 15:44:52.180   283  6841 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 15:44:52.180   283  6841 V audio_hw_primary: adev_set_parameters: exit
08-30 15:44:52.180  7243  7273 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-30 15:44:52.190  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:44:52.190  1015  1678 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 15:44:52.190  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 15:44:52.190  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:52.190  1015  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.190  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 15:44:52.200  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:44:52.200  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 15:44:52.210  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:52.210  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 15:44:52.210  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:52.210  7243  7243 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 15:44:52.210  1015  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 15:44:52.210  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 15:44:52.220  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:52.220  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:52.220  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:52.230  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 15:44:52.230  1015  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 15:44:52.230  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 15:44:52.230  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:52.240  1015  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:52.240  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:52.240  1905  7360 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 15:44:52.240  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 15:44:52.240  1015  2020 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:52.250  1015  2020 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:52.250  1015  2020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 15:44:52.250  1015  2020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:52.260   288   288 E SMD     : DCD OFF,
,08-30 15:44:52.260  1015  1477 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,08-30 15:44:52.270  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:52.270  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:52.270  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:52.270  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:52.280  7243  7364 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 15:44:52.280  7243  7364 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:44:52.280  1905  7360 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-30 15:44:52.280  7243  7364 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-30 15:44:52.280  7243  7364 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 15:44:52.280  7243  7364 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 15:44:52.280  7243  7364 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3fe37746
08-30 15:44:52.280  7243  7364 D BluetoothSocket: channel: 12
08-30 15:44:52.280  7243  7364 I BtOppRfcommListener: Accept thread started.
,08-30 15:44:53.910  6615  6668 D BluetoothAdapter: disable()
,08-30 15:44:53.920  1015  1133 D SettingsProvider: name = bluetooth_on
,08-30 15:44:53.930  7243  7258 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-30 15:44:53.930  7243  7258 D BluetoothAdapterProperties: Setting state to 13
08-30 15:44:53.930  7243  7258 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 15:44:53.930  7243  7258 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 15:44:53.930  7243  7258 D BluetoothAdapterService: updateAdapterState state is 13
,08-30 15:44:53.930  1015  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 15:44:53.930  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 15:44:53.930  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:53.930  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:53.930  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:53.930  7243  7243 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-30 15:44:53.930  7243  7258 D BluetoothAdapterService: Autoconnection is available 
,08-30 15:44:53.930  7243  7258 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-30 15:44:53.930  7243  7258 D BluetoothAdapterService: terminating service from this receiver
08-30 15:44:53.940  7243  7243 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8554d07, channel: 19, state: LISTENING
08-30 15:44:53.940  7243  7243 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@8554d07, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d5ec86e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24341e34mSocket: android.net.LocalSocket@1b9ce45d impl:android.net.LocalSocketImpl@c4fc1d2 fd:FileDescriptor[74]
08-30 15:44:53.940  7243  7243 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1b9ce45d impl:android.net.LocalSocketImpl@c4fc1d2 fd:FileDescriptor[74]
,08-30 15:44:53.940  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 15:44:53.940  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:53.940  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 15:44:53.940  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:53.950  7243  7258 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 15:44:53.950  1296  1296 D BluetoothPbap: Proxy object disconnected
08-30 15:44:53.950  1296  1296 D PbapServerProfile: Bluetooth service disconnected
,08-30 15:44:53.950  7243  7258 D BluetoothAdapterProperties: mDiscovering is false
,08-30 15:44:53.950  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:53.950  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-30 15:44:53.950  1015  1133 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 15:44:53.950  7243  7258 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 15:44:53.960  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-30 15:44:53.960  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 15:44:53.960  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 15:44:53.960  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:53.970  1175  1175 D BluetoothTile:  getBluetoothState : 13
,08-30 15:44:53.970  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 15:44:53.970  1794  1794 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 15:44:53.970  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Bluetooth,
08-30 15:44:53.970  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:53.980  1015  1462 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 15:44:53.980  1015  1504 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 15:44:53.980  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 15:44:53.980  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:44:53.980  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:53.980  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:53.980  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:53.980  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:53.980  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:53.980  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:53.980  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:53.980  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:44:53.980  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:53.980  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:44:53.980  1015  1215 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 15:44:53.980  1015  1215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 15:44:53.990  7243  7261 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 15:44:53.990  7243  7261 D BluetoothAdapterProperties: Scan Mode:20,
08-30 15:44:53.990  1015  1215 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:53.990  1015  1215 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:53.990  1015  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:53.990  7243  7258 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-30 15:44:53.990  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:53.990  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:53.990  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:53.990  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:44:53.990  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:53.990  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:53.990  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:53.990  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:53.990  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:44:54.000  7243  7258 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-30 15:44:54.000  7243  7258 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-30 15:44:54.000  7243  7258 E bt-btif : cmd socket is not created
,08-30 15:44:54.000  7243  7364 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:44:54.000  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.000  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:44:54.000  7243  7258 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 15:44:54.000  7243  7299 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-30 15:44:54.000  7243  7299 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 15:44:54.000  7243  7299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:44:54.000  7243  7299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:44:54.000  7243  7299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 15:44:54.000  7243  7243 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@260ee9a0, channel: 5, state: LISTENING
08-30 15:44:54.000  7243  7243 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@260ee9a0, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ea779c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@11486959mSocket: android.net.LocalSocket@3fc4291e impl:android.net.LocalSocketImpl@1640d5ff fd:FileDescriptor[76]
08-30 15:44:54.000  7243  7243 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3fc4291e impl:android.net.LocalSocketImpl@1640d5ff fd:FileDescriptor[76]
,08-30 15:44:54.000  7243  7243 I BtOppRfcommListener: stopping Accept Thread
08-30 15:44:54.000  7243  7243 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d08ffcc, channel: 12, state: LISTENING
08-30 15:44:54.000  7243  7243 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3d08ffcc, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3fe37746, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e8d4215mSocket: android.net.LocalSocket@3d85b92a impl:android.net.LocalSocketImpl@10d6d31b fd:FileDescriptor[79]
08-30 15:44:54.000  7243  7243 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d85b92a impl:android.net.LocalSocketImpl@10d6d31b fd:FileDescriptor[79]
,08-30 15:44:54.000  7243  7364 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 15:44:54.000  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:44:54.010  1015  1409 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 15:44:54.010  1015  1409 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 15:44:54.010  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:54.010  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:54.010  1015  1409 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:54.010  1015  1409 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 15:44:54.010  1015  1409 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 15:44:54.020  7243  7243 V BluetoothOppManager: cleanUp...
,08-30 15:44:54.030  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:44:54.030  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 15:44:54.040  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:54.040  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 15:44:54.060  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 15:44:54.060  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 15:44:54.210  7243  7299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 15:44:54.210  7243  7299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:44:54.210  7243  7299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:44:54.210  7243  7299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:44:54.210  7243  7299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:44:54.210  7243  7299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:44:54.210  7243  7299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:44:54.210  7243  7299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:44:54.210  7243  7299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:44:54.210  7243  7299 W bt-btif : ag scb idx 1 not allocated
08-30 15:44:54.210  7243  7299 W bt-btif : ag scb idx 2 not allocated
08-30 15:44:54.210  7243  7299 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 15:44:54.210  7243  7344 I bt_userial_mct: exiting userial_read_thread
08-30 15:44:54.210  7243  7344 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 15:44:54.210  7243  7261 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 15:44:54.210  7243  7301 I bt_vendor: hw_epilog_process
08-30 15:44:54.210  7243  7261 D bt_userial_mct: userial_close
08-30 15:44:54.210  7243  7261 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 15:44:55.240  7243  7261 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-30 15:44:55.240  7243  7261 I bt_vendor: bluetooth satus is on
,08-30 15:44:55.240  7243  7261 I bt_vendor: bt-vendor : resetting BT status
08-30 15:44:55.240  7243  7261 I bt_vendor: Starting hciattach daemon
,08-30 15:44:55.240  7243  7261 I bt_vendor: try to set false
,08-30 15:44:55.240  7243  7261 I bt_vendor: Starting hciattach daemon,
08-30 15:44:55.240  7243  7261 I bt_vendor: try to set false
,08-30 15:44:55.240  7243  7261 I bt_vendor: cleanup,
,08-30 15:44:55.240  7243  7299 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-30 15:44:55.240  7243  7261 I GKI_LINUX: GKI_exit_task 0 done,
,08-30 15:44:55.240  7243  7261 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-30 15:44:55.250  7243  7258 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
08-30 15:44:55.250  7243  7258 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 15:44:55.250  1015  1409 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 15:44:55.250  7243  7258 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
08-30 15:44:55.250  1015  1409 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 15:44:55.250  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
08-30 15:44:55.250  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 15:44:55.250  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-30 15:44:55.250  1015  1409 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:55.250  1015  1409 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:55.250  1015  1409 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 15:44:55.250  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
08-30 15:44:55.250  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 15:44:55.250  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-30 15:44:55.250  1015  1462 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:55.260  7243  7243 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 15:44:55.250  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 15:44:55.260  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:55.260  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-30 15:44:55.260  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-30 15:44:55.260   288   288 E SMD     : DCD OFF
08-30 15:44:55.260  1015  1464 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 15:44:55.260  7243  7243 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 15:44:55.260  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 15:44:55.260  7243  7243 D BtGatt.GattService: stop()
08-30 15:44:55.260  7243  7243 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 15:44:55.260  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 15:44:55.260  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 15:44:55.260  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-30 15:44:55.260  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
08-30 15:44:55.260  1015  1464 W ActivityManager: userId = 0, bbcId = -10000,
08-30 15:44:55.260  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:55.260  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:55.260  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 15:44:55.260  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 15:44:55.260  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-30 15:44:55.270  7243  7243 D HeadsetService: Received stop request...Stopping profile...
08-30 15:44:55.270  1015  1409 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:55.270  1015  1409 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 15:44:55.270  1015  1409 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:55.270  1015  1409 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:55.270  1015  1409 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 15:44:55.270  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 15:44:55.270  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 15:44:55.270  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-30 15:44:55.270  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:55.270  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:55.270  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 15:44:55.270  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:55.270  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:55.270  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:55.270  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-30 15:44:55.270  1296  1296 D HeadsetProfile: Bluetooth service disconnected
08-30 15:44:55.270  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 15:44:55.270  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 15:44:55.270  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-30 15:44:55.280  1015  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:55.280  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 15:44:55.280  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:55.280  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:55.280  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 15:44:55.280  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 15:44:55.280  1015  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:55.280  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 15:44:55.280  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:55.280  1015  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:55.280  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 15:44:55.280  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 15:44:55.280  1015  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:44:55.280  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 15:44:55.280  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:55.280  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:44:55.280  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:44:55.280  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:55.280  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 15:44:55.280  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 15:44:55.280  7243  7258 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 15:44:55.280  7243  7258 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 15:44:55.280  7243  7258 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 15:44:55.290  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-30 15:44:55.290  7243  7243 D A2dpService: Received stop request...Stopping profile...
08-30 15:44:55.290  7243  7287 D A2dpStateMachine: Exit Disconnected: -1
,08-30 15:44:55.290  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:55.290  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-30 15:44:55.290  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-30 15:44:55.290  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-30 15:44:55.290  1296  1296 D BluetoothA2dp: Proxy object disconnected
08-30 15:44:55.290  1296  1296 D A2dpProfile: Bluetooth service disconnected
08-30 15:44:55.290  7243  7243 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 15:44:55.290  7243  7243 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 15:44:55.290  7243  7243 D HidService: Received stop request...Stopping profile...
08-30 15:44:55.290  7243  7243 D HidService: Stopping Bluetooth HidService
08-30 15:44:55.290  7243  7243 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 15:44:55.290  7243  7243 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 15:44:55.290  7243  7243 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 15:44:55.290  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:55.290  1296  1296 D BluetoothInputDevice: Proxy object disconnected
08-30 15:44:55.290  1296  1296 D HidProfile: Bluetooth service disconnected
,08-30 15:44:55.290  7243  7243 D HealthService: Received stop request...Stopping profile...
,08-30 15:44:55.290  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:55.300  7243  7243 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 15:44:55.300  7243  7243 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 15:44:55.300  7243  7243 D PanService: Received stop request...Stopping profile...
,08-30 15:44:55.300  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:55.300  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 15:44:55.300  7243  7243 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 15:44:55.300  1296  1296 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 15:44:55.300  1296  1296 D PanProfile: Bluetooth service disconnected
,08-30 15:44:55.310  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:55.310  7243  7243 D SapService: Received stop request...Stopping profile...
08-30 15:44:55.310  7243  7243 D SapService: Stopping Bluetooth SapService
08-30 15:44:55.310  7243  7243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2729dd74
,08-30 15:44:55.310  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-30 15:44:55.310  7243  7243 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 15:44:55.310  7243  7243 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 15:44:55.310  7243  7243 D BluetoothA2dp: Proxy object disconnected
08-30 15:44:55.310  7243  7243 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-30 15:44:55.310  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 15:44:55.310  7243  7243 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:55.310  7243  7243 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-30 15:44:55.310  7243  7288 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-30 15:44:55.310  7243  7243 I GKI_LINUX: GKI_exit_task 2 done
08-30 15:44:55.310  7243  7243 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 15:44:55.310  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 15:44:55.310  7243  7243 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:55.310  7243  7243 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:55.310  7243  7243 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 15:44:55.310  7243  7243 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:44:55.310  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-30 15:44:55.310  7243  7243 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:55.310  7243  7243 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 15:44:55.310  7243  7243 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 15:44:55.310  7243  7243 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 15:44:55.310  1296  1296 D BluetoothMap: Proxy object disconnected
,08-30 15:44:55.310  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-30 15:44:55.310  7243  7243 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 15:44:55.310  7243  7243 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-30 15:44:55.310  7243  7243 E BluetoothAdapterService(657055092): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-30 15:44:55.320  1296  1296 D MapProfile: Bluetooth service disconnected
,08-30 15:44:55.320  7243  7243 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 15:44:55.320  7243  7243 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-30 15:44:55.320  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 15:44:55.320  1296  1296 D SapProfile: Bluetooth service disconnected
,08-30 15:44:55.320  7243  7258 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-30 15:44:55.320  7243  7258 D BluetoothAdapterProperties: Setting state to 10
08-30 15:44:55.320  7243  7258 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-30 15:44:55.320  7243  7258 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-30 15:44:55.320  7243  7258 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 15:44:55.320  7243  7258 D BluetoothAdapterService: Autoconnection is available ,
,08-30 15:44:55.320  7243  7258 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-30 15:44:55.320  7243  7258 I BluetoothAdapterState: Entering OffState
,08-30 15:44:55.320  1426  1439 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:55.320  1426  1439 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 15:44:55.320  7243  7252 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 15:44:55.320  1296  1314 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:55.320  1296  1314 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:55.330  1455  1478 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 15:44:55.330  1455  1478 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:55.330  1440  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:55.330  1440  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:55.330  7293  7305 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:55.330  7293  7305 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:55.330  1296  1306 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 15:44:55.330  1296  1314 D BluetoothInputDevice: onBluetoothStateChange: up=false,
,08-30 15:44:55.330  6615  6623 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:55.330  6615  6623 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:55.330  6615  6623 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 15:44:55.330  6615  6623 D BluetoothLeAdvertiser: Exit stop advertising
,08-30 15:44:55.330  6615  6623 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 15:44:55.330  6615  6623 D BluetoothLeScanner: Exiting stopAllScan
08-30 15:44:55.330  1905  1916 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:55.330  1905  1916 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:55.330  1296  6698 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 15:44:55.330  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 15:44:55.330  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:55.330  1296  1306 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:44:55.330  1175  1210 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:55.330  1175  1210 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:55.330  1296  6698 D Bluetoothsap: onBluetoothStateChange: up=false,
08-30 15:44:55.330  1296  6698 D Bluetoothsap: Unbinding service...
08-30 15:44:55.330  7243  7353 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 15:44:55.330  7243  7353 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 15:44:55.330  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:44:55.330  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 15:44:55.340  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 15:44:55.340  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:55.340  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-30 15:44:55.340  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 15:44:55.350  7243  7261 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 15:44:55.350  1175  1175 D BluetoothAdapter: 357474663: getState() :  mService = null. Returning STATE_OFF
08-30 15:44:55.350  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 15:44:55.350  1175  1717 D BluetoothAdapter: 357474663: getState() :  mService = null. Returning STATE_OFF
,08-30 15:44:55.350  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:55.350  1175  1175 D BluetoothTile:  getBluetoothState : 10
08-30 15:44:55.350  1175  1717 D BluetoothAdapter: 357474663: getState() :  mService = null. Returning STATE_OFF
,08-30 15:44:55.350  7243  7243 I GKI_LINUX: GKI_exit_task 1 done
08-30 15:44:55.350  7243  7243 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 15:44:55.350  7243  7243 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 15:44:55.350  1175  1175 D BluetoothAdapter: 357474663: getState() :  mService = null. Returning STATE_OFF
08-30 15:44:55.350  1175  1175 D BluetoothAdapter: 357474663: getState() :  mService = null. Returning STATE_OFF
,08-30 15:44:55.350  1015  2020 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 15:44:55.350  1794  1794 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 15:44:55.350  1015  1480 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 15:44:55.350  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 15:44:55.350  1905  2121 D BluetoothAdapter: 415431216: getState() :  mService = null. Returning STATE_OFF
,08-30 15:44:55.350  7243  7243 I art     : System.exit called, status: 0
,08-30 15:44:55.350  7243  7243 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 15:44:55.350  1905  2121 D BluetoothAdapter: 415431216: getState() :  mService = null. Returning STATE_OFF
08-30 15:44:55.350  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:44:55.360  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:55.360  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:55.360  1015  1464 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:44:55.360  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 15:44:55.360  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:55.360  1015  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:55.360  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 15:44:55.360  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:44:55.360  1015  1678 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 15:44:55.360  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 15:44:55.360  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:44:55.360  1015  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 15:44:55.360  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 15:44:55.380  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:44:55.380  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 15:44:55.380  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:55.380  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 15:44:55.380  1015  2020 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!,
,08-30 15:44:55.390  1015  2020 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 15:44:55.390  1015  2020 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-30 15:44:55.390  1015  2020 W BroadcastQueue: android.os.TransactionTooLargeException
08-30 15:44:55.390  1015  2020 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 15:44:55.390  1015  2020 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 15:44:55.390  1015  2020 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-30 15:44:55.390  1015  2020 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-30 15:44:55.390  1015  2020 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-30 15:44:55.390  1015  2020 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-30 15:44:55.390  1015  2020 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-30 15:44:55.390  1015  2020 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-30 15:44:55.390  1015  2020 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 15:44:55.390  1015  2020 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-30 15:44:55.400  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:55.400  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:55.400  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:44:55.400  1015  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:44:55.410  1015  2020 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7381 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-30 15:44:55.410  7381  7381 E Zygote  : MountEmulatedStorage()
08-30 15:44:55.410  7381  7381 E Zygote  : v2
08-30 15:44:55.410  7381  7381 I libpersona: KNOX_SDCARD checking this for 1002
08-30 15:44:55.410  7381  7381 I libpersona: KNOX_SDCARD not a persona
,08-30 15:44:55.410  7381  7381 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:44:55.420  7381  7381 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 15:44:55.420  7381  7381 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:44:55.430  7381  7381 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:44:55.440  7381  7381 D ActivityThread: Added TimaKeyStore provider
,08-30 15:44:55.450  7381  7381 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 15:44:55.450  7381  7381 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 15:44:55.470  7381  7381 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding GattService
,08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding HeadsetService
08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding A2dpService
,08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding HidService
08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding HealthService
08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding PanService
,08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding SapService
08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding SapClientService
08-30 15:44:55.500  7381  7381 D BtSettings.ProfileConfig: Adding HidDevService
08-30 15:44:55.500  7381  7381 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-30 15:44:55.510  1015  1504 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-30 15:44:55.510  1015  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.510  1015  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:55.510  1015  1504 D SettingsProvider: selectionArgs: false
08-30 15:44:55.510  1015  1504 D SettingsProvider: selectionArgs: 1002
08-30 15:44:55.510  1015  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:55.510  1015  1504 D SettingsProvider: ret = -1
,08-30 15:44:55.510  1015  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-30 15:44:55.510  1015  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.510  1015  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 15:44:55.510  1015  1480 D SettingsProvider: selectionArgs: false
08-30 15:44:55.510  1015  1480 D SettingsProvider: selectionArgs: 1002
08-30 15:44:55.510  1015  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 15:44:55.510  1015  1480 D SettingsProvider: ret = -1
,08-30 15:44:55.510  1015  1462 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-30 15:44:55.510  1015  1462 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.510  1015  1462 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:55.510  1015  1462 D SettingsProvider: selectionArgs: false
08-30 15:44:55.510  1015  1462 D SettingsProvider: selectionArgs: 1002
08-30 15:44:55.510  1015  1462 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:55.510  1015  1462 D SettingsProvider: ret = -1
,08-30 15:44:55.510  1015  1678 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-30 15:44:55.510  1015  1678 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.510  1015  1678 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:55.510  1015  1678 D SettingsProvider: selectionArgs: false
08-30 15:44:55.510  1015  1678 D SettingsProvider: selectionArgs: 1002
08-30 15:44:55.510  1015  1678 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:55.510  1015  1678 D SettingsProvider: ret = -1
,08-30 15:44:55.510  1015  1464 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-30 15:44:55.510  1015  1464 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.510  1015  1464 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:55.510  1015  1464 D SettingsProvider: selectionArgs: false
,08-30 15:44:55.510  1015  1464 D SettingsProvider: selectionArgs: 1002
08-30 15:44:55.510  1015  1464 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:55.510  1015  1464 D SettingsProvider: ret = -1
,08-30 15:44:55.510  1015  2020 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-30 15:44:55.510  1015  2020 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.510  1015  2020 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 15:44:55.510  1015  2020 D SettingsProvider: selectionArgs: false
,08-30 15:44:55.510  1015  2020 D SettingsProvider: selectionArgs: 1002
08-30 15:44:55.510  1015  2020 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:55.510  1015  2020 D SettingsProvider: ret = -1
,08-30 15:44:55.510  1015  1409 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-30 15:44:55.510  1015  1409 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.510  1015  1409 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:55.510  1015  1409 D SettingsProvider: selectionArgs: false
08-30 15:44:55.510  1015  1409 D SettingsProvider: selectionArgs: 1002
08-30 15:44:55.510  1015  1409 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:55.510  1015  1409 D SettingsProvider: ret = -1
,08-30 15:44:55.520  1015  1479 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-30 15:44:55.520  1015  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.520  1015  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 15:44:55.520  1015  1479 D SettingsProvider: selectionArgs: false
08-30 15:44:55.520  1015  1479 D SettingsProvider: selectionArgs: 1002
08-30 15:44:55.520  1015  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:55.520  1015  1479 D SettingsProvider: ret = -1
,08-30 15:44:55.520  1015  1215 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:44:55.520  1015  1215 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.520  1015  1215 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 15:44:55.520  1015  1215 D SettingsProvider: selectionArgs: false
08-30 15:44:55.520  1015  1215 D SettingsProvider: selectionArgs: 1002
08-30 15:44:55.520  1015  1215 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:55.520  1015  1215 D SettingsProvider: ret = -1
,08-30 15:44:55.520  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:44:55.520  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.520  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:55.520  1015  1133 D SettingsProvider: selectionArgs: false
08-30 15:44:55.520  1015  1133 D SettingsProvider: selectionArgs: 1002
,08-30 15:44:55.520  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:55.520  1015  1133 D SettingsProvider: ret = -1
,08-30 15:44:55.520  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-30 15:44:55.520  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.520  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 15:44:55.520  1015  1028 D SettingsProvider: selectionArgs: false
08-30 15:44:55.520  1015  1028 D SettingsProvider: selectionArgs: 1002
08-30 15:44:55.520  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:44:55.520  1015  1028 D SettingsProvider: ret = -1
08-30 15:44:55.520  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-30 15:44:55.520  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:44:55.520  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:44:55.520  1015  1027 D SettingsProvider: selectionArgs: false
08-30 15:44:55.520  1015  1027 D SettingsProvider: selectionArgs: 1002
08-30 15:44:55.520  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 15:44:55.520  1015  1027 D SettingsProvider: ret = -1
,08-30 15:44:55.530  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 15:44:55.530  1015  1409 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 15:44:55.530  1015  1409 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 15:44:55.530  1015  1409 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:55.530  1015  1409 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:55.530  1015  1409 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:55.540  1905  7397 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 15:44:55.540  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 15:44:55.550  1015  1462 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:44:55.550  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:44:55.550  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:44:55.550  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:44:55.560  1905  7397 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-30 15:44:56.930  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:44:56.930  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:44:57.440  1015  1215 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-30 15:44:57.440  1015  1215 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
,08-30 15:44:57.440  1015  1215 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 15:44:57.440  1015  1215 D BatteryService: stay LED for fully charged,
08-30 15:44:57.440  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 15:44:57.450  1015  1015 I MotionRecognitionService: Plugged,
08-30 15:44:57.450  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 15:44:57.450  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 15:44:57.450  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 15:44:57.450  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 15:44:57.450  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 15:44:57.470  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 15:44:57.470  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 15:44:57.480  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 15:44:57.480  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-30 15:44:57.480  1175  1175 D SViewCoverView: level :100 plugged : 2
,08-30 15:44:58.240  1015  2894 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 15:44:58.260   288   288 E SMD     : DCD OFF,
,08-30 15:44:58.930  1015  2844 D SSRM:n  : SIOP:: AP = 340,
,08-30 15:44:59.570  1015  1325 E Watchdog: !@Sync 4
,08-30 15:44:59.930  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:44:59.930  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1600b7e9 added. We now have 6 listener(s)
,08-30 15:44:59.930  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:44:59.930  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-30 15:44:59.930  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d8d7c6e added. We now have 7 listener(s)
08-30 15:44:59.930  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-30 15:44:59.930  6615  6668 I System.out: IsBluetoothEnabled
08-30 15:44:59.930  6615  6668 D BluetoothAdapter: disable(),
08-30 15:44:59.930  1015  1479 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-30 15:44:59.940  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-30 15:44:59.940  6615  6668 D BluetoothAdapter: enable(),
,08-30 15:44:59.950  1015  1133 W ActivityManager: Permission Denial: getCurrentUser() from pid=6615, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-30 15:44:59.950  1015  1133 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-30 15:44:59.950  1015  1133 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6615, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-30 15:44:59.950  1015  1133 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 15:44:59.950  1015  1133 W BluetoothManagerService: 	,at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-30 15:44:59.950  1015  1133 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-30 15:44:59.950  1015  1133 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-30 15:44:59.950  1015  1133 W BluetoothManagerService: ,	at android.os.Binder.execTransact(Binder.java:446)
,08-30 15:44:59.950  1015  1133 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 15:44:59.950  1015  1133 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 15:44:59.950  1015  1133 D SettingsProvider: name = bluetooth_on
,08-30 15:44:59.960  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 15:44:59.960  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 15:44:59.960  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
,08-30 15:44:59.960  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2,
,08-30 15:44:59.990  1015  1093 V AlarmManager: waitForAlarm result :8
,08-30 15:44:59.990  7381  7381 D BluetoothAdapterState: make
,08-30 15:45:00.000  7381  7381 I bluedroid: init
,08-30 15:45:00.000  7381  7381 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 15:45:00.000  7381  7381 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 15:45:00.000  7381  7381 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 15:45:00.000  7381  7381 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 15:45:00.000  7381  7403 I BluetoothAdapterState: Entering OffState
,08-30 15:45:00.000  7381  7381 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-30 15:45:00.000  7381  7381 I bluedroid: get_profile_interface socket
08-30 15:45:00.000  7381  7381 I bluedroid: get_profile_interface map_client
08-30 15:45:00.010  7381  7406 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-30 15:45:00.010  7381  7381 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-30 15:45:00.010  7381  7406 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-30 15:45:00.010  7381  7406 E BluetoothServiceJni: populateRssiValuesNative
08-30 15:45:00.010  7381  7406 I bluedroid: getModelRssiValues
,08-30 15:45:00.010  7381  7406 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 15:45:00.010  7381  7406 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 15:45:00.020  7381  7406 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-30 15:45:00.020  1015  1015 D SettingsProvider: name = bluetooth_name
08-30 15:45:00.020  7381  7381 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:45:00.020  1015  1409 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 15:45:00.020  1015  1409 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.020  1015  1409 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:00.020  1015  1409 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.020  1015  1409 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.020  7381  7389 I bluedroid: config_hci_snoop_log
,08-30 15:45:00.020  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 15:45:00.030  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-30 15:45:00.030  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-30 15:45:00.030  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-30 15:45:00.030  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 15:45:00.030  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 15:45:00.030  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 15:45:00.040  7381  7381 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-30 15:45:00.040  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 15:45:00.040  7381  7403 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-30 15:45:00.040  7381  7403 D BluetoothAdapterProperties: Setting state to 11
,08-30 15:45:00.040  7381  7403 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-30 15:45:00.040  7381  7403 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-30 15:45:00.040  7381  7403 D BluetoothAdapterService: updateAdapterState state is 11
,08-30 15:45:00.040  7381  7403 D BluetoothAdapterService: Autoconnection is available 
,08-30 15:45:00.050  7381  7403 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-30 15:45:00.050  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:45:00.050  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-30 15:45:00.050  7381  7403 D BluetoothSecureManager: getInstant: null
08-30 15:45:00.050  7381  7403 D BluetoothSecureManager: calling getMethod for getService
08-30 15:45:00.050  7381  7403 D BluetoothSecureManager: calling getService
,08-30 15:45:00.060  7381  7403 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@51e7f8
08-30 15:45:00.060  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 15:45:00.060  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:00.060  1175  1175 D BluetoothTile:  getBluetoothState : 11
,08-30 15:45:00.060  1015  1479 D BluetoothSecureManagerService: isSecureModeEnabled,
08-30 15:45:00.060  1015  1479 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable,
08-30 15:45:00.060  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
08-30 15:45:00.060  1794  1794 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0,
,08-30 15:45:00.060  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-30 15:45:00.060  7381  7403 D BtConfig.SecureMode: isSecureModeOn:false
08-30 15:45:00.060  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 15:45:00.060  7381  7403 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,08-30 15:45:00.060  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 15:45:00.060  7381  7403 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,08-30 15:45:00.060  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 15:45:00.060  7381  7403 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,08-30 15:45:00.060  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 15:45:00.070  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:00.070  7381  7403 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,08-30 15:45:00.070  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 15:45:00.070  1015  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 15:45:00.070  7381  7403 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-30 15:45:00.070  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 15:45:00.070  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:00.070  7381  7403 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-30 15:45:00.070  1015  1678 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-30 15:45:00.070  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:45:00.070  1015  2020 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:45:00.070  1015  2020 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.070  7381  7403 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-30 15:45:00.070  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 15:45:00.070  7381  7403 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-30 15:45:00.070  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 15:45:00.070  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 15:45:00.070  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 15:45:00.070  7381  7403 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:45:00.070  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 15:45:00.070  7381  7403 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:45:00.080  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 15:45:00.080  1015  2020 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:00.080  7381  7403 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-30 15:45:00.080  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 15:45:00.080  1015  2020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:45:00.080  7381  7403 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-30 15:45:00.080  1015  2020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 15:45:00.080  7381  7403 D BluetoothBondStateMachine: make
,08-30 15:45:00.080  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-30 15:45:00.080  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 15:45:00.080  7381  7403 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 15:45:00.080  7381  7407 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 15:45:00.080  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 15:45:00.090  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 15:45:00.090  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.090  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:45:00.090  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-30 15:45:00.090  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:00.090  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 15:45:00.090  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.090  7381  7381 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 15:45:00.090  7381  7381 D BtGatt.GattService: Received start request. Starting profile...
08-30 15:45:00.090  7381  7381 D BtGatt.GattService: start()
08-30 15:45:00.090  7381  7381 D BtGatt.GattService: start()
,08-30 15:45:00.090  7381  7381 I bluedroid: get_profile_interface gatt
,08-30 15:45:00.090  7381  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ea7b312
08-30 15:45:00.090  7381  7381 D BtGatt.AdvertiseManager: advertise manager created
,08-30 15:45:00.100  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 15:45:00.100  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 15:45:00.100  7381  7403 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 15:45:00.100  1015  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:45:00.100  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.100  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:00.100  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.100  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.110  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-30 15:45:00.110  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 15:45:00.110  7381  7403 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 15:45:00.110  7381  7381 D BtGatt.GattService: mStartError = false
,08-30 15:45:00.110  7381  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ea7b312
,08-30 15:45:00.120  1015  2020 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:45:00.120  1015  2020 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.120  1015  2020 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:00.120  1015  2020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.120  1015  2020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.120  7381  7381 D HeadsetService: Received start request. Starting profile...
08-30 15:45:00.120  7381  7381 D HeadsetService: start()
,08-30 15:45:00.120  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-30 15:45:00.120  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 15:45:00.120  7381  7403 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 15:45:00.120  7381  7381 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 15:45:00.120  7381  7381 D HeadsetStateMachine: make
08-30 15:45:00.120  1015  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:45:00.120  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.120  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:00.120  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.120  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.120  7381  7381 E HeadsetStateMachine: # of Max HF connection is 2
,08-30 15:45:00.130  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 15:45:00.130  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 15:45:00.130  7381  7403 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 15:45:00.130  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:45:00.130  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.130  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:00.130  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.130  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.130  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-30 15:45:00.130  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 15:45:00.130  7381  7403 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 15:45:00.130  1015  2020 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:45:00.130  1015  2020 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.130  1015  2020 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:00.130  1015  2020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.130  1015  2020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.140  1015  1409 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-30 15:45:00.140  1015  1409 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-30 15:45:00.140  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-30 15:45:00.140  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 15:45:00.140  7381  7403 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 15:45:00.140  1015  1409 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:00.140  1015  1409 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.140  1015  1409 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 15:45:00.140  1015  1462 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:45:00.140  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.140  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:00.140  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.140  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.140  1015  1133 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-30 15:45:00.140  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 15:45:00.140  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 15:45:00.140  7381  7403 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 15:45:00.140  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.140  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:00.140  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.140  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 15:45:00.140  7381  7381 I bluedroid: get_profile_interface handsfree
08-30 15:45:00.140  1015  1678 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:45:00.140  1015  1678 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.150  1015  1678 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:00.150  1015  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.150  1015  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.150  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:45:00.150  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:45:00.150  7381  7403 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 15:45:00.150  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:45:00.150  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:45:00.150  7381  7403 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 15:45:00.150  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 15:45:00.150  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 15:45:00.150  7381  7403 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 15:45:00.150  7381  7403 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 15:45:00.150  7381  7403 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 15:45:00.150  7381  7403 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 15:45:00.150  7381  7403 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 15:45:00.160  7381  7381 I DualScoManager: Instantiating Dual Sco Manager
,08-30 15:45:00.160  7381  7381 I DualScoManager: Set HeadsetServiceHelper
,08-30 15:45:00.160  7381  7381 D BluetoothAtMessage: createCMTIContentObservers
,08-30 15:45:00.160  1015  1464 D SettingsProvider: name = bluetooth_hfp_allowed_bvra,
08-30 15:45:00.160  1015  1464 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:45:00.160  1015  1464 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:45:00.160  1015  1464 D SettingsProvider: selectionArgs: false
,08-30 15:45:00.160  1015  1464 D SettingsProvider: selectionArgs: 1002,
08-30 15:45:00.160  1015  1464 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:45:00.160  1015  1464 D SettingsProvider: ret = -1
08-30 15:45:00.160  7381  7411 D HeadsetStateMachine: Enter Disconnected: -2
,08-30 15:45:00.170  7381  7381 D HeadsetService: mStartError = false
08-30 15:45:00.170  7381  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ea7b312
,08-30 15:45:00.170  7381  7381 E BluetoothAdapterService(514306834): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-30 15:45:00.170  7381  7411 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-30 15:45:00.170  7381  7411 D HeadsetStateMachine: map size, before remove : 0
08-30 15:45:00.170  7381  7411 D HeadsetStateMachine: map size, after remove: 0
,08-30 15:45:00.170  7381  7381 D A2dpService: Received start request. Starting profile...
08-30 15:45:00.170  7381  7381 D A2dpService: start()
,08-30 15:45:00.170  7381  7381 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 15:45:00.180  7381  7381 I bluedroid: get_profile_interface avrcp
,08-30 15:45:00.180  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 15:45:00.190  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 15:45:00.190  7381  7381 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 15:45:00.190  7381  7381 D Avrcp   : Initialize Media Controller
,08-30 15:45:00.190  7381  7381 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-30 15:45:00.190  7381  7381 E Avrcp   : getActiveSessions
,08-30 15:45:00.190  7381  7381 D Avrcp   : pick active media Controller
08-30 15:45:00.190  7381  7381 D Avrcp   : Get the active Media Controller 
,08-30 15:45:00.210  7381  7381 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 15:45:00.210  7381  7416 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-30 15:45:00.210  7381  7381 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:45:00.210  7381  7381 D A2dpStateMachine: make
,08-30 15:45:00.210  7381  7381 I bluedroid: get_profile_interface a2dp
,08-30 15:45:00.220  7381  7418 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 15:45:00.220  7381  7381 E bt-btif : warning : media task started media_task_refcnt 1 
,08-30 15:45:00.220  7381  7381 D A2dpService: mStartError = false
,08-30 15:45:00.220  7381  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ea7b312
,08-30 15:45:00.220  7381  7381 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 15:45:00.220  7381  7417 D A2dpStateMachine: Enter Disconnected: -2
,08-30 15:45:00.220  7381  7381 D HidService: Received start request. Starting profile...
08-30 15:45:00.220  7381  7381 D HidService: start()
08-30 15:45:00.220  7381  7381 I bluedroid: get_profile_interface hidhost
08-30 15:45:00.220  7381  7381 D HidService: setHidService(): set to: null
08-30 15:45:00.220  7381  7381 D HidService: mStartError = false
08-30 15:45:00.220  7381  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ea7b312
,08-30 15:45:00.220  7381  7381 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 15:45:00.230  7381  7381 D HealthService: Received start request. Starting profile...
,08-30 15:45:00.230  7381  7381 D HealthService: start()
,08-30 15:45:00.230  7381  7381 I bluedroid: get_profile_interface health
,08-30 15:45:00.230  7381  7381 D HealthService: mStartError = false
08-30 15:45:00.230  7381  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ea7b312
08-30 15:45:00.230  7381  7381 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 15:45:00.230   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 15:45:00.230  7381  7381 D PanService: Received start request. Starting profile...
08-30 15:45:00.230  7381  7381 D PanService: start()
08-30 15:45:00.230  7381  7381 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 15:45:00.230  7381  7381 I bluedroid: get_profile_interface pan
,08-30 15:45:00.230  7381  7381 D PanService: mStartError = false
08-30 15:45:00.230  7381  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ea7b312
,08-30 15:45:00.230  7381  7381 D HeadsetStateMachine: Try to query the phonestate on bind
,08-30 15:45:00.240  1426  1439 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 15:45:00.240  1426  1426 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-30 15:45:00.240  1426  1426 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 15:45:00.240  1426  1439 I Telecom : BluetoothPhoneService: Result of Message : true
,08-30 15:45:00.240  7381  7416 D BluetoothMediaBrowser: no now playing list
,08-30 15:45:00.240  7381  7416 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 15:45:00.240  7381  7381 D BluetoothMapService: Received start request. Starting profile...
,08-30 15:45:00.240  7381  7381 D BluetoothMapService: start()
,08-30 15:45:00.240  7381  7381 D BluetoothMapService: mStartError = false
,08-30 15:45:00.240  7381  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ea7b312
08-30 15:45:00.240  7381  7381 D HeadsetStateMachine: Proxy object connected
,08-30 15:45:00.240  7381  7381 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-30 15:45:00.250  7381  7381 D SapService: Received start request. Starting profile...
,08-30 15:45:00.250  7381  7381 D SapService: start()
08-30 15:45:00.250  7381  7381 D BluetoothSAPServiceJni: initializeNative(L209): sap
,08-30 15:45:00.250  7381  7381 I bluedroid: get_profile_interface sap
08-30 15:45:00.250  7381  7381 D SapService: mStartError = false
08-30 15:45:00.250  7381  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ea7b312
,08-30 15:45:00.250  7381  7381 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-30 15:45:00.250  7381  7411 D HeadsetStateMachine: Disconnected process message: 11
08-30 15:45:00.250  7381  7381 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-30 15:45:00.250  7381  7411 D HeadsetStateMachine: Disconnected process message: 18
08-30 15:45:00.250  7381  7381 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-30 15:45:00.250  7381  7381 E BluetoothAdapterService(514306834): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-30 15:45:00.250  7381  7381 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 15:45:00.250  7381  7381 D BluetoothA2dp: Proxy object connected
08-30 15:45:00.250  7381  7381 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-30 15:45:00.250  7381  7381 E BluetoothAdapterService(514306834): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 15:45:00.250  7381  7381 E BluetoothAdapterService(514306834): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-30 15:45:00.250  7381  7381 E BluetoothAdapterService(514306834): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-30 15:45:00.250  7381  7381 E BluetoothAdapterService(514306834): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-30 15:45:00.250  7381  7411 D HeadsetStateMachine: Disconnected process message: 10
08-30 15:45:00.250  7381  7411 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 15:45:00.250  7381  7411 D HeadsetStateMachine: Disconnected process message: 11
,08-30 15:45:00.280  7381  7381 E BluetoothAdapterService(514306834): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-30 15:45:00.280  7381  7381 E BluetoothAdapterService(514306834): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 15:45:00.280  7381  7403 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-30 15:45:00.280  7381  7403 I bluedroid: enable
,08-30 15:45:00.280  7381  7403 I bt_hci_bdroid: init
,08-30 15:45:00.280  7381  7422 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-30 15:45:00.280  7381  7403 I bt_vendor: bt-vendor : init
,08-30 15:45:00.280  7381  7403 I bt_vendor: bt-vendor : get_bt_soc_type
,08-30 15:45:00.290  7381  7403 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 15:45:00.290  7381  7403 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
,08-30 15:45:00.290  7381  7403 D bt_userial_mct: userial_init
,08-30 15:45:00.290  7381  7403 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 15:45:00.290  7381  7403 I bt_vendor: Starting hciattach daemon
,08-30 15:45:00.290  7381  7403 I bt_vendor: try to set false
,08-30 15:45:00.290  7381  7403 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-30 15:45:00.290  7381  7403 I bt_vendor: Starting hciattach daemon
08-30 15:45:00.290  7381  7403 I bt_vendor: try to set true
,08-30 15:45:00.310  7426  7426 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-30 15:45:00.360  7432  7432 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-30 15:45:00.360  7433  7433 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 15:45:00.380  7435  7435 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 15:45:00.390  7436  7436 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-30 15:45:00.400  7437  7437 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 15:45:00.410  7438  7438 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-30 15:45:00.610  7441  7441 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-30 15:45:00.620  7442  7442 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 15:45:00.650  7381  7403 I bt_vendor: bluetooth satus is on
,08-30 15:45:00.650  7381  7424 D bt_userial_mct: userial_open(port:0)
08-30 15:45:00.650  7381  7424 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 15:45:00.650  7381  7424 I bt_vendor: Done intiailizing UART,
08-30 15:45:00.650  7381  7424 I bt_vendor: Done intiailizing UART
08-30 15:45:00.650  7381  7424 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 15:45:00.650  7381  7424 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 15:45:00.650  7381  7444 D bt_userial_mct: Entering userial_read_thread()
,08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_BTM,
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_SAP
,08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 15:45:00.660  7381  7422 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-30 15:45:00.750  7381  7422 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-30 15:45:00.760  7381  7422 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4191ed1 
,08-30 15:45:00.760  7381  7422 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4191ed1 
,08-30 15:45:00.770  7381  7406 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-30 15:45:00.780  7381  7406 E bt-btif : Calling BTA_HhEnable
,08-30 15:45:00.780  7381  7406 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 15:45:00.780  7381  7406 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-30 15:45:00.780  7381  7406 E BluetoothServiceJni: populateRssiValuesNative
,08-30 15:45:00.780  7381  7406 I bluedroid: getModelRssiValues
,08-30 15:45:00.780  7381  7406 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 15:45:00.780  7381  7406 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 15:45:00.780  1015  1015 D SettingsProvider: name = bluetooth_name
,08-30 15:45:00.780  7381  7406 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-30 15:45:00.790  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:00.790  7381  7406 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 15:45:00.800  7381  7406 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:45:00.800  7381  7406 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 15:45:00.800  7381  7406 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-30 15:45:00.800  7381  7406 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-30 15:45:00.800  7381  7406 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-30 15:45:00.800  7381  7406 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-30 15:45:00.800  7381  7406 E bt-btif : btif_sock_init: !vhci_init
,08-30 15:45:00.800  7381  7406 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-30 15:45:00.800  7381  7406 D IOP_DB_BT: db_open: db_open : handle 3028062224l, read 13894 bytes onto local cache
08-30 15:45:00.800  7381  7406 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-30 15:45:00.800  7381  7406 D IOP_DB_BT: db_query: result 1
08-30 15:45:00.800  7381  7406 I         : iop_db_open: iop_db_open status 0
,08-30 15:45:00.800  7381  7406 D bte_conf: Device ID record 1 : primary
08-30 15:45:00.800  7381  7406 D bte_conf:   vendorId            = 0075
08-30 15:45:00.800  7381  7406 D bte_conf:   vendorIdSource      = 0001
08-30 15:45:00.800  7381  7406 D bte_conf:   product             = 0100
08-30 15:45:00.800  7381  7406 D bte_conf:   version             = 0200
08-30 15:45:00.800  7381  7406 D bte_conf:   clientExecutableURL = 
08-30 15:45:00.800  7381  7406 D bte_conf:   serviceDescription  = 
08-30 15:45:00.800  7381  7406 D bte_conf:   documentationURL    = 
08-30 15:45:00.800  7381  7406 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 15:45:00.800  7381  7406 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 15:45:00.800  7381  7444 E bt_mct  : hci lib postload completed
,08-30 15:45:00.800  7381  7403 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-30 15:45:00.800  7381  7403 D BluetoothAdapterProperties: ScanMode =  20
,08-30 15:45:00.800  7381  7403 D BluetoothAdapterProperties: State =  11
,08-30 15:45:00.800  1015  1464 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 15:45:00.810  7381  7403 D BluetoothAdapterProperties: Setting state to 12
,08-30 15:45:00.810  7381  7403 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 15:45:00.810  7381  7406 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 15:45:00.810  7381  7406 D BluetoothAdapterProperties: Scan Mode:21
,08-30 15:45:00.810  7381  7406 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 15:45:00.810  1015  1479 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-30 15:45:00.810  1015  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:45:00.810  1015  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:45:00.810  1015  1479 D SettingsProvider: selectionArgs: false
,08-30 15:45:00.810  1015  1479 D SettingsProvider: selectionArgs: 1002
,08-30 15:45:00.810  1015  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 15:45:00.810  1015  1479 D SettingsProvider: ret = -1
,08-30 15:45:00.820  7381  7403 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 15:45:00.820  7381  7403 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 15:45:00.820  1015  2020 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:45:00.820  1015  2020 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 15:45:00.820  1015  2020 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:00.820  1015  2020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.820  1015  2020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.820  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:00.820  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:00.820  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:45:00.820  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:00.820  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:00.820  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:00.820  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:00.820  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:45:00.830  1426  2846 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:45:00.830  1426  2846 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 15:45:00.830  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 15:45:00.830  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 15:45:00.830  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 15:45:00.830  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 15:45:00.830  1296  1306 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:45:00.830  1296  1306 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:45:00.830  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:45:00.830  7381  7403 D BluetoothAdapterService: Autoconnection is available 
08-30 15:45:00.830  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 15:45:00.830  7381  7403 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 15:45:00.830  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-30 15:45:00.830  7381  7403 D BluetoothAdapterService: starting service from this receiver
,08-30 15:45:00.830  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:00.830  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.830  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.840  1426  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:45:00.840  7381  7403 I BluetoothAdapterState: Entering On State from state = 11
,08-30 15:45:00.840  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 15:45:00.840  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 15:45:00.840  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:00.840  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:00.840  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:00.840  1426  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 15:45:00.840  1296  1314 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:45:00.850  7381  7381 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-30 15:45:00.960  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:00.960  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:00.960  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:45:00.960  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:00.960  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:00.960  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:00.960  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:00.960  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:45:00.970  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:45:00.970  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:45:00.970  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c3baf0f added. We now have 8 listener(s)
08-30 15:45:00.970  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:45:00.970  1015  1678 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 15:45:00.970  1015  1678 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 15:45:00.970  1015  1678 D SecContentProvider2: mCursor = null
,08-30 15:45:00.970  1015  1678 D WifiService: setWifiEnabled: false pid=6615, uid=10171
,08-30 15:45:00.970  1015  1678 D SettingsProvider: name = wifi_on
,08-30 15:45:00.980  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:00.980  1015  1464 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 15:45:00.980  1015  1464 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-30 15:45:00.990  1015  1464 D SecContentProvider2: mCursor = null
,08-30 15:45:00.990  1015  1464 D WifiService: setWifiEnabled: true pid=6615, uid=10171
,08-30 15:45:00.990  1015  1464 W ActivityManager: Permission Denial: getCurrentUser() from pid=6615, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-30 15:45:00.990  1015  1464 W WifiService: Failed getting userId using ActivityManagerNative
08-30 15:45:00.990  1015  1464 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6615, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-30 15:45:00.990  1015  1464 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 15:45:00.990  1015  1464 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 15:45:00.990  1015  1464 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 15:45:00.990  1015  1464 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 15:45:00.990  1015  1464 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 15:45:00.990  1015  1464 D SettingsProvider: name = wifi_on
,08-30 15:45:01.000  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 15:45:01.000  1015  1044 I art     : Explicit concurrent mark sweep GC freed 22517(1305KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 6.050ms total 151.365ms
08-30 15:45:01.000  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 15:45:01.000  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 15:45:01.000  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:01.000  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.000  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:01.000  1296  1314 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 15:45:01.000  1296  1296 D HeadsetProfile: Bluetooth service connected
,08-30 15:45:01.010  1455  2451 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 15:45:01.010  1455  2451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:45:01.010  1440  1461 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:45:01.010  1440  1461 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:45:01.010  7293  7307 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:45:01.010  7293  7307 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:45:01.010  1296  1314 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 15:45:01.010  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-30 15:45:01.010  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 15:45:01.010  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:01.010  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.010  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth,
,08-30 15:45:01.020  1426  2846 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:45:01.020  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 15:45:01.020  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 15:45:01.020  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:01.020  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.020  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:01.020  1426  2846 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 15:45:01.020  1426  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:45:01.020  7381  7381 I BluetoothPbapService: Handler(): got msg=1
,08-30 15:45:01.030  1015  1479 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 15:45:01.030  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 15:45:01.030  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 15:45:01.030  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:01.030  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.030  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:01.030  1426  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 15:45:01.030  1296  1296 D BluetoothMap: Proxy object connected
08-30 15:45:01.030  1296  1306 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 15:45:01.030  7381  7452 V BluetoothPbapService: PBAP Service initSocket try: 0
08-30 15:45:01.030  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-30 15:45:01.030  1296  1296 D MapProfile: Bluetooth service connected
08-30 15:45:01.030  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-30 15:45:01.030  1296  1296 D BluetoothMap: getConnectedDevices()
,08-30 15:45:01.030  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:01.030  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.030  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:01.040  7381  7451 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 15:45:01.040  6615  6624 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 15:45:01.040  6615  6624 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:45:01.040  1905  1913 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:45:01.040  1905  1913 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 15:45:01.040  1296  1296 D BluetoothInputDevice: Proxy object connected
,08-30 15:45:01.040  1455  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:45:01.040  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 15:45:01.040  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 15:45:01.040  1296  1296 D HidProfile: Bluetooth service connected
08-30 15:45:01.040  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:01.040  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.040  7381  7452 D BluetoothSocket: bindListen(): myUserId = 0
08-30 15:45:01.040  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-30 15:45:01.040  7381  7452 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:45:01.040  1455  1476 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 15:45:01.050  1015  1044 D BluetoothPan: Binding service...
08-30 15:45:01.050  7381  7452 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-30 15:45:01.050  7381  7452 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 15:45:01.050  7381  7452 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 15:45:01.050  7381  7452 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ea779c
08-30 15:45:01.050  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 15:45:01.050  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 15:45:01.050  7381  7452 D BluetoothSocket: channel: 19
08-30 15:45:01.050  7381  7452 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 15:45:01.050  1296  6698 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 15:45:01.050  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 15:45:01.050  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-30 15:45:01.050  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 15:45:01.050  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:01.050  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.050  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:01.050  7381  7390 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 15:45:01.050  7381  7390 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 15:45:01.050  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:45:01.050  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 15:45:01.050  1296  1296 D BluetoothPbap: Proxy object connected
08-30 15:45:01.050  1296  1296 D PbapServerProfile: Bluetooth service connected
08-30 15:45:01.050  1296  6698 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 15:45:01.060  1296  6698 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 15:45:01.060  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 15:45:01.060  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 15:45:01.060  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:01.060  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.060  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:01.060  1296  1296 D BluetoothA2dp: Proxy object connected
,08-30 15:45:01.060  1175  1890 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 15:45:01.060  1175  1890 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 15:45:01.060  1296  1296 D A2dpProfile: Bluetooth service connected
08-30 15:45:01.060  1296  1306 D BluetoothPan: Binding service...
,08-30 15:45:01.060  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 15:45:01.060  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 15:45:01.060  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:01.060  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.060  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:01.060  1296  6698 D Bluetoothsap: onBluetoothStateChange: up=true
,08-30 15:45:01.060  1296  6698 D Bluetoothsap: Binding service...
08-30 15:45:01.070  1296  1296 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 15:45:01.070  1296  1296 D PanProfile: Bluetooth service connected
,08-30 15:45:01.070  1296  6698 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-30 15:45:01.070  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-30 15:45:01.070  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 15:45:01.070  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:01.070  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.070  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 15:45:01.070  1296  6698 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 15:45:01.070  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:45:01.070  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-30 15:45:01.070  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 15:45:01.070  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 15:45:01.070  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 15:45:01.070  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-30 15:45:01.070  1015  1015 D BluetoothA2dp: Proxy object connected
,08-30 15:45:01.080  1426  1426 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@f631b3b, true
,08-30 15:45:01.080  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object connected
08-30 15:45:01.080  1296  1296 D SapProfile: Bluetooth service connected
08-30 15:45:01.080  1296  1296 D Bluetoothsap: getConnectedDevices()
,08-30 15:45:01.080  1426  1426 D BluetoothHeadset: registerMessageListener
,08-30 15:45:01.080  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-30 15:45:01.080  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 15:45:01.080  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 15:45:01.090  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:45:01.090  1175  1175 D BluetoothTile:  getBluetoothState : 12
,08-30 15:45:01.090  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 15:45:01.090  1794  1794 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 15:45:01.090  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:45:01.100  1015  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 15:45:01.100  1015  1504 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-30 15:45:01.100  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 15:45:01.100  1015  1409 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:45:01.100  1015  1409 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 15:45:01.100  1015  1409 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:01.100  1015  1409 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:45:01.100  1015  1409 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:45:01.100  7381  7390 D HeadsetService: registerMessageListener
,08-30 15:45:01.100  7381  7390 D HeadsetService: registerMessageListener
,08-30 15:45:01.100  7381  7411 D HeadsetStateMachine: Disconnected process message: 70
08-30 15:45:01.100  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:45:01.100  1426  1426 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 15:45:01.100  1426  1426 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 15:45:01.100  7381  7411 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3eea5a5
08-30 15:45:01.100  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-30 15:45:01.100  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 15:45:01.100  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:01.110  1296  1296 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-30 15:45:01.110  1296  1296 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-30 15:45:01.110  1296  1296 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 15:45:01.110  1296  1296 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-30 15:45:01.110  1426  1426 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-30 15:45:01.110  1175  1717 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 15:45:01.110  1426  1426 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-30 15:45:01.110  1426  1426 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-30 15:45:01.110  7381  7454 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-30 15:45:01.110  7381  7411 D HeadsetStateMachine: Disconnected process message: 9
,08-30 15:45:01.110  7381  7411 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-30 15:45:01.120   283  6841 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-30 15:45:01.120   283  6841 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 15:45:01.120   283  6841 V voice   : voice_set_parameters: exit with code(-2)
08-30 15:45:01.120   283  6841 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-30 15:45:01.120   283  6841 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 15:45:01.120   283  6841 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 15:45:01.120   283  6841 V audio_hw_primary: adev_set_parameters: exit
,08-30 15:45:01.120  7381  7411 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-30 15:45:01.120  7381  7454 D BluetoothSocket: bindListen(): myUserId = 0
08-30 15:45:01.120  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:45:01.120  7381  7454 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:45:01.120  1015  1464 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 15:45:01.120  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 15:45:01.120  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:01.120  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.120  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 15:45:01.130  7381  7454 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-30 15:45:01.130  7381  7454 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 15:45:01.130  7381  7454 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 15:45:01.130  7381  7454 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25b2fd7a
08-30 15:45:01.130  7381  7454 D BluetoothSocket: channel: 5
,08-30 15:45:01.140  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:45:01.140  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 15:45:01.140  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:01.140  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 15:45:01.150  7381  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ea7b312
08-30 15:45:01.150  7381  7381 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 15:45:01.150  1015  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 15:45:01.150  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 15:45:01.150  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:01.150  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.150  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 15:45:01.170  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 15:45:01.170  1015  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:45:01.170  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 15:45:01.170  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:01.170  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 15:45:01.170  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:45:01.180  1905  7460 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 15:45:01.180  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 15:45:01.180  1015  1133 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 15:45:01.180  1015  1462 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:45:01.190  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:01.190  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:45:01.190  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:45:01.200  7381  7464 D BluetoothSocket: bindListen(): myUserId = 0
08-30 15:45:01.200  7381  7464 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:45:01.200  1015  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 15:45:01.210  7381  7464 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-30 15:45:01.210  7381  7464 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 15:45:01.210  7381  7464 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-30 15:45:01.210  7381  7464 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3fe37746
08-30 15:45:01.210  7381  7464 D BluetoothSocket: channel: 12
08-30 15:45:01.210  7381  7464 I BtOppRfcommListener: Accept thread started.
,08-30 15:45:01.210  1015  1480 W ActivityManager: userId = 0, bbcId = -10000,
08-30 15:45:01.210  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:45:01.210  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:45:01.220  1905  7460 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-30 15:45:01.230   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 15:45:01.260   288   288 E SMD     : DCD OFF
,08-30 15:45:01.350  1015  1042 D Tethering: interfaceAdded wlan0
,08-30 15:45:01.360  1015  1128 E Tethering: No numeric data
,08-30 15:45:01.360  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-30 15:45:01.360  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:01.370  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 15:45:01.370  1015  1128 D Tethering: clearTetheredNotification()
,08-30 15:45:01.370  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:45:01.370  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 15:45:01.370  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 15:45:01.370  1175  1175 D HotspotTile: updateTetherState():false, false
,08-30 15:45:01.370  1015  1122 V NetworkStats: performPollLocked() took 9ms
,08-30 15:45:01.370  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:01.380  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 15:45:01.380  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 15:45:01.380  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 15:45:01.380  1015  1128 D Tethering: InitialState.processMessage what=4
08-30 15:45:01.390  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:01.390  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:01.390  1015  1042 D Tethering: interfaceAdded p2p0
08-30 15:45:01.390  1015  1128 E Tethering: No numeric data
,08-30 15:45:01.390  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 15:45:01.390  1015  1128 D Tethering: clearTetheredNotification()
,08-30 15:45:01.400  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring,
08-30 15:45:01.400  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-30 15:45:01.400   278   894 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-30 15:45:01.400  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:01.400  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 15:45:01.400   278   894 D SoftapController: Softap fwReload - Ok
08-30 15:45:01.400  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 15:45:01.400  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-30 15:45:01.400  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:45:01.400  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 15:45:01.400  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 15:45:01.400  1175  1175 D HotspotTile: updateTetherState():false, false
08-30 15:45:01.400   278   894 D CommandListener: Setting iface cfg
08-30 15:45:01.400   278   894 D CommandListener: Trying to bring down wlan0
,08-30 15:45:01.400   278   894 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:45:01.410  1015  1122 V NetworkStats: performPollLocked() took 8ms
08-30 15:45:01.410  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:01.410  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:01.410  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:01.410  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-30 15:45:01.410  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 15:45:01.420  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:45:01.420  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 15:45:01.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:01.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:01.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:01.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:01.420  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 15:45:01.420  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 15:45:01.420  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-30 15:45:01.420  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 15:45:01.430  1175  1175 D HotspotTile: onReceive : 2, 0
,08-30 15:45:01.430  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:45:01.430  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:01.430  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 15:45:01.430  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 15:45:01.430  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:01.430  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:01.430  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 15:45:01.440  1640  1640 I Hs20UtilService: Starting #19
08-30 15:45:01.440  1640  1699 I Hs20UtilService: Message received 5011
,08-30 15:45:01.440  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 15:45:01.440  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 15:45:01.440  6484  6484 D SecurityLogAgent: StateMachine : Current State = 1
08-30 15:45:01.440  6484  6484 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 15:45:01.460  7472  7472 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-30 15:45:01.460  7472  7472 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 15:45:01.460  7472  7472 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 15:45:01.480  7472  7472 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-30 15:45:01.480   377   377 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7472
08-30 15:45:01.480   377   377 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-30 15:45:01.480  7472  7472 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 15:45:01.480  7472  7472 I wpa_supplicant: ssSupport state is = 1
08-30 15:45:01.480  7472  7472 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 15:45:01.480  7472  7472 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-30 15:45:01.480   377   377 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7472
08-30 15:45:01.480   377   377 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-30 15:45:01.620   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-30 15:45:01.620  7472  7472 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-30 15:45:01.670  7472  7472 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-30 15:45:01.670  7472  7472 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 15:45:01.680  7472  7472 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-30 15:45:01.680   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7472
08-30 15:45:01.680   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 15:45:01.680  7472  7472 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 15:45:01.680  7472  7472 I wpa_supplicant: ssSupport state is = 1
08-30 15:45:01.680  7472  7472 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 15:45:01.680  7472  7472 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-30 15:45:01.680  7472  7472 E wpa_supplicant: SIM READ ERROR
08-30 15:45:01.680  7472  7472 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 15:45:01.680  7472  7472 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 15:45:01.680  7472  7472 E wpa_supplicant: SIM READ ERROR
08-30 15:45:01.680  7472  7472 I wpa_supplicant: Blacklist: Clear (all) 
08-30 15:45:01.680  7472  7472 I wpa_supplicant: wpa_default_ap_write_once,
08-30 15:45:01.680  7472  7472 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 15:45:01.680  7472  7472 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 15:45:01.680  7472  7472 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 15:45:01.680  7472  7472 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 15:45:01.680  7472  7472 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 15:45:01.680  7472  7472 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-30 15:45:01.690  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 15:45:01.690  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:45:01.690  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
,08-30 15:45:01.740  7472  7472 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-30 15:45:02.110  7472  7472 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-30 15:45:02.110  7472  7472 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-30 15:45:02.120  7472  7472 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 15:45:02.120   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7472
08-30 15:45:02.120   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-30 15:45:02.120  7472  7472 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 15:45:02.120  7472  7472 I wpa_supplicant: ssSupport state is = 1
,08-30 15:45:02.120  7472  7472 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-30 15:45:02.130  7472  7472 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 15:45:02.140  7472  7472 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 15:45:02.140   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7472
08-30 15:45:02.140   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 15:45:02.140  7472  7472 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-30 15:45:02.140  7472  7472 I wpa_supplicant: ssSupport state is = 1
08-30 15:45:02.140  7472  7472 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 15:45:02.140  7472  7472 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-30 15:45:02.140  7472  7472 E wpa_supplicant: SIM READ ERROR
08-30 15:45:02.140  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 15:45:02.140  7472  7472 I wpa_supplicant: wpa_default_ap_write_once
08-30 15:45:02.140  7472  7472 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 15:45:02.140  7472  7472 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 15:45:02.140  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 15:45:02.140  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 15:45:02.150  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 15:45:02.150  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 15:45:02.150  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 15:45:02.210  7472  7472 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-30 15:45:02.210  7472  7472 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 15:45:02.230   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 15:45:02.270  7472  7472 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-30 15:45:02.270  7472  7472 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-30 15:45:02.270  7472  7472 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 15:45:02.280  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-30 15:45:02.280  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 15:45:02.280  7472  7472 I wpa_supplicant: HOTSPOT20_ENABLE called
08-30 15:45:02.280  7472  7472 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 15:45:02.280  7472  7472 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 15:45:02.280  7472  7472 E wpa_supplicant: SIM READ ERROR
08-30 15:45:02.280  7472  7472 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 15:45:02.300  7472  7472 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-30 15:45:02.310  7472  7472 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-30 15:45:02.320  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 15:45:02.320  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:45:02.320  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:02.320  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:02.320  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:02.320  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:02.320  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
,08-30 15:45:02.320  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:45:02.320  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-30 15:45:02.330  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:45:02.330  1175  1717 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 15:45:02.330  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:45:02.330  1175  1175 D HotspotTile: onReceive : 3, 0
,08-30 15:45:02.330  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:02.330  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:02.330  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:45:02.330  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:02.330  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:02.330  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:02.330  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:02.330  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:45:02.330  1015  1125 E WifiConfigStore: Not a HS20
,08-30 15:45:02.330  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 15:45:02.330  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 15:45:02.340  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:02.340  1015  1504 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 15:45:02.340  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 15:45:02.340  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:02.340  1015  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:02.340  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 15:45:02.340  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 15:45:02.340  7472  7472 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 15:45:02.340  7472  7472 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 15:45:02.340  7472  7472 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 15:45:02.340  7472  7472 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 15:45:02.340  7472  7472 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 15:45:02.340  7472  7472 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 15:45:02.340  7472  7472 I wpa_supplicant: First Scan Start
,08-30 15:45:02.340  7472  7472 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-30 15:45:02.340  1640  1640 I Hs20UtilService: Starting #20
,08-30 15:45:02.340  1640  1699 I Hs20UtilService: Message received 5011
,08-30 15:45:02.340  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 15:45:02.350  6484  6484 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 15:45:02.350  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-30 15:45:02.350  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 15:45:02.350  6484  6484 D SecurityLogAgent: StateMachine : Current State = 1
08-30 15:45:02.350  1015  1125 I WifiNative-HAL: startHal
08-30 15:45:02.350  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d55788c
08-30 15:45:02.350  1015  1125 I WifiNative-HAL: Could not start hal
08-30 15:45:02.350  6484  6484 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 15:45:02.350  6808  6808 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:45:02.350  1015  1125 E WifiNative-wlan0: do suspend true
,08-30 15:45:02.350  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-30 15:45:02.350  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-30 15:45:02.360   278   894 D CommandListener: Setting iface cfg
08-30 15:45:02.360   278   894 D CommandListener: Trying to bring up p2p0
,08-30 15:45:02.360  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-30 15:45:02.360  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 15:45:02.360  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 15:45:02.360  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-30 15:45:02.360  1015  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:02.360  1015  1148 I WifiNative-HAL: startHal
08-30 15:45:02.360  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e0f19bc
08-30 15:45:02.360  1015  1148 I WifiNative-HAL: Could not start hal
08-30 15:45:02.360  1015  1148 E WifiScanningService: could not start HAL
08-30 15:45:02.360  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 15:45:02.360  1015  1124 D WifiP2pService: P2pEnablingState
,08-30 15:45:02.360  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 15:45:02.360  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-30 15:45:02.360  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 15:45:02.360  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-30 15:45:02.360  1015  1124 D WifiP2pService: P2p socket connection successful
08-30 15:45:02.360  1015  1124 D WifiP2pService: P2pEnabledState
,08-30 15:45:02.360  7472  7472 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-30 15:45:02.360  7472  7472 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 15:45:02.360  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-30 15:45:02.360  7472  7472 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-30 15:45:02.360  1015  1125 E WifiStateMachine: Failed to set frequency band 0
08-30 15:45:02.360  1015  1149 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:02.370  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 15:45:02.370  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:45:02.370  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 15:45:02.370  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:45:02.370  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-30 15:45:02.370  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 15:45:02.370  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 15:45:02.370  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
,08-30 15:45:02.370  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 15:45:02.370  1015  1045 D WifiDisplayController: disconnect
08-30 15:45:02.370  1015  1045 D WifiDisplayController: updateConnection
,08-30 15:45:02.370  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 15:45:02.370  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 15:45:02.380  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 15:45:02.380  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 15:45:02.380  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 15:45:02.380  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-30 15:45:02.380  1015  1133 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 15:45:02.380  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 15:45:02.380  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
08-30 15:45:02.380  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-30 15:45:02.380  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 15:45:02.380  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-30 15:45:02.380  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 15:45:02.380  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 15:45:02.380  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 15:45:02.380  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 15:45:02.380  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 15:45:02.390  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,08-30 15:45:02.390  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  secondary type: null
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  wps: 0
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  grpcapab: 0
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  devcapab: 0
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  status: 3
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  wfdInfo: null
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-30 15:45:02.390  1015  1045 D WifiDisplayController:  SConnectInfo : null
08-30 15:45:02.390  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 15:45:02.390  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-30 15:45:02.390  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 15:45:02.390  1296  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 15:45:02.390  7176  7176 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 15:45:02.390  7176  7176 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 15:45:02.390  7176  7176 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 15:45:02.400  7191  7191 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 15:45:02.410  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-30 15:45:02.410  1015  1124 D WifiP2pService: InactiveState
,08-30 15:45:02.410  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-30 15:45:02.410  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 15:45:02.410  7472  7472 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 15:45:02.410  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-30 15:45:02.410  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 15:45:03.010  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:03.010  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:03.010  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:45:03.010  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:03.010  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:03.010  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:03.010  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:03.010  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:45:03.020  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:45:03.020  6615  6668 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 15:45:03.020  6615  6668 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 15:45:03.030  6615  6668 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@28bf04c2 Bundle[{}]
,08-30 15:45:03.030  6615  6668 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 15:45:03.030  6615  6668 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 15:45:03.030  6615  6668 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 15:45:03.030  6615  6668 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 15:45:03.030  6615  6668 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 15:45:03.030  6615  6668 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 15:45:03.040  6615  6668 I System.out: Running OutgoingSocketThread
,08-30 15:45:03.040  6615  7483 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1304)
,08-30 15:45:03.040  6615  7483 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55877
,08-30 15:45:03.040  6615  7483 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 15:45:03.240   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 15:45:03.580  7472  7472 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
08-30 15:45:03.580  7472  7472 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-30 15:45:03.580  7472  7472 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-30 15:45:03.580  7472  7472 I wpa_supplicant: Trying to associate with  'G700'
08-30 15:45:03.580  7472  7472 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-30 15:45:03.580  7472  7472 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-30 15:45:03.590  1015  7478 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-30 15:45:03.600  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 15:45:03.600  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:45:03.700  7472  7472 E wpa_supplicant: Cmd 35605 not handled
,08-30 15:45:03.700  7472  7472 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-30 15:45:03.700  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:45:03.700  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 15:45:03.700  7472  7472 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-30 15:45:03.700  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:45:03.700  7472  7472 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-30 15:45:03.700  7472  7472 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-30 15:45:03.700  7472  7472 I wpa_supplicant: Associated with F4.99.3E,
08-30 15:45:03.700  7472  7472 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 15:45:03.710  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:45:03.700  7472  7472 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 15:45:03.700  7472  7472 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-30 15:45:03.710  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:45:03.710  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 15:45:03.710  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 15:45:03.710  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 15:45:03.710  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 15:45:03.710  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 15:45:03.710  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-30 15:45:03.710  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-30 15:45:03.710  1015  1128 E Tethering: No numeric data
08-30 15:45:03.710  7472  7472 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 15:45:03.710  7472  7472 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-30 15:45:03.710  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 15:45:03.710  1015  1128 D Tethering: clearTetheredNotification()
08-30 15:45:03.710  7472  7472 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-30 15:45:03.710  7472  7472 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-30 15:45:03.710  7472  7472 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:45:03.710  7472  7472 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-30 15:45:03.710  7472  7472 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-30 15:45:03.710  7472  7472 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 15:45:03.710  7472  7472 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-30 15:45:03.720  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,08-30 15:45:03.720  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-30 15:45:03.720  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
08-30 15:45:03.720  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 15:45:03.720  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:03.720  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 15:45:03.720  1175  1175 D HotspotTile: updateTetherState():false, false
,08-30 15:45:03.720  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:45:03.720  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 15:45:03.730  1015  1122 V NetworkStats: performPollLocked() took 7ms
08-30 15:45:03.730  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:03.730  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:03.730  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:03.730  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 15:45:03.740  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1,
08-30 15:45:03.740  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:45:03.740  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:45:03.740  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:03.740  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:03.740  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:03.740  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:45:03.740  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-30 15:45:03.740  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:45:03.740  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 15:45:03.740  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 15:45:03.740  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 15:45:03.750  1015  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 15:45:03.750  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 15:45:03.750  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:03.750  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:03.750  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 15:45:03.750  1640  1640 I Hs20UtilService: Starting #21
,08-30 15:45:03.750  1640  1699 I Hs20UtilService: Message received 5007
,08-30 15:45:03.760  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:45:03.760  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 15:45:03.760  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 15:45:03.760  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,08-30 15:45:03.760  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 15:45:03.760  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-30 15:45:03.760  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 15:45:03.760  1296  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,08-30 15:45:03.770   278   894 D CommandListener: Setting iface cfg
,08-30 15:45:03.770  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 15:45:03.770  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-30 15:45:03.770  1015  1125 D SecContentProvider2: mCursor = null,
08-30 15:45:03.780  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 15:45:03.780  1015  1125 D SecContentProvider2: mCursor = null
08-30 15:45:03.780  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 15:45:03.780  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:45:03.790  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 15:45:03.790  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 15:45:03.790  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:03.790  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:45:03.790  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 15:45:03.790  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:45:03.790  1015  1125 E WifiNative-wlan0: do suspend false,
,08-30 15:45:03.800  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-30 15:45:03.800  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
08-30 15:45:03.800  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 15:45:03.800  1015  1125 D SecContentProvider2: mCursor = null
,08-30 15:45:03.870  1015  1990 V SAMP_SPCM_test: CSC File load.. 
,08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
,08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling,
,08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,08-30 15:45:03.880  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-30 15:45:03.890  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-30 15:45:03.890  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction,
08-30 15:45:03.890  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-30 15:45:03.890  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
,08-30 15:45:03.890  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-30 15:45:03.930  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,08-30 15:45:03.940  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-30 15:45:03.940  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
,08-30 15:45:03.940  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-30 15:45:03.940  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-30 15:45:03.940  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
,08-30 15:45:03.940  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-30 15:45:03.940  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-30 15:45:03.950  1015  1990 ,W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-30 15:45:03.950  1015  1990 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-30 15:45:03.950  1015  1990 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-30 15:45:03.960  1015  1990 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:03.960  1015  1990 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:03.960  1015  1990 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:03.960  1015  1990 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:03.970  1015  1990 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7487 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 15:45:03.970  7487  7487 E Zygote  : MountEmulatedStorage()
08-30 15:45:03.970  7487  7487 E Zygote  : v2
08-30 15:45:03.970  7487  7487 I libpersona: KNOX_SDCARD checking this for 1000
08-30 15:45:03.970  7487  7487 I libpersona: KNOX_SDCARD not a persona
08-30 15:45:03.980  7487  7487 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:45:03.980  7487  7487 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 15:45:03.980  7487  7487 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:45:04.010  7502  7502 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 15:45:04.010  7502  7502 I dhcpcd  : version 5.5.6 starting,
,08-30 15:45:04.020  7487  7487 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:45:04.020  7487  7487 D ActivityThread: Added TimaKeyStore provider,
,08-30 15:45:04.020  7502  7502 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 15:45:04.040  6615  6668 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1305)
08-30 15:45:04.050  7487  7487 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 15:45:04.040  6615  6668 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1305)
08-30 15:45:04.050  6615  6668 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1310)
,08-30 15:45:04.050  6615  6668 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 15:45:04.050  6615  6668 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1311)
,08-30 15:45:04.050  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:45:04.050  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95a4b9c added. We now have 2 listener(s)
,08-30 15:45:04.060  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-30 15:45:04.060  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:04.060  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:04.060  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-30 15:45:04.060  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1523e9a5 added. We now have 9 listener(s)
08-30 15:45:04.060  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:04.060  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:45:04.060  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:45:04.080  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:45:04.080  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:04.080  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:45:04.080  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:04.080  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:04.080  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:04.080  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:04.080  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:45:04.080  7502  7502 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-30 15:45:04.080  7502  7502 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-30 15:45:04.080  7502  7502 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-30 15:45:04.080  7502  7502 I dhcpcd  : bssid match
,08-30 15:45:04.080  7502  7502 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-30 15:45:04.080  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:45:04.080  6615  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:45:04.090  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:04.090  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e8e2d2b added. We now have 3 listener(s)
,08-30 15:45:04.090  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:04.090  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:04.090  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-30 15:45:04.090  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:04.090  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:04.090  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:04.090  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8e8588 added. We now have 10 listener(s)
08-30 15:45:04.090  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:04.090  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:45:04.090  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:04.090  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:45:04.090  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:04.090  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.090  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:04.090  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:04.090  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95a4b9c removed from the list
08-30 15:45:04.090  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.090  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1523e9a5 removed from the list
08-30 15:45:04.090  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:45:04.090  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.090  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.090  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:45:04.090  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:04.090  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:04.090  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.090  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1523e9a5 not in the list
08-30 15:45:04.090  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.090  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.090  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:04.090  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:04.090  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.090  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8e8588 removed from the list
08-30 15:45:04.090  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:04.090  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.090  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.090  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:04.090  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e8e2d2b removed from the list
08-30 15:45:04.090  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:04.090  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e8e7b21 added. We now have 2 listener(s)
,08-30 15:45:04.100  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 15:45:04.100  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:04.100  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:04.100  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:04.100  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18b4ab46 added. We now have 9 listener(s)
08-30 15:45:04.100  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:45:04.100  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:45:04.100  1015  1990 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-30 15:45:04.110  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:45:04.110  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:45:04.110  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:04.110  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:45:04.110  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:04.110  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:04.110  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:04.110  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:04.110  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:45:04.110  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:04.110  6615  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:45:04.110  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:04.110  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@134a7234 added. We now have 3 listener(s)
,08-30 15:45:04.110  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:04.110  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:04.110  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-30 15:45:04.110  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:04.110  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:04.120  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:04.120  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db6a85d added. We now have 10 listener(s)
08-30 15:45:04.120  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:04.120  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:45:04.120  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:45:04.120  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:45:04.120  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:04.120  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 15:45:04.120  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:45:04.120  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:45:04.130  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:45:04.130  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 15:45:04.130  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:45:04.130  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 15:45:04.130  7381  7389 D BtGatt.GattService: registerClient() - UUID=4443790a-fc2f-4ecc-a8af-ed29ef5d23df
,08-30 15:45:04.140  7502  7502 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-30 15:45:04.180  7381  7406 D BtGatt.GattService: onClientRegistered() - UUID=4443790a-fc2f-4ecc-a8af-ed29ef5d23df, clientIf=6
,08-30 15:45:04.180  6615  6624 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 15:45:04.180  7381  7451 D BtGatt.GattService: start scan with filters
,08-30 15:45:04.180  7381  7410 D BtGatt.ScanManager: handling starting scan
,08-30 15:45:04.180  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:45:04.180  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:45:04.180  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 15:45:04.180  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:45:04.180  7381  7410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ea7b312
,08-30 15:45:04.190  7502  7502 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
08-30 15:45:04.190  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:45:04.190  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 15:45:04.190  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:45:04.190  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:45:04.190  6615  6668 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-30 15:45:04.190  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:04.190  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:45:04.190  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.190  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:45:04.190  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:45:04.190  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 15:45:04.190  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:45:04.190  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:45:04.190  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:45:04.200  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 15:45:04.200  7381  7453 D BtGatt.GattService: stopScan() - queue size =1
08-30 15:45:04.200  7381  7406 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 15:45:04.200  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.200  7381  7412 D BtGatt.GattService: unregisterClient() - clientIf=6
08-30 15:45:04.200  7381  7410 D BtGatt.ScanManager: allow scan with filters,
08-30 15:45:04.200  7381  7410 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 15:45:04.200  7381  7410 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-30 15:45:04.200  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:45:04.200  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 15:45:04.200  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:45:04.200  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:45:04.200  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 15:45:04.200  7381  7406 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 15:45:04.200  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.200  7381  7410 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:45:04.200  7381  7410 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 15:45:04.200  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:45:04.200  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:45:04.200  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:45:04.200  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:45:04.210  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:04.210  7381  7406 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 15:45:04.210  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.210  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:45:04.210  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:45:04.210  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:45:04.210  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:45:04.210  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:04.210  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:45:04.210  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:04.210  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.210  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:04.210  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:04.210  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e8e7b21 removed from the list
08-30 15:45:04.210  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.210  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18b4ab46 removed from the list
08-30 15:45:04.210  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:45:04.210  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.220  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.220  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.220  7381  7406 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 15:45:04.220  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:04.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:04.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.220  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18b4ab46 not in the list
08-30 15:45:04.220  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.220  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.220  7381  7410 D BtGatt.ScanManager: filter size is 1
08-30 15:45:04.220  7381  7410 D BtGatt.ScanManager: delete FilterIndex - 3
08-30 15:45:04.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:04.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:04.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.220  7381  7406 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 15:45:04.220  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db6a85d removed from the list
08-30 15:45:04.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:04.220  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.220  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.220  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.220  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:04.220  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@134a7234 removed from the list
08-30 15:45:04.220  7381  7410 D BtGatt.ScanManager: stopping BLe Batch
08-30 15:45:04.220  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:04.230  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@253a6d59 added. We now have 2 listener(s)
08-30 15:45:04.230  7381  7406 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 15:45:04.230  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.230  7381  7410 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-30 15:45:04.230  7381  7406 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 15:45:04.230  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.230  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 15:45:04.230  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:04.230  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:04.230  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:04.230  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1307dd1e added. We now have 9 listener(s)
08-30 15:45:04.230  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:04.230  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:45:04.240  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:04.240   315   315 I ServiceManager: Waiting for service AtCmdFwd...
08-30 15:45:04.250  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:45:04.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:04.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:45:04.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:04.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:04.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:04.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:04.250  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:45:04.250  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:04.250  6615  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:45:04.250  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:04.250  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@615d3cc added. We now have 3 listener(s)
08-30 15:45:04.250  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:04.250  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:04.250  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 15:45:04.250  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:04.250  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:04.260  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:04.260  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@199b8615 added. We now have 10 listener(s)
08-30 15:45:04.260  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:04.260  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:45:04.260  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:45:04.260  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:45:04.260  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:45:04.260  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:04.260  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:45:04.260  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:45:04.260   288   288 E SMD     : DCD OFF
,08-30 15:45:04.290  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:45:04.290  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-30 15:45:04.290  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 15:45:04.290  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:45:04.290  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 15:45:04.300  7381  7412 D BtGatt.GattService: registerClient() - UUID=3f842b95-8a36-4bb7-a7a8-a3df6f23eb8b
,08-30 15:45:04.340  7381  7406 D BtGatt.GattService: onClientRegistered() - UUID=3f842b95-8a36-4bb7-a7a8-a3df6f23eb8b, clientIf=6
08-30 15:45:04.340  6615  6623 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-30 15:45:04.340  7381  7451 D BtGatt.GattService: start scan with filters
08-30 15:45:04.340  7381  7410 D BtGatt.ScanManager: handling starting scan
08-30 15:45:04.340  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-30 15:45:04.340  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:45:04.340  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:45:04.340  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
08-30 15:45:04.340  7381  7406 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 15:45:04.340  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.340  7381  7410 D BtGatt.ScanManager: allow scan with filters
08-30 15:45:04.340  7381  7410 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 15:45:04.340  7381  7410 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-30 15:45:04.340  7381  7406 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 15:45:04.340  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.340  7381  7410 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:45:04.340  7381  7410 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-30 15:45:04.340  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:45:04.340  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 15:45:04.350  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:45:04.350  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:45:04.350  7381  7406 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 15:45:04.350  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:45:04.350  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 15:45:04.350  6615  6668 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 15:45:04.350  7381  7406 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 15:45:04.350  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.350  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-30 15:45:04.350  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:04.350  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:45:04.350  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:45:04.350  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.350  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:45:04.350  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:04.350  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@253a6d59 removed from the list
08-30 15:45:04.350  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 15:45:04.350  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1307dd1e removed from the list
08-30 15:45:04.350  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:45:04.350  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:04.350  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.350  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-30 15:45:04.350  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.350  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:04.350  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:04.350  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:04.350  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.350  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1307dd1e not in the list
,08-30 15:45:04.350  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:45:04.350  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:45:04.350  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:45:04.350  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:45:04.350  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 15:45:04.360  7381  7453 D BtGatt.GattService: stopScan() - queue size =1
,08-30 15:45:04.360  7381  7412 D BtGatt.GattService: unregisterClient() - clientIf=6
08-30 15:45:04.360  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:45:04.360  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 15:45:04.360  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:45:04.360  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:45:04.360  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 15:45:04.360  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-30 15:45:04.360  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:45:04.360  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 15:45:04.360  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:45:04.360  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.360  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:45:04.360  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:45:04.360  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:45:04.360  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:45:04.360  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:04.360  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.360  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@199b8615 removed from the list
08-30 15:45:04.360  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:04.360  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:45:04.360  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.360  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:04.360  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@615d3cc removed from the list
08-30 15:45:04.360  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:04.360  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bbb6e91 added. We now have 2 listener(s)
,08-30 15:45:04.370  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 15:45:04.370  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:04.370  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:04.370  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:04.370  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fa471f6 added. We now have 9 listener(s)
08-30 15:45:04.370  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:45:04.370  7381  7410 D BtGatt.ScanManager: filter size is 1
08-30 15:45:04.370  7381  7410 D BtGatt.ScanManager: delete FilterIndex - 4
08-30 15:45:04.370  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:45:04.370  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:04.370  7381  7406 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 15:45:04.370  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.370  7381  7410 D BtGatt.ScanManager: stopping BLe Batch
,08-30 15:45:04.370  7381  7406 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 15:45:04.370  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.370  7381  7410 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 15:45:04.380  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:45:04.380  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:04.380  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:45:04.380  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:04.380  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:04.380  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:04.380  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:04.380  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:45:04.380  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:04.380  6615  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:45:04.380  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:45:04.380  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2488d064 added. We now have 3 listener(s)
08-30 15:45:04.380  7381  7406 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 15:45:04.380  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:45:04.380  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:04.380  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-30 15:45:04.380  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:04.380  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 15:45:04.390  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:04.390  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1762cd added. We now have 10 listener(s)
08-30 15:45:04.390  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:04.390  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 15:45:04.390  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:45:04.390  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:45:04.390  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:04.390  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 15:45:04.390  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:04.390  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:45:04.400  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:45:04.400  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:45:04.400  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 15:45:04.400  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 15:45:04.400  6615  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 15:45:04.410  1015  1125 E WifiNative-wlan0: do suspend true
,08-30 15:45:04.410  7381  7451 D BtGatt.GattService: registerClient() - UUID=ab86d816-1173-4c3a-8fa3-db1de12a04e6
,08-30 15:45:04.440  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-30 15:45:04.440  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 15:45:04.440  1015  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 15:45:04.440  1015  1125 E WifiStateMachine: VerifyingLinkState enter
,08-30 15:45:04.440  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 15:45:04.440  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:45:04.440  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.440  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.440  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.440  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:45:04.440  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 15:45:04.450  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-30 15:45:04.450  1015  1127 D ConnectivityService: Adding iface wlan0 to network 504
,08-30 15:45:04.450  7381  7406 D BtGatt.GattService: onClientRegistered() - UUID=ab86d816-1173-4c3a-8fa3-db1de12a04e6, clientIf=6
,08-30 15:45:04.450  6615  6623 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 15:45:04.450  7381  7390 D BtGatt.GattService: start scan with filters
,08-30 15:45:04.460  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 15:45:04.460  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:45:04.460  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 15:45:04.460  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:45:04.460  7381  7410 D BtGatt.ScanManager: handling starting scan
,08-30 15:45:04.460  1015  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-30 15:45:04.470  1015  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 15:45:04.470  1015  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 15:45:04.470  1015  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 15:45:04.470  1015  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 15:45:04.470  7381  7406 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 15:45:04.470  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.470  7381  7410 D BtGatt.ScanManager: allow scan with filters
,08-30 15:45:04.470  7381  7410 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 15:45:04.470  7381  7410 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-30 15:45:04.480  7381  7406 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-30 15:45:04.480  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.480  7381  7410 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:45:04.480  7381  7410 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-30 15:45:04.480  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:45:04.480  1015  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-30 15:45:04.480  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 15:45:04.480  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.480  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.480  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.480  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:45:04.480  1015  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-30 15:45:04.480  1015  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-30 15:45:04.480  7381  7406 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 15:45:04.480  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:45:04.490  1015  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 15:45:04.490  1015  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,08-30 15:45:04.490  1015  1127 D ConnectivityService: LTETest block dns file not exists
,08-30 15:45:04.490  1015  1462 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 15:45:04.490  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 15:45:04.490  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:45:04.490  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 15:45:04.490  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:45:04.490  7381  7406 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 15:45:04.490  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.490  1015  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-30 15:45:04.500  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:04.500  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:04.500  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 15:45:04.500  1015  1127 V NetworkStats: updateIfacesLocked()
08-30 15:45:04.500  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.500  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-30 15:45:04.500  1640  1640 I Hs20UtilService: Starting #22
,08-30 15:45:04.500  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:45:04.500  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 15:45:04.500  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 15:45:04.500  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 15:45:04.500  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:45:04.500  1640  1699 I Hs20UtilService: Message received 5007
,08-30 15:45:04.500  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.500  1015  1127 V NetworkStats: performPollLocked() took 5ms
08-30 15:45:04.500  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 15:45:04.510  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 15:45:04.510  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 15:45:04.510  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.510  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.510  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.510  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:45:04.510  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 15:45:04.510  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
,08-30 15:45:04.510  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-30 15:45:04.520  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:45:04.520  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 15:45:04.520  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:45:04.520  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.520  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.520  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:45:04.530  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-30 15:45:04.530  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 15:45:04.530  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:45:04.530  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 15:45:04.530  1015  1127 V NetworkStats: updateIfacesLocked()
08-30 15:45:04.530  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.530  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-30 15:45:04.530  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:45:04.530  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 15:45:04.530  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 15:45:04.530  1296  1296 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 15:45:04.540  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:04.540  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.540  1015  1127 V NetworkStats: performPollLocked() took 9ms
08-30 15:45:04.540  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:04.540  1015  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-30 15:45:04.540  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.540  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-30 15:45:04.540  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.540  1015  7485 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:04.540  1015  7485 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-30 15:45:04.540  1015  7485 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:04.540  1015  7485 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-30 15:45:04.540  1015  7485 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 15:45:04.540  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:45:04.540  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:04.540  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:45:04.540  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:04.540  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.540  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:45:04.540  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:04.540  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bbb6e91 removed from the list
08-30 15:45:04.540  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.540  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fa471f6 removed from the list
08-30 15:45:04.540  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:45:04.540  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:45:04.540  1015  1127 D ConnectivityService:    accepting network in place of null
08-30 15:45:04.550  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-30 15:45:04.550  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-30 15:45:04.550  1455  1455 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 15:45:04.550  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-30 15:45:04.550   278   887 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 15:45:04.550  1015  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-30 15:45:04.550   278   887 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-30 15:45:04.550  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:45:04.550  1015  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 15:45:04.550  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.550  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-30 15:45:04.550  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.550  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:04.550  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:04.550  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:04.550  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.550  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fa471f6 not in the list
08-30 15:45:04.550  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:45:04.550  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:45:04.550  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:45:04.550  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:45:04.550  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 15:45:04.550  7381  7389 D BtGatt.GattService: stopScan() - queue size =1
,08-30 15:45:04.550  7381  7410 D BtGatt.ScanManager: filter size is 1
08-30 15:45:04.550  7381  7410 D BtGatt.ScanManager: delete FilterIndex - 5
08-30 15:45:04.550  7381  7406 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 15:45:04.550  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.550  7381  7410 D BtGatt.ScanManager: stopping BLe Batch
08-30 15:45:04.550  7381  7412 D BtGatt.GattService: unregisterClient() - clientIf=6
08-30 15:45:04.560  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 15:45:04.560  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 15:45:04.560  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:45:04.560  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:45:04.560  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 15:45:04.560  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:45:04.560  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:45:04.560  6615  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:45:04.560  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 15:45:04.560  7381  7406 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 15:45:04.560  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 15:45:04.560  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-30 15:45:04.560  7381  7410 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 15:45:04.560  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.560  1015  1128 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:45:04.560  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.560  1015  1122 V NetworkStats: updateIfacesLocked()
08-30 15:45:04.560  7381  7406 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 15:45:04.560  1015  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-30 15:45:04.560  7381  7406 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 15:45:04.560  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-30 15:45:04.560  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:45:04.560  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 15:45:04.560  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-30 15:45:04.560  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:04.560  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.560  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1762cd removed from the list
08-30 15:45:04.560  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:04.560  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.560  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.560  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:04.560  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2488d064 removed from the list
08-30 15:45:04.560  1015  1122 V NetworkStats: performPollLocked() took 3ms
08-30 15:45:04.560  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:04.560  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17c45ec9 added. We now have 2 listener(s)
08-30 15:45:04.560  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:45:04.560  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:45:04.560  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.560  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:45:04.570  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
08-30 15:45:04.570  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 15:45:04.570  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 15:45:04.570  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-30 15:45:04.570  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0,
08-30 15:45:04.570  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 15:45:04.570  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-30 15:45:04.570  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-30 15:45:04.570  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:04.570  1015  1464 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 15:45:04.570  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:04.570  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 15:45:04.570  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:04.570  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf3c9ce added. We now have 9 listener(s)
08-30 15:45:04.570  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:04.570  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:45:04.570  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-30 15:45:04.570  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:04.570  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:04.570  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 15:45:04.570  1640  1640 I Hs20UtilService: Starting #23
,08-30 15:45:04.570  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.570  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-30 15:45:04.570  1175  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 15:45:04.570  4352  6679 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 15:45:04.570  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.570  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.570  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.570  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:04.570  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:04.580  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 15:45:04.580  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-30 15:45:04.580  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-30 15:45:04.580  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:45:04.580  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 15:45:04.580  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.580  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.580  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:04.580  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:45:04.580  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:04.580  1640  1699 I Hs20UtilService: Message received 5007
08-30 15:45:04.580  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 15:45:04.580  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 15:45:04.580  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-30 15:45:04.580  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 15:45:04.580  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-30 15:45:04.580  1296  1296 I NearbySettings: MountReceiver.onReceive - Keep current state
08-30 15:45:04.580  6615  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:45:04.580  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:04.580  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:45:04.580  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:04.580  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:04.580  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:04.580  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:45:04.580  6615  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:45:04.590  6615  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:04.590  6615  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:45:04.590  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:04.590  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@329bc7fc added. We now have 3 listener(s)
08-30 15:45:04.590  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:04.590  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:04.590  1015  1464 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 15:45:04.590  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 15:45:04.590  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:04.590  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:04.590  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 15:45:04.590  1640  1640 I Hs20UtilService: Starting #24
08-30 15:45:04.590  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-30 15:45:04.590  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:04.590  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:04.590  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:04.590  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c2b1e85 added. We now have 10 listener(s)
08-30 15:45:04.590  6615  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:04.590  6615  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:45:04.590  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:04.590  6615  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:45:04.590  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:04.590  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.590  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:04.590  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:04.590  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17c45ec9 removed from the list
08-30 15:45:04.590  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.590  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf3c9ce removed from the list
08-30 15:45:04.590  6615  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:45:04.590  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.590  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 15:45:04.590  1640  1699 I Hs20UtilService: Message received 5007
08-30 15:45:04.600  1296  1296 I NearbySettings: MountReceiver.onReceive - Keep current state
08-30 15:45:04.600  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.600  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.600  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:04.600  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:04.600  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.600  6615  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf3c9ce not in the list
08-30 15:45:04.600  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.600  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.600  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:04.600  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:04.600  6615  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:04.600  6615  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c2b1e85 removed from the list
08-30 15:45:04.600  6615  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:04.600  6615  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:04.600  6615  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:04.600  6615  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:04.600  6615  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@329bc7fc removed from the list
08-30 15:45:04.600  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 15:45:04.600  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 15:45:04.600  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 15:45:04.600  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:45:04.600  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 15:45:04.600  6615  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:04.610  6615  7539 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1318, name: My test thread name)
08-30 15:45:04.610  6615  7539 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1318, thread name: My test thread name)
08-30 15:45:04.610  6615  7539 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1318, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 15:45:04.610  1015  1409 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-30 15:45:04.610  1015  1133 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-30 15:45:04.610  1015  1133 D SecContentProvider2: mCursor = null
08-30 15:45:04.610  6615  7540 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1320, name: My test thread name)
08-30 15:45:04.610  6615  7540 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1320, thread name: My test thread name)
08-30 15:45:04.610  6615  7540 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1320, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 15:45:04.610  1015  1504 D SecContentProvider2: uri = 15 selection = getToastGravity
08-30 15:45:04.610  1015  1504 D SecContentProvider2: mCursor = null
08-30 15:45:04.610  6615  6668 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 15:45:04.610  6615  6668 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 15:45:04.610  6615  6668 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 15:45:04.610  6615  6668 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 15:45:04.610  6615  6668 D com.test.thalitest.ThaliTestRunner: Total duration: 23425 ms
08-30 15:45:04.610  1015  1027 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-30 15:45:04.610  1015  1027 D SecContentProvider2: mCursor = null
,08-30 15:45:04.620  6615  6668 I jxcore-log: *Native tests were executed*
08-30 15:45:04.620  6615  6668 I jxcore-log: 
08-30 15:45:04.620  6615  6668 I jxcore-log: Total number of executed tests:  80
08-30 15:45:04.620  6615  6668 I jxcore-log: 
08-30 15:45:04.620  6615  6668 I jxcore-log: Number of passed tests:  80
08-30 15:45:04.620  6615  6668 I jxcore-log: 
08-30 15:45:04.620  1015  1479 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-30 15:45:04.620  1015  1479 D SecContentProvider2: mCursor = null
08-30 15:45:04.620  6615  6668 I jxcore-log: Number of failed tests:  0
08-30 15:45:04.620  6615  6668 I jxcore-log: 
08-30 15:45:04.620  6615  6668 I jxcore-log: Number of ignored tests:  0
08-30 15:45:04.620  6615  6668 I jxcore-log: 
,08-30 15:45:04.620  6615  6668 I jxcore-log: Total duration:  23425
08-30 15:45:04.620  6615  6668 I jxcore-log: 
08-30 15:45:04.620  6615  6668 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 15:45:04.620  6615  6668 I jxcore-log: 
08-30 15:45:04.620  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:04.620  6615  6668 I jxcore-log: 
,08-30 15:45:04.620  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:04.620  6615  6668 I jxcore-log: 
08-30 15:45:04.620  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:04.620  6615  6668 I jxcore-log: 
08-30 15:45:04.630  1015  2020 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-30 15:45:04.630  1015  2020 D SecContentProvider2: mCursor = null
08-30 15:45:04.630  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:04.630  6615  6668 I jxcore-log: 
08-30 15:45:04.630  1015  1028 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-30 15:45:04.630  6615  6615 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 15:45:04.630  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:04.630  6615  6668 I jxcore-log: 
08-30 15:45:04.630  1015  1028 D SecContentProvider2: mCursor = null
08-30 15:45:04.630  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:04.630  6615  6668 I jxcore-log: 
08-30 15:45:04.630  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:04.630  6615  6668 I jxcore-log: 
08-30 15:45:04.630  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:45:04.630  6615  6668 I jxcore-log: 
08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
,08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
,08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-30 15:45:04.640  6615  6668 I jxcore-log: 
08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
,08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
,08-30 15:45:04.640  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:45:04.640  6615  6668 I jxcore-log: 
08-30 15:45:04.650  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 15:45:04.650  6615  6668 I jxcore-log: 
08-30 15:45:04.650  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:45:04.650  6615  6668 I jxcore-log: 
,08-30 15:45:04.650  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:45:04.650  6615  6668 I jxcore-log: 
,08-30 15:45:04.650  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:45:04.650  6615  6668 I jxcore-log: 
08-30 15:45:04.650  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:04.650  6615  6668 I jxcore-log: 
,08-30 15:45:04.660   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-30 15:45:04.680  1015  1504 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,08-30 15:45:04.680  1175  1175 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 15:45:04.710  6615  6615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:45:04.710  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:45:04.710  6615  6668 I jxcore-log: 
,08-30 15:45:04.860  6615  6615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-30 15:45:04.860  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:45:04.860  6615  6668 I jxcore-log: 
,08-30 15:45:04.910  7542  7542 D AndroidRuntime: ,
08-30 15:45:04.910  7542  7542 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 15:45:04.910  7542  7542 D AndroidRuntime: CheckJNI is OFF,
08-30 15:45:04.910  7542  7542 D AndroidRuntime: readGMSProperty: start
,08-30 15:45:04.910  7542  7542 D AndroidRuntime: readGMSProperty: already setted!!
08-30 15:45:04.910  7542  7542 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 15:45:04.910  7542  7542 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 15:45:04.910  7542  7542 D AndroidRuntime: readGMSProperty: end
08-30 15:45:04.910  7542  7542 D AndroidRuntime: addProductProperty: start,
,08-30 15:45:05.040  7542  7542 E AffinityControl: AffinityControl: registerfunction enter,
,08-30 15:45:05.060  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:45:05.060  6615  6615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:45:05.070  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:45:05.070  6615  6668 I jxcore-log: 
,08-30 15:45:05.070  7542  7542 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 15:45:05.090  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-30 15:45:05.090  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:05.090  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:45:05.090  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:05.090  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:05.090  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:05.090  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:45:05.090  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:45:05.090  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 15:45:05.090  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:45:05.090  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.090  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.090  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.090  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:45:05.100  6615  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:05.100  6615  6668 I jxcore-log: 
,08-30 15:45:05.100  1015  1479 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-30 15:45:05.100  1015  1479 D PackageManager: START PACKAGE DELETE: observer{968560395}
08-30 15:45:05.100  1015  1479 D PackageManager: pkg{<packageName>}
08-30 15:45:05.100  1015  1479 D PackageManager: user{0}
08-30 15:45:05.100  1015  1479 D PackageManager: caller{2000}
08-30 15:45:05.100  1015  1479 D PackageManager: flags{2}
08-30 15:45:05.100  1015  1479 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 15:45:05.100  1015  1479 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-30 15:45:05.100  1015  1479 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 15:45:05.100  1015  1479 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 15:45:05.110  7552  7552 E Zygote  : MountEmulatedStorage()
,08-30 15:45:05.110  7552  7552 I libpersona: KNOX_SDCARD checking this for 1000
08-30 15:45:05.110  7552  7552 E Zygote  : v2
08-30 15:45:05.110  7552  7552 I libpersona: KNOX_SDCARD not a persona
08-30 15:45:05.110  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 15:45:05.110  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-30 15:45:05.110  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1,
,08-30 15:45:05.110  7552  7552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:45:05.110  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-30 15:45:05.110  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 15:45:05.110  7552  7552 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:45:05.110  7552  7552 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:45:05.120  1015  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-30 15:45:05.130  1015  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7552 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 15:45:05.140  7552  7552 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:45:05.140  7552  7552 D ActivityThread: Added TimaKeyStore provider
,08-30 15:45:05.150   307   307 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 23.503ms
,08-30 15:45:05.170  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-30 15:45:05.170  1015  1040 I ActivityManager: Killing 6615:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 15:45:05.170   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.220ms total 17.731ms
,08-30 15:45:05.190   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.721ms
,08-30 15:45:05.230  1015  1055 W PackageSettings: Skipping PackageSetting{378a13ad com.example.hello/10168} due to missing metadata
,08-30 15:45:05.240   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-30 15:45:05.260   258   442 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-30 15:45:05.260  1015  1409 I WindowState: WIN DEATH: Window{2df1b6cd u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 15:45:05.260   258  1095 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-30 15:45:05.270   258   440 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-30 15:45:05.270  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{25fabded u0 com.test.thalitest/.MainActivity t2}
,08-30 15:45:05.270  1015  1409 D InputDispatcher: Focus left window: 6615
,08-30 15:45:05.280  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 15:45:05.280  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 15:45:05.280  1015  2020 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-30 15:45:05.280  1015  2020 D SecContentProvider2: mCursor = null
,08-30 15:45:05.290  1015  1040 D InputDispatcher: Focused application released
,08-30 15:45:05.290  1015  1040 D FocusedStackFrame: Set to : 0
,08-30 15:45:05.300  1015  1040 W ActivityManager: mDVFSHelper.acquire()
,08-30 15:45:05.300  1015  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-30 15:45:05.310  1015  1464 W ActivityManager: Spurious death for ProcessRecord{bcf1e8 6615:com.test.thalitest/u0a171}, curProc for 6615: null
,08-30 15:45:05.310  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-30 15:45:05.330  1481  1481 D Launcher: onRestart, Launcher: 1036082400
,08-30 15:45:05.330  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-30 15:45:05.340  1481  1481 D Launcher: onStart, Launcher: 1036082400
08-30 15:45:05.340  1481  1481 D Launcher.HomeView: onStart
,08-30 15:45:05.350  1481  1481 D Launcher: onResume, Launcher: 1036082400
,08-30 15:45:05.350  1015  1477 D SettingsProvider: name = kids_home_mode
,08-30 15:45:05.350  1015  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 15:45:05.350  1015  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 15:45:05.350  1015  1477 D SettingsProvider: selectionArgs: false
08-30 15:45:05.350  1015  1477 D SettingsProvider: selectionArgs: 10006
08-30 15:45:05.350  1015  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 15:45:05.350  1015  1477 D SettingsProvider: ret = -1
,08-30 15:45:05.350  1481  1481 D Launcher.HomeView: onResume
,08-30 15:45:05.350  5799  5799 I art     : Explicit concurrent mark sweep GC freed 2083(119KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 677us total 30.663ms
,08-30 15:45:05.360  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-30 15:45:05.380  7552  7552 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-30 15:45:05.380  7552  7552 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 15:45:05.380  7552  7552 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 15:45:05.380  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 15:45:05.390  1794  1794 E SamsungIME: mOCRHelper is null
,08-30 15:45:05.390  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-30 15:45:05.390  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-30 15:45:05.400  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-30 15:45:05.400  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-30 15:45:05.400  4352  4352 I art     : Explicit concurrent mark sweep GC freed 22345(1363KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.327ms total 81.892ms
08-30 15:45:05.400  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-30 15:45:05.400  1015  1039 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
08-30 15:45:05.400  1015  1039 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,08-30 15:45:05.410  4352  4373 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-30 15:45:05.410  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-30 15:45:05.420  7552  7552 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-30 15:45:05.420  7552  7552 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 15:45:05.420  7552  7552 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 15:45:05.420  7552  7552 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:45:05.420  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-30 15:45:05.420  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,08-30 15:45:05.460  1015  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-30 15:45:05.460  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:05.460  1015  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-30 15:45:05.460  1481  1481 D MenuAppsGridFragment: onResume
,08-30 15:45:05.460  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 15:45:05.460  1015  1040 I ActivityManager: Killing 6937:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-30 15:45:05.470  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 15:45:05.470  1015  1122 V NetworkStats: performPollLocked() took 12ms
08-30 15:45:05.470  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:05.470  1015  1678 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=9, mSplitNum[1]=16, mSplitNum[2]=23, mBgSplitQueueNum=3 divideNum= 6 r.nextReceiver= 2 receivers.size=29
,08-30 15:45:05.470  1015  1678 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-30 15:45:05.470  1015  1464 D ActivityManager: handle home activity for 0
,08-30 15:45:05.480  1015  1464 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-30 15:45:05.480  1015  1464 D KnoxTimeoutHandler: post home show event for user 0
08-30 15:45:05.480  1015  1464 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 15:45:05.480  1015  1464 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 15:45:05.480  1015  1464 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 15:45:05.480  1481  1481 D Launcher.HomeView: onPause
,08-30 15:45:05.480  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-30 15:45:05.490  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:05.490  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:05.490  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-30 15:45:05.490  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.490  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.490  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.490  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:45:05.500  1015  7485 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 15:45:05.500  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 15:45:05.500  7570  7570 E Zygote  : MountEmulatedStorage()
,08-30 15:45:05.500  7570  7570 E Zygote  : v2
08-30 15:45:05.500  7570  7570 I libpersona: KNOX_SDCARD checking this for 10031
08-30 15:45:05.500  7570  7570 I libpersona: KNOX_SDCARD not a persona
,08-30 15:45:05.500  7570  7570 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:45:05.510  1015  1040 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7570 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-30 15:45:05.510  7570  7570 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:45:05.510  7570  7570 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:45:05.510  1015  1133 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-30 15:45:05.510  1015  1039 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
08-30 15:45:05.510  1015  1133 D SecContentProvider2: mCursor = null
08-30 15:45:05.510  1015  1039 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,08-30 15:45:05.510   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-30 15:45:05.520  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 15:45:05.520  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 15:45:05.520  1015  2020 D InputDispatcher: Focus entered window: 1481
,08-30 15:45:05.530  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 15:45:05.530  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 15:45:05.530  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 15:45:05.530  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 15:45:05.530  1015  1127 V NetworkStats: updateIfacesLocked()
08-30 15:45:05.530  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-30 15:45:05.530  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 15:45:05.530  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 15:45:05.530  1015  1127 V NetworkStats: performPollLocked() took 4ms
,08-30 15:45:05.530  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:05.540  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 15:45:05.550  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 15:45:05.550  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-30 15:45:05.550  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-30 15:45:05.550  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 15:45:05.550  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 15:45:05.550  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 15:45:05.550  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 15:45:05.550  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 15:45:05.550  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 15:45:05.550  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 15:45:05.550  1015  2020 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 15:45:05.550  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:45:05.550  1440  1440 D RegisteredServicesCache: empty dynamic service
,08-30 15:45:05.560  1015  2020 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6615 uid 10171
,08-30 15:45:05.560  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-30 15:45:05.560  1015  7586 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 15:45:05.560  1175  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 15:45:05.560  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-30 15:45:05.570  7570  7570 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 15:45:05.570  4352  6679 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 15:45:05.570  7570  7570 D ActivityThread: Added TimaKeyStore provider
,08-30 15:45:05.570  1015  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-30 15:45:05.570  1794  1794 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false,
08-30 15:45:05.570  4352  6679 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 15:45:05.570  1175  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 15:45:05.580  1015  1409 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 15:45:05.580  1015  1464 D PersonaManager: isKioskContainerExistOnDevice
,08-30 15:45:05.580  1015  1480 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 15:45:05.590  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 15:45:05.590  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-30 15:45:05.590  1015  2844 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-30 15:45:05.590  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:05.590  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 15:45:05.610  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 15:45:05.610  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-30 15:45:05.610  1015  1039 W TextServicesManagerService: no available spell checker services found
,08-30 15:45:05.610  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-30 15:45:05.630  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-30 15:45:05.630  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-30 15:45:05.630  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-30 15:45:05.630  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 15:45:05.630  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 15:45:05.630  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 15:45:05.630  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 15:45:05.630  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 15:45:05.630  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 15:45:05.630  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 15:45:05.640  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 15:45:05.650  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,08-30 15:45:05.650  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,08-30 15:45:05.650  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-30 15:45:05.650  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 15:45:05.650  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 15:45:05.660  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 15:45:05.670  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,08-30 15:45:05.680  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-30 15:45:05.680  1175  1175 I StatusBar: Icon Only
,08-30 15:45:05.680  1175  1175 D PanelView: There is/are notification(s) 
,08-30 15:45:05.680  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 15:45:05.680  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.680  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:45:05.680  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.680  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:45:05.690  7081  7081 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-30 15:45:05.700  7589  7589 E Zygote  : MountEmulatedStorage()
,08-30 15:45:05.700  7589  7589 E Zygote  : v2
08-30 15:45:05.700  7589  7589 I libpersona: KNOX_SDCARD checking this for 10001
08-30 15:45:05.700  7589  7589 I libpersona: KNOX_SDCARD not a persona
,08-30 15:45:05.700  7589  7589 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:45:05.700  7589  7589 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:45:05.700  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7589 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 15:45:05.700  7589  7589 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:45:05.720  1015  7485 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 13:45:05 GMT], X-Android-Received-Millis=[1472564705728], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472564705678]}
08-30 15:45:05.720  1015  7485 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 15:45:05.720  1015  7485 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-30 15:45:05.720  1015  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-30 15:45:05.720  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-30 15:45:05.720  1015  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-30 15:45:05.720  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-30 15:45:05.720  4352  6679 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 15:45:05.720  1175  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 15:45:05.720  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 15:45:05.730  1015  1045 W ActivityManager: mDVFSHelper.release()
08-30 15:45:05.730  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ac4b2d8 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:144635
,08-30 15:45:05.730  7589  7589 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 15:45:05.730  1015  1055 I art     : Explicit concurrent mark sweep GC freed 88257(5MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/37MB, paused 11.267ms total 314.356ms
08-30 15:45:05.730  1015  1028 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
08-30 15:45:05.730  7589  7589 D ActivityThread: Added TimaKeyStore provider
08-30 15:45:05.730  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-30 15:45:05.740  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:05.740  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:45:05.740  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-30 15:45:05.740  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 15:45:05.760  1015  1055 D PackageManager: delete codoeFile: 
,08-30 15:45:05.770  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
08-30 15:45:05.770  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 15:45:05.770  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 15:45:05.770  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-30 15:45:05.770  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 15:45:05.770  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 15:45:05.770  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 15:45:05.770  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-30 15:45:05.770  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-30 15:45:05.770  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 15:45:05.770  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 15:45:05.780  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:05.780  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:05.780  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 15:45:05.780  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 15:45:05.780  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-30 15:45:05.780  1015  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-30 15:45:05.790  1015  1055 D PackageManager: result of delete: 1{968560395}
,08-30 15:45:05.800  1015  1464 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-30 15:45:05.800  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-30 15:45:05.800  7542  7542 D AndroidRuntime: Shutting down VM
,08-30 15:45:05.800  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:05.800  1015  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 15:45:05.800  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 15:45:05.840  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 15:45:05.840  1015  1055 D PackageManager: userId{-1}
08-30 15:45:05.840  1015  1055 D PackageManager: andCode{true}
,08-30 15:45:05.840  6808  7608 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-30 15:45:05.840  6808  7608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 15:45:05.840  6808  7608 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 15:45:05.840  6808  7608 I System.out: (HTTPLog)-Thread-1216-64892951: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-30 15:45:05.840  6808  7608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 15:45:05.840   278   887 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 15:45:05.840   278   887 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-30 15:45:05.850  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-30 15:45:05.850  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.850  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.850  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.850  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:45:05.860  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-30 15:45:05.860  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 15:45:05.860  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 15:45:05.870  7615  7615 E Zygote  : MountEmulatedStorage()
,08-30 15:45:05.870  7615  7615 E Zygote  : v2
08-30 15:45:05.870  7615  7615 I libpersona: KNOX_SDCARD checking this for 10003
08-30 15:45:05.870  7615  7615 I libpersona: KNOX_SDCARD not a persona
,08-30 15:45:05.870  7615  7615 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:45:05.870  7615  7615 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 15:45:05.870  7615  7615 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 15:45:05.870  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 15:45:05.870  1015  1055 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7615 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-30 15:45:05.880  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 15:45:05.880  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:45:05.880  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 15:45:05.880  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 15:45:05.880  1015  1462 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-30 15:45:05.890  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.890  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.890  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:05.890  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:45:05.890  6808  7608 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 15:45:05.900  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-30 15:45:05.900  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 15:45:05.900  7625  7625 E Zygote  : MountEmulatedStorage()
08-30 15:45:05.900  7625  7625 E Zygote  : v2
08-30 15:45:05.900  7625  7625 I libpersona: KNOX_SDCARD checking this for 10121
08-30 15:45:05.900  7625  7625 I libpersona: KNOX_SDCARD not a persona,
08-30 15:45:05.900  7625  7625 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 15:45:05.910  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-30 15:45:05.910  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 15:45:05.910  7625  7625 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 15:45:05.910  7625  7625 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-30 15:45:05.910  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 15:45:05.910  1015  1462 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7625 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-30 15:45:05.910  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 15:45:05.910  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 15:45:05.920  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 15:45:05.920  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 15:45:05.920  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 15:45:05.920  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-30 15:45:05.920  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-30 15:45:05.930  6985  6985 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-30 15:45:05.940  7615  7615 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:45:05.940  7615  7615 D ActivityThread: Added TimaKeyStore provider
08-30 15:45:05.940  7625  7625 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:45:05.940  7625  7625 D ActivityThread: Added TimaKeyStore provider
08-30 15:45:05.940  3464  7633 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
08-30 15:45:05.940  3464  7633 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
08-30 15:45:05.940  3464  7633 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-30 15:45:05.950  6503  6503 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-30 15:45:05.950  6503  6503 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,08-30 15:45:05.950  6503  6503 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-30 15:45:05.960  1905  2115 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 15:45:05.960  6808  7608 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 15:45:05.990  7003  7003 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:45:05.990  7003  7003 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-30 15:45:05.990  7003  7003 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-30 15:45:05.990  7003  7003 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-30 15:45:06.000  7625  7625 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:45:06.000  7625  7625 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 15:45:06.000  7625  7625 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 15:45:06.010  6503  6503 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-30 15:45:06.010  6503  6503 I SA      : [OR] == isSIMCardReady false ==
,08-30 15:45:06.010  1015  1215 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-30 15:45:06.010  1015  1215 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-30 15:45:06.010  6503  6503 I SA      : [SCU] == networkStateCheck == true
,08-30 15:45:06.010  3464  7633 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-30 15:45:06.010  3464  7633 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-30 15:45:06.010  6503  6503 I SA      : [DM] getCountryCodeFromCSC : PL
08-30 15:45:06.010  3464  7633 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
08-30 15:45:06.010  1015  1215 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:06.010  1015  1215 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-30 15:45:06.010  1015  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
08-30 15:45:06.010  3464  7633 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-30 15:45:06.020  6503  6503 I SA      : isChinaCountryCode : false
08-30 15:45:06.020  6503  6503 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-30 15:45:06.020  6503  6503 I SA      : [OR] == networkStateCheck true ==
08-30 15:45:06.020  3464  7633 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
08-30 15:45:06.020  3464  7633 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
08-30 15:45:06.020  7542  7542 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-30 15:45:06.020  3464  7633 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-30 15:45:06.020  3464  7633 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-30 15:45:06.030  6503  6503 I SA      : [OR] GetMyCountryZoneTask
,08-30 15:45:06.030  7081  7081 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-30 15:45:06.040  7081  7081 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-30 15:45:06.040  7625  7625 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:45:06.040  7081  7081 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-30 15:45:06.040  7625  7625 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-30 15:45:06.040  1015  1409 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 15:45:06.040  1015  1409 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-30 15:45:06.040  6503  6503 I SA      : [OR] onReceive END
,08-30 15:45:06.040  1015  1409 W ActivityManager: userId = 0, bbcId = -10000
08-30 15:45:06.040  1015  1409 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 15:45:06.040  7081  7081 D InitializeManagerStateMachine: exit::IDLE
08-30 15:45:06.040  7081  7081 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-30 15:45:06.040  1015  1409 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 15:45:06.050  7081  7081 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-30 15:45:06.050  7081  7081 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-30 15:45:06.050  7081  7081 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-30 15:45:06.050  7081  7081 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-30 15:45:06.050  7081  7081 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-30 15:45:06.050  7081  7081 D InitializeManagerStateMachine: entry::SUCCESS
08-30 15:45:06.050  7081  7081 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-30 15:45:06.050  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:45:06.050  1015  1504 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-30 15:45:06.050  1015  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-30 15:45:06.060  3464  7633 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-30 15:45:06.060  6503  7652 I SA      : [SRS] prepareGetMyCountryZone
08-30 15:45:06.060  7625  7625 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-30 15:45:06.060   278   887 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 15:45:06.060   278   887 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-30 15:45:06.070  1015  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-30 15:45:06.070  1015  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 15:45:06.070  1015  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-30 15:45:06.070  3464  7633 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-30 15:45:06.080  4352  4352 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 15:45:06.080  4352  4805 I iu.UploadsManager: num queued entries: 0
,08-30 15:45:06.080  4352  4805 I iu.UploadsManager: num updated entries: 0
,08-30 15:45:06.080  7081  7081 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-30 15:45:06.080  7081  7081 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-30 15:45:06.080  7081  7081 D InitializeManagerStateMachine: exit::SUCCESS
08-30 15:45:06.080  7081  7081 D InitializeManagerStateMachine: entry::IDLE
,08-30 15:45:06.090  1924  1924 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 15:45:06.090  4352  4805 I iu.SyncManager: NEXT; no task
,08-30 15:45:06.090  6503  7652 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-30 15:45:06.090  6503  7652 I SA      : [SSP] query invoked
,08-30 15:45:06.090  1015  1027 I ActivityManager: Killing 7049:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-30 15:45:06.100  1015  1215 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-30 15:45:06.100  1015  1215 D SecContentProvider2: mCursor = null
,08-30 15:45:06.110  1015  1477 I ActivityManager: Killing 7065:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-30 15:45:06.110  2648  2660 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 21
,08-30 15:45:06.110  1924  1924 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-30 15:45:06.120  1924  1924 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-30 15:45:06.120  1924  1924 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-30 15:45:06.120  1924  1924 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-30 15:45:06.120  1924  1924 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 15:45:06.130  1924  1924 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-30 15:45:06.140  1015  1477 W ActivityManager: ProcessRecord{242ef405 7065:com.sec.android.fotaclient/u0a8} is already killed
,08-30 15:45:06.140   255   255 E lowmemorykiller: Error writing /proc/7065/oom_score_adj; errno=22
,08-30 15:45:06.140  1015  1477 I ActivityManager: Existing provider com.sec.android.fotaclient/.log.MasterLogProvider is crashing; detaching ProcessRecord{37359c5a 7003:com.sec.android.diagmonagent/1000}
,08-30 15:45:06.140  1015  1477 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
08-30 15:45:06.140  6503  7652 I SA      : [TPMU] GetMccFromDB : null
08-30 15:45:06.140  6503  7652 I SA      : [SCU] getMccFromPreferece mcc = 260
08-30 15:45:06.140  6503  7652 I SA      : [LBE] isSupportCheckDomainRegion : false
08-30 15:45:06.140  6503  7652 I SA      : [TPM] isNoProxy(default) : true
,08-30 15:45:06.140  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:06.140  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:45:06.150  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 15:45:06.150  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 15:45:06.150  6503  7652 E File    : fail readDirectory() errno=2
,08-30 15:45:06.160  7658  7658 E Zygote  : MountEmulatedStorage()
08-30 15:45:06.160  7658  7658 I libpersona: KNOX_SDCARD checking this for 10008
08-30 15:45:06.160  7658  7658 E Zygote  : v2
08-30 15:45:06.160  7658  7658 I libpersona: KNOX_SDCARD not a persona
08-30 15:45:06.160  7658  7658 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 15:45:06.160  7658  7658 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 15:45:06.160  1015  1477 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7658 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:45:06.160  7658  7658 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 15:45:06.200  7658  7658 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 15:45:06.200  7658  7658 D ActivityThread: Added TimaKeyStore provider
,08-30 15:45:06.200  1905  7653 I qtaguid : Tagging socket 53 with tag 1000040700000000{268436487,0} for uid -1, pid: 1905, getuid(): 10011
,08-30 15:45:06.230  1015  1462 I ActivityManager: Killing 6746:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-30 15:45:06.250  1905  1905 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/ns.db" with flag (131138) and mode_t (0) due to error (30)
,08-30 15:45:06.250  1905  1905 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1508)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at ivm.g(:com.google.android.gms:204)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at ivm.e(:com.google.android.gms:176)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at ivh.a(:com.google.android.gms:22519)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at oek.b(:com.google.android.gms:342)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at oeh.a(:com.google.android.gms:844)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at oei.handleMessage(:com.google.android.gms:13054)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:45:06.250  1905  1905 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-30 15:45:06.260  1905  1905 D AndroidRuntime: Shutting down VM
,08-30 15:45:06.260  1905  1905 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQstg5Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
08-30 15:45:06.260  1905  1905 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjQgKDMwNTE3NzQtMDM0KRji-eAR
08-30 15:45:06.260  1905  1905 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQwPngEQ
08-30 15:45:06.260  1905  1905 I GCore-Chimera-Crash: ==
08-30 15:45:06.260  1905  1905 I GCore-Chimera-Crash: GCore-Chimera-Crash
,08-30 15:45:06.260  1905  1905 I DeviceDoctorDatabaseHelper: Cleaning stale data from database!
,08-30 15:45:06.260  1905  1905 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131138) and mode_t (0) due to error (30)
08-30 15:45:06.260  1905  1905 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131072) and mode_t (0) due to error (2)
08-30 15:45:06.260  1905  1905 E SQLiteLog: (14) cannot open file at line 32510 of [b3bb660af9]
08-30 15:45:06.260  1905  1905 E SQLiteLog: (14) os_unix.c:32510: (2) open(/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db) - 
,08-30 15:45:06.260  1905  1905 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db'.
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1508)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at ivm.g(:com.google.android.gms:204)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at ivm.e(:com.google.android.gms:176)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at ivh.a(:com.google.android.gms:22519)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at iiq.c(:com.google.android.gms:207)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at ifm.uncaughtException(:com.google.android.gms:2111)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at ifs.uncaughtException(:com.google.android.gms:54)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at ifl.uncaughtException(:com.google.android.gms:62)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-30 15:45:06.260  1905  1905 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: FATAL EXCEPTION: main
08-30 15:45:06.260  1905  1905 E AndroidRuntime: Process: com.google.android.gms.persistent, PID: 1905
08-30 15:45:06.260  1905  1905 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at andro,id.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1508)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at ivm.g(:com.google.android.gms:204)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at ivm.e(:com.google.android.gms:176)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at ivh.a(:com.google.android.gms:22519)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at oek.b(:com.google.android.gms:342)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at oeh.a(:com.google.android.gms:844)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at oei.handleMessage(:com.google.android.gms:13054)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 15:45:06.260  1905  1905 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 15:45:06.270  1481  1481 I Choreographer: Skipped 41 frames!  The application may be doing too much work on its main thread.
08-30 15:45:06.270  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{b5fc488 token=android.os.BinderProxy@2d5ef611 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-30 15:45:06.270  1481  1481 D Launcher.HomeView: onStop
08-30 15:45:06.270  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d5ef611 time:145176
08-30 15:45:06.270  1015  1678 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
08-30 15:45:06.270  7149  7647 E SQLiteLog: (28) failed to open "/data/data/com.google.android.apps.plus/databases/es0.db" with flag (131138) and mode_t (0) due to error (30)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.plus/databases/es0.db'.
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at hga.getReadableDatabase(PG:168)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at bfb.a(PG:222)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at ddv.a(PG:18181)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at ddv.a(PG:9087)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at ddw.run(PG:1686)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-30 15:45:06.290  7149  7647 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: Couldn't open es0.db for writing (will try read-only):
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at hga.getReadableDatabase(PG:168)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at bfb.a(PG:222)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at ddv.a(PG:18181)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at ddv.a(PG:9087)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at ddw.run(PG:1686)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-30 15:45:06.290  7149  7647 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-30 15:45:06.290  1905  1905 I Process : Sending signal. PID: 1905 SIG: 9
08-30 15:45:06.300  7149  7647 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database

```
