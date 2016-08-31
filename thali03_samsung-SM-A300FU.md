#### Test 82894682929afb6_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system,
08-31 08:52:40.579  1019  3368 D SSRM:n  : SIOP:: AP = 260
--------- beginning of main
08-31 08:52:40.849  7368  7368 D AndroidRuntime: 
08-31 08:52:40.849  7368  7368 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 08:52:40.859  7368  7368 D AndroidRuntime: CheckJNI is OFF
08-31 08:52:40.859  7368  7368 D AndroidRuntime: readGMSProperty: start
08-31 08:52:40.859  7368  7368 D AndroidRuntime: readGMSProperty: already setted!!
08-31 08:52:40.859  7368  7368 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 08:52:40.859  7368  7368 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 08:52:40.859  7368  7368 D AndroidRuntime: readGMSProperty: end
08-31 08:52:40.859  7368  7368 D AndroidRuntime: addProductProperty: start
08-31 08:52:40.989  7368  7368 E AffinityControl: AffinityControl: registerfunction enter
08-31 08:52:41.019  7368  7368 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 08:52:41.029  1019  4377 E PersonaManagerService: inState():  stateMachine is null !!
08-31 08:52:41.029  1019  4377 I PersonaManagerService: PersonaId don't exist
08-31 08:52:41.029  1019  4377 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 08:52:41.029  1019  4377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 08:52:41.039  1019  4377 W ActivityManager: mDVFSHelper.acquire()
08-31 08:52:41.039  1019  4377 D FocusedStackFrame: Set to : 0
08-31 08:52:41.049  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:41.049  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:41.049  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:41.049  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:41.049  1019  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 08:52:41.049  1019  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-31 08:52:41.059  7379  7379 E Zygote  : MountEmulatedStorage()
08-31 08:52:41.059  7379  7379 E Zygote  : v2
08-31 08:52:41.059  7379  7379 I libpersona: KNOX_SDCARD checking this for 10170
08-31 08:52:41.059  7379  7379 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:41.059  7379  7379 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:52:41.059  1019  4377 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7379 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 08:52:41.059  1019  4377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-31 08:52:41.059  1019  4377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 08:52:41.059  1019  4377 D InputDispatcher: Focused application set to: xxxx
08-31 08:52:41.059  1019  4377 D InputDispatcher: Focus left window: 1489
08-31 08:52:41.059  7368  7368 D AndroidRuntime: Shutting down VM
08-31 08:52:41.069  7379  7379 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:52:41.069  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 08:52:41.069  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 08:52:41.069   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-31 08:52:41.069  7379  7379 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 08:52:41.079  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 08:52:41.079  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 08:52:41.089   308   308 I art     : Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 22.121ms
08-31 08:52:41.099  7379  7379 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 08:52:41.099  7379  7379 D ActivityThread: Added TimaKeyStore provider
08-31 08:52:41.099  1019  1461 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-31 08:52:41.099   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.660ms
08-31 08:52:41.109  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 08:52:41.119   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 17.246ms
08-31 08:52:41.119  1019  1461 D PersonaManager: isKioskContainerExistOnDevice
08-31 08:52:41.139  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-31 08:52:41.159   258  6402 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-31 08:52:41.159   258   437 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-31 08:52:41.169  1489  1489 V ActivityThread: updateVisibility : ActivityRecord{379d710a token=android.os.BinderProxy@30021878 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-31 08:52:41.169  1489  1489 D Launcher: onTrimMemory. Level: 20
08-31 08:52:41.229  7379  7379 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-31 08:52:41.249  7379  7379 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 3780-3783)
08-31 08:52:41.249  7379  7379 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 08:52:41.269  7368  7368 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 08:52:41.279  7379  7379 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10dc6623}
,08-31 08:52:41.289  7379  7379 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 08:52:41.289  7379  7379 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 08:52:41.329  7379  7379 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 08:52:41.329  7379  7379 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 08:52:41.339  7379  7379 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 08:52:41.379  7379  7379 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 08:52:41.379  7379  7379 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 08:52:41.379  7379  7379 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 08:52:41.379  7379  7379 I Adreno-EGL: Local Branch: 
08-31 08:52:41.379  7379  7379 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 08:52:41.379  7379  7379 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 08:52:41.379  7379  7379 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 08:52:41.449  7379  7379 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 08:52:41.469  7379  7379 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-31 08:52:41.469  7379  7379 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-31 08:52:41.479  7379  7379 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-31 08:52:41.479  7379  7379 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-31 08:52:41.599  7379  7379 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 08:52:41.609  7379  7379 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 08:52:41.619  7379  7379 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-31 08:52:41.619  7379  7379 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-31 08:52:41.629  1019  1045 W ActivityManager: Activity pause timeout for ActivityRecord{25383d10 u0 com.test.thalitest/.MainActivity t164}
,08-31 08:52:41.629  7379  7379 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-31 08:52:41.639  7379  7379 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 08:52:41.639  7379  7379 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 08:52:41.679  7379  7417 D OpenGLRenderer: Render dirty regions requested: true
,08-31 08:52:41.679  1019  1484 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 08:52:41.679  1019  1484 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 08:52:41.679  1019  1484 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 08:52:41.679  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 08:52:41.679  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 08:52:41.689  7379  7406 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup,
,08-31 08:52:41.689  7379  7379 V ActivityThread: updateVisibility : ActivityRecord{367fb203 token=android.os.BinderProxy@29111c14 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-31 08:52:41.699  7379  7379 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-31 08:52:41.699  7379  7379 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-31 08:52:41.709   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-31 08:52:41.729  1019  1506 D InputDispatcher: Focus entered window: 7379
,08-31 08:52:41.729  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-31 08:52:41.729  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 08:52:41.729  7379  7379 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-31 08:52:41.729  7379  7417 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 08:52:41.739  7379  7417 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-31 08:52:41.739  7379  7417 D OpenGLRenderer: Enabling debug mode 0
,08-31 08:52:41.769  1019  1495 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 08:52:41.769  1182  1182 D PanelView: There is/are notification(s) 
,08-31 08:52:41.779  1019  7423 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 08:52:41.779  1019  1050 I ActivityManager: Displayed Component not be shown by security: +655ms (total +35s638ms),
08-31 08:52:41.779  1019  1050 W ActivityManager: mDVFSHelper.release()
08-31 08:52:41.779  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{25383d10 u0 com.test.thalitest/.MainActivity t164} time:154318
,08-31 08:52:41.789   258   437 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-31 08:52:41.789   258  1041 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-31 08:52:41.789  7379  7379 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-31 08:52:41.799  7379  7379 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29111c14 time:154332
,08-31 08:52:41.829  1880  1880 I SamsungIME: getCurrentCandidateView
,08-31 08:52:41.939  1880  1880 D SamsungIME: Dismiss ExpandCandiate
,08-31 08:52:41.939  7379  7379 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7379
,08-31 08:52:42.089  1880  1880 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 08:52:42.119  7379  7379 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 08:52:42.129  1880  1880 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 08:52:42.149  1880  1880 I SamsungIME: KeybaordView init() : load resources
,08-31 08:52:42.169  1880  1880 I SamsungIME: getCurrentKeyboard
,08-31 08:52:42.169  1880  1880 I SamsungIME: getTextKeyboard
,08-31 08:52:42.189  1880  1880 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 08:52:42.199  7379  7425 D jxcore_app_log: JniHelper::setJavaVM(0xb76cd2b0), pthread_self() = -1211776984
,08-31 08:52:42.209  7379  7425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 08:52:42.209  7379  7425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 08:52:42.209  7379  7425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 08:52:42.209  7379  7425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 08:52:42.209  7379  7425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 08:52:42.209  7379  7425 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33e1d4f1 added. We now have 1 listener(s)
,08-31 08:52:42.219  7379  7425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-31 08:52:42.219  7379  7425 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-31 08:52:42.219  7379  7425 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 08:52:42.219  7379  7425 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 08:52:42.219  7379  7425 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27bdb244 added. We now have 1 listener(s)
,08-31 08:52:42.229  7379  7425 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:42.229  7379  7425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 08:52:42.229  7379  7425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 08:52:42.229  7379  7425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-31 08:52:42.229  7379  7425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 08:52:42.229  7379  7425 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 08:52:42.239  7379  7425 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:42.239  7379  7425 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-31 08:52:42.249  7379  7425 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 08:52:42.249  7379  7425 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:42.249  7379  7425 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:42.249  7379  7425 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:42.249  7379  7425 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:42.249  7379  7425 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:42.249  7379  7425 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:42.249  7379  7425 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:42.249  7379  7425 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:42.249  7379  7425 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-31 08:52:42.249  7379  7425 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:52:42.249  7379  7425 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 08:52:42.249  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:42.249  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:42.279  7379  7379 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 08:52:42.409   289   289 E SMD     : DCD OFF
,08-31 08:52:42.819  7379  7432 W jxcore-log: Initializing JXcore engine
08-31 08:52:42.819  7379  7432 W jxcore-log: JXcore engine is ready
,08-31 08:52:42.879  1932  1932 E audit   : type=1400 msg=audit(1472626362.879:205): avc:  denied  { ioctl } for  pid=7432 comm="Thread-1405" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3080 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 08:52:42.879  1932  1932 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:52:42.879  1932  1932 E audit   : type=1300 msg=audit(1472626362.879:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9f8fb8f8 items=0 ppid=308 ppcomm=main pid=7432 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1405" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-31 08:52:42.889  1932  1932 E audit   : type=1320 msg=audit(1472626362.879:205): 
,08-31 08:52:42.899  7379  7432 W jxcore-log: Starting JXcore engine
,08-31 08:52:42.999  7379  7432 W jxcore-log: Platform android
08-31 08:52:42.999  7379  7432 W jxcore-log: 
08-31 08:52:42.999  7379  7432 W jxcore-log: Process ARCH arm
08-31 08:52:42.999  7379  7432 W jxcore-log: 
,08-31 08:52:43.199  7379  7432 I jxcore-log: JXcore Cordova bridge is ready!
08-31 08:52:43.199  7379  7432 I jxcore-log: 
,08-31 08:52:43.199  7379  7432 W jxcore-log: JXcore engine is started
,08-31 08:52:43.209  7379  7425 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 08:52:43.209  7379  7379 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 08:52:43.679  1019  1265 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 08:52:43.679  1019  1265 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4271, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 08:52:43.679  1019  1265 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-31 08:52:43.679  1019  1265 D BatteryService: stay LED for charging
08-31 08:52:43.679  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 08:52:43.679  1019  1019 I MotionRecognitionService: Plugged
,08-31 08:52:43.679  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 08:52:43.679  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 08:52:43.689  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 08:52:43.689  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 08:52:43.689  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 08:52:43.689  3200  3200 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-31 08:52:43.689  3200  3359 D HeadsetStateMachine: Disconnected process message: 10
,08-31 08:52:43.709  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 08:52:43.709  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 08:52:43.709  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 08:52:45.419   289   289 E SMD     : DCD OFF,
,08-31 08:52:46.429   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:52:47.429   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 08:52:48.419   289   289 E SMD     : DCD OFF,
,08-31 08:52:48.429   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 08:52:49.429   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 08:52:50.389  1019  3401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-31 08:52:50.429   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 08:52:50.609  1019  3368 D SSRM:n  : SIOP:: AP = 300
,08-31 08:52:51.099  1019  1060 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-31 08:52:51.419   289   289 E SMD     : DCD OFF
,08-31 08:52:51.429   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-31 08:52:53.719  1019  4381 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-31 08:52:53.719  1019  4381 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4270, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 08:52:53.719  1019  4381 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 08:52:53.719  1019  4381 D BatteryService: stay LED for charging
08-31 08:52:53.719  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 08:52:53.729  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 08:52:53.729  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 08:52:53.729  1019  1019 I MotionRecognitionService: Plugged
,08-31 08:52:53.729  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 08:52:53.729  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 08:52:53.729  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 08:52:53.739  3200  3200 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-31 08:52:53.739  3200  3359 D HeadsetStateMachine: Disconnected process message: 10
,08-31 08:52:53.749  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 08:52:53.749  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 08:52:53.749  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 08:52:54.419   289   289 E SMD     : DCD OFF
,08-31 08:52:55.309  1019  1308 E Watchdog: !@Sync 5,
,08-31 08:52:55.399  1019  1052 I PowerManagerService: [PWL] Off : 105s ago,
,08-31 08:52:55.539  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-31 08:52:55.539  7379  7432 I jxcore-log: 
,08-31 08:52:55.549  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-31 08:52:55.549  7379  7432 I jxcore-log: 
,08-31 08:52:55.549  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:55.549  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:55.549  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:55.549  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:55.549  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:55.549  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:55.549  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:55.549  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:55.549  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-31 08:52:55.559  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-31 08:52:55.559  7379  7432 I jxcore-log: 
,08-31 08:52:55.559  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-31 08:52:55.559  7379  7432 I jxcore-log: 
,08-31 08:52:56.219  7379  7432 D executeNativeTests: Running unit tests,
,08-31 08:52:56.299  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:56.299  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 added. We now have 2 listener(s)
,08-31 08:52:56.309  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 08:52:56.309  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:56.309  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:56.309  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:56.309  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 added. We now have 2 listener(s)
08-31 08:52:56.309  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:56.309  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:52:56.309  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:56.309  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:56.309  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:56.309  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:56.309  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:56.309  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:56.309  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
08-31 08:52:56.309  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:56.309  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:56.319  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-31 08:52:56.319  7379  7432 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:52:56.319  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 08:52:56.319  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-31 08:52:56.319  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 08:52:56.319  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-31 08:52:56.319  7379  7432 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-31 08:52:56.319  7379  7432 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-31 08:52:56.319  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
08-31 08:52:56.319  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
08-31 08:52:56.319  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:52:56.319  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.319  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.319  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.319  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 08:52:56.319  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.319  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.319  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:56.319  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:56.319  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 removed from the list
08-31 08:52:56.319  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.319  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 removed from the list,
,08-31 08:52:56.319  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop,
08-31 08:52:56.319  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.329  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.329  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.329  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:56.329  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 08:52:56.329  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.329  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.329  7379  7432 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 08:52:56.329  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.329  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.329  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.329  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:52:56.329  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.329  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.329  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.329  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.329  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.329  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:52:56.329  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.329  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.329  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.329  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.329  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:56.329  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.329  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.329  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 08:52:56.339  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.339  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.339  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.339  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.339  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.339  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.339  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.339  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.339  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.339  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.339  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.339  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.339  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.339  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.339  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 08:52:56.339  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.339  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.339  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.339  7379  7432 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 08:52:56.339  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:56.349  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:56.349  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-31 08:52:56.349  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:56.349  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:56.349  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:56.349  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:56.349  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:56.349  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:56.349  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:52:56.349  7379  7432 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:56.349  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:56.349  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:52:56.349  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:52:56.349  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:56.349  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:52:56.349  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:56.349  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:52:56.349  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:56.359  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:52:56.369  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:52:56.369  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 08:52:56.369  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-31 08:52:56.369  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:52:56.369  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 08:52:56.369  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:52:56.379  3200  3355 D BtGatt.GattService: registerClient() - UUID=93263f2e-7625-4df2-9bfb-3ce54d1733b5
,08-31 08:52:56.419  3200  3278 D BtGatt.GattService: onClientRegistered() - UUID=93263f2e-7625-4df2-9bfb-3ce54d1733b5, clientIf=6
,08-31 08:52:56.419  7379  7388 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 08:52:56.429  3200  3211 D BtGatt.GattService: start scan with filters
,08-31 08:52:56.429  3200  3357 D BtGatt.ScanManager: handling starting scan
,08-31 08:52:56.429  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:52:56.429  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 08:52:56.429  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 08:52:56.429  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 08:52:56.429  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:56.439  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:52:56.439  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:56.439  3200  3357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:52:56.439  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:52:56.439  7379  7432 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 08:52:56.449  3200  3278 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 08:52:56.449  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:52:56.449  3200  3357 D BtGatt.ScanManager: allow scan with filters,
08-31 08:52:56.449  3200  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 08:52:56.449  3200  3357 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-31 08:52:56.449  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.449  7379  7432 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:52:56.449  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.449  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 08:52:56.449  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.449  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:52:56.449  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:52:56.449  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:52:56.449  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:52:56.449  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 08:52:56.449  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 08:52:56.449  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:52:56.449  3200  3211 D BtGatt.GattService: stopScan() - queue size =1
,08-31 08:52:56.459  3200  3219 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 08:52:56.459  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 08:52:56.459  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:52:56.459  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:52:56.459  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:52:56.459  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:52:56.459  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:52:56.459  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.459  3200  3357 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:52:56.459  3200  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 08:52:56.459  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:56.459  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 08:52:56.459  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 08:52:56.469  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 08:52:56.469  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:52:56.469  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 08:52:56.469  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:56.469  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:56.469  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.469  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.469  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:56.469  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.469  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.469  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.469  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.469  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.469  7379  7432 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 08:52:56.469  3200  3278 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 08:52:56.469  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.469  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:56.479  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:56.479  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:56.479  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:56.479  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:56.479  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:56.479  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:56.479  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:56.479  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:56.479  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:52:56.479  7379  7432 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:52:56.489  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:56.489  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:52:56.489  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:52:56.489  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:56.489  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:52:56.489  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:56.489  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 08:52:56.489  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.489  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:52:56.499  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:56.499  3200  3357 D BtGatt.ScanManager: filter size is 1
,08-31 08:52:56.499  3200  3357 D BtGatt.ScanManager: delete FilterIndex - 3
08-31 08:52:56.499  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 08:52:56.499  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:52:56.499  3200  3357 D BtGatt.ScanManager: stopping BLe Batch
,08-31 08:52:56.499  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:52:56.499  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:52:56.509  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 08:52:56.509  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.509  3200  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 08:52:56.509  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:52:56.509  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 08:52:56.509  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:52:56.509  3200  3355 D BtGatt.GattService: registerClient() - UUID=01f06404-6cb3-465b-a582-339a7abf73b7
,08-31 08:52:56.519  3200  3278 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-31 08:52:56.519  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.559  3200  3278 D BtGatt.GattService: onClientRegistered() - UUID=01f06404-6cb3-465b-a582-339a7abf73b7, clientIf=6
,08-31 08:52:56.559  7379  7387 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-31 08:52:56.559  3200  3211 D BtGatt.GattService: start scan with filters
,08-31 08:52:56.559  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:52:56.559  3200  3357 D BtGatt.ScanManager: handling starting scan
08-31 08:52:56.559  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:52:56.559  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 08:52:56.559  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 08:52:56.559  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:56.559  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:56.569  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:52:56.569  3200  3278 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 08:52:56.569  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.569  3200  3357 D BtGatt.ScanManager: allow scan with filters
08-31 08:52:56.569  3200  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 08:52:56.569  3200  3357 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-31 08:52:56.569  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:52:56.579  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 08:52:56.579  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.579  3200  3357 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 08:52:56.579  3200  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 08:52:56.579  7379  7432 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 08:52:56.579  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:52:56.589  7379  7432 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:52:56.589  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.589  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 08:52:56.589  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.589  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:52:56.589  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:52:56.589  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:52:56.589  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:52:56.589  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:52:56.589  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:52:56.589  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:52:56.589  3200  3211 D BtGatt.GattService: stopScan() - queue size =1
,08-31 08:52:56.589  3200  3370 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 08:52:56.589  3200  3278 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 08:52:56.589  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.589  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 08:52:56.589  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 08:52:56.599  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:52:56.599  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:52:56.599  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:52:56.599  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:56.599  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 08:52:56.599  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 08:52:56.599  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.599  3200  3357 D BtGatt.ScanManager: filter size is 1
,08-31 08:52:56.599  3200  3357 D BtGatt.ScanManager: delete FilterIndex - 4
,08-31 08:52:56.609  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:52:56.609  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 08:52:56.609  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:52:56.609  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 08:52:56.609  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 08:52:56.609  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:56.609  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:52:56.609  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.609  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:52:56.609  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
,08-31 08:52:56.609  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 08:52:56.609  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.609  3200  3357 D BtGatt.ScanManager: stopping BLe Batch
,08-31 08:52:56.609  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:56.609  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.609  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:52:56.609  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.619  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.619  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.619  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:56.619  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 08:52:56.619  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:56.619  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.619  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 08:52:56.619  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.619  3200  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 08:52:56.619  7379  7432 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 08:52:56.619  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:56.629  3200  3278 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 08:52:56.629  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.629  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:56.629  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:56.629  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:56.629  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:56.629  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:56.629  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:56.629  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:56.629  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:56.629  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:52:56.629  7379  7432 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:52:56.629  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:56.639  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:56.639  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:52:56.639  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:52:56.639  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:56.639  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:52:56.639  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:56.639  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:52:56.649  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:52:56.649  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:52:56.649  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:52:56.649  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 08:52:56.649  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:52:56.649  3200  3211 D BtGatt.GattService: registerClient() - UUID=b350e362-94f9-4f9d-986b-0eaab1ba1aa1
,08-31 08:52:56.689  3200  3278 D BtGatt.GattService: onClientRegistered() - UUID=b350e362-94f9-4f9d-986b-0eaab1ba1aa1, clientIf=6
,08-31 08:52:56.689  7379  7388 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 08:52:56.699  3200  3370 D BtGatt.GattService: start scan with filters
,08-31 08:52:56.699  3200  3357 D BtGatt.ScanManager: handling starting scan
,08-31 08:52:56.699  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:52:56.699  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 08:52:56.699  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 08:52:56.699  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 08:52:56.709  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:56.709  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:56.709  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:52:56.709  3200  3278 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 08:52:56.709  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.709  3200  3357 D BtGatt.ScanManager: allow scan with filters
,08-31 08:52:56.709  3200  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 08:52:56.709  3200  3357 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-31 08:52:56.709  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 08:52:56.719  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.719  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:52:56.719  3200  3357 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:52:56.719  3200  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 08:52:56.719  3200  3278 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 08:52:56.719  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.719  7379  7432 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 08:52:56.729  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.729  7379  7432 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:52:56.729  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.729  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 08:52:56.729  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.729  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:52:56.729  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:52:56.729  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:52:56.729  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:52:56.729  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:52:56.729  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:52:56.729  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:52:56.729  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 08:52:56.729  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.729  3200  3219 D BtGatt.GattService: stopScan() - queue size =1
,08-31 08:52:56.729  3200  3357 D BtGatt.ScanManager: filter size is 1
,08-31 08:52:56.729  3200  3357 D BtGatt.ScanManager: delete FilterIndex - 5
,08-31 08:52:56.739  3200  3355 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 08:52:56.739  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:52:56.739  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:52:56.739  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:52:56.739  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:52:56.739  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:52:56.739  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 08:52:56.739  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:52:56.739  3200  3357 D BtGatt.ScanManager: stopping BLe Batch
08-31 08:52:56.739  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:56.739  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 08:52:56.739  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 08:52:56.739  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 08:52:56.739  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:52:56.749  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 08:52:56.749  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.749  7379  7432 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:52:56.749  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.749  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.749  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.749  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.749  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:56.749  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.749  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.749  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.749  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.749  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.749  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:56.749  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:56.749  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.749  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.749  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 08:52:56.749  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:52:56.749  3200  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 08:52:56.749  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:56.749  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 08:52:56.749  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:56.749  3200  3278 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 08:52:56.749  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:56.749  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.759  7379  7432 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-31 08:52:56.759  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:52:56.759  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:52:56.759  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:52:56.759  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:52:56.759  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.759  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.759  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.759  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:56.759  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.759  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.759  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.759  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.759  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.759  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.759  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:56.759  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 08:52:56.759  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:56.759  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.769  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-31 08:52:56.769  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.769  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:52:56.769  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:52:56.769  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.769  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.769  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.769  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
,08-31 08:52:56.769  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.769  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.769  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.769  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.769  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.769  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.769  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.769  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:56.769  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.769  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:56.769  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.769  7379  7432 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-31 08:52:56.769  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:52:56.769  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:52:56.769  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:52:56.779  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:52:56.779  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.779  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.779  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
,08-31 08:52:56.779  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.779  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.779  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.779  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.779  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.779  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.779  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.779  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:56.779  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 08:52:56.779  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.779  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.779  7379  7432 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted,
08-31 08:52:56.779  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.779  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:52:56.779  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.779  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.779  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.779  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.779  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.779  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.779  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.779  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.779  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.779  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.779  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.779  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.779  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 08:52:56.779  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.779  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.779  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.779  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 08:52:56.789  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 08:52:56.789  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 08:52:56.789  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:52:56.789  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 08:52:56.789  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 08:52:56.789  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.789  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.789  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.789  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.789  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.789  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.789  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.789  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.789  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.789  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.789  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.789  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.789  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.789  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:56.789  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.789  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.789  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.789  7379  7432 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:52:56.789  7379  7432 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-31 08:52:56.789  7379  7432 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-31 08:52:56.789  7379  7432 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010],
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610],
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-31 08:52:56.789  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 08:52:56.789  7379  7432 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 08:52:56.789  7379  7432 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 08:52:56.789  7379  7432 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 08:52:56.789  7379  7432 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:52:56.789  7379  7432 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-31 08:52:56.789  7379  7432 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 08:52:56.789  7379  7432 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:52:56.789  7379  7432 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 08:52:56.799  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 08:52:56.799  7379  7432 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 08:52:56.799  7379  7432 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:52:56.799  7379  7432 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-31 08:52:56.799  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.799  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.799  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.799  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.799  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.799  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 08:52:56.799  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.799  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.799  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.799  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.799  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.799  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.799  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.799  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.799  7379  7432 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-31 08:52:56.799  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.799  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.799  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.799  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.799  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.799  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.799  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:56.799  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.799  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.799  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.799  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.799  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.799  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.809  7379  7443 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1469
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.809  7379  7432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 08:52:56.809  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:52:56.809  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.809  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.809  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.809  7379  7442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1469)
08-31 08:52:56.809  7379  7442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1469)
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.809  7379  7432 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 08:52:56.809  7379  7432 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 08:52:56.809  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:52:56.809  7379  7432 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 08:52:56.809  7379  7432 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 08:52:56.809  7379  7432 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-31 08:52:56.809  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 08:52:56.809  7379  7432 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 08:52:56.809  7379  7432 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 08:52:56.809  7379  7432 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-31 08:52:56.809  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 08:52:56.809  7379  7432 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 08:52:56.809  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.809  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:52:56.809  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
,08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.809  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.809  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.809  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.809  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.809  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.809  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.809  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:56.809  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.809  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:56.809  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:52:56.819  7379  7379 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 08:52:56.819  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.819  7379  7379 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:52:56.819  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:52:56.819  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:56.819  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:56.819  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:56.819  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.819  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.819  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.819  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.819  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.819  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.819  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.819  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.819  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.819  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.819  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.819  7379  7432 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 08:52:56.819  7379  7432 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-31 08:52:56.819  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:52:56.819  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.819  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.819  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:52:56.819  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.819  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.819  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.819  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.819  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:52:56.819  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.819  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.819  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.819  7379  7444 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
08-31 08:52:56.819  7379  7444 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 08:52:56.819  7379  7379 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.829  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.829  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.829  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.829  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.829  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.829  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.829  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.829  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.829  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.829  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.829  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.829  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.829  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.829  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
,08-31 08:52:56.829  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:56.829  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:56.829  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:56.829  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.829  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:56.829  7379  7432 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c40d81 not in the list
08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.829  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.829  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:56.829  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.829  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.829  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:56.829  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:56.829  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:56.829  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5d3e26 not in the list
08-31 08:52:56.829  7379  7432 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 08:52:56.829  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:52:56.829  7379  7432 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 08:52:56.829  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:52:56.829  7379  7432 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 08:52:56.829  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 08:52:56.829  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 08:52:56.829  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-31 08:52:56.839  7379  7432 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 08:52:56.839  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 08:52:56.839  7379  7432 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 08:52:56.839  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 08:52:56.839  7379  7432 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 08:52:56.839  7379  7432 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-31 08:52:56.839  7379  7432 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 08:52:56.839  7379  7432 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-31 08:52:56.839  7379  7432 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 08:52:56.839  7379  7432 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 08:52:56.839  7379  7432 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 08:52:56.839  7379  7432 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-31 08:52:56.839  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:56.839  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29faf898 added. We now have 2 listener(s)
08-31 08:52:56.839  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:56.839  7379  7432 D BluetoothAdapter: enable()
,08-31 08:52:56.839  7379  7432 D BluetoothAdapter: enable(): BT is already enabled..!
,08-31 08:52:56.839  1019  4378 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 08:52:56.839  1019  4378 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 08:52:56.839  1019  4378 D SecContentProvider2: mCursor = null
,08-31 08:52:56.839  1019  4378 D WifiService: setWifiEnabled: true pid=7379, uid=10170
,08-31 08:52:56.839  1019  4378 W ActivityManager: Permission Denial: getCurrentUser() from pid=7379, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 08:52:56.859  1019  4378 W WifiService: Failed getting userId using ActivityManagerNative
08-31 08:52:56.859  1019  4378 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7379, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:52:56.859  1019  4378 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 08:52:56.859  1019  4378 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 08:52:56.859  1019  4378 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 08:52:56.859  1019  4378 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 08:52:56.859  1019  4378 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 08:52:56.859  1019  4378 D SettingsProvider: name = wifi_on
,08-31 08:52:56.859  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:56.859  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@352a58f1 added. We now have 3 listener(s)
08-31 08:52:56.859  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:56.859  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:52:56.859  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5877cd6 added. We now have 4 listener(s)
,08-31 08:52:56.859  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:56.869  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:52:56.869  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@63d8b57 added. We now have 5 listener(s)
,08-31 08:52:56.869  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:56.869  1019  1032 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 08:52:56.869  1019  1032 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 08:52:56.869  1019  1032 D SecContentProvider2: mCursor = null
,08-31 08:52:56.869  1019  1032 D WifiService: setWifiEnabled: false pid=7379, uid=10170
,08-31 08:52:56.869  1019  1032 D SettingsProvider: name = wifi_on
,08-31 08:52:56.879  1019  1128 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 08:52:56.879  1381  1381 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 08:52:56.879  1381  1381 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-31 08:52:56.879  1381  1381 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 08:52:56.879  1381  1381 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 08:52:56.879  7379  7432 D BluetoothAdapter: disable()
,08-31 08:52:56.889  1019  1484 D SettingsProvider: name = bluetooth_on,
,08-31 08:52:56.889  1019  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:52:56.899  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:56.899  3200  3275 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-31 08:52:56.899  3200  3275 D BluetoothAdapterProperties: Setting state to 13
08-31 08:52:56.899  3200  3275 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 08:52:56.899  3200  3275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:52:56.899  3200  3275 D BluetoothAdapterService: updateAdapterState state is 13
,08-31 08:52:56.899  1019  4380 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:56.899  1019  4380 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 08:52:56.899  1019  4380 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:56.899  1019  4380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:56.909  1019  4380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:56.909  1019  1128 E WifiNative-wlan0: do suspend true
,08-31 08:52:56.909  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:56.909  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:56.909  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:56.909  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:56.909  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:56.909  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:56.909  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:56.909  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:56.909  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:56.909  3200  3275 D BluetoothAdapterService: Autoconnection is available 
,08-31 08:52:56.909  1019  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-31 08:52:56.909  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:56.909  3200  3275 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-31 08:52:56.909  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:56.909  3200  3275 D BluetoothAdapterService: terminating service from this receiver
08-31 08:52:56.909  7379  7432 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:56.909  3200  3200 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-31 08:52:56.909  3200  3200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c9b6212, channel: 19, state: LISTENING
08-31 08:52:56.909  3200  3200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c9b6212, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37dcdc6b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31f66de3mSocket: android.net.LocalSocket@3bfa23e0 impl:android.net.LocalSocketImpl@1fafb699 fd:FileDescriptor[82]
08-31 08:52:56.909  3200  3200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3bfa23e0 impl:android.net.LocalSocketImpl@1fafb699 fd:FileDescriptor[82]
,08-31 08:52:56.909  1019  1471 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:56.909  1019  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:56.909  1019  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:56.909  3200  3275 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 08:52:56.909  3200  3275 D BluetoothAdapterProperties: mDiscovering is false
,08-31 08:52:56.909  1019  1385 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
08-31 08:52:56.909  3200  3275 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-31 08:52:56.919  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-31 08:52:56.919  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
08-31 08:52:56.919  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:52:56.919  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:56.919  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:56.919  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:56.919  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:56.919  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:56.919  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:56.919  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:56.919  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:56.919  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-31 08:52:56.919  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:52:56.919  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:56.919  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-31 08:52:56.929  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 08:52:56.929  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:52:56.929  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:56.929  1182  1182 D BluetoothTile:  getBluetoothState : 13
,08-31 08:52:56.929  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:52:56.929  1880  1880 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:52:56.929  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 08:52:56.939  4872  4872 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:56.939  1019  1138 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:52:56.939  3200  3200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ac98d5e, channel: 5, state: LISTENING
,08-31 08:52:56.939  3200  3200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ac98d5e, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@843d5ba, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@598053fmSocket: android.net.LocalSocket@10d9e0c impl:android.net.LocalSocketImpl@223c2355 fd:FileDescriptor[80]
08-31 08:52:56.939  3200  3200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@10d9e0c impl:android.net.LocalSocketImpl@223c2355 fd:FileDescriptor[80]
,08-31 08:52:56.939  1019  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 08:52:56.949  3200  3200 I BtOppRfcommListener: stopping Accept Thread
08-31 08:52:56.949  3200  3200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f1d216a, channel: 12, state: LISTENING
,08-31 08:52:56.949  3200  3200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f1d216a, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3cddd9d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1191b65bmSocket: android.net.LocalSocket@5fc8ef8 impl:android.net.LocalSocketImpl@be89fd1 fd:FileDescriptor[86]
,08-31 08:52:56.949  3200  3200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@5fc8ef8 impl:android.net.LocalSocketImpl@be89fd1 fd:FileDescriptor[86]
08-31 08:52:56.949  3200  5355 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 08:52:56.949  3200  5355 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 08:52:56.949  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 08:52:56.949  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 08:52:56.949  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:52:56.949  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:56.949  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:56.949  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:56.949  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:56.949  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:56.949  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:56.949  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:56.949  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:56.949  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:56.949  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:52:56.949  3200  3278 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-31 08:52:56.949  3200  3278 D BluetoothAdapterProperties: Scan Mode:20
,08-31 08:52:56.959  3200  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 08:52:56.959  3200  3275 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-31 08:52:56.959  3200  3200 V BluetoothOppManager: cleanUp...
,08-31 08:52:56.959  3200  3275 E bt-btif : HAL bt_hal_cbacks->log_co
,08-31 08:52:56.959  3200  3279 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-31 08:52:56.959  3200  3275 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 08:52:56.959  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:56.959  4872  4872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:52:56.959  1019  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 08:52:56.959  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 08:52:56.969  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:56.969  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:56.969  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:56.969  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:52:56.969  3200  3279 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:52:56.969  3200  3279 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:52:56.969  3200  3279 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:52:56.969  3200  3279 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:52:56.969  3200  3279 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:52:56.969  3200  3279 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 08:52:56.969  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:56.969  4872  4872 D BluetoothPbap: Proxy object disconnected
08-31 08:52:56.969  4872  4872 D PbapServerProfile: Bluetooth service disconnected
,08-31 08:52:56.979  4872  4872 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:52:56.979  1657  1657 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:56.979  4872  4872 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:52:56.979  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:56.979  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 08:52:56.989  1019  1265 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-31 08:52:56.989  1019  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:56.989  1019  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:56.989  1019  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:56.989  1019  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:56.999  7449  7449 E Zygote  : MountEmulatedStorage(),
08-31 08:52:56.999  7449  7449 I libpersona: KNOX_SDCARD checking this for 10055
08-31 08:52:56.999  7449  7449 E Zygote  : v2
08-31 08:52:56.999  7449  7449 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:56.999  7449  7449 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 08:52:56.999  1019  1265 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7449 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-31 08:52:56.999  7449  7449 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:57.009  7449  7449 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 08:52:57.029  7449  7449 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:57.029  7449  7449 D ActivityThread: Added TimaKeyStore provider,
,08-31 08:52:57.049  1019  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-31 08:52:57.049  1019  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 08:52:57.049   279   979 D CommandListener: Clearing all IP addresses on wlan0,
,08-31 08:52:57.049  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:52:57.049  1657  2536 V NativeCrypto: Read error: ssl=0xb7bf59c8: I/O error during system call, Connection timed out
,08-31 08:52:57.049  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 08:52:57.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:57.059  1657  2536 V NativeCrypto: SSL shutdown failed: ssl=0xb7bf59c8: I/O error during system call, Broken pipe
,08-31 08:52:57.059  1019  1130 E ConnectivityService: updateNetworkInfo()
08-31 08:52:57.059  1019  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:52:57.059  1019  1130 E ConnectivityService: updateNetworkInfo()
08-31 08:52:57.059  1019  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,08-31 08:52:57.059  1019  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 08:52:57.059  1019  1127 D WifiP2pService: InactiveState{ what=131204 }
08-31 08:52:57.059  1019  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-31 08:52:57.059  7449  7449 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-31 08:52:57.059  1019  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-31 08:52:57.069  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 08:52:57.069  1019  1350 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-31 08:52:57.069  1019  1771 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:57.069  1019  1771 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:57.069  1019  1771 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 08:52:57.069  1019  1771 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:57.069  1019  1771 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-31 08:52:57.069  1019  1771 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 08:52:57.069  1019  1771 I qtaguid : Tagging socket 377 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1019, getuid(): 1000
,08-31 08:52:57.079  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 08:52:57.079  1019  1153 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:52:57.079  1019  1019 D RttService: SCAN_AVAILABLE : 1
08-31 08:52:57.079  1019  1154 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:57.079  1019  1771 I qtaguid : Untagging socket 377
,08-31 08:52:57.079  1019  1771 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 08:52:57.079  1019  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 08:52:57.079  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-31 08:52:57.079  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
,08-31 08:52:57.089  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 08:52:57.089  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 08:52:57.089  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 08:52:57.089  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 08:52:57.089  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-31 08:52:57.089  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:52:57.089  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:52:57.089  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:52:57.089  1019  1050 D WifiDisplayController: disconnect
08-31 08:52:57.089  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.089  1019  1050 D WifiDisplayController: updateConnection
08-31 08:52:57.089  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:52:57.089  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 08:52:57.089  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.089  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.089  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.089  1019  1127 D WifiP2pService: P2pDisablingState
,08-31 08:52:57.089  1019  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-31 08:52:57.089  1019  1127 D WifiP2pService: p2p socket connection lost
,08-31 08:52:57.099  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-31 08:52:57.099  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
,08-31 08:52:57.099  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 08:52:57.099  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 08:52:57.099  7449  7449 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-31 08:52:57.099  1019  1127 D WifiP2pService: P2pDisabledState
08-31 08:52:57.099  7449  7449 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-31 08:52:57.099  7449  7449 D UserAnalysis: Create SecureDbHelper
,08-31 08:52:57.099  1019  1128 E WifiNative-wlan0: do suspend true,
,08-31 08:52:57.099  1019  1127 D WifiP2pService: P2pDisabledState{ what=143375 },
08-31 08:52:57.099  1019  1127 D WifiP2pService: DefaultState{ what=143375 },
,08-31 08:52:57.109  7449  7449 D IntelligenceServiceApplication: onCreate(),
08-31 08:52:57.109  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 08:52:57.109  1019  4378 I ActivityManager: Killing 6948:com.sec.pcw.device/1000 (adj 15): empty #21
,08-31 08:52:57.119  1019  1471 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 08:52:57.119  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 08:52:57.119  7449  7449 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 08:52:57.119  1019  1495 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 08:52:57.119  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 08:52:57.119  1019  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:57.119  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:52:57.119  1019  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:57.119  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:52:57.119  1019  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:57.119  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.119  1019  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:57.119  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.119  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.119  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:57.139  7469  7469 E Zygote  : MountEmulatedStorage()
,08-31 08:52:57.139  7469  7469 E Zygote  : v2
08-31 08:52:57.139  7469  7469 I libpersona: KNOX_SDCARD checking this for 10105
08-31 08:52:57.139  7469  7469 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:57.139  1019  1495 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7469 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-31 08:52:57.139  7469  7469 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:57.139  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
,08-31 08:52:57.139  7449  7449 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 08:52:57.139  7469  7469 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:57.139  7469  7469 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:52:57.149   279   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:52:57.149   279   975 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-31 08:52:57.149   279   979 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:52:57.149  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.149  1019  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-31 08:52:57.149  1019  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:52:57.149  1019  1130 V NetworkStats: updateIfacesLocked()
08-31 08:52:57.149  1019  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:52:57.149  1019  1130 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:52:57.149  7449  7449 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-31 08:52:57.149  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 08:52:57.149  1381  1381 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-31 08:52:57.149  1019  1771 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-31 08:52:57.149  1019  1771 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-31 08:52:57.149  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.149  1019  1130 V NetworkStats: performPollLocked() took 7ms
,08-31 08:52:57.159  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:52:57.159  1019  1128 D SecContentProvider2: mCursor = null
,08-31 08:52:57.159  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 08:52:57.159  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:52:57.159  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:52:57.159  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.159  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.159  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.159  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:57.169  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:52:57.169  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:52:57.169  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:52:57.169  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.169  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:57.169  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.169  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:52:57.169  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.169  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:52:57.169  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-31 08:52:57.169  4872  4872 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-31 08:52:57.169  1182  1182 D HotspotTile: onReceive : 0, 0
08-31 08:52:57.169  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 08:52:57.169  1019  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-31 08:52:57.179  3200  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 08:52:57.179  3200  3275 D BtConfig.SecureMode: isSecureModeOn:false
08-31 08:52:57.179  7469  7469 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 08:52:57.179  3200  3275 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-31 08:52:57.179  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-31 08:52:57.179  3200  3275 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-31 08:52:57.179  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 08:52:57.179  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 08:52:57.179  7469  7469 D ActivityThread: Added TimaKeyStore provider
08-31 08:52:57.179  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 08:52:57.179  1019  1771 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:57.179  1019  1130 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 08:52:57.179  1019  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 08:52:57.179  1019  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 08:52:57.179  1460  1460 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 08:52:57.179  1460  1460 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:57.179  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.179  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.179  1182  1727 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-31 08:52:57.179  1019  4378 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:57.179  1019  4378 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 08:52:57.179  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:57.179  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:57.179  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:57.179  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:57.179  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:57.179  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:57.179  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:57.179  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:57.179  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:52:57.179  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:57.179  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:57.179  1019  4378 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:57.179  1019  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-31 08:52:57.179  1019  4378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:57.179  1019  1130 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-31 08:52:57.179  1019  4378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:57.179  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 08:52:57.179  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 08:52:57.179  3200  3200 D HeadsetService: Received stop request...Stopping profile...
,08-31 08:52:57.179  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-31 08:52:57.179  1019  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 08:52:57.189  1019  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-31 08:52:57.189  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
08-31 08:52:57.189  1019  3871 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:57.189  1019  3871 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:52:57.189  1019  3871 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:57.189  1019  3871 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:57.189  1019  3871 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:57.189  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-31 08:52:57.189  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:52:57.189  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 08:52:57.199  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 08:52:57.199  1019  4378 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:57.199  1019  4378 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:57.199  1019  4378 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-31 08:52:57.199  1019  4378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:57.199  1019  4378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:57.199  1019  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 08:52:57.199  1019  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-31 08:52:57.199  1019  1130 E ConnectivityService: updateNetworkInfo()
08-31 08:52:57.199  1019  1130 E ConnectivityService: updateNetworkInfo()
08-31 08:52:57.199  1019  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 08:52:57.199  4872  4872 D HeadsetProfile: Bluetooth service disconnected
,08-31 08:52:57.199  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-31 08:52:57.199  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 08:52:57.199  1019  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
,08-31 08:52:57.199  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-31 08:52:57.199  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-31 08:52:57.199  1019  1133 D Tethering: MasterInitialState.processMessage what=3
,08-31 08:52:57.199  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:57.199  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:57.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:57.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:57.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:57.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:57.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:57.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:57.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:57.199  1019  1125 V NetworkStats: updateIfacesLocked()
08-31 08:52:57.199  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.199  1019  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-31 08:52:57.209  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:52:57.209  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:52:57.209  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
08-31 08:52:57.209  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 08:52:57.209  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 08:52:57.209  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:57.209  1182  1182 D StatusBar.NetworkController: updateDataNetType()
08-31 08:52:57.209  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:57.209  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.209  1019  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:57.209  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.209  1019  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-31 08:52:57.209  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.209  1019  1125 V NetworkStats: performPollLocked() took 6ms
08-31 08:52:57.209  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.209  1019  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 08:52:57.209  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.209  1019  1461 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:57.209  1019  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:57.209  1019  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:57.209  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-31 08:52:57.209  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 08:52:57.209  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 08:52:57.209  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 08:52:57.209  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 08:52:57.219  1019  4381 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:57.219  1019  4381 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-31 08:52:57.219  1019  4381 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:57.219  1019  4381 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:57.219  1019  4381 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:57.219  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 08:52:57.219  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 08:52:57.219  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 08:52:57.219  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService,
08-31 08:52:57.219  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.219  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.219  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 16 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-31 08:52:57.219  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-31 08:52:57.219  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-31 08:52:57.219  1019  4378 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:57.219  1019  4378 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 08:52:57.229  1019  4378 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:57.229  1019  4378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:57.229  1019  4378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:52:57.229  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 08:52:57.229  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:52:57.229  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:52:57.229  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:57.229  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.229  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.229  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.229  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-31 08:52:57.229  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 08:52:57.229  3200  3275 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 08:52:57.229  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:57.229  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 08:52:57.229  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:57.229  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:57.229  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:57.229  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:52:57.229  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:52:57.229  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:52:57.229  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:52:57.229  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:52:57.229  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:52:57.229  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,08-31 08:52:57.229  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 08:52:57.229  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 08:52:57.239  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 08:52:57.239  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 08:52:57.239  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 08:52:57.239  3200  3275 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 08:52:57.239  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-31 08:52:57.239  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:52:57.239  3200  3200 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 08:52:57.239  1381  1381 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 08:52:57.239  3200  3200 D A2dpService: Received stop request...Stopping profile...
,08-31 08:52:57.239  3200  3361 D A2dpStateMachine: Exit Disconnected: -1
,08-31 08:52:57.239  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:52:57.249  1019  1019 D BluetoothA2dp: Proxy object disconnected
08-31 08:52:57.249  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 08:52:57.249  4872  4872 D BluetoothA2dp: Proxy object disconnected
08-31 08:52:57.249  4872  4872 D A2dpProfile: Bluetooth service disconnected
,08-31 08:52:57.249  3200  3200 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 08:52:57.249  3200  3200 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 08:52:57.249  3200  3200 D HidService: Received stop request...Stopping profile...
08-31 08:52:57.249  3200  3200 D HidService: Stopping Bluetooth HidService
08-31 08:52:57.249  3200  3200 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 08:52:57.249  3200  3200 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 08:52:57.249  3200  3200 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 08:52:57.249  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:52:57.249  3200  3200 D HealthService: Received stop request...Stopping profile...
,08-31 08:52:57.259  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:52:57.259  4872  4872 D BluetoothInputDevice: Proxy object disconnected
08-31 08:52:57.259  4872  4872 D HidProfile: Bluetooth service disconnected
,08-31 08:52:57.259  3200  3200 D PanService: Received stop request...Stopping profile...
08-31 08:52:57.259  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:52:57.259  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 08:52:57.269  3200  3200 D BluetoothMapService: Received stop request...Stopping profile...
08-31 08:52:57.269  4872  4872 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 08:52:57.269  4872  4872 D PanProfile: Bluetooth service disconnected
,08-31 08:52:57.269  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:52:57.269  3200  3200 D SapService: Received stop request...Stopping profile...
08-31 08:52:57.269  3200  3200 D SapService: Stopping Bluetooth SapService
08-31 08:52:57.269  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
08-31 08:52:57.269  4872  4872 D BluetoothMap: Proxy object disconnected
08-31 08:52:57.269  4872  4872 D MapProfile: Bluetooth service disconnected
,08-31 08:52:57.269  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-31 08:52:57.269  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:52:57.269  3200  3200 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 08:52:57.269  3200  3362 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 08:52:57.269  3200  3200 I GKI_LINUX: GKI_exit_task 2 done
08-31 08:52:57.269  3200  3200 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-31 08:52:57.279  3200  3200 D BluetoothA2dp: Proxy object disconnected
,08-31 08:52:57.279  3200  3200 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-31 08:52:57.279  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 08:52:57.279  3200  3200 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-31 08:52:57.279  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:52:57.279  3200  3200 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 08:52:57.279  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-31 08:52:57.279  3200  3200 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 08:52:57.279  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:52:57.279  3200  3200 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 08:52:57.279  3200  3200 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 08:52:57.279  3200  3200 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 08:52:57.279  4872  4872 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-31 08:52:57.279  4872  4872 D SapProfile: Bluetooth service disconnected
08-31 08:52:57.279  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 08:52:57.279  3200  3200 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 08:52:57.279  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:52:57.279  3200  3200 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-31 08:52:57.279  3200  3200 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 08:52:57.279  3200  3200 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 08:52:57.279  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-31 08:52:57.279  3200  3200 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 08:52:57.279  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 08:52:57.279  3200  3200 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-31 08:52:57.279  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-31 08:52:57.279  3200  3200 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 08:52:57.279  1381  1381 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 08:52:57.279  3200  3200 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 08:52:57.279  3200  3200 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-31 08:52:57.279  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:52:57.279  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:52:57.279  3200  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-31 08:52:57.279  3200  3275 D BluetoothAdapterProperties: Setting state to 10
08-31 08:52:57.279  3200  3275 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 08:52:57.279  3200  3275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:52:57.279  3200  3275 D BluetoothAdapterService: updateAdapterState state is 10
08-31 08:52:57.279  3200  3275 D BluetoothAdapterService: Autoconnection is available 
08-31 08:52:57.279  3200  3275 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-31 08:52:57.279  3200  3275 I BluetoothAdapterState: Entering OffState
,08-31 08:52:57.279  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 08:52:57.279  3200  3211 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 08:52:57.289  7379  7388 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:57.289  7379  7388 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:57.289  7379  7388 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-31 08:52:57.289  7379  7388 D BluetoothLeAdvertiser: Exit stop advertising
08-31 08:52:57.289  7379  7388 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-31 08:52:57.289  7379  7388 D BluetoothLeScanner: Exiting stopAllScan
08-31 08:52:57.289  4872  4880 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 08:52:57.289  1433  1452 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:57.289  1433  1452 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:57.289  1460  4802 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:57.289  1460  4802 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:52:57.299  1182  1191 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:52:57.299  1182  1191 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:52:57.299  4872  4880 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 08:52:57.299  4872  4882 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 08:52:57.299  4872  4882 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:57.299  4872  4882 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:52:57.309  1381  1381 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-31 08:52:57.309  1381  1381 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-31 08:52:57.309  1381  1381 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 08:52:57.309  1381  1381 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-31 08:52:57.309  1381  1381 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 08:52:57.309  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:52:57.309  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:52:57.309  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:52:57.309  1019  1133 D Tethering: InitialState.processMessage what=4
,08-31 08:52:57.309  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 08:52:57.309  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:52:57.309  1743  1754 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:57.309  1743  1754 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
08-31 08:52:57.309  1019  1133 E Tethering: No numeric data
08-31 08:52:57.309  3200  3370 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:57.309  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:52:57.309  3200  3370 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:52:57.309  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 08:52:57.309  1019  1133 D Tethering: clearTetheredNotification()
08-31 08:52:57.309  4872  4880 D Bluetoothsap: onBluetoothStateChange: up=false
08-31 08:52:57.309  4872  4880 D Bluetoothsap: Unbinding service...
08-31 08:52:57.309  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:52:57.309  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:52:57.309  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 08:52:57.319  1019  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:52:57.319  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:57.319  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-31 08:52:57.319  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 08:52:57.319  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:52:57.319  1182  1182 D HotspotTile: updateTetherState():false, false
08-31 08:52:57.319  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 08:52:57.319  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 08:52:57.319  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:57.319  1019  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:57.319  1444  1477 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:57.319  1444  1477 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:57.319  7379  7379 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 08:52:57.319  4872  4882 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 08:52:57.319  1019  1125 V NetworkStats: performPollLocked() took 4ms
08-31 08:52:57.319  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.319  1657  4383 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:57.319  1657  4383 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:57.319  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:52:57.319  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:57.319  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:57.319  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.329  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 08:52:57.329  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:57.329  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
08-31 08:52:57.329  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-31 08:52:57.329  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.329  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:52:57.329  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.329  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:52:57.329  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 08:52:57.329  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:57.329  1182  1182 D BluetoothTile:  getBluetoothState : 10
,08-31 08:52:57.339  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.339  1880  1880 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:52:57.339  4872  4872 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:57.339  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 08:52:57.339  1019  1461 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 08:52:57.339  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.339  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:57.339  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:57.339  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:57.339  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:57.339  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:57.339  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:57.339  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:57.339  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:57.339  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:57.339  1019  1484 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 08:52:57.339  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:52:57.339  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 08:52:57.339  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.349  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 08:52:57.349  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:52:57.349  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:57.349  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:57.349  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:57.349  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:57.349  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:57.349  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:57.349  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:57.349  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:57.349  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.349  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 08:52:57.349  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.349  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 08:52:57.349  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.349  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:52:57.349  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.359   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 08:52:57.359   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:52:57.359  7469  7489 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 08:52:57.359  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 08:52:57.359  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.359  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 08:52:57.359  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.359  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:52:57.359  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 08:52:57.359   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 08:52:57.359   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:52:57.359  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-31 08:52:57.359  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:52:57.359  7469  7489 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
08-31 08:52:57.359  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:52:57.369  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:52:57.419   289   289 E SMD     : DCD OFF,
,08-31 08:52:57.449  1381  1381 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 08:52:57.509  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:52:57.509  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:52:57.509  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:52:57.509  1381  1381 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-31 08:52:57.529  7469  7469 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:52:57.529  7469  7469 D StrictMode: ,	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331),
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209),
08-31 08:52:57.529  7469  7469 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
,08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:52:57.529  7469  7469 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:52:57.529  1019  1484 I ActivityManager: Killing 6963:com.google.android.apps.docs/u0a87 (adj 1,5): empty #21
08-31 08:52:57.529  7469  7469 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:52:57.539  1019  1461 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:52:57.529  7469  7469 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:52:57.539  1019  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:52:57.529  7469  7469 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:52:57.529  7469  7469 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:52:57.529  7469  7469 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:52:57.529  7469  7469 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:57.529  7469  7469 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:52:57.539  1019  1461 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:57.539  1019  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:57.539  1019  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 08:52:57.539  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 08:52:57.549  1638  1638 I Hs20UtilService: Starting #8
08-31 08:52:57.549  1638  1695 I Hs20UtilService: Message received 5007
08-31 08:52:57.549  4872  4872 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 08:52:57.549  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 08:52:57.549  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 08:52:57.549  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:52:57.549  4872  4872 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 08:52:57.549  4872  4917 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 08:52:57.559  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 08:52:57.559  4872  4872 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 08:52:57.569  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 08:52:57.569  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 08:52:57.569  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:52:57.569  4872  4872 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 08:52:57.569  4872  4917 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 08:52:57.569  1019  1265 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-31 08:52:57.569  1019  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:57.569  1019  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:57.569  1019  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:57.569  1019  1265 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:57.579  7516  7516 E Zygote  : MountEmulatedStorage()
08-31 08:52:57.579  7516  7516 E Zygote  : v2
08-31 08:52:57.579  7516  7516 I libpersona: KNOX_SDCARD checking this for 10064
08-31 08:52:57.579  7516  7516 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:57.589  7516  7516 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:52:57.589  7516  7516 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:52:57.589  7516  7516 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:52:57.589  7469  7510 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-31 08:52:57.599  1019  1265 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7516 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 08:52:57.609  7516  7516 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:57.609  7516  7516 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:57.619  1019  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-31 08:52:57.619  1019  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 08:52:57.629  4872  4872 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:52:57.629  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:57.639  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:52:57.639  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:52:57.639  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:52:57.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:57.639  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:57.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:57.639  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:52:57.639  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-31 08:52:57.639  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:52:57.639  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 08:52:57.639  1182  1182 D HotspotTile: onReceive : 1, 0
,08-31 08:52:57.639  1743  2198 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:52:57.649  1019  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:52:57.649  1019  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:57.649  1019  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 08:52:57.649  1019  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 08:52:57.659  7516  7516 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 08:52:57.679  7516  7516 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:52:57.679  7516  7516 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 08:52:57.699  1019  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:57.699  1019  1019 I ApplicationPolicy: updateDataUsageMap
,08-31 08:52:57.709  7516  7516 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 08:52:57.719  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:57.719  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:57.719  1019  1471 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-31 08:52:57.729  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:57.729  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:57.729  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:57.729  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:57.739  1019  1471 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7533 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 08:52:57.739  1019  1471 I ActivityManager: Killing 6863:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-31 08:52:57.739  7533  7533 E Zygote  : MountEmulatedStorage()
08-31 08:52:57.739  7533  7533 I libpersona: KNOX_SDCARD checking this for 10065
08-31 08:52:57.739  7533  7533 E Zygote  : v2
08-31 08:52:57.739  7533  7533 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:57.739  7533  7533 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:57.749  1019  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:57.749  7533  7533 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:52:57.749  7533  7533 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:52:57.779  7533  7533 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:57.779  7533  7533 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:57.809  1019  1484 I art     : Explicit concurrent mark sweep GC freed 68489(4MB) AllocSpace objects, 35(608KB) LOS objects, 33% free, 23MB/35MB, paused 3.148ms total 189.278ms
,08-31 08:52:57.819  7533  7533 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:52:57.829  1019  4377 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:57.829  1019  4377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 08:52:57.829  1019  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-31 08:52:57.829  1019  4377 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-31 08:52:57.829  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:57.829  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:57.829  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:57.829  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:57.849  7549  7549 E Zygote  : MountEmulatedStorage(),
08-31 08:52:57.849  7549  7549 E Zygote  : v2
08-31 08:52:57.849  7549  7549 I libpersona: KNOX_SDCARD checking this for 10102
08-31 08:52:57.849  7549  7549 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:57.849  7549  7549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 08:52:57.849  1019  4377 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7549 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 08:52:57.849  7549  7549 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:57.849  7549  7549 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:52:57.849  1019  4377 I ActivityManager: Killing 7060:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-31 08:52:57.869  7549  7549 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:57.869  7549  7549 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:57.889  7549  7549 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 08:52:58.069  7549  7569 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-31 08:52:58.069  7549  7569 I Babel_SMS: MmsConfig.loadMmsSettings
,08-31 08:52:58.079  7549  7569 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-31 08:52:58.079  7549  7569 I Babel_SMS: MmsConfig.loadFromDatabase
,08-31 08:52:58.089  7549  7569 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-31 08:52:58.089  7549  7569 I Babel_SMS: MmsConfig.loadFromResources
,08-31 08:52:58.089  7549  7569 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 08:52:58.089  7549  7569 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-31 08:52:58.119  1019  1471 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-31 08:52:58.119  1019  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-31 08:52:58.119  1019  1471 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.119  1019  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:58.119  1019  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 08:52:58.139  7549  7549 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:52:58.149  7549  7549 I Babel_Crash: startup - clean
,08-31 08:52:58.179  1019  1461 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:52:58.179  1019  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:52:58.179  1019  1461 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.179  1019  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:58.179  1019  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:52:58.179  1638  1638 I Hs20UtilService: Starting #9
,08-31 08:52:58.179  1638  1695 I Hs20UtilService: Message received 5007
,08-31 08:52:58.179  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 08:52:58.179  4872  4872 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:52:58.179  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:52:58.189  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:52:58.189  1019  1047 D Tethering: interfaceRemoved wlan0
,08-31 08:52:58.189  1019  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 08:52:58.189  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:52:58.189  4872  4872 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 08:52:58.189  4872  4917 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:52:58.199  7549  7549 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:52:58.199  1019  1138 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:52:58.199  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:52:58.199  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.199  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.199  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:52:58.199  7549  7549 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 08:52:58.199  1019  4378 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-31 08:52:58.199  7549  7549 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 08:52:58.199  1019  4378 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:58.199  1019  4378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:58.199  1638  1638 I Hs20UtilService: Starting #10
08-31 08:52:58.199  1019  4378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:58.199  1019  4378 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:58.199  1638  1695 I Hs20UtilService: Message received 5011
,08-31 08:52:58.209  7549  7549 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-31 08:52:58.209  7549  7549 W AudioCapabilities: Unsupported mime audio/mpeg-L2
08-31 08:52:58.209  7549  7549 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-31 08:52:58.209  7549  7549 W AudioCapabilities: Unsupported mime audio/x-ima
,08-31 08:52:58.219  7549  7549 W AudioCapabilities: Unsupported mime audio/qcelp,
08-31 08:52:58.219  7572  7572 I libpersona: KNOX_SDCARD checking this for 1000
08-31 08:52:58.219  7572  7572 E Zygote  : MountEmulatedStorage(),
08-31 08:52:58.219  7572  7572 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:58.219  7572  7572 E Zygote  : v2
08-31 08:52:58.219  7572  7572 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:58.219  7549  7549 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 08:52:58.219  7572  7572 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:52:58.219  7572  7572 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 08:52:58.229  1019  4378 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7572 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 08:52:58.229  7549  7549 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 08:52:58.229  7549  7549 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 08:52:58.239  7549  7549 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-31 08:52:58.239  7572  7572 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:58.239  7572  7572 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:58.239  7549  7549 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 08:52:58.249  7549  7549 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 08:52:58.249  7549  7549 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-31 08:52:58.249  7549  7549 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-31 08:52:58.259  7549  7549 W VideoCapabilities: Unsupported mime video/mp43
,08-31 08:52:58.259  7549  7549 W VideoCapabilities: Unsupported mime video/sorenson
,08-31 08:52:58.269  7549  7549 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-31 08:52:58.279  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 08:52:58.279  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 08:52:58.279  7572  7572 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 08:52:58.279  7572  7572 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:52:58.289  1019  4380 I ActivityManager: Killing 7083:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-31 08:52:58.289  1019  4377 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:58.289  1019  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.289  1019  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.299  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.299  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.299  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.299  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:58.299  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.299  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.299  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:58.299  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.299  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.299  7549  7549 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 08:52:58.309  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:58.309  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.309  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.309  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:58.309  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.309  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.319  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:58.319  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.319  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.319  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:58.319  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.319  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.319  7549  7549 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:52:58.329  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.329  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.329  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.329  7549  7549 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:52:58.329  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.329  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.329  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.329  7549  7549 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:52:58.329  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.329  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.329  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.329  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.329  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.329  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.339  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.339  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.339  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.339  7549  7549 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:52:58.339  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.339  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.339  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.339  1019  1350 I ActivityManager: Killing 7100:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-31 08:52:58.339  7549  7549 I vclib   : onServiceConnected
,08-31 08:52:58.349  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.349  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.349  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:52:58.349  4872  4872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:52:58.349  1019  1484 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 08:52:58.349  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-31 08:52:58.359  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.359  1019  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.359  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:52:58.359  1657  1657 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:58.359  4872  4872 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:52:58.359  4872  4872 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:52:58.369  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:58.369  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 08:52:58.379  1019  1138 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:52:58.379  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:52:58.379  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:58.379  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:58.379  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:52:58.379  1638  1638 I Hs20UtilService: Starting #11
,08-31 08:52:58.389  1638  1695 I Hs20UtilService: Message received 5011
,08-31 08:52:58.389  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 08:52:58.389  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 08:52:58.389  7572  7572 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:52:58.389  7572  7572 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:52:58.399  1019  1047 D Tethering: interfaceRemoved p2p0
,08-31 08:52:58.399  1019  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 08:52:58.399  1019  1506 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 08:52:58.399  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:58.399  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:58.399  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:58.399  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:58.409  7590  7590 E Zygote  : MountEmulatedStorage()
08-31 08:52:58.409  7590  7590 I libpersona: KNOX_SDCARD checking this for 1000
08-31 08:52:58.409  7590  7590 E Zygote  : v2
08-31 08:52:58.409  7590  7590 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:58.409  7590  7590 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:52:58.409  1019  1506 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7590 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 08:52:58.419  7590  7590 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:58.419  7590  7590 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:52:58.429  1743  2694 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-31 08:52:58.429  7590  7590 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:58.429  7590  7590 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:58.459  7590  7590 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-31 08:52:58.459  7590  7590 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 08:52:58.459  7590  7590 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 08:52:58.469  7590  7590 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-31 08:52:58.469  7590  7590 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-31 08:52:58.469  7590  7590 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-31 08:52:58.469  7590  7590 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:58.469  1019  1265 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-31 08:52:58.469  1019  1265 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-31 08:52:58.469  1019  1265 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-31 08:52:58.469  1019  1265 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
08-31 08:52:58.479  7590  7605 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-31 08:52:58.479  1019  1265 I ActivityManager: Killing 7118:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-31 08:52:58.479  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 08:52:58.479  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:58.489  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:58.489  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:58.489  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:58.499  7607  7607 E Zygote  : MountEmulatedStorage()
08-31 08:52:58.499  7607  7607 E Zygote  : v2
08-31 08:52:58.499  7607  7607 I libpersona: KNOX_SDCARD checking this for 10001
08-31 08:52:58.499  7607  7607 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:58.499  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7607 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 08:52:58.499  7607  7607 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:58.509  7607  7607 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:52:58.509  7607  7607 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 08:52:58.529  7607  7607 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:58.529  7607  7607 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:58.599  1019  1484 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-31 08:52:58.599  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:58.599  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:58.599  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:58.599  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:58.609  7624  7624 E Zygote  : MountEmulatedStorage(),
08-31 08:52:58.609  7624  7624 I libpersona: KNOX_SDCARD checking this for 1000
,08-31 08:52:58.609  7624  7624 E Zygote  : v2
08-31 08:52:58.609  7624  7624 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:58.609  7624  7624 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:58.609  1019  1484 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7624 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 08:52:58.619  1019  1484 I ActivityManager: Killing 7150:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-31 08:52:58.619  7624  7624 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:52:58.619  7624  7624 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:52:58.629  7624  7624 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-31 08:52:58.639  7624  7624 D ActivityThread: Added TimaKeyStore provider,
,08-31 08:52:58.679  7624  7624 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 08:52:58.819  7624  7624 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 08:52:58.819  7624  7624 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-31 08:52:58.829  7624  7624 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:58.829  7624  7624 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 08:52:58.829  7624  7624 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-31 08:52:58.829  7624  7624 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-31 08:52:58.829  1019  1506 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-31 08:52:58.829  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:58.829  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:58.829  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:58.829  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:58.849  7640  7640 E Zygote  : MountEmulatedStorage(),
,08-31 08:52:58.849  1019  1506 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7640 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-31 08:52:58.849  1019  1506 I ActivityManager: Killing 7034:com.android.mms/u0a41 (adj 15): empty #21
08-31 08:52:58.849  7640  7640 E Zygote  : v2
08-31 08:52:58.849  7640  7640 I libpersona: KNOX_SDCARD checking this for 10008
08-31 08:52:58.849  7640  7640 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:58.849  7640  7640 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:58.849  7640  7640 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:58.859  7640  7640 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 08:52:58.869  7640  7640 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:58.879  7640  7640 D ActivityThread: Added TimaKeyStore provider,
,08-31 08:52:58.899  1019  1098 V AlarmManager: waitForAlarm result :4
,08-31 08:52:58.899  1019  1019 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-31 08:52:58.899  1019  1019 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-31 08:52:58.899  1019  1019 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-31 08:52:58.899  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-31 08:52:58.909  1182  1182 D KeyguardUpdateMonitor: handleTimeUpdate
,08-31 08:52:58.909  1182  1182 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-31 08:52:58.909  1182  1182 D SecKeyguardClockView: HomeTimezone(): 1
,08-31 08:52:58.909  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 08:52:58.919  1182  1182 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-31 08:52:58.919  1182  1182 I KeyguardEffectViewController: *** don't update sliding image ***
,08-31 08:52:58.949  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 08:52:58.949  1019  1495 I ActivityManager: Killing 7168:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-31 08:52:58.949  1019  1265 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-31 08:52:58.949  1019  1265 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 08:52:58.949  1019  1265 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:58.949  1019  1265 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:58.949  1019  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 08:52:58.959  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 08:52:58.969  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 08:52:58.979  1019  1031 D CountryDetector: No listener is left
,08-31 08:52:58.989  3872  7656 I iu.SyncManager: SYNC; picasa accounts
,08-31 08:52:58.989  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 08:52:58.999  3872  3872 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-31 08:52:59.019  1019  1461 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:52:59.019  1019  1461 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-31 08:52:59.019  1019  1461 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:59.019  1019  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:59.019  1019  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:52:59.029  3872  3872 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 08:52:59.029  3872  3872 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-31 08:52:59.039  2845  2845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 08:52:59 GMT+02:00 2016
,08-31 08:52:59.039  1019  4378 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-31 08:52:59.039  1019  4378 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 08:52:59.039  1019  4378 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:59.039  1019  4378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:59.039  1019  4378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 08:52:59.049  2845  2845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 08:52:59.049  2845  2845 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 08:52:59.049  2845  2845 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 08:52:59.059  1019  1385 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-31 08:52:59.059  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:59.059  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:59.059  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:59.059  1019  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:59.069  2845  2845 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,08-31 08:52:59.069  2845  7658 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 08:52:59.069  2845  7658 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-31 08:52:59.069  7659  7659 E Zygote  : MountEmulatedStorage(),
08-31 08:52:59.069  7659  7659 E Zygote  : v2
08-31 08:52:59.069  7659  7659 I libpersona: KNOX_SDCARD checking this for 10031
08-31 08:52:59.069  7659  7659 I libpersona: KNOX_SDCARD not a persona,
08-31 08:52:59.069  7659  7659 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:59.079  7659  7659 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 08:52:59.079  2845  7658 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-31 08:52:59.079  7659  7659 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:52:59.079  2845  7658 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
08-31 08:52:59.079  1019  1385 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7659 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-31 08:52:59.089  2845  2845 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 08:52:59.109   308   308 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 27.095ms
,08-31 08:52:59.109  7659  7659 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:59.109  7659  7659 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:59.119   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.718ms
,08-31 08:52:59.139   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.384ms
,08-31 08:52:59.139  1019  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
08-31 08:52:59.139  7659  7659 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-31 08:52:59.139  1019  1506 I ActivityManager: Killing 7203:com.wsomacp/u0a23 (adj 15): empty #21
,08-31 08:52:59.159  1019  1461 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-31 08:52:59.159  1019  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:59.159  1019  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:59.159  1019  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:59.159  1019  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:59.159  2782  7674 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false,
,08-31 08:52:59.169  2782  7674 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-31 08:52:59.169  2782  7674 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-31 08:52:59.169  2782  7674 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-31 08:52:59.169  7675  7675 E Zygote  : MountEmulatedStorage()
,08-31 08:52:59.169  7675  7675 E Zygote  : v2
08-31 08:52:59.169  7675  7675 I libpersona: KNOX_SDCARD checking this for 10032
08-31 08:52:59.169  7675  7675 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:59.169  7675  7675 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:59.169  1019  1461 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7675 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-31 08:52:59.179  7675  7675 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:59.179  7675  7675 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-31 08:52:59.179  2782  7674 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-31 08:52:59.199  7675  7675 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 08:52:59.199  7675  7675 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:59.259  7675  7690 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-31 08:52:59.259  7675  7690 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-31 08:52:59.259  7675  7675 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-31 08:52:59.269  1019  1461 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-31 08:52:59.269  1019  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:59.269  1019  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:59.269  1019  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:59.269  1019  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:59.269  7675  7690 D SPPClientService: PushLog.txt file is not deleted.
,08-31 08:52:59.269  7675  7690 D SPPClientService: PushLog.txt file is not deleted.
08-31 08:52:59.269  7675  7690 D SPPClientService: ============PushLog. stop!
,08-31 08:52:59.289  7692  7692 E Zygote  : MountEmulatedStorage(),
08-31 08:52:59.289  7692  7692 E Zygote  : v2
08-31 08:52:59.289  7692  7692 I libpersona: KNOX_SDCARD checking this for 10036
,08-31 08:52:59.289  7692  7692 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:59.289  7692  7692 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:59.289  1019  1461 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7692 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 08:52:59.299  7692  7692 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:52:59.299  7692  7692 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-31 08:52:59.299  1019  1461 I ActivityManager: Killing 7224:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
08-31 08:52:59.299  1019  1471 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-31 08:52:59.299  1019  1471 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:59.299  1019  1471 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-31 08:52:59.299  1019  1471 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 08:52:59.299  1019  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push,
,08-31 08:52:59.319  7692  7692 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:59.319  7692  7692 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:59.329  7675  7701 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-31 08:52:59.349  7692  7692 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@a750cab
,08-31 08:52:59.359  7692  7692 I SA      : [SSP] onCreated
,08-31 08:52:59.369  7692  7692 I SA      : [TPM] There is no property file
,08-31 08:52:59.369  7692  7692 I SA      : [SCU] isHaveSA() - false
,08-31 08:52:59.379  7692  7692 I SA      : [TPM] getModelProperty : null
,08-31 08:52:59.379  7692  7692 I SA      : [TPM] getCSCProperty : null
,08-31 08:52:59.379  7692  7692 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-31 08:52:59.379  7692  7692 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-31 08:52:59.379  7692  7692 I SA      : [DM] TFT FEATURE: false
,08-31 08:52:59.379  7692  7692 I SA      : [DM] init START
,08-31 08:52:59.379  7692  7692 I SA      : [DM] This device is not a Vodafone
,08-31 08:52:59.389  7692  7692 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-31 08:52:59.389  7692  7692 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-31 08:52:59.389  7692  7692 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-31 08:52:59.389  7692  7692 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-31 08:52:59.389  7692  7692 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-31 08:52:59.389  7692  7692 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-31 08:52:59.389  7692  7692 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-31 08:52:59.389  7692  7692 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 08:52:59.389  7692  7692 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-31 08:52:59.389  7692  7692 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-31 08:52:59.399  7692  7692 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-31 08:52:59.409  7692  7692 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-31 08:52:59.409  7692  7692 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-31 08:52:59.409  7692  7692 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-31 08:52:59.409  7692  7692 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-31 08:52:59.409  7692  7692 I SA      : [SCU] isHaveSA() - false
08-31 08:52:59.409  7692  7692 I SA      : support phone number id : false
08-31 08:52:59.409  7692  7692 I SA      : [DM] Supports Ref Jpn : true
,08-31 08:52:59.409  7692  7692 I SA      : [DM] init END
08-31 08:52:59.409  7692  7692 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-31 08:52:59.419  7692  7692 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-31 08:52:59.419  7692  7692 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 08:52:59.419  7692  7692 I SA      : [SLFUCHKMGR] constructor called
,08-31 08:52:59.429  7692  7692 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 08:52:59.429  7692  7692 I SA      : [OR] == isSIMCardReady false ==
,08-31 08:52:59.429  7692  7692 I SA      : [SCU] == networkStateCheck == false
,08-31 08:52:59.429  7692  7692 I SA      : [OR] onReceive END
,08-31 08:52:59.429  1019  1484 I ActivityManager: Killing 7297:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-31 08:52:59.439  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:59.439  1781  1781 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 08:52:59.449  2545  2557 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-31 08:52:59.449  1781  1781 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-31 08:52:59.449  1781  1781 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-31 08:52:59.449  1781  1781 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-31 08:52:59.459  1781  1781 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-31 08:52:59.459  1781  1781 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 08:52:59.459  1781  1781 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-31 08:52:59.459  1019  1471 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-31 08:52:59.469  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:59.469  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:59.469  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:59.469  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:59.479  7714  7714 E Zygote  : MountEmulatedStorage(),
08-31 08:52:59.479  1019  1471 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7714 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 08:52:59.479  7714  7714 E Zygote  : v2
08-31 08:52:59.479  7714  7714 I libpersona: KNOX_SDCARD checking this for 10077
08-31 08:52:59.479  7714  7714 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:59.479  7714  7714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:59.489  7714  7714 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:52:59.489  7714  7714 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-31 08:52:59.499  7714  7714 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-31 08:52:59.499  7714  7714 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:59.699  1019  4378 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-31 08:52:59.699  1019  4378 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-31 08:52:59.699  1019  4378 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:59.699  1019  4378 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:59.699  1019  4378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 08:52:59.699  1019  4377 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-31 08:52:59.699  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:59.699  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:59.699  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:59.699  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:59.719  7734  7734 E Zygote  : MountEmulatedStorage()
,08-31 08:52:59.719  7734  7734 E Zygote  : v2
08-31 08:52:59.719  7734  7734 I libpersona: KNOX_SDCARD checking this for 10110
08-31 08:52:59.719  7734  7734 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:59.719  1019  4377 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7734 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-31 08:52:59.719  1019  1265 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
08-31 08:52:59.719  7734  7734 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 08:52:59.719  1019  1265 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-31 08:52:59.719  1019  1265 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:59.719  1019  1265 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 08:52:59.719  1019  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-31 08:52:59.719  7734  7734 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:59.719  7549  7733 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-31 08:52:59.719  7734  7734 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:52:59.729  1019  1032 I ActivityManager: Killing 7257:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-31 08:52:59.739  7734  7734 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:59.739  7734  7734 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:59.869  1019  1484 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 08:52:59.909  1019  4381 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 08:52:59.909  1019  4381 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 08:52:59.909  1019  4381 D SecContentProvider2: mCursor = null
,08-31 08:52:59.909  1019  4381 D WifiService: setWifiEnabled: true pid=7379, uid=10170
08-31 08:52:59.909  1019  4381 W ActivityManager: Permission Denial: getCurrentUser() from pid=7379, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:52:59.909  1019  4381 W WifiService: Failed getting userId using ActivityManagerNative
08-31 08:52:59.909  1019  4381 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7379, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:52:59.909  1019  4381 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 08:52:59.909  1019  4381 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 08:52:59.909  1019  4381 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 08:52:59.909  1019  4381 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 08:52:59.909  1019  4381 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 08:52:59.909  1019  4381 D SettingsProvider: name = wifi_on
,08-31 08:52:59.919  1019  1128 E WifiHW  : ##################### set firmware type 0 #####################,
,08-31 08:52:59.989  1019  1098 V AlarmManager: waitForAlarm result :8
,08-31 08:53:00.019  7734  7734 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 08:53:00.019  7734  7734 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 08:53:00.019  7734  7734 I GAv4    :   adb logcat -s GAv4
,08-31 08:53:00.039  7734  7734 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 08:53:00.039  1019  1506 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 08:53:00.049   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 08:53:00.049   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:53:00.049  7734  7753 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 08:53:00.049   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 08:53:00.049   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:53:00.059  7734  7753 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 08:53:00.069  7734  7734 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 08:53:00.079  7734  7756 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 08:53:00.079   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 08:53:00.079   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:53:00.079  7734  7755 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 08:53:00.079   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 08:53:00.079   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:53:00.089  7734  7755 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 08:53:00.279  1019  1047 D Tethering: interfaceAdded wlan0
,08-31 08:53:00.289  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 08:53:00.289  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:53:00.289  1019  1133 E Tethering: No numeric data
,08-31 08:53:00.289  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 08:53:00.299  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 08:53:00.299  1019  1133 D Tethering: clearTetheredNotification()
08-31 08:53:00.299  1019  1133 D Tethering: InitialState.processMessage what=4
,08-31 08:53:00.299  1019  1133 E Tethering: No numeric data
,08-31 08:53:00.299  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:00.299  1019  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:53:00.299  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:53:00.299  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
08-31 08:53:00.299  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:00.299  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:53:00.299  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 08:53:00.299  1019  1125 V NetworkStats: performPollLocked() took 3ms,
08-31 08:53:00.299  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-31 08:53:00.299  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 08:53:00.299  1019  1047 D Tethering: interfaceAdded p2p0
,08-31 08:53:00.299  1182  1182 D HotspotTile: updateTetherState():false, false
08-31 08:53:00.299  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 08:53:00.299  1019  1133 D Tethering: clearTetheredNotification()
08-31 08:53:00.299  1019  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
08-31 08:53:00.299   279   979 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 08:53:00.299  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:00.299   279   979 D SoftapController: Softap fwReload - Ok
08-31 08:53:00.299  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:00.309   279   979 D CommandListener: Setting iface cfg
08-31 08:53:00.309   279   979 D CommandListener: Trying to bring down wlan0
08-31 08:53:00.309  1019  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:53:00.309  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:00.309  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 08:53:00.309  1182  1182 D HotspotTile: updateTetherState():false, false
,08-31 08:53:00.309  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:00.309   279   979 D CommandListener: Clearing all IP addresses on wlan0
08-31 08:53:00.309  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:53:00.309  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:00.309  1019  1125 V NetworkStats: performPollLocked() took 3ms
,08-31 08:53:00.309  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:00.309  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:00.309  1019  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 08:53:00.309  1019  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-31 08:53:00.319  1019  1128 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
,08-31 08:53:00.329  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:53:00.329  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:00.329  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:53:00.329  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:00.329  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:00.329  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:00.329  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:00.329  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:53:00.329  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-31 08:53:00.329  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:53:00.329  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 08:53:00.329  1182  1182 D HotspotTile: onReceive : 2, 0
,08-31 08:53:00.339  4872  4872 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:53:00.339  1019  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:53:00.339  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:00.339  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:00.339  1019  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:00.339  1019  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:00.339  1019  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-31 08:53:00.389  7734  7734 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-31 08:53:00.389  7778  7778 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 08:53:00.389  7778  7778 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 08:53:00.389  7778  7778 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 08:53:00.399  7778  7778 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-31 08:53:00.409   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7778,
08-31 08:53:00.409   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-31 08:53:00.409  7778  7778 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 08:53:00.409  7778  7778 I wpa_supplicant: ssSupport state is = 1
,08-31 08:53:00.409  7778  7778 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 08:53:00.409  7778  7778 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-31 08:53:00.409  7734  7734 I cr.library_loader: Time to load native libraries: 4 ms (timestamps 2938-2942)
08-31 08:53:00.409  7734  7734 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 08:53:00.409   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7778
08-31 08:53:00.409   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-31 08:53:00.419  7734  7734 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c9b6212},
08-31 08:53:00.419  7734  7734 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 08:53:00.419  7734  7734 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 08:53:00.419   289   289 E SMD     : DCD OFF,
,08-31 08:53:00.439  7734  7734 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 08:53:00.439  7734  7734 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 08:53:00.439  7734  7734 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 08:53:00.459  7734  7734 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 08:53:00.459  7734  7734 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 08:53:00.459  7734  7734 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 08:53:00.459  7734  7734 I Adreno-EGL: Local Branch: 
08-31 08:53:00.459  7734  7734 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 08:53:00.459  7734  7734 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 08:53:00.459  7734  7734 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 08:53:00.579   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-31 08:53:00.579  7778  7778 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-31 08:53:00.589  7734  7793 W cr.media: Requires BLUETOOTH permission
,08-31 08:53:00.609  7734  7734 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 08:53:00.619  7734  7734 I NSApplication: Starting up...
,08-31 08:53:00.619  1019  1484 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 08:53:00.619  1019  1461 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 08:53:00.629  1019  3368 D SSRM:n  : SIOP:: AP = 320
,08-31 08:53:00.629  7778  7778 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 08:53:00.629  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
08-31 08:53:00.629  7778  7778 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 08:53:00.629  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 08:53:00.629  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:00.629  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 08:53:00.629  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:00.649  7799  7799 E Zygote  : MountEmulatedStorage()
,08-31 08:53:00.649  7799  7799 E Zygote  : v2
08-31 08:53:00.649  7799  7799 I libpersona: KNOX_SDCARD checking this for 10117
08-31 08:53:00.649  7799  7799 I libpersona: KNOX_SDCARD not a persona
,08-31 08:53:00.649  7799  7799 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:53:00.649  1019  1031 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7799 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 08:53:00.649  1019  1031 I ActivityManager: Killing 7276:com.android.calendar/u0a131 (adj 15): empty #21,
08-31 08:53:00.649  7778  7778 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-31 08:53:00.649  7799  7799 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 08:53:00.649   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7778
08-31 08:53:00.649   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 08:53:00.649  7778  7778 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 08:53:00.649  7778  7778 I wpa_supplicant: ssSupport state is = 1
08-31 08:53:00.649  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:53:00.649  7799  7799 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:53:00.649  7778  7778 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:53:00.649  7778  7778 E wpa_supplicant: SIM READ ERROR
08-31 08:53:00.649  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:53:00.649  7778  7778 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:53:00.649  7778  7778 E wpa_supplicant: SIM READ ERROR
08-31 08:53:00.649  7778  7778 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 08:53:00.659  7778  7778 I wpa_supplicant: wpa_default_ap_write_once
08-31 08:53:00.659  7778  7778 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 08:53:00.659  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:53:00.659  7778  7778 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 08:53:00.659  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:53:00.659  7778  7778 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 08:53:00.659  7778  7778 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 08:53:00.659  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:53:00.659  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:53:00.659  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:53:00.669  7799  7799 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:53:00.679  7799  7799 D ActivityThread: Added TimaKeyStore provider
,08-31 08:53:00.689  7778  7778 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-31 08:53:00.689  7799  7799 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 08:53:00.809  7778  7778 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-31 08:53:00.809  7778  7778 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 08:53:00.829  7778  7778 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-31 08:53:00.829   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7778
08-31 08:53:00.829   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-31 08:53:00.829  7778  7778 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 08:53:00.829  7778  7778 I wpa_supplicant: ssSupport state is = 1
,08-31 08:53:00.829  7778  7778 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-31 08:53:00.829  7778  7778 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 08:53:00.839  7778  7778 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-31 08:53:00.839   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7778
08-31 08:53:00.839   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-31 08:53:00.839  7778  7778 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 08:53:00.839  7778  7778 I wpa_supplicant: ssSupport state is = 1
08-31 08:53:00.839  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:53:00.839  7778  7778 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:53:00.839  7778  7778 E wpa_supplicant: SIM READ ERROR,
08-31 08:53:00.839  7778  7778 I wpa_supplicant: wpa_default_ap_write_once
08-31 08:53:00.839  7778  7778 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 08:53:00.839  7778  7778 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 08:53:00.839  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:53:00.839  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
08-31 08:53:00.849  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 08:53:00.849  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
,08-31 08:53:00.849  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:53:00.849  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 08:53:00.969  7778  7778 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-31 08:53:00.969  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 08:53:01.069  1019  4377 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-31 08:53:01.069  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:01.069  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:01.069  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:01.069  1019  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:01.079  7778  7778 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
,08-31 08:53:01.089  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-31 08:53:01.089  7778  7778 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 08:53:01.089  7823  7823 E Zygote  : MountEmulatedStorage(),
08-31 08:53:01.089  7823  7823 I libpersona: KNOX_SDCARD checking this for 10121
08-31 08:53:01.089  7823  7823 E Zygote  : v2
08-31 08:53:01.089  7823  7823 I libpersona: KNOX_SDCARD not a persona
08-31 08:53:01.089  1019  4377 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7823 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-31 08:53:01.089  1019  4377 I ActivityManager: Killing 7241:com.google.android.gms.wearable/u0a11 (adj 15): empty #21,
,08-31 08:53:01.099  7823  7823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:53:01.099  7823  7823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:53:01.099  7823  7823 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:53:01.119  7823  7823 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:53:01.119  7823  7823 D ActivityThread: Added TimaKeyStore provider
,08-31 08:53:01.139  7823  7823 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 08:53:01.139  7823  7823 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 08:53:01.139  7823  7823 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 08:53:01.149  7823  7823 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:53:01.159  7823  7823 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-31 08:53:01.159  7823  7823 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-31 08:53:01.159  1019  1350 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast,
08-31 08:53:01.159  1019  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 08:53:01.159  1019  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:01.159  1019  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:01.159  1019  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:01.179  7840  7840 E Zygote  : MountEmulatedStorage(),
08-31 08:53:01.179  7840  7840 E Zygote  : v2
08-31 08:53:01.179  7840  7840 I libpersona: KNOX_SDCARD checking this for 10141
08-31 08:53:01.179  7840  7840 I libpersona: KNOX_SDCARD not a persona
,08-31 08:53:01.179  7840  7840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 08:53:01.179  1019  1350 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7840 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-31 08:53:01.179  1019  1350 I ActivityManager: Killing 7186:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-31 08:53:01.179  7840  7840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:53:01.179  7840  7840 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:53:01.199  7840  7840 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:53:01.199  7840  7840 D ActivityThread: Added TimaKeyStore provider
,08-31 08:53:01.219  7840  7840 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-31 08:53:01.219  7840  7840 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:53:01.219  7840  7840 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 08:53:01.219  7840  7840 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-31 08:53:01.259  1019  1495 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:53:01.269  1019  4381 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:53:01.289  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
,08-31 08:53:01.289  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:53:01.289  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 08:53:01.289  1019  1098 V AlarmManager: waitForAlarm result :4
,08-31 08:53:01.299  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-31 08:53:01.299  1182  1182 D KeyguardUpdateMonitor: handleTimeUpdate
,08-31 08:53:01.309  1182  1182 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-31 08:53:01.309  1182  1182 D SecKeyguardClockView: HomeTimezone(): 1
,08-31 08:53:01.309  1019  1484 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:53:01.319  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 08:53:01.319  1182  1182 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-31 08:53:01.319  1019  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-31 08:53:01.319  1182  1182 I KeyguardEffectViewController: *** don't update sliding image ***
,08-31 08:53:01.319  1019  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 08:53:01.319  7778  7778 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 08:53:01.319  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:53:01.319  7778  7778 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:53:01.319  7778  7778 E wpa_supplicant: SIM READ ERROR
08-31 08:53:01.319  7778  7778 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 08:53:01.339  1019  1495 D RCPManagerService: exchangeData() failure , invalid userId,
,08-31 08:53:01.349  7778  7778 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 08:53:01.349  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 08:53:01.359  7778  7778 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 08:53:01.359  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 08:53:01.359  1019  1128 D WifiConfigStore: Loading config and enabling all networks 
,08-31 08:53:01.369  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:53:01.369  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:01.369  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:53:01.369  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:01.369  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:01.369  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:01.369  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:01.369  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:53:01.369  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-31 08:53:01.369  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:53:01.369  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 08:53:01.369  1182  1182 D HotspotTile: onReceive : 3, 0
,08-31 08:53:01.369  4872  4872 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:53:01.379  1019  1128 E WifiConfigStore: Not a HS20
,08-31 08:53:01.379  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:53:01.379  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:53:01.379  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:01.379  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:01.379  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:53:01.379  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:53:01.379  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:01.379  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:01.379  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:01.379  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 08:53:01.379  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:53:01.379  1019  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
08-31 08:53:01.379  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:01.389  1019  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 08:53:01.389  7778  7778 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 08:53:01.389  7778  7778 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 08:53:01.389  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:53:01.389  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:53:01.389  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:01.389  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:01.389  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:53:01.389  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:53:01.389  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:01.389  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:01.389  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:01.389  7778  7778 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 08:53:01.389  7778  7778 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 08:53:01.389  7778  7778 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 08:53:01.389  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 08:53:01.389  7778  7778 I wpa_supplicant: First Scan Start
,08-31 08:53:01.389  7778  7778 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-31 08:53:01.389  1019  1032 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:53:01.389  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:53:01.389  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:53:01.389  1019  1128 D WifiNative-wlan0: Setting external_sim to 1
,08-31 08:53:01.389  1019  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 08:53:01.389  1019  1128 I WifiNative-HAL: startHal
08-31 08:53:01.389  1019  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9d61688c
08-31 08:53:01.389  1019  1128 I WifiNative-HAL: Could not start hal
,08-31 08:53:01.399  1019  1128 E WifiNative-wlan0: do suspend true
,08-31 08:53:01.399  1019  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 08:53:01.399  1019  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-31 08:53:01.399  1019  1138 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:53:01.399   279   979 D CommandListener: Setting iface cfg
08-31 08:53:01.399   279   979 D CommandListener: Trying to bring up p2p0
08-31 08:53:01.399  1019  4380 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-31 08:53:01.399  1019  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 08:53:01.399  1019  1127 D WifiP2pService: P2pEnablingState
08-31 08:53:01.399  1019  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-31 08:53:01.399  7549  7549 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:53:01.399  1019  1127 D WifiP2pService: P2p socket connection successful
08-31 08:53:01.399  1019  1127 D WifiP2pService: P2pEnabledState
,08-31 08:53:01.409  1019  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:01.409  1019  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:01.409  1019  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:01.409  1019  4380 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:01.409  1019  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 08:53:01.409  1019  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 08:53:01.409  1019  1128 E WifiNative-wlan0: invaild command id : 215
,08-31 08:53:01.409  7778  7778 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 08:53:01.409  7778  7778 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 08:53:01.409  7778  7778 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-31 08:53:01.409  1019  1128 E WifiStateMachine: Failed to set frequency band 0
,08-31 08:53:01.409  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:53:01.409  1019  1128 D SecContentProvider2: mCursor = null
,08-31 08:53:01.419  7868  7868 E Zygote  : MountEmulatedStorage()
08-31 08:53:01.419  7868  7868 E Zygote  : v2
08-31 08:53:01.419  7868  7868 I libpersona: KNOX_SDCARD checking this for 10068
08-31 08:53:01.419  7868  7868 I libpersona: KNOX_SDCARD not a persona
,08-31 08:53:01.419  7868  7868 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:53:01.419  1019  4380 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7868 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,08-31 08:53:01.429  7868  7868 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:53:01.429  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:53:01.429  1019  1128 D SecContentProvider2: mCursor = null,
08-31 08:53:01.429  1019  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-31 08:53:01.429  1019  1130 E ConnectivityService: updateNetworkInfo()
,08-31 08:53:01.429  7868  7868 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
08-31 08:53:01.429  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3,
08-31 08:53:01.429  1019  1153 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:53:01.429  1019  1153 I WifiNative-HAL: startHal
,08-31 08:53:01.439  1019  1019 D RttService: SCAN_AVAILABLE : 3
08-31 08:53:01.439  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 08:53:01.439  1019  1154 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:53:01.439  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 08:53:01.439  1019  1127 D WifiNative-p2p0: p2pGetDeviceAddress
08-31 08:53:01.439  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 08:53:01.439  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:53:01.439  1019  1050 D WifiDisplayController: disconnect
08-31 08:53:01.439  1019  1050 D WifiDisplayController: updateConnection
08-31 08:53:01.439  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:53:01.439  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 08:53:01.439  1019  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-31 08:53:01.439  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:53:01.439  1019  1153 E wifi    : getStaticLongField sWifiHalHandle 0x9e4cc9bc
08-31 08:53:01.439  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-31 08:53:01.439  1019  1153 I WifiNative-HAL: Could not start hal
08-31 08:53:01.439  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 08:53:01.439  1019  1153 E WifiScanningService: could not start HAL
08-31 08:53:01.439  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 08:53:01.439  1019  1127 D WifiP2pService: DeviceAddress: 0a:75:42
,08-31 08:53:01.459  1019  1471 D RCPManagerService: exchangeData() failure , invalid userId
08-31 08:53:01.459  7868  7868 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:53:01.459  7868  7868 D ActivityThread: Added TimaKeyStore provider
,08-31 08:53:01.469  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 08:53:01.469  1019  1461 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 08:53:01.469  1019  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  secondary type: null
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  wps: 0
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  grpcapab: 0
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  devcapab: 0
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  status: 3
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  wfdInfo: null
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  groupownerAddress: null
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  GOdeviceName: null
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  interfaceAddress: 
08-31 08:53:01.469  1019  1050 D WifiDisplayController:  SConnectInfo : null
,08-31 08:53:01.469  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 08:53:01.469  1019  1350 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-31 08:53:01.469  1019  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:01.469  1019  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:01.469  1019  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:01.469  1019  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:01.489  1019  1127 D WifiP2pService: sending p2p persistent groups changed broadcast,
08-31 08:53:01.489  7883  7883 E Zygote  : MountEmulatedStorage()
08-31 08:53:01.489  7883  7883 I libpersona: KNOX_SDCARD checking this for 10009
08-31 08:53:01.489  7883  7883 E Zygote  : v2
,08-31 08:53:01.489  7883  7883 I libpersona: KNOX_SDCARD not a persona
08-31 08:53:01.489  7883  7883 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:53:01.489  1019  1350 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7883 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
08-31 08:53:01.489  7883  7883 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:53:01.489  1019  1350 I ActivityManager: Killing 7001:com.android.vending/u0a26 (adj 15): empty #21
,08-31 08:53:01.489  1019  1127 D WifiP2pService: InactiveState
08-31 08:53:01.489  1019  1127 D WifiP2pService: InactiveState{ what=143376 }
08-31 08:53:01.499  7883  7883 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-31 08:53:01.499  1019  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 08:53:01.499  7778  7778 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 08:53:01.499  1019  1127 D WifiP2pService: InactiveState{ what=143376 },
08-31 08:53:01.499  1019  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
08-31 08:53:01.499  1019  1265 I ActivityManager: Killing 7342:com.samsung.android.sm/1000 (adj 15): empty #21
,08-31 08:53:01.519  7883  7883 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:53:01.529  7883  7883 D ActivityThread: Added TimaKeyStore provider
,08-31 08:53:01.529  7868  7868 D BadgeProvider: onCreate
,08-31 08:53:01.539  7868  7868 D BadgeProvider: DatabaseHelper
,08-31 08:53:01.549  7868  7877 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-31 08:53:01.559  7868  7877 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-31 08:53:01.559  7868  7877 D BadgeProvider: sendNotify, [notify] : null
08-31 08:53:01.559  7868  7877 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-31 08:53:01.559  7868  7877 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-31 08:53:01.559  7868  7877 D BadgeProvider: update, [UpdateCount] : 1
,08-31 08:53:01.559  1489  1489 D Launcher.Model: reloadBadges entered.
,08-31 08:53:01.599  1019  1385 I ActivityManager: Killing 7516:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-31 08:53:01.619  1019  1350 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-31 08:53:01.619   279   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:53:01.619  1019  1350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:53:01.619   279   975 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-31 08:53:01.619  1019  1350 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:01.619  1019  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:01.619  1019  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:53:01.619  1638  1638 I Hs20UtilService: Starting #12
08-31 08:53:01.619  1638  1695 I Hs20UtilService: Message received 5011
,08-31 08:53:01.619  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 08:53:01.619  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 08:53:01.619  7572  7572 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:53:01.619  7572  7572 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:53:01.639  1019  1484 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:53:01.639  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:53:01.639  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:01.639  1019  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:53:01.639  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:53:01.649  1638  1638 I Hs20UtilService: Starting #13
,08-31 08:53:01.649  1638  1695 I Hs20UtilService: Message received 5011
,08-31 08:53:01.649  1019  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 08:53:01.649  1019  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 08:53:01.649  1019  1128 E WifiNative-wlan0: invaild command id : 215
,08-31 08:53:01.659  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 08:53:01.659  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 08:53:01.659  7572  7572 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:53:01.659  7572  7572 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:53:01.669  1019  1385 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-31 08:53:01.669  1019  1385 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-31 08:53:01.669  1019  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-31 08:53:01.669  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 08:53:01.669  1019  4378 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-31 08:53:01.669  4872  4872 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:53:01.679  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:53:01.679  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:53:01.679  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:53:01.679  4872  4872 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 08:53:01.679  4872  4917 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:53:01.679  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-31 08:53:01.679  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:01.679  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:01.679  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:01.679  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:01.689  1019  1031 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7902 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-31 08:53:01.699  7902  7902 E Zygote  : MountEmulatedStorage()
08-31 08:53:01.699  7902  7902 I libpersona: KNOX_SDCARD checking this for 10064
08-31 08:53:01.699  7902  7902 E Zygote  : v2,
08-31 08:53:01.699  7902  7902 I libpersona: KNOX_SDCARD not a persona
,08-31 08:53:01.699  7902  7902 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:53:01.699  7902  7902 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:53:01.699  7902  7902 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:53:01.719  7902  7902 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 08:53:01.719  7902  7902 D ActivityThread: Added TimaKeyStore provider
,08-31 08:53:01.729  7902  7902 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 08:53:01.739  7902  7902 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:53:01.739  7902  7902 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 08:53:01.769  7902  7902 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 08:53:01.769  7533  7533 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:53:01.779  1019  1265 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:01.779  1019  1265 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:01.779  1019  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-31 08:53:01.779  1019  1385 I ActivityManager: Killing 7449:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-31 08:53:02.609  7778  7778 I wpa_supplicant: nl80211: Received scan results (23 BSSes)
,08-31 08:53:02.609  7778  7778 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 08:53:02.609  7778  7778 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-31 08:53:02.609  7778  7778 I wpa_supplicant: Trying to associate with  'G700'
08-31 08:53:02.609  7778  7778 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-31 08:53:02.609  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-31 08:53:02.609  1019  7861 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-31 08:53:02.629  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:53:02.629  1019  1128 D SecContentProvider2: mCursor = null
,08-31 08:53:02.749  7778  7778 E wpa_supplicant: Cmd 35605 not handled
,08-31 08:53:02.749  7778  7778 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 08:53:02.749  7778  7778 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-31 08:53:02.749  7778  7778 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 08:53:02.749  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:53:02.749  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:53:02.749  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-31 08:53:02.749  7778  7778 I wpa_supplicant: Associated with F4.99.3E
08-31 08:53:02.749  7778  7778 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 08:53:02.749  7778  7778 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-31 08:53:02.749  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-31 08:53:02.759  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 08:53:02.759  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:53:02.759  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 08:53:02.759  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:53:02.759  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 08:53:02.759  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:53:02.759  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 08:53:02.759  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 08:53:02.759  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
08-31 08:53:02.759  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:53:02.759  1019  1128 D SecContentProvider2: mCursor = null
,08-31 08:53:02.769  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 08:53:02.769  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 08:53:02.769  1019  1128 D SecContentProvider2: mCursor = null
08-31 08:53:02.769  1019  1133 E Tethering: No numeric data,
08-31 08:53:02.769  7778  7778 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-31 08:53:02.769  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 08:53:02.769  1019  1133 D Tethering: clearTetheredNotification()
08-31 08:53:02.769  7778  7778 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-31 08:53:02.769  7778  7778 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-31 08:53:02.769  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-31 08:53:02.769  7778  7778 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 08:53:02.769  7778  7778 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 08:53:02.769  7778  7778 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-31 08:53:02.769  7778  7778 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 08:53:02.769  1019  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:53:02.769  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-31 08:53:02.769  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:02.779  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 08:53:02.779  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
08-31 08:53:02.779  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 08:53:02.779  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:02.779  1182  1182 D HotspotTile: updateTetherState():false, false
08-31 08:53:02.779  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:53:02.779  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 08:53:02.779  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 08:53:02.779  1019  1125 V NetworkStats: performPollLocked() took 9ms
08-31 08:53:02.789  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:02.789  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:02.789  1019  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 08:53:02.789  1019  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 08:53:02.799  1019  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:53:02.799  1019  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-31 08:53:02.799  1019  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 08:53:02.799  1019  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:53:02.799  1019  1130 E ConnectivityService: updateNetworkInfo()
,08-31 08:53:02.799  1019  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:53:02.799  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:02.799  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:53:02.799  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:53:02.799  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 08:53:02.799  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 08:53:02.799  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:02.799  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:53:02.799  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:02.799  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:02.799  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:02.799  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:02.809  1638  1638 I Hs20UtilService: Starting #14
08-31 08:53:02.809  1638  1695 I Hs20UtilService: Message received 5007
,08-31 08:53:02.809  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 08:53:02.809  4872  4872 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:53:02.809  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:53:02.809  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:53:02.809  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:53:02.809  4872  4872 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 08:53:02.819  4872  4917 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:53:02.819  1019  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:53:02.829   279   979 D CommandListener: Setting iface cfg
,08-31 08:53:02.829  1019  1128 E WifiStateMachine: Start Dhcp Watchdog 2
,08-31 08:53:02.829  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 08:53:02.829  1019  1128 D SecContentProvider2: mCursor = null
,08-31 08:53:02.849  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:53:02.849  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:53:02.849  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 08:53:02.849  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:02.849  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:02.849  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:02.849  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:02.849  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 08:53:02.859  1019  1128 D SecContentProvider2: mCursor = null
,08-31 08:53:02.859  1019  1128 E WifiNative-wlan0: do suspend false
,08-31 08:53:02.859  1019  1127 D WifiP2pService: InactiveState{ what=143375 },
08-31 08:53:02.859  1019  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 08:53:02.919  1019  4378 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-31 08:53:02.919  1019  4378 D WifiService: setWifiEnabled: false pid=7379, uid=10170
08-31 08:53:02.919  1019  4378 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 08:53:02.919  1019  4378 D SecContentProvider2: mCursor = null
,08-31 08:53:02.919  1019  4378 D SettingsProvider: name = wifi_on
,08-31 08:53:02.929  1019  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:53:02.939  1019  1128 E WifiNative-wlan0: do suspend true
,08-31 08:53:02.959  1019  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-31 08:53:02.959  1019  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 08:53:02.969  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 08:53:02.969   279   979 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:53:02.969  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:53:02.969  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 08:53:02.969  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:02.969  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:02.969  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:02.969  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:02.969  1019  1130 E ConnectivityService: updateNetworkInfo()
08-31 08:53:02.969  1019  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 08:53:02.969  1019  1130 E ConnectivityService: updateNetworkInfo()
08-31 08:53:02.969  1019  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-31 08:53:02.969  1019  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 08:53:02.969  1019  1127 D WifiP2pService: InactiveState{ what=131204 }
08-31 08:53:02.969   279   979 E Netd    : no such netId 503
08-31 08:53:02.969  1019  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-31 08:53:02.969  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-31 08:53:02.969  1019  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-31 08:53:02.979  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 08:53:02.979  1019  1130 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
,08-31 08:53:02.979  1019  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:02.979  1019  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-31 08:53:02.979  1019  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:53:02.979  1019  1130 V NetworkStats: updateIfacesLocked()
08-31 08:53:02.979  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 08:53:02.979  1019  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-31 08:53:02.979  1019  1153 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:53:02.979  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 08:53:02.979  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:02.979  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:53:02.989  1019  1130 V NetworkStats: performPollLocked() took 5ms
08-31 08:53:02.979  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:02.979  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:02.979  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:02.979  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:02.989  1019  1019 D RttService: SCAN_AVAILABLE : 1
08-31 08:53:02.989  1019  1154 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:53:02.989  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:02.989  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 08:53:02.989  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-31 08:53:02.989  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-31 08:53:02.989  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 08:53:02.989  1019  1350 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:53:02.989  1019  1350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:53:02.999  1019  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-31 08:53:02.999  1019  7917 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:53:02.999  1019  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 08:53:02.999  1019  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 08:53:02.999  1019  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-31 08:53:02.999  1019  1130 E ConnectivityService: updateNetworkInfo()
08-31 08:53:02.999  1019  1350 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:02.999  1019  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:02.999  1019  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:53:02.999  1019  7917 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 08:53:02.999  1019  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-31 08:53:02.999  1638  1638 I Hs20UtilService: Starting #15
08-31 08:53:02.999  1019  1130 E ConnectivityService: updateNetworkInfo()
,08-31 08:53:02.999  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:02.999  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:02.999  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 08:53:02.999  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-31 08:53:02.999  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:53:02.999  1019  1050 D WifiDisplayController: disconnect
08-31 08:53:02.999  1638  1695 I Hs20UtilService: Message received 5007
,08-31 08:53:02.999  1019  1050 D WifiDisplayController: updateConnection
08-31 08:53:02.999  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:53:02.999  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 08:53:02.999  1019  1127 D WifiP2pService: P2pDisablingState
08-31 08:53:02.999  1019  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-31 08:53:02.999  1019  1127 D WifiP2pService: p2p socket connection lost
08-31 08:53:02.999  1019  1127 D WifiP2pService: P2pDisabledState
08-31 08:53:02.999  1019  1128 E WifiNative-wlan0: do suspend true
,08-31 08:53:03.009  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 08:53:03.009  4872  4872 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 08:53:03.009  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
08-31 08:53:03.009  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-31 08:53:03.009  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:53:03.009  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 08:53:03.009  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 08:53:03.009  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-31 08:53:03.009  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 08:53:03.009  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:53:03.009  1019  4380 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 08:53:03.009  4872  4872 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 08:53:03.009  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-31 08:53:03.009  4872  4917 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:53:03.019  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 08:53:03.019  4872  4872 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:53:03.019  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:53:03.019  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:53:03.019  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:53:03.019  4872  4872 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 08:53:03.019  4872  4917 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:53:03.029  7902  7902 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:53:03.029  7902  7902 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-31 08:53:03.029  7902  7902 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 08:53:03.029  1019  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-31 08:53:03.029   279   979 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:53:03.029  7533  7533 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-31 08:53:03.039  1019  1127 D WifiP2pService: DefaultState{ what=143375 }
,08-31 08:53:03.039  7778  7778 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
08-31 08:53:03.039  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 08:53:03.039  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:53:03.039  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:03.049  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 08:53:03.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:03.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:03.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:03.049  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:53:03.049  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:03.049  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:53:03.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.049  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.049  1019  4380 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:53:03.049  1019  4380 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:53:03.059  1019  4380 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:03.059  1019  4380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:53:03.059  1019  4380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:53:03.059  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:53:03.059  1019  1128 D SecContentProvider2: mCursor = null
,08-31 08:53:03.059  1638  1638 I Hs20UtilService: Starting #16
,08-31 08:53:03.059  1638  1695 I Hs20UtilService: Message received 5007
,08-31 08:53:03.069  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:53:03.069  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:53:03.069  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:53:03.069  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.069  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.069  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.069  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:03.069  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:53:03.069  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:53:03.069  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0),
08-31 08:53:03.069  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 08:53:03.069  1182  1182 D HotspotTile: onReceive : 0, 0,
08-31 08:53:03.079  4872  4872 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:53:03.079  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:53:03.079  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:53:03.079  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:53:03.079  7920  7920 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-31 08:53:03.079  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:03.079  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:53:03.079  7920  7920 I dhcpcd  : version 5.5.6 starting
,08-31 08:53:03.079  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:53:03.079  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:03.089  7920  7920 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-31 08:53:03.089  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 08:53:03.089  4872  4872 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 08:53:03.089  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:53:03.089  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 08:53:03.089  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:53:03.089  4872  4872 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 08:53:03.089  4872  4917 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:53:03.099  1019  4378 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:53:03.099  1019  4378 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:53:03.099  1019  4378 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:03.099  1019  4378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:03.099  1019  4378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 08:53:03.099  1638  1638 I Hs20UtilService: Starting #17
,08-31 08:53:03.109  1638  1695 I Hs20UtilService: Message received 5011
,08-31 08:53:03.109  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 08:53:03.109  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 08:53:03.109  7572  7572 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:53:03.109  7572  7572 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:53:03.139  7920  7920 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-31 08:53:03.139  7920  7920 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 08:53:03.139  7920  7920 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-31 08:53:03.149  7778  7778 I wpa_supplicant: Blacklist: Clear (all) 
08-31 08:53:03.149  7920  7920 I dhcpcd  : bssid match
,08-31 08:53:03.149  7920  7920 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-31 08:53:03.219  7778  7778 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 08:53:03.219  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 08:53:03.219  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:53:03.219  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:53:03.229  7920  7920 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-31 08:53:03.229  7920  7920 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-31 08:53:03.249  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:53:03.249  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:53:03.249  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:53:03.249  1019  1133 D Tethering: InitialState.processMessage what=4
,08-31 08:53:03.249  7778  7778 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-31 08:53:03.249  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:53:03.249  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:53:03.249  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:53:03.249  1019  1133 E Tethering: No numeric data
08-31 08:53:03.249  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 08:53:03.259  1019  1125 V NetworkStats: performPollLocked(flags=0x1),
08-31 08:53:03.249  1019  1133 D Tethering: clearTetheredNotification()
08-31 08:53:03.259  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:03.259  7778  7778 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-31 08:53:03.259  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:03.259  7778  7778 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 08:53:03.259  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:53:03.259  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:53:03.259  1019  1047 D Tethering: interfaceStatusChanged wlan0, false,
,08-31 08:53:03.259  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:03.259  1019  1125 V NetworkStats: performPollLocked() took 7ms
08-31 08:53:03.259  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-31 08:53:03.269  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-31 08:53:03.259  1182  1182 D HotspotTile: updateTetherState():false, false
08-31 08:53:03.269  7778  7778 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 08:53:03.269  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 08:53:03.269  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:03.269  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:03.419   289   289 E SMD     : DCD OFF
,08-31 08:53:03.539  7778  7778 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 08:53:03.699  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:53:03.699  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:53:03.699  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:53:03.699  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:53:03.699  7778  7778 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 08:53:03.699  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:53:03.699  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:53:03.779  1019  4380 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 08:53:03.779  1019  4380 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4265, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-31 08:53:03.779  1019  4380 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 08:53:03.779  1019  4380 D BatteryService: stay LED for charging
08-31 08:53:03.779  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 08:53:03.779  1019  1019 I MotionRecognitionService: Plugged
08-31 08:53:03.779  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 08:53:03.789  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 08:53:03.789  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 08:53:03.789  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 08:53:03.789  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 08:53:03.799  1019  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-31 08:53:03.799  1019  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 08:53:03.809  7549  7549 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-31 08:53:03.809  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 08:53:03.819  4872  4872 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-31 08:53:03.819  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 08:53:03.819  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 08:53:03.829  1743  2198 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:53:03.829  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:53:03.829  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:53:03.829  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:53:03.829  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:03.829  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:03.829  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:53:03.829  1638  1638 I Hs20UtilService: Starting #18
,08-31 08:53:03.829  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:53:03.829  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:03.829  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:53:03.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.829  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:03.839  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:53:03.829  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:53:03.839  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-31 08:53:03.839  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 08:53:03.839  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:03.839  1182  1182 D HotspotTile: onReceive : 1, 0
,08-31 08:53:03.839  1638  1695 I Hs20UtilService: Message received 5011
,08-31 08:53:03.839  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 08:53:03.839  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 08:53:03.849  7572  7572 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:53:03.849  7572  7572 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:53:04.579   279   973 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-31 08:53:04.579  1019  1047 D Tethering: interfaceRemoved wlan0
,08-31 08:53:04.579  1019  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 08:53:04.739  1019  1047 D Tethering: interfaceRemoved p2p0,
08-31 08:53:04.739  1019  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 08:53:05.279  1019  1098 V AlarmManager: waitForAlarm result :4
,08-31 08:53:05.289   279   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:53:05.289   279   975 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-31 08:53:05.299  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:05.299  1019  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:05.299  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-31 08:53:05.519  1019  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-31 08:53:05.929  7379  7432 D BluetoothAdapter: enable()
,08-31 08:53:05.929  1019  4380 W ActivityManager: Permission Denial: getCurrentUser() from pid=7379, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 08:53:05.939  1019  4380 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 08:53:05.939  1019  4380 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7379, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:53:05.939  1019  4380 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 08:53:05.939  1019  4380 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-31 08:53:05.939  1019  4380 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 08:53:05.939  1019  4380 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-31 08:53:05.939  1019  4380 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 08:53:05.939  1019  4380 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 08:53:05.939  1019  4380 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 08:53:05.939  1019  4380 D SettingsProvider: name = bluetooth_on,
,08-31 08:53:05.949  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-31 08:53:05.949  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 08:53:05.949  1019  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 08:53:05.959  3200  3275 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON,
08-31 08:53:05.959  3200  3275 D BluetoothAdapterProperties: Setting state to 11
08-31 08:53:05.959  1019  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:05.959  3200  3275 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11,
08-31 08:53:05.959  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 08:53:05.959  3200  3275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:53:05.959  3200  3275 D BluetoothAdapterService: updateAdapterState state is 11,
08-31 08:53:05.959  3200  3275 D BluetoothAdapterService: Autoconnection is available 
08-31 08:53:05.959  3200  3275 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 08:53:05.959  3200  3275 D BtConfig.SecureMode: isSecureModeOn:false
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10,
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 08:53:05.959  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 08:53:05.959  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 08:53:05.959  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:05.959  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:05.959  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:05.969  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 08:53:05.969  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 08:53:05.969  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 08:53:05.969  3200  3200 D HeadsetService: Received start request. Starting profile...
,08-31 08:53:05.969  3200  3200 D HeadsetService: start()
08-31 08:53:05.969  3200  3200 D HeadsetStateMachine: make
,08-31 08:53:05.969  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:05.969  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,08-31 08:53:05.979  3200  3200 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 08:53:05.989  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 08:53:05.989  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:53:05.989  1182  1182 D BluetoothTile:  getBluetoothState : 11
,08-31 08:53:05.989  1880  1880 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:53:05.989  1019  1385 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:53:05.999  1019  3871 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 08:53:05.999  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 08:53:05.999  4872  4872 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:06.009  1019  4377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:06.009  1019  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 08:53:06.009  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
08-31 08:53:06.009  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 08:53:06.009  1019  4377 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.009  1019  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.009  1019  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.009  1019  1495 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone,
08-31 08:53:06.009  1019  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.009  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-31 08:53:06.009  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:06.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:53:06.009  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-31 08:53:06.009  1019  1495 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.009  1019  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.009  1019  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 08:53:06.019  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:06.169  1019  1461 I art     : Explicit concurrent mark sweep GC freed 71988(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.413ms total 174.139ms
,08-31 08:53:06.169  1019  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:06.169  1019  1495 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.169  1019  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-31 08:53:06.169  1019  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.169  1019  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.169  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-31 08:53:06.169  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 08:53:06.169  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 08:53:06.169  1019  4380 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-31 08:53:06.169  1019  4380 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.169  1019  4380 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.169  1019  4380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.169  1019  4380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-31 08:53:06.169  1019  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:06.169  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.169  3200  3200 I bluedroid: get_profile_interface handsfree
08-31 08:53:06.169  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.169  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.169  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.179  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-31 08:53:06.179  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 08:53:06.179  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 08:53:06.179  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:06.179  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.179  1657  1657 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:53:06.189  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:06.189  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.189  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.189  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 08:53:06.189  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:53:06.189  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 08:53:06.189  1019  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:06.189  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.199  3200  3200 E DualScoManager: Dual Sco Manager already instantiated
08-31 08:53:06.199  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.199  1019  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.199  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:53:06.199  3200  3200 I DualScoManager: Set HeadsetServiceHelper
,08-31 08:53:06.199  3200  3200 D BluetoothAtMessage: createCMTIContentObservers
,08-31 08:53:06.199  1019  1471 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-31 08:53:06.199  1019  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:53:06.199  1019  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:53:06.199  1019  1471 D SettingsProvider: selectionArgs: false
,08-31 08:53:06.199  1019  1471 D SettingsProvider: selectionArgs: 1002
08-31 08:53:06.199  1019  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:53:06.199  1019  1471 D SettingsProvider: ret = -1
08-31 08:53:06.199  4872  4872 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:53:06.199  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-31 08:53:06.199  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 08:53:06.199  3200  3275 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 08:53:06.199  1019  4378 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:06.199  1019  4378 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.199  3200  7953 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 08:53:06.199  1019  4378 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:06.199  1019  4378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.199  1019  4378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.209  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:53:06.209  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:53:06.209  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:53:06.209  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:53:06.209  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:53:06.209  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:53:06.209  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 08:53:06.209  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 08:53:06.209  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 08:53:06.209  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 08:53:06.209  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 08:53:06.209  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 08:53:06.209  3200  3275 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 08:53:06.209  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:06.209  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 08:53:06.209  3200  3200 D HeadsetService: mStartError = false
,08-31 08:53:06.209  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:06.209  3200  3200 D A2dpService: Received start request. Starting profile...
08-31 08:53:06.209  3200  3200 D A2dpService: start()
08-31 08:53:06.209  3200  3200 I bluedroid: get_profile_interface avrcp
,08-31 08:53:06.209  1019  4381 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-31 08:53:06.219  3200  7953 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-31 08:53:06.219  3200  7953 D HeadsetStateMachine: map size, before remove : 0
08-31 08:53:06.219  3200  7953 D HeadsetStateMachine: map size, after remove: 0
,08-31 08:53:06.219  1019  4381 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:06.219  1019  4381 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:06.219  1019  4381 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:06.219  1019  4381 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:06.229  3200  3200 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
08-31 08:53:06.229  3200  3200 D Avrcp   : Initialize Media Controller
08-31 08:53:06.229  3200  3200 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-31 08:53:06.229  7955  7955 E Zygote  : MountEmulatedStorage()
,08-31 08:53:06.229  7955  7955 E Zygote  : v2
08-31 08:53:06.229  7955  7955 I libpersona: KNOX_SDCARD checking this for 10055
08-31 08:53:06.229  7955  7955 I libpersona: KNOX_SDCARD not a persona
,08-31 08:53:06.229  7955  7955 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:53:06.229  3200  3200 E Avrcp   : getActiveSessions
,08-31 08:53:06.229  1019  4381 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7955 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-31 08:53:06.229  3200  3200 D Avrcp   : pick active media Controller
08-31 08:53:06.229  3200  3200 D Avrcp   : Get the active Media Controller 
08-31 08:53:06.239  7955  7955 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:53:06.239  7955  7955 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:53:06.239  3200  3200 I Avrcp   :  Updating now playing list upon AVRCP Start
08-31 08:53:06.239  3200  3200 D A2dpStateMachine: make
08-31 08:53:06.239  3200  7954 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-31 08:53:06.239  3200  3200 I bluedroid: get_profile_interface a2dp
08-31 08:53:06.239  3200  7965 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 08:53:06.239  3200  3200 E bt-btif : warning : media task started media_task_refcnt 1 
08-31 08:53:06.239  3200  3200 D A2dpService: mStartError = false
08-31 08:53:06.239  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
08-31 08:53:06.249  3200  3200 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 08:53:06.249  3200  7963 D A2dpStateMachine: Enter Disconnected: -2
08-31 08:53:06.249  1433  1452 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 08:53:06.249  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-31 08:53:06.249  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 08:53:06.249  1433  1452 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 08:53:06.249  3200  3200 D HidService: Received start request. Starting profile...
08-31 08:53:06.249  3200  3200 D HidService: start()
08-31 08:53:06.249  3200  3200 I bluedroid: get_profile_interface hidhost
08-31 08:53:06.249  3200  3200 D HidService: setHidService(): set to: null
08-31 08:53:06.249  3200  3200 D HidService: mStartError = false
08-31 08:53:06.249  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
08-31 08:53:06.249  3200  3200 D HeadsetStateMachine: Proxy object connected
08-31 08:53:06.249  3200  3200 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 08:53:06.249  3200  7953 D HeadsetStateMachine: Disconnected process message: 11
08-31 08:53:06.249  3200  3200 D HealthService: Received start request. Starting profile...
08-31 08:53:06.249  3200  3200 D HealthService: start()
,08-31 08:53:06.259  3200  3200 I bluedroid: get_profile_interface health
08-31 08:53:06.259  3200  3200 D HealthService: mStartError = false
08-31 08:53:06.259  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
08-31 08:53:06.259  3200  3200 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 08:53:06.259  3200  3200 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-31 08:53:06.259  3200  7953 D HeadsetStateMachine: Disconnected process message: 18
,08-31 08:53:06.259  3200  3200 D PanService: Received start request. Starting profile...
08-31 08:53:06.259  3200  3200 D PanService: start()
,08-31 08:53:06.259  3200  3200 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 08:53:06.259  3200  3200 I bluedroid: get_profile_interface pan
08-31 08:53:06.259  3200  3200 D PanService: mStartError = false
08-31 08:53:06.259  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:06.259   308   308 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 772us total 27.129ms
,08-31 08:53:06.259  3200  3200 D BluetoothMapService: Received start request. Starting profile...
08-31 08:53:06.259  3200  3200 D BluetoothMapService: start()
,08-31 08:53:06.259  3200  3200 D BluetoothMapService: mStartError = false
08-31 08:53:06.259  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:06.269  3200  3200 D SapService: Received start request. Starting profile...
08-31 08:53:06.269  3200  3200 D SapService: start()
08-31 08:53:06.269  3200  3200 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 08:53:06.269  3200  3200 I bluedroid: get_profile_interface sap
08-31 08:53:06.269  3200  3200 D SapService: mStartError = false
08-31 08:53:06.269  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:06.269  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 08:53:06.269  3200  3200 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 08:53:06.269  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 08:53:06.269  3200  7954 D BluetoothMediaBrowser: no now playing list
08-31 08:53:06.269  3200  7954 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-31 08:53:06.269  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 08:53:06.269  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 08:53:06.269  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-31 08:53:06.269  3200  7953 D HeadsetStateMachine: Disconnected process message: 10
08-31 08:53:06.269  3200  7953 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 08:53:06.269  3200  7953 D HeadsetStateMachine: Disconnected process message: 11
,08-31 08:53:06.279   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 703us total 19.819ms
,08-31 08:53:06.289  7955  7955 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:53:06.289  7955  7955 D ActivityThread: Added TimaKeyStore provider
,08-31 08:53:06.289  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-31 08:53:06.289  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 08:53:06.289  3200  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-31 08:53:06.289  3200  3275 I bluedroid: enable
,08-31 08:53:06.299   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 722us total 20.770ms
,08-31 08:53:06.309  3200  3278 E bt-btif : Calling BTA_HhEnable
08-31 08:53:06.309  3200  3278 E bt-btif : BTA got event 0x122b
08-31 08:53:06.309  3200  3278 E bt-btif : BTA got event 0(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 08:53:06.309  3200  3278 E bt-btif : BTM_SEC_REG[3]: id 37, is_orig 1, psm 0x0019, proto_id 7
08-31 08:53:06.309  3200  3278 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-31 08:53:06.309  3200  3278 E BluetoothServiceJni: populateRssiValuesNative
08-31 08:53:06.309  3200  3278 I bluedroid: getModelRssiValues
08-31 08:53:06.309  3200  3278 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 08:53:06.309  3200  3278 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 08:53:06.309  3200  3278 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-31 08:53:06.309  1019  1019 D SettingsProvider: name = bluetooth_name
,08-31 08:53:06.319  3200  3278 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 08:53:06.319  3200  3278 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:53:06.319  3200  3278 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 08:53:06.319  3200  3278 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-31 08:53:06.319  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:06.319  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:06.319  3200  3278 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
,08-31 08:53:06.319  3200  3278 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-31 08:53:06.319  3200  3278 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-31 08:53:06.319  3200  3278 E bt-btif : JVenable fails
,08-31 08:53:06.329  3200  3278 D bte_conf: Device ID record 1 : primary
08-31 08:53:06.329  3200  3278 D bte_conf:   vendorId            = 0075
08-31 08:53:06.329  3200  3278 D bte_conf:   vendorIdSource      = 0001
08-31 08:53:06.329  3200  3278 D bte_conf:   product             = 0100
08-31 08:53:06.329  3200  3278 D bte_conf:   version             = 0200
08-31 08:53:06.329  3200  3278 D bte_conf:   clientExecutableURL = 
08-31 08:53:06.329  3200  3278 D bte_conf:   serviceDescription  = 
08-31 08:53:06.329  3200  3278 D bte_conf:   documentationURL    = 
,08-31 08:53:06.329  3200  3278 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 08:53:06.329  7955  7955 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 08:53:06.329  3200  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 08:53:06.329  3200  3275 D BluetoothAdapterProperties: ScanMode =  20
08-31 08:53:06.329  3200  3275 D BluetoothAdapterProperties: State =  11
,08-31 08:53:06.329  1019  1031 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 08:53:06.329  3200  3275 D BluetoothAdapterProperties: Setting state to 12
08-31 08:53:06.329  3200  3275 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 08:53:06.329  3200  3278 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-31 08:53:06.339  3200  3278 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 08:53:06.339  3200  3278 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 08:53:06.339  3200  3278 D BluetoothAdapterProperties: Scan Mode:21
08-31 08:53:06.339  3200  3278 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 08:53:06.339  1019  1385 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-31 08:53:06.339  1019  1385 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:53:06.339  1019  1385 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:53:06.339  1019  1385 D SettingsProvider: selectionArgs: false
08-31 08:53:06.339  1019  1385 D SettingsProvider: selectionArgs: 1002
08-31 08:53:06.339  1019  1385 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:53:06.339  1019  1385 D SettingsProvider: ret = -1
,08-31 08:53:06.339  3200  3275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-31 08:53:06.339  3200  3275 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 08:53:06.339  1019  4377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:06.339  1019  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.339  1019  4377 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.339  1019  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.339  1019  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.349  3200  3219 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:53:06.349  3200  3275 D BluetoothAdapterService: Autoconnection is available 
08-31 08:53:06.349  3200  3275 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-31 08:53:06.349  3200  3275 D BluetoothAdapterService: starting service from this receiver
,08-31 08:53:06.349  1019  3871 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:06.349  1019  3871 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.349  3200  3219 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:06.349  1019  3871 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:06.349  1019  3871 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.349  1019  3871 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:53:06.349  3200  3200 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-31 08:53:06.349  3200  3200 I BluetoothPbapService: Handler(): got msg=1
,08-31 08:53:06.359  1019  3871 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-31 08:53:06.359  1019  1049 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 08:53:06.359  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.359  3200  3275 I BluetoothAdapterState: Entering On State from state = 11
08-31 08:53:06.359  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:53:06.359  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:06.359  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:06.359  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:53:06.359  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:53:06.359  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:06.359  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:06.359  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:06.359  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.359  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.359  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.369  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:06.369  3200  3200 D BluetoothA2dp: Proxy object connected
08-31 08:53:06.369  3200  3200 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-31 08:53:06.369  7955  7955 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-31 08:53:06.369  3200  7976 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 08:53:06.369  7379  7387 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:06.369  7955  7955 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-31 08:53:06.369  7955  7955 D UserAnalysis: Create SecureDbHelper
,08-31 08:53:06.369  7379  7387 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:53:06.369  4872  4882 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 08:53:06.369  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:53:06.369  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:06.369  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:06.369  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:53:06.369  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:53:06.369  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:06.369  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:06.369  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:06.369  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-31 08:53:06.369  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.369  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:06.379  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.379  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-31 08:53:06.379  3200  7976 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 08:53:06.379  3200  7976 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:53:06.379  1433  3358 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:06.379  1433  3358 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:06.379  7955  7955 D IntelligenceServiceApplication: onCreate()
08-31 08:53:06.379  1460  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:06.379  1460  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:06.379  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:06.379  3200  7976 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-31 08:53:06.379  3200  7976 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:53:06.379  3200  7976 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:53:06.379  3200  7976 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2691fe0f
08-31 08:53:06.379  4872  4872 D BluetoothMap: Proxy object connected
08-31 08:53:06.379  4872  4872 D MapProfile: Bluetooth service connected
08-31 08:53:06.379  4872  4872 D BluetoothMap: getConnectedDevices()
,08-31 08:53:06.379  3200  7976 D BluetoothSocket: channel: 19
08-31 08:53:06.379  3200  7976 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 08:53:06.379  1019  1471 I ActivityManager: Killing 7469:com.google.android.apps.maps/u0a105 (adj 15): empty #21
08-31 08:53:06.379  1460  4801 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:06.389  1019  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:53:06.389  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:53:06.389  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.389  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.389  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.389  1460  4801 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:53:06.389  7955  7955 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 08:53:06.389  4872  4880 D BluetoothPan: Binding service...
,08-31 08:53:06.389  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 08:53:06.389  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.389  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.389  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.389  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.389  1019  1385 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-31 08:53:06.399  1433  1451 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:06.399  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:53:06.399  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 08:53:06.399  4872  4872 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 08:53:06.399  4872  4872 D PanProfile: Bluetooth service connected
,08-31 08:53:06.399  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.399  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.399  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.399  1433  1451 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 08:53:06.399  7955  7955 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 08:53:06.399  1433  3358 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:06.399  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:53:06.399  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:53:06.399  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.399  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.399  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-31 08:53:06.399  1433  3358 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:53:06.399  1182  1909 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:06.399  1182  1909 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:06.399  1019  1049 D BluetoothPan: Binding service...
,08-31 08:53:06.399  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 08:53:06.399  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-31 08:53:06.399  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 08:53:06.399  4872  7977 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 08:53:06.409  7955  7955 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 08:53:06.409  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-31 08:53:06.409  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.409  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.409  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.409  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-31 08:53:06.409  4872  4880 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:53:06.409  4872  4880 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:06.409  4872  4872 D BluetoothPbap: Proxy object connected
08-31 08:53:06.409  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 08:53:06.409  4872  4872 D PbapServerProfile: Bluetooth service connected
08-31 08:53:06.409  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 08:53:06.409  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.409  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.409  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.409  4872  4872 D BluetoothA2dp: Proxy object connected
,08-31 08:53:06.409  4872  4872 D A2dpProfile: Bluetooth service connected
08-31 08:53:06.409  4872  7977 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:06.419  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:53:06.419  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:53:06.419  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.419  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.419  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.419  4872  7977 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:53:06.419  4872  4882 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:06.419  4872  4882 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:06.419  1019  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 08:53:06.419  4872  4872 D HeadsetProfile: Bluetooth service connected
,08-31 08:53:06.419  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:53:06.419  1019  1049 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 08:53:06.419  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 08:53:06.419  1743  1918 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:06.419  1743  1918 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:06.419  3200  3211 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:06.419  3200  3211 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:53:06.419  1019  1049 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-31 08:53:06.429   289   289 E SMD     : DCD OFF
,08-31 08:53:06.429  1019  1049 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #18
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: android.os.TransactionTooLargeException
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 08:53:06.429  1019  1049 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-31 08:53:06.429  4872  7977 D Bluetoothsap: onBluetoothStateChange: up=true
08-31 08:53:06.429  4872  7977 D Bluetoothsap: Binding service...
,08-31 08:53:06.429  4872  7977 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 ,
08-31 08:53:06.429  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-31 08:53:06.429  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-31 08:53:06.429  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.429  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.429  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.429  4872  7977 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-31 08:53:06.439  4872  4872 D Bluetoothsap: BluetoothSAP Proxy object connected
08-31 08:53:06.439  4872  4872 D SapProfile: Bluetooth service connected
,08-31 08:53:06.439  4872  4872 D Bluetoothsap: getConnectedDevices()
,08-31 08:53:06.439  1433  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:06.439  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:53:06.439  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:53:06.439  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.439  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.439  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-31 08:53:06.439  1433  1452 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:53:06.439  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 08:53:06.439  1019  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-31 08:53:06.439  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 08:53:06.439  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 08:53:06.439  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:06.439  1019  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:53:06.439  1019  1019 D BluetoothA2dp: Proxy object connected
08-31 08:53:06.439  1444  1477 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:06.439  1444  1477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:53:06.439  4872  4882 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 08:53:06.439  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-31 08:53:06.439  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.439  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.439  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.439  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.449  4872  4872 D BluetoothInputDevice: Proxy object connected
08-31 08:53:06.449  4872  4872 D HidProfile: Bluetooth service connected
08-31 08:53:06.449  1657  1668 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:06.449  1657  1668 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:06.449  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-31 08:53:06.449  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 08:53:06.449  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 08:53:06.449  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
08-31 08:53:06.449  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 08:53:06.449  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-31 08:53:06.449  1433  1433 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@33e1d4f1, true
,08-31 08:53:06.459  1433  1433 D BluetoothHeadset: registerMessageListener
,08-31 08:53:06.459  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 08:53:06.459  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:53:06.459  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:06.459  1182  1182 D BluetoothTile:  getBluetoothState : 12
,08-31 08:53:06.459  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
08-31 08:53:06.459  1880  1880 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:53:06.459  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:53:06.469  1019  1385 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:53:06.469  1019  1495 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 08:53:06.469  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:53:06.469  4872  4872 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:06.469  3200  3219 D HeadsetService: registerMessageListener
,08-31 08:53:06.469  3200  3219 D HeadsetService: registerMessageListener
,08-31 08:53:06.479  3200  7953 D HeadsetStateMachine: Disconnected process message: 70
08-31 08:53:06.479  3200  7953 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@362bee9c
,08-31 08:53:06.479  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:06.479  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 08:53:06.479  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 08:53:06.479  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 08:53:06.479  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 08:53:06.479  4872  4872 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-31 08:53:06.479  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-31 08:53:06.479  4872  4872 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-31 08:53:06.479  4872  4872 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 08:53:06.479  4872  4872 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-31 08:53:06.479  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:06.479  3200  7979 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-31 08:53:06.479  3200  7953 D HeadsetStateMachine: Disconnected process message: 9
08-31 08:53:06.479  3200  7953 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 08:53:06.489   284   748 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-31 08:53:06.489   284   748 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 08:53:06.489   284   748 V voice   : voice_set_parameters: exit with code(-2)
08-31 08:53:06.489   284   748 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 08:53:06.489   284   748 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 08:53:06.489   284   748 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 08:53:06.489   284   748 V audio_hw_primary: adev_set_parameters: exit
,08-31 08:53:06.489  3200  7953 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 08:53:06.489  3200  7979 D BluetoothSocket: bindListen(): myUserId = 0
08-31 08:53:06.489  3200  7979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:53:06.489  3200  7979 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-31 08:53:06.489  3200  7979 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:53:06.489  3200  7979 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:53:06.489  3200  7979 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c1050a5
08-31 08:53:06.489  3200  7979 D BluetoothSocket: channel: 5
,08-31 08:53:06.489  4872  4872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:53:06.489  1019  1138 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 08:53:06.489  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.489  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.489  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.489  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:53:06.499  1657  1657 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:53:06.509  4872  4872 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:53:06.509  4872  4872 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:53:06.509  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:06.509  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 08:53:06.519  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:06.519  3200  3200 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 08:53:06.519  1019  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:06.519  1019  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 08:53:06.529  1019  1506 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:06.529  1019  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:06.529  1019  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:06.529  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 08:53:06.529  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:06.529  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:06.529  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:06.529  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:06.539  7982  7982 E Zygote  : MountEmulatedStorage(),
,08-31 08:53:06.549  7982  7982 E Zygote  : v2,
08-31 08:53:06.549  7982  7982 I libpersona: KNOX_SDCARD checking this for 10105
08-31 08:53:06.549  7982  7982 I libpersona: KNOX_SDCARD not a persona
,08-31 08:53:06.549  7982  7982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:53:06.549  1019  1032 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7982 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-31 08:53:06.549  7982  7982 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:53:06.549  1019  1484 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-31 08:53:06.549  7982  7982 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-31 08:53:06.559  3200  7992 D BluetoothSocket: bindListen(): myUserId = 0
08-31 08:53:06.559  3200  7992 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:53:06.559  3200  7992 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-31 08:53:06.559  3200  7992 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:53:06.559  3200  7992 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:53:06.559  3200  7992 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@155a5221
08-31 08:53:06.559  3200  7992 D BluetoothSocket: channel: 12
08-31 08:53:06.559  3200  7992 I BtOppRfcommListener: Accept thread started.
,08-31 08:53:06.569  7982  7982 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:53:06.579  7982  7982 D ActivityThread: Added TimaKeyStore provider
,08-31 08:53:06.689   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 08:53:06.689   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:53:06.689  7982  8003 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 08:53:06.689   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 08:53:06.689   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:53:06.689  7982  8003 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 08:53:06.849  7982  7982 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 08:53:06.849  7982  7982 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 08:53:06.849  7982  7982 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 08:53:06.849  7982  7982 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 08:53:06.849  7982  7982 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 08:53:06.849  7982  7982 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:53:06.849  7982  7982 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:53:06.849  7982  79,82 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:53:06.849  7982  7982 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:53:06.849  7982  7982 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 08:53:06.849  1019  1265 I ActivityManager: Killing 7590:com.sec.pcw.device/1000 (adj 15): empty #21
,08-31 08:53:06.919  7982  8002 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 08:53:06.939  1019  1506 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:53:06.949  1019  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:06.949  1019  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 08:53:06.949  1019  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 08:53:08.949  7379  7432 D BluetoothAdapter: disable()
,08-31 08:53:08.949  1019  3871 D SettingsProvider: name = bluetooth_on
,08-31 08:53:08.959  3200  3275 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-31 08:53:08.959  3200  3275 D BluetoothAdapterProperties: Setting state to 13
08-31 08:53:08.959  3200  3275 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 08:53:08.959  3200  3275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:53:08.959  3200  3275 D BluetoothAdapterService: updateAdapterState state is 13
,08-31 08:53:08.969  1019  1265 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:08.969  1019  1265 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 08:53:08.969  1019  1265 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:08.969  1019  1265 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:53:08.969  1019  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:08.969  3200  3200 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-31 08:53:08.969  3200  3200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3013646, channel: 19, state: LISTENING
,08-31 08:53:08.969  3200  3200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3013646, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2691fe0f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2631a007mSocket: android.net.LocalSocket@2e4d7534 impl:android.net.LocalSocketImpl@2ae8ef5d fd:FileDescriptor[80]
,08-31 08:53:08.969  3200  3200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2e4d7534 impl:android.net.LocalSocketImpl@2ae8ef5d fd:FileDescriptor[80]
,08-31 08:53:08.969  3200  3275 D BluetoothAdapterService: Autoconnection is available 
,08-31 08:53:08.979  4872  4872 D BluetoothPbap: Proxy object disconnected
08-31 08:53:08.979  4872  4872 D PbapServerProfile: Bluetooth service disconnected
08-31 08:53:08.979  3200  3275 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-31 08:53:08.979  3200  3275 D BluetoothAdapterService: terminating service from this receiver
,08-31 08:53:08.979  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:08.979  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,08-31 08:53:08.979  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-31 08:53:08.989  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-31 08:53:08.989  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 08:53:08.989  1182  1182 D BluetoothTile:  getBluetoothState : 13
,08-31 08:53:08.989  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:53:08.989  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:53:08.989  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 08:53:08.999  1880  1880 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:53:08.999  1019  3871 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:53:08.999  1019  1495 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 08:53:08.999  4872  4872 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:08.999  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 08:53:08.999  3200  3200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e35a3, channel: 5, state: LISTENING
08-31 08:53:08.999  3200  3200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3e35a3, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c1050a5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2de6b0a0mSocket: android.net.LocalSocket@10ca2459 impl:android.net.LocalSocketImpl@32fac81e fd:FileDescriptor[82]
08-31 08:53:08.999  3200  3200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@10ca2459 impl:android.net.LocalSocketImpl@32fac81e fd:FileDescriptor[82]
,08-31 08:53:09.009  3200  3200 I BtOppRfcommListener: stopping Accept Thread
08-31 08:53:09.009  3200  3200 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f488ff, channel: 12, state: LISTENING
08-31 08:53:09.009  3200  3200 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f488ff, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@155a5221, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@381636ccmSocket: android.net.LocalSocket@13efad15 impl:android.net.LocalSocketImpl@3707482a fd:FileDescriptor[86]
08-31 08:53:09.009  3200  3200 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@13efad15 impl:android.net.LocalSocketImpl@3707482a fd:FileDescriptor[86]
,08-31 08:53:09.009  3200  7992 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:53:09.009  3200  7992 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 08:53:09.009  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:53:09.009  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:53:09.009  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:09.009  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:09.009  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:53:09.009  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:53:09.009  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:09.009  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:09.009  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:09.009  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:53:09.009  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:09.009  1019  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 08:53:09.009  1019  4377 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:09.009  1019  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:09.009  1019  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:09.019  3200  3275 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 08:53:09.019  3200  3275 D BluetoothAdapterProperties: mDiscovering is false
,08-31 08:53:09.019  1019  1484 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 08:53:09.019  3200  3275 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-31 08:53:09.019  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:53:09.019  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:53:09.019  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:09.019  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:09.019  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:53:09.019  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:53:09.019  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:09.019  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:09.019  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:09.019  4872  4872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:53:09.029  7379  7379 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:53:09.029  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:09.029  3200  3278 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 08:53:09.029  3200  3278 D BluetoothAdapterProperties: Scan Mode:20
,08-31 08:53:09.029  1019  1350 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 08:53:09.029  1019  1350 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 08:53:09.029  1019  1350 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:09.029  1019  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:09.029  1019  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:53:09.029  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:09.029  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:09.039  3200  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-31 08:53:09.039  3200  3275 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-31 08:53:09.039  3200  3275 E bt-btif : cmd socket is not created
,08-31 08:53:09.039  3200  3275 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 08:53:09.039  3200  3279 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-31 08:53:09.039  3200  3200 V BluetoothOppManager: cleanUp...
,08-31 08:53:09.049  3200  3279 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:53:09.049  3200  3279 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:53:09.049  3200  3279 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:53:09.049  3200  3279 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:53:09.049  3200  3279 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:53:09.049  3200  3279 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 08:53:09.049  1657  1657 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:53:09.049  4872  4872 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:53:09.059  4872  4872 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:53:09.059  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:09.059  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 08:53:09.239  3200  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-31 08:53:09.239  3200  3275 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 08:53:09.239  3200  3275 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-31 08:53:09.239  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,08-31 08:53:09.239  3200  3275 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-31 08:53:09.239  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,08-31 08:53:09.239  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 08:53:09.239  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
,08-31 08:53:09.249  1019  4378 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:09.249  1019  4378 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 08:53:09.249  1019  4378 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:09.249  1019  4378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:09.249  1019  4378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:09.249  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 08:53:09.249  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 08:53:09.249  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-31 08:53:09.249  3200  3200 D HeadsetService: Received stop request...Stopping profile...
08-31 08:53:09.249  1019  4380 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:09.249  1019  4380 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:53:09.249  1019  4380 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:09.249  1019  4380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:09.249  1019  4380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:09.249  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-31 08:53:09.249  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:53:09.249  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:09.249  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 08:53:09.259  4872  4872 D HeadsetProfile: Bluetooth service disconnected
,08-31 08:53:09.259  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-31 08:53:09.259  1019  1385 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:09.259  3200  3200 D A2dpService: Received stop request...Stopping profile...
,08-31 08:53:09.259  3200  7963 D A2dpStateMachine: Exit Disconnected: -1
08-31 08:53:09.259  1019  1385 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 08:53:09.259  1019  1385 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:09.259  1019  1385 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:09.259  1019  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:09.259  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-31 08:53:09.259  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 08:53:09.259  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 08:53:09.259  1019  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:09.259  1019  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 08:53:09.259  1019  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:09.259  1019  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:09.259  1019  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:09.259  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-31 08:53:09.259  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 08:53:09.269  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-31 08:53:09.269  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
08-31 08:53:09.269  1019  1019 D BluetoothA2dp: Proxy object disconnected
08-31 08:53:09.269  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 08:53:09.269  4872  4872 D BluetoothA2dp: Proxy object disconnected
08-31 08:53:09.269  4872  4872 D A2dpProfile: Bluetooth service disconnected
,08-31 08:53:09.269  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:09.269  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:53:09.269  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:09.269  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:09.269  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:09.269  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 08:53:09.269  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:53:09.269  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 08:53:09.269  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:09.269  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 08:53:09.279  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:09.279  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:09.279  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:09.279  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-31 08:53:09.279  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 08:53:09.279  3200  3275 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 08:53:09.279  1019  3871 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:09.279  1019  3871 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 08:53:09.279  1019  3871 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:09.279  1019  3871 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:09.279  1019  3871 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:09.279  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:53:09.279  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:53:09.279  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:53:09.279  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:53:09.279  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:53:09.279  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:53:09.279  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 08:53:09.279  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 08:53:09.279  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 08:53:09.279  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 08:53:09.279  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 08:53:09.279  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 08:53:09.279  3200  3275 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-31 08:53:09.279  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-31 08:53:09.279  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:53:09.279  3200  3200 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-31 08:53:09.279  3200  3200 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-31 08:53:09.279  3200  3200 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 08:53:09.289  3200  3200 D HidService: Received stop request...Stopping profile...
,08-31 08:53:09.289  3200  3200 D HidService: Stopping Bluetooth HidService
08-31 08:53:09.289  3200  3200 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 08:53:09.289  3200  3200 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,08-31 08:53:09.289  3200  3200 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 08:53:09.289  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:09.289  3200  3200 D HealthService: Received stop request...Stopping profile...
,08-31 08:53:09.289  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:09.289  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-31 08:53:09.289  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:53:09.289  3200  3200 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 08:53:09.289  3200  3200 D BluetoothA2dp: Proxy object disconnected
08-31 08:53:09.289  3200  3200 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-31 08:53:09.289  3200  7965 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 08:53:09.289  3200  3200 I GKI_LINUX: GKI_exit_task 2 done
08-31 08:53:09.289  3200  3200 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-31 08:53:09.289  4872  4872 D BluetoothInputDevice: Proxy object disconnected
08-31 08:53:09.289  4872  4872 D HidProfile: Bluetooth service disconnected
08-31 08:53:09.289  3200  3200 D PanService: Received stop request...Stopping profile...,
08-31 08:53:09.289  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:09.299  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 08:53:09.299  3200  3200 D BluetoothMapService: Received stop request...Stopping profile...
,08-31 08:53:09.299  4872  4872 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 08:53:09.299  4872  4872 D PanProfile: Bluetooth service disconnected
,08-31 08:53:09.299  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:09.299  3200  3200 D SapService: Received stop request...Stopping profile...
,08-31 08:53:09.299  3200  3200 D SapService: Stopping Bluetooth SapService
08-31 08:53:09.299  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:09.299  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true,
08-31 08:53:09.309  3200  3200 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 08:53:09.309  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService,
08-31 08:53:09.309  3200  3200 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 08:53:09.309  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-31 08:53:09.309  3200  3200 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 08:53:09.309  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 08:53:09.309  3200  3200 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 08:53:09.309  3200  3200 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 08:53:09.309  3200  3200 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 08:53:09.309  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 08:53:09.309  3200  3200 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-31 08:53:09.309  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:53:09.309  3200  3200 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 08:53:09.309  3200  3200 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 08:53:09.309  3200  3200 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 08:53:09.309  4872  4872 D BluetoothMap: Proxy object disconnected
,08-31 08:53:09.309  4872  4872 D MapProfile: Bluetooth service disconnected
08-31 08:53:09.309  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-31 08:53:09.309  3200  3200 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 08:53:09.309  4872  4872 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 08:53:09.309  3200  3200 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 08:53:09.309  4872  4872 D SapProfile: Bluetooth service disconnected
08-31 08:53:09.309  3200  3200 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-31 08:53:09.309  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-31 08:53:09.309  3200  3200 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 08:53:09.309  3200  3200 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 08:53:09.309  3200  3200 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-31 08:53:09.309  3200  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-31 08:53:09.309  3200  3275 D BluetoothAdapterProperties: Setting state to 10
08-31 08:53:09.309  3200  3275 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 08:53:09.309  3200  3275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:53:09.309  3200  3275 D BluetoothAdapterService: updateAdapterState state is 10
,08-31 08:53:09.309  3200  3275 D BluetoothAdapterService: Autoconnection is available 
08-31 08:53:09.309  3200  3211 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 08:53:09.309  3200  3275 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-31 08:53:09.309  3200  3275 I BluetoothAdapterState: Entering OffState
,08-31 08:53:09.309  7379  7387 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:53:09.309  7379  7387 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:53:09.309  7379  7387 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-31 08:53:09.309  7379  7387 D BluetoothLeAdvertiser: Exit stop advertising
08-31 08:53:09.309  7379  7387 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-31 08:53:09.309  7379  7387 D BluetoothLeScanner: Exiting stopAllScan
,08-31 08:53:09.309  4872  7977 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 08:53:09.319  1433  1451 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:53:09.319  1433  1451 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:53:09.319  1460  1861 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:53:09.319  1460  1861 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:53:09.319  7982  7999 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:53:09.319  7982  7999 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:53:09.319  1182  1191 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:53:09.319  1182  1191 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:53:09.319  4872  4880 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 08:53:09.319  4872  7977 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 08:53:09.319  4872  4880 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:53:09.319  4872  4880 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:53:09.319  1743  1754 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:53:09.319  1743  1754 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:53:09.319  3200  3370 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:53:09.329  3200  3370 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:53:09.329  4872  7977 D Bluetoothsap: onBluetoothStateChange: up=false
08-31 08:53:09.329  4872  7977 D Bluetoothsap: Unbinding service...
,08-31 08:53:09.329  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 08:53:09.329  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:53:09.329  1019  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:53:09.329  1444  1477 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:53:09.329  1444  1477 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:53:09.329  4872  4882 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 08:53:09.329  1657  1668 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:53:09.329  1657  1668 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:53:09.329  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:09.329  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
08-31 08:53:09.329  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 08:53:09.339  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 08:53:09.339  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:09.339  1182  1182 D BluetoothTile:  getBluetoothState : 10
,08-31 08:53:09.339  1019  4380 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:53:09.349  1880  1880 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:53:09.349  1019  4378 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 08:53:09.349  4872  4872 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:09.349  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 08:53:09.349  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:09.349  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:09.359  4872  4872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:53:09.359  1019  4381 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 08:53:09.359  1019  4381 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 08:53:09.359  1019  4381 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:09.359  1019  4381 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:09.359  1019  4381 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:53:09.359  1657  1657 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:53:09.369  4872  4872 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:53:09.369  4872  4872 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:53:09.369  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:09.369  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 08:53:09.429   289   289 E SMD     : DCD OFF
,08-31 08:53:10.399  1019  3401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-31 08:53:10.679  1019  3368 D SSRM:n  : SIOP:: AP = 300,
,08-31 08:53:11.439   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 08:53:11.959  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:53:11.959  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:53:12.429   289   289 E SMD     : DCD OFF,
,08-31 08:53:12.439   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:53:12.589  1019  1098 V AlarmManager: waitForAlarm result :4,
,08-31 08:53:12.599   279   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:53:12.599   279   975 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-31 08:53:12.609  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:12.609  1019  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:12.609  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-31 08:53:13.439   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:53:13.829  1019  1350 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 08:53:13.829  1019  1350 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-31 08:53:13.829  1019  1350 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
08-31 08:53:13.829  1019  1350 D BatteryService: stay LED for charging,
08-31 08:53:13.839  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 08:53:13.829  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-31 08:53:13.839  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 08:53:13.829  1019  1019 I MotionRecognitionService: Plugged
08-31 08:53:13.829  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false,
08-31 08:53:13.839  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 08:53:13.839  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 08:53:13.859  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 08:53:13.859  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 08:53:13.869  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 08:53:14.439   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 08:53:14.969  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-31 08:53:14.969  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fa932d added. We now have 6 listener(s)
08-31 08:53:14.969  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:53:14.969  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:53:14.969  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c569062 added. We now have 7 listener(s)
08-31 08:53:14.969  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:53:14.969  7379  7432 I System.out: IsBluetoothEnabled
08-31 08:53:14.969  7379  7432 D BluetoothAdapter: disable()
,08-31 08:53:14.979  1019  1031 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
08-31 08:53:14.979  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:14.979  7379  7432 D BluetoothAdapter: enable()
,08-31 08:53:14.989  1019  1350 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-31 08:53:14.989  1019  1350 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7379, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:53:14.989  1019  1350 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 08:53:14.989  1019  1350 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256),
08-31 08:53:14.989  1019  1350 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 08:53:14.989  1019  1350 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-31 08:53:14.989  1019  1350 W BluetoothManagerService: 	,at android.os.Binder.execTransact(Binder.java:446)
08-31 08:53:14.989  1019  1350 W ActivityManager: Permission Denial: getCurrentUser() from pid=7379, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 08:53:14.989  1019  1350 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-31 08:53:14.989  1019  1350 D SettingsProvider: name = bluetooth_on,
,08-31 08:53:14.989  1019  1350 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 08:53:14.999  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 08:53:14.999  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-31 08:53:14.999  1019  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
08-31 08:53:15.009  3200  3275 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-31 08:53:15.009  3200  3275 D BluetoothAdapterProperties: Setting state to 11
08-31 08:53:15.009  3200  3275 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 08:53:15.009  3200  3275 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
08-31 08:53:15.009  3200  3275 D BluetoothAdapterService: updateAdapterState state is 11
08-31 08:53:15.009  3200  3275 D BluetoothAdapterService: Autoconnection is available 
08-31 08:53:15.009  3200  3275 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 08:53:15.009  3200  3275 D BtConfig.SecureMode: isSecureModeOn:false
08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
,08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,08-31 08:53:15.009  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 08:53:15.009  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 08:53:15.009  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:15.009  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,08-31 08:53:15.019  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:15.019  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 08:53:15.019  1182  1182 D BluetoothTile:  getBluetoothState : 11
,08-31 08:53:15.019  1880  1880 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:53:15.019  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
08-31 08:53:15.019  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 08:53:15.019  4872  4872 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:15.019  1019  1461 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:53:15.029  1019  4381 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:15.029  1019  4381 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.029  1019  3871 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 08:53:15.029  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:15.029  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 08:53:15.029  1019  4381 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.029  1019  4381 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.029  1019  4381 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.029  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 08:53:15.029  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 08:53:15.029  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 08:53:15.039  3200  3200 D HeadsetService: Received start request. Starting profile...
,08-31 08:53:15.039  3200  3200 D HeadsetService: start()
,08-31 08:53:15.039  3200  3200 D HeadsetStateMachine: make
,08-31 08:53:15.039  1019  4380 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:15.039  1019  4380 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.039  1019  4380 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.039  1019  4380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:53:15.039  1019  4380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.049  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-31 08:53:15.049  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:53:15.049  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 08:53:15.049  1657  1657 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:53:15.049  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:15.049  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.049  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.049  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:53:15.049  3200  3200 E HeadsetStateMachine: # of Max HF connection is 2
08-31 08:53:15.049  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.049  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-31 08:53:15.049  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 08:53:15.049  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 08:53:15.049  1019  4378 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:15.049  1019  4378 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.049  1019  4378 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.049  1019  4378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.049  1019  4378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.059  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-31 08:53:15.059  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 08:53:15.059  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 08:53:15.059  1019  4377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:15.059  1019  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.059  1019  4377 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.059  1019  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:53:15.059  1019  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.069  1019  1461 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-31 08:53:15.069  1019  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.069  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 08:53:15.069  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 08:53:15.069  3200  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 08:53:15.069  1019  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.069  1019  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.069  1019  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 08:53:15.079  1019  3871 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:15.079  1019  3871 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.079  1019  3871 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.079  1019  3871 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:53:15.079  1019  3871 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.079  1019  4381 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-31 08:53:15.079  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-31 08:53:15.079  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 08:53:15.079  3200  3275 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-31 08:53:15.079  1019  4381 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.079  1019  4381 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.079  1019  4381 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.079  1019  4381 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 08:53:15.079  1019  3871 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:15.079  3200  3200 I bluedroid: get_profile_interface handsfree
,08-31 08:53:15.089  4872  4872 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:53:15.089  1019  3871 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.089  1019  3871 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.089  1019  3871 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.089  1019  3871 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.089  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:53:15.089  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService,
08-31 08:53:15.089  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:53:15.089  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:53:15.089  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:53:15.089  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:53:15.089  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService,
08-31 08:53:15.089  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 08:53:15.089  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 08:53:15.089  3200  3275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService,
08-31 08:53:15.089  3200  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 08:53:15.089  3200  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-31 08:53:15.089  3200  3275 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 08:53:15.099  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:15.099  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 08:53:15.099  3200  3200 E DualScoManager: Dual Sco Manager already instantiated,
08-31 08:53:15.099  3200  3200 I DualScoManager: Set HeadsetServiceHelper
08-31 08:53:15.099  3200  3200 D BluetoothAtMessage: createCMTIContentObservers
,08-31 08:53:15.099  1019  4378 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-31 08:53:15.099  1019  4378 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:53:15.099  1019  4378 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:53:15.099  1019  4378 D SettingsProvider: selectionArgs: false
08-31 08:53:15.099  1019  4378 D SettingsProvider: selectionArgs: 1002
08-31 08:53:15.099  1019  4378 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:53:15.099  1019  4378 D SettingsProvider: ret = -1
,08-31 08:53:15.099  3200  8030 D HeadsetStateMachine: Enter Disconnected: -2,
,08-31 08:53:15.109  3200  3200 D HeadsetService: mStartError = false
08-31 08:53:15.109  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:15.109  3200  3200 D A2dpService: Received start request. Starting profile...
,08-31 08:53:15.109  3200  3200 D A2dpService: start()
08-31 08:53:15.109  3200  3200 I bluedroid: get_profile_interface avrcp
08-31 08:53:15.109  3200  8030 D HeadsetStateMachine: Clear mHeadsetBrsf
08-31 08:53:15.109  3200  8030 D HeadsetStateMachine: map size, before remove : 0
08-31 08:53:15.109  3200  8030 D HeadsetStateMachine: map size, after remove: 0
,08-31 08:53:15.109  3200  3200 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 08:53:15.109  3200  3200 D Avrcp   : Initialize Media Controller
08-31 08:53:15.109  3200  3200 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-31 08:53:15.119  3200  3200 E Avrcp   : getActiveSessions
,08-31 08:53:15.119  3200  3200 D Avrcp   : pick active media Controller
08-31 08:53:15.119  3200  3200 D Avrcp   : Get the active Media Controller 
,08-31 08:53:15.119  3200  3200 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 08:53:15.119  3200  3200 D A2dpStateMachine: make
,08-31 08:53:15.119  3200  8031 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 08:53:15.129  3200  3200 I bluedroid: get_profile_interface a2dp
08-31 08:53:15.129  3200  8033 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 08:53:15.129  3200  3200 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 08:53:15.129  3200  3200 D A2dpService: mStartError = false
08-31 08:53:15.129  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:15.129  3200  8032 D A2dpStateMachine: Enter Disconnected: -2
,08-31 08:53:15.129  3200  3200 D HidService: Received start request. Starting profile...
08-31 08:53:15.129  3200  3200 D HidService: start()
08-31 08:53:15.129  3200  3200 I bluedroid: get_profile_interface hidhost
08-31 08:53:15.129  3200  3200 D HidService: setHidService(): set to: null
08-31 08:53:15.129  3200  3200 D HidService: mStartError = false
08-31 08:53:15.129  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:15.129  3200  3200 D HealthService: Received start request. Starting profile...
,08-31 08:53:15.129  3200  3200 D HealthService: start()
,08-31 08:53:15.129  3200  3200 I bluedroid: get_profile_interface health
,08-31 08:53:15.129  3200  3200 D HealthService: mStartError = false
08-31 08:53:15.129  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:15.129  3200  3200 D PanService: Received start request. Starting profile...
08-31 08:53:15.129  3200  3200 D PanService: start()
08-31 08:53:15.129  3200  3200 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 08:53:15.129  3200  3200 I bluedroid: get_profile_interface pan
08-31 08:53:15.129  3200  3200 D PanService: mStartError = false
08-31 08:53:15.129  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
08-31 08:53:15.129  3200  3200 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 08:53:15.129  1433  1451 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 08:53:15.129  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-31 08:53:15.129  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 08:53:15.129  1433  1451 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 08:53:15.129  3200  3200 D HeadsetStateMachine: Proxy object connected
,08-31 08:53:15.139  3200  3200 D BluetoothMapService: Received start request. Starting profile...
,08-31 08:53:15.139  3200  3200 D BluetoothMapService: start()
,08-31 08:53:15.139  3200  3200 D BluetoothMapService: mStartError = false
,08-31 08:53:15.139  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
08-31 08:53:15.139  3200  3200 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 08:53:15.139  3200  8030 D HeadsetStateMachine: Disconnected process message: 11
,08-31 08:53:15.139  3200  3200 D SapService: Received start request. Starting profile...
,08-31 08:53:15.139  3200  3200 D SapService: start()
08-31 08:53:15.139  3200  3200 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 08:53:15.139  3200  3200 I bluedroid: get_profile_interface sap
08-31 08:53:15.139  3200  3200 D SapService: mStartError = false
08-31 08:53:15.139  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
08-31 08:53:15.139  3200  3200 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 08:53:15.139  3200  3200 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-31 08:53:15.139  3200  3200 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 08:53:15.139  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-31 08:53:15.139  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 08:53:15.139  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 08:53:15.139  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 08:53:15.139  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-31 08:53:15.139  3200  8030 D HeadsetStateMachine: Disconnected process message: 18
08-31 08:53:15.139  3200  8030 D HeadsetStateMachine: Disconnected process message: 10
08-31 08:53:15.139  3200  8030 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 08:53:15.139  3200  8030 D HeadsetStateMachine: Disconnected process message: 11
,08-31 08:53:15.149  3200  8031 D BluetoothMediaBrowser: no now playing list
,08-31 08:53:15.149  3200  8031 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-31 08:53:15.159  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-31 08:53:15.159  3200  3200 E BluetoothAdapterService(242815826): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 08:53:15.159  3200  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-31 08:53:15.159  3200  3275 I bluedroid: enable
,08-31 08:53:15.169  3200  3278 E bt-btif : Calling BTA_HhEnable
08-31 08:53:15.169  3200  3278 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 08:53:15.169  3200  3278 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 08:53:15.169  3200  3278 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-31 08:53:15.169  3200  3278 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-31 08:53:15.169  3200  3278 E BluetoothServiceJni: populateRssiValuesNative
08-31 08:53:15.169  3200  3278 I bluedroid: getModelRssiValues
08-31 08:53:15.169  3200  3278 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 08:53:15.169  3200  3278 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 08:53:15.169  3200  3278 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-31 08:53:15.169  1019  1019 D SettingsProvider: name = bluetooth_name
,08-31 08:53:15.169  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:15.179  3200  3278 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 08:53:15.179  3200  3278 D BluetoothAdapterProperties: Scan Mode:20
,08-31 08:53:15.179  3200  3278 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 08:53:15.179  3200  3278 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-31 08:53:15.179  3200  3278 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-31 08:53:15.179  3200  3278 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-31 08:53:15.179  3200  3278 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-31 08:53:15.179  3200  3278 E bt-btif : JVenable fails
,08-31 08:53:15.179  3200  3278 D bte_conf: Device ID record 1 : primary
,08-31 08:53:15.179  3200  3278 D bte_conf:   vendorId            = 0075
08-31 08:53:15.179  3200  3278 D bte_conf:   vendorIdSource      = 0001
,08-31 08:53:15.179  3200  3278 D bte_conf:   product             = 0100
08-31 08:53:15.179  3200  3278 D bte_conf:   version             = 0200
,08-31 08:53:15.179  3200  3278 D bte_conf:   clientExecutableURL = 
,08-31 08:53:15.179  3200  3278 D bte_conf:   serviceDescription  = 
08-31 08:53:15.179  3200  3278 D bte_conf:   documentationURL    = 
,08-31 08:53:15.179  3200  3278 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 08:53:15.189  3200  3278 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 08:53:15.189  3200  3278 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 08:53:15.189  3200  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-31 08:53:15.189  3200  3275 D BluetoothAdapterProperties: ScanMode =  20
08-31 08:53:15.189  3200  3275 D BluetoothAdapterProperties: State =  11
,08-31 08:53:15.189  1019  1506 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 08:53:15.189  3200  3275 D BluetoothAdapterProperties: Setting state to 12
,08-31 08:53:15.189  3200  3275 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 08:53:15.189  3200  3278 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 08:53:15.189  3200  3278 D BluetoothAdapterProperties: Scan Mode:21
08-31 08:53:15.189  3200  3278 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 08:53:15.189  1019  4378 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-31 08:53:15.189  1019  4378 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 08:53:15.199  1019  4378 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:53:15.199  1019  4378 D SettingsProvider: selectionArgs: false,
08-31 08:53:15.199  1019  4378 D SettingsProvider: selectionArgs: 1002,
08-31 08:53:15.199  1019  4378 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:53:15.199  1019  1265 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:15.199  1019  4378 D SettingsProvider: ret = -1
08-31 08:53:15.199  1019  1265 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.199  3200  3275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:53:15.199  3200  3275 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 08:53:15.199  1019  1265 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.199  1019  1265 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.199  1019  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.199  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:53:15.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:15.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:15.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:53:15.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:53:15.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:15.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:15.199  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:15.199  3200  3275 D BluetoothAdapterService: Autoconnection is available 
,08-31 08:53:15.199  3200  3275 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 08:53:15.199  3200  3275 D BluetoothAdapterService: starting service from this receiver
,08-31 08:53:15.199  1019  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:53:15.199  3200  3211 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:53:15.199  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.199  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.199  3200  3211 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-31 08:53:15.199  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.199  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.209  3200  3200 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-31 08:53:15.209  3200  3200 I BluetoothPbapService: Handler(): got msg=1
,08-31 08:53:15.209  1019  1049 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 08:53:15.209  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.209  3200  3275 I BluetoothAdapterState: Entering On State from state = 11
08-31 08:53:15.209  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:15.209  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.209  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.209  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.209  1019  1265 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 08:53:15.209  7379  7388 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:15.209  7379  7388 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:53:15.209  4872  4880 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 08:53:15.209  3200  8038 V BluetoothPbapService: PBAP Service initSocket try: 0
08-31 08:53:15.209  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-31 08:53:15.209  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.219  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.219  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.219  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.219  1433  3358 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:15.219  1433  3358 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:53:15.219  1460  4802 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:53:15.219  1460  4802 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:53:15.219  1460  4801 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:15.219  3200  8038 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 08:53:15.219  3200  8038 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:53:15.219  3200  3200 D BluetoothA2dp: Proxy object connected
08-31 08:53:15.219  3200  3200 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-31 08:53:15.219  4872  4872 D BluetoothMap: Proxy object connected
08-31 08:53:15.219  4872  4872 D MapProfile: Bluetooth service connected
08-31 08:53:15.219  1019  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 08:53:15.219  4872  4872 D BluetoothMap: getConnectedDevices()
,08-31 08:53:15.219  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:53:15.229  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.229  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.229  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.229  1460  4801 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:53:15.229  3200  8038 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-31 08:53:15.229  3200  8038 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:53:15.229  3200  8038 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:53:15.229  3200  8038 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20ff99e2
08-31 08:53:15.229  3200  8038 D BluetoothSocket: channel: 19
08-31 08:53:15.229  3200  8038 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 08:53:15.229  7982  7996 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:15.229  7982  7996 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:15.229  4872  4882 D BluetoothPan: Binding service...
,08-31 08:53:15.229  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 08:53:15.229  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.229  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.229  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.229  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.239  4872  4872 D BluetoothPan: BluetoothPAN Proxy object connected,
,08-31 08:53:15.249  4872  4872 D PanProfile: Bluetooth service connected
08-31 08:53:15.239  1433  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:15.249  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:53:15.249  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:53:15.249  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.249  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.249  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.249  1433  1452 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:53:15.249  1433  3358 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:15.249  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 08:53:15.249  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:53:15.249  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.249  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.249  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.249  1433  3358 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 08:53:15.249  1182  1909 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:53:15.249  1182  1909 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:15.249  1019  1049 D BluetoothPan: Binding service...
,08-31 08:53:15.249  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 08:53:15.249  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.249  4872  7977 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 08:53:15.249  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 08:53:15.249  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-31 08:53:15.259  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.259  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.259  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.259  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.259  4872  4872 D BluetoothPbap: Proxy object connected
,08-31 08:53:15.259  4872  4872 D PbapServerProfile: Bluetooth service connected
08-31 08:53:15.259  4872  4880 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:53:15.259  4872  4880 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:15.259  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 08:53:15.259  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.259  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.259  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.259  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.259  4872  4872 D BluetoothA2dp: Proxy object connected
08-31 08:53:15.259  4872  4872 D A2dpProfile: Bluetooth service connected
,08-31 08:53:15.269  4872  7977 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:53:15.269  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:53:15.269  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:53:15.269  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.269  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.269  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.269  4872  4872 D HeadsetProfile: Bluetooth service connected
,08-31 08:53:15.269  4872  7977 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:53:15.269  4872  4880 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:53:15.269  4872  4880 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:53:15.269  1019  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 08:53:15.269  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:53:15.269  1019  1049 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 08:53:15.269  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:53:15.269  1743  1754 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:15.269  1743  1754 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:15.269  3200  3354 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:53:15.269  3200  3354 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:53:15.269  4872  4882 D Bluetoothsap: onBluetoothStateChange: up=true
,08-31 08:53:15.269  4872  4882 D Bluetoothsap: Binding service...
,08-31 08:53:15.269  4872  4882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-31 08:53:15.409  1019  1049 I art     : Explicit concurrent mark sweep GC freed 19289(1191KB) AllocSpace objects, 5(81KB) LOS objects, 33% free, 23MB/34MB, paused 2.329ms total 138.614ms
08-31 08:53:15.409  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-31 08:53:15.409  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.409  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.419  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:53:15.419  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.419  4872  4882 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-31 08:53:15.419  1433  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 08:53:15.419  4872  4872 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-31 08:53:15.419  4872  4872 D SapProfile: Bluetooth service connected
08-31 08:53:15.419  4872  4872 D Bluetoothsap: getConnectedDevices()
08-31 08:53:15.419  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:53:15.419  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:53:15.419  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.419  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.419  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.419  1433  1452 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 08:53:15.419  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 08:53:15.419  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 08:53:15.419  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 08:53:15.419  1019  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-31 08:53:15.419  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:15.419  1019  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:15.419  1019  1019 D BluetoothA2dp: Proxy object connected
08-31 08:53:15.419  1444  1477 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:15.419  1444  1477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:15.419  4872  7977 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 08:53:15.419  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-31 08:53:15.419  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.419  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:15.419  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.419  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.429  1657  1676 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:53:15.429  1657  1676 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:53:15.429  4872  4872 D BluetoothInputDevice: Proxy object connected
08-31 08:53:15.429  4872  4872 D HidProfile: Bluetooth service connected
08-31 08:53:15.429  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 08:53:15.429  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 08:53:15.429  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:15.429  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
,08-31 08:53:15.429  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 08:53:15.429   289   289 E SMD     : DCD OFF
,08-31 08:53:15.429  1433  1433 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@96f48d6, true
,08-31 08:53:15.439  1433  1433 D BluetoothHeadset: registerMessageListener
,08-31 08:53:15.439  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-31 08:53:15.439   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:53:15.439  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 08:53:15.439  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:53:15.439  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:15.439  1182  1182 D BluetoothTile:  getBluetoothState : 12
,08-31 08:53:15.439  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:53:15.449  1182  1735 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:53:15.449  1019  1495 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:53:15.449  1880  1880 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:53:15.449  1019  1461 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 08:53:15.449  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:53:15.449  4872  4872 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:15.459  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:15.459  3200  3211 D HeadsetService: registerMessageListener
,08-31 08:53:15.459  3200  3211 D HeadsetService: registerMessageListener
,08-31 08:53:15.459  3200  8030 D HeadsetStateMachine: Disconnected process message: 70
08-31 08:53:15.459  3200  8030 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@14839173
,08-31 08:53:15.459  3200  8040 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-31 08:53:15.459  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-31 08:53:15.459  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 08:53:15.459  4872  4872 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-31 08:53:15.459  4872  4872 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-31 08:53:15.459  4872  4872 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 08:53:15.459  4872  4872 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 08:53:15.469  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-31 08:53:15.469  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-31 08:53:15.469  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 08:53:15.469  3200  8030 D HeadsetStateMachine: Disconnected process message: 9
,08-31 08:53:15.469  3200  8030 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 08:53:15.469  3200  8040 D BluetoothSocket: bindListen(): myUserId = 0
08-31 08:53:15.469  3200  8040 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:53:15.469  3200  8040 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-31 08:53:15.469  3200  8040 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:53:15.469  3200  8040 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:53:15.469  3200  8040 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4482830
,08-31 08:53:15.469   284   749 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-31 08:53:15.469   284   749 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 08:53:15.469   284   749 V voice   : voice_set_parameters: exit with code(-2)
08-31 08:53:15.469   284   749 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 08:53:15.469   284   749 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 08:53:15.469   284   749 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 08:53:15.469   284   749 V audio_hw_primary: adev_set_parameters: exit
08-31 08:53:15.469  3200  8030 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-31 08:53:15.479  3200  8040 D BluetoothSocket: channel: 5
,08-31 08:53:15.479  4872  4872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:53:15.479  1019  1461 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 08:53:15.479  1019  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.479  1019  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.479  1019  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:53:15.479  1019  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:53:15.489  1657  1657 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:53:15.489  4872  4872 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:53:15.489  4872  4872 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:53:15.499  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:53:15.499  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 08:53:15.509  3200  3200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e791352
,08-31 08:53:15.509  3200  3200 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 08:53:15.509  1019  4377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:53:15.509  1019  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 08:53:15.509  1019  4377 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:15.509  1019  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:15.509  1019  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:53:15.519  1019  4377 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 08:53:15.529  3200  8045 D BluetoothSocket: bindListen(): myUserId = 0
08-31 08:53:15.529  3200  8045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:53:15.529  3200  8045 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-31 08:53:15.529  3200  8045 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:53:15.529  3200  8045 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:53:15.529  3200  8045 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c3f975c
,08-31 08:53:15.529  3200  8045 D BluetoothSocket: channel: 12
,08-31 08:53:15.529  3200  8045 I BtOppRfcommListener: Accept thread started.
,08-31 08:53:16.009  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:53:16.009  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:16.009  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:16.009  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:53:16.009  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:53:16.009  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:16.009  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:16.009  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:16.009  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:16.009  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:53:16.009  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ea585f3 added. We now have 8 listener(s)
,08-31 08:53:16.009  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:53:16.019  1019  1461 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 08:53:16.019  1019  1461 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 08:53:16.019  1019  1461 D SecContentProvider2: mCursor = null
,08-31 08:53:16.019  1019  1461 D WifiService: setWifiEnabled: false pid=7379, uid=10170
,08-31 08:53:16.019  1019  1461 D SettingsProvider: name = wifi_on
,08-31 08:53:16.019  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:16.029  1019  3871 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 08:53:16.029  1019  3871 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 08:53:16.029  1019  3871 D SecContentProvider2: mCursor = null
,08-31 08:53:16.029  1019  3871 D WifiService: setWifiEnabled: true pid=7379, uid=10170
,08-31 08:53:16.029  1019  3871 W ActivityManager: Permission Denial: getCurrentUser() from pid=7379, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 08:53:16.029  1019  3871 W WifiService: Failed getting userId using ActivityManagerNative
08-31 08:53:16.029  1019  3871 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7379, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:53:16.029  1019  3871 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 08:53:16.029  1019  3871 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 08:53:16.029  1019  3871 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 08:53:16.029  1019  3871 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 08:53:16.029  1019  3871 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 08:53:16.029  1019  3871 D SettingsProvider: name = wifi_on
,08-31 08:53:16.039  1019  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 08:53:16.359  1019  1047 D Tethering: interfaceAdded wlan0
,08-31 08:53:16.369  1019  1133 E Tethering: No numeric data
,08-31 08:53:16.369  1019  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-31 08:53:16.369  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:16.369  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 08:53:16.369  1182  1182 D HotspotTile: updateTetherState():false, false
,08-31 08:53:16.379  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 08:53:16.379  1019  1133 D Tethering: clearTetheredNotification()
,08-31 08:53:16.379  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:16.379  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:53:16.379  1019  1125 V NetworkStats: performPollLocked() took 10ms
,08-31 08:53:16.379  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:16.379  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:16.379  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:16.389  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 08:53:16.389  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:53:16.389  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 08:53:16.389  1019  1133 D Tethering: InitialState.processMessage what=4
,08-31 08:53:16.389  1019  1133 E Tethering: No numeric data
,08-31 08:53:16.399  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 08:53:16.399  1019  1133 D Tethering: clearTetheredNotification()
,08-31 08:53:16.399  1019  1047 D Tethering: interfaceAdded p2p0,
,08-31 08:53:16.399  1019  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 08:53:16.399  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 08:53:16.399  1182  1182 D HotspotTile: updateTetherState():false, false
,08-31 08:53:16.399  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:53:16.399  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:53:16.409  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 08:53:16.409  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 08:53:16.409  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:16.409  1019  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:53:16.409   279   979 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 08:53:16.409  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:53:16.409   279   979 D SoftapController: Softap fwReload - Ok
,08-31 08:53:16.409   279   979 D CommandListener: Setting iface cfg,
08-31 08:53:16.409   279   979 D CommandListener: Trying to bring down wlan0
08-31 08:53:16.409  1019  1125 V NetworkStats: performPollLocked() took 6ms
08-31 08:53:16.409  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:16.409   279   979 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:53:16.419  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 08:53:16.419  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:16.419  1019  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 08:53:16.439   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-31 08:53:16.469  8056  8056 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-31 08:53:16.469  8056  8056 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 08:53:16.469  8056  8056 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,08-31 08:53:16.489  8056  8056 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-31 08:53:16.489   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 8056
08-31 08:53:16.489   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
,08-31 08:53:16.489  8056  8056 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 08:53:16.489  8056  8056 I wpa_supplicant: ssSupport state is = 1,
08-31 08:53:16.489  8056  8056 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 08:53:16.489  8056  8056 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-31 08:53:16.489   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 8056
08-31 08:53:16.489   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-31 08:53:16.519  1019  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-31 08:53:16.539  4872  4872 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:53:16.539  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:53:16.539  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:16.539  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:53:16.539  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:16.539  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:16.539  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:16.539  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:16.539  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:53:16.539  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:53:16.539  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-31 08:53:16.539  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 08:53:16.539  1182  1182 D HotspotTile: onReceive : 2, 0
08-31 08:53:16.549  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:16.549  1019  4381 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:53:16.549  1019  4381 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:53:16.549  1019  4381 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:16.549  1019  4381 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:16.549  1019  4381 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:53:16.549  1638  1638 I Hs20UtilService: Starting #19
,08-31 08:53:16.549  1638  1695 I Hs20UtilService: Message received 5011
,08-31 08:53:16.549  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 08:53:16.549  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 08:53:16.549  7572  7572 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:53:16.549  7572  7572 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:53:16.649   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-31 08:53:16.649  8056  8056 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-31 08:53:16.699  8056  8056 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 08:53:16.699  8056  8056 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 08:53:16.709  8056  8056 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 08:53:16.709   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 8056
08-31 08:53:16.709   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 08:53:16.709  8056  8056 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-31 08:53:16.709  8056  8056 I wpa_supplicant: ssSupport state is = 1,
08-31 08:53:16.709  8056  8056 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:53:16.709  8056  8056 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:53:16.709  8056  8056 E wpa_supplicant: SIM READ ERROR
08-31 08:53:16.709  8056  8056 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:53:16.709  8056  8056 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 08:53:16.709  8056  8056 E wpa_supplicant: SIM READ ERROR
08-31 08:53:16.709  8056  8056 I wpa_supplicant: Blacklist: Clear (all) 
08-31 08:53:16.709  8056  8056 I wpa_supplicant: wpa_default_ap_write_once
08-31 08:53:16.709  8056  8056 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 08:53:16.709  8056  8056 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-31 08:53:16.709  8056  8056 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 08:53:16.709  8056  8056 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:53:16.709  8056  8056 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 08:53:16.709  8056  8056 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-31 08:53:16.709  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 08:53:16.709  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:53:16.709  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:53:16.819  8056  8056 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-31 08:53:16.989  8056  8056 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-31 08:53:16.989  8056  8056 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-31 08:53:16.999  8056  8056 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-31 08:53:16.999   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 8056
08-31 08:53:16.999   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-31 08:53:16.999  8056  8056 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-31 08:53:16.999  8056  8056 I wpa_supplicant: ssSupport state is = 1
08-31 08:53:17.009  8056  8056 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 08:53:17.009  8056  8056 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-31 08:53:17.019  8056  8056 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 08:53:17.019   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 8056
08-31 08:53:17.019   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-31 08:53:17.019  8056  8056 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
,08-31 08:53:17.019  8056  8056 I wpa_supplicant: ssSupport state is = 1
08-31 08:53:17.029  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-31 08:53:17.019  8056  8056 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:53:17.029  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-31 08:53:17.019  8056  8056 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:53:17.019  8056  8056 E wpa_supplicant: SIM READ ERROR
,08-31 08:53:17.019  8056  8056 I wpa_supplicant: wpa_default_ap_write_once
08-31 08:53:17.019  8056  8056 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 08:53:17.019  8056  8056 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
08-31 08:53:17.029  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:53:17.029  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
08-31 08:53:17.029  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 08:53:17.029  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:53:17.069  8056  8056 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-31 08:53:17.069  8056  8056 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 08:53:17.179  8056  8056 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-31 08:53:17.179  8056  8056 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-31 08:53:17.179  8056  8056 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 08:53:17.189  1019  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-31 08:53:17.189  1019  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 08:53:17.189  8056  8056 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-31 08:53:17.189  8056  8056 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 08:53:17.199  8056  8056 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:53:17.199  8056  8056 E wpa_supplicant: SIM READ ERROR
08-31 08:53:17.199  8056  8056 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 08:53:17.219  8056  8056 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-31 08:53:17.229  8056  8056 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 08:53:17.239  1019  1128 D WifiConfigStore: Loading config and enabling all networks 
,08-31 08:53:17.239  4872  4872 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:53:17.239  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:53:17.239  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:53:17.239  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:53:17.239  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:17.239  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:53:17.239  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:17.239  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:17.239  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:17.239  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:53:17.239  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:17.239  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:17.239  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:17.239  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:53:17.239  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-31 08:53:17.239  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:53:17.239  1182  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 08:53:17.239  1182  1182 D HotspotTile: onReceive : 3, 0
,08-31 08:53:17.249  1638  1638 I Hs20UtilService: Starting #20
,08-31 08:53:17.249  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:53:17.249  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:17.249  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:17.249  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:53:17.249  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:53:17.249  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:17.249  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:17.249  7379  7379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:17.249  1019  1128 E WifiConfigStore: Not a HS20
,08-31 08:53:17.249  7379  7379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:17.249  1638  1695 I Hs20UtilService: Message received 5011
,08-31 08:53:17.259  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 08:53:17.259  1019  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 08:53:17.259  7572  7572 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 08:53:17.259  7572  7572 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:53:17.259  7572  7572 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:53:17.259  1019  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 08:53:17.259  8056  8056 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 08:53:17.259  8056  8056 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 08:53:17.259  8056  8056 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 08:53:17.259  8056  8056 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 08:53:17.259  8056  8056 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 08:53:17.259  8056  8056 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 08:53:17.259  8056  8056 I wpa_supplicant: First Scan Start
,08-31 08:53:17.259  8056  8056 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 08:53:17.259  1019  1128 D WifiNative-wlan0: Setting external_sim to 1
,08-31 08:53:17.259  1019  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 08:53:17.259  1019  1128 I WifiNative-HAL: startHal
08-31 08:53:17.259  1019  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9d61688c
08-31 08:53:17.259  1019  1128 I WifiNative-HAL: Could not start hal
,08-31 08:53:17.269  7549  7549 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:53:17.269  1019  1128 E WifiNative-wlan0: do suspend true
,08-31 08:53:17.269  1019  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-31 08:53:17.269  1019  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 08:53:17.269  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 08:53:17.269  1019  1153 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:53:17.269  1019  1153 I WifiNative-HAL: startHal
08-31 08:53:17.269  1019  1153 E wifi    : getStaticLongField sWifiHalHandle 0x9e4cc9bc
08-31 08:53:17.269  1019  1153 I WifiNative-HAL: Could not start hal
,08-31 08:53:17.269  1019  1153 E WifiScanningService: could not start HAL
08-31 08:53:17.269  1019  1019 D RttService: SCAN_AVAILABLE : 3
08-31 08:53:17.269  1019  1154 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:53:17.269   279   979 D CommandListener: Setting iface cfg
,08-31 08:53:17.269   279   979 D CommandListener: Trying to bring up p2p0
,08-31 08:53:17.269  1019  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 08:53:17.269  1019  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 08:53:17.269  1019  1128 E WifiNative-wlan0: invaild command id : 215
08-31 08:53:17.269  1019  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 08:53:17.269  1019  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,08-31 08:53:17.269  1019  1128 E WifiNative-wlan0: invaild command id : 215
08-31 08:53:17.269  1019  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 08:53:17.269  1019  1127 D WifiP2pService: P2pEnablingState
08-31 08:53:17.269  1019  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-31 08:53:17.279  8056  8056 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 08:53:17.279  1019  1127 D WifiP2pService: P2p socket connection successful
,08-31 08:53:17.279  8056  8056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 08:53:17.279  1019  1127 D WifiP2pService: P2pEnabledState
08-31 08:53:17.279  1019  1130 E ConnectivityService: updateNetworkInfo()
,08-31 08:53:17.279  1019  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 08:53:17.279  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 08:53:17.279  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 08:53:17.279  8056  8056 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-31 08:53:17.279  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:53:17.279  1019  1128 E WifiStateMachine: Failed to set frequency band 0
08-31 08:53:17.279  1019  1050 D WifiDisplayController: disconnect
,08-31 08:53:17.279  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:53:17.279  1019  1050 D WifiDisplayController: updateConnection
08-31 08:53:17.279  1019  1128 D SecContentProvider2: mCursor = null
08-31 08:53:17.279  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-31 08:53:17.279  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 08:53:17.279  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:53:17.279  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-31 08:53:17.279  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 08:53:17.279  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 08:53:17.279  1019  1127 D WifiNative-p2p0: p2pGetDeviceAddress
,08-31 08:53:17.279  1019  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-31 08:53:17.289  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 08:53:17.289  1019  4378 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 08:53:17.289  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 08:53:17.289  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 08:53:17.289  4872  4872 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:53:17.289  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:53:17.289  1019  1128 D SecContentProvider2: mCursor = null
,08-31 08:53:17.289  1019  1127 D WifiP2pService: DeviceAddress: 0a:75:42
08-31 08:53:17.289  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:53:17.289  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:53:17.289  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:53:17.289  1019  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  secondary type: null
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  wps: 0
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  grpcapab: 0
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  devcapab: 0
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  status: 3
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  wfdInfo: null
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  groupownerAddress: null
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  GOdeviceName: null
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  interfaceAddress: 
08-31 08:53:17.289  1019  1050 D WifiDisplayController:  SConnectInfo : null
08-31 08:53:17.289  4872  4872 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 08:53:17.289  4872  4917 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:53:17.299  7902  7902 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:53:17.299  7902  7902 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 08:53:17.299  7902  7902 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 08:53:17.309  1019  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 08:53:17.309  1019  1127 D WifiP2pService: InactiveState
,08-31 08:53:17.309  1019  1127 D WifiP2pService: InactiveState{ what=143376 }
08-31 08:53:17.309  7533  7533 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-31 08:53:17.309  1019  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 08:53:17.309  8056  8056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 08:53:17.309  1019  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-31 08:53:17.309  1019  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 08:53:17.389  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
,08-31 08:53:17.389  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:53:17.389  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 08:53:18.049  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:53:18.049  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:18.049  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:18.049  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:53:18.049  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:53:18.049  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:18.049  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:18.049  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:18.059  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:18.059  7379  7432 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 08:53:18.069  7379  7432 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 08:53:18.069  7379  7432 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@34efc850 Bundle[{}]
,08-31 08:53:18.069  7379  7432 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 08:53:18.069  7379  7432 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-31 08:53:18.069  7379  7432 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 08:53:18.069  7379  7432 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 08:53:18.069  7379  7432 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-31 08:53:18.069  7379  7432 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 08:53:18.079  7379  7432 I System.out: Running OutgoingSocketThread
,08-31 08:53:18.079  7379  8065 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1500)
,08-31 08:53:18.079  7379  8065 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48672
,08-31 08:53:18.079  7379  8065 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 08:53:18.429   289   289 E SMD     : DCD OFF,
,08-31 08:53:18.469  8056  8056 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
08-31 08:53:18.469  8056  8056 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 08:53:18.469  8056  8056 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-31 08:53:18.469  8056  8056 I wpa_supplicant: Trying to associate with  'G700'
08-31 08:53:18.469  8056  8056 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-31 08:53:18.469  8056  8056 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-31 08:53:18.469  1019  8062 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 08:53:18.489  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 08:53:18.489  1019  1128 D SecContentProvider2: mCursor = null
,08-31 08:53:18.579  8056  8056 E wpa_supplicant: Cmd 35605 not handled
08-31 08:53:18.579  8056  8056 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 08:53:18.589  8056  8056 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 08:53:18.589  8056  8056 I wpa_supplicant: Associated with F4.99.3E
,08-31 08:53:18.589  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 08:53:18.589  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:53:18.589  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 08:53:18.589  8056  8056 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 08:53:18.589  8056  8056 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 08:53:18.589  8056  8056 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-31 08:53:18.589  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:53:18.589  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:53:18.589  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:53:18.589  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 08:53:18.589  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 08:53:18.589  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
,08-31 08:53:18.589  1019  1133 E Tethering: No numeric data
,08-31 08:53:18.589  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 08:53:18.599  1019  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:53:18.589  1019  1133 D Tethering: clearTetheredNotification()
08-31 08:53:18.599  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 08:53:18.599  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:18.599  1182  1182 D HotspotTile: updateTetherState():false, false
08-31 08:53:18.599  8056  8056 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 08:53:18.599  8056  8056 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-31 08:53:18.599  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:18.599  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:53:18.599  8056  8056 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-31 08:53:18.599  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:53:18.599  1019  1128 D SecContentProvider2: mCursor = null
08-31 08:53:18.599  8056  8056 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 08:53:18.599  8056  8056 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 08:53:18.599  8056  8056 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
08-31 08:53:18.599  8056  8056 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-31 08:53:18.609  8056  8056 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 08:53:18.609  8056  8056 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-31 08:53:18.609  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 08:53:18.609  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
08-31 08:53:18.609  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 08:53:18.609  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:53:18.609  1019  1125 V NetworkStats: performPollLocked() took 13ms
08-31 08:53:18.609  1019  1128 D SecContentProvider2: mCursor = null
08-31 08:53:18.609  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:18.609  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:18.609  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:18.619  1019  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 08:53:18.619  1019  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 08:53:18.629  1019  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 08:53:18.629  1019  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 08:53:18.629  1019  1130 E ConnectivityService: updateNetworkInfo()
,08-31 08:53:18.629  1019  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 08:53:18.629  1019  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:53:18.639  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-31 08:53:18.639  1019  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:53:18.639  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:18.639  1019  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:53:18.639  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:53:18.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:18.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:18.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:18.639  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:18.639  1019  1506 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:18.639  1019  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:53:18.639  1019  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:53:18.639  1638  1638 I Hs20UtilService: Starting #21
08-31 08:53:18.639  1638  1695 I Hs20UtilService: Message received 5007
08-31 08:53:18.649  1019  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 08:53:18.649  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 08:53:18.649  4872  4872 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
,08-31 08:53:18.649  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:53:18.659  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-31 08:53:18.659  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:53:18.659   279   979 D CommandListener: Setting iface cfg
,08-31 08:53:18.659  4872  4872 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 08:53:18.659  4872  4917 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:53:18.669  1019  1128 E WifiStateMachine: Start Dhcp Watchdog 3
,08-31 08:53:18.669  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-31 08:53:18.669  1019  1128 D SecContentProvider2: mCursor = null
,08-31 08:53:18.679  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-31 08:53:18.679  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:53:18.679  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:53:18.679  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:18.679  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:18.679  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:18.679  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:18.689  1019  1128 E WifiNative-wlan0: do suspend false
,08-31 08:53:18.689  1019  1127 D WifiP2pService: InactiveState{ what=143375 },
,08-31 08:53:18.689  1019  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:53:18.689  1019  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
08-31 08:53:18.689  1019  1128 D SecContentProvider2: mCursor = null
,08-31 08:53:18.909  8068  8068 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 08:53:18.909  8068  8068 I dhcpcd  : version 5.5.6 starting
,08-31 08:53:18.919  8068  8068 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 08:53:18.969  8068  8068 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-31 08:53:18.969  8068  8068 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 08:53:18.969  8068  8068 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-31 08:53:18.969  8068  8068 I dhcpcd  : bssid match
08-31 08:53:18.969  8068  8068 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-31 08:53:19.029  8068  8068 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-31 08:53:19.079  7379  7432 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1501)
08-31 08:53:19.079  7379  7432 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1501)
08-31 08:53:19.089  7379  7432 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1506)
,08-31 08:53:19.089  7379  7432 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 08:53:19.089  7379  7432 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1507)
08-31 08:53:19.089  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:53:19.089  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@183c42b0 added. We now have 2 listener(s)
,08-31 08:53:19.089  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 08:53:19.089  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:53:19.089  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:53:19.089  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:53:19.099  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@321a3529 added. We now have 9 listener(s)
08-31 08:53:19.099  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:53:19.099  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 08:53:19.099  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:53:19.099  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:53:19.099  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:19.099  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:19.099  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:53:19.099  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:53:19.099  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:19.099  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:19.099  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:53:19.109  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:53:19.109  7379  7432 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:53:19.109  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:53:19.109  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:53:19.109  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:53:19.109  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a888e4f added. We now have 3 listener(s)
08-31 08:53:19.119  8068  8068 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
08-31 08:53:19.119  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 08:53:19.119  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:53:19.119  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:53:19.119  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:53:19.119  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79ad9dc added. We now have 10 listener(s)
08-31 08:53:19.119  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:53:19.119  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:53:19.119  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:53:19.119  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:53:19.119  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:53:19.119  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.119  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:53:19.119  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:53:19.119  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@183c42b0 removed from the list
08-31 08:53:19.119  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.119  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@321a3529 removed from the list
08-31 08:53:19.119  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:53:19.119  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:53:19.119  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.119  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:53:19.119  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:53:19.119  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:53:19.119  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.119  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@321a3529 not in the list
08-31 08:53:19.119  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.119  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:53:19.129  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:53:19.129  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:53:19.129  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.129  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79ad9dc removed from the list
08-31 08:53:19.129  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:53:19.129  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.129  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:53:19.129  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:53:19.129  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a888e4f removed from the list
08-31 08:53:19.129  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:53:19.129  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@777fae5 added. We now have 2 listener(s)
08-31 08:53:19.139  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 08:53:19.139  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:53:19.139  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:53:19.139  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:53:19.139  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea5c9ba added. We now have 9 listener(s)
08-31 08:53:19.139  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:53:19.139  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 08:53:19.139  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:53:19.149  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:53:19.149  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:19.149  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:19.149  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:53:19.149  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:53:19.149  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:19.149  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:19.149  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:53:19.149  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:53:19.149  7379  7432 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:53:19.159  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:53:19.159  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce9b7c8 added. We now have 3 listener(s)
08-31 08:53:19.159  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:53:19.159  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 08:53:19.159  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:53:19.159  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:53:19.159  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:53:19.159  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22326061 added. We now have 10 listener(s)
08-31 08:53:19.159  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:53:19.159  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:53:19.159  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:53:19.159  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:53:19.159  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:53:19.159  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 08:53:19.169  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:53:19.169  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:53:19.169  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 08:53:19.169  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:53:19.179  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:53:19.179  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:53:19.179  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:53:19.179  3200  3219 D BtGatt.GattService: registerClient() - UUID=39eeb842-0f25-43bd-bb8d-f6d24116a829,
,08-31 08:53:19.219  3200  3278 D BtGatt.GattService: onClientRegistered() - UUID=39eeb842-0f25-43bd-bb8d-f6d24116a829, clientIf=6,
,08-31 08:53:19.229  7379  7548 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 08:53:19.229  3200  3211 D BtGatt.GattService: start scan with filters,
08-31 08:53:19.229  3200  3357 D BtGatt.ScanManager: handling starting scan
08-31 08:53:19.229  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 08:53:19.229  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:53:19.229  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:53:19.229  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 08:53:19.239  3200  3278 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-31 08:53:19.239  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:53:19.239  3200  3357 D BtGatt.ScanManager: allow scan with filters
08-31 08:53:19.239  3200  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 08:53:19.239  3200  3357 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
08-31 08:53:19.239  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 08:53:19.239  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:53:19.239  3200  3357 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:53:19.239  3200  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 08:53:19.239  3200  3278 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-31 08:53:19.239  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:53:19.239  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:53:19.239  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 08:53:19.249  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:53:19.249  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:53:19.249  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 08:53:19.249  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:53:19.249  7379  7432 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:53:19.249  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:53:19.249  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 08:53:19.249  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.249  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:53:19.249  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:53:19.249  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:53:19.249  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:53:19.249  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:53:19.249  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:53:19.249  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:53:19.249  3200  3355 D BtGatt.GattService: stopScan() - queue size =1
,08-31 08:53:19.249  3200  3354 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-31 08:53:19.259  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:53:19.259  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:53:19.259  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:53:19.259  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:53:19.259  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:53:19.259  3200  3357 D BtGatt.ScanManager: filter size is 1
08-31 08:53:19.259  3200  3357 D BtGatt.ScanManager: delete FilterIndex - 6
,08-31 08:53:19.259  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:53:19.259  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-31 08:53:19.259  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:53:19.259  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 08:53:19.259  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:53:19.259  3200  3357 D BtGatt.ScanManager: stopping BLe Batch
08-31 08:53:19.259  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:53:19.259  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:53:19.269  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:53:19.269  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:53:19.269  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:53:19.269  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 08:53:19.269  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:53:19.269  3200  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 08:53:19.269  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:53:19.269  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:53:19.269  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-31 08:53:19.269  3200  3278 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-31 08:53:19.269  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:53:19.269  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:53:19.269  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.269  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:53:19.269  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:53:19.269  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@777fae5 removed from the list
08-31 08:53:19.269  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.269  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea5c9ba removed from the list
,08-31 08:53:19.269  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:53:19.269  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:53:19.269  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.269  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:53:19.279  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:53:19.279  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:53:19.279  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.279  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea5c9ba not in the list
08-31 08:53:19.279  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.279  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:53:19.279  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 08:53:19.279  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:53:19.279  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.279  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22326061 removed from the list
08-31 08:53:19.279  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:53:19.279  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:53:19.279  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:53:19.279  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:53:19.279  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce9b7c8 removed from the list
,08-31 08:53:19.279  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:53:19.279  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d3a19d added. We now have 2 listener(s)
,08-31 08:53:19.279  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-31 08:53:19.279  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:53:19.279  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:53:19.279  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:53:19.279  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c7d612 added. We now have 9 listener(s)
,08-31 08:53:19.279  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:53:19.279  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:53:19.289  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:53:19.289  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:53:19.289  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:19.289  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:19.289  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:53:19.289  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:53:19.289  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:19.289  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:19.289  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:19.289  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-31 08:53:19.289  7379  7432 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:53:19.289  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:53:19.289  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dfdb7e0 added. We now have 3 listener(s)
,08-31 08:53:19.299  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
,08-31 08:53:19.299  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:53:19.299  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:53:19.299  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-31 08:53:19.299  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a4dba99 added. We now have 10 listener(s)
,08-31 08:53:19.299  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:53:19.299  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 08:53:19.299  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:53:19.299  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:53:19.299  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:53:19.299  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:53:19.299  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:53:19.299  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 08:53:19.299  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:19.309  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-31 08:53:19.309  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:53:19.309  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:53:19.319  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:53:19.319  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:53:19.319  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:53:19.329  3200  3211 D BtGatt.GattService: registerClient() - UUID=51da8e0c-2a6b-439f-b1ce-d77f6ac89e33
,08-31 08:53:19.369  3200  3278 D BtGatt.GattService: onClientRegistered() - UUID=51da8e0c-2a6b-439f-b1ce-d77f6ac89e33, clientIf=6
08-31 08:53:19.369  7379  7388 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-31 08:53:19.369  3200  3219 D BtGatt.GattService: start scan with filters
08-31 08:53:19.369  3200  3357 D BtGatt.ScanManager: handling starting scan
08-31 08:53:19.369  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 08:53:19.369  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:53:19.369  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-31 08:53:19.369  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 08:53:19.369  3200  3278 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-31 08:53:19.369  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:53:19.369  3200  3357 D BtGatt.ScanManager: allow scan with filters
08-31 08:53:19.369  3200  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 08:53:19.369  3200  3357 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6,
08-31 08:53:19.369  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 08:53:19.369  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:53:19.369  3200  3357 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:53:19.369  3200  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
08-31 08:53:19.369  3200  3278 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 08:53:19.369  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:53:19.369  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:53:19.369  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:53:19.369  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:53:19.379  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 08:53:19.379  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:53:19.379  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:53:19.379  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 08:53:19.379  7379  7432 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 08:53:19.379  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:53:19.379  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:53:19.379  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:53:19.389  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:53:19.389  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 08:53:19.389  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:53:19.389  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:53:19.389  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d3a19d removed from the list
08-31 08:53:19.389  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.389  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c7d612 removed from the list,
08-31 08:53:19.389  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:53:19.389  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:53:19.389  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.389  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-31 08:53:19.389  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.389  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:53:19.389  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:53:19.389  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:53:19.389  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.389  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c7d612 not in the list
08-31 08:53:19.389  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:53:19.389  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:53:19.389  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 08:53:19.389  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:53:19.389  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:53:19.389  3200  3354 D BtGatt.GattService: stopScan() - queue size =1
,08-31 08:53:19.389  3200  3357 D BtGatt.ScanManager: filter size is 1
,08-31 08:53:19.389  3200  3357 D BtGatt.ScanManager: delete FilterIndex - 7
,08-31 08:53:19.389  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-31 08:53:19.389  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:53:19.389  3200  3357 D BtGatt.ScanManager: stopping BLe Batch
08-31 08:53:19.389  3200  3211 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 08:53:19.389  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 08:53:19.389  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:53:19.389  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:53:19.389  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:53:19.389  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:53:19.399  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 08:53:19.399  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:53:19.399  3200  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 08:53:19.399  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:53:19.399  3200  3278 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-31 08:53:19.399  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:53:19.399  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 08:53:19.399  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:53:19.399  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 08:53:19.399  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:53:19.399  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-31 08:53:19.399  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:53:19.399  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:53:19.399  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:53:19.399  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:53:19.399  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.399  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a4dba99 removed from the list,
08-31 08:53:19.399  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:53:19.399  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.399  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-31 08:53:19.399  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:53:19.399  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dfdb7e0 removed from the list
08-31 08:53:19.399  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:53:19.399  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22b66755 added. We now have 2 listener(s)
,08-31 08:53:19.409  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-31 08:53:19.409  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:53:19.409  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:53:19.409  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:53:19.409  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be4156a added. We now have 9 listener(s)
08-31 08:53:19.409  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:53:19.409  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:53:19.409  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:53:19.409  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:53:19.409  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:19.409  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:19.409  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:53:19.409  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:53:19.409  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:19.409  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:19.409  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:19.419  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:19.419  7379  7432 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:53:19.419  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:53:19.419  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ea2f8 added. We now have 3 listener(s)
,08-31 08:53:19.419  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:19.419  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 08:53:19.419  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:53:19.419  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:53:19.419  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:53:19.419  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13c323d1 added. We now have 10 listener(s)
08-31 08:53:19.419  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:53:19.419  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:53:19.419  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:53:19.419  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:53:19.419  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:53:19.419  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:53:19.419  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:19.419  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:53:19.429  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:53:19.429  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:53:19.429  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:53:19.429  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 08:53:19.429  7379  7432 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:53:19.439  3200  3219 D BtGatt.GattService: registerClient() - UUID=49f9239d-e8f7-4ab1-b01a-edbcf50c92d0
,08-31 08:53:19.479  3200  3278 D BtGatt.GattService: onClientRegistered() - UUID=49f9239d-e8f7-4ab1-b01a-edbcf50c92d0, clientIf=6
,08-31 08:53:19.479  7379  7387 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 08:53:19.479  3200  3355 D BtGatt.GattService: start scan with filters
,08-31 08:53:19.479  3200  3357 D BtGatt.ScanManager: handling starting scan
,08-31 08:53:19.479  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:53:19.479  3200  3278 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 08:53:19.479  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:53:19.489  3200  3357 D BtGatt.ScanManager: allow scan with filters
08-31 08:53:19.489  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:53:19.489  3200  3357 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 08:53:19.489  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:53:19.489  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 08:53:19.489  3200  3357 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-31 08:53:19.489  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 08:53:19.489  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:53:19.489  3200  3357 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 08:53:19.489  3200  3357 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 08:53:19.489  3200  3278 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 08:53:19.489  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:53:19.489  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 08:53:19.499  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:53:19.499  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:53:19.499  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:53:19.499  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:53:19.499  1019  1128 E WifiNative-wlan0: do suspend true
,08-31 08:53:19.499  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:53:19.509  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:53:19.509  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:53:19.509  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:53:19.509  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:53:19.509  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:53:19.509  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:53:19.509  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 08:53:19.509  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22b66755 removed from the list
,08-31 08:53:19.509  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:53:19.509  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be4156a removed from the list
,08-31 08:53:19.509  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:53:19.509  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:53:19.509  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:53:19.509  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-31 08:53:19.509  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.519  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:53:19.519  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:53:19.519  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 08:53:19.519  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:53:19.519  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be4156a not in the list
,08-31 08:53:19.519  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:53:19.519  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:53:19.519  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:53:19.519  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:53:19.519  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:53:19.519  1019  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-31 08:53:19.519  3200  3370 D BtGatt.GattService: stopScan() - queue size =1
,08-31 08:53:19.519  3200  3357 D BtGatt.ScanManager: filter size is 1
08-31 08:53:19.519  3200  3357 D BtGatt.ScanManager: delete FilterIndex - 8
,08-31 08:53:19.519  1019  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 08:53:19.519  1019  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
08-31 08:53:19.519  1019  1128 E WifiStateMachine: VerifyingLinkState enter
,08-31 08:53:19.529  3200  3278 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 08:53:19.529  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:53:19.529  3200  3357 D BtGatt.ScanManager: stopping BLe Batch
,08-31 08:53:19.529  3200  3354 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 08:53:19.529  1019  1130 E ConnectivityService: updateNetworkInfo()
,08-31 08:53:19.529  3200  3278 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 08:53:19.529  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:53:19.529  3200  3357 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 08:53:19.529  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:53:19.529  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:53:19.529  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:53:19.529  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:53:19.529  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:53:19.529  1019  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-31 08:53:19.529  1019  1130 D ConnectivityService: Adding iface wlan0 to network 504
,08-31 08:53:19.529  3200  3278 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 08:53:19.529  3200  3278 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:53:19.539  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:53:19.539  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 08:53:19.539  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:19.539  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 08:53:19.539  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.539  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-31 08:53:19.539  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.539  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.549  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 08:53:19.549  7379  7432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:53:19.549  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 08:53:19.549  1019  1147 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-31 08:53:19.549  1019  1147 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 08:53:19.549  1019  1147 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 08:53:19.549  1019  1147 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 08:53:19.549  1019  1147 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 08:53:19.549  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:53:19.559  1019  4378 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:53:19.559  1019  4378 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:53:19.559  1019  4378 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:19.559  1019  4378 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:19.559  1019  4378 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:53:19.559  1638  1638 I Hs20UtilService: Starting #22
08-31 08:53:19.559  1019  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-31 08:53:19.559  1638  1695 I Hs20UtilService: Message received 5007
08-31 08:53:19.559  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:53:19.559  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:19.559  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:53:19.559  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.569  1019  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-31 08:53:19.559  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.559  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.559  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.569  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 08:53:19.569  1019  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-31 08:53:19.569  4872  4872 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 08:53:19.569  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:53:19.569  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:53:19.569  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.569  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13c323d1 removed from the list
08-31 08:53:19.569  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:53:19.569  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.569  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:53:19.569  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:53:19.569  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5ea2f8 removed from the list
08-31 08:53:19.569  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:53:19.569  7379  7379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:53:19.569  7379  7379 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:53:19.569  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:53:19.569  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a052c0d added. We now have 2 listener(s)
08-31 08:53:19.569  1019  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-31 08:53:19.569  1019  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 08:53:19.569  1019  1130 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,08-31 08:53:19.569  1019  1130 D ConnectivityService: LTETest block dns file not exists
,08-31 08:53:19.569  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 08:53:19.569  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:53:19.569  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:53:19.569  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:53:19.569  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ade7c2 added. We now have 9 listener(s)
08-31 08:53:19.569  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:53:19.569  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:53:19.579  1019  1130 V NetworkStats: updateIfacesLocked()
08-31 08:53:19.579  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.579  1019  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-31 08:53:19.579  1019  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:19.579  1019  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:53:19.589  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:53:19.589  1019  1130 V NetworkStats: performPollLocked() took 3ms
08-31 08:53:19.589  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:19.589  7379  7432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:53:19.589  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:53:19.589  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:53:19.589  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:53:19.589  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:53:19.589  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:53:19.589  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:53:19.589  7379  7432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:53:19.589  7379  7432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:53:19.589  7379  7432 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:53:19.589  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 08:53:19.589  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b5ed910 added. We now have 3 listener(s)
,08-31 08:53:19.599  1019  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 08:53:19.599  1019  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 08:53:19.599  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 08:53:19.609  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 08:53:19.609  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:19.609  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:19.609  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 08:53:19.609  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 08:53:19.609  1019  1019 I WifiTrafficPoller: mBoosterFLAG : 0
08-31 08:53:19.609  1019  1019 I WifiTrafficPoller: current booster mode : FullMode
,08-31 08:53:19.609  7379  7379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:53:19.609  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.609  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.609  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.609  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:19.619  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:19.619  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 08:53:19.619  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:19.619  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:19.619  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.619  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:53:19.619  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-31 08:53:19.619  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:53:19.619  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 08:53:19.619  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:53:19.619  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe57c09 added. We now have 10 listener(s)
08-31 08:53:19.619  7379  7432 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:53:19.619  7379  7432 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:53:19.619  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:53:19.619  7379  7432 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:53:19.629  1019  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-31 08:53:19.629  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:53:19.629  1019  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:53:19.629  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.629  1019  1130 V NetworkStats: updateIfacesLocked()
08-31 08:53:19.629  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:53:19.629  1019  1130 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:53:19.629  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:53:19.629  1019  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:53:19.629  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a052c0d removed from the list
08-31 08:53:19.629  1019  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:53:19.629  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.629  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ade7c2 removed from the list
08-31 08:53:19.629  7379  7432 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:53:19.629  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:53:19.629  1019  1130 E ConnectivityService: updateNetworkInfo()
08-31 08:53:19.629  1019  1130 E ConnectivityService: updateNetworkInfo()
08-31 08:53:19.629  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.629  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:53:19.629  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.629  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.629  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.629  1019  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:19.629  1019  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:53:19.629  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:53:19.629  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:53:19.629  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.629  7379  7432 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ade7c2 not in the list
08-31 08:53:19.629  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.629  1019  1130 V NetworkStats: performPollLocked() took 3ms
08-31 08:53:19.629  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:53:19.629  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:53:19.629  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:53:19.629  7379  7432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:53:19.629  7379  7432 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe57c09 removed from the list
08-31 08:53:19.629  7379  7432 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:53:19.629  7379  7432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:53:19.629  7379  7432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:53:19.629  7379  7432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:53:19.629  7379  7432 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b5ed910 removed from the list
08-31 08:53:19.629  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.629  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 08:53:19.629  1019  1495 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:19.629  1019  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:19.629  1019  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 08:53:19.629  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 08:53:19.629  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 08:53:19.629  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:53:19.629  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 08:53:19.629  7379  7432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
,08-31 08:53:19.629  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.629  1019  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-31 08:53:19.629  1019  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-31 08:53:19.629  1638  1638 I Hs20UtilService: Starting #23
08-31 08:53:19.629  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.629  1019  8066 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:53:19.639  1019  8066 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-31 08:53:19.639  1019  8066 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:53:19.639  1019  8066 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-31 08:53:19.639  1638  1695 I Hs20UtilService: Message received 5007
08-31 08:53:19.639  1019  8066 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 08:53:19.639  1019  1130 D ConnectivityService:    accepting network in place of null
,08-31 08:53:19.639  1019  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 08:53:19.639  1019  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-31 08:53:19.639  1019  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 08:53:19.639  1019  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-31 08:53:19.639  1019  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 08:53:19.639  7379  8105 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1514, name: My test thread name)
08-31 08:53:19.639   279   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:53:19.639   279   975 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-31 08:53:19.639  1019  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-31 08:53:19.649  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-31 08:53:19.649  1019  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-31 08:53:19.649  1460  1460 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 08:53:19.649  7379  8105 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1514, thread name: My test thread name)
08-31 08:53:19.649  1460  1460 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:53:19.649  7379  8105 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1514, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 08:53:19.649  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 08:53:19.649  4872  4872 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:53:19.649  1019  1133 D Tethering: MasterInitialState.processMessage what=3
,08-31 08:53:19.649  1019  1125 V NetworkStats: updateIfacesLocked()
08-31 08:53:19.649  1182  1727 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 08:53:19.649  1019  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-31 08:53:19.649  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-31 08:53:19.649  1019  1125 V NetworkStats: performPollLocked() took 3ms
08-31 08:53:19.649  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.649  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:19.649  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:53:19.649  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 08:53:19.649  4872  4872 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-31 08:53:19.649  4872  4872 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 08:53:19.649  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.649  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
08-31 08:53:19.649  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 08:53:19.649  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 08:53:19.649  1182  1182 D StatusBar.NetworkController: updateDataNetType()
08-31 08:53:19.659  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.659  7379  8107 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1516, name: My test thread name)
08-31 08:53:19.659  1019  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-31 08:53:19.659  7379  8107 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1516, thread name: My test thread name)
08-31 08:53:19.659  7379  8107 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1516, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 08:53:19.659  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.659  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.659  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.659  7379  7432 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 08:53:19.659  7379  7432 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 08:53:19.659  7379  7432 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 08:53:19.659  7379  7432 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 08:53:19.659  7379  7432 D com.test.thalitest.ThaliTestRunner: Total duration: 23357 ms
08-31 08:53:19.659  7379  7432 I jxcore-log: *Native tests were executed*
08-31 08:53:19.659  7379  7432 I jxcore-log: 
08-31 08:53:19.659  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 08:53:19.659  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-31 08:53:19.659  7379  7432 I jxcore-log: Total number of executed tests:  80
08-31 08:53:19.659  7379  7432 I jxcore-log: 
08-31 08:53:19.659  7379  7432 I jxcore-log: Number of passed tests:  80
08-31 08:53:19.659  7379  7432 I jxcore-log: 
08-31 08:53:19.659  7379  7432 I jxcore-log: Number of failed tests:  0
08-31 08:53:19.659  7379  7432 I jxcore-log: 
08-31 08:53:19.659  7379  7432 I jxcore-log: Number of ignored tests:  0
08-31 08:53:19.659  7379  7432 I jxcore-log: 
08-31 08:53:19.659  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 08:53:19.659  7379  7432 I jxcore-log: Total duration:  23357
08-31 08:53:19.659  7379  7432 I jxcore-log: 
08-31 08:53:19.659  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 16 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-31 08:53:19.659  7379  7432 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 08:53:19.659  7379  7432 I jxcore-log: 
08-31 08:53:19.659  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-31 08:53:19.659  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-31 08:53:19.659  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:53:19.659  1182  1182 D STATUSBAR-WifiQuickSetting,Button: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 08:53:19.659  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.659  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.659  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.659  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:53:19.659  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.659  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:19.659  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:53:19.659  7379  7432 I jxcore-log: 
08-31 08:53:19.669  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:53:19.669  7379  7432 I jxcore-log: 
08-31 08:53:19.669  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:53:19.669  7379  7432 I jxcore-log: 
08-31 08:53:19.669  1019  3871 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:53:19.669  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:53:19.669  7379  7432 I jxcore-log: 
08-31 08:53:19.669  1019  3871 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:53:19.669  1019  3871 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:19.669  1019  3871 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:53:19.669  1019  3871 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 08:53:19.669  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:53:19.669  7379  7432 I jxcore-log: 
08-31 08:53:19.669  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:53:19.669  7379  7432 I jxcore-log: 
08-31 08:53:19.669  4872  4872 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 08:53:19.669  4872  4872 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 08:53:19.669  1638  1638 I Hs20UtilService: Starting #24
08-31 08:53:19.679  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:53:19.679  7379  7432 I jxcore-log: 
08-31 08:53:19.679  1638  1695 I Hs20UtilService: Message received 5007
08-31 08:53:19.679  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:53:19.679  7379  7432 I jxcore-log: 
08-31 08:53:19.679  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:53:19.679  7379  7432 I jxcore-log: 
08-31 08:53:19.679  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:53:19.679  7379  7432 I jxcore-log: 
,08-31 08:53:19.679  7379  7379 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 08:53:19.679  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:53:19.679  7379  7432 I jxcore-log: 
,08-31 08:53:19.679  1019  1265 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
08-31 08:53:19.679  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 08:53:19.679  7379  7432 I jxcore-log: 
08-31 08:53:19.679  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 08:53:19.679  7379  7432 I jxcore-log: 
,08-31 08:53:19.679  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-31 08:53:19.679  7379  7432 I jxcore-log: 
08-31 08:53:19.679  1019  1484 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-31 08:53:19.679  1019  1484 D SecContentProvider2: mCursor = null
08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
,08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
08-31 08:53:19.689  1019  1031 D SecContentProvider2: uri = 15 selection = getToastGravity
08-31 08:53:19.689  1019  1031 D SecContentProvider2: mCursor = null
08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
,08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
08-31 08:53:19.689  1019  1385 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-31 08:53:19.689  1019  1385 D SecContentProvider2: mCursor = null
,08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
,08-31 08:53:19.689  1019  1495 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-31 08:53:19.689  1019  1495 D SecContentProvider2: mCursor = null
08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
,08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
,08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
08-31 08:53:19.689  1019  4381 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-31 08:53:19.689  1019  4381 D SecContentProvider2: mCursor = null
08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-31 08:53:19.689  7379  7432 I jxcore-log: 
,08-31 08:53:19.689  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:53:19.689  7379  7432 I jxcore-log: 
,08-31 08:53:19.689  1019  1471 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-31 08:53:19.689  1019  1471 D SecContentProvider2: mCursor = null
,08-31 08:53:19.719   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-31 08:53:19.729  1019  1138 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,08-31 08:53:19.739  1182  1182 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,08-31 08:53:19.769  7379  7379 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-31 08:53:19.769  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:53:19.769  7379  7432 I jxcore-log: 
,08-31 08:53:19.899  7379  7379 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-31 08:53:19.899  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:53:19.899  7379  7432 I jxcore-log: 
,08-31 08:53:19.929  8108  8108 D AndroidRuntime: ,
08-31 08:53:19.929  8108  8108 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 08:53:19.929  8108  8108 D AndroidRuntime: CheckJNI is OFF,
08-31 08:53:19.929  8108  8108 D AndroidRuntime: readGMSProperty: start,
08-31 08:53:19.929  8108  8108 D AndroidRuntime: readGMSProperty: already setted!!
08-31 08:53:19.929  8108  8108 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 08:53:19.929  8108  8108 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 08:53:19.929  8108  8108 D AndroidRuntime: readGMSProperty: end
08-31 08:53:19.929  8108  8108 D AndroidRuntime: addProductProperty: start
,08-31 08:53:20.069  7379  7379 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-31 08:53:20.069  7379  7432 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:53:20.069  7379  7432 I jxcore-log: ,
,08-31 08:53:20.069  8108  8108 E AffinityControl: AffinityControl: registerfunction enter
,08-31 08:53:20.099  8108  8108 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 08:53:20.119  1019  1495 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-31 08:53:20.119  1019  1495 D PackageManager: START PACKAGE DELETE: observer{1016652822}
08-31 08:53:20.119  1019  1495 D PackageManager: pkg{<packageName>}
08-31 08:53:20.119  1019  1495 D PackageManager: user{0}
08-31 08:53:20.119  1019  1495 D PackageManager: caller{2000}
08-31 08:53:20.119  1019  1495 D PackageManager: flags{2}
08-31 08:53:20.119  1019  1495 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-31 08:53:20.119  1019  1495 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-31 08:53:20.119  1019  1495 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
08-31 08:53:20.119  1019  1495 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 08:53:20.119  1019  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-31 08:53:20.119  1019  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-31 08:53:20.119  1019  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 08:53:20.119  1019  1060 D ApplicationPolicy: getApplicationUninstallationEnabled
08-31 08:53:20.119  1019  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 08:53:20.129  1019  1060 D PackageManager: !@killApplicatoin: 10170, uninstall pkg,
,08-31 08:53:20.129  1019  1045 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg,
,08-31 08:53:20.129  1019  1045 I ActivityManager: Killing 7379:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg,
,08-31 08:53:20.139  1019  1045 I ActivityManager:   Force finishing activity ActivityRecord{25383d10 u0 com.test.thalitest/.MainActivity t164}
,08-31 08:53:20.139  1019  1045 D InputDispatcher: Focus left window: 7379
,08-31 08:53:20.139   258  1041 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-31 08:53:20.149  1019  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 08:53:20.139   258   447 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
08-31 08:53:20.139  1019  1045 D InputDispatcher: Focused application released
08-31 08:53:20.149  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 08:53:20.149  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 08:53:20.259  1019  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:53:20.309  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast,
,08-31 08:53:20.309  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:20.309  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:20.309  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:20.309  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:20.329  1019  1045 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8119 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 08:53:20.329  8119  8119 E Zygote  : MountEmulatedStorage()
08-31 08:53:20.329  8119  8119 E Zygote  : v2
08-31 08:53:20.329  8119  8119 I libpersona: KNOX_SDCARD checking this for 1000
08-31 08:53:20.329  8119  8119 I libpersona: KNOX_SDCARD not a persona
,08-31 08:53:20.329  8119  8119 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 08:53:20.329  1019  1060 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-31 08:53:20.339  8119  8119 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:53:20.339  1019  1060 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-31 08:53:20.349  8119  8119 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:53:20.369  8119  8119 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:53:20.369  8119  8119 D ActivityThread: Added TimaKeyStore provider
,08-31 08:53:20.379  2861  2861 I art     : Explicit concurrent mark sweep GC freed 18124(1055KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 778us total 33.153ms
,08-31 08:53:20.389  1880  1880 E SamsungIME: mOCRHelper is null
08-31 08:53:20.389  1743  1948 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 08:53:20.399  1019  4377 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-31 08:53:20.399  1019  4377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-31 08:53:20.409  1019  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 08:53:20.409  1019  4377 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:20.409  1019  4377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:20.409  1019  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 08:53:20.429  1444  1444 D PersonaManager: isKioskContainerExistOnDevice
,08-31 08:53:20.439  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,08-31 08:53:20.439  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 08:53:20.439  1019  1125 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-31 08:53:20.439  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:20.439  1019  1125 V NetworkStats: performPollLocked(flags=0x3)
,08-31 08:53:20.439  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 08:53:20.439  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-31 08:53:20.439  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-31 08:53:20.439  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:53:20.439  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:53:20.449  1019  1125 V NetworkStats: performPollLocked() took 6ms
,08-31 08:53:20.449  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:20.469  1444  1444 D RegisteredServicesCache: empty dynamic service
,08-31 08:53:20.479  1019  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
08-31 08:53:20.479  1019  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-31 08:53:20.489  1019  1044 W TextServicesManagerService: no available spell checker services found
,08-31 08:53:20.489  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 08:53:20.489  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-31 08:53:20.489  1019  1495 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-31 08:53:20.499  1019  1495 D SecContentProvider2: mCursor = null
,08-31 08:53:20.509  1444  1444 D RegisteredComponentCache: Collect Tech packages for Knox
,08-31 08:53:20.509  1444  1444 D PersonaManager: isKioskContainerExistOnDevice
,08-31 08:53:20.509  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:53:20.519  8119  8119 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-31 08:53:20.519  8119  8119 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 08:53:20.519  8119  8119 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 08:53:20.529  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:53:20.539  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:53:20.539  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:53:20.539  8119  8119 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-31 08:53:20.539  8119  8119 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-31 08:53:20.539  8119  8119 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 08:53:20.539  8119  8119 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:53:20.549  1019  4381 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-31 08:53:20.549  1019  4381 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-31 08:53:20.549  1019  4381 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-31 08:53:20.549  1019  4381 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-31 08:53:20.549  1019  4381 I ActivityManager: Killing 7607:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-31 08:53:20.579  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:53:20.579  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:53:20.589  1019  4380 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-31 08:53:20.589  1019  4380 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,08-31 08:53:20.589  1019  4380 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:20.589  1019  4380 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:20.589  1019  4380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 08:53:20.639  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-31 08:53:20.639  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-31 08:53:20.639  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:20.639  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 08:53:20.639  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 08:53:20.649  1019  1130 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-31 08:53:20.659  1019  1060 I art     : Explicit concurrent mark sweep GC freed 68033(4MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 2.997ms total 230.404ms
,08-31 08:53:20.679  1657  8137 I VacuumService: Vacuum at: now=1472626400673 tag=VacuumService
,08-31 08:53:20.679  1019  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-31 08:53:20.679  1019  1265 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:53:20.679  1019  1265 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:20.689  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:53:20.689  1019  1265 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 08:53:20.689  1019  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,08-31 08:53:20.699  1019  3368 D SSRM:n  : SIOP:: AP = 300
,08-31 08:53:20.729  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:53:20.729  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-31 08:53:20.729  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 08:53:20.739  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:53:20.739  1019  1060 D PackageManager: delete codoeFile: 
,08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
,08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 08:53:20.739  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 08:53:20.739  1019  3368 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-31 08:53:20.739  1019  1164 D TaskPersister: removeObsoleteFile: deleting file=164_task.xml
08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 08:53:20.739  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-31 08:53:20.749  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 08:53:20.749  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 08:53:20.749  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 08:53:20.749  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 08:53:20.749  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 08:53:20.749  1019  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 08:53:20.749  1019  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:53:20.749  1019  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 08:53:20.749  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:53:20.749  1019  1019 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-31 08:53:20.749  1019  1060 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-31 08:53:20.749  1019  1060 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-31 08:53:20.759  1019  1060 D PackageManager: result of delete: 1{1016652822}
,08-31 08:53:20.759  1019  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:53:20.759  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:20.759  1019  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:20.759  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 08:53:20.759  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:53:20.769  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:53:20.769  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:53:20.769  8108  8108 D AndroidRuntime: Shutting down VM
08-31 08:53:20.769  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 08:53:20.769  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:53:20.779  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:53:20.779  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 08:53:20.779  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:53:20.779  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 08:53:20.779  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:53:20.779  1019  1044 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-31 08:53:20.789  1019  1044 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-31 08:53:20.829  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 08:53:20.829  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:20.829  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:20.829  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:20.829  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:20.839  8141  8141 E Zygote  : MountEmulatedStorage(),
,08-31 08:53:20.839  8141  8141 I libpersona: KNOX_SDCARD checking this for 10001,
,08-31 08:53:20.839  8141  8141 E Zygote  : v2
08-31 08:53:20.839  8141  8141 I libpersona: KNOX_SDCARD not a persona
08-31 08:53:20.839  8141  8141 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:53:20.839  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=8141 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 08:53:20.849  8141  8141 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:53:20.849  8141  8141 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:53:20.849  1019  1265 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:53:20.859  1019  1265 W ActivityManager: userId = 0, bbcId = -10000,
08-31 08:53:20.859  1019  1265 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 08:53:20.859  1019  1265 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 08:53:20.859  1019  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:53:20.859  1019  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:20.859  1019  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:20.859  1019  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 08:53:20.869  8141  8141 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:53:20.869  8141  8141 D ActivityThread: Added TimaKeyStore provider
,08-31 08:53:20.909  1657  8138 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-31 08:53:20.909  1657  8138 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 08:53:20.909  1019  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:53:20.919  1019  1471 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:20.919  1019  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:20.919  1019  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 08:53:20.929  7624  7624 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:53:20.929  7624  7624 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 08:53:20.929  7624  7624 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-31 08:53:20.929  7624  7624 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-31 08:53:20.969  1657  8138 W Uploader:  no longer exists, so no auth token.
,08-31 08:53:20.969  1019  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:53:20.969  1019  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:20.969  1019  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:20.969  1019  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 08:53:20.979  8108  8108 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 08:53:20.989  1019  1138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:53:20.989  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:20.989  1019  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:20.989  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 08:53:20.999  1019  1060 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 08:53:20.999  1019  1060 D PackageManager: userId{-1}
08-31 08:53:20.999  1019  1060 D PackageManager: andCode{true}
,08-31 08:53:20.999  1019  4381 D ActivityManager: bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
08-31 08:53:20.999  1019  4381 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-31 08:53:20.999  1019  4381 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:53:20.999  1019  4381 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:20.999  1019  4381 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 08:53:20.999  1019  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-31 08:53:21.009  1019  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:21.009  1019  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:21.009  1019  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:53:21.009  1019  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:53:21.019  8161  8161 E Zygote  : MountEmulatedStorage()
,08-31 08:53:21.019  8161  8161 E Zygote  : v2
08-31 08:53:21.019  8161  8161 I libpersona: KNOX_SDCARD checking this for 10003
08-31 08:53:21.019  8161  8161 I libpersona: KNOX_SDCARD not a persona
,08-31 08:53:21.019  8161  8161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:53:21.019  1019  1060 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8161 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 08:53:21.029  8161  8161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:53:21.029  8161  8161 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:53:21.039  1657  8138 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-31 08:53:21.039  1657  8138 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 08:53:21.049  1657  8138 I System.out: (HTTPLog)-Static: isShipBuild true
,08-31 08:53:21.049  1657  8138 I System.out: (HTTPLog)-Thread-212-459655822: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-31 08:53:21.049  1657  8138 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 08:53:21.049   279   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:53:21.049   279   975 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-31 08:53:21.069  8161  8161 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:53:21.069  8161  8161 D ActivityThread: Added TimaKeyStore provider
,08-31 08:53:21.109  7640  7640 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-31 08:53:21.119  1019  1138 I ActivityManager: Killing 7659:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-31 08:53:21.119  7640  7640 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-31 08:53:21.129  7640  7640 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild,
,08-31 08:53:21.129  7640  7640 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-31 08:53:21.159  1019  1471 I ActivityManager: Killing 7675:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-31 08:53:21.159  1019  4381 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-31 08:53:21.159  1019  4381 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 08:53:21.159  1019  4381 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:53:21.159  1019  4381 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:53:21.159  1019  4381 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms

```
