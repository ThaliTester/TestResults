#### Test 828946820542738_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main,
09-06 19:09:24.227   287   287 E SMD     : DCD OFF
09-06 19:09:24.507  6738  6738 D AndroidRuntime: 
09-06 19:09:24.507  6738  6738 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:09:24.507  6738  6738 D AndroidRuntime: CheckJNI is OFF
09-06 19:09:24.507  6738  6738 D AndroidRuntime: readGMSProperty: start
09-06 19:09:24.507  6738  6738 D AndroidRuntime: readGMSProperty: already setted!!
09-06 19:09:24.507  6738  6738 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 19:09:24.507  6738  6738 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:09:24.507  6738  6738 D AndroidRuntime: readGMSProperty: end
09-06 19:09:24.507  6738  6738 D AndroidRuntime: addProductProperty: start
09-06 19:09:24.647  6738  6738 E AffinityControl: AffinityControl: registerfunction enter
09-06 19:09:24.667  6738  6738 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-06 19:09:24.687  1015  1718 E PersonaManagerService: inState():  stateMachine is null !!
09-06 19:09:24.687  1015  1718 I PersonaManagerService: PersonaId don't exist
09-06 19:09:24.687  1015  1718 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-06 19:09:24.687  1015  1718 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-06 19:09:24.707  1015  1718 W ActivityManager: mDVFSHelper.acquire()
09-06 19:09:24.717   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-06 19:09:24.717   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-06 19:09:24.737  1015  1718 D FocusedStackFrame: Set to : 0
09-06 19:09:24.737  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 19:09:24.737  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-06 19:09:24.747  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.747  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.747  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.747  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 19:09:24.747  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.747  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 19:09:24.757   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
09-06 19:09:24.767  6750  6750 E Zygote  : MountEmulatedStorage()
09-06 19:09:24.767  6750  6750 E Zygote  : v2
09-06 19:09:24.767  6750  6750 I libpersona: KNOX_SDCARD checking this for 10171
09-06 19:09:24.767  6750  6750 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:24.767  1015  1718 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-06 19:09:24.767  1015  1718 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6750 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:09:24.767  1015  1718 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:09:24.767  1015  1718 D InputDispatcher: Focused application set to: xxxx
09-06 19:09:24.767  1015  1718 D InputDispatcher: Focus left window: 1495
09-06 19:09:24.767  6750  6750 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:24.767  6738  6738 D AndroidRuntime: Shutting down VM
09-06 19:09:24.777  6750  6750 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:24.787  6750  6750 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-06 19:09:24.787  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:09:24.787  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 19:09:24.797  6750  6750 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:24.807  6750  6750 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:24.807  1015  1486 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-06 19:09:24.817  1015  1015 V ActivityManager: Display changed displayId=0
09-06 19:09:24.817  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-06 19:09:24.827  1015  1486 D PersonaManager: isKioskContainerExistOnDevice
09-06 19:09:24.837  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-06 19:09:24.857   257   443 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
09-06 19:09:24.857   257  1058 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
09-06 19:09:24.867  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{19f494db token=android.os.BinderProxy@2be726e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-06 19:09:24.867  1495  1495 D Launcher: onTrimMemory. Level: 20
09-06 19:09:24.967  6750  6750 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-06 19:09:24.977  6738  6738 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-06 19:09:24.997  6750  6750 I cr.library_loader: Time to load native libraries: 13 ms (timestamps 7923-7936)
09-06 19:09:24.997  6750  6750 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-06 19:09:25.047  6750  6750 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a351f00}
09-06 19:09:25.047  6750  6750 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-06 19:09:25.047  6750  6750 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:09:25.087  6750  6750 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-06 19:09:25.087  6750  6750 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:09:25.087  6750  6750 E SysUtils: ApplicationContext is null in ApplicationStatus
09-06 19:09:25.147  6750  6750 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:25.147  6750  6750 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:25.147  6750  6750 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:25.147  6750  6750 I Adreno-EGL: Local Branch: 
09-06 19:09:25.147  6750  6750 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:25.147  6750  6750 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:25.147  6750  6750 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-06 19:09:25.237  6750  6750 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:09:25.247  6750  6750 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-06 19:09:25.247  6750  6750 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-06 19:09:25.257  6750  6750 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-06 19:09:25.257  6750  6750 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-06 19:09:25.337  1015  1040 W ActivityManager: Activity pause timeout for ActivityRecord{3584791d u0 com.test.thalitest/.MainActivity t2}
09-06 19:09:25.377  6750  6750 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:09:25.387  6750  6750 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-06 19:09:25.397  6750  6750 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 19:09:25.397  6750  6750 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-06 19:09:25.407  6750  6750 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-06 19:09:25.417  6750  6750 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:09:25.417  6750  6750 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:09:25.547  6750  6790 D OpenGLRenderer: Render dirty regions requested: true
09-06 19:09:25.547  1015  4382 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 19:09:25.547  1015  4382 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:09:25.547  1015  4382 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 19:09:25.547  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:09:25.547  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-06 19:09:25.557  6750  6777 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
09-06 19:09:25.557  6750  6750 V ActivityThread: updateVisibility : ActivityRecord{15c1d60 token=android.os.BinderProxy@31d5611d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 19:09:25.567  6750  6750 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 19:09:25.567  6750  6750 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 19:09:25.577   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
09-06 19:09:25.597  1015  1137 D InputDispatcher: Focus entered window: 6750
09-06 19:09:25.607  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:09:25.607  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 19:09:25.607  6750  6750 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-06 19:09:25.607  6750  6790 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 19:09:25.607  6750  6790 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-06 19:09:25.607  6750  6790 D OpenGLRenderer: Enabling debug mode 0
09-06 19:09:25.637  1015  1486 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-06 19:09:25.637  1015  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-06 19:09:25.637  1177  1177 I StatusBar: Icon Only
09-06 19:09:25.637  1177  1177 D PanelView: There is/are notification(s) 
09-06 19:09:25.657  1015  1045 I ActivityManager: Displayed Component not be shown by security: +820ms (total +911ms)
09-06 19:09:25.657  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3584791d u0 com.test.thalitest/.MainActivity t2} time:108592
09-06 19:09:25.657  1015  1045 W ActivityManager: mDVFSHelper.release()
09-06 19:09:25.657   257   443 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
09-06 19:09:25.657  6750  6750 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-06 19:09:25.657  6750  6750 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@31d5611d time:108597
09-06 19:09:25.657   257  1058 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
09-06 19:09:25.667  1963  1963 I SamsungIME: getCurrentCandidateView
09-06 19:09:25.677  6750  6750 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6750
09-06 19:09:25.747  1015  1326 E Watchdog: !@Sync 3
,09-06 19:09:25.787  1963  1963 D SamsungIME: Dismiss ExpandCandiate
,09-06 19:09:25.867  6750  6750 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 19:09:25.937  1963  1963 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 19:09:25.947  6750  6794 D jxcore_app_log: JniHelper::setJavaVM(0xb71d72b0), pthread_self() = -1216980720
,09-06 19:09:25.957  6750  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:09:25.957  6750  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:09:25.957  6750  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:09:25.957  6750  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:09:25.957  6750  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-06 19:09:25.957  6750  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46f6fb6 added. We now have 1 listener(s)
,09-06 19:09:25.967  6750  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-06 19:09:25.967  6750  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:09:25.967  6750  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:09:25.967  6750  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:09:25.967  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-06 19:09:25.977  6750  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb5cb8d added. We now have 1 listener(s)
,09-06 19:09:25.977  6750  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:25.977  6750  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:09:25.977  6750  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 19:09:25.977  6750  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:09:25.977  6750  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:09:25.977  6750  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 19:09:25.977  1963  1963 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 19:09:25.987  6750  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:25.987  6750  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-06 19:09:25.987  6750  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-06 19:09:25.987  6750  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:25.987  6750  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:25.987  6750  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:25.987  6750  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:25.987  6750  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:25.987  6750  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:25.987  6750  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:25.987  6750  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:25.987  6750  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:09:25.987  6750  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:25.997  6750  6794 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:09:25.997  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:25.997  1963  1963 I SamsungIME: KeybaordView init() : load resources
,09-06 19:09:25.997  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:26.027  1963  1963 I SamsungIME: getCurrentKeyboard
,09-06 19:09:26.027  6750  6750 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:09:26.027  1963  1963 I SamsungIME: getTextKeyboard
,09-06 19:09:26.057  1963  1963 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-06 19:09:26.237   325   325 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-06 19:09:26.237   325   325 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-06 19:09:26.587  6750  6803 W jxcore-log: Initializing JXcore engine
09-06 19:09:26.587  6750  6803 W jxcore-log: JXcore engine is ready
,09-06 19:09:26.647  1964  1964 E audit   : type=1400 msg=audit(1473181766.637:205): avc:  denied  { ioctl } for  pid=6803 comm="Thread-1250" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-06 19:09:26.647  1964  1964 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:26.647  1964  1964 E audit   : type=1300 msg=audit(1473181766.637:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9f8fb8f8 items=0 ppid=308 ppcomm=main pid=6803 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1250" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-06 19:09:26.647  1964  1964 E audit   : type=1320 msg=audit(1473181766.637:205): 
,09-06 19:09:26.657  6750  6803 W jxcore-log: Starting JXcore engine
,09-06 19:09:26.757  6750  6803 W jxcore-log: Platform android
09-06 19:09:26.757  6750  6803 W jxcore-log: 
09-06 19:09:26.757  6750  6803 W jxcore-log: Process ARCH arm
09-06 19:09:26.757  6750  6803 W jxcore-log: 
,09-06 19:09:26.967  6750  6803 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:09:26.967  6750  6803 I jxcore-log: 
,09-06 19:09:26.967  6750  6803 W jxcore-log: JXcore engine is started
,09-06 19:09:26.967  6750  6794 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:09:26.967  6750  6750 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:09:27.227   287   287 E SMD     : DCD OFF
,09-06 19:09:29.527  1015  1047 I PowerManagerService: [PWL] Off : 50s ago,
,09-06 19:09:29.667  1015  3373 D SSRM:n  : SIOP:: AP = 330,
,09-06 19:09:30.227   287   287 E SMD     : DCD OFF
,09-06 19:09:31.237   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:09:32.237   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:33.227  5652  5652 D FactoryTest: Not factory mode
09-06 19:09:33.227  5652  5652 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-06 19:09:33.227  5652  5652 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-06 19:09:33.227  5652  5652 D MTPRx   : still no open session command from host, so toast
,09-06 19:09:33.227   287   287 E SMD     : DCD OFF
,09-06 19:09:33.237  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-06 19:09:33.237  5652  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-06 19:09:33.237  5652  5652 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116172
,09-06 19:09:33.237  1015  1313 E PersonaManagerService: inState():  stateMachine is null !!
09-06 19:09:33.237  1015  1313 I PersonaManagerService: PersonaId don't exist
,09-06 19:09:33.237  1015  1313 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-06 19:09:33.237  1015  1313 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:09:33.237   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:33.237  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:33.237  1015  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:33.247  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-06 19:09:33.267  1015  1313 W ActivityManager: mDVFSHelper.acquire()
,09-06 19:09:33.277  1015  1532 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:09:33.277  1015  1532 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-06 19:09:33.277  1015  1532 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:09:33.277  1015  1532 D BatteryService: stay LED for fully charged
,09-06 19:09:33.287  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:09:33.287  1015  1313 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:09:33.297  1015  1313 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:09:33.297  1015  1313 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:09:33.297  1015  1313 D InputDispatcher: Focused application set to: xxxx
,09-06 19:09:33.297  1015  1313 D InputDispatcher: Focus left window: 6750
,09-06 19:09:33.297  5652  5652 E MTPRx   : started activity for popup
,09-06 19:09:33.297  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:09:33.297  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:09:33.307  1015  1015 I MotionRecognitionService: Plugged,
09-06 19:09:33.307  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:09:33.317  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-06 19:09:33.317  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:09:33.317  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:09:33.317  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 19:09:33.327  5652  5652 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-06 19:09:33.327  5652  5652 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-06 19:09:33.327  5652  5652 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:09:33.327  5652  5652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:09:33.327  5652  5652 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:09:33.327  5652  5652 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:09:33.327  3187  3187 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:09:33.327  3187  3284 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:09:33.337  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:09:33.337  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:09:33.347  5652  5652 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-06 19:09:33.347  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:09:33.347  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-06 19:09:33.347  1177  1177 D SViewCoverView: level :100 plugged : 2
,09-06 19:09:33.367  1015  4387 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:09:33.367  1015  4387 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 19:09:33.367  1015  4387 D InputDispatcher: Focused application set to: xxxx
,09-06 19:09:33.367  1015  4387 D InputDispatcher: Focus entered window: 6750
,09-06 19:09:33.377  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:09:33.377  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:09:33.377  1015  1532 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 19:09:33.377  1015  1532 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@145f3c84 attribute=null, token = android.os.BinderProxy@1aff9654
,09-06 19:09:33.417  5652  5652 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-06 19:09:33.427  5652  5652 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-06 19:09:33.427  5652  5652 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-06 19:09:33.447  6750  6750 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:09:33.447  6750  6750 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-06 19:09:33.447  6750  6750 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 19:09:33.447  6750  6750 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-06 19:09:33.447  1015  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-06 19:09:33.447  1015  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:09:33.447  1015  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-06 19:09:33.447  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:09:33.457  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 19:09:33.467  6750  6750 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:09:33.467  6750  6750 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-06 19:09:33.467  6750  6750 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a738ca9 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@156a4256, 16908290=android.view.AbsSavedState$1@156a4256}, android:focusedViewId=100}]}]
09-06 19:09:33.467  6750  6750 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-06 19:09:33.467  6750  6750 V ActivityThread: updateVisibility : ActivityRecord{15c1d60 token=android.os.BinderProxy@31d5611d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 19:09:33.467  6750  6750 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:09:33.467  6750  6750 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-06 19:09:33.467  6750  6750 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@31d5611d time:116409
,09-06 19:09:33.477  1015  1502 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:09:34.237   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:34.797  1015  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,09-06 19:09:35.237   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:36.227   287   287 E SMD     : DCD OFF,
,09-06 19:09:36.237   325   325 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-06 19:09:36.267  1015  1040 W ActivityManager: mDVFSHelper.release()
,09-06 19:09:37.067  1015  1093 V AlarmManager: waitForAlarm result :4,
,09-06 19:09:37.077  1015  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-06 19:09:37.107  1980  1980 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-06 19:09:37.277  1015  1486 I art     : Explicit concurrent mark sweep GC freed 32601(1786KB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 2.454ms total 155.988ms
,09-06 19:09:37.297  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:37.297  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-06 19:09:37.297  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:37.297  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:37.297  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:37.307  4796  4796 D ConnectivityManager: CallingUid : 10011, CallingPid : 4796
,09-06 19:09:37.307  1015  1137 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:09:37.307  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
09-06 19:09:37.307  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-06 19:09:37.307  1015  1126 D ConnectivityService: apparently satisfied.  currentScore=60
,09-06 19:09:37.307  4796  6812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 19:09:37.367  4796  6813 W DriveInitializer: Background init thread started
,09-06 19:09:37.417   256   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-06 19:09:37.417   256   527 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:37.417  4796  6813 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-06 19:09:37.467  1015  4386 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:37.467  1015  4386 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-06 19:09:37.467  1015  4386 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:37.467  1015  4386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:37.467  1015  4386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:37.477  1015  1486 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-06 19:09:37.477  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-06 19:09:37.507  1015  1518 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:37.507  1015  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-06 19:09:37.507  1015  1518 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:37.507  1015  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:37.507  1015  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:37.527  4796  6813 W DriveInitializer: Background init thread ended
,09-06 19:09:37.547  4796  6821 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-06 19:09:37.547  4796  6821 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-06 19:09:37.567  1980  1980 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:09:37.617  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:37.617  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:37.617  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:37.737  1980  1980 I art     : Explicit concurrent mark sweep GC freed 64825(3MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 10MB/17MB, paused 1.235ms total 68.013ms,
,09-06 19:09:37.757  1015  4386 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:37.757  1015  4386 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-06 19:09:37.757  1015  4386 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:37.757  1015  4386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:37.757  1015  4386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:37.787  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:37.787  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-06 19:09:37.797  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:37.797  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:37.797  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:37.857  1015  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:37.857  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:37.857  1015  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:37.857  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:37.897  1015  1718 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:37.897  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:37.897  1015  1718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:37.897  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:37.957  1015  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:37.957  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:37.957  1015  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:37.957  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:37.957  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:09:37.957  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:37.957  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:37.957  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:37.977  6826  6826 E Zygote  : MountEmulatedStorage(),
09-06 19:09:37.977  6826  6826 E Zygote  : v2
,09-06 19:09:37.977  6826  6826 I libpersona: KNOX_SDCARD checking this for 10011
09-06 19:09:37.977  6826  6826 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:37.977  1015  1488 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6826 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-06 19:09:37.977  6826  6826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:37.987  6826  6826 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:37.987  6826  6826 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:38.007  6826  6826 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:38.007  6826  6826 D ActivityThread: Added TimaKeyStore provider,
,09-06 19:09:38.027  6826  6826 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-06 19:09:38.027  6826  6826 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 19:09:38.067  6826  6826 I MultiDex: VM with version 2.1.0 has multidex support
09-06 19:09:38.067  6826  6826 I MultiDex: install
09-06 19:09:38.067  6826  6826 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 19:09:38.097  6826  6826 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-06 19:09:38.167  6826  6826 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 19:09:38.167  6826  6826 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d6a13bc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-06 19:09:38.167  6826  6826 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-06 19:09:38.187  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-06 19:09:38.197  6826  6826 D ChimeraCfgMgr: Reading stored module config
,09-06 19:09:38.197  1015  1718 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.207  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.207  1015  1718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:38.207  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.217  1015  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.217  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.217  1015  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.217  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.277  1980  1980 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=ab797c21-ab69-4fd2-8a57-e6b5d55ef91e
,09-06 19:09:38.297  6826  6843 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-06 19:09:38.307  1015  1137 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-06 19:09:38.307  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-06 19:09:38.307  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:38.307  1015  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.307  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.307  1980  1980 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:09:38.317  1980  1980 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:09:38.327  1015  4387 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.327  1015  4387 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.327  1015  4387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.327  1015  4387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.327  6826  6826 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-06 19:09:38.327  6826  6826 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-06 19:09:38.417   282   815 D WVCdm   : Instantiating CDM.
,09-06 19:09:38.417   282   795 I WVCdm   : CdmEngine::OpenSession
,09-06 19:09:38.417   282   795 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-06 19:09:38.427   282   795 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-06 19:09:38.457   282   795 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,09-06 19:09:38.487  4348  4514 I art     : Explicit concurrent mark sweep GC freed 1418(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 772us total 21.421ms
,09-06 19:09:38.507   282   795 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-06 19:09:38.517   282   815 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-06 19:09:38.517   282   815 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-06 19:09:38.517   282   815 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-06 19:09:38.517   282   815 D WVCdm   : PrepareKeyRequest: nonce=1801763871
,09-06 19:09:38.547  6826  6838 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-06 19:09:38.547  6826  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:09:38.547  6826  6838 I System.out: (HTTPLog)-Static: isShipBuild true
09-06 19:09:38.547  6826  6838 I System.out: (HTTPLog)-Thread-1230-435712249: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-06 19:09:38.547  6826  6838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:38.547   277   917 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:09:38.547   277   917 D Netd    : getNetworkForDns: using netid 502 for uid 10011
09-06 19:09:38.567  1980  2146 W GCoreFlp: No location to return for getLastLocation()
,09-06 19:09:38.597  6826  6838 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:09:38.597  6826  6838 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6826, getuid(): 10011
,09-06 19:09:38.597  1015  1531 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.607  1015  1531 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.607  1015  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.607  1015  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.607  1015  4386 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.607  1015  4386 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:38.607  1015  4386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.607  1015  4386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.617  1015  1718 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.617  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.617  1015  1718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.617  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.637  4796  6822 D UdcContextInitService: registered all accounts: true
,09-06 19:09:38.637  1980  2149 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:09:38.677  1980  2165 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-06 19:09:38.767  1015  1313 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:38.767  1015  1313 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-06 19:09:38.767  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.767  1015  1313 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.767  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.857  1015  1718 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-06 19:09:38.857  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-06 19:09:38.857  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.857  1015  1718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.857  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.877  1015  1518 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.877  1015  1518 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.877  1015  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:38.877  1015  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.907  1015  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.907  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.907  1015  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.907  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.927  6826  6838 I qtaguid : Untagging socket 33
,09-06 19:09:38.977  1015  1531 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.977  1015  1531 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:38.977  1015  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.977  1015  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:09:38.977  1980  6856 E CommitToConfigurationOperation: Malformed snapshot token (size): 
09-06 19:09:38.977  1980  6854 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-06 19:09:38.977  1015  1518 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.977  1015  1518 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.977  1015  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.977  1015  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:39.007  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:39.007  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:39.007  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:39.007  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:39.007  1980  6856 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-06 19:09:39.007  1980  6854 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-06 19:09:39.007  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:39.007  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:39.007  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:39.007  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:39.037  1015  4387 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:39.037  1015  4387 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:39.037  1015  4387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:39.037  1015  4387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:39.037  1980  6856 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-06 19:09:39.037  1980  6854 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-06 19:09:39.037  1980  6854 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-06 19:09:39.047  1980  6854 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-06 19:09:39.187  1980  6854 I art     : Explicit concurrent mark sweep GC freed 38934(2MB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 11MB/18MB, paused 1.630ms total 80.858ms
,09-06 19:09:39.207  1015  5159 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 19:09:39.237   287   287 E SMD     : DCD OFF
,09-06 19:09:39.267  1015  1531 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-06 19:09:39.267  1015  1531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-06 19:09:39.277  1015  1531 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:39.277  1015  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:39.277  1015  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:39.307  1980  6854 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-06 19:09:39.307  1980  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:09:39.307  1980  6854 I System.out: (HTTPLog)-Static: isShipBuild true
09-06 19:09:39.307  1980  6854 I System.out: (HTTPLog)-Thread-276-296090235: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-06 19:09:39.307  1980  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:39.317   277   917 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:09:39.317   277   917 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-06 19:09:39.317  1980  6854 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:09:39.317  1980  6854 I qtaguid : Tagging socket 69 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1980, getuid(): 10011
,09-06 19:09:39.337  6858  6858 I dex2oat : ----------------------------------------------------
09-06 19:09:39.337  6858  6858 I dex2oat : <SS>: S T A R T I N G . . .
09-06 19:09:39.337  6858  6858 I dex2oat : <SS>: Zip is absent. Canceled.
,09-06 19:09:39.337  6858  6858 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-06 19:09:39.397  1980  6854 I qtaguid : Tagging socket 72 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1980, getuid(): 10011
,09-06 19:09:39.407  6858  6858 I dex2oat : dex2oat took 62.502ms (threads: 4)
,09-06 19:09:39.417  6826  6838 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:39.417  6826  6838 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:39.417  6826  6838 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:39.417  6826  6838 I Adreno-EGL: Local Branch: 
09-06 19:09:39.417  6826  6838 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:39.417  6826  6838 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:39.417  6826  6838 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:09:39.497  6826  6838 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:39.497  6826  6838 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:39.497  6826  6838 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:39.497  6826  6838 I Adreno-EGL: Local Branch: 
09-06 19:09:39.497  6826  6838 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:39.497  6826  6838 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:39.497  6826  6838 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:09:39.537  6826  6838 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:39.537  6826  6838 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:39.537  6826  6838 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:39.537  6826  6838 I Adreno-EGL: Local Branch: 
09-06 19:09:39.537  6826  6838 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:39.537  6826  6838 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:39.537  6826  6838 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:09:39.677  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:09:39.677  6750  6803 I jxcore-log: 
,09-06 19:09:39.687  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:09:39.687  6750  6803 I jxcore-log: 
,09-06 19:09:39.687  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:39.687  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:39.687  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:39.687  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:39.687  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:39.687  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.687  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:39.687  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:39.687  1015  3373 D SSRM:n  : SIOP:: AP = 360
09-06 19:09:39.697  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.697  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:09:39.697  6750  6803 I jxcore-log: 
09-06 19:09:39.697  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:09:39.697  6750  6803 I jxcore-log: 
,09-06 19:09:39.717  1015  4382 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 19:09:39.727  1980  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:39.727  1980  6854 I qtaguid : Tagging socket 69 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1980, getuid(): 10011
,09-06 19:09:39.877  1015  1028 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 19:09:39.897  1980  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:39.897  1980  6854 I qtaguid : Tagging socket 69 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1980, getuid(): 10011
,09-06 19:09:39.917  1980  6824 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:39.927   277   917 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:09:39.927   277   917 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-06 19:09:39.927  1980  6824 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:09:39.927  1980  6824 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1980, getuid(): 10011
,09-06 19:09:39.967  1980  6824 I qtaguid : Tagging socket 75 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1980, getuid(): 10011
,09-06 19:09:39.977  1015  3386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:09:40.077   282   282 I WVCdm   : CdmEngine::CloseSession
,09-06 19:09:40.087   282   282 I WVCdm   : L3 Terminate.
,09-06 19:09:40.217  1980  2165 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-06 19:09:40.217  1980  2165 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-06 19:09:40.227  1980  2165 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-06 19:09:38.759+0200, stopTime=2016-09-06 19:09:40.234+0200, duration=1475ms
,09-06 19:09:40.237  1980  6872 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:40.237   277   917 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:09:40.237   277   917 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-06 19:09:40.237  1980  6872 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:09:40.237  1980  6872 I qtaguid : Tagging socket 77 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1980, getuid(): 10011
,09-06 19:09:40.277  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-06 19:09:40.287  1980  6872 I qtaguid : Tagging socket 79 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1980, getuid(): 10011
,09-06 19:09:40.397  6750  6803 D executeNativeTests: Running unit tests
,09-06 19:09:40.467  1015  4386 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 19:09:40.467  1980  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:40.467  1980  6854 I qtaguid : Tagging socket 69 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1980, getuid(): 10011
,09-06 19:09:40.497  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:09:40.497  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 added. We now have 2 listener(s)
,09-06 19:09:40.497  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:09:40.497  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:09:40.497  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:09:40.497  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:40.497  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 added. We now have 2 listener(s)
09-06 19:09:40.497  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:40.497  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:09:40.497  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:40.497  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:40.497  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:40.497  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:40.497  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:40.497  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:40.497  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:40.497  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:40.497  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:40.507  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:40.507  6750  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:09:40.507  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:40.507  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:09:40.507  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:40.507  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:40.507  6750  6803 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-06 19:09:40.507  6750  6803 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:09:40.507  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:09:40.507  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:40.507  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:40.507  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.507  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:40.507  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.507  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.507  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.507  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.507  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:40.507  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:09:40.507  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 removed from the list
09-06 19:09:40.507  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.507  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 removed from the list
09-06 19:09:40.507  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.507  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.517  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.517  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.517  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.517  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.517  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.517  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.517  6750  6803 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 19:09:40.517  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.517  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.517  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.517  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.517  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.517  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.517  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.517  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.517  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.517  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.517  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.517  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.517  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.517  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.517  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.517  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.517  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.517  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:09:40.527  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.527  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.527  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.527  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.527  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.527  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.527  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.527  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.527  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.527  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.527  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.527  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.527  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.527  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.527  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.527  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.527  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.527  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.527  6750  6803 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:09:40.527  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:40.537  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:40.537  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:40.537  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:40.537  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:40.537  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:40.537  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:40.537  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:40.537  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:40.537  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:40.537  6750  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:09:40.537  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:09:40.537  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:09:40.537  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:09:40.537  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:40.537  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:09:40.537  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:40.547  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:09:40.547  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:40.547  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:09:40.547  1980  6872 I qtaguid : Untagging socket 77
09-06 19:09:40.557  1980  2165 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
09-06 19:09:40.557  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:09:40.557  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-06 19:09:40.557  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-06 19:09:40.557  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:09:40.567  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:09:40.567  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:09:40.577  3187  3354 D BtGatt.GattService: registerClient() - UUID=31a81f63-721f-4f95-923f-b99fd7734b2e
,09-06 19:09:40.617  3187  3276 D BtGatt.GattService: onClientRegistered() - UUID=31a81f63-721f-4f95-923f-b99fd7734b2e, clientIf=6
,09-06 19:09:40.627  6750  6759 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:09:40.627  3187  3209 D BtGatt.GattService: start scan with filters
,09-06 19:09:40.627  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:09:40.627  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:09:40.627  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:09:40.627  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:09:40.627  3187  3282 D BtGatt.ScanManager: handling starting scan,
,09-06 19:09:40.627  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:09:40.627  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:09:40.627  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:09:40.627  3187  3282 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:40.637  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,09-06 19:09:40.647  3187  3276 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:09:40.647  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.647  3187  3282 D BtGatt.ScanManager: allow scan with filters
09-06 19:09:40.647  3187  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:09:40.647  3187  3282 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-06 19:09:40.647  6750  6803 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:09:40.647  3187  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:09:40.647  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.647  3187  3282 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:09:40.647  3187  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-06 19:09:40.647  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.647  6750  6803 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:09:40.647  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:09:40.647  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 19:09:40.647  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.647  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-06 19:09:40.647  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:40.647  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:09:40.647  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:09:40.647  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:09:40.647  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:09:40.647  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:09:40.647  3187  3276 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
09-06 19:09:40.647  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.657  3187  3285 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:09:40.657  3187  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:09:40.657  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.657  3187  3209 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:09:40.657  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:09:40.657  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:09:40.657  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:09:40.657  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:09:40.657  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:09:40.657  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:40.657  3187  3282 D BtGatt.ScanManager: filter size is 1
09-06 19:09:40.657  3187  3282 D BtGatt.ScanManager: delete FilterIndex - 3
,09-06 19:09:40.667  3187  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:09:40.667  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.667  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:09:40.667  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:09:40.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:09:40.667  3187  3282 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:09:40.667  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:40.667  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:40.667  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:40.667  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:40.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.667  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.667  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:40.667  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.667  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.667  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.667  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.667  6750  6803 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:09:40.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:40.667  3187  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:09:40.667  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.667  3187  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:09:40.667  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:40.667  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:40.667  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:40.667  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:40.667  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:40.667  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:40.667  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:40.667  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:40.667  3187  3276 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:09:40.667  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.677  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:40.677  6750  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:40.677  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:40.677  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:09:40.677  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:09:40.677  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:09:40.677  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:40.677  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:09:40.677  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:40.677  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:09:40.687  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:09:40.687  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:09:40.687  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:09:40.687  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:09:40.687  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:09:40.687  3187  3285 D BtGatt.GattService: registerClient() - UUID=d3981b6a-1070-4eff-b10f-d827cdcfe03a
,09-06 19:09:40.727  3187  3276 D BtGatt.GattService: onClientRegistered() - UUID=d3981b6a-1070-4eff-b10f-d827cdcfe03a, clientIf=6
,09-06 19:09:40.737  6750  6758 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-06 19:09:40.737  3187  3354 D BtGatt.GattService: start scan with filters
,09-06 19:09:40.737  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:09:40.737  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:09:40.737  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:09:40.737  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:09:40.737  3187  3282 D BtGatt.ScanManager: handling starting scan
,09-06 19:09:40.737  3187  3276 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:09:40.737  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.737  3187  3282 D BtGatt.ScanManager: allow scan with filters
09-06 19:09:40.737  3187  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:09:40.737  3187  3282 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 19:09:40.737  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:09:40.737  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:09:40.737  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:40.737  3187  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:09:40.737  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.737  3187  3282 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:09:40.737  3187  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:09:40.737  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:09:40.747  3187  3276 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:09:40.747  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.747  3187  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:09:40.747  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.747  6750  6803 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:09:40.757  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:09:40.757  6750  6803 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:09:40.757  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:09:40.757  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 19:09:40.757  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.757  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:09:40.757  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:40.757  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:09:40.757  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:09:40.757  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:09:40.757  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 19:09:40.757  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:09:40.757  3187  3209 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:09:40.757  3187  3282 D BtGatt.ScanManager: filter size is 1
,09-06 19:09:40.767  3187  3354 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:09:40.767  3187  3282 D BtGatt.ScanManager: delete FilterIndex - 4
,09-06 19:09:40.767  3187  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:09:40.767  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.767  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-06 19:09:40.767  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:09:40.767  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 19:09:40.767  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:09:40.767  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:09:40.767  3187  3282 D BtGatt.ScanManager: stopping BLe Batch,
09-06 19:09:40.767  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:40.777  3187  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:09:40.777  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:09:40.777  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.777  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:09:40.777  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:09:40.777  3187  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:09:40.777  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:40.777  3187  3276 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:09:40.777  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.777  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:09:40.777  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:09:40.777  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:40.777  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:09:40.777  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:40.777  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:40.777  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.777  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.777  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.777  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.777  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.777  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:40.777  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.787  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:09:40.787  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:09:40.787  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.787  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
,09-06 19:09:40.787  6750  6803 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:09:40.787  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:40.797  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:40.797  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:40.797  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:40.797  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:40.797  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:40.797  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:40.797  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:40.797  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:40.797  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:40.797  6750  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:40.797  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:40.807  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:09:40.807  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:09:40.807  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:09:40.807  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:40.807  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:09:40.807  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:40.807  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:09:40.807  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:09:40.807  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:09:40.817  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:09:40.817  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:09:40.817  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:09:40.817  3187  3202 D BtGatt.GattService: registerClient() - UUID=751de3c7-72e6-40fb-af7b-c16179809053
,09-06 19:09:40.857  3187  3276 D BtGatt.GattService: onClientRegistered() - UUID=751de3c7-72e6-40fb-af7b-c16179809053, clientIf=6
,09-06 19:09:40.857  6750  6759 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:09:40.857  3187  3285 D BtGatt.GattService: start scan with filters
,09-06 19:09:40.867  3187  3282 D BtGatt.ScanManager: handling starting scan
,09-06 19:09:40.867  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:09:40.867  3187  3276 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:09:40.867  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.867  3187  3282 D BtGatt.ScanManager: allow scan with filters
09-06 19:09:40.867  3187  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:09:40.867  3187  3282 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 19:09:40.867  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:09:40.867  3187  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:09:40.867  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.867  3187  3282 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:09:40.867  3187  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:09:40.867  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:09:40.877  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:09:40.877  3187  3276 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:09:40.877  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.877  3187  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:09:40.877  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.877  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:09:40.877  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:09:40.877  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:40.877  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:09:40.887  6750  6803 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:09:40.887  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.887  6750  6803 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:09:40.887  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.887  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:09:40.887  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:40.887  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:09:40.887  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:40.887  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:40.887  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:09:40.887  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:09:40.887  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:09:40.887  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:09:40.887  3187  3202 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:09:40.897  3187  3282 D BtGatt.ScanManager: filter size is 1
09-06 19:09:40.897  3187  3282 D BtGatt.ScanManager: delete FilterIndex - 5
09-06 19:09:40.897  3187  3285 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:09:40.897  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:09:40.897  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:09:40.897  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:09:40.897  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:09:40.897  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:09:40.897  3187  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:09:40.897  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.897  3187  3282 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:09:40.897  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:40.897  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 19:09:40.897  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:09:40.897  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:09:40.897  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:40.897  3187  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:09:40.897  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.897  3187  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:09:40.907  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:40.907  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:09:40.907  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:40.907  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.907  6750  6803 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:09:40.907  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.907  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:09:40.907  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.907  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:40.907  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.907  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list,
09-06 19:09:40.907  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.907  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-06 19:09:40.907  3187  3276 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
09-06 19:09:40.907  3187  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.907  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.907  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.907  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
,09-06 19:09:40.907  6750  6803 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 19:09:40.907  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:09:40.907  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.907  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.907  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.907  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.907  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.907  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.907  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.907  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:40.907  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.907  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.907  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.907  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.907  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-06 19:09:40.907  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.907  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.907  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.907  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:40.907  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.907  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.907  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:40.907  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.907  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:09:40.907  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.907  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.907  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.907  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.917  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.917  6750  6803 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 19:09:40.917  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:09:40.917  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.917  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.917  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.917  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.917  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.917  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.917  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:09:40.917  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.917  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-06 19:09:40.917  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.917  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:40.917  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.917  6750  6803 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted,
09-06 19:09:40.917  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.917  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.917  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.917  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.917  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.917  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
,09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.917  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.917  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.917  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.917  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.917  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.917  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:40.917  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:09:40.917  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:09:40.917  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:40.917  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:09:40.917  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:40.917  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.917  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.917  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.927  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:09:40.927  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.927  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.927  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.927  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:40.927  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.927  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.927  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.927  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.927  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:40.927  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.927  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.927  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.927  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:40.927  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.927  6750  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:40.927  6750  6803 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:09:40.927  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-06 19:09:40.937  6750  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:40.937  6750  6803 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710],
,09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010],
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:09:40.937  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:09:40.937  6750  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:09:40.937  6750  6803 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:40.937  6750  6803 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-06 19:09:40.937  6750  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:40.937  6750  6803 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:40.937  6750  6803 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:09:40.937  6750  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:40.937  6750  6803 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:40.937  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 19:09:40.937  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:09:40.937  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:09:40.937  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 19:09:40.947  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:09:40.947  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:09:40.947  6750  6803 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:09:40.947  6750  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:40.947  6750  6803 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-06 19:09:40.947  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.947  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.947  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.947  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.947  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.947  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.947  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-06 19:09:40.947  6750  6880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1314)
09-06 19:09:40.947  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.947  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.947  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.947  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.947  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.947  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.947  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.947  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.947  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.947  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:09:40.947  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.947  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.947  6750  6881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1314
09-06 19:09:40.947  6750  6803 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:09:40.947  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.947  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.947  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.947  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.947  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.947  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.947  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.947  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.947  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.947  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:09:40.947  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.947  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.947  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.947  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.947  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.947  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.947  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.947  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
,09-06 19:09:40.957  6750  6803 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:09:40.957  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.957  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.957  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.957  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.957  6750  6803 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:09:40.957  6750  6803 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-06 19:09:40.957  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:40.957  6750  6803 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:09:40.957  6750  6803 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:09:40.957  6750  6803 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:09:40.957  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:09:40.957  6750  6803 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:09:40.957  6750  6803 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:09:40.957  6750  6803 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:09:40.957  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:09:40.957  6750  6803 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,09-06 19:09:40.957  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.957  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.957  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.957  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.957  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.957  6750  6880 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.957  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.957  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.957  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.957  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.957  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.957  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.957  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.957  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.967  6750  6803 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:09:40.967  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:40.967  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-06 19:09:40.967  6750  6803 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:09:40.967  6750  6803 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:09:40.967  6750  6880 D BluetoothSocket: connect(): myUserId = 0
09-06 19:09:40.967  6750  6880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:09:40.967  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:09:40.967  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:40.967  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.967  6750  6750 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:09:40.967  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:09:40.967  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:09:40.967  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:09:40.967  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.967  6750  6803 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:09:40.967  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.967  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.967  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:40.967  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:09:40.967  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:09:40.967  6750  6750 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:09:40.967  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.967  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.967  6750  6882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:09:40.967  6750  6882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 19:09:40.967  3187  3202 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:09:40.967  6750  6880 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-06 19:09:40.967  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:40.967  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:40.967  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:40.967  6750  6750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 19:09:40.967  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:40.967  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.,DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.967  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.967  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.967  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.967  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.967  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.967  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.967  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.967  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.967  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.977  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.977  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.977  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.977  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.977  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.977  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 19:09:40.977  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.977  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.977  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
,09-06 19:09:40.977  6750  6803 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:09:40.977  6750  6803 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:09:40.977  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:09:40.977  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:40.977  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.977  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.977  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.977  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.977  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.977  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.977  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
,09-06 19:09:40.977  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.977  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.977  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.977  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.977  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.977  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.977  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.977  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.977  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.977  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.977  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
,09-06 19:09:40.977  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.977  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.977  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:09:40.977  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.987  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.987  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.987  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.987  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.987  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.987  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:40.987  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.987  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.987  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.987  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:09:40.987  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.987  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.987  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.987  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.987  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.987  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.987  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.987  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.987  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.987  6750  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b51efc7 not in the list
09-06 19:09:40.987  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:40.987  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.987  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.987  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.987  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.987  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.987  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.987  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.987  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.987  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbe9f4 not in the list
,09-06 19:09:40.987  6750  6803 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:40.987  6750  6803 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:40.987  6750  6803 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:09:40.987  6750  6803 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:09:40.987  6750  6803 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:09:40.987  6750  6803 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:09:40.987  6750  6803 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:09:40.997  6750  6803 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-06 19:09:40.997  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:40.997  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1959a3b6 added. We now have 2 listener(s)
09-06 19:09:40.997  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:40.997  6750  6803 D BluetoothAdapter: enable()
,09-06 19:09:40.997  6750  6803 D BluetoothAdapter: enable(): BT is already enabled..!
,09-06 19:09:40.997  1015  1532 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 19:09:40.997  1015  1532 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:09:40.997  1015  1532 D SecContentProvider2: mCursor = null
,09-06 19:09:40.997  1015  1532 D WifiService: setWifiEnabled: true pid=6750, uid=10171
,09-06 19:09:41.007  1015  1532 W ActivityManager: Permission Denial: getCurrentUser() from pid=6750, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:09:41.007  1015  1532 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:09:41.007  1015  1532 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6750, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:41.007  1015  1532 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:09:41.007  1015  1532 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:09:41.007  1015  1532 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:09:41.007  1015  1532 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:09:41.007  1015  1532 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 19:09:41.007  1015  1532 D SettingsProvider: name = wifi_on
,09-06 19:09:41.007  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:41.007  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fd058b7 added. We now have 3 listener(s)
09-06 19:09:41.007  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:41.017  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:09:41.017  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b47b824 added. We now have 4 listener(s)
09-06 19:09:41.017  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:41.017  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:41.017  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@177c8f8d added. We now have 5 listener(s)
09-06 19:09:41.017  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:41.017  1015  4382 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 19:09:41.017  1015  4382 D WifiService: setWifiEnabled: false pid=6750, uid=10171
09-06 19:09:41.017  1015  4382 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:09:41.017  1015  4382 D SecContentProvider2: mCursor = null
09-06 19:09:41.017  1015  4382 D SettingsProvider: name = wifi_on
,09-06 19:09:41.027  1015  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-06 19:09:41.027  6750  6803 D BluetoothAdapter: disable()
09-06 19:09:41.027  1348  1348 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:09:41.027  1348  1348 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-06 19:09:41.027  1015  1486 D SettingsProvider: name = bluetooth_on
09-06 19:09:41.027  1348  1348 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-06 19:09:41.027  1348  1348 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:09:41.037  3187  3273 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-06 19:09:41.037  3187  3273 D BluetoothAdapterProperties: Setting state to 13
09-06 19:09:41.037  3187  3273 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:09:41.037  3187  3273 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:41.037  3187  3273 D BluetoothAdapterService: updateAdapterState state is 13
,09-06 19:09:41.037  1015  1718 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:41.037  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.037  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.037  1015  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.037  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:41.037  1348  1348 I wpa_supplicant: Scan aborted because the firmware maybe busy.
09-06 19:09:41.037  1348  1348 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.,
09-06 19:09:41.037  1348  1348 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
09-06 19:09:41.037  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:09:41.037  3187  3187 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-06 19:09:41.037  3187  3187 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e6e0ef2, channel: 19, state: LISTENING
09-06 19:09:41.037  3187  3187 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e6e0ef2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1935469a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e964943mSocket: android.net.LocalSocket@2d21cbc0 impl:android.net.LocalSocketImpl@19f870f9 fd:FileDescriptor[74]
09-06 19:09:41.037  3187  3187 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d21cbc0 impl:android.net.LocalSocketImpl@19f870f9 fd:FileDescriptor[74]
09-06 19:09:41.037  3187  3273 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:41.037  3187  3273 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:09:41.047  3187  3273 D BluetoothAdapterService: terminating service from this receiver
,09-06 19:09:41.047  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:41.047  1015  1518 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.047  1015  1518 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.047  1015  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.047  1015  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:41.047  3187  3273 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:09:41.047  3187  3273 D BluetoothAdapterProperties: mDiscovering is false,
,09-06 19:09:41.047  1015  4387 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:09:41.047  3187  3273 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 19:09:41.047  3063  3063 D BluetoothPbap: Proxy object disconnected
,09-06 19:09:41.057  3187  3276 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
09-06 19:09:41.057  3187  3276 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:09:41.057  3063  3063 D PbapServerProfile: Bluetooth service disconnected
09-06 19:09:41.057  1015  1124 E WifiNative-wlan0: do suspend true
,09-06 19:09:41.057  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.057  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:41.057  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:41.057  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:41.057  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:41.057  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:41.057  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:41.057  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:41.057  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:41.057  3187  3273 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:09:41.057  3187  3273 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-06 19:09:41.057  3187  3273 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-06 19:09:41.057  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.057  3187  3273 E bt-btif : cmd socket is not created
09-06 19:09:41.057  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:41.057  6750  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:41.057  6750  6880 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1587c953, channel: -1, state: INIT
09-06 19:09:41.057  6750  6880 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1587c953, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@135a3290, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@242f9789mSocket: android.net.LocalSocket@2565738e impl:android.net.LocalSocketImpl@33ba7af fd:FileDescriptor[105]
09-06 19:09:41.057  6750  6880 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2565738e impl:android.net.LocalSocketImpl@33ba7af fd:FileDescriptor[105]
09-06 19:09:41.057  6750  6880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1314)
,09-06 19:09:41.057  3187  3296 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-06 19:09:41.057  3187  3296 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 19:09:41.057  3187  5225 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:09:41.057  3187  3273 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:09:41.067  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.067  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.067  3187  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:41.067  3187  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:41.067  3187  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:09:41.067  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.067  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:41.067  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:41.067  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:41.067  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:41.067  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:41.067  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:41.067  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:41.067  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:41.067  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.067  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:41.077  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.087  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-06 19:09:41.087  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-06 19:09:41.097  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:09:41.097  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:09:41.107  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:41.107  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:41.107  1177  1177 D BluetoothTile:  getBluetoothState : 13
,09-06 19:09:41.107  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:41.107  1963  1963 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:41.107  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:09:41.107  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:41.107  3187  3187 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e4a369f, channel: 5, state: LISTENING
09-06 19:09:41.107  3187  3187 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e4a369f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c4e2bcb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2037e3ecmSocket: android.net.LocalSocket@33c623b5 impl:android.net.LocalSocketImpl@3d3c8a4a fd:FileDescriptor[76]
09-06 19:09:41.107  3187  3187 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33c623b5 impl:android.net.LocalSocketImpl@3d3c8a4a fd:FileDescriptor[76]
,09-06 19:09:41.107  3187  3187 I BtOppRfcommListener: stopping Accept Thread
09-06 19:09:41.107  1015  4382 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 19:09:41.107  3187  3187 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4259dbb, channel: 12, state: LISTENING
09-06 19:09:41.107  3187  3187 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@4259dbb, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e7db1fd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33b552d8mSocket: android.net.LocalSocket@2e824631 impl:android.net.LocalSocketImpl@39c10116 fd:FileDescriptor[79]
09-06 19:09:41.107  3187  3187 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2e824631 impl:android.net.LocalSocketImpl@39c10116 fd:FileDescriptor[79]
,09-06 19:09:41.117  3187  5225 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:09:41.117  1015  1531 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:41.117  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.117  1015  1718 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:41.117  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.117  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:41.117  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.127  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.127  1015  1718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:41.127  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:41.127  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:41.127  1015  1488 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:09:41.127  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.127  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.127  1015  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.127  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:41.127  3187  3187 V BluetoothOppManager: cleanUp...
,09-06 19:09:41.137  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:41.137  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:41.147  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:41.147  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:09:41.147  1015  1518 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 19:09:41.147  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.147  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.147  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.147  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.157  1015  1518 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6888 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-06 19:09:41.167  6888  6888 E Zygote  : MountEmulatedStorage()
09-06 19:09:41.167  6888  6888 I libpersona: KNOX_SDCARD checking this for 10055
09-06 19:09:41.167  6888  6888 E Zygote  : v2
09-06 19:09:41.167  6888  6888 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:41.167  6888  6888 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:41.167  6888  6888 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:41.167  6888  6888 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:41.207  6888  6888 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:41.207  6888  6888 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:41.207  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
09-06 19:09:41.207  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:09:41.217   277   921 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:09:41.217  1980  3018 V NativeCrypto: Read error: ssl=0xb76ce5f0: I/O error during system call, Connection timed out
,09-06 19:09:41.217  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-06 19:09:41.217  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.217  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:09:41.217  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:09:41.217  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-06 19:09:41.217  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.217  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.217  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.217  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.217  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 19:09:41.217  1980  3018 V NativeCrypto: SSL shutdown failed: ssl=0xb76ce5f0: I/O error during system call, Broken pipe
,09-06 19:09:41.227  1980  3018 E GCM     : Wifi connection closed with errorCode 20
,09-06 19:09:41.227  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:09:41.237  1015  1486 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,09-06 19:09:41.237  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.237  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:41.237  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.237  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.237  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.237  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.237  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
09-06 19:09:41.237  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-06 19:09:41.247  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:09:41.247  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-06 19:09:41.247  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:09:41.247  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:09:41.247  1015  1015 D RttService: SCAN_AVAILABLE : 1
,09-06 19:09:41.247  1015  1148 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:09:41.247  1015  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-14ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:41.247  1015  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-14ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:41.247  1015  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 19:09:41.247  1015  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:41.247  1015  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-06 19:09:41.247   325   325 I ServiceManager: Waiting for service AtCmdFwd...
09-06 19:09:41.247  1015  1737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:41.247  1015  1737 I qtaguid : Tagging socket 96 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
,09-06 19:09:41.257  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:09:41.257  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:09:41.257  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,09-06 19:09:41.257  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:09:41.257  1015  1737 I qtaguid : Untagging socket 96
,09-06 19:09:41.257  1015  1737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:41.257  1015  1123 D WifiP2pService: P2pDisablingState
,09-06 19:09:41.257  3187  3296 W bt-l2cap: HC lib lpm enable=0 return 0
09-06 19:09:41.257  3187  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:41.257  3187  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:41.257  3187  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:41.257  3187  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:41.257  3187  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:41.257  3187  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:41.257  3187  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:41.257  3187  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:41.257  3187  3296 W bt-btif : ag scb idx 1 not allocated
09-06 19:09:41.257  3187  3296 W bt-btif : ag scb idx 2 not allocated
09-06 19:09:41.257  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:41.257  3187  3296 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:09:41.257  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:09:41.257  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-06 19:09:41.257  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:41.257  1015  1045 D WifiDisplayController: disconnect
09-06 19:09:41.257  1015  1045 D WifiDisplayController: updateConnection
09-06 19:09:41.257  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:41.257  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:09:41.257  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:09:41.257  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:41.257  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:09:41.257  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:09:41.257  3187  3340 I bt_userial_mct: exiting userial_read_thread
09-06 19:09:41.257  3187  3340 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:09:41.257  3187  3276 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:09:41.257  3187  3298 I bt_vendor: hw_epilog_process
09-06 19:09:41.267  3187  3276 D bt_userial_mct: userial_close
09-06 19:09:41.267  3187  3276 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 19:09:41.297  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 19:09:41.297  1015  1123 D WifiP2pService: p2p socket connection lost
09-06 19:09:41.297  1015  1123 D WifiP2pService: P2pDisabledState
,09-06 19:09:41.307   277   917 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:09:41.307   277   917 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-06 19:09:41.307  1015  1124 E WifiNative-wlan0: do suspend true
,09-06 19:09:41.307  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.307  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-06 19:09:41.307  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:41.307  1015  1126 V NetworkStats: updateIfacesLocked()
09-06 19:09:41.307  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:09:41.317  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:09:41.307  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
,09-06 19:09:41.317  1015  1126 V NetworkStats: performPollLocked() took 5ms
09-06 19:09:41.317  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.317  1015  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,09-06 19:09:41.317  1015  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-06 19:09:41.317  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.317  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.317  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-06 19:09:41.317  1015  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:09:41.327  1177  1636 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:09:41.327  4796  6812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-06 19:09:41.327  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 19:09:41.327  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:09:41.327  1015  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:09:41.327  1468  1468 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:09:41.327  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-06 19:09:41.327  1468  1468 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:09:41.327  1015  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-06 19:09:41.327  1015  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:09:41.327  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-06 19:09:41.327  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-06 19:09:41.337  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 19:09:41.337  6888  6888 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-06 19:09:41.337  1015  1128 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:09:41.337  1015  1121 V NetworkStats: updateIfacesLocked()
09-06 19:09:41.337  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.337  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:09:41.337  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 19:09:41.337  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 19:09:41.337  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 19:09:41.337  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:09:41.337  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-06 19:09:41.337  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
,09-06 19:09:41.337  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.337  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:41.337  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:09:41.337  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-06 19:09:41.337  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:09:41.337  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:09:41.337  1177  1177 D StatusBar.NetworkController: updateDataNetType()
09-06 19:09:41.337  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 19:09:41.337  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 19:09:41.337  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.337  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.337  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 19:09:41.337  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.347  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-06 19:09:41.347  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-06 19:09:41.347  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-06 19:09:41.347  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.347  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:41.347  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.347  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.347  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.347  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.357  1015  1121 V NetworkStats: performPollLocked() took 16ms
09-06 19:09:41.357  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.357  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.357  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.367  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-06 19:09:41.367  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,09-06 19:09:41.367   277   921 D CommandListener: Clearing all IP addresses on wlan0,
,09-06 19:09:41.377  6888  6888 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-06 19:09:41.377  6888  6888 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-06 19:09:41.377  6888  6888 D UserAnalysis: Create SecureDbHelper
,09-06 19:09:41.377  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.377  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:41.377  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.377  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.377  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.377  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.377  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:09:41.387  1348  1348 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:09:41.397  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.397  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:41.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.397  6888  6888 D IntelligenceServiceApplication: onCreate(),
09-06 19:09:41.407  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 19:09:41.407  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:41.407  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:09:41.407  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.407  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:41.407  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.407  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.407  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.407  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.417  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:41.417  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-06 19:09:41.417  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:41.417  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:09:41.417  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:41.417  1177  1177 D HotspotTile: onReceive : 0, 0,
,09-06 19:09:41.427  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:41.427  6888  6888 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 19:09:41.427  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.427  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:41.427  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:41.427  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:41.437  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.437  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:41.437  1015  5159 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 19:09:41.437  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.437  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.437  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.437  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.457  6912  6912 E Zygote  : MountEmulatedStorage(),
09-06 19:09:41.457  6912  6912 E Zygote  : v2
09-06 19:09:41.457  6912  6912 I libpersona: KNOX_SDCARD checking this for 10105
09-06 19:09:41.457  6912  6912 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:41.457  6912  6912 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:41.457  1015  5159 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6912 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-06 19:09:41.457  6912  6912 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:41.457  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-06 19:09:41.457  6888  6888 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-06 19:09:41.457  6912  6912 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:41.467  6888  6888 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 19:09:41.477  6750  6750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-06 19:09:41.477  1348  1348 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:09:41.487  3187  3276 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:09:41.487  3187  3276 I bt_vendor: bluetooth satus is on
09-06 19:09:41.487  3187  3276 I bt_vendor: bt-vendor : resetting BT status
09-06 19:09:41.487  3187  3276 I bt_vendor: Starting hciattach daemon
09-06 19:09:41.487  3187  3276 I bt_vendor: try to set false
,09-06 19:09:41.487  3187  3276 I bt_vendor: Starting hciattach daemon
09-06 19:09:41.487  3187  3276 I bt_vendor: try to set false
,09-06 19:09:41.487  3187  3276 I bt_vendor: cleanup
09-06 19:09:41.487  3187  3296 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-06 19:09:41.487  3187  3276 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:09:41.487  3187  3276 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:09:41.487  6912  6912 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:41.487  6912  6912 D ActivityThread: Added TimaKeyStore provider,
09-06 19:09:41.487  3187  3273 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:09:41.487  3187  3273 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:09:41.487  3187  3273 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-06 19:09:41.487  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:09:41.487  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:09:41.497  3187  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 19:09:41.497  1015  4387 I art     : Explicit concurrent mark sweep GC freed 40033(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 4.937ms total 232.585ms
,09-06 19:09:41.497  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.497  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.497  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.497  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.497  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:41.507  3187  3187 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:09:41.507  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:09:41.507  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:41.507  3187  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:41.507  3187  3187 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:09:41.507  3187  3187 D BtGatt.GattService: stop()
09-06 19:09:41.507  3187  3187 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 19:09:41.507  1015  1532 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.507  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.517  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.517  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.517  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:41.517  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:09:41.517  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:41.517  3187  3187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:41.517  3187  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:41.517  3187  3187 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:09:41.517  1015  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:41.517  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.527  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.527  1015  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.527  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:41.527  1015  1488 I ActivityManager: Killing 6423:com.samsung.helphub/1000 (adj 15): empty #21
,09-06 19:09:41.527  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:09:41.527  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:09:41.527  3187  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:09:41.527  3187  3187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
09-06 19:09:41.537  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.537  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.537  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.537  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.537  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:41.537  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:09:41.537  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:41.537  3187  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:09:41.537  1015  4382 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.537  1015  4382 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.537  1015  4382 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-06 19:09:41.537  1015  4382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.537  1015  4382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:41.537  3063  3063 D HeadsetProfile: Bluetooth service disconnected
09-06 19:09:41.537  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-06 19:09:41.537  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 19:09:41.537  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:41.537  3187  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:09:41.547  1348  1348 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-06 19:09:41.547  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:41.547  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:09:41.547  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:09:41.547  1015  5159 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.547  1015  5159 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.547  1015  5159 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.547  1015  5159 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.547  1015  5159 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:41.547  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:09:41.547  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:41.547  3187  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:41.547  1015  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.547  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.547  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.547  1015  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.547  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:41.547  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:09:41.557  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:09:41.557  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:41.557  3187  3273 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:09:41.557  1015  1313 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.557  1015  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.557  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.557  1015  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.557  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:41.557  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:41.557  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:41.557  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.557  3187  3273 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:41.557  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:41.557  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:41.557  3187  3273 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:41.557  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:41.557  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:41.557  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:09:41.557  3187  3273 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:09:41.557  3187  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:09:41.557  3187  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:41.557  3187  3273 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:09:41.557  3187  3273 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:09:41.557  3187  3187 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-06 19:09:41.557  3187  3187 D A2dpService: Received stop request...Stopping profile...
09-06 19:09:41.557  3187  3288 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:09:41.567  3187  3187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:41.567  1015  1015 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:41.567  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:09:41.567  3187  3187 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 19:09:41.567  3187  3187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:41.567  3187  3187 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:09:41.567  1348  1348 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-06 19:09:41.567  1348  1348 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 19:09:41.567  1348  1348 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 19:09:41.567  1348  1348 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 19:09:41.567  1348  1348 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:09:41.567  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.567  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:41.567  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.567  3063  3063 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:41.567  3063  3063 D A2dpProfile: Bluetooth service disconnected
09-06 19:09:41.567  1015  1128 D Tethering: InitialState.processMessage what=4
,09-06 19:09:41.577  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.577  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.577  3187  3187 D HidService: Received stop request...Stopping profile...
09-06 19:09:41.577  3187  3187 D HidService: Stopping Bluetooth HidService
09-06 19:09:41.577  3187  3187 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:09:41.577  3187  3187 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 19:09:41.577  3187  3187 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:09:41.577  3187  3187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:41.577  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.577  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:41.577  1015  1128 E Tethering: No numeric data
,09-06 19:09:41.577  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:09:41.577  1015  1128 D Tethering: clearTetheredNotification()
09-06 19:09:41.577  3063  3063 D BluetoothInputDevice: Proxy object disconnected
09-06 19:09:41.577  3063  3063 D HidProfile: Bluetooth service disconnected
09-06 19:09:41.577  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.577  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:09:41.577  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:41.577  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:09:41.577  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.577  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.577  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:41.577  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.577  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:41.577  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:09:41.577  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.587  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:09:41.587  1177  1177 D HotspotTile: updateTetherState():false, false
,09-06 19:09:41.587  1015  1121 V NetworkStats: performPollLocked() took 5ms
09-06 19:09:41.587  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.587  3187  3187 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:09:41.587  3187  3187 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:09:41.587  3187  3187 D HealthService: Received stop request...Stopping profile...
09-06 19:09:41.587  3187  3187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:41.587  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.587  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.587  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.587  3187  3187 D PanService: Received stop request...Stopping profile...
09-06 19:09:41.587  3187  3187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
09-06 19:09:41.587  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.587  3063  3063 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:09:41.587  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:09:41.587  3187  3187 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 19:09:41.587  3063  3063 D PanProfile: Bluetooth service disconnected
,09-06 19:09:41.587  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.597  3187  3187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:41.597  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.597  3063  3063 D BluetoothMap: Proxy object disconnected
09-06 19:09:41.597  3063  3063 D MapProfile: Bluetooth service disconnected
09-06 19:09:41.597  3187  3187 D SapService: Received stop request...Stopping profile...
09-06 19:09:41.597  3187  3187 D SapService: Stopping Bluetooth SapService
09-06 19:09:41.597  3187  3187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
09-06 19:09:41.597  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.597  3187  3187 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 19:09:41.597  3187  3187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:41.597  3187  3187 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:09:41.597  3187  3187 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:41.597  3187  3187 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-06 19:09:41.597  3187  3289 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:09:41.597  3187  3187 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:09:41.597  3187  3187 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:09:41.597  3063  3063 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:09:41.597  3063  3063 D SapProfile: Bluetooth service disconnected
,09-06 19:09:41.597  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.597  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.597  3187  3187 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 19:09:41.597  3187  3187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:41.597  3187  3187 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:41.607  3187  3187 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 19:09:41.607  3187  3187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:41.607  3187  3187 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:41.607  3187  3187 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:09:41.607  3187  3187 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:09:41.607  3187  3187 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 19:09:41.607  3187  3187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:41.607  3187  3187 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:41.607  3187  3187 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:09:41.607  3187  3187 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:09:41.607  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.607  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:09:41.607  3187  3187 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-06 19:09:41.607  3187  3187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:41.607  3187  3187 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-06 19:09:41.607  3187  3187 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-06 19:09:41.607  3187  3187 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:09:41.607  3187  3187 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-06 19:09:41.607  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.607  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:09:41.607  3187  3273 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:09:41.607  3187  3273 D BluetoothAdapterProperties: Setting state to 10
09-06 19:09:41.607  3187  3273 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:09:41.607  3187  3273 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:41.607  3187  3273 D BluetoothAdapterService: updateAdapterState state is 10
,09-06 19:09:41.607  3187  3273 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:41.607  3187  3273 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 19:09:41.607  3187  3273 I BluetoothAdapterState: Entering OffState
09-06 19:09:41.607  3187  3285 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.607  3187  3285 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:41.607  3063  3071 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.607  3063  3071 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.607  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.607  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.617  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.617  1468  1832 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.617  1468  1832 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:41.617  3063  3072 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:41.617  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.617  3063  3071 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:09:41.617  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.617  3063  3072 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:09:41.617  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.627  3063  3071 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:09:41.627  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.627  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.627  6750  6759 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:41.627  6750  6759 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.627   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb714d7c8
09-06 19:09:41.627   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-06 19:09:41.627  6750  6759 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-06 19:09:41.627   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-06 19:09:41.627   272   339 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1223371464)
,09-06 19:09:41.627  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.627  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:09:41.627  6750  6759 D BluetoothLeAdvertiser: Exit stop advertising
09-06 19:09:41.627  6750  6759 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 19:09:41.627  6750  6759 D BluetoothLeScanner: Exiting stopAllScan
09-06 19:09:41.627  3187  3202 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:09:41.627  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.627  1177  3879 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:41.627  1177  3879 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.637  3063  3071 D Bluetoothsap: onBluetoothStateChange: up=false
09-06 19:09:41.637  3063  3071 D Bluetoothsap: Unbinding service...
09-06 19:09:41.637  1455  1485 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.637  1455  1485 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.637  1445  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.637  1445  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
09-06 19:09:41.637  1980  1996 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.637  1980  1996 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.637  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:09:41.637  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.637  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.637  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-06 19:09:41.647  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:09:41.657  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:41.657  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-06 19:09:41.657  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:09:41.657  1177  1177 D BluetoothAdapter: 713492178: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:41.657  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:09:41.657  1177  1662 D BluetoothAdapter: 713492178: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:41.657  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:41.657  1177  1177 D BluetoothTile:  getBluetoothState : 10
,09-06 19:09:41.657  1177  1662 D BluetoothAdapter: 713492178: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:41.657  1177  1177 D BluetoothAdapter: 713492178: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:41.657  1177  1177 D BluetoothAdapter: 713492178: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:41.657  1015  1313 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:41.667  1015  1718 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:41.667  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:41.667  1980  2155 D BluetoothAdapter: 993648318: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:41.667  1963  1963 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:09:41.667  1980  2155 D BluetoothAdapter: 993648318: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:41.667  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:41.667  1015  4387 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:41.667  1015  4387 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.677  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.677  1015  4387 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.677  1015  4387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:41.677  1015  4387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:41.677  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.677  3187  3276 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 19:09:41.677  3187  3187 I GKI_LINUX: GKI_exit_task 1 done
,09-06 19:09:41.677  3187  3187 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-06 19:09:41.677   272   339 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
,09-06 19:09:41.677   272   339 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-06 19:09:41.677   272   339 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1223371464) wakelock released: 1, error no: 0
09-06 19:09:41.677   272   339 I rmt_storage: 
09-06 19:09:41.687  3187  3187 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 19:09:41.687   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb714d7c8
,09-06 19:09:41.697  3187  3187 I art     : System.exit called, status: 0
09-06 19:09:41.697  3187  3187 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:09:41.697   256   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:09:41.697   256   527 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:41.707  6912  6949 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:09:41.707   256   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:09:41.707   256   527 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:41.707  6912  6949 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:09:41.717  1348  1348 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:09:41.747  1015  4382 I ActivityManager: Process com.android.bluetooth (pid 3187)(adj 0) has died(31,713)
,09-06 19:09:41.777  1348  1348 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-06 19:09:41.787  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:09:41.787  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:41.787  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:41.837  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:41.837  1015  1015 I ApplicationPolicy: updateDataUsageMap
,09-06 19:09:41.837  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:09:41.847  6912  6912 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.847  6912  6912 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:41.847  6912  6912 D StrictMode:, 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.847  6912  6912 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.847  6912  6912 D StrictMod,e: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.847  6912  6912 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.847  6912  6912 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.k.d(PG:583)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.847  6912  6912 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.847  6912  6912 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.847  6912  6912 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.847  6912  6912 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.857  1015  1313 I ActivityManager: Killing 6456:com.google.android.apps.plus/u0a117 (adj 15): empty #21
09-06 19:09:41.857  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:41.857  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:41.857  1980  1980 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 19:09:41.867  1980  1980 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-06 19:09:41.877  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:41.877  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:41.877  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.877  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.877  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:09:41.877  1602  1602 I Hs20UtilService: Starting #8
09-06 19:09:41.877  1602  1637 I Hs20UtilService: Message received 5007
,09-06 19:09:41.877  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:09:41.887  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-06 19:09:41.887  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-06 19:09:41.897  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.897  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:41.897  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.897  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.897  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.897  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.897  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:41.897  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-06 19:09:41.897  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:09:41.897  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:41.897  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:09:41.897  1980  2155 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:09:41.897  1177  1177 D HotspotTile: onReceive : 1, 0
09-06 19:09:41.907  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:41.907  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:09:41.907  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:41.907  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:41.907  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:41.907  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:09:41.907  3063  3880 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 19:09:41.907  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:41.917  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:09:41.917  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:09:41.917  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:09:41.917  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:41.917  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:41.917  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:09:41.917  3063  3880 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:41.917  1015  1531 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-06 19:09:41.917  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.917  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.917  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.917  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.927  6912  6960 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:09:41.937  6965  6965 E Zygote  : MountEmulatedStorage(),
09-06 19:09:41.937  6965  6965 E Zygote  : v2
09-06 19:09:41.937  6965  6965 I libpersona: KNOX_SDCARD checking this for 10064
09-06 19:09:41.937  6965  6965 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:41.937  6965  6965 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:41.937  1015  1531 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6965 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:41.937  6965  6965 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:41.937  6965  6965 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:41.957  1015  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:41.967  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.967  1015  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:41.967  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-06 19:09:41.967  6965  6965 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:41.967  6965  6965 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:41.977  6965  6965 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 19:09:41.987  6965  6965 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:41.997  6965  6965 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:09:42.017  6965  6965 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:09:42.017  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-06 19:09:42.027  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.027  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.027  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.027  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.037  6982  6982 E Zygote  : MountEmulatedStorage(),
09-06 19:09:42.037  6982  6982 I libpersona: KNOX_SDCARD checking this for 10065
09-06 19:09:42.037  6982  6982 E Zygote  : v2
09-06 19:09:42.037  6982  6982 I libpersona: KNOX_SDCARD not a persona,
09-06 19:09:42.037  6982  6982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:42.037  1015  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6982 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:42.037  6982  6982 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:42.037  6982  6982 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:42.037  1015  1027 I ActivityManager: Killing 6484:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-06 19:09:42.057  6982  6982 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.057  6982  6982 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.087  6982  6982 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:42.097  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.097  1015  1718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:42.097  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-06 19:09:42.097  1015  1718 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-06 19:09:42.097  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.097  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.097  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.097  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.107  6998  6998 E Zygote  : MountEmulatedStorage()
09-06 19:09:42.107  6998  6998 E Zygote  : v2
,09-06 19:09:42.107  6998  6998 I libpersona: KNOX_SDCARD checking this for 10102
09-06 19:09:42.107  6998  6998 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:42.107  1015  1718 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6998 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-06 19:09:42.117  6998  6998 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:42.117  6998  6998 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:42.117  1015  1718 I ActivityManager: Killing 6535:com.samsung.android.sm/1000 (adj 15): empty #21
,09-06 19:09:42.117  6998  6998 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.137  6998  6998 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.137  6998  6998 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.157  6998  6998 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:09:42.237   287   287 E SMD     : DCD OFF
,09-06 19:09:42.247   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:42.297  1980  2165 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-06 19:09:42.297  1980  2165 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,09-06 19:09:42.357  6998  7018 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-06 19:09:42.357  6998  7018 I Babel_SMS: MmsConfig.loadMmsSettings
,09-06 19:09:42.367  6998  7018 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-06 19:09:42.367  6998  7018 I Babel_SMS: MmsConfig.loadFromDatabase
,09-06 19:09:42.387  6998  7018 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-06 19:09:42.387  6998  7018 I Babel_SMS: MmsConfig.loadFromResources
,09-06 19:09:42.397  6998  7018 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-06 19:09:42.397  6998  7018 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-06 19:09:42.437  1015  4386 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-06 19:09:42.437  1015  4386 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-06 19:09:42.437  1015  4386 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.437  1015  4386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:42.437  1015  4386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:09:42.447  1015  1042 D Tethering: interfaceRemoved wlan0
,09-06 19:09:42.447  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:09:42.467  6998  6998 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:09:42.467  6998  6998 I Babel_Crash: startup - clean
,09-06 19:09:42.487  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.487  1015  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.487  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.497  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.497  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.497  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.497  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.497  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.497  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.507  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.507  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.507  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.507  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.507  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.507  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.507  6998  6998 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:09:42.507  6998  6998 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:09:42.507  6998  6998 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:09:42.517  1015  1532 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:42.517  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:42.517  6998  6998 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-06 19:09:42.517  6998  6998 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-06 19:09:42.517  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.517  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:42.517  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:42.517  1602  1602 I Hs20UtilService: Starting #9
09-06 19:09:42.517  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:09:42.517  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:09:42.527  1602  1637 I Hs20UtilService: Message received 5007
,09-06 19:09:42.527  6998  6998 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-06 19:09:42.527  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:42.527  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:42.527  6998  6998 W AudioCapabilities: Unsupported mime audio/x-ima
,09-06 19:09:42.527  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:42.527  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:42.527  3063  3880 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 19:09:42.527  6998  6998 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:09:42.527  6998  6998 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:09:42.527  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.537  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.537  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.537  1015  1718 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:42.537  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:42.537  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.537  1015  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.537  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:42.547  1602  1602 I Hs20UtilService: Starting #10
,09-06 19:09:42.547  1602  1637 I Hs20UtilService: Message received 5011
,09-06 19:09:42.547  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:09:42.547  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:42.547  6551  6551 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:09:42.547  6998  6998 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:09:42.547  6551  6551 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:42.547  6998  6998 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:09:42.557  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.557  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.557  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.557  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.557  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.557  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,09-06 19:09:42.557  1015  1042 D Tethering: interfaceRemoved p2p0
09-06 19:09:42.557  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:09:42.557  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.557  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.557  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.567  6998  6998 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-06 19:09:42.567  6998  6998 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:09:42.567  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.567  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.567  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.567  6998  6998 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:09:42.567  6998  6998 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-06 19:09:42.567  6998  6998 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-06 19:09:42.567  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.567  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:42.567  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.577  6998  6998 W VideoCapabilities: Unsupported mime video/mp43
,09-06 19:09:42.577  6998  6998 W VideoCapabilities: Unsupported mime video/sorenson
,09-06 19:09:42.577  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.577  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.577  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.577  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.587  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.587  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.587  6998  6998 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 19:09:42.587  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.587  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.587  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.587  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.587  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.587  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.597  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:42.597  1015  1313 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:09:42.597  1015  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:42.597  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.597  1015  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.597  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:42.607  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:42.607  6998  6998 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 19:09:42.607  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:42.617  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:42.617  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 19:09:42.617  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-06 19:09:42.617  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.617  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.617  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.617  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.637  7022  7022 E Zygote  : MountEmulatedStorage(),
09-06 19:09:42.637  7022  7022 E Zygote  : v2
09-06 19:09:42.637  7022  7022 I libpersona: KNOX_SDCARD checking this for 1002
09-06 19:09:42.637  7022  7022 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:42.637  7022  7022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:42.637  1015  1028 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7022 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-06 19:09:42.637  7022  7022 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:42.637  7022  7022 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:09:42.647  6998  6998 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:09:42.647  6998  6998 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:09:42.657  6998  6998 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:09:42.657  6998  6998 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:09:42.657  1015  5159 I ActivityManager: Killing 6515:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-06 19:09:42.657  6998  6998 I vclib   : onServiceConnected
,09-06 19:09:42.667  7022  7022 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.667  7022  7022 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.677  7022  7022 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 19:09:42.677  7022  7022 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:09:42.707  7022  7022 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding GattService
,09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding HeadsetService
09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding A2dpService
09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding HidService
09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding HealthService
,09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding PanService
09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding SapService
09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding SapClientService
09-06 19:09:42.737  7022  7022 D BtSettings.ProfileConfig: Adding HidDevService
09-06 19:09:42.737  7022  7022 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 19:09:42.737  1015  1518 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 19:09:42.737  1015  1518 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:42.737  1015  1518 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:42.737  1015  1518 D SettingsProvider: selectionArgs: false
,09-06 19:09:42.737  1015  1518 D SettingsProvider: selectionArgs: 1002
09-06 19:09:42.737  1015  1518 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:42.737  1015  1518 D SettingsProvider: ret = -1
,09-06 19:09:42.737  1015  1502 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-06 19:09:42.737  1015  1502 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:42.737  1015  1502 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:42.737  1015  1502 D SettingsProvider: selectionArgs: false
09-06 19:09:42.737  1015  1502 D SettingsProvider: selectionArgs: 1002
09-06 19:09:42.737  1015  1502 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:42.737  1015  1502 D SettingsProvider: ret = -1
09-06 19:09:42.737  1015  4387 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:42.737  1015  4387 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:42.737  1015  4387 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:42.737  1015  4387 D SettingsProvider: selectionArgs: false
09-06 19:09:42.737  1015  4387 D SettingsProvider: selectionArgs: 1002
09-06 19:09:42.737  1015  4387 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:42.737  1015  4387 D SettingsProvider: ret = -1
,09-06 19:09:42.747  1015  4382 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-06 19:09:42.747  1015  4382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:42.747  1015  4382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:42.747  1015  4382 D SettingsProvider: selectionArgs: false
09-06 19:09:42.747  1015  4382 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:42.747  1015  4382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:42.747  1015  4382 D SettingsProvider: ret = -1
,09-06 19:09:42.747  1015  1486 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-06 19:09:42.747  1015  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:09:42.747  1015  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:42.747  1015  1486 D SettingsProvider: selectionArgs: false
09-06 19:09:42.747  1015  1486 D SettingsProvider: selectionArgs: 1002
09-06 19:09:42.747  1015  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:42.747  1015  1486 D SettingsProvider: ret = -1
,09-06 19:09:42.747  1015  1718 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-06 19:09:42.747  1015  1718 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:42.747  1015  1718 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:42.747  1015  1718 D SettingsProvider: selectionArgs: false
09-06 19:09:42.747  1015  1718 D SettingsProvider: selectionArgs: 1002
09-06 19:09:42.747  1015  1718 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:42.747  1015  1718 D SettingsProvider: ret = -1
,09-06 19:09:42.747  1015  1531 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 19:09:42.747  1015  1531 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:42.747  1015  1531 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:42.747  1015  1531 D SettingsProvider: selectionArgs: false
09-06 19:09:42.747  1015  1531 D SettingsProvider: selectionArgs: 1002
09-06 19:09:42.747  1015  1531 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:42.747  1015  1531 D SettingsProvider: ret = -1
,09-06 19:09:42.747  1015  5159 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
09-06 19:09:42.747  1015  5159 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:42.747  1015  5159 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:42.747  1015  5159 D SettingsProvider: selectionArgs: false,
09-06 19:09:42.747  1015  5159 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:42.747  1015  5159 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:42.747  1015  5159 D SettingsProvider: ret = -1
09-06 19:09:42.747  1015  1313 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:42.747  1015  1313 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:42.747  1015  1313 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:42.747  1015  1313 D SettingsProvider: selectionArgs: false
,09-06 19:09:42.747  1015  1313 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:42.747  1015  1313 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:42.747  1015  1313 D SettingsProvider: ret = -1
09-06 19:09:42.757  1015  1518 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:42.757  1015  1518 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:42.757  1015  1518 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:42.757  1015  1518 D SettingsProvider: selectionArgs: false
09-06 19:09:42.757  1015  1518 D SettingsProvider: selectionArgs: 1002
09-06 19:09:42.757  1015  1518 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:42.757  1015  1518 D SettingsProvider: ret = -1
09-06 19:09:42.757  1015  1502 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 19:09:42.757  1015  1502 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-06 19:09:42.757  1015  1502 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:42.757  1015  1502 D SettingsProvider: selectionArgs: false
09-06 19:09:42.757  1015  1502 D SettingsProvider: selectionArgs: 1002
09-06 19:09:42.757  1015  1502 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:42.757  1015  1502 D SettingsProvider: ret = -1
09-06 19:09:42.757  1015  4387 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-06 19:09:42.757  1015  4387 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:09:42.757  1015  4387 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:42.757  1015  4387 D SettingsProvider: selectionArgs: false
09-06 19:09:42.757  1015  4387 D SettingsProvider: selectionArgs: 1002
09-06 19:09:42.757  1015  4387 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:42.757  1015  4387 D SettingsProvider: ret = -1
,09-06 19:09:42.767  1015  4382 I ActivityManager: Killing 6585:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-06 19:09:42.767  1980  1980 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:42.767  1015  4386 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:42.767  1015  4386 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:09:42.767  1015  4386 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.767  1015  4386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:42.767  1015  4386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:42.777  1980  7038 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:09:42.777  1980  1980 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:42.777  1015  4382 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 19:09:42.777  1015  4382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.777  1015  4382 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.777  1015  4382 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.777  1015  4382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.787  7039  7039 E Zygote  : MountEmulatedStorage(),
09-06 19:09:42.787  7039  7039 E Zygote  : v2
09-06 19:09:42.787  7039  7039 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:09:42.787  7039  7039 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:42.797  7039  7039 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:42.797  7039  7039 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:42.797  7039  7039 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-06 19:09:42.797  1015  4382 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7039 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:09:42.797  1015  4386 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:42.807  1015  4386 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:42.807  1015  4386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:42.807  1015  4386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:42.817  1015  1531 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:42.817  1015  1531 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.817  1015  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:42.817  1015  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:42.827  7039  7039 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.837  7039  7039 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.837  1980  7038 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-06 19:09:42.857  7039  7039 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-06 19:09:42.857  7039  7039 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-06 19:09:42.857  7039  7039 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-06 19:09:42.867  7039  7039 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-06 19:09:42.867  7039  7039 I PCWCLIENTTRACE_PushUtil: sales region : global
09-06 19:09:42.867  7039  7039 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-06 19:09:42.867  7039  7039 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:42.877  1015  1313 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
09-06 19:09:42.877  1015  1313 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-06 19:09:42.877  7039  7054 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-06 19:09:42.877  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-06 19:09:42.877  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.877  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.877  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.877  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.897  7056  7056 E Zygote  : MountEmulatedStorage()
09-06 19:09:42.897  7056  7056 I libpersona: KNOX_SDCARD checking this for 10001
09-06 19:09:42.897  7056  7056 E Zygote  : v2
09-06 19:09:42.897  7056  7056 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:42.897  7056  7056 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:42.897  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7056 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:42.897  7056  7056 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:42.897  7056  7056 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.907  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-06 19:09:42.907  1801  1801 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:09:42.907  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.907  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.907  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.907  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.917  7056  7056 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.917  7056  7056 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.927   308   308 I art     : Explicit concurrent mark sweep GC freed 8705(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 28.990ms
,09-06 19:09:42.937   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 569us total 16.116ms
,09-06 19:09:42.957   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 569us total 16.346ms
,09-06 19:09:42.967  7071  7071 E Zygote  : MountEmulatedStorage(),
09-06 19:09:42.967  7071  7071 E Zygote  : v2
,09-06 19:09:42.967  7071  7071 I libpersona: KNOX_SDCARD checking this for 10121
09-06 19:09:42.967  7071  7071 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:42.967  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7071 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-06 19:09:42.967  1015  1718 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
09-06 19:09:42.967  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:09:42.967  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.967  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.967  1015  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.977  7071  7071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:42.987  7071  7071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:42.987  7077  7077 E Zygote  : MountEmulatedStorage()
09-06 19:09:42.987  7077  7077 I libpersona: KNOX_SDCARD checking this for 10031
09-06 19:09:42.987  7077  7077 E Zygote  : v2
09-06 19:09:42.987  7077  7077 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:42.987  7071  7071 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:42.987  1015  1718 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7077 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
09-06 19:09:42.987  7077  7077 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:42.987  7077  7077 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:42.987  7077  7077 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.997  2469  2761 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,09-06 19:09:42.997  1801  1801 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-06 19:09:43.007  1801  1801 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-06 19:09:43.007  1801  1801 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-06 19:09:43.007  1801  1801 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-06 19:09:43.007  1801  1801 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:09:43.017  1801  1801 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-06 19:09:43.017  1015  1531 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
09-06 19:09:43.017  7071  7071 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.017  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.017  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.017  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.017  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.017  7071  7071 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.017  7077  7077 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.027  7077  7077 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.037  7101  7101 E Zygote  : MountEmulatedStorage()
09-06 19:09:43.037  7101  7101 E Zygote  : v2
09-06 19:09:43.037  7101  7101 I libpersona: KNOX_SDCARD checking this for 10077
09-06 19:09:43.037  7101  7101 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.037  1015  1531 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7101 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:43.037  7101  7101 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:43.037  7101  7101 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:43.047  7101  7101 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.057  7071  7071 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:09:43.057  7071  7071 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 19:09:43.057  7071  7071 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:09:43.067  7101  7101 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.067  7101  7101 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.077  7077  7077 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
09-06 19:09:43.077  7071  7071 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:43.077  1015  1488 I ActivityManager: Killing 6596:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-06 19:09:43.087  7071  7071 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-06 19:09:43.087  7071  7071 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-06 19:09:43.087  1015  1518 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-06 19:09:43.097  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.097  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.097  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.097  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.107  7118  7118 E Zygote  : MountEmulatedStorage(),
09-06 19:09:43.107  7118  7118 E Zygote  : v2
09-06 19:09:43.107  7118  7118 I libpersona: KNOX_SDCARD checking this for 10141,
09-06 19:09:43.107  7118  7118 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.117  7118  7118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:43.117  7118  7118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:43.117  1015  1518 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7118 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
09-06 19:09:43.117  7118  7118 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:43.117  1015  1518 I ActivityManager: Killing 6611:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-06 19:09:43.117  1015  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
09-06 19:09:43.127  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.127  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.127  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.127  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.127  2753  7125 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-06 19:09:43.137  2753  7125 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-06 19:09:43.137  7118  7118 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:43.137  7133  7133 E Zygote  : MountEmulatedStorage()
09-06 19:09:43.137  7133  7133 I libpersona: KNOX_SDCARD checking this for 10032
09-06 19:09:43.137  7133  7133 E Zygote  : v2
09-06 19:09:43.137  7133  7133 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.137  7133  7133 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:43.137  2753  7125 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-06 19:09:43.137  1015  1488 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7133 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:43.137  7133  7133 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:43.137  2753  7125 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
09-06 19:09:43.147  7133  7133 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-06 19:09:43.147  7118  7118 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:43.147  2753  7125 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-06 19:09:43.147  1015  1486 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-06 19:09:43.147  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.147  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.147  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.147  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.167  7147  7147 E Zygote  : MountEmulatedStorage(),
09-06 19:09:43.167  7147  7147 E Zygote  : v2
09-06 19:09:43.167  7147  7147 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:09:43.167  7147  7147 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.167  7147  7147 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:43.167  1015  1486 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7147 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:09:43.167  1015  1486 I ActivityManager: Killing 6631:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-06 19:09:43.167  7147  7147 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:43.167  7147  7147 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.197  7133  7133 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.197  7133  7133 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.197  7147  7147 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.197  7147  7147 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.207  7118  7118 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-06 19:09:43.207  7118  7118 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:09:43.207  7118  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:09:43.207  7118  7118 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-06 19:09:43.257   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:43.257  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 19:09:43.277  1015  4382 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:43.287  7147  7147 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-06 19:09:43.287  1015  1486 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:43.297  7133  7166 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-06 19:09:43.297  7133  7166 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-06 19:09:43.307  7133  7133 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-06 19:09:43.307  1015  1502 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-06 19:09:43.307  7133  7166 D SPPClientService: PushLog.txt file is not deleted.
09-06 19:09:43.307  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.307  7133  7166 D SPPClientService: PushLog.txt file is not deleted.
09-06 19:09:43.307  7133  7166 D SPPClientService: ============PushLog. stop!
,09-06 19:09:43.307  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.307  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.307  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.327  7170  7170 E Zygote  : MountEmulatedStorage()
,09-06 19:09:43.327  7170  7170 E Zygote  : v2
09-06 19:09:43.327  7170  7170 I libpersona: KNOX_SDCARD checking this for 10036
09-06 19:09:43.327  7170  7170 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.327  7170  7170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:43.327  7170  7170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:43.327  7170  7170 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.327  1015  1502 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7170 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:43.337  1015  1502 I ActivityManager: Killing 6565:com.android.providers.calendar/u0a37 (adj 15): empty #21
09-06 19:09:43.337  1015  1531 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-06 19:09:43.337  1015  1531 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-06 19:09:43.337  1015  1531 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.337  1015  1531 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-06 19:09:43.337  1015  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-06 19:09:43.347  1015  4382 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-06 19:09:43.347  1015  1718 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-06 19:09:43.347  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.347  1015  4382 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:09:43.347  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.347  1015  4382 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:09:43.347  1015  1718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.347  1015  4382 D BatteryService: stay LED for fully charged
09-06 19:09:43.347  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
09-06 19:09:43.347  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:09:43.347  1015  1718 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:43.357  1015  1015 I MotionRecognitionService: Plugged
09-06 19:09:43.357  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:09:43.357  7170  7170 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.357  7170  7170 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.367  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:09:43.367  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:09:43.367  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:09:43.367  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,09-06 19:09:43.377  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:09:43.377  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:09:43.377  1015  1502 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
09-06 19:09:43.387  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.387  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.387  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.387  1015  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.397  7133  7180 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-06 19:09:43.407  7190  7190 E Zygote  : MountEmulatedStorage()
,09-06 19:09:43.407  7190  7190 E Zygote  : v2
09-06 19:09:43.407  7190  7190 I libpersona: KNOX_SDCARD checking this for 10110
09-06 19:09:43.407  7190  7190 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.407  1015  1502 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7190 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:43.407  7190  7190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-06 19:09:43.407  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:09:43.407  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-06 19:09:43.407  1177  1177 D SViewCoverView: level :100 plugged : 2
09-06 19:09:43.407  1015  4387 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-06 19:09:43.407  1015  4387 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.417  1015  4387 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.417  1015  4387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.417  1015  4387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
09-06 19:09:43.417  1015  5159 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:43.417  7190  7190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:43.417  6998  7188 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
09-06 19:09:43.417  7190  7190 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.427  1015  4387 I ActivityManager: Killing 6067:com.android.mms/u0a41 (adj 15): empty #21
,09-06 19:09:43.437  7190  7190 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.437  7190  7190 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.457  7147  7147 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-06 19:09:43.467  7147  7147 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-06 19:09:43.477  7147  7147 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:43.477  7147  7147 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-06 19:09:43.477  7147  7147 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-06 19:09:43.477  7147  7147 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-06 19:09:43.477  1015  4382 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-06 19:09:43.477  1015  4382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.477  1015  4382 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.477  1015  4382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.477  1015  4382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.477  7170  7170 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1aa3dae8
,09-06 19:09:43.497  7170  7170 I SA      : [SSP] onCreated,
09-06 19:09:43.497  7207  7207 E Zygote  : MountEmulatedStorage()
09-06 19:09:43.497  7207  7207 I libpersona: KNOX_SDCARD checking this for 10008
09-06 19:09:43.497  7207  7207 E Zygote  : v2
09-06 19:09:43.497  7207  7207 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.497  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:43.497  1015  1137 D CountryDetector: No listener is left
,09-06 19:09:43.497  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 19:09:43.497  1015  4382 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7207 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:43.497  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-06 19:09:43.497  1015  4382 I ActivityManager: Killing 6657:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-06 19:09:43.517  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.517  7207  7207 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.517  7170  7170 I SA      : [TPM] There is no property file
,09-06 19:09:43.527  7170  7170 I SA      : [SCU] isHaveSA() - false
,09-06 19:09:43.527  7170  7170 I SA      : [TPM] getModelProperty : null
09-06 19:09:43.527  7170  7170 I SA      : [TPM] getCSCProperty : null
,09-06 19:09:43.527  7170  7170 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-06 19:09:43.527  7170  7170 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-06 19:09:43.527  7170  7170 I SA      : [DM] TFT FEATURE: false
,09-06 19:09:43.527  1015  1531 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-06 19:09:43.537  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.537  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.537  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.537  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.537  7170  7170 I SA      : [DM] init START
,09-06 19:09:43.547  1015  4382 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:43.547  7228  7228 E Zygote  : MountEmulatedStorage()
,09-06 19:09:43.547  7228  7228 E Zygote  : v2
09-06 19:09:43.547  7228  7228 I libpersona: KNOX_SDCARD checking this for 10068
09-06 19:09:43.547  7228  7228 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:43.547  7228  7228 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:43.547  1015  1531 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7228 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-06 19:09:43.547  7228  7228 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:43.547  7228  7228 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-06 19:09:43.547  7170  7170 I SA      : [DM] This device is not a Vodafone
,09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
09-06 19:09:43.567  7170  7170 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-06 19:09:43.577  7170  7170 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-06 19:09:43.577  7228  7228 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:43.577  7170  7170 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-06 19:09:43.577  7228  7228 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:43.577  7170  7170 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-06 19:09:43.577  7170  7170 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-06 19:09:43.577  7170  7170 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-06 19:09:43.577  7170  7170 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-06 19:09:43.577  7170  7170 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-06 19:09:43.577  7170  7170 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-06 19:09:43.587  1015  1718 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:43.587  7170  7170 I SA      : [SCU] isHaveSA() - false
09-06 19:09:43.587  7170  7170 I SA      : support phone number id : false
09-06 19:09:43.587  7170  7170 I SA      : [DM] Supports Ref Jpn : true
,09-06 19:09:43.587  7170  7170 I SA      : [DM] init END
09-06 19:09:43.587  7170  7170 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-06 19:09:43.587  7170  7170 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-06 19:09:43.587  7170  7170 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-06 19:09:43.597  1015  1028 I ActivityManager: Killing 6677:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-06 19:09:43.607  2907  2907 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 19:09:43 GMT+02:00 2016
,09-06 19:09:43.607  1015  1137 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:09:43.607  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.607  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.607  1015  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:43.607  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 19:09:43.607  2907  2907 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-06 19:09:43.607  7228  7228 D BadgeProvider: onCreate
09-06 19:09:43.607  7228  7228 D BadgeProvider: DatabaseHelper
,09-06 19:09:43.627  2907  2907 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-06 19:09:43.627  2907  2907 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 19:09:43.627  7228  7236 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-06 19:09:43.637  2907  2907 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 19:09:43.637  7170  7170 I SA      : [SLFUCHKMGR] constructor called
,09-06 19:09:43.647  2907  7245 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 19:09:43.647  7228  7238 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-06 19:09:43.647  7228  7238 D BadgeProvider: sendNotify, [notify] : null
09-06 19:09:43.647  7228  7238 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-06 19:09:43.647  7228  7238 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-06 19:09:43.647  7228  7238 D BadgeProvider: update, [UpdateCount] : 1
,09-06 19:09:43.647  2907  7245 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-06 19:09:43.647  1495  1495 D Launcher.Model: reloadBadges entered.
,09-06 19:09:43.657  1015  1502 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:43.657  2907  7245 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-06 19:09:43.657  7170  7170 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-06 19:09:43.657  7170  7170 I SA      : [OR] == isSIMCardReady false ==
,09-06 19:09:43.657  2907  7245 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-06 19:09:43.667  7170  7170 I SA      : [SCU] == networkStateCheck == false
,09-06 19:09:43.667  7170  7170 I SA      : [OR] onReceive END
,09-06 19:09:43.667  1015  1028 I ActivityManager: Killing 6500:com.android.calendar/u0a131 (adj 15): empty #21
,09-06 19:09:43.677  1223  1223 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:43.677  1015  1532 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:43.677  2907  2907 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-06 19:09:43.677  1015  4387 I ActivityManager: Killing 6692:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-06 19:09:43.687  1015  4386 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-06 19:09:43.687  1015  4386 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.687  1015  4386 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.687  1015  4382 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
09-06 19:09:43.687  1015  4386 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.687  1015  4386 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.697  7247  7247 E Zygote  : MountEmulatedStorage()
09-06 19:09:43.697  7247  7247 E Zygote  : v2
09-06 19:09:43.697  7247  7247 I libpersona: KNOX_SDCARD checking this for 10009
09-06 19:09:43.697  7247  7247 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:43.697  7247  7247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:43.697  1015  4386 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7247 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,09-06 19:09:43.707  1015  4386 I ActivityManager: Killing 6028:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-06 19:09:43.707  7247  7247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:43.707  7247  7247 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.727   308   308 I art     : Explicit concurrent mark sweep GC freed 8704(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 23.789ms
,09-06 19:09:43.727  7247  7247 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.737  7247  7247 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.747   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.934ms
,09-06 19:09:43.767   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.700ms
,09-06 19:09:43.807  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-06 19:09:43.807  1015  1532 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-06 19:09:43.807  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.807  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.817  1015  1531 I ActivityManager: Killing 5829:com.android.vending/u0a26 (adj 15): empty #21
,09-06 19:09:43.827  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:43.827  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.827  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.827  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.827  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:43.837  4796  7266 I iu.SyncManager: SYNC; picasa accounts
,09-06 19:09:43.857  4796  4796 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-06 19:09:43.897   256   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 19:09:43.897   256   527 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:43.897  7190  7269 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:09:43.897   256   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:09:43.897   256   527 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:43.897  7190  7269 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
,09-06 19:09:43.917   256   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 19:09:43.917   256   527 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:43.917  7190  7270 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:09:43.927   256   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:09:43.927   256   527 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:43.927  7190  7270 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 19:09:43.937  7190  7190 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 19:09:43.937  7190  7190 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 19:09:43.937  7190  7190 I GAv4    :   adb logcat -s GAv4
,09-06 19:09:43.957  7190  7190 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:09:43.957  1015  4386 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:09:43.967  7190  7190 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:09:43.977  7190  7272 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:09:44.057  1015  1532 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:09:44.057  1015  1532 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:09:44.057  1015  1532 D SecContentProvider2: mCursor = null
,09-06 19:09:44.057  1015  1532 D WifiService: setWifiEnabled: true pid=6750, uid=10171
,09-06 19:09:44.057  1015  1532 W ActivityManager: Permission Denial: getCurrentUser() from pid=6750, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:09:44.067  1015  1532 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:09:44.067  1015  1532 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6750, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:44.067  1015  1532 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:09:44.067  1015  1532 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:09:44.067  1015  1532 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:09:44.067  1015  1532 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:09:44.067  1015  1532 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:09:44.067  1015  1532 D SettingsProvider: name = wifi_on
,09-06 19:09:44.067  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 19:09:44.227  1015  5159 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:44.227  1015  5159 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:44.227  1015  5159 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:44.227  1015  5159 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-06 19:09:44.257  7190  7190 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-06 19:09:44.257   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:44.267  7190  7190 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 7205-7208)
09-06 19:09:44.267  7190  7190 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:09:44.287  7190  7190 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e964943}
,09-06 19:09:44.287  7190  7190 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-06 19:09:44.287  7190  7190 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:09:44.307  7190  7190 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-06 19:09:44.307  7190  7190 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:09:44.317  7190  7190 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 19:09:44.327  7190  7190 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:44.327  7190  7190 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:44.327  7190  7190 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:44.327  7190  7190 I Adreno-EGL: Local Branch: 
09-06 19:09:44.327  7190  7190 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:44.327  7190  7190 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:44.327  7190  7190 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:09:44.387  7190  7190 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:09:44.397  7190  7308 W cr.media: Requires BLUETOOTH permission
,09-06 19:09:44.397  7190  7190 I NSApplication: Starting up...
,09-06 19:09:44.397  1015  1028 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:09:44.407  1015  1531 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:09:44.407  1015  1518 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-06 19:09:44.407  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:44.407  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:44.407  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:44.407  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:44.427  7313  7313 E Zygote  : MountEmulatedStorage()
,09-06 19:09:44.427  7313  7313 E Zygote  : v2
09-06 19:09:44.427  7313  7313 I libpersona: KNOX_SDCARD checking this for 10117
09-06 19:09:44.427  7313  7313 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:44.427  7313  7313 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:44.427  1015  1518 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7313 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:44.427  1015  1518 I ActivityManager: Killing 6965:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-06 19:09:44.427  7313  7313 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:44.437  1015  1042 D Tethering: interfaceAdded wlan0
09-06 19:09:44.437  7313  7313 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:44.447  1015  1128 E Tethering: No numeric data,
09-06 19:09:44.447  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:44.447  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
09-06 19:09:44.447  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:09:44.447  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:44.447  1015  1128 D Tethering: clearTetheredNotification()
,09-06 19:09:44.447  1015  1128 D Tethering: InitialState.processMessage what=4
09-06 19:09:44.447  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:09:44.447  1015  1128 E Tethering: No numeric data
09-06 19:09:44.447  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-06 19:09:44.447  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:44.447  1177  1177 D HotspotTile: updateTetherState():false, false
09-06 19:09:44.447  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-06 19:09:44.447  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:09:44.447  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:09:44.447  1015  1128 D Tethering: clearTetheredNotification()
,09-06 19:09:44.447  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:44.447  1015  1121 V NetworkStats: performPollLocked() took 4ms
,09-06 19:09:44.457  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:09:44.457  1177  1177 D HotspotTile: updateTetherState():false, false
,09-06 19:09:44.457  1015  1042 D Tethering: interfaceAdded p2p0
09-06 19:09:44.457  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-06 19:09:44.457   277   921 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-06 19:09:44.457   277   921 D SoftapController: Softap fwReload - Ok
09-06 19:09:44.457  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:09:44.457  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:44.457  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:44.457  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:44.457  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:44.457  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:09:44.457   277   921 D CommandListener: Setting iface cfg
09-06 19:09:44.457  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:09:44.457   277   921 D CommandListener: Trying to bring down wlan0
,09-06 19:09:44.457  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:44.457  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:09:44.457   277   921 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:09:44.467  1015  1121 V NetworkStats: performPollLocked() took 5ms,
09-06 19:09:44.467  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.467  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:44.467  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:44.467  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
09-06 19:09:44.467  7313  7313 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:44.467  7313  7313 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:44.497  7313  7313 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:09:44.507  7328  7328 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-06 19:09:44.507  7328  7328 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:09:44.507  7328  7328 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 19:09:44.527  7328  7328 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-06 19:09:44.537   390   390 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7328
,09-06 19:09:44.537   390   390 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-06 19:09:44.537  7328  7328 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-06 19:09:44.537  7328  7328 I wpa_supplicant: ssSupport state is = 1
09-06 19:09:44.537  7328  7328 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:09:44.537  7328  7328 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-06 19:09:44.537   390   390 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7328
09-06 19:09:44.537   390   390 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-06 19:09:44.567  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-06 19:09:44.567  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:09:44.567  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:44.567  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:44.567  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:44.567  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:44.567  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:44.577  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-06 19:09:44.577  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-06 19:09:44.577  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:09:44.587  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:44.587  1177  1177 D HotspotTile: onReceive : 2, 0
,09-06 19:09:44.587  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:44.587  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:44.587  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:44.707   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
09-06 19:09:44.707  7328  7328 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-06 19:09:44.757  7328  7328 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:09:44.757  7328  7328 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:09:44.767  7328  7328 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-06 19:09:44.767   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7328
09-06 19:09:44.767   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:09:44.767  7328  7328 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 19:09:44.767  7328  7328 I wpa_supplicant: ssSupport state is = 1
,09-06 19:09:44.777  7328  7328 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 19:09:44.777  7328  7328 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:09:44.777  7328  7328 E wpa_supplicant: SIM READ ERROR
09-06 19:09:44.777  7328  7328 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-06 19:09:44.777  7328  7328 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:09:44.777  7328  7328 E wpa_supplicant: SIM READ ERROR
09-06 19:09:44.777  7328  7328 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:09:44.777  7328  7328 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:09:44.777  7328  7328 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-06 19:09:44.777  7328  7328 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:44.777  7328  7328 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 19:09:44.777  7328  7328 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:44.777  7328  7328 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 19:09:44.777  7328  7328 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:09:44.777  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:09:44.777  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:44.777  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:44.857  1015  1313 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-06 19:09:44.857  1015  1313 I ActivityManager: Killing 6982:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,09-06 19:09:44.867  7328  7328 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-06 19:09:44.867  1015  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:44.867  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:44.867  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:44.867  1015  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:44.867  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:44.877  1602  1602 I Hs20UtilService: Starting #11
09-06 19:09:44.877  1602  1637 I Hs20UtilService: Message received 5011
,09-06 19:09:44.877  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:09:44.877  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:44.877  6551  6551 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:44.877  6551  6551 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:44.887  1015  4382 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:44.887  1015  4382 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:44.887  1015  4382 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:44.887  1015  4382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:44.887  1015  4382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:44.887  1602  1602 I Hs20UtilService: Starting #12
,09-06 19:09:44.887  1602  1637 I Hs20UtilService: Message received 5011
,09-06 19:09:44.897  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:44.897  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:44.897  6551  6551 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:44.897  6551  6551 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:44.907  1015  4387 I ActivityManager: Killing 6888:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-06 19:09:45.017  7328  7328 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-06 19:09:45.017  7328  7328 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:09:45.027  7328  7328 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,09-06 19:09:45.037   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7328
09-06 19:09:45.037   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:09:45.037  7328  7328 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,09-06 19:09:45.037  7328  7328 I wpa_supplicant: ssSupport state is = 1
,09-06 19:09:45.037  7328  7328 I wpa_supplicant: Ctrl_iface: loading cred from phone,
,09-06 19:09:45.037  7328  7328 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:09:45.047  7328  7328 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-06 19:09:45.057   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7328
09-06 19:09:45.057   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:09:45.057  7328  7328 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
09-06 19:09:45.057  7328  7328 I wpa_supplicant: ssSupport state is = 1
09-06 19:09:45.057  7328  7328 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:45.057  7328  7328 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 19:09:45.057  7328  7328 E wpa_supplicant: SIM READ ERROR,
09-06 19:09:45.057  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:09:45.057  7328  7328 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:09:45.057  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:09:45.057  7328  7328 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-06 19:09:45.057  7328  7328 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:09:45.057  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:45.057  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:09:45.057  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:45.057  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:09:45.097  7328  7328 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-06 19:09:45.097  7328  7328 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:09:45.157  7328  7328 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-06 19:09:45.157  7328  7328 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-06 19:09:45.157  7328  7328 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:09:45.167  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-06 19:09:45.167  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:09:45.167  7328  7328 I wpa_supplicant: HOTSPOT20_ENABLE called
09-06 19:09:45.167  7328  7328 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:45.167  7328  7328 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:09:45.167  7328  7328 E wpa_supplicant: SIM READ ERROR
09-06 19:09:45.167  7328  7328 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:09:45.197  7328  7328 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-06 19:09:45.207  7328  7328 I wpa_supplicant: Skip scan - bUseNetwork false,
09-06 19:09:45.207  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:45.207  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:09:45.207  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:45.207  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:45.207  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:45.207  1177  1177 D HotspotTile: onReceive : 3, 0
09-06 19:09:45.207  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:45.207  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:45.207  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:09:45.207  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:45.207  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-06 19:09:45.217  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
09-06 19:09:45.217  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-06 19:09:45.217  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:45.217  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:45.217  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:45.217  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:45.217  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:45.217  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:45.217  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:45.217  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:45.217  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:45.217  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:45.217  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:45.227  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:45.227  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:45.227  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:45.227  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:45.227  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:45.227  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:45.227  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:45.227  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:45.227  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:45.227  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:45.227  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:45.227  1015  1531 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:45.227  1015  1531 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:45.227  1015  1531 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:45.227  1015  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:45.227  1015  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:45.227  1602  1602 I Hs20UtilService: Starting #13
09-06 19:09:45.227  1602  1637 I Hs20UtilService: Message received 5011,
,09-06 19:09:45.237  1015  1124 E WifiConfigStore: Not a HS20
,09-06 19:09:45.237  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:09:45.237  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:45.237  6551  6551 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:45.237  6551  6551 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:45.237   287   287 E SMD     : DCD OFF
,09-06 19:09:45.247  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:09:45.247  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-06 19:09:45.247  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-06 19:09:45.247  7328  7328 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 19:09:45.247  7328  7328 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:09:45.247  7328  7328 I wpa_supplicant: reset timer : RESET_TIMER 0
,09-06 19:09:45.247  7328  7328 I wpa_supplicant: P2P: Current p2p state = IDLE,
09-06 19:09:45.247  7328  7328 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:09:45.247  7328  7328 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:09:45.247  7328  7328 I wpa_supplicant: First Scan Start
,09-06 19:09:45.247  7328  7328 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-06 19:09:45.247  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
09-06 19:09:45.247  6998  6998 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:09:45.257  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:09:45.257  1015  1124 I WifiNative-HAL: startHal,
09-06 19:09:45.257  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d5f388c
09-06 19:09:45.257  1015  1124 I WifiNative-HAL: Could not start hal
,09-06 19:09:45.257   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:45.257  1015  1124 E WifiNative-wlan0: do suspend true
,09-06 19:09:45.257  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-06 19:09:45.257  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,09-06 19:09:45.257  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:45.257  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
09-06 19:09:45.257  1015  1147 I WifiNative-HAL: startHal
,09-06 19:09:45.257  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9eab19bc
09-06 19:09:45.257  1015  1147 I WifiNative-HAL: Could not start hal
09-06 19:09:45.257  1015  1147 E WifiScanningService: could not start HAL
09-06 19:09:45.257  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:09:45.257  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:09:45.257  1015  1124 E WifiNative-wlan0: invaild command id : 215
09-06 19:09:45.257  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-06 19:09:45.257  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:09:45.257  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:09:45.257  1015  1124 E WifiNative-wlan0: invaild command id : 215
09-06 19:09:45.257   277   921 D CommandListener: Setting iface cfg
09-06 19:09:45.257   277   921 D CommandListener: Trying to bring up p2p0
,09-06 19:09:45.267  1015  1148 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:45.267  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:09:45.267  1015  1123 D WifiP2pService: P2pEnablingState
,09-06 19:09:45.267  7328  7328 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:09:45.267  7328  7328 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 19:09:45.267  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
09-06 19:09:45.267  1015  1123 D WifiP2pService: P2p socket connection successful
09-06 19:09:45.267  1015  1123 D WifiP2pService: P2pEnabledState
09-06 19:09:45.267  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-06 19:09:45.267  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 19:09:45.267  7328  7328 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-06 19:09:45.267  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,09-06 19:09:45.267  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:45.267  1015  1124 D SecContentProvider2: mCursor = null
09-06 19:09:45.267  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 19:09:45.267  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-06 19:09:45.267  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:45.267  1015  1045 D WifiDisplayController: disconnect
09-06 19:09:45.267  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:45.267  1015  1045 D WifiDisplayController: updateConnection
09-06 19:09:45.267  1015  1124 D SecContentProvider2: mCursor = null
09-06 19:09:45.267  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:45.267  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:09:45.277  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:09:45.277  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:09:45.277  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:45.277  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:09:45.277  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress,
09-06 19:09:45.277  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:09:45.277  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
09-06 19:09:45.277  1015  4382 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:09:45.277  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-06 19:09:45.277  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:09:45.277  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:45.277  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:09:45.287  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
,09-06 19:09:45.287  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:09:45.287  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:45.287  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:09:45.287  3063  3880 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:45.287  1015  5159 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-06 19:09:45.287  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  secondary type: null
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  wps: 0
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  grpcapab: 0
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  devcapab: 0
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  status: 3
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  wfdInfo: null
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  groupownerAddress: null
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  GOdeviceName: null
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  interfaceAddress: 
09-06 19:09:45.287  1015  1045 D WifiDisplayController:  SConnectInfo : null
,09-06 19:09:45.287  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.287  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.287  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.287  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.297  7346  7346 E Zygote  : MountEmulatedStorage()
,09-06 19:09:45.307  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 19:09:45.307  7346  7346 E Zygote  : v2
09-06 19:09:45.307  7346  7346 I libpersona: KNOX_SDCARD checking this for 10064
09-06 19:09:45.307  7346  7346 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:45.307  7346  7346 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:45.307  1015  5159 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7346 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-06 19:09:45.307  7346  7346 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:45.317  1015  1123 D WifiP2pService: InactiveState,
09-06 19:09:45.317  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
09-06 19:09:45.317  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:09:45.317  7328  7328 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-06 19:09:45.317  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
09-06 19:09:45.317  7346  7346 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:45.317  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:09:45.337  7346  7346 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:45.337  7346  7346 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:45.347  7346  7346 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 19:09:45.357  7346  7346 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:45.367  7346  7346 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:09:45.397  7346  7346 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:09:45.397  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-06 19:09:45.397  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.397  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.397  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.397  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.417  7361  7361 E Zygote  : MountEmulatedStorage()
,09-06 19:09:45.417  7361  7361 E Zygote  : v2
,09-06 19:09:45.417  7361  7361 I libpersona: KNOX_SDCARD checking this for 10065
09-06 19:09:45.417  7361  7361 I libpersona: KNOX_SDCARD not a persona,
09-06 19:09:45.417  1015  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7361 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:45.417  1015  1027 I ActivityManager: Killing 7022:com.android.bluetooth/1002 (adj 15): empty #21,
09-06 19:09:45.417  7361  7361 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:45.417  7361  7361 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:45.427  7361  7361 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:45.437  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:45.437  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:09:45.437  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:09:45.447  7361  7361 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:45.447  7361  7361 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:45.467  7361  7361 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:45.477  1015  1137 I ActivityManager: Killing 6912:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-06 19:09:46.257   325   325 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-06 19:09:46.507  7328  7328 I wpa_supplicant: nl80211: Received scan results (15 BSSes),
09-06 19:09:46.507  7328  7328 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:09:46.507  7328  7328 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-06 19:09:46.507  7328  7328 I wpa_supplicant: Trying to associate with  'G700',
09-06 19:09:46.507  7328  7328 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-06 19:09:46.507  7328  7328 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-06 19:09:46.507  1015  7342 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-06 19:09:46.527  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:46.527  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:09:46.627  7328  7328 E wpa_supplicant: Cmd 35605 not handled
,09-06 19:09:46.627  7328  7328 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:09:46.627  7328  7328 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-06 19:09:46.627  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:46.627  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:46.627  7328  7328 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-06 19:09:46.627  7328  7328 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 19:09:46.627  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:46.627  7328  7328 I wpa_supplicant: Associated with F4.99.3E
09-06 19:09:46.627  7328  7328 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-06 19:09:46.627  7328  7328 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 19:09:46.627  7328  7328 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:09:46.627  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:46.627  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:46.627  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:46.627  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
,09-06 19:09:46.627  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
,09-06 19:09:46.627  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:46.627  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:09:46.627  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-06 19:09:46.627  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
09-06 19:09:46.637  7328  7328 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
,09-06 19:09:46.637  7328  7328 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-06 19:09:46.637  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:09:46.637  1015  1128 E Tethering: No numeric data
09-06 19:09:46.637  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:09:46.637  7328  7328 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-06 19:09:46.637  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:09:46.637  7328  7328 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-06 19:09:46.647  1177  1177 D HotspotTile: updateTetherState():false, false
09-06 19:09:46.637  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:09:46.637  1015  1128 D Tethering: clearTetheredNotification()
09-06 19:09:46.637  7328  7328 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:09:46.637  7328  7328 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 19:09:46.637  7328  7328 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 19:09:46.637  7328  7328 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 19:09:46.637  7328  7328 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-06 19:09:46.637  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:46.637  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:09:46.637  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:46.637  1015  1124 D SecContentProvider2: mCursor = null
09-06 19:09:46.637  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
09-06 19:09:46.647  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:46.647  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:09:46.647  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:46.647  1015  1121 V NetworkStats: performPollLocked() took 7ms
,09-06 19:09:46.647  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:46.647  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:46.647  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-06 19:09:46.657  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1,
09-06 19:09:46.657  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:09:46.657  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:46.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.657  1015  1718 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:46.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.657  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:46.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.667  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:46.667  1015  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-06 19:09:46.667  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:46.667  1602  1602 I Hs20UtilService: Starting #14
,09-06 19:09:46.667  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 19:09:46.667  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 19:09:46.667  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 19:09:46.667  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:09:46.667  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:09:46.667  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:09:46.667  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:46.667  1602  1637 I Hs20UtilService: Message received 5007
,09-06 19:09:46.667  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:46.677  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:09:46.677  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:46.677  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:46.677  3063  3880 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:46.697  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:09:46.707   277   921 D CommandListener: Setting iface cfg,
09-06 19:09:46.707  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,09-06 19:09:46.707  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:46.707  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:09:46.717  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:09:46.717  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:09:46.717  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:09:46.717  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:46.717  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:46.717  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:46.717  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.717  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:46.727  1015  1124 E WifiNative-wlan0: do suspend false
,09-06 19:09:46.727  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:09:46.727  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:46.727  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:09:46.727  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:09:46.947  7379  7379 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:09:46.957  7379  7379 I dhcpcd  : version 5.5.6 starting,
,09-06 19:09:46.957  7379  7379 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:09:47.017  7379  7379 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-06 19:09:47.017  7379  7379 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-06 19:09:47.017  7379  7379 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-06 19:09:47.017  7379  7379 I dhcpcd  : bssid match
,09-06 19:09:47.017  7379  7379 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-06 19:09:47.067  1015  1532 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 19:09:47.067  1015  1532 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:09:47.067  1015  1532 D SecContentProvider2: mCursor = null
,09-06 19:09:47.077  1015  1532 D WifiService: setWifiEnabled: false pid=6750, uid=10171
,09-06 19:09:47.077  1015  1532 D SettingsProvider: name = wifi_on
,09-06 19:09:47.087  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:09:47.097  1015  1124 E WifiNative-wlan0: do suspend true
,09-06 19:09:47.097  7379  7379 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,09-06 19:09:47.117  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
09-06 19:09:47.117  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 },
09-06 19:09:47.117  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:47.117  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:47.117  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:09:47.117  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.117  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.117  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.127   277   921 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:09:47.127  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 19:09:47.127  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 19:09:47.127  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:09:47.127  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
09-06 19:09:47.127  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-06 19:09:47.127   277   921 E Netd    : no such netId 503
09-06 19:09:47.127  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
09-06 19:09:47.127  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
09-06 19:09:47.137  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
09-06 19:09:47.137  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.137  1015  1126 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
09-06 19:09:47.137  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-06 19:09:47.137  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-06 19:09:47.137  1015  1126 V NetworkStats: updateIfacesLocked()
09-06 19:09:47.137  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:09:47.137  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:47.137  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:47.137  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.137  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.137  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.137  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.147  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:09:47.147  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:47.147  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:47.147  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:09:47.147  1015  1015 D RttService: SCAN_AVAILABLE : 1
09-06 19:09:47.147  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:09:47.147  1015  1126 V NetworkStats: performPollLocked() took 14ms
09-06 19:09:47.147  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:47.157  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-06 19:09:47.157  1015  7377 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:47.157  1015  7377 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 19:09:47.157  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 19:09:47.157  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 19:09:47.157  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 19:09:47.157  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-06 19:09:47.167  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:09:47.167  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:09:47.167  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:47.167  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:09:47.167  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.167  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:47.167  1015  4386 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:47.167  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-06 19:09:47.167  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-06 19:09:47.167  1015  4386 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:47.167  1015  4386 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:47.167  1015  4386 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:47.167  1015  4386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:47.177  1015  1123 D WifiP2pService: P2pDisablingState
,09-06 19:09:47.177  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 19:09:47.177  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-06 19:09:47.177  1602  1602 I Hs20UtilService: Starting #15
09-06 19:09:47.177  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:47.177  1015  1124 E WifiNative-wlan0: do suspend true
09-06 19:09:47.177  1015  1045 D WifiDisplayController: disconnect
09-06 19:09:47.177  1602  1637 I Hs20UtilService: Message received 5007
09-06 19:09:47.177  1015  1045 D WifiDisplayController: updateConnection
09-06 19:09:47.177  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:47.177  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:09:47.177  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 19:09:47.177  1015  1123 D WifiP2pService: p2p socket connection lost
09-06 19:09:47.177  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:09:47.177  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:09:47.177  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:47.177  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:09:47.177  1015  1123 D WifiP2pService: P2pDisabledState
,09-06 19:09:47.187  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:09:47.187  1015  1488 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:09:47.187  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:09:47.197  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:09:47.197  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:47.197  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:47.197  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:09:47.197  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:47.197  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:47.197  3063  3880 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:47.217  7379  7379 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,09-06 19:09:47.217  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
09-06 19:09:47.217  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,09-06 19:09:47.217  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:09:47.217  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:47.227  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:47.227  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:09:47.227  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-06 19:09:47.227   277   921 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:09:47.227  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:47.227  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:47.227  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.227  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.227  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.227  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.227  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:09:47.227  3063  3880 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:47.237  7346  7346 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:47.237  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
09-06 19:09:47.237  7346  7346 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 19:09:47.237  7346  7346 D FileShare-Client: Outbound.stopDelayTimer - 
09-06 19:09:47.237  7328  7328 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:09:47.257  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 19:09:47.257  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:47.257  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.257  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.257  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.257  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.257  7361  7361 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:47.267  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:47.267  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:09:47.267  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-06 19:09:47.267  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:47.267  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.267  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.267  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.267  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:09:47.267  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:47.267  1177  1177 D HotspotTile: onReceive : 0, 0
09-06 19:09:47.267  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-06 19:09:47.267  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-06 19:09:47.267  1015  1124 D SecContentProvider2: mCursor = null,
09-06 19:09:47.267  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:47.277  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:47.277  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:47.277  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:47.277  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:47.277  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:47.277  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:47.277  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:47.287  1015  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:47.287  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:47.287  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:47.287  1015  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:47.287  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:09:47.287  1602  1602 I Hs20UtilService: Starting #16,
,09-06 19:09:47.287  1602  1637 I Hs20UtilService: Message received 5007,
,09-06 19:09:47.287  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:09:47.287  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:47.297  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:47.297  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:47.297  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:47.297  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:47.297  3063  3880 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:47.307  1015  1531 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-06 19:09:47.307  1015  1531 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:47.307  1015  1531 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:47.307  1015  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:47.307  1015  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:47.307  1602  1602 I Hs20UtilService: Starting #17
,09-06 19:09:47.317  1602  1637 I Hs20UtilService: Message received 5011
,09-06 19:09:47.317  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:47.317  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:47.317  6551  6551 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:47.317  6551  6551 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:47.347  1015  1040 W ProcessCpuTracker: Skipping unknown process pid 7391
,09-06 19:09:47.387  7328  7328 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:09:47.447  7328  7328 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 19:09:47.447  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:47.447  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:09:47.447  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:09:47.477  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 19:09:47.477  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.477  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
09-06 19:09:47.477  1015  1128 D Tethering: InitialState.processMessage what=4
,09-06 19:09:47.477  1015  1128 E Tethering: No numeric data
09-06 19:09:47.477  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
,09-06 19:09:47.477  1015  1128 D Tethering: clearTetheredNotification()
09-06 19:09:47.487  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.487  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:09:47.487  7328  7328 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-06 19:09:47.487  7328  7328 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 19:09:47.487  7328  7328 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 19:09:47.487  7328  7328 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 19:09:47.487  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:47.487  7328  7328 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-06 19:09:47.487  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:09:47.487  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.487  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:09:47.487  1177  1177 D HotspotTile: updateTetherState():false, false
,09-06 19:09:47.487  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:47.487  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:47.487  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.487  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:47.487  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:47.497  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.497  1015  1121 V NetworkStats: performPollLocked() took 10ms
,09-06 19:09:47.497  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.497  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:47.617  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.617  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.617  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:47.777  7328  7328 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:09:47.837  7328  7328 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 19:09:47.837  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.837  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.837  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
,09-06 19:09:47.847  1015  1488 I ActivityManager: Killing 7039:com.sec.pcw.device/1000 (adj 15): empty #21
,09-06 19:09:47.957  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-06 19:09:47.957  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:09:47.967  6998  6998 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:09:47.967  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:09:47.967  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:47.967  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.967  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.967  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.967  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.967  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:47.967  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-06 19:09:47.967  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:47.967  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:09:47.967  1177  1177 D HotspotTile: onReceive : 1, 0
,09-06 19:09:47.977  1980  2155 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-06 19:09:47.977  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:47.977  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:47.977  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:47.977  1015  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:47.987  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:47.987  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:47.987  1015  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:47.987  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:47.987  1602  1602 I Hs20UtilService: Starting #18
,09-06 19:09:47.987  1602  1637 I Hs20UtilService: Message received 5011
,09-06 19:09:47.987  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:47.987  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:47.987  6551  6551 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:47.987  6551  6551 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:48.237   287   287 E SMD     : DCD OFF
,09-06 19:09:48.617  1015  1042 D Tethering: interfaceRemoved wlan0
,09-06 19:09:48.617  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:09:48.857  1015  1042 D Tethering: interfaceRemoved p2p0
,09-06 19:09:48.857  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:09:49.687  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,09-06 19:09:49.707  1015  3373 D SSRM:n  : SIOP:: AP = 360,
,09-06 19:09:50.087  6750  6803 D BluetoothAdapter: enable()
,09-06 19:09:50.087  1015  1532 W ActivityManager: Permission Denial: getCurrentUser() from pid=6750, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:09:50.087  1015  1532 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 19:09:50.087  1015  1532 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6750, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:50.087  1015  1532 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:09:50.087  1015  1532 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-06 19:09:50.087  1015  1532 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 19:09:50.087  1015  1532 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 19:09:50.087  1015  1532 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:09:50.087  1015  1532 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:09:50.087  1015  1532 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:50.087  1015  1532 D SettingsProvider: name = bluetooth_on
,09-06 19:09:50.097  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:09:50.097  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:50.097  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-06 19:09:50.097  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-06 19:09:50.097  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:50.097  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:50.097  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:50.097  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:50.117  7411  7411 E Zygote  : MountEmulatedStorage(),
09-06 19:09:50.117  7411  7411 E Zygote  : v2
09-06 19:09:50.117  7411  7411 I libpersona: KNOX_SDCARD checking this for 1002,
09-06 19:09:50.117  7411  7411 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:50.117  7411  7411 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:09:50.127  7411  7411 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:50.127  7411  7411 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-06 19:09:50.127  1015  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7411 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-06 19:09:50.157  7411  7411 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:50.157  7411  7411 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:50.177  7411  7411 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 19:09:50.177  7411  7411 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:09:50.207  7411  7411 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding GattService
,09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding HeadsetService
,09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding A2dpService
09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding HidService
,09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding HealthService
09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding PanService
09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding SapService
,09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding SapClientService
,09-06 19:09:50.247  7411  7411 D BtSettings.ProfileConfig: Adding HidDevService
09-06 19:09:50.247  7411  7411 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 19:09:50.257  1015  1531 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 19:09:50.257  1015  1531 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.257  1015  1531 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.257  1015  1531 D SettingsProvider: selectionArgs: false
09-06 19:09:50.257  1015  1531 D SettingsProvider: selectionArgs: 1002,
09-06 19:09:50.257  1015  1531 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:50.257  1015  1531 D SettingsProvider: ret = -1
09-06 19:09:50.257  1015  1718 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:50.257  1015  1718 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.257  1015  1718 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.257  1015  1718 D SettingsProvider: selectionArgs: false
09-06 19:09:50.257  1015  1718 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:50.257  1015  1718 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:50.257  1015  1718 D SettingsProvider: ret = -1
09-06 19:09:50.257  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-06 19:09:50.257  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:09:50.257  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.257  1015  1028 D SettingsProvider: selectionArgs: false
09-06 19:09:50.257  1015  1028 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.257  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:50.257  1015  1028 D SettingsProvider: ret = -1,
09-06 19:09:50.257  1015  5159 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-06 19:09:50.257  1015  5159 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.257  1015  5159 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.257  1015  5159 D SettingsProvider: selectionArgs: false
09-06 19:09:50.257  1015  5159 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:50.257  1015  5159 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:50.257  1015  5159 D SettingsProvider: ret = -1
09-06 19:09:50.257  1015  1518 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-06 19:09:50.257  1015  1518 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.257  1015  1518 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.257  1015  1518 D SettingsProvider: selectionArgs: false
,09-06 19:09:50.257  1015  1518 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.257  1015  1518 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:50.257  1015  1518 D SettingsProvider: ret = -1
09-06 19:09:50.257  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-06 19:09:50.257  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.257  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.257  1015  1027 D SettingsProvider: selectionArgs: false
,09-06 19:09:50.257  1015  1027 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.257  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:50.257  1015  1027 D SettingsProvider: ret = -1
09-06 19:09:50.257  1015  4382 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 19:09:50.257  1015  4382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.257  1015  4382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-06 19:09:50.257  1015  4382 D SettingsProvider: selectionArgs: false
09-06 19:09:50.257  1015  4382 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.257  1015  4382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:50.257  1015  4382 D SettingsProvider: ret = -1
09-06 19:09:50.257  1015  1486 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
09-06 19:09:50.257  1015  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.257  1015  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.257  1015  1486 D SettingsProvider: selectionArgs: false
09-06 19:09:50.257  1015  1486 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.257  1015  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:50.257  1015  1486 D SettingsProvider: ret = -1
09-06 19:09:50.257  1015  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:50.257  1015  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.257  1015  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.257  1015  1137 D SettingsProvider: selectionArgs: false
09-06 19:09:50.257  1015  1137 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.257  1015  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:50.257  1015  1137 D SettingsProvider: ret = -1,
09-06 19:09:50.267  1015  4386 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:09:50.267  1015  4386 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.267  1015  4386 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.267  1015  4386 D SettingsProvider: selectionArgs: false
,09-06 19:09:50.267  1015  4386 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.267  1015  4386 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:50.267  1015  4386 D SettingsProvider: ret = -1
09-06 19:09:50.267  1015  1502 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 19:09:50.267  1015  1502 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.267  1015  1502 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.267  1015  1502 D SettingsProvider: selectionArgs: false
,09-06 19:09:50.267  1015  1502 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.267  1015  1502 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:50.267  1015  1502 D SettingsProvider: ret = -1
09-06 19:09:50.267  1015  1488 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-06 19:09:50.267  1015  1488 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.267  1015  1488 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-06 19:09:50.267  1015  1488 D SettingsProvider: selectionArgs: false
09-06 19:09:50.267  1015  1488 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.267  1015  1488 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:50.267  1015  1488 D SettingsProvider: ret = -1
,09-06 19:09:50.287  7411  7411 D BluetoothAdapterState: make
,09-06 19:09:50.287  7411  7426 I BluetoothAdapterState: Entering OffState
,09-06 19:09:50.287  7411  7411 I bluedroid: init
,09-06 19:09:50.297  7411  7411 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
09-06 19:09:50.297  7411  7411 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:09:50.297  7411  7411 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:09:50.297  7411  7411 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-06 19:09:50.297  7411  7411 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-06 19:09:50.297  7411  7411 I bluedroid: get_profile_interface socket
,09-06 19:09:50.297  7411  7429 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 19:09:50.297  7411  7411 I bluedroid: get_profile_interface map_client
,09-06 19:09:50.297  7411  7411 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,09-06 19:09:50.297  7411  7429 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-06 19:09:50.307  7411  7429 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:09:50.307  7411  7429 I bluedroid: getModelRssiValues
09-06 19:09:50.307  7411  7429 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:09:50.307  7411  7429 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:09:50.307  1015  1015 D SettingsProvider: name = bluetooth_name
,09-06 19:09:50.307  7411  7429 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 19:09:50.307  7411  7411 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
09-06 19:09:50.307  1015  1137 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:50.307  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.317  1015  1137 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:50.317  1015  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.317  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.317  7411  7421 I bluedroid: config_hci_snoop_log
,09-06 19:09:50.317  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-06 19:09:50.317  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-06 19:09:50.327  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-06 19:09:50.327  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-06 19:09:50.327  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:09:50.327  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:50.327  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:50.327  7411  7411 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-06 19:09:50.337  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:09:50.337  7411  7426 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 19:09:50.337  7411  7426 D BluetoothAdapterProperties: Setting state to 11
09-06 19:09:50.337  7411  7426 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:09:50.337  7411  7426 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:50.337  7411  7426 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 19:09:50.337  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-06 19:09:50.337  7411  7426 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:09:50.337  7411  7426 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 19:09:50.347  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:50.347  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-06 19:09:50.347  7411  7426 D BluetoothSecureManager: getInstant: null
,09-06 19:09:50.347  7411  7426 D BluetoothSecureManager: calling getMethod for getService
,09-06 19:09:50.357  7411  7426 D BluetoothSecureManager: calling getService
,09-06 19:09:50.357  7411  7426 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@26f7ce18
,09-06 19:09:50.357  1015  5159 D BluetoothSecureManagerService: isSecureModeEnabled
09-06 19:09:50.357  1015  5159 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-06 19:09:50.357  7411  7426 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:09:50.357  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:50.357  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:09:50.357  1015  4386 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:50.357  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:09:50.357  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:50.357  1177  1177 D BluetoothTile:  getBluetoothState : 11
,09-06 19:09:50.367  1015  4386 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.367  1963  1963 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:09:50.367  1015  4386 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.367  7411  7426 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 19:09:50.367  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:50.367  1015  4386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:50.367  1015  4386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:09:50.367  7411  7426 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-06 19:09:50.367  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService,
09-06 19:09:50.367  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:50.367  1015  1313 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:50.367  7411  7426 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-06 19:09:50.367  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:09:50.377  7411  7426 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-06 19:09:50.377  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:50.377  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:09:50.377  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-06 19:09:50.377  1015  4382 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:50.377  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 19:09:50.377  7411  7426 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-06 19:09:50.377  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 19:09:50.377  7411  7426 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 19:09:50.377  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:50.377  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:50.377  7411  7426 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 19:09:50.377  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:50.377  7411  7426 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-06 19:09:50.377  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:50.377  7411  7426 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:50.377  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:09:50.377  7411  7426 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:50.377  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:50.377  7411  7426 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:50.377  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 19:09:50.377  7411  7426 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-06 19:09:50.377  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:50.387  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:50.397  7411  7426 D BluetoothBondStateMachine: make
,09-06 19:09:50.397  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:50.397  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 19:09:50.397  1015  1518 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 19:09:50.397  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:09:50.397  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:09:50.397  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 19:09:50.397  7411  7432 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:09:50.397  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:50.397  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:50.397  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:50.397  1015  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:50.407  7433  7433 E Zygote  : MountEmulatedStorage(),
09-06 19:09:50.407  7433  7433 E Zygote  : v2
09-06 19:09:50.407  7433  7433 I libpersona: KNOX_SDCARD checking this for 10055
09-06 19:09:50.407  7433  7433 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:50.417  7433  7433 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:50.407  1015  1518 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7433 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-06 19:09:50.417  1015  5159 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.417  1015  5159 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.417  7433  7433 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:50.417  1015  5159 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.417  1015  5159 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.417  1015  5159 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.417  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:09:50.417  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:09:50.417  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 19:09:50.417  1015  1532 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.417  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.417  7411  7411 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:09:50.417  7433  7433 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:50.417  7411  7411 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:09:50.417  7411  7411 D BtGatt.GattService: start()
09-06 19:09:50.417  7411  7411 D BtGatt.GattService: start()
09-06 19:09:50.417  7411  7411 I bluedroid: get_profile_interface gatt
09-06 19:09:50.417  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
09-06 19:09:50.417  7411  7411 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:09:50.417  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.417  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.417  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.427  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:09:50.427  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:50.427  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:50.427  1015  4387 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.427  1015  4387 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.427  1015  4387 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.427  1015  4387 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.427  1015  4387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.427  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:09:50.427  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:50.427  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:09:50.427  1015  1532 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.427  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.427  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.427  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.427  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.437  7411  7411 D BtGatt.GattService: mStartError = false
09-06 19:09:50.437  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:50.437  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:09:50.437  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:50.437  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-06 19:09:50.437  1015  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.437  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.437  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.437  1015  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:50.437  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:50.437  7411  7411 D HeadsetService: Received start request. Starting profile...
09-06 19:09:50.437  7411  7411 D HeadsetService: start()
,09-06 19:09:50.437  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 19:09:50.437  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:50.437  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:09:50.437  1015  4386 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.437  1015  4386 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-06 19:09:50.437  7411  7411 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:09:50.437  1015  4386 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.437  1015  4386 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.437  1015  4386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:50.437  7411  7411 D HeadsetStateMachine: make
09-06 19:09:50.437  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:50.437  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:50.437  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:50.437  7411  7411 E HeadsetStateMachine: # of Max HF connection is 2
09-06 19:09:50.437  1015  1313 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.447  1015  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.447  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.447  1015  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.447  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.447  1015  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-06 19:09:50.447  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-06 19:09:50.447  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:09:50.447  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
09-06 19:09:50.447  7411  7426 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-06 19:09:50.457  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.457  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.457  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:09:50.457  1015  5159 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.457  1015  5159 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.457  1015  5159 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.457  1015  5159 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.457  1015  5159 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.457  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:50.457  1015  1718 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 19:09:50.457  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:50.457  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-06 19:09:50.457  7411  7426 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:50.457  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:50.457  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:50.457  7411  7426 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:50.457  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:50.457  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:50.457  7411  7426 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:09:50.457  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:09:50.457  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:50.457  7411  7426 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:09:50.457  7411  7426 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 19:09:50.457  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.457  1015  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.457  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:09:50.457  7411  7411 I bluedroid: get_profile_interface handsfree
09-06 19:09:50.457  7433  7433 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:50.457  7433  7433 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:50.477  7411  7411 I DualScoManager: Instantiating Dual Sco Manager
,09-06 19:09:50.487  7411  7411 I DualScoManager: Set HeadsetServiceHelper
,09-06 19:09:50.487  7411  7411 D BluetoothAtMessage: createCMTIContentObservers
,09-06 19:09:50.487  1015  1532 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-06 19:09:50.487  1015  1532 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:09:50.487  1015  1532 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.487  1015  1532 D SettingsProvider: selectionArgs: false
09-06 19:09:50.487  1015  1532 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.487  1015  1532 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:50.487  1015  1532 D SettingsProvider: ret = -1
,09-06 19:09:50.487  7411  7446 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 19:09:50.487  7411  7411 D HeadsetService: mStartError = false
09-06 19:09:50.487  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:50.487  7433  7433 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-06 19:09:50.497  7411  7411 D A2dpService: Received start request. Starting profile...
09-06 19:09:50.497  7411  7411 D A2dpService: start()
,09-06 19:09:50.497  7411  7411 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 19:09:50.497  7411  7411 I bluedroid: get_profile_interface avrcp,
,09-06 19:09:50.497  7411  7446 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 19:09:50.497  7411  7446 D HeadsetStateMachine: map size, before remove : 0
,09-06 19:09:50.497  7411  7446 D HeadsetStateMachine: map size, after remove: 0
,09-06 19:09:50.507  7411  7411 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:09:50.507  7411  7411 D Avrcp   : Initialize Media Controller
,09-06 19:09:50.507  7411  7411 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 19:09:50.507  7411  7411 E Avrcp   : getActiveSessions
,09-06 19:09:50.507  7411  7411 D Avrcp   : pick active media Controller
09-06 19:09:50.507  7411  7411 D Avrcp   : Get the active Media Controller 
,09-06 19:09:50.527  7433  7433 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-06 19:09:50.527  7433  7433 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-06 19:09:50.527  7433  7433 D UserAnalysis: Create SecureDbHelper
,09-06 19:09:50.527  7411  7411 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 19:09:50.527  7411  7454 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-06 19:09:50.527  7411  7411 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:09:50.527  7411  7411 D A2dpStateMachine: make
09-06 19:09:50.527  7433  7433 D IntelligenceServiceApplication: onCreate()
,09-06 19:09:50.537  7411  7411 I bluedroid: get_profile_interface a2dp
,09-06 19:09:50.537  7411  7456 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 19:09:50.537  7411  7411 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 19:09:50.537  1015  5159 I ActivityManager: Killing 7056:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-06 19:09:50.537  7411  7411 D A2dpService: mStartError = false
09-06 19:09:50.537  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:50.537  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-06 19:09:50.537  7411  7411 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:09:50.537  7411  7455 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:09:50.537  7411  7411 D HidService: Received start request. Starting profile...
09-06 19:09:50.537  7411  7411 D HidService: start()
,09-06 19:09:50.537  7411  7411 I bluedroid: get_profile_interface hidhost
09-06 19:09:50.537  7411  7411 D HidService: setHidService(): set to: null
09-06 19:09:50.537  7411  7411 D HidService: mStartError = false
09-06 19:09:50.537  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
09-06 19:09:50.537  7433  7433 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 19:09:50.537  7411  7411 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 19:09:50.547  7411  7411 D HealthService: Received start request. Starting profile...
09-06 19:09:50.547  1015  1502 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-06 19:09:50.547  7411  7411 D HealthService: start()
,09-06 19:09:50.547  7411  7411 I bluedroid: get_profile_interface health
,09-06 19:09:50.547  7411  7411 D HealthService: mStartError = false
09-06 19:09:50.547  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:50.547  7433  7433 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-06 19:09:50.547  7411  7411 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:09:50.547  7411  7411 D PanService: Received start request. Starting profile...
09-06 19:09:50.547  7411  7411 D PanService: start()
09-06 19:09:50.547  7411  7411 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:09:50.547  7411  7411 I bluedroid: get_profile_interface pan
,09-06 19:09:50.547  7411  7411 D PanService: mStartError = false
09-06 19:09:50.547  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:50.557  7411  7454 D BluetoothMediaBrowser: no now playing list
09-06 19:09:50.557  7411  7411 D BluetoothMapService: Received start request. Starting profile...
09-06 19:09:50.557  7411  7411 D BluetoothMapService: start()
,09-06 19:09:50.557  7433  7433 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 19:09:50.557  7411  7454 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-06 19:09:50.557  7411  7411 D BluetoothMapService: mStartError = false
09-06 19:09:50.557  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:50.557  7411  7411 D HeadsetStateMachine: Try to query the phonestate on bind
,09-06 19:09:50.557  1445  1454 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 19:09:50.557  1445  1445 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-06 19:09:50.557  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-06 19:09:50.557  1445  1454 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 19:09:50.567  7411  7411 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-06 19:09:50.567  7411  7411 D SapService: Received start request. Starting profile...
,09-06 19:09:50.567  7411  7411 D SapService: start()
09-06 19:09:50.567  7411  7411 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 19:09:50.567  7411  7411 I bluedroid: get_profile_interface sap
09-06 19:09:50.567  7411  7411 D SapService: mStartError = false
09-06 19:09:50.567  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
09-06 19:09:50.567  7411  7411 D HeadsetStateMachine: Proxy object connected
09-06 19:09:50.567  7411  7411 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-06 19:09:50.567  7411  7411 D HeadsetPhoneState: sendDeviceDataStateChanged
09-06 19:09:50.567  7411  7446 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:09:50.567  7411  7446 D HeadsetStateMachine: Disconnected process message: 18
09-06 19:09:50.567  7411  7411 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-06 19:09:50.567  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 19:09:50.567  7411  7411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:09:50.567  7411  7411 D BluetoothA2dp: Proxy object connected
09-06 19:09:50.567  7411  7411 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-06 19:09:50.567  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 19:09:50.567  7411  7446 D HeadsetStateMachine: Disconnected process message: 10
09-06 19:09:50.567  7411  7446 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:09:50.567  7411  7446 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:09:50.567  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 19:09:50.567  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-06 19:09:50.567  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:09:50.567  1015  1531 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 19:09:50.567  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:50.567  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:50.567  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:50.567  1015  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:50.577  7461  7461 E Zygote  : MountEmulatedStorage()
09-06 19:09:50.577  7461  7461 E Zygote  : v2
09-06 19:09:50.577  7461  7461 I libpersona: KNOX_SDCARD checking this for 10105
09-06 19:09:50.577  7461  7461 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:50.587  1015  1531 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7461 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-06 19:09:50.587  7461  7461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:50.587  7461  7461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:09:50.587  7461  7461 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-06 19:09:50.607  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-06 19:09:50.607  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 19:09:50.617  7411  7426 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:09:50.617  7411  7426 I bluedroid: enable
,09-06 19:09:50.617  7411  7426 I bt_hci_bdroid: init
,09-06 19:09:50.617  7411  7472 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-06 19:09:50.617  7411  7426 I bt_vendor: bt-vendor : init
09-06 19:09:50.617  7411  7426 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:09:50.617  7411  7426 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:09:50.617  7411  7426 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-06 19:09:50.617  7411  7426 D bt_userial_mct: userial_init
,09-06 19:09:50.617  7411  7426 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:09:50.617  7411  7426 I bt_vendor: Starting hciattach daemon
09-06 19:09:50.617  7411  7426 I bt_vendor: try to set false
09-06 19:09:50.617  7411  7426 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:09:50.617  7411  7426 I bt_vendor: Starting hciattach daemon
09-06 19:09:50.617  7411  7426 I bt_vendor: try to set true
,09-06 19:09:50.637  7479  7479 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 19:09:50.657  7461  7461 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:50.657  7461  7461 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:50.687  7487  7487 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 19:09:50.697  7488  7488 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:09:50.717  7490  7490 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:09:50.727  7491  7491 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-06 19:09:50.747  7492  7492 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:09:50.757  7493  7493 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-06 19:09:50.817   256   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:09:50.817   256   527 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:50.817  7461  7499 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:09:50.827   256   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:09:50.827   256   527 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:50.827  7461  7499 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:09:50.967  7461  7461 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:50.967  7461  7461 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:50.967  7461  7461 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:50.967  7461  7461 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:50.967  7461  7461 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.k.d(PG:583)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:50.967  7461  7461 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:50.967  1015  1313 I ActivityManager: Killing 7077:com.sec.android.soagent/u0a31 (adj 15): empty #21
09-06 19:09:50.967  7461  7461 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:50.967  7461  7461 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:50.967  7461  7461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:50.967  1980  1980 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 19:09:50.977  1980  1980 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:51.007  7510  7510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
09-06 19:09:51.017  7511  7511 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-06 19:09:51.037  7461  7503 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:09:51.067  7411  7426 I bt_vendor: bluetooth satus is on
,09-06 19:09:51.077  7411  7476 D bt_userial_mct: userial_open(port:0)
,09-06 19:09:51.077  7411  7476 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 19:09:51.077  7411  7476 I bt_vendor: Done intiailizing UART
,09-06 19:09:51.077  7411  7476 I bt_vendor: Done intiailizing UART
,09-06 19:09:51.077  7411  7476 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,09-06 19:09:51.077  7411  7476 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-06 19:09:51.077  7411  7514 D bt_userial_mct: Entering userial_read_thread()
,09-06 19:09:51.217  1015  1137 I art     : Explicit concurrent mark sweep GC freed 84228(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.445ms total 159.243ms
,09-06 19:09:51.217  1015  4387 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:51.217  1015  4387 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:09:51.217  1015  4387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:09:51.217  1015  4387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_SAP
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 19:09:51.217  7411  7472 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-06 19:09:51.247   287   287 E SMD     : DCD OFF,
,09-06 19:09:51.307  7411  7472 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 19:09:51.317  7411  7472 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4232ed1 
,09-06 19:09:51.317  7411  7472 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4232ed1 
,09-06 19:09:51.327  7411  7429 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-06 19:09:51.337  7411  7429 E bt-btif : Calling BTA_HhEnable
,09-06 19:09:51.337  7411  7429 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 19:09:51.337  7411  7429 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-06 19:09:51.337  7411  7429 E BluetoothServiceJni: populateRssiValuesNative
,09-06 19:09:51.337  7411  7429 I bluedroid: getModelRssiValues
09-06 19:09:51.337  7411  7429 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-06 19:09:51.347  7411  7429 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:09:51.347  1015  1015 D SettingsProvider: name = bluetooth_name
,09-06 19:09:51.347  7411  7429 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 19:09:51.357  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:51.357  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:51.357  7411  7429 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 19:09:51.357  7411  7429 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:09:51.357  7411  7429 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:09:51.357  7411  7429 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,09-06 19:09:51.357  7411  7429 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-06 19:09:51.357  7411  7429 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-06 19:09:51.357  7411  7429 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-06 19:09:51.357  7411  7429 E bt-btif : btif_sock_init: !vhci_init
,09-06 19:09:51.367  7411  7514 E bt_mct  : hci lib postload completed
09-06 19:09:51.367  7411  7429 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-06 19:09:51.367  7411  7429 D IOP_DB_BT: db_open: db_open : handle 3027755024l, read 13894 bytes onto local cache
,09-06 19:09:51.367  7411  7429 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-06 19:09:51.367  7411  7429 D IOP_DB_BT: db_query: result 1
,09-06 19:09:51.367  7411  7429 I         : iop_db_open: iop_db_open status 0
,09-06 19:09:51.367  7411  7429 D bte_conf: Device ID record 1 : primary
,09-06 19:09:51.367  7411  7429 D bte_conf:   vendorId            = 0075
09-06 19:09:51.367  7411  7429 D bte_conf:   vendorIdSource      = 0001
,09-06 19:09:51.367  7411  7429 D bte_conf:   product             = 0100
,09-06 19:09:51.377  7411  7429 D bte_conf:   version             = 0200
09-06 19:09:51.377  7411  7429 D bte_conf:   clientExecutableURL = 
09-06 19:09:51.377  7411  7429 D bte_conf:   serviceDescription  = 
09-06 19:09:51.377  7411  7429 D bte_conf:   documentationURL    = 
09-06 19:09:51.377  7411  7429 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:09:51.377  7411  7429 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:09:51.377  7411  7426 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 19:09:51.377  7411  7426 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:09:51.377  7411  7426 D BluetoothAdapterProperties: State =  11
,09-06 19:09:51.377  1015  1502 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:09:51.377  7411  7426 D BluetoothAdapterProperties: Setting state to 12
,09-06 19:09:51.377  7411  7426 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:09:51.377  7411  7429 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:09:51.377  7411  7429 D BluetoothAdapterProperties: Scan Mode:21
,09-06 19:09:51.387  7411  7429 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:09:51.387  1015  4386 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-06 19:09:51.387  1015  4386 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:09:51.387  1015  4386 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:51.387  1015  4386 D SettingsProvider: selectionArgs: false
09-06 19:09:51.387  1015  4386 D SettingsProvider: selectionArgs: 1002
09-06 19:09:51.387  1015  4386 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:51.387  1015  4386 D SettingsProvider: ret = -1
,09-06 19:09:51.387  7411  7426 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:51.387  7411  7426 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 19:09:51.387  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:51.387  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.387  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:51.387  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.387  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:51.397  7411  7426 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:51.397  7411  7426 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 19:09:51.397  7411  7426 D BluetoothAdapterService: starting service from this receiver
,09-06 19:09:51.397  1015  1518 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:51.397  3063  3072 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:51.397  1015  1518 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.397  3063  3072 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:51.397  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:51.397  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:51.397  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:51.397  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:51.397  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:51.397  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:51.397  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:51.397  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:51.397  1015  1518 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.397  1015  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.397  1015  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:51.397  7411  7426 I BluetoothAdapterState: Entering On State from state = 11
,09-06 19:09:51.397  1468  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:51.397  1468  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:51.407  1445  6930 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:51.407  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:51.407  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:51.407  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:51.407  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:51.407  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:51.407  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:51.407  1445  6930 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:51.417  3063  3071 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:51.417  3063  3071 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:51.417  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:51.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:51.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:51.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:51.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:51.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:51.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:51.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:51.417  7411  7411 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-06 19:09:51.417  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:51.417  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.417  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.417  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.417  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:51.417  7411  7430 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:51.417  7411  7430 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:51.417  1445  1456 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:51.427  3063  3063 D BluetoothA2dp: Proxy object connected
09-06 19:09:51.427  3063  3063 D A2dpProfile: Bluetooth service connected
,09-06 19:09:51.427  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:51.427  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:51.427  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.427  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.427  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-06 19:09:51.427  1445  1456 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:51.427  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:51.427  3063  3071 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:09:51.427  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-06 19:09:51.427  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.427  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.427  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.437  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:51.437  7411  7411 I BluetoothPbapService: Handler(): got msg=1
,09-06 19:09:51.437  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:51.437  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:51.437  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:51.437  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:09:51.437  3063  3072 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:09:51.437  1015  1486 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:09:51.437  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-06 19:09:51.437  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.437  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:51.437  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.437  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:51.447  3063  7519 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:09:51.447  3063  3063 D BluetoothPbap: Proxy object connected
09-06 19:09:51.447  3063  3063 D PbapServerProfile: Bluetooth service connected
09-06 19:09:51.447  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-06 19:09:51.447  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.447  7411  7520 V BluetoothPbapService: PBAP Service initSocket try: 0
09-06 19:09:51.447  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.447  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.447  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:51.447  3063  3063 D BluetoothMap: Proxy object connected
09-06 19:09:51.447  3063  3063 D MapProfile: Bluetooth service connected
09-06 19:09:51.447  3063  3063 D BluetoothMap: getConnectedDevices()
,09-06 19:09:51.447  7461  7480 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:51.447  7461  7480 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:51.447  3063  3072 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:51.447  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:51.447  7411  7520 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:09:51.447  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:09:51.447  7411  7520 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:51.447  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.447  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.447  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:51.447  3063  3072 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:09:51.447  6750  6758 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:51.447  6750  6758 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:51.447  3063  3063 D BluetoothInputDevice: Proxy object connected
,09-06 19:09:51.447  3063  3063 D HidProfile: Bluetooth service connected
09-06 19:09:51.447  1177  1203 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:51.447  1177  1203 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:51.457  7411  7520 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-06 19:09:51.457  7411  7520 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:51.457  7411  7520 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:51.457  7411  7520 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@795df45
09-06 19:09:51.457  7411  7520 D BluetoothSocket: channel: 19
,09-06 19:09:51.457  7411  7520 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-06 19:09:51.457  3063  7519 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 19:09:51.457  3063  7519 D Bluetoothsap: Binding service...
,09-06 19:09:51.457  3063  3063 D HeadsetProfile: Bluetooth service connected
,09-06 19:09:51.457  3063  7519 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:09:51.457  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-06 19:09:51.457  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.457  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.457  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.457  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 19:09:51.457  3063  7519 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:09:51.457  7411  7421 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:09:51.467  1455  1489 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:51.467  1455  1489 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:51.467  3063  3063 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 19:09:51.467  3063  3063 D SapProfile: Bluetooth service connected
09-06 19:09:51.467  3063  3063 D Bluetoothsap: getConnectedDevices()
,09-06 19:09:51.467  1445  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:51.467  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:51.467  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:51.467  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.467  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:51.467  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:51.467  1445  1454 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:51.467  1445  1456 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:51.467  1445  1456 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:51.467  3063  3072 D BluetoothPan: Binding service...
,09-06 19:09:51.467  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-06 19:09:51.467  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.477  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:51.477  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.477  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:51.477  1980  1996 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:51.477  1980  1996 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:51.477  3063  3063 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:09:51.477  3063  3063 D PanProfile: Bluetooth service connected
09-06 19:09:51.477  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:51.477  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 19:09:51.477  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:51.477  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.477  1015  1015 D BluetoothA2dp: Proxy object connected
,09-06 19:09:51.477  1468  1713 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:51.477  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:51.477  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:51.477  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.477  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.477  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-06 19:09:51.477  1468  1713 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:51.477  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:51.477  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:51.477  1015  1044 D BluetoothPan: Binding service...
,09-06 19:09:51.477  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:09:51.487  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:09:51.477  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-06 19:09:51.487  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:09:51.487  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:09:51.487  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:51.487  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-06 19:09:51.487  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:09:51.487  1445  1445 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3680cb51, true
,09-06 19:09:51.487  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:09:51.497  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:09:51.497  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:51.497  1177  1177 D BluetoothTile:  getBluetoothState : 12
,09-06 19:09:51.497  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:51.497  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:51.497  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:51.497  1445  1445 D BluetoothHeadset: registerMessageListener
,09-06 19:09:51.497  1015  1137 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:51.507  1015  4382 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 19:09:51.507  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:51.507  1963  1963 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:51.507  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:51.507  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:51.507  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:51.517  7411  7421 D HeadsetService: registerMessageListener
,09-06 19:09:51.517  7411  7421 D HeadsetService: registerMessageListener
09-06 19:09:51.517  1015  4387 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:51.517  1015  4387 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.517  7411  7446 D HeadsetStateMachine: Disconnected process message: 70
09-06 19:09:51.517  7411  7446 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1935469a
,09-06 19:09:51.517  7411  7521 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-06 19:09:51.517  1445  1445 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 19:09:51.517  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:09:51.517  1015  4387 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.517  1015  4387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:51.517  1015  4387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:51.517  7411  7521 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:09:51.517  7411  7521 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:09:51.517  1445  1445 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-06 19:09:51.517  1445  1445 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-06 19:09:51.527  3063  3063 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-06 19:09:51.527  3063  3063 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 19:09:51.527  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-06 19:09:51.527  3063  3063 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 19:09:51.527  3063  3063 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 19:09:51.527  7411  7521 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-06 19:09:51.527  7411  7521 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:51.527  7411  7521 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:51.527  7411  7521 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c4e2bcb
,09-06 19:09:51.527  7411  7521 D BluetoothSocket: channel: 5
,09-06 19:09:51.527  7411  7446 D HeadsetStateMachine: Disconnected process message: 9
,09-06 19:09:51.527  7411  7446 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 19:09:51.537  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:51.537  1015  5159 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:09:51.537  1015  5159 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-06 19:09:51.537   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-06 19:09:51.537   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 19:09:51.537   282   282 V voice   : voice_set_parameters: exit with code(-2)
09-06 19:09:51.537   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 19:09:51.537   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 19:09:51.537   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:09:51.537   282   282 V audio_hw_primary: adev_set_parameters: exit
09-06 19:09:51.537  7411  7446 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 19:09:51.537  1015  5159 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:51.537  1015  5159 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.537  1015  5159 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:51.547  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:51.547  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:51.557  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:51.557  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:09:51.557  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:51.557  7411  7411 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:09:51.567  1015  4387 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:51.567  1015  4387 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.567  1015  4387 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.567  1015  4387 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:51.567  1015  4387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:51.587  1980  1980 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:51.587  1015  1518 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:51.587  1015  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:09:51.587  1015  1518 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:51.587  1015  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:51.597  1015  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:51.597  1015  1531 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:09:51.597  1980  7529 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:09:51.597  1980  1980 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:51.607  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:51.607  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:51.607  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:51.607  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:51.617  7411  7531 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:09:51.617  7411  7531 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:51.617  7411  7531 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,09-06 19:09:51.617  7411  7531 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:51.617  7411  7531 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-06 19:09:51.627  7411  7531 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e7db1fd
,09-06 19:09:51.627  7411  7531 D BluetoothSocket: channel: 12
09-06 19:09:51.627  7411  7531 I BtOppRfcommListener: Accept thread started.
,09-06 19:09:51.627  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:51.627  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:51.627  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:51.627  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:51.637  1980  7529 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 19:09:53.097  6750  6803 D BluetoothAdapter: disable()
,09-06 19:09:53.097  1015  1718 D SettingsProvider: name = bluetooth_on
,09-06 19:09:53.117  7411  7426 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-06 19:09:53.117  7411  7426 D BluetoothAdapterProperties: Setting state to 13
09-06 19:09:53.127  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.117  7411  7426 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:09:53.127  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-06 19:09:53.117  7411  7426 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:53.117  7411  7426 D BluetoothAdapterService: updateAdapterState state is 13
,09-06 19:09:53.127  1015  1027 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:53.127  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:53.127  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-06 19:09:53.127  7411  7411 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-06 19:09:53.127  7411  7426 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:09:53.127  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-06 19:09:53.127  7411  7426 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:09:53.127  7411  7426 D BluetoothAdapterService: terminating service from this receiver,
09-06 19:09:53.127  7411  7411 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e6e0ef2, channel: 19, state: LISTENING
09-06 19:09:53.127  7411  7411 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e6e0ef2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@795df45, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e964943mSocket: android.net.LocalSocket@2d21cbc0 impl:android.net.LocalSocketImpl@19f870f9 fd:FileDescriptor[74]
09-06 19:09:53.127  7411  7411 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d21cbc0 impl:android.net.LocalSocketImpl@19f870f9 fd:FileDescriptor[74]
,09-06 19:09:53.137  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.137  1015  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.137  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-06 19:09:53.137  7411  7426 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:09:53.137  7411  7426 D BluetoothAdapterProperties: mDiscovering is false
,09-06 19:09:53.137  1015  1313 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:09:53.137  7411  7426 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 19:09:53.137  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:53.137  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-06 19:09:53.147  3063  3063 D BluetoothPbap: Proxy object disconnected
09-06 19:09:53.147  3063  3063 D PbapServerProfile: Bluetooth service disconnected
,09-06 19:09:53.147  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:09:53.147  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:09:53.157  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:53.157  1177  1177 D BluetoothTile:  getBluetoothState : 13
,09-06 19:09:53.157  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:53.157  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:53.157  1963  1963 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:53.157  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:09:53.157  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:53.167  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:53.167  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:53.167  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:53.167  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:53.167  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:53.167  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:53.167  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:53.167  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:53.167  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:53.167  1015  1518 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:53.167  1015  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:53.167  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 19:09:53.167  1015  1531 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:53.167  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:53.177  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:53.177  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:53.177  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.177  1015  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:53.177  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:53.177  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:53.177  7411  7429 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:09:53.177  7411  7429 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:09:53.177  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:53.177  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:53.177  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:53.177  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:53.177  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:53.177  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:53.177  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:53.177  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:53.177  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:53.177  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:53.187  7411  7426 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-06 19:09:53.187  7411  7426 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-06 19:09:53.187  7411  7426 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-06 19:09:53.187  7411  7426 E bt-btif : cmd socket is not created
,09-06 19:09:53.187  7411  7426 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:09:53.187  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:53.187  1015  4382 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:09:53.187  1015  4382 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.187  7411  7472 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,09-06 19:09:53.187  7411  7472 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-06 19:09:53.187  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:53.187  7411  7472 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:53.187  7411  7472 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-06 19:09:53.187  7411  7531 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:09:53.187  7411  7472 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:09:53.197  1015  4382 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.197  1015  4382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:53.197  1015  4382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:53.207  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:53.217  7411  7411 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e4a369f, channel: 5, state: LISTENING
,09-06 19:09:53.217  7411  7411 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e4a369f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c4e2bcb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2037e3ecmSocket: android.net.LocalSocket@33c623b5 impl:android.net.LocalSocketImpl@3d3c8a4a fd:FileDescriptor[76]
,09-06 19:09:53.217  7411  7411 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33c623b5 impl:android.net.LocalSocketImpl@3d3c8a4a fd:FileDescriptor[76]
09-06 19:09:53.217  7411  7411 I BtOppRfcommListener: stopping Accept Thread
09-06 19:09:53.217  7411  7411 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4259dbb, channel: 12, state: LISTENING
09-06 19:09:53.217  7411  7411 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@4259dbb, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e7db1fd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33b552d8mSocket: android.net.LocalSocket@2e824631 impl:android.net.LocalSocketImpl@39c10116 fd:FileDescriptor[79]
,09-06 19:09:53.217  7411  7411 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2e824631 impl:android.net.LocalSocketImpl@39c10116 fd:FileDescriptor[79]
09-06 19:09:53.217  7411  7531 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:09:53.217  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:53.227  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:53.227  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:53.227  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:09:53.227  7411  7411 V BluetoothOppManager: cleanUp...
,09-06 19:09:53.257  1980  1980 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:53.257  1980  1980 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:53.387  7411  7472 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 19:09:53.387  7411  7472 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:53.387  7411  7472 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:09:53.387  7411  7472 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:53.397  7411  7472 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:53.397  7411  7514 I bt_userial_mct: exiting userial_read_thread
09-06 19:09:53.397  7411  7514 D bt_userial_mct: Leaving userial_evt_read_thread()
,09-06 19:09:53.397  7411  7472 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:53.397  7411  7472 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:53.397  7411  7472 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:53.397  7411  7472 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:53.397  7411  7472 W bt-btif : ag scb idx 1 not allocated
09-06 19:09:53.397  7411  7472 W bt-btif : ag scb idx 2 not allocated
09-06 19:09:53.397  7411  7472 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:09:53.397  7411  7429 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,09-06 19:09:53.397  7411  7476 I bt_vendor: hw_epilog_process
,09-06 19:09:53.397  7411  7429 D bt_userial_mct: userial_close
09-06 19:09:53.397  7411  7429 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 19:09:53.417  1015  4386 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:09:53.417  1015  4386 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-06 19:09:53.417  1015  4386 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-06 19:09:53.417  1015  4386 D BatteryService: stay LED for fully charged
,09-06 19:09:53.417  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:09:53.417  1015  1015 I MotionRecognitionService: Plugged
,09-06 19:09:53.427  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:09:53.427  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-06 19:09:53.427  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:09:53.427  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:09:53.427  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 19:09:53.447  7411  7411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:09:53.447  7411  7446 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:09:53.447  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:09:53.447  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:09:53.447  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:09:53.457  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-06 19:09:53.457  1177  1177 D SViewCoverView: level :100 plugged : 2
,09-06 19:09:53.777  7411  7429 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-06 19:09:53.777  7411  7429 I bt_vendor: bluetooth satus is on
09-06 19:09:53.777  7411  7429 I bt_vendor: bt-vendor : resetting BT status
09-06 19:09:53.777  7411  7429 I bt_vendor: Starting hciattach daemon
09-06 19:09:53.777  7411  7429 I bt_vendor: try to set false
,09-06 19:09:53.777  7411  7429 I bt_vendor: Starting hciattach daemon
09-06 19:09:53.777  7411  7429 I bt_vendor: try to set false
,09-06 19:09:53.777  7411  7429 I bt_vendor: cleanup
,09-06 19:09:53.777  7411  7472 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 19:09:53.777  7411  7429 I GKI_LINUX: GKI_exit_task 0 done
,09-06 19:09:53.777  7411  7429 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-06 19:09:53.777  7411  7426 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-06 19:09:53.777  7411  7426 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:09:53.777  7411  7426 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-06 19:09:53.777  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:09:53.777  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:09:53.777  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 19:09:53.787  1015  1718 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.787  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.787  1015  1718 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:53.787  1015  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:53.787  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.787  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:53.787  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:09:53.787  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 19:09:53.787  7411  7411 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:09:53.787  7411  7411 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:09:53.787  1015  1718 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.787  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.787  7411  7411 D BtGatt.GattService: stop()
09-06 19:09:53.787  7411  7411 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 19:09:53.787  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.787  1015  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:53.787  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.797  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:53.797  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:53.797  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-06 19:09:53.797  1015  1718 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.797  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 19:09:53.797  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
09-06 19:09:53.797  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.797  1015  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.797  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.797  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:09:53.797  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:53.797  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:09:53.797  1015  1718 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.797  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.797  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.797  1015  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.797  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:53.797  7411  7411 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:09:53.797  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:09:53.797  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:53.797  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:09:53.797  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:53.797  1015  1532 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.797  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.797  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.797  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.797  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.807  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 19:09:53.807  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:53.807  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:09:53.807  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-06 19:09:53.807  1015  4387 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.807  1015  4387 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.807  1015  4387 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.807  1015  4387 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.807  1015  4387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:53.807  3063  3063 D HeadsetProfile: Bluetooth service disconnected
,09-06 19:09:53.807  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:53.807  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.807  7411  7426 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:53.807  1015  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.807  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.807  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.807  1015  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.807  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.807  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:09:53.817  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:53.817  7411  7426 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:09:53.817  1015  1313 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.817  1015  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-06 19:09:53.817  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.817  1015  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.817  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.817  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:53.817  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:53.817  7411  7426 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:53.817  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:53.817  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:09:53.817  7411  7426 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:53.817  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:53.817  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:53.817  7411  7426 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:09:53.817  7411  7426 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:09:53.817  7411  7426 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:53.817  7411  7426 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:09:53.817  7411  7426 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:09:53.817  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-06 19:09:53.817  7411  7411 D A2dpService: Received stop request...Stopping profile...
,09-06 19:09:53.817  7411  7455 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:09:53.817  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:53.817  1015  1015 D BluetoothA2dp: Proxy object disconnected
,09-06 19:09:53.817  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:09:53.817  3063  3063 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:53.817  7411  7411 D HidService: Received stop request...Stopping profile...
09-06 19:09:53.817  7411  7411 D HidService: Stopping Bluetooth HidService
09-06 19:09:53.817  7411  7411 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:09:53.817  7411  7411 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 19:09:53.817  7411  7411 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:09:53.817  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:53.827  3063  3063 D A2dpProfile: Bluetooth service disconnected
,09-06 19:09:53.827  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 19:09:53.827  7411  7411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:53.827  7411  7411 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:09:53.827  3063  3063 D BluetoothInputDevice: Proxy object disconnected
09-06 19:09:53.827  3063  3063 D HidProfile: Bluetooth service disconnected
,09-06 19:09:53.827  7411  7411 D HealthService: Received stop request...Stopping profile...
,09-06 19:09:53.827  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:53.827  7411  7411 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-06 19:09:53.827  7411  7411 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:09:53.827  7411  7411 D PanService: Received stop request...Stopping profile...
,09-06 19:09:53.827  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:53.827  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:09:53.837  3063  3063 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:09:53.837  3063  3063 D PanProfile: Bluetooth service disconnected
09-06 19:09:53.837  7411  7411 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 19:09:53.837  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:53.837  3063  3063 D BluetoothMap: Proxy object disconnected
,09-06 19:09:53.837  3063  3063 D MapProfile: Bluetooth service disconnected
,09-06 19:09:53.837  7411  7411 D SapService: Received stop request...Stopping profile...
09-06 19:09:53.837  7411  7411 D SapService: Stopping Bluetooth SapService
09-06 19:09:53.837  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2de1e183
,09-06 19:09:53.837  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-06 19:09:53.837  7411  7411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:53.837  7411  7411 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:09:53.837  7411  7411 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:53.837  7411  7411 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-06 19:09:53.837  7411  7456 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-06 19:09:53.837  7411  7411 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:09:53.837  7411  7411 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:09:53.837  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 19:09:53.837  7411  7411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.837  7411  7411 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.837  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 19:09:53.837  7411  7411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.837  7411  7411 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.837  7411  7411 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:09:53.837  7411  7411 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:09:53.837  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 19:09:53.837  7411  7411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.837  7411  7411 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.837  7411  7411 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:09:53.837  7411  7411 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:09:53.847  3063  3063 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:09:53.847  3063  3063 D SapProfile: Bluetooth service disconnected
,09-06 19:09:53.847  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-06 19:09:53.847  7411  7411 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:53.847  7411  7411 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-06 19:09:53.847  7411  7411 E BluetoothAdapterService(769778051): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-06 19:09:53.847  7411  7411 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:09:53.847  7411  7411 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-06 19:09:53.847  7411  7426 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-06 19:09:53.847  7411  7426 D BluetoothAdapterProperties: Setting state to 10
09-06 19:09:53.847  7411  7426 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-06 19:09:53.847  7411  7426 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:53.847  7411  7426 D BluetoothAdapterService: updateAdapterState state is 10
,09-06 19:09:53.847  7411  7426 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:09:53.847  7411  7426 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 19:09:53.847  7411  7426 I BluetoothAdapterState: Entering OffState
,09-06 19:09:53.847  3063  3071 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:53.847  3063  3071 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.847  1468  1832 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.847  1468  1832 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.847  3063  7519 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:53.857  7411  7536 D BluetoothAdapter: onBluetoothStateChange: up=false,
09-06 19:09:53.857  7411  7536 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.857  3063  3072 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:09:53.857  3063  3071 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 19:09:53.857  3063  7519 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:09:53.857  7461  7474 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.857  7461  7474 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.857  6750  6759 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.857  6750  6759 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:53.857  6750  6759 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-06 19:09:53.857  6750  6759 D BluetoothLeAdvertiser: Exit stop advertising
09-06 19:09:53.857  6750  6759 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,09-06 19:09:53.857  6750  6759 D BluetoothLeScanner: Exiting stopAllScan
,09-06 19:09:53.857  1177  3881 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:53.857  1177  3881 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.857  3063  3071 D Bluetoothsap: onBluetoothStateChange: up=false
09-06 19:09:53.857  3063  3071 D Bluetoothsap: Unbinding service...
,09-06 19:09:53.857  7411  7419 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:53.867  1455  1489 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.867  1455  1489 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.867  1445  6930 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.867  1445  6930 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.867  1980  2153 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.867  1980  2153 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:53.867  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:53.867  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.867  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.867  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-06 19:09:53.867  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:09:53.877  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:53.877  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-06 19:09:53.877  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:09:53.877  1177  1177 D BluetoothAdapter: 713492178: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:53.877  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:09:53.877  1177  1662 D BluetoothAdapter: 713492178: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:53.887  7411  7429 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 19:09:53.887  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:53.887  1177  1177 D BluetoothTile:  getBluetoothState : 10
09-06 19:09:53.887  1177  1662 D BluetoothAdapter: 713492178: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:53.887  1963  1963 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:09:53.887  7411  7411 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:09:53.887  7411  7411 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-06 19:09:53.887  7411  7411 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 19:09:53.887  1177  1177 D BluetoothAdapter: 713492178: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:53.887  1177  1177 D BluetoothAdapter: 713492178: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:53.887  1980  2155 D BluetoothAdapter: 993648318: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:53.887  1980  2155 D BluetoothAdapter: 993648318: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:53.887  1015  5159 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:53.887  1015  4387 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:53.887  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 19:09:53.887  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:53.887  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:53.887  1015  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:53.887  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.887  7411  7411 I art     : System.exit called, status: 0
09-06 19:09:53.887  7411  7411 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:09:53.897  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:53.897  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.897  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 19:09:53.897  1015  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:53.897  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:53.897  1015  1486 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:09:53.897  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.897  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.897  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.897  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:53.897  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:53.907  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:53.907  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:53.907  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 19:09:53.917  1015  5159 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 19:09:53.927  1015  5159 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 19:09:53.927  1015  5159 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-06 19:09:53.927  1015  5159 W BroadcastQueue: android.os.TransactionTooLargeException
09-06 19:09:53.927  1015  5159 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:09:53.927  1015  5159 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:09:53.927  1015  5159 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-06 19:09:53.927  1015  5159 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-06 19:09:53.927  1015  5159 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-06 19:09:53.927  1015  5159 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-06 19:09:53.927  1015  5159 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-06 19:09:53.927  1015  5159 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-06 19:09:53.927  1015  5159 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:09:53.927  1015  5159 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-06 19:09:53.927  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:53.927  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:53.927  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:53.927  1015  5159 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:53.947  7549  7549 E Zygote  : MountEmulatedStorage(),
09-06 19:09:53.947  1015  5159 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7549 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
09-06 19:09:53.947  7549  7549 E Zygote  : v2
,09-06 19:09:53.947  7549  7549 I libpersona: KNOX_SDCARD checking this for 1002
,09-06 19:09:53.947  7549  7549 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:53.947  7549  7549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:53.947  7549  7549 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:09:53.947  7549  7549 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:53.967  7549  7549 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:53.967  7549  7549 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:53.977  7549  7549 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 19:09:53.977  7549  7549 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:09:54.007  7549  7549 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 19:09:54.047  7549  7549 D BtSettings.ProfileConfig: Adding GattService
,09-06 19:09:54.047  7549  7549 D BtSettings.ProfileConfig: Adding HeadsetService
,09-06 19:09:54.047  7549  7549 D BtSettings.ProfileConfig: Adding A2dpService
,09-06 19:09:54.047  7549  7549 D BtSettings.ProfileConfig: Adding HidService
,09-06 19:09:54.047  7549  7549 D BtSettings.ProfileConfig: Adding HealthService
09-06 19:09:54.047  7549  7549 D BtSettings.ProfileConfig: Adding PanService
,09-06 19:09:54.047  7549  7549 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-06 19:09:54.057  7549  7549 D BtSettings.ProfileConfig: Adding SapService
,09-06 19:09:54.057  7549  7549 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-06 19:09:54.057  7549  7549 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-06 19:09:54.057  7549  7549 D BtSettings.ProfileConfig: Adding SapClientService
,09-06 19:09:54.057  7549  7549 D BtSettings.ProfileConfig: Adding HidDevService
,09-06 19:09:54.057  7549  7549 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 19:09:54.057  1015  1486 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 19:09:54.057  1015  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:09:54.057  1015  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:54.057  1015  1486 D SettingsProvider: selectionArgs: false
09-06 19:09:54.057  1015  1486 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:54.057  1015  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:54.057  1015  1486 D SettingsProvider: ret = -1
,09-06 19:09:54.067  1015  1518 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:54.067  1015  1518 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:54.067  1015  1518 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:54.067  1015  1518 D SettingsProvider: selectionArgs: false
09-06 19:09:54.067  1015  1518 D SettingsProvider: selectionArgs: 1002
09-06 19:09:54.067  1015  1518 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:54.067  1015  1518 D SettingsProvider: ret = -1
,09-06 19:09:54.067  1015  1502 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-06 19:09:54.067  1015  1502 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:09:54.067  1015  1502 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:54.067  1015  1502 D SettingsProvider: selectionArgs: false
09-06 19:09:54.067  1015  1502 D SettingsProvider: selectionArgs: 1002
09-06 19:09:54.067  1015  1502 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:54.067  1015  1502 D SettingsProvider: ret = -1
,09-06 19:09:54.067  1015  4382 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-06 19:09:54.067  1015  4382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:09:54.067  1015  4382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:54.067  1015  4382 D SettingsProvider: selectionArgs: false
09-06 19:09:54.067  1015  4382 D SettingsProvider: selectionArgs: 1002
09-06 19:09:54.067  1015  4382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:54.067  1015  4382 D SettingsProvider: ret = -1
,09-06 19:09:54.067  1015  1488 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-06 19:09:54.067  1015  1488 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:54.067  1015  1488 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:54.067  1015  1488 D SettingsProvider: selectionArgs: false
09-06 19:09:54.067  1015  1488 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:54.067  1015  1488 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:54.067  1015  1488 D SettingsProvider: ret = -1
,09-06 19:09:54.067  1015  4387 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-06 19:09:54.067  1015  4387 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:54.067  1015  4387 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:54.067  1015  4387 D SettingsProvider: selectionArgs: false
09-06 19:09:54.067  1015  4387 D SettingsProvider: selectionArgs: 1002
09-06 19:09:54.067  1015  4387 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:54.067  1015  4387 D SettingsProvider: ret = -1
,09-06 19:09:54.067  1015  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 19:09:54.067  1015  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:54.067  1015  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:54.067  1015  1137 D SettingsProvider: selectionArgs: false
09-06 19:09:54.067  1015  1137 D SettingsProvider: selectionArgs: 1002
09-06 19:09:54.067  1015  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:54.067  1015  1137 D SettingsProvider: ret = -1
,09-06 19:09:54.067  1015  1531 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-06 19:09:54.067  1015  1531 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:54.067  1015  1531 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:54.067  1015  1531 D SettingsProvider: selectionArgs: false
09-06 19:09:54.067  1015  1531 D SettingsProvider: selectionArgs: 1002
09-06 19:09:54.067  1015  1531 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:54.067  1015  1531 D SettingsProvider: ret = -1
,09-06 19:09:54.077  1015  1718 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService,
09-06 19:09:54.077  1015  1718 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:54.077  1015  1718 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:54.077  1015  1718 D SettingsProvider: selectionArgs: false
09-06 19:09:54.077  1015  1718 D SettingsProvider: selectionArgs: 1002
09-06 19:09:54.077  1015  1718 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:54.077  1015  1718 D SettingsProvider: ret = -1
,09-06 19:09:54.077  1015  1313 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:54.077  1015  1313 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:54.077  1015  1313 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:54.077  1015  1313 D SettingsProvider: selectionArgs: false
09-06 19:09:54.077  1015  1313 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:54.077  1015  1313 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:54.077  1015  1313 D SettingsProvider: ret = -1
,09-06 19:09:54.077  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 19:09:54.077  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:54.077  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:54.077  1015  1027 D SettingsProvider: selectionArgs: false
,09-06 19:09:54.077  1015  1027 D SettingsProvider: selectionArgs: 1002
09-06 19:09:54.077  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:54.077  1015  1027 D SettingsProvider: ret = -1
,09-06 19:09:54.077  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-06 19:09:54.077  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-06 19:09:54.077  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:54.077  1015  1028 D SettingsProvider: selectionArgs: false
09-06 19:09:54.077  1015  1028 D SettingsProvider: selectionArgs: 1002
09-06 19:09:54.077  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:54.077  1015  1028 D SettingsProvider: ret = -1
,09-06 19:09:54.087  1980  1980 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:54.087  1015  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:54.087  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:09:54.097  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:54.097  1015  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:54.097  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:54.097  1980  7565 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:09:54.107  1980  1980 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:54.107  1015  4382 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:54.107  1015  4382 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:54.107  1015  4382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:54.107  1015  4382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:54.117  1980  7565 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-06 19:09:54.247   287   287 E SMD     : DCD OFF
,09-06 19:09:54.527  1015  1047 I PowerManagerService: [PWL] Off : 75s ago
,09-06 19:09:54.527  1015  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,09-06 19:09:54.527  1015  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-06 19:09:54.527  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=13188)
09-06 19:09:54.527  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2993)
09-06 19:09:54.527  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2992)
,09-06 19:09:55.747  1015  1326 E Watchdog: !@Sync 4
,09-06 19:09:56.117  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:09:56.117  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:56.257   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:09:57.247   287   287 E SMD     : DCD OFF
,09-06 19:09:57.257   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:58.257   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:59.117  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:09:59.117  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2dd7e7bc added. We now have 6 listener(s)
,09-06 19:09:59.117  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:59.117  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:09:59.117  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f12345 added. We now have 7 listener(s)
,09-06 19:09:59.127  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:59.127  6750  6803 I System.out: IsBluetoothEnabled
,09-06 19:09:59.127  6750  6803 D BluetoothAdapter: disable()
,09-06 19:09:59.127  1015  1137 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-06 19:09:59.137  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:59.137  6750  6803 D BluetoothAdapter: enable()
,09-06 19:09:59.137  1015  4382 I ActivityManager: Killing 7071:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,09-06 19:09:59.137  1015  1718 W ActivityManager: Permission Denial: getCurrentUser() from pid=6750, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:09:59.147  1015  1718 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 19:09:59.147  1015  1718 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6750, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:59.147  1015  1718 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:09:59.147  1015  1718 W BluetoothManagerService: ,	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-06 19:09:59.147  1015  1718 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 19:09:59.147  1015  1718 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 19:09:59.147  1015  1718 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:09:59.147  1015  1718 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:09:59.147  1015  1718 D SettingsProvider: name = bluetooth_on
,09-06 19:09:59.147  1015  1718 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:59.157  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:09:59.157  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:59.157  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-06 19:09:59.157  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-06 19:09:59.177  7549  7549 D BluetoothAdapterState: make
,09-06 19:09:59.177  7549  7549 I bluedroid: init
,09-06 19:09:59.187  7549  7572 I BluetoothAdapterState: Entering OffState,
09-06 19:09:59.187  7549  7549 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:09:59.187  7549  7549 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:09:59.187  7549  7549 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-06 19:09:59.187  7549  7549 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:09:59.187  7549  7549 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-06 19:09:59.187  7549  7549 I bluedroid: get_profile_interface socket
09-06 19:09:59.187  7549  7549 I bluedroid: get_profile_interface map_client
,09-06 19:09:59.187  7549  7575 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 19:09:59.187  7549  7575 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
09-06 19:09:59.187  7549  7575 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:09:59.187  7549  7575 I bluedroid: getModelRssiValues
,09-06 19:09:59.187  7549  7575 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127,
09-06 19:09:59.187  7549  7575 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
09-06 19:09:59.187  7549  7549 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-06 19:09:59.197  7549  7575 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 19:09:59.197  1015  1015 D SettingsProvider: name = bluetooth_name
,09-06 19:09:59.197  7549  7549 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.197  1015  1313 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp,
09-06 19:09:59.197  1015  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.207  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.207  1015  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.207  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.207  7549  7557 I bluedroid: config_hci_snoop_log
,09-06 19:09:59.207  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 19:09:59.217  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-06 19:09:59.217  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-06 19:09:59.217  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-06 19:09:59.217  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:09:59.217  7549  7549 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-06 19:09:59.227  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:59.227  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:59.237  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:09:59.237  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-06 19:09:59.237  7549  7572 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-06 19:09:59.237  7549  7572 D BluetoothAdapterProperties: Setting state to 11
09-06 19:09:59.237  7549  7572 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:09:59.237  7549  7572 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:59.237  7549  7572 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 19:09:59.237  7549  7572 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:09:59.237  7549  7572 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 19:09:59.247  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.247  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-06 19:09:59.247  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:09:59.257  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.257  1177  1177 D BluetoothTile:  getBluetoothState : 11
,09-06 19:09:59.257  7549  7572 D BluetoothSecureManager: getInstant: null
09-06 19:09:59.257  7549  7572 D BluetoothSecureManager: calling getMethod for getService
09-06 19:09:59.257  1963  1963 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:09:59.257  7549  7572 D BluetoothSecureManager: calling getService
,09-06 19:09:59.257  7549  7572 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@114a7ed7
,09-06 19:09:59.257  1015  1531 D BluetoothSecureManagerService: isSecureModeEnabled
09-06 19:09:59.257  1015  1531 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-06 19:09:59.257  7549  7572 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:09:59.257  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:09:59.257  7549  7572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 19:09:59.257  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:59.257  7549  7572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-06 19:09:59.257  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:59.257  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:09:59.257  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:09:59.257  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:59.257  7549  7572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-06 19:09:59.257  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:09:59.257  7549  7572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-06 19:09:59.257  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:59.257   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:59.257  7549  7572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-06 19:09:59.257  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 19:09:59.257  7549  7572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 19:09:59.257  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:59.257  1015  4386 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:59.267  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:59.267  1015  1488 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:59.267  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:59.267  7549  7572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 19:09:59.267  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:09:59.267  7549  7572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-06 19:09:59.267  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:59.267  1015  1718 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:59.267  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 19:09:59.267  7549  7572 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:59.267  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:09:59.267  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.267  1015  1718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:59.267  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:59.267  7549  7572 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:59.267  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:09:59.267  7549  7572 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:59.267  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:59.267  7549  7572 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-06 19:09:59.267  7549  7572 D BluetoothBondStateMachine: make
,09-06 19:09:59.277  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:09:59.277  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:09:59.277  7549  7572 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 19:09:59.277  7549  7577 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:09:59.277  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:59.277  1015  4382 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:59.277  1015  4382 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.277  1015  4382 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.277  1015  4382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.277  1015  4382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.277  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:09:59.277  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:09:59.277  7549  7572 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:59.277  7549  7549 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:09:59.277  1015  1313 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.277  1015  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.287  7549  7549 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:09:59.287  7549  7549 D BtGatt.GattService: start()
09-06 19:09:59.287  7549  7549 D BtGatt.GattService: start()
09-06 19:09:59.287  7549  7549 I bluedroid: get_profile_interface gatt
,09-06 19:09:59.287  7549  7549 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2106339
09-06 19:09:59.287  7549  7549 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:09:59.287  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.287  1015  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.287  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.287  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:09:59.287  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:59.287  7549  7572 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:59.287  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.287  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 19:09:59.297  1015  5159 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.297  1015  5159 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.297  1015  5159 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.297  1015  5159 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.297  1015  5159 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.297  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:09:59.297  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:59.297  7549  7572 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:09:59.297  7549  7549 D BtGatt.GattService: mStartError = false
09-06 19:09:59.297  7549  7549 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2106339
,09-06 19:09:59.307  7549  7549 D HeadsetService: Received start request. Starting profile...
,09-06 19:09:59.307  7549  7549 D HeadsetService: start()
,09-06 19:09:59.307  7549  7549 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 19:09:59.307  7549  7549 D HeadsetStateMachine: make
,09-06 19:09:59.307  1015  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:59.307  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.307  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.307  1015  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.307  7549  7549 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 19:09:59.317  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.317  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-06 19:09:59.317  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 19:09:59.317  7549  7572 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:09:59.317  1015  1313 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.317  1015  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.317  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.317  1015  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.317  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.317  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 19:09:59.317  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:59.317  7549  7572 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:09:59.327  1015  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:59.327  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.327  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.327  1015  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.327  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.327  1015  4387 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-06 19:09:59.327  1015  4387 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.327  1015  4387 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.327  1015  4387 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.327  1015  4387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:09:59.327  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:59.327  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:59.327  7549  7572 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:59.327  1015  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 19:09:59.327  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.327  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.327  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.327  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-06 19:09:59.327  7549  7549 I bluedroid: get_profile_interface handsfree
09-06 19:09:59.327  1015  1532 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:59.327  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.337  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.337  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.337  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.337  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-06 19:09:59.337  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:59.337  7549  7572 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:09:59.337  1015  1313 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:59.337  1015  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.337  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.337  1015  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.337  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.337  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:59.337  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:59.337  7549  7572 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:59.337  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:59.337  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:59.337  7549  7572 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:59.337  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:59.337  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:59.337  7549  7572 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:09:59.337  7549  7572 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:09:59.337  7549  7572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:59.337  7549  7572 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:09:59.337  7549  7572 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 19:09:59.347  7549  7549 I DualScoManager: Instantiating Dual Sco Manager
09-06 19:09:59.347  7549  7549 I DualScoManager: Set HeadsetServiceHelper
09-06 19:09:59.347  7549  7549 D BluetoothAtMessage: createCMTIContentObservers
,09-06 19:09:59.347  1015  1027 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-06 19:09:59.347  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:59.347  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:59.347  1015  1027 D SettingsProvider: selectionArgs: false
09-06 19:09:59.347  1015  1027 D SettingsProvider: selectionArgs: 1002
09-06 19:09:59.347  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:59.347  1015  1027 D SettingsProvider: ret = -1
,09-06 19:09:59.357  7549  7581 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 19:09:59.357  7549  7549 D HeadsetService: mStartError = false
09-06 19:09:59.357  7549  7549 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2106339
,09-06 19:09:59.357  7549  7581 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 19:09:59.357  7549  7581 D HeadsetStateMachine: map size, before remove : 0
09-06 19:09:59.357  7549  7581 D HeadsetStateMachine: map size, after remove: 0
,09-06 19:09:59.357  7549  7549 D A2dpService: Received start request. Starting profile...
,09-06 19:09:59.357  7549  7549 D A2dpService: start()
,09-06 19:09:59.357  7549  7549 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 19:09:59.357  7549  7549 I bluedroid: get_profile_interface avrcp
,09-06 19:09:59.367  7549  7549 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:09:59.367  7549  7549 D Avrcp   : Initialize Media Controller
09-06 19:09:59.367  7549  7549 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 19:09:59.367  7549  7549 E Avrcp   : getActiveSessions
09-06 19:09:59.367  7549  7549 D Avrcp   : pick active media Controller
09-06 19:09:59.367  7549  7549 D Avrcp   : Get the active Media Controller 
,09-06 19:09:59.387  7549  7549 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 19:09:59.387  7549  7585 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-06 19:09:59.387  7549  7549 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:09:59.387  7549  7549 D A2dpStateMachine: make
,09-06 19:09:59.397  7549  7549 I bluedroid: get_profile_interface a2dp
,09-06 19:09:59.397  7549  7587 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 19:09:59.397  7549  7549 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 19:09:59.397  7549  7549 D A2dpService: mStartError = false
09-06 19:09:59.397  7549  7549 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2106339
,09-06 19:09:59.397  7549  7549 E BluetoothAdapterService(34628409): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-06 19:09:59.397  7549  7586 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:09:59.397  7549  7549 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:09:59.397  7549  7549 D HidService: Received start request. Starting profile...
,09-06 19:09:59.397  7549  7549 D HidService: start()
09-06 19:09:59.397  7549  7549 I bluedroid: get_profile_interface hidhost
09-06 19:09:59.397  7549  7549 D HidService: setHidService(): set to: null
09-06 19:09:59.397  7549  7549 D HidService: mStartError = false
,09-06 19:09:59.397  7549  7549 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2106339
09-06 19:09:59.397  7549  7549 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 19:09:59.407  7549  7549 D HealthService: Received start request. Starting profile...
09-06 19:09:59.407  7549  7549 D HealthService: start()
,09-06 19:09:59.407  7549  7585 D BluetoothMediaBrowser: no now playing list
,09-06 19:09:59.407  7549  7585 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 19:09:59.407  7549  7549 I bluedroid: get_profile_interface health
,09-06 19:09:59.407  7549  7549 D HealthService: mStartError = false
09-06 19:09:59.407  7549  7549 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2106339
,09-06 19:09:59.407  7549  7549 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:09:59.407  7549  7549 D PanService: Received start request. Starting profile...
09-06 19:09:59.407  7549  7549 D PanService: start()
09-06 19:09:59.407  7549  7549 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:09:59.407  7549  7549 I bluedroid: get_profile_interface pan
,09-06 19:09:59.417  7549  7549 D PanService: mStartError = false
09-06 19:09:59.417  7549  7549 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2106339
,09-06 19:09:59.417  7549  7549 D HeadsetStateMachine: Try to query the phonestate on bind
,09-06 19:09:59.417  1445  1454 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 19:09:59.417  1445  1445 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-06 19:09:59.417  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-06 19:09:59.417  1445  1454 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 19:09:59.417  7549  7549 D HeadsetStateMachine: Proxy object connected
,09-06 19:09:59.417  1980  1980 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:59.417  7549  7549 D BluetoothMapService: Received start request. Starting profile...
09-06 19:09:59.417  7549  7549 D BluetoothMapService: start()
,09-06 19:09:59.417  1980  1980 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:59.427  7549  7549 D BluetoothMapService: mStartError = false
,09-06 19:09:59.427  7549  7549 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2106339
,09-06 19:09:59.427  7549  7549 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-06 19:09:59.427  7549  7549 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-06 19:09:59.427  7549  7581 D HeadsetStateMachine: Disconnected process message: 11
,09-06 19:09:59.427  7549  7549 D SapService: Received start request. Starting profile...
09-06 19:09:59.427  7549  7549 D SapService: start()
09-06 19:09:59.427  7549  7549 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 19:09:59.427  7549  7549 I bluedroid: get_profile_interface sap
09-06 19:09:59.427  7549  7549 D SapService: mStartError = false
09-06 19:09:59.427  7549  7549 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2106339
09-06 19:09:59.427  7549  7549 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-06 19:09:59.427  7549  7549 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-06 19:09:59.427  7549  7549 E BluetoothAdapterService(34628409): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 19:09:59.427  7549  7549 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:09:59.427  7549  7549 D BluetoothA2dp: Proxy object connected
09-06 19:09:59.427  7549  7549 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-06 19:09:59.427  7549  7549 E BluetoothAdapterService(34628409): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 19:09:59.427  7549  7549 E BluetoothAdapterService(34628409): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-06 19:09:59.427  7549  7581 D HeadsetStateMachine: Disconnected process message: 18
09-06 19:09:59.427  7549  7581 D HeadsetStateMachine: Disconnected process message: 10
09-06 19:09:59.427  7549  7581 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:09:59.427  7549  7581 D HeadsetStateMachine: Disconnected process message: 11
,09-06 19:09:59.427  7549  7549 E BluetoothAdapterService(34628409): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-06 19:09:59.427  7549  7549 E BluetoothAdapterService(34628409): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:09:59.447  7549  7549 E BluetoothAdapterService(34628409): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-06 19:09:59.447  7549  7549 E BluetoothAdapterService(34628409): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 19:09:59.457  7549  7572 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-06 19:09:59.457  7549  7572 I bluedroid: enable
09-06 19:09:59.457  7549  7591 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 19:09:59.457  7549  7572 I bt_hci_bdroid: init
,09-06 19:09:59.457  7549  7572 I bt_vendor: bt-vendor : init
,09-06 19:09:59.457  7549  7572 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:09:59.457  7549  7572 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:09:59.457  7549  7572 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
,09-06 19:09:59.457  7549  7572 D bt_userial_mct: userial_init
09-06 19:09:59.457  7549  7572 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-06 19:09:59.457  7549  7572 I bt_vendor: Starting hciattach daemon
09-06 19:09:59.457  7549  7572 I bt_vendor: try to set false
,09-06 19:09:59.457  7549  7572 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-06 19:09:59.457  7549  7572 I bt_vendor: Starting hciattach daemon
09-06 19:09:59.457  7549  7572 I bt_vendor: try to set true
,09-06 19:09:59.477  7595  7595 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-06 19:09:59.517  7601  7601 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-06 19:09:59.527  7602  7602 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 19:09:59.547  7604  7604 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:09:59.547  7605  7605 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-06 19:09:59.557  7606  7606 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:09:59.567  7607  7607 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-06 19:09:59.737  1015  3373 D SSRM:n  : SIOP:: AP = 330,
,09-06 19:09:59.787  7610  7610 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,09-06 19:09:59.797  7611  7611 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 19:09:59.817  7549  7572 I bt_vendor: bluetooth satus is on
,09-06 19:09:59.817  7549  7593 D bt_userial_mct: userial_open(port:0)
09-06 19:09:59.817  7549  7593 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 19:09:59.817  7549  7593 I bt_vendor: Done intiailizing UART
,09-06 19:09:59.817  7549  7593 I bt_vendor: Done intiailizing UART
09-06 19:09:59.817  7549  7593 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 19:09:59.817  7549  7593 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-06 19:09:59.827  7549  7613 D bt_userial_mct: Entering userial_read_thread()
,09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_L2CAP,
09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_BNEP,
09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_GAP
,09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_SAP
,09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_GATT
,09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 19:09:59.827  7549  7591 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-06 19:09:59.917  7549  7591 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 19:09:59.927  7549  7591 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4232ed1 
,09-06 19:09:59.927  7549  7591 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4232ed1 
,09-06 19:09:59.927  1015  2039 V SAMP_SPCM_test: CSC File load.. 
,09-06 19:09:59.947  7549  7575 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0,
,09-06 19:09:59.947  7549  7575 E bt-btif : Calling BTA_HhEnable
09-06 19:09:59.947  7549  7575 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
09-06 19:09:59.947  7549  7575 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
09-06 19:09:59.947  7549  7575 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:09:59.947  7549  7575 I bluedroid: getModelRssiValues
,09-06 19:09:59.947  7549  7575 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:09:59.947  7549  7575 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-06 19:09:59.957  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-06 19:09:59.977  1015  3386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:09:59.987  1015  1093 V AlarmManager: waitForAlarm result :8
,09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-06 19:09:59.997  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
,09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-06 19:10:00.007  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
,09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
,09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
,09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
,09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction,
09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-06 19:10:00.017  1015  2039 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-06 19:10:00.017  7549  7575 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 19:10:00.017  1015  1015 D SettingsProvider: name = bluetooth_name
,09-06 19:10:00.027  1015  2039 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,09-06 19:10:00.027  7549  7575 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:10:00.027  7549  7575 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:10:00.027  7549  7575 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:10:00.027  7549  7575 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
09-06 19:10:00.027  7549  7575 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-06 19:10:00.027  7549  7575 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-06 19:10:00.027  7549  7575 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-06 19:10:00.027  7549  7575 E bt-btif : btif_sock_init: !vhci_init
,09-06 19:10:00.027  7549  7575 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-06 19:10:00.027  7549  7575 D IOP_DB_BT: db_open: db_open : handle 3027656720l, read 13894 bytes onto local cache
09-06 19:10:00.027  7549  7575 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-06 19:10:00.027  7549  7575 D IOP_DB_BT: db_query: result 1
09-06 19:10:00.027  7549  7575 I         : iop_db_open: iop_db_open status 0
,09-06 19:10:00.027  7549  7575 D bte_conf: Device ID record 1 : primary
09-06 19:10:00.027  7549  7575 D bte_conf:   vendorId            = 0075
09-06 19:10:00.027  7549  7575 D bte_conf:   vendorIdSource      = 0001
09-06 19:10:00.027  7549  7575 D bte_conf:   product             = 0100
09-06 19:10:00.027  7549  7575 D bte_conf:   version             = 0200
09-06 19:10:00.027  7549  7575 D bte_conf:   clientExecutableURL = 
09-06 19:10:00.027  7549  7575 D bte_conf:   serviceDescription  = 
09-06 19:10:00.027  7549  7575 D bte_conf:   documentationURL    = 
09-06 19:10:00.027  7549  7575 D bte_conf: bte_load_did_conf no section named DID2.
09-06 19:10:00.027  7549  7575 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:10:00.027  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:00.027  1015  2039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:00.027  1015  2039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:00.027  1015  2039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:00.027  1015  2039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:00.037  7549  7613 E bt_mct  : hci lib postload completed
,09-06 19:10:00.047  7616  7616 E Zygote  : MountEmulatedStorage()
,09-06 19:10:00.047  7616  7616 E Zygote  : v2
09-06 19:10:00.047  7616  7616 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:10:00.047  7616  7616 I libpersona: KNOX_SDCARD not a persona
,09-06 19:10:00.047  7616  7616 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:10:00.047  1015  2039 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7616 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-06 19:10:00.047  7549  7572 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 19:10:00.047  7616  7616 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:10:00.047  7549  7572 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:10:00.047  7549  7572 D BluetoothAdapterProperties: State =  11
09-06 19:10:00.047  1015  4386 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:10:00.047  7549  7572 D BluetoothAdapterProperties: Setting state to 12
,09-06 19:10:00.047  7549  7572 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:10:00.047  7616  7616 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:10:00.057  7549  7575 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:10:00.057  7549  7575 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:10:00.057  7549  7575 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:10:00.057  1015  1137 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-06 19:10:00.057  1015  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:10:00.057  1015  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:10:00.057  1015  1137 D SettingsProvider: selectionArgs: false
09-06 19:10:00.057  1015  1137 D SettingsProvider: selectionArgs: 1002
09-06 19:10:00.057  1015  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:10:00.057  1015  1137 D SettingsProvider: ret = -1
,09-06 19:10:00.057  7549  7572 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:10:00.057  7549  7572 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 19:10:00.057  1015  1718 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:10:00.057  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:10:00.057  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:00.057  1015  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.057  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:10:00.057  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:00.057  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:00.057  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:00.057  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:10:00.057  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:00.057  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:00.057  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:00.057  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:00.057  7549  7572 D BluetoothAdapterService: Autoconnection is available 
09-06 19:10:00.067  7549  7572 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 19:10:00.067  7549  7572 D BluetoothAdapterService: starting service from this receiver
,09-06 19:10:00.067  1015  4382 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:10:00.067  1015  4382 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-06 19:10:00.067  3063  7519 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:10:00.067  3063  7519 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:10:00.067  1015  4382 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:00.067  1015  4382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.067  1015  4382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:10:00.067  7549  7572 I BluetoothAdapterState: Entering On State from state = 11
09-06 19:10:00.067  1468  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:10:00.067  1468  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:10:00.067  1445  6930 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:10:00.067  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:10:00.067  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:10:00.067  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:00.067  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.067  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-06 19:10:00.067  1445  6930 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:10:00.067  3063  3071 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:10:00.077  3063  3071 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:10:00.077  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:10:00.077  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:10:00.077  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:00.077  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.077  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 19:10:00.077  3063  3063 D BluetoothA2dp: Proxy object connected
09-06 19:10:00.077  3063  3063 D A2dpProfile: Bluetooth service connected
,09-06 19:10:00.077  7549  7557 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:10:00.077  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:10:00.077  7549  7549 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-06 19:10:00.087  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:10:00.077  1445  1456 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:10:00.087  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:10:00.087  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:00.087  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.087  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:10:00.087  1445  1456 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:10:00.087  3063  3071 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:10:00.087  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-06 19:10:00.087  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:10:00.087  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:00.087  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.087  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:10:00.087  7616  7616 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-06 19:10:00.087  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:10:00.087  7616  7616 D ActivityThread: Added TimaKeyStore provider
09-06 19:10:00.087  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset,
,09-06 19:10:00.087  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:10:00.087  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:10:00.097  7549  7576 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:10:00.097  7549  7576 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:10:00.097  3063  7519 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:10:00.097  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap,
09-06 19:10:00.097  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-06 19:10:00.097  1015  1044 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:10:00.097  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.097  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 19:10:00.097  7549  7549 I BluetoothPbapService: Handler(): got msg=1
,09-06 19:10:00.107  3063  3072 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:10:00.107  1015  1137 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:10:00.107  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-06 19:10:00.107  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:10:00.107  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:00.107  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.107  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 19:10:00.107  7549  7632 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 19:10:00.107  7461  7480 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:10:00.107  7461  7480 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:10:00.107  3063  3063 D BluetoothPbap: Proxy object connected
,09-06 19:10:00.117  3063  3063 D PbapServerProfile: Bluetooth service connected
09-06 19:10:00.117  3063  3063 D BluetoothMap: Proxy object connected
09-06 19:10:00.117  3063  3072 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:10:00.117  3063  3063 D MapProfile: Bluetooth service connected
09-06 19:10:00.117  3063  3063 D BluetoothMap: getConnectedDevices()
,09-06 19:10:00.117  3063  3063 D BluetoothInputDevice: Proxy object connected
09-06 19:10:00.117  7616  7616 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:10:00.117  3063  3063 D HidProfile: Bluetooth service connected
09-06 19:10:00.117  7549  7632 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:10:00.117  7549  7632 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:10:00.117  7549  7632 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-06 19:10:00.117  7549  7632 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:10:00.117  7549  7632 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:10:00.117  7549  7632 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c4e2bcb
09-06 19:10:00.117  7549  7632 D BluetoothSocket: channel: 19
09-06 19:10:00.117  7549  7632 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-06 19:10:00.157  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:00.157  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:00.157  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:00.157  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:10:00.157  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:00.157  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:00.157  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:00.157  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:00.157  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:00.157  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:00.157  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fc93a9a added. We now have 8 listener(s)
09-06 19:10:00.167  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:00.167  1015  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:10:00.167  1015  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:10:00.167  1015  1027 D SecContentProvider2: mCursor = null
,09-06 19:10:00.167  1015  1027 D WifiService: setWifiEnabled: false pid=6750, uid=10171
,09-06 19:10:00.167  1015  1027 D SettingsProvider: name = wifi_on
,09-06 19:10:00.167  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:00.167  1015  1718 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:10:00.177  1015  1718 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:10:00.177  1015  1718 D SecContentProvider2: mCursor = null
,09-06 19:10:00.177  1015  1718 D WifiService: setWifiEnabled: true pid=6750, uid=10171
,09-06 19:10:00.177  1015  1718 W ActivityManager: Permission Denial: getCurrentUser() from pid=6750, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:10:00.177  1015  1718 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:10:00.177  1015  1718 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6750, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:10:00.177  1015  1718 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:10:00.177  1015  1718 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:10:00.177  1015  1718 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:10:00.177  1015  1718 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:10:00.177  1015  1718 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:10:00.177  1015  1718 D SettingsProvider: name = wifi_on
,09-06 19:10:00.177  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 19:10:00.247   287   287 E SMD     : DCD OFF
,09-06 19:10:00.257   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:10:00.257  1015  1044 I art     : Explicit concurrent mark sweep GC freed 29341(1684KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.593ms total 148.385ms,
09-06 19:10:00.257  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:10:00.257  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:10:00.267  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:00.267  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.267  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:10:00.267  3063  3072 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:10:00.267  6750  6928 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:10:00.267  6750  6928 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:10:00.267  3063  3063 D HeadsetProfile: Bluetooth service connected
,09-06 19:10:00.267  1177  1203 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:10:00.267  1177  1203 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:10:00.267  3063  7519 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 19:10:00.267  3063  7519 D Bluetoothsap: Binding service...
,09-06 19:10:00.267  3063  7519 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:10:00.267  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-06 19:10:00.267  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:10:00.277  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:00.277  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.277  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:10:00.277  3063  7519 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:10:00.277  3063  3063 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 19:10:00.277  3063  3063 D SapProfile: Bluetooth service connected
09-06 19:10:00.277  3063  3063 D Bluetoothsap: getConnectedDevices()
,09-06 19:10:00.277  1455  1489 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:10:00.277  1455  1489 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:10:00.277  1015  2039 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-06 19:10:00.277  1445  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:10:00.287  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:10:00.287  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:10:00.287  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:00.287  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.287  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:10:00.287  1445  1454 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:10:00.287  1445  6930 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:10:00.287  1445  6930 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:10:00.287  3063  3071 D BluetoothPan: Binding service...
,09-06 19:10:00.287  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:10:00.287  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:10:00.287  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:00.287  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.287  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:10:00.287  1980  2153 D BluetoothAdapter: onBluetoothStateChange: up=true,
,09-06 19:10:00.287  1980  2153 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:10:00.287  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:10:00.287  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:10:00.287  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 19:10:00.287  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 19:10:00.297  1015  1015 D BluetoothA2dp: Proxy object connected
,09-06 19:10:00.297  3063  3063 D BluetoothPan: BluetoothPAN Proxy object connected,
09-06 19:10:00.297  3063  3063 D PanProfile: Bluetooth service connected
,09-06 19:10:00.297  1468  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:10:00.297  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:10:00.297  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:10:00.297  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:00.297  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.297  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 19:10:00.297  1468  1476 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:10:00.297  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:10:00.297  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:10:00.297  1015  1044 D BluetoothPan: Binding service...
,09-06 19:10:00.307  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-06 19:10:00.307  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:10:00.307  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:10:00.307  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-06 19:10:00.307  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:10:00.307  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:10:00.307  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-06 19:10:00.307  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:10:00.317  1445  1445 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@46f6fb6, true
,09-06 19:10:00.317  1445  1445 D BluetoothHeadset: registerMessageListener
,09-06 19:10:00.317  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:10:00.317  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:10:00.317  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:10:00.317  1177  1177 D BluetoothTile:  getBluetoothState : 12
,09-06 19:10:00.317  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:10:00.327  1963  1963 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:10:00.327  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:10:00.327  3063  3063 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:10:00.327  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:00.327  1177  1662 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:10:00.327  1015  1518 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:10:00.327  7549  7557 D HeadsetService: registerMessageListener
09-06 19:10:00.327  1015  4387 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:10:00.327  1015  4387 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:10:00.327  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 19:10:00.327  1015  4387 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:00.327  1015  4387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:10:00.327  1015  4387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:10:00.337  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:10:00.337  7549  7557 D HeadsetService: registerMessageListener
,09-06 19:10:00.337  7549  7581 D HeadsetStateMachine: Disconnected process message: 70
09-06 19:10:00.337  7549  7581 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@18a2afa8
,09-06 19:10:00.337  1445  1445 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-06 19:10:00.337  3063  3063 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-06 19:10:00.337  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-06 19:10:00.337  3063  3063 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 19:10:00.337  3063  3063 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 19:10:00.337  3063  3063 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 19:10:00.347  7549  7638 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-06 19:10:00.347  7549  7638 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:10:00.347  7549  7638 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:10:00.347  1445  1445 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-06 19:10:00.347  1445  1445 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-06 19:10:00.347  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-06 19:10:00.347  7549  7638 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-06 19:10:00.347  7549  7638 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:10:00.347  7549  7638 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:10:00.347  7549  7638 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12ba2ac1
,09-06 19:10:00.357  7549  7638 D BluetoothSocket: channel: 5
,09-06 19:10:00.357  7549  7581 D HeadsetStateMachine: Disconnected process message: 9
,09-06 19:10:00.357  7549  7581 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 19:10:00.357  3063  3063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:10:00.357  1015  1313 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:10:00.357  1015  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:10:00.357  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:00.357  1015  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.357  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:10:00.367   282   795 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-06 19:10:00.367   282   795 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 19:10:00.367   282   795 V voice   : voice_set_parameters: exit with code(-2)
09-06 19:10:00.367   282   795 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 19:10:00.367   282   795 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 19:10:00.367   282   795 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:10:00.367   282   795 V audio_hw_primary: adev_set_parameters: exit
09-06 19:10:00.367  7549  7581 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 19:10:00.387  3063  3063 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:10:00.387  3063  3063 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:10:00.387  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:10:00.387  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:10:00.397  7549  7549 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2106339
09-06 19:10:00.397  7549  7549 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:10:00.397  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:10:00.397  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:10:00.397  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:00.397  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.397  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:10:00.417  1980  1980 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:10:00.417  1015  1313 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:10:00.417  1015  1313 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:10:00.417  1015  1313 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:00.417  1015  1313 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:10:00.417  1015  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:10:00.427  1015  1486 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:10:00.427  1980  7653 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:10:00.427  1980  1980 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:10:00.437  1015  1718 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:10:00.437  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:00.437  1015  1718 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:10:00.437  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:10:00.447  7549  7654 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:10:00.447  7549  7654 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:10:00.447  7549  7654 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-06 19:10:00.447  7549  7654 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:10:00.447  7549  7654 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:10:00.447  7549  7654 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e7db1fd
,09-06 19:10:00.447  7549  7654 D BluetoothSocket: channel: 12
09-06 19:10:00.447  7549  7654 I BtOppRfcommListener: Accept thread started.
,09-06 19:10:00.457  1015  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:10:00.457  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:00.457  1015  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:10:00.457  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:10:00.467  1980  7653 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 19:10:00.517  1015  1042 D Tethering: interfaceAdded wlan0
,09-06 19:10:00.527  1015  1128 E Tethering: No numeric data
09-06 19:10:00.527  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:10:00.527  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:10:00.527  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:10:00.527  1015  1128 D Tethering: clearTetheredNotification()
09-06 19:10:00.527  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.527  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:00.527  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:10:00.527  1015  1128 D Tethering: InitialState.processMessage what=4
,09-06 19:10:00.537  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:00.537  1015  1128 E Tethering: No numeric data
,09-06 19:10:00.537  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:10:00.537  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:10:00.537  1015  1128 D Tethering: clearTetheredNotification()
09-06 19:10:00.537  1177  1177 D HotspotTile: updateTetherState():false, false
09-06 19:10:00.537  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:00.537  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:10:00.537  1177  1177 D HotspotTile: updateTetherState():false, false
09-06 19:10:00.537  1015  1042 D Tethering: interfaceAdded p2p0
,09-06 19:10:00.537  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-06 19:10:00.547  1015  1121 V NetworkStats: performPollLocked() took 19ms
09-06 19:10:00.547  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:00.547  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:10:00.557  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:10:00.557  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:10:00.557  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.557  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.557   277   921 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-06 19:10:00.557  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.557   277   921 D SoftapController: Softap fwReload - Ok
09-06 19:10:00.557  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:00.557  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:00.557   277   921 D CommandListener: Setting iface cfg
09-06 19:10:00.557   277   921 D CommandListener: Trying to bring down wlan0
09-06 19:10:00.557  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:10:00.557   277   921 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:10:00.567  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.567  1015  1121 V NetworkStats: performPollLocked() took 8ms
,09-06 19:10:00.567  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.567  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:00.567  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
,09-06 19:10:00.617  7656  7656 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-06 19:10:00.617  7656  7656 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:10:00.617  7656  7656 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 19:10:00.627  7656  7656 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-06 19:10:00.627   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7656
09-06 19:10:00.627   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:10:00.637  7656  7656 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
09-06 19:10:00.637  7656  7656 I wpa_supplicant: ssSupport state is = 1
09-06 19:10:00.637  7656  7656 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:10:00.637  7656  7656 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-06 19:10:00.637   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7656
,09-06 19:10:00.637   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-06 19:10:00.667  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-06 19:10:00.677  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 19:10:00.677  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:10:00.677  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:00.677  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:00.677  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:00.677  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:00.687  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:10:00.687  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2),
09-06 19:10:00.687  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:10:00.687  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,09-06 19:10:00.697  1177  1177 D HotspotTile: onReceive : 2, 0
,09-06 19:10:00.697  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:10:00.697  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:00.697  1015  1531 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:10:00.697  1015  1531 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:00.707  1015  1531 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:10:00.707  1015  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:10:00.707  1015  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:00.707  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:10:00.707  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 19:10:00.707  6551  6551 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:10:00.707  6551  6551 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-06 19:10:00.717  1602  1602 I Hs20UtilService: Starting #19
09-06 19:10:00.717  1602  1637 I Hs20UtilService: Message received 5011
,09-06 19:10:00.827   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-06 19:10:00.827  7656  7656 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-06 19:10:00.867  7656  7656 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-06 19:10:00.867  7656  7656 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:10:00.877  7656  7656 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 19:10:00.877   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7656
09-06 19:10:00.877   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:10:00.877  7656  7656 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,09-06 19:10:00.877  7656  7656 I wpa_supplicant: ssSupport state is = 1
09-06 19:10:00.877  7656  7656 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:00.877  7656  7656 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:00.877  7656  7656 E wpa_supplicant: SIM READ ERROR
,09-06 19:10:00.877  7656  7656 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:00.877  7656  7656 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:00.877  7656  7656 E wpa_supplicant: SIM READ ERROR
09-06 19:10:00.877  7656  7656 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:10:00.877  7656  7656 I wpa_supplicant: wpa_default_ap_write_once,
,09-06 19:10:00.877  7656  7656 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:10:00.887  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:10:00.877  7656  7656 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:00.877  7656  7656 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 19:10:00.877  7656  7656 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:00.877  7656  7656 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:00.887  7656  7656 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:10:00.887  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:00.887  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:10:00.997  7656  7656 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-06 19:10:01.187  7656  7656 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:10:01.187  7656  7656 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:10:01.197  7656  7656 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-06 19:10:01.197   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7656
09-06 19:10:01.197   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:10:01.197  7656  7656 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:10:01.197  7656  7656 I wpa_supplicant: ssSupport state is = 1
09-06 19:10:01.197  7656  7656 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:10:01.197  7656  7656 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-06 19:10:01.217  7656  7656 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
09-06 19:10:01.217   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7656,
09-06 19:10:01.217   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:10:01.217  7656  7656 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:10:01.217  7656  7656 I wpa_supplicant: ssSupport state is = 1,
09-06 19:10:01.217  7656  7656 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:01.217  7656  7656 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:01.217  7656  7656 E wpa_supplicant: SIM READ ERROR
09-06 19:10:01.217  7656  7656 I wpa_supplicant: wpa_default_ap_write_once,
09-06 19:10:01.217  7656  7656 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:10:01.217  7656  7656 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:10:01.217  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
09-06 19:10:01.217  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:10:01.217  1015  1042 D Tethering: interfaceStatusChanged p2p0, false,
,09-06 19:10:01.227  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:10:01.227  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:10:01.227  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,09-06 19:10:01.267   325   325 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-06 19:10:01.267  7656  7656 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-06 19:10:01.267  7656  7656 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:10:01.357  7656  7656 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-06 19:10:01.357  7656  7656 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-06 19:10:01.357  7656  7656 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:10:01.357  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,09-06 19:10:01.367  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-06 19:10:01.367  7656  7656 I wpa_supplicant: HOTSPOT20_ENABLE called
09-06 19:10:01.367  7656  7656 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-06 19:10:01.367  7656  7656 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:01.367  7656  7656 E wpa_supplicant: SIM READ ERROR,
,09-06 19:10:01.367  7656  7656 I wpa_supplicant: Blacklist: Clear (all) ,
,09-06 19:10:01.387  7656  7656 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-06 19:10:01.397  7656  7656 I wpa_supplicant: Skip scan - bUseNetwork false,
09-06 19:10:01.397  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:01.397  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:10:01.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:01.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:01.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:01.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:01.397  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:10:01.397  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:10:01.397  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3),
09-06 19:10:01.407  1177  1662 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
09-06 19:10:01.407  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:10:01.407  1177  1177 D HotspotTile: onReceive : 3, 0
,09-06 19:10:01.407  3063  3063 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:10:01.417  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:01.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:01.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:01.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:01.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:01.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:01.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:01.417  6750  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:01.417  1015  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:01.417  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:01.417  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:01.417  1015  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:10:01.417  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:01.417  1602  1602 I Hs20UtilService: Starting #20
,09-06 19:10:01.417  1602  1637 I Hs20UtilService: Message received 5011
,09-06 19:10:01.417  1015  1124 E WifiConfigStore: Not a HS20
,09-06 19:10:01.427  6750  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:01.427  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:10:01.427  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:10:01.427  6551  6551 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 19:10:01.427  6551  6551 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:10:01.427  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-06 19:10:01.427  6551  6551 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:10:01.437  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 19:10:01.437  7656  7656 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 19:10:01.437  7656  7656 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 19:10:01.437  7656  7656 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:10:01.437  7656  7656 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:10:01.437  7656  7656 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:10:01.437  7656  7656 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:10:01.437  7656  7656 I wpa_supplicant: First Scan Start
09-06 19:10:01.437  7656  7656 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:10:01.447  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
,09-06 19:10:01.447  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:10:01.447  1015  1124 I WifiNative-HAL: startHal
09-06 19:10:01.447  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d5f388c
09-06 19:10:01.447  1015  1124 I WifiNative-HAL: Could not start hal
,09-06 19:10:01.447  6998  6998 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:10:01.457  1015  1124 E WifiNative-wlan0: do suspend true
,09-06 19:10:01.457  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 19:10:01.457  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-06 19:10:01.457   277   921 D CommandListener: Setting iface cfg
09-06 19:10:01.457   277   921 D CommandListener: Trying to bring up p2p0
,09-06 19:10:01.457  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:10:01.457  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:10:01.457  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-06 19:10:01.457  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:10:01.457  1015  1147 I WifiNative-HAL: startHal
09-06 19:10:01.457  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9eab19bc
09-06 19:10:01.457  1015  1147 I WifiNative-HAL: Could not start hal
09-06 19:10:01.457  1015  1147 E WifiScanningService: could not start HAL
,09-06 19:10:01.457  1015  1148 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:10:01.457  1015  1123 D WifiP2pService: P2pEnablingState
09-06 19:10:01.457  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-06 19:10:01.457  1015  1123 D WifiP2pService: P2p socket connection successful
09-06 19:10:01.457  1015  1123 D WifiP2pService: P2pEnabledState
09-06 19:10:01.457  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:10:01.457  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:10:01.457  1015  1124 E WifiNative-wlan0: invaild command id : 215,
,09-06 19:10:01.457  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:10:01.457  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:10:01.457  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:10:01.457  1015  1124 E WifiNative-wlan0: invaild command id : 215
09-06 19:10:01.457  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-06 19:10:01.467  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:10:01.467  7656  7656 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:10:01.467  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 19:10:01.467  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:10:01.467  7656  7656 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 19:10:01.467  1015  1045 D WifiDisplayController: disconnect
09-06 19:10:01.467  1015  1045 D WifiDisplayController: updateConnection
09-06 19:10:01.467  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:10:01.467  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:10:01.467  7656  7656 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-06 19:10:01.467  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,09-06 19:10:01.467  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:01.467  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:10:01.477  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:10:01.477  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:10:01.477  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
09-06 19:10:01.477  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:10:01.477  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:10:01.477  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-06 19:10:01.477  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:10:01.477  1015  1718 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:10:01.477  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:10:01.477  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:10:01.477  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
09-06 19:10:01.477  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  secondary type: null
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  wps: 0
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  grpcapab: 0
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  devcapab: 0
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  status: 3
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  wfdInfo: null
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  groupownerAddress: null
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  GOdeviceName: null
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  interfaceAddress: 
09-06 19:10:01.477  1015  1045 D WifiDisplayController:  SConnectInfo : null
,09-06 19:10:01.477  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:01.477  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:10:01.487  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:10:01.487  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:10:01.487  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:10:01.487  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-06 19:10:01.487  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:10:01.487  3063  3880 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:10:01.487  7346  7346 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:10:01.497  7346  7346 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:10:01.497  7346  7346 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:10:01.497  7361  7361 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:10:01.507  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 19:10:01.507  1015  1123 D WifiP2pService: InactiveState
,09-06 19:10:01.507  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:10:01.507  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:10:01.507  7656  7656 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:10:01.507  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:10:01.507  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:10:01.527  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-06 19:10:01.527  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:10:01.527  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:10:02.187  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:02.187  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:02.187  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:02.187  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:02.187  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:02.187  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:02.187  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:02.187  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:02.197  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:02.197  6750  6803 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 19:10:02.197  6750  6803 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 19:10:02.197  6750  6803 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a738ca9 Bundle[{}]
,09-06 19:10:02.197  6750  6803 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:10:02.197  6750  6803 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 19:10:02.207  6750  6803 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:10:02.207  6750  6803 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-06 19:10:02.207  6750  6803 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-06 19:10:02.207  6750  6803 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:10:02.207  6750  6803 I System.out: Running OutgoingSocketThread
,09-06 19:10:02.207  6750  7664 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1345)
,09-06 19:10:02.217  6750  7664 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48467
,09-06 19:10:02.217  6750  7664 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 19:10:02.677  7656  7656 I wpa_supplicant: nl80211: Received scan results (22 BSSes),
09-06 19:10:02.677  7656  7656 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:10:02.677  7656  7656 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-06 19:10:02.677  7656  7656 I wpa_supplicant: Trying to associate with  'G700'
09-06 19:10:02.677  7656  7656 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-06 19:10:02.677  7656  7656 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-06 19:10:02.677  1015  7661 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,09-06 19:10:02.697  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-06 19:10:02.697  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:10:02.807  7656  7656 E wpa_supplicant: Cmd 35605 not handled
,09-06 19:10:02.807  7656  7656 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-06 19:10:02.817  7656  7656 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,09-06 19:10:02.817  7656  7656 I wpa_supplicant: Associated with F4.99.3E
09-06 19:10:02.817  7656  7656 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-06 19:10:02.817  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:10:02.817  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.817  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:10:02.817  7656  7656 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 19:10:02.817  7656  7656 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:10:02.817  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.817  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:10:02.817  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:10:02.817  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:10:02.817  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:10:02.817  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:10:02.827  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,09-06 19:10:02.827  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:10:02.827  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-06 19:10:02.827  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:10:02.827  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:10:02.827  7656  7656 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-06 19:10:02.827  7656  7656 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-06 19:10:02.827  7656  7656 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-06 19:10:02.827  7656  7656 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-06 19:10:02.827  1015  1128 E Tethering: No numeric data
09-06 19:10:02.827  7656  7656 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:10:02.827  7656  7656 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 19:10:02.827  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 19:10:02.827  7656  7656 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 19:10:02.827  1015  1128 D Tethering: clearTetheredNotification()
09-06 19:10:02.827  7656  7656 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 19:10:02.827  7656  7656 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-06 19:10:02.827  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:10:02.827  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:10:02.837  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:10:02.837  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:10:02.837  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:02.837  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
09-06 19:10:02.837  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-06 19:10:02.837  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:10:02.837  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:10:02.837  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
09-06 19:10:02.837  1177  1177 D HotspotTile: updateTetherState():false, false
,09-06 19:10:02.847  1015  1121 V NetworkStats: performPollLocked() took 8ms
,09-06 19:10:02.847  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:02.847  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:02.847  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:02.847  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-06 19:10:02.857  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 19:10:02.857  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:10:02.857  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:10:02.857  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.857  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.857  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.857  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.867  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 19:10:02.867  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 19:10:02.867  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 19:10:02.867  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:10:02.867  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:10:02.867  1015  5159 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:10:02.867  1015  5159 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:02.867  1015  5159 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:02.867  1015  5159 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:02.867  1015  5159 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:02.877  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:10:02.877  1602  1602 I Hs20UtilService: Starting #21
,09-06 19:10:02.877  1602  1637 I Hs20UtilService: Message received 5007
,09-06 19:10:02.887  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:10:02.887  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:10:02.887  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:10:02.887  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:10:02.887  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:10:02.887  3063  3063 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:10:02.887  3063  3880 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:10:02.887   277   921 D CommandListener: Setting iface cfg
,09-06 19:10:02.897  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 3
,09-06 19:10:02.897  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:10:02.897  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:10:02.907  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:10:02.907  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:02.907  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.907  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.907  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:02.907  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:02.917  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:10:02.917  1015  1124 D SecContentProvider2: mCursor = null
,09-06 19:10:02.917  1015  1124 E WifiNative-wlan0: do suspend false
,09-06 19:10:02.927  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:10:02.927  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:10:03.147  7668  7668 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:10:03.147  7668  7668 I dhcpcd  : version 5.5.6 starting
,09-06 19:10:03.147  7668  7668 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-06 19:10:03.197  7668  7668 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-06 19:10:03.197  7668  7668 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-06 19:10:03.197  7668  7668 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-06 19:10:03.197  7668  7668 I dhcpcd  : bssid match
09-06 19:10:03.197  7668  7668 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-06 19:10:03.207  6750  6803 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1346),
09-06 19:10:03.207  6750  6803 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1346)
,09-06 19:10:03.217  6750  6803 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1351)
,09-06 19:10:03.217  6750  6803 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-06 19:10:03.217  6750  6803 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1352)
,09-06 19:10:03.217  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:03.217  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a50fcb added. We now have 2 listener(s)
,09-06 19:10:03.217  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:10:03.217  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.217  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-06 19:10:03.217  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.217  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3419c3a8 added. We now have 9 listener(s)
09-06 19:10:03.217  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.217  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.217  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:03.227  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-06 19:10:03.227  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.227  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.227  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.227  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.227  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.227  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.227  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:10:03.227  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:10:03.227  6750  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:10:03.227  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.227  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12706666 added. We now have 3 listener(s)
09-06 19:10:03.227  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.227  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.227  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
09-06 19:10:03.227  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.227  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:03.227  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.227  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31f2dda7 added. We now have 10 listener(s)
09-06 19:10:03.227  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.227  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:03.227  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.227  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:03.227  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.227  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.227  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.227  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.227  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a50fcb removed from the list
09-06 19:10:03.227  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.227  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3419c3a8 removed from the list
,09-06 19:10:03.227  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:03.227  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.227  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 19:10:03.227  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.227  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.227  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.227  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:03.227  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3419c3a8 not in the list
09-06 19:10:03.227  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.227  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.227  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.227  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.227  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.227  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31f2dda7 removed from the list
09-06 19:10:03.227  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.227  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.227  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.227  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.237  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12706666 removed from the list
09-06 19:10:03.237  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.237  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a1b7254 added. We now have 2 listener(s)
,09-06 19:10:03.237  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:10:03.237  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.237  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-06 19:10:03.237  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.237  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b7d75fd added. We now have 9 listener(s)
09-06 19:10:03.237  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.237  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.237  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:03.237  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.237  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.237  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.237  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.237  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.237  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.237  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.237  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.237  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:10:03.237  6750  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:10:03.237  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.237  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1765ad43 added. We now have 3 listener(s)
,09-06 19:10:03.247  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.247  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:10:03.247  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.247  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.247  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.247  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e75fc0 added. We now have 10 listener(s)
09-06 19:10:03.247  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.247  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.247  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
09-06 19:10:03.247  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:10:03.247  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.247  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:10:03.247  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.247   287   287 E SMD     : DCD OFF
,09-06 19:10:03.247  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:10:03.257  7668  7668 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
09-06 19:10:03.257  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:10:03.257  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:10:03.257  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:10:03.257  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:10:03.257  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:10:03.257  7549  7636 D BtGatt.GattService: registerClient() - UUID=c67d95af-184a-4f5e-a0e9-abb05dbfc442
,09-06 19:10:03.297  7549  7575 D BtGatt.GattService: onClientRegistered() - UUID=c67d95af-184a-4f5e-a0e9-abb05dbfc442, clientIf=6
,09-06 19:10:03.307  6750  6758 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:10:03.307  7549  7576 D BtGatt.GattService: start scan with filters
,09-06 19:10:03.307  7549  7580 D BtGatt.ScanManager: handling starting scan
,09-06 19:10:03.307  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:10:03.307  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:10:03.307  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:10:03.307  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,09-06 19:10:03.307  7549  7580 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2106339
,09-06 19:10:03.317  7549  7575 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 19:10:03.317  7668  7668 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
09-06 19:10:03.317  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.317  7549  7580 D BtGatt.ScanManager: allow scan with filters
09-06 19:10:03.317  7549  7580 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:10:03.317  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:10:03.317  7549  7580 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-06 19:10:03.317  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:10:03.317  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:03.327  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:10:03.327  7549  7575 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:10:03.327  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.327  7549  7580 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:10:03.327  7549  7580 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:10:03.327  6750  6803 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:10:03.327  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.327  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:10:03.327  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:03.327  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:10:03.327  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:10:03.327  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:10:03.327  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:10:03.327  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:10:03.337  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 19:10:03.337  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:10:03.337  7549  7575 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:10:03.337  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.337  7549  7636 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:03.347  7549  7575 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-06 19:10:03.347  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.347  7549  7637 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:10:03.347  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:10:03.357  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:10:03.357  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:03.357  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:10:03.357  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:10:03.357  7549  7580 D BtGatt.ScanManager: filter size is 1
,09-06 19:10:03.357  7549  7580 D BtGatt.ScanManager: delete FilterIndex - 3
,09-06 19:10:03.357  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-06 19:10:03.357  7549  7575 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:10:03.357  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.357  7549  7580 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:10:03.357  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:10:03.357  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:10:03.357  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:10:03.357  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.367  7549  7575 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:10:03.367  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.367  7549  7580 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:10:03.367  7549  7575 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
09-06 19:10:03.367  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.367  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.367  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.367  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:03.377  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-06 19:10:03.377  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.377  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:03.377  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.377  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 19:10:03.377  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:03.377  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.377  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a1b7254 removed from the list
09-06 19:10:03.377  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.377  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b7d75fd removed from the list,
09-06 19:10:03.377  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:03.377  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.377  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.377  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.387  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:10:03.387  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.387  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:03.387  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b7d75fd not in the list
09-06 19:10:03.387  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.387  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-06 19:10:03.387  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.387  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.387  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.387  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e75fc0 removed from the list
09-06 19:10:03.387  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.387  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.387  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.387  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.387  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1765ad43 removed from the list
09-06 19:10:03.387  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:03.387  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c2b7ec added. We now have 2 listener(s)
,09-06 19:10:03.387  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:10:03.387  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.387  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.387  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,09-06 19:10:03.387  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307a67b5 added. We now have 9 listener(s)
09-06 19:10:03.387  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.397  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.417  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:03.437  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.437  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.437  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.437  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.437  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.437  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.437  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.437  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.437  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-06 19:10:03.437  6750  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:10:03.437  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:03.437  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22fd81bb added. We now have 3 listener(s)
,09-06 19:10:03.437  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.447  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:10:03.447  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.447  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.447  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.447  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351966d8 added. We now have 10 listener(s)
09-06 19:10:03.447  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.447  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:03.447  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.447  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.447  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:10:03.447  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:10:03.447  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:03.447  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:10:03.447  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:10:03.467  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-06 19:10:03.477  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:10:03.477  1015  4386 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-06 19:10:03.477  1015  4386 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:10:03.477  1015  4386 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:10:03.477  1015  4386 D BatteryService: stay LED for fully charged
09-06 19:10:03.477  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,09-06 19:10:03.477  1015  1015 I MotionRecognitionService: Plugged,
09-06 19:10:03.477  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:10:03.487  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:10:03.487  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:10:03.487  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:10:03.487  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:10:03.487  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:10:03.497  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:10:03.497  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-06 19:10:03.497  7549  7637 D BtGatt.GattService: registerClient() - UUID=64822238-1637-4c38-be44-24f796c56ba3
,09-06 19:10:03.507  7549  7549 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:10:03.507  7549  7581 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:10:03.517  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
09-06 19:10:03.517  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:10:03.517  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:10:03.517  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
09-06 19:10:03.517  1177  1177 D SViewCoverView: level :100 plugged : 2
,09-06 19:10:03.537  7549  7575 D BtGatt.GattService: onClientRegistered() - UUID=64822238-1637-4c38-be44-24f796c56ba3, clientIf=6
,09-06 19:10:03.537  6750  6758 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:10:03.537  7549  7557 D BtGatt.GattService: start scan with filters
09-06 19:10:03.537  7549  7580 D BtGatt.ScanManager: handling starting scan
09-06 19:10:03.537  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:10:03.537  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:10:03.537  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:10:03.537  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
09-06 19:10:03.537  7549  7575 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 19:10:03.537  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.537  7549  7580 D BtGatt.ScanManager: allow scan with filters
09-06 19:10:03.537  7549  7580 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:10:03.537  7549  7580 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
09-06 19:10:03.537  7549  7575 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:10:03.537  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.537  7549  7580 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:10:03.537  7549  7580 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:10:03.547  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:10:03.547  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:10:03.547  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:10:03.547  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:10:03.547  7549  7575 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:10:03.547  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.547  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
09-06 19:10:03.547  6750  6803 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-06 19:10:03.547  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:10:03.547  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.547  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:03.547  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.547  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.547  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:10:03.547  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.547  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c2b7ec removed from the list
09-06 19:10:03.547  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.547  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307a67b5 removed from the list
09-06 19:10:03.547  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:03.547  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:03.547  7549  7575 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:10:03.547  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.547  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.547  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:10:03.547  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.547  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.557  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.557  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.557  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:03.557  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307a67b5 not in the list
09-06 19:10:03.557  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:10:03.557  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:10:03.557  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:10:03.557  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:10:03.557  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:10:03.557  7549  7576 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:03.557  7549  7637 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:10:03.557  7549  7580 D BtGatt.ScanManager: filter size is 1
,09-06 19:10:03.557  7549  7580 D BtGatt.ScanManager: delete FilterIndex - 4
,09-06 19:10:03.557  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:10:03.557  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 19:10:03.557  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:03.557  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
09-06 19:10:03.557  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:10:03.557  7549  7575 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:10:03.557  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.557  7549  7580 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:10:03.557  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:03.557  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-06 19:10:03.557  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:10:03.557  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:10:03.557  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.567  7549  7575 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:10:03.567  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.567  7549  7580 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:10:03.567  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.567  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.567  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.567  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351966d8 removed from the list
09-06 19:10:03.567  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.567  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.567  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.567  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.567  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22fd81bb removed from the list
,09-06 19:10:03.567  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.567  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@302a1884 added. We now have 2 listener(s)
,09-06 19:10:03.567  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.567  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.567  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:03.567  7549  7575 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:10:03.567  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.567  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:10:03.567  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.567  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.567  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.567  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7cd86d added. We now have 9 listener(s)
09-06 19:10:03.567  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.567  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.567  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:03.577  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.577  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.577  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.577  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.577  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.577  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.577  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.577  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.577  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:03.577  6750  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:10:03.577  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.577  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@173c6d33 added. We now have 3 listener(s)
,09-06 19:10:03.577  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.577  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:03.577  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:10:03.577  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.577  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.577  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.577  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@367238f0 added. We now have 10 listener(s)
09-06 19:10:03.577  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.577  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.577  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:10:03.577  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:10:03.577  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.577  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:10:03.587  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:10:03.587  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:10:03.587  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:10:03.587  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:10:03.587  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:10:03.587  6750  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:10:03.597  7549  7636 D BtGatt.GattService: registerClient() - UUID=916973a7-e29e-4bb4-828f-bc3aaca11a8e
,09-06 19:10:03.637  7549  7575 D BtGatt.GattService: onClientRegistered() - UUID=916973a7-e29e-4bb4-828f-bc3aaca11a8e, clientIf=6
,09-06 19:10:03.637  6750  6759 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:10:03.637  7549  7558 D BtGatt.GattService: start scan with filters
,09-06 19:10:03.637  7549  7580 D BtGatt.ScanManager: handling starting scan
,09-06 19:10:03.637  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:10:03.637  7549  7575 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:10:03.637  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.637  7549  7580 D BtGatt.ScanManager: allow scan with filters
,09-06 19:10:03.637  7549  7580 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:10:03.637  7549  7580 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 19:10:03.637  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:10:03.637  7549  7575 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:10:03.637  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.637  7549  7580 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:10:03.647  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:10:03.647  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:10:03.647  7549  7580 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:10:03.647  7549  7575 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:10:03.647  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.647  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:03.657  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:10:03.657  7549  7575 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:10:03.657  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.657  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:03.657  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:10:03.667  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:03.667  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.667  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:03.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.667  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.667  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:10:03.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.667  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@302a1884 removed from the list
09-06 19:10:03.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.667  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7cd86d removed from the list
09-06 19:10:03.667  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:03.667  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:03.667  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.667  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:10:03.667  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.667  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:10:03.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.667  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7cd86d not in the list
09-06 19:10:03.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:10:03.667  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:10:03.667  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:10:03.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:10:03.667  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:10:03.667  7549  7637 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:03.667  7549  7580 D BtGatt.ScanManager: filter size is 1
,09-06 19:10:03.667  7549  7580 D BtGatt.ScanManager: delete FilterIndex - 5
,09-06 19:10:03.677  7549  7576 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:10:03.677  7549  7575 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:10:03.677  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.677  7549  7580 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:10:03.677  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:10:03.677  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:10:03.677  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:03.677  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:10:03.677  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:10:03.677  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:03.677  7549  7575 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:10:03.677  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.677  7549  7580 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:10:03.677  7549  7575 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:10:03.687  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:10:03.687  6750  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:10:03.687  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:10:03.687  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.687  7549  7575 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.687  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:10:03.687  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:10:03.687  6750  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:03.687  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.687  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:10:03.687  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:03.687  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@367238f0 removed from the list
09-06 19:10:03.687  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:10:03.687  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:03.687  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.687  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:10:03.687  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@173c6d33 removed from the list
,09-06 19:10:03.697  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:03.697  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13d9f41c added. We now have 2 listener(s)
,09-06 19:10:03.697  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:10:03.697  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:03.697  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:03.697  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.697  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d5a825 added. We now have 9 listener(s)
,09-06 19:10:03.697  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.697  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.707  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:03.707  6750  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.707  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.707  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.707  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.707  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.707  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.707  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.707  6750  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.707  6750  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:03.707  6750  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:10:03.717  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.717  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@310e4fab added. We now have 3 listener(s)
,09-06 19:10:03.717  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.717  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.717  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:10:03.717  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:03.717  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.717  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:03.717  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a03608 added. We now have 10 listener(s)
09-06 19:10:03.717  6750  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.717  6750  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:03.717  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.717  6750  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:03.717  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.717  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.717  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:03.717  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.717  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13d9f41c removed from the list
09-06 19:10:03.717  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.717  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d5a825 removed from the list
09-06 19:10:03.717  6750  6803 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:03.717  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.717  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.717  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.717  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:10:03.727  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.727  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.727  6750  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d5a825 not in the list
09-06 19:10:03.727  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.727  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.727  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:10:03.727  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.727  6750  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.727  6750  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a03608 removed from the list
,09-06 19:10:03.727  6750  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.727  6750  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.727  6750  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.727  6750  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:10:03.727  6750  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@310e4fab removed from the list
,09-06 19:10:03.727  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-06 19:10:03.727  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 19:10:03.727  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-06 19:10:03.727  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.727  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:10:03.727  6750  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:10:03.737  6750  7699 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1359, name: My test thread name)
,09-06 19:10:03.737  1015  1124 E WifiNative-wlan0: do suspend true
,09-06 19:10:03.737  6750  7699 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1359, thread name: My test thread name)
,09-06 19:10:03.737  6750  7699 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1359, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:10:03.747  6750  7700 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1361, name: My test thread name)
,09-06 19:10:03.747  6750  7700 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1361, thread name: My test thread name)
,09-06 19:10:03.747  6750  7700 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1361, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:10:03.747  6750  6803 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-06 19:10:03.747  6750  6803 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:10:03.747  6750  6803 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-06 19:10:03.747  6750  6803 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:10:03.747  6750  6803 D com.test.thalitest.ThaliTestRunner: Total duration: 23258 ms
,09-06 19:10:03.747  6750  6803 I jxcore-log: *Native tests were executed*
09-06 19:10:03.747  6750  6803 I jxcore-log: 
,09-06 19:10:03.747  6750  6803 I jxcore-log: Total number of executed tests:  80
09-06 19:10:03.747  6750  6803 I jxcore-log: 
09-06 19:10:03.747  6750  6803 I jxcore-log: Number of passed tests:  80
09-06 19:10:03.747  6750  6803 I jxcore-log: 
09-06 19:10:03.747  6750  6803 I jxcore-log: Number of failed tests:  0
09-06 19:10:03.747  6750  6803 I jxcore-log: 
09-06 19:10:03.747  6750  6803 I jxcore-log: Number of ignored tests:  0
09-06 19:10:03.747  6750  6803 I jxcore-log: 
,09-06 19:10:03.747  6750  6803 I jxcore-log: Total duration:  23258
09-06 19:10:03.747  6750  6803 I jxcore-log: 
09-06 19:10:03.747  6750  6803 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:10:03.747  6750  6803 I jxcore-log: 
,09-06 19:10:03.757  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.757  6750  6803 I jxcore-log: 
09-06 19:10:03.757  6750  6750 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:10:03.757  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.757  6750  6803 I jxcore-log: 
09-06 19:10:03.757  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.757  6750  6803 I jxcore-log: 
09-06 19:10:03.767  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.767  6750  6803 I jxcore-log: 
09-06 19:10:03.767  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.767  6750  6803 I jxcore-log: 
09-06 19:10:03.767  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
09-06 19:10:03.767  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
09-06 19:10:03.767  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.767  6750  6803 I jxcore-log: 
09-06 19:10:03.767  1015  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 19:10:03.767  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.767  6750  6803 I jxcore-log: 
09-06 19:10:03.767  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:03.767  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.767  6750  6803 I jxcore-log: 
09-06 19:10:03.767  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:03.777  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.777  6750  6803 I jxcore-log: 
09-06 19:10:03.777  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.777  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.777  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.777  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.777  1015  1124 E WifiStateMachine: VerifyingLinkState enter
09-06 19:10:03.777  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:03.777  6750  6803 I jxcore-log: 
09-06 19:10:03.777  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.777  6750  6803 I jxcore-log: 
,09-06 19:10:03.777  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.777  6750  6803 I jxcore-log: 
,09-06 19:10:03.777  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 19:10:03.777  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.777  6750  6803 I jxcore-log: 
,09-06 19:10:03.777  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.777  6750  6803 I jxcore-log: 
09-06 19:10:03.777  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-06 19:10:03.777  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.777  6750  6803 I jxcore-log: 
,09-06 19:10:03.777  1015  1126 D ConnectivityService: Adding iface wlan0 to network 504
,09-06 19:10:03.777  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.777  6750  6803 I jxcore-log: 
09-06 19:10:03.777  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.777  6750  6803 I jxcore-log: 
09-06 19:10:03.777  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.777  6750  6803 I jxcore-log: 
,09-06 19:10:03.777  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.777  6750  6803 I jxcore-log: 
,09-06 19:10:03.787  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.787  6750  6803 I jxcore-log: 
09-06 19:10:03.787  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.787  6750  6803 I jxcore-log: 
09-06 19:10:03.787  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.787  6750  6803 I jxcore-log: 
09-06 19:10:03.787  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.787  6750  6803 I jxcore-log: 
09-06 19:10:03.787  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.787  6750  6803 I jxcore-log: 
09-06 19:10:03.787  1015  1141 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-06 19:10:03.787  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.787  6750  6803 I jxcore-log: 
09-06 19:10:03.787  1015  1141 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:10:03.787  1015  1141 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:10:03.787  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.787  6750  6803 I jxcore-log: 
09-06 19:10:03.787  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.787  6750  6803 I jxcore-log: 
,09-06 19:10:03.787  1015  1141 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:10:03.787  1015  1141 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-06 19:10:03.797  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:03.797  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:03.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.797  1015  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-06 19:10:03.797  1015  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-06 19:10:03.797  1015  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-06 19:10:03.797  1015  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:10:03.797  1015  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,09-06 19:10:03.807  1015  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-06 19:10:03.807  1015  1126 D ConnectivityService: LTETest block dns file not exists
09-06 19:10:03.807  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.807  1015  1126 V NetworkStats: updateIfacesLocked()
,09-06 19:10:03.807  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:10:03.807  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:03.807  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,09-06 19:10:03.807  1015  1126 V NetworkStats: performPollLocked() took 7ms
09-06 19:10:03.807  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:03.817  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-06 19:10:03.817  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-06 19:10:03.817  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.817  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:03.817  1015  5159 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:03.817  1015  5159 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:10:03.817  1015  5159 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:03.817  1015  5159 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:03.817  1015  5159 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:03.817  1602  1602 I Hs20UtilService: Starting #22
,09-06 19:10:03.817  1602  1637 I Hs20UtilService: Message received 5007
,09-06 19:10:03.817  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 19:10:03.817  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:10:03.817  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.817  1015  1126 V NetworkStats: updateIfacesLocked()
09-06 19:10:03.817  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:10:03.817  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 19:10:03.817  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:10:03.817  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:03.817  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:03.817  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:10:03.827  1015  1126 V NetworkStats: performPollLocked() took 5ms
09-06 19:10:03.827  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:03.827  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:10:03.827  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:10:03.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.827  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
09-06 19:10:03.827  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
09-06 19:10:03.827  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,09-06 19:10:03.837  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 19:10:03.837  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:10:03.837  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.837  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.837  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.837  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.847  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:10:03.847  3063  3063 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 19:10:03.847  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.847  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:03.847  1015  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504],
09-06 19:10:03.847  1015  7665 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:10:03.847  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-06 19:10:03.847  1015  7665 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-06 19:10:03.847  1015  1126 D ConnectivityService:    accepting network in place of null
09-06 19:10:03.847  1015  7665 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:10:03.847  1015  7665 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-06 19:10:03.857  1015  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-06 19:10:03.847  1015  7665 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:10:03.857  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:10:03.847  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 19:10:03.847  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:10:03.847  1468  1468 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-06 19:10:03.847  1468  1468 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:10:03.857  1015  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:10:03.857   277   917 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:10:03.857   277   917 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-06 19:10:03.857  1015  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-06 19:10:03.857  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 19:10:03.857  1015  1128 D Tethering: MasterInitialState.processMessage what=3
09-06 19:10:03.857  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-06 19:10:03.857  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.857  1015  1121 V NetworkStats: updateIfacesLocked()
09-06 19:10:03.857  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:10:03.857  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-06 19:10:03.857  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:10:03.857  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-06 19:10:03.857  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:10:03.857  1015  1121 V NetworkStats: performPollLocked() took 4ms
09-06 19:10:03.857  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:10:03.857  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:10:03.857  1177  1177 D StatusBar.NetworkController: updateDataNetType()
09-06 19:10:03.857  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 19:10:03.857  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-06 19:10:03.857  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.867  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:03.867  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.867  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.867  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.867  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-06 19:10:03.867  1177  1636 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:10:03.867  4796  6812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
,09-06 19:10:03.867  6750  6750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:10:03.867  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:03.867  6750  6803 I jxcore-log: 
,09-06 19:10:03.877  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:10:03.877  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-06 19:10:03.877  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-06 19:10:03.877  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:03.877  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:10:03.877  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.877  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:03.877  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.877  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.877  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.877  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.877  1015  1486 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:03.877  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:03.877  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:03.877  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:03.877  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:10:03.877  1602  1602 I Hs20UtilService: Starting #23
,09-06 19:10:03.887  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:10:03.887  3063  3063 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:10:03.887  1602  1637 I Hs20UtilService: Message received 5007
09-06 19:10:03.887  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-06 19:10:03.887  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:10:03.887  3063  3063 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-06 19:10:03.887  3063  3063 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 19:10:03.897  1015  4386 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:03.897  1015  4386 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:03.897  1015  4386 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:03.897  1015  4386 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:03.897  1015  4386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:03.897  3063  3063 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:10:03.897  3063  3063 I NearbySettings: MountReceiver.onReceive - Keep current state
09-06 19:10:03.907  1602  1602 I Hs20UtilService: Starting #24,
09-06 19:10:03.907  1602  1637 I Hs20UtilService: Message received 5007
,09-06 19:10:03.907  1015  5159 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-06 19:10:03.907  1015  1502 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-06 19:10:03.907  1015  1502 D SecContentProvider2: mCursor = null
,09-06 19:10:03.917  1015  1488 D SecContentProvider2: uri = 15 selection = getToastGravity
09-06 19:10:03.917  1015  1488 D SecContentProvider2: mCursor = null
,09-06 19:10:03.917  1015  4382 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-06 19:10:03.917  1015  4382 D SecContentProvider2: mCursor = null
,09-06 19:10:03.917  1015  1718 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-06 19:10:03.917  1015  1718 D SecContentProvider2: mCursor = null
,09-06 19:10:03.917  1015  1518 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,09-06 19:10:03.917  1015  1518 D SecContentProvider2: mCursor = null
,09-06 19:10:03.917  1015  4386 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-06 19:10:03.917  1015  4386 D SecContentProvider2: mCursor = null
,09-06 19:10:03.947   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-06 19:10:03.967  1015  1027 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015,
,09-06 19:10:03.967  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,09-06 19:10:04.037  7704  7704 D AndroidRuntime: 
09-06 19:10:04.037  7704  7704 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-06 19:10:04.037  7704  7704 D AndroidRuntime: CheckJNI is OFF
,09-06 19:10:04.037  7704  7704 D AndroidRuntime: readGMSProperty: start
09-06 19:10:04.037  7704  7704 D AndroidRuntime: readGMSProperty: already setted!!
09-06 19:10:04.037  7704  7704 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 19:10:04.037  7704  7704 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:10:04.037  7704  7704 D AndroidRuntime: readGMSProperty: end
09-06 19:10:04.037  7704  7704 D AndroidRuntime: addProductProperty: start
,09-06 19:10:04.067  6750  6750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-06 19:10:04.067  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:04.067  6750  6803 I jxcore-log: 
,09-06 19:10:04.187  7704  7704 E AffinityControl: AffinityControl: registerfunction enter,
,09-06 19:10:04.187  6750  6750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-06 19:10:04.187  6750  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:04.187  6750  6803 I jxcore-log: 
,09-06 19:10:04.207  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:10:04.207  1015  1126 V NetworkStats: updateIfacesLocked()
09-06 19:10:04.207  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:04.207  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:10:04.207  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:10:04.207  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:10:04.207  1015  1126 V NetworkStats: performPollLocked() took 3ms,
09-06 19:10:04.207  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 19:10:04.207  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:04.217  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-06 19:10:04.207  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:04.217  4796  6812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 19:10:04.217  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-06 19:10:04.217  1177  1636 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 19:10:04.217  7704  7704 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 19:10:04.217  1177  1636 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 19:10:04.217  4796  6812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 19:10:04.227  1015  4387 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-06 19:10:04.227  1015  4387 D PackageManager: START PACKAGE DELETE: observer{307458264}
09-06 19:10:04.227  1015  4387 D PackageManager: pkg{<packageName>}
09-06 19:10:04.227  1015  4387 D PackageManager: user{0}
09-06 19:10:04.227  1015  4387 D PackageManager: caller{2000}
09-06 19:10:04.227  1015  4387 D PackageManager: flags{2}
09-06 19:10:04.227  1015  4387 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,09-06 19:10:04.227  1015  4387 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,09-06 19:10:04.227  1015  4387 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-06 19:10:04.227  1015  4387 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-06 19:10:04.237  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-06 19:10:04.237  1015  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-06 19:10:04.237  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-06 19:10:04.237  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
09-06 19:10:04.237  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-06 19:10:04.237  1015  1054 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-06 19:10:04.257  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,09-06 19:10:04.257  1015  1040 I ActivityManager: Killing 6750:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-06 19:10:04.347  1015  1054 W PackageSettings: Skipping PackageSetting{2d0a10e4 com.example.hello/10168} due to missing metadata
,09-06 19:10:04.357  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:04.367  1015  1518 I WindowState: WIN DEATH: Window{3798c9fd u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-06 19:10:04.367   257   443 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-06 19:10:04.367   257   443 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-06 19:10:04.367  1015  1518 D InputDispatcher: Focus left window: 6750
,09-06 19:10:04.377  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{3584791d u0 com.test.thalitest/.MainActivity t2}
,09-06 19:10:04.387  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:10:04.387  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:10:04.387  1015  1718 W ActivityManager: Spurious death for ProcessRecord{18f90c31 6750:com.test.thalitest/u0a171}, curProc for 6750: null
,09-06 19:10:04.397  1015  1054 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-06 19:10:04.397  1015  1054 I ActivityManager:   Force finishing activity ActivityRecord{3584791d u0 com.test.thalitest/.MainActivity t2 f}
,09-06 19:10:04.397  1015  1054 W ActivityManager: Duplicate finish request for ActivityRecord{3584791d u0 com.test.thalitest/.MainActivity t2 f}
,09-06 19:10:04.427  1015  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-06 19:10:04.487  2637  2637 I art     : Explicit concurrent mark sweep GC freed 19569(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 816us total 45.195ms
,09-06 19:10:04.487  1015  1040 D InputDispatcher: Focused application released
,09-06 19:10:04.487  1015  1040 D FocusedStackFrame: Set to : 0
,09-06 19:10:04.487  4796  4796 I art     : Explicit concurrent mark sweep GC freed 22841(1376KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.322ms total 89.613ms
,09-06 19:10:04.497  1015  1040 W ActivityManager: mDVFSHelper.acquire()
,09-06 19:10:04.497  1015  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-06 19:10:04.517  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:04.537  1495  1495 D Launcher: onRestart, Launcher: 72815327
,09-06 19:10:04.567  1015  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:10:04.577  1015  1486 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 19:10:04.577  1015  1486 D SecContentProvider2: mCursor = null
,09-06 19:10:04.577  1963  1963 E SamsungIME: mOCRHelper is null
,09-06 19:10:04.577  1980  2149 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:10:04.587  1468  1468 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:10:04.587  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,09-06 19:10:04.597  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-06 19:10:04.597  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-06 19:10:04.597  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-06 19:10:04.597  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-06 19:10:04.617  1015  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-06 19:10:04.617  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:04.617  1015  1121 V NetworkStats: performPollLocked(flags=0x3)
,09-06 19:10:04.627  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
09-06 19:10:04.627  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-06 19:10:04.627  1015  1039 W TextServicesManagerService: no available spell checker services found
,09-06 19:10:04.627  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:04.627  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:04.637  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 19:10:04.647  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,09-06 19:10:04.647  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:04.647  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:04.647  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.647  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:04.647  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-06 19:10:04.647  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:04.647  1015  1121 V NetworkStats: performPollLocked() took 25ms
,09-06 19:10:04.657  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.657  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.657  7718  7718 E Zygote  : MountEmulatedStorage()
09-06 19:10:04.657  7718  7718 E Zygote  : v2
09-06 19:10:04.657  7718  7718 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:10:04.657  7718  7718 I libpersona: KNOX_SDCARD not a persona,
,09-06 19:10:04.667  7718  7718 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:10:04.667  7718  7718 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:10:04.667  1015  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7718 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:10:04.667  1015  1054 I art     : Explicit concurrent mark sweep GC freed 67354(3MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 24MB/36MB, paused 10.505ms total 236.780ms
09-06 19:10:04.667  7718  7718 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:10:04.667  1495  1495 D Launcher: onStart, Launcher: 72815327
09-06 19:10:04.667  1495  1495 D Launcher.HomeView: onStart
,09-06 19:10:04.677  1495  1495 D Launcher: onResume, Launcher: 72815327
,09-06 19:10:04.677  1015  1028 D SettingsProvider: name = kids_home_mode
09-06 19:10:04.677  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:10:04.677  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:10:04.677  1015  1028 D SettingsProvider: selectionArgs: false
09-06 19:10:04.677  1015  1028 D SettingsProvider: selectionArgs: 10006
09-06 19:10:04.677  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:10:04.677  1015  1028 D SettingsProvider: ret = -1
09-06 19:10:04.677  1495  1495 D Launcher.HomeView: onResume
,09-06 19:10:04.687  1455  1455 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:10:04.687  1455  1455 D RegisteredServicesCache: empty dynamic service
,09-06 19:10:04.697  1495  1495 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-06 19:10:04.697  1495  1495 D MenuAppsGridFragment: onResume
,09-06 19:10:04.697  1495  1495 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-06 19:10:04.697  1495  1495 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-06 19:10:04.717  1455  1455 D RegisteredComponentCache: Collect Tech packages for Knox
,09-06 19:10:04.717  1455  1455 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:10:04.717  1015  1531 D ActivityManager: handle home activity for 0,
09-06 19:10:04.717  1015  1531 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-06 19:10:04.717  1015  1531 D KnoxTimeoutHandler: post home show event for user 0
09-06 19:10:04.717  1015  1531 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 19:10:04.717  1015  1531 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:10:04.717  1015  1531 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 19:10:04.717  1495  1495 D Launcher.HomeView: onPause
,09-06 19:10:04.717  1495  1495 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-06 19:10:04.737   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,09-06 19:10:04.737  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-06 19:10:04.737  1015  5159 D InputDispatcher: Focus entered window: 1495
09-06 19:10:04.737  1015  1054 D PackageManager: delete codoeFile: 
,09-06 19:10:04.737  7718  7718 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:10:04.737  7718  7718 D ActivityThread: Added TimaKeyStore provider
,09-06 19:10:04.747  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:10:04.747  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:10:04.747  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-06 19:10:04.747  1495  1495 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 19:10:04.757  1015  1054 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-06 19:10:04.757  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.757  1015  1054 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,09-06 19:10:04.767  1015  1137 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 19:10:04.767  1015  1054 D PackageManager: result of delete: 1{307458264}
,09-06 19:10:04.767  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:04.767  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:04.777  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.777  1015  7735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:10:04.777  1015  1137 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6750 uid 10171
,09-06 19:10:04.787  7704  7704 D AndroidRuntime: Shutting down VM
,09-06 19:10:04.787  1015  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-06 19:10:04.787  1015  1054 D PackageManager: userId{-1}
09-06 19:10:04.787  1015  1054 D PackageManager: andCode{true}
,09-06 19:10:04.787  1963  1963 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
09-06 19:10:04.787  1015  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-06 19:10:04.817  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.817  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.817  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.817  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:04.847  7738  7738 E Zygote  : MountEmulatedStorage()
09-06 19:10:04.847  7738  7738 I libpersona: KNOX_SDCARD checking this for 10003
09-06 19:10:04.847  7738  7738 E Zygote  : v2
09-06 19:10:04.847  7738  7738 I libpersona: KNOX_SDCARD not a persona
,09-06 19:10:04.857  7738  7738 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-06 19:10:04.857  7718  7718 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-06 19:10:04.857  7718  7718 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-06 19:10:04.857  7718  7718 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-06 19:10:04.857  7738  7738 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:10:04.857  1015  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
09-06 19:10:04.857  1015  1531 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 19:10:04.857  1015  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7738 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-06 19:10:04.857  1015  1531 D SecContentProvider2: mCursor = null
,09-06 19:10:04.867  7738  7738 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:10:04.877  7718  7718 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-06 19:10:04.877  7718  7718 I PCWCLIENTTRACE_PushUtil: sales region : global
09-06 19:10:04.877  7718  7718 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-06 19:10:04.877  7718  7718 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:04.897  1015  1137 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 6 r.nextReceiver= 1 receivers.size=28
09-06 19:10:04.897  1015  1137 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-06 19:10:04.907  1015  1045 W ActivityManager: mDVFSHelper.release()
09-06 19:10:04.907  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2298d436 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147842
,09-06 19:10:04.917  1801  1801 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:10:04.917  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-06 19:10:04.917  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.917  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.917  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.917  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:04.927  7738  7738 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:10:04.927  7738  7738 D ActivityThread: Added TimaKeyStore provider
,09-06 19:10:04.927  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75),
,09-06 19:10:04.937  7754  7754 E Zygote  : MountEmulatedStorage()
09-06 19:10:04.937  7754  7754 E Zygote  : v2
09-06 19:10:04.937  7754  7754 I libpersona: KNOX_SDCARD checking this for 10121
09-06 19:10:04.937  7754  7754 I libpersona: KNOX_SDCARD not a persona
09-06 19:10:04.937  7754  7754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:10:04.937  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7754 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
09-06 19:10:04.937  7754  7754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:10:04.937  7754  7754 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:10:04.937  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.947  1015  1313 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
09-06 19:10:04.947  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.947  1015  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.947  1015  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.947  1015  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.947  1015  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:04.957  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.957  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-06 19:10:04.957  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:10:04.957  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:10:04.957  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.957   308   308 I art     : Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 23.856ms
,09-06 19:10:04.967  7754  7754 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:10:04.967  7754  7754 D ActivityThread: Added TimaKeyStore provider
,09-06 19:10:04.977  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 19:10:04.977   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.489ms
09-06 19:10:04.977  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 19:10:04.977  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-06 19:10:04.977  1015  1015 V EnterpriseBillingPolicy: uID is 10171
09-06 19:10:04.977  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 19:10:04.977  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-06 19:10:04.977  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 19:10:04.977  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 19:10:04.977  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 19:10:04.977  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-06 19:10:04.987  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 19:10:04.987  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.987  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.987  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:10:04.987  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:10:04.987  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.997  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:10:04.997  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:10:04.997   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 826us total 17.507ms
09-06 19:10:04.997  7704  7704 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-06 19:10:04.997  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-06 19:10:04.997  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:10:04.997  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:05.007  7769  7769 E Zygote  : MountEmulatedStorage()
,09-06 19:10:05.007  7769  7769 E Zygote  : v2
09-06 19:10:05.007  7769  7769 I libpersona: KNOX_SDCARD checking this for 10031
09-06 19:10:05.007  7769  7769 I libpersona: KNOX_SDCARD not a persona
,09-06 19:10:05.017  7769  7769 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:10:05.017  1015  1313 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7769 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
09-06 19:10:05.017  1015  1137 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-06 19:10:05.017  7769  7769 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:10:05.017  1015  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
09-06 19:10:05.017  1015  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:05.017  1015  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:05.017  1015  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
09-06 19:10:05.017  7769  7769 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:10:05.027  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:10:05.027  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
09-06 19:10:05.027  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-06 19:10:05.027  1015  3373 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-06 19:10:05.027  1015  1015 V EnterpriseBillingPolicy: uID is 10171
09-06 19:10:05.027  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 19:10:05.027  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-06 19:10:05.027  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-06 19:10:05.027  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
09-06 19:10:05.027  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 19:10:05.027  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 19:10:05.027  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 19:10:05.027  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-06 19:10:05.027  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-06 19:10:05.037  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-06 19:10:05.037  2469  2761 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
09-06 19:10:05.037  7769  7769 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:10:05.037  7769  7769 D ActivityThread: Added TimaKeyStore provider
,09-06 19:10:05.047  1801  1801 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
09-06 19:10:05.047  1801  1801 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-06 19:10:05.047  1801  1801 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-06 19:10:05.047  1801  1801 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-06 19:10:05.047  7754  7754 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:10:05.047  7754  7754 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-06 19:10:05.047  7754  7754 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:10:05.057  1801  1801 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-06 19:10:05.057  1801  1801 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-06 19:10:05.067  7754  7754 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:05.077  7754  7754 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-06 19:10:05.077  1015  4386 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
09-06 19:10:05.077  1015  4386 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,09-06 19:10:05.077  1015  4386 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:05.077  1015  4386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:10:05.077  1015  4386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,09-06 19:10:05.077  7754  7754 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-06 19:10:05.097  1015  1502 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:10:05.097  1015  1518 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:10:05.107  1015  1486 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-06 19:10:05.107  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 19:10:05.107  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:05.107  1015  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:10:05.107  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:10:05.137  6998  7789 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-06 19:10:05.137  6998  7789 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:10:05.137  6998  7789 I System.out: (HTTPLog)-Static: isShipBuild true
09-06 19:10:05.137  6998  7789 I System.out: (HTTPLog)-Thread-1265-1014681922: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-06 19:10:05.137  6998  7789 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:10:05.137   277   917 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:10:05.137   277   917 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,09-06 19:10:05.147  2753  7791 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-06 19:10:05.147  7133  7133 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-06 19:10:05.147  2753  7791 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-06 19:10:05.147  2753  7791 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-06 19:10:05.147  7247  7247 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-06 19:10:05.157  7170  7170 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-06 19:10:05.157  7170  7170 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,09-06 19:10:05.157  7170  7170 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-06 19:10:05.177  6998  7789 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:10:05.177  7170  7170 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-06 19:10:05.177  7170  7170 I SA      : [OR] == isSIMCardReady false ==
,09-06 19:10:05.177  7170  7170 I SA      : [SCU] == networkStateCheck == true
,09-06 19:10:05.177  7170  7170 I SA      : [DM] getCountryCodeFromCSC : PL
09-06 19:10:05.177  7170  7170 I SA      : isChinaCountryCode : false
09-06 19:10:05.177  7170  7170 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-06 19:10:05.177  7170  7170 I SA      : [OR] == networkStateCheck true ==
,09-06 19:10:05.187  2753  7791 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-06 19:10:05.187  2753  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-06 19:10:05.187  2753  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-06 19:10:05.187  2753  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-06 19:10:05.197  2753  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-06 19:10:05.197  2753  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-06 19:10:05.197  2753  7791 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-06 19:10:05.197  2753  7791 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-06 19:10:05.217  2753  7791 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-06 19:10:05.217  7170  7170 I SA      : [OR] GetMyCountryZoneTask
,09-06 19:10:05.217  7170  7170 I SA      : [OR] onReceive END
,09-06 19:10:05.227  1015  4382 I ActivityManager: Killing 7147:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-06 19:10:05.237  1223  1223 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:05.237  2753  7791 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-06 19:10:05.237  1015  1718 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-06 19:10:05.237  1015  1718 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-06 19:10:05.237  1015  1718 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:05.237  1015  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:05.237  1015  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-06 19:10:05.257  1015  5159 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-06 19:10:05.257  1015  5159 D SecContentProvider2: mCursor = null
,09-06 19:10:05.257  7170  7795 I SA      : [SRS] prepareGetMyCountryZone
,09-06 19:10:05.257  6998  7789 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 19:10:05.257  1015  5159 I ActivityManager: Killing 7228:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-06 19:10:05.267  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{19f494db token=android.os.BinderProxy@2be726e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
09-06 19:10:05.267  1495  1495 D Launcher.HomeView: onStop
,09-06 19:10:05.277  1495  1495 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2be726e time:148211
,09-06 19:10:05.287  1015  1028 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:10:05.297  7170  7795 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-06 19:10:05.297  7170  7795 I SA      : [SSP] query invoked
,09-06 19:10:05.307  7170  7795 I SA      : [TPMU] GetMccFromDB : null
09-06 19:10:05.307  7170  7795 I SA      : [SCU] getMccFromPreferece mcc = 260
09-06 19:10:05.307  7170  7795 I SA      : [LBE] isSupportCheckDomainRegion : false
09-06 19:10:05.307  7170  7795 I SA      : [TPM] isNoProxy(default) : true
,09-06 19:10:05.327  7170  7795 E File    : fail readDirectory() errno=2
,09-06 19:10:05.337  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,09-06 19:10:05.337  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,09-06 19:10:05.337  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:10:05.337  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 19:10:05.337  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,09-06 19:10:05.357  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-06 19:10:05.357  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:05.357  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:05.357  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:05.357  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:05.357  1177  1177 I StatusBar: Icon Only,
09-06 19:10:05.357  1177  1177 D PanelView: There is/are notification(s) ,
,09-06 19:10:05.367  7799  7799 E Zygote  : MountEmulatedStorage(),
09-06 19:10:05.367  7799  7799 E Zygote  : v2
09-06 19:10:05.367  7799  7799 I libpersona: KNOX_SDCARD checking this for 10001,
09-06 19:10:05.367  7799  7799 I libpersona: KNOX_SDCARD not a persona
09-06 19:10:05.377  7799  7799 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:10:05.377  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7799 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-06 19:10:05.377  7799  7799 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:10:05.377  7799  7799 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:10:05.397  7799  7799 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:10:05.407  7799  7799 D ActivityThread: Added TimaKeyStore provider
,09-06 19:10:05.437  1015  1488 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-06 19:10:05.437  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-06 19:10:05.447  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:05.447  1015  1488 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-06 19:10:05.447  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-06 19:10:05.457  1015  1531 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:10:05.457  1015  1531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 19:10:05.457  1015  1531 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:05.457  1015  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:10:05.457  1015  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms

```
