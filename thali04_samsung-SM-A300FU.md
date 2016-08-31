#### Test 82894682929afb6_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
08-31 08:51:30.605   291   291 E SMD     : DCD OFF
,08-31 08:51:30.885  6710  6710 D AndroidRuntime: 
08-31 08:51:30.885  6710  6710 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 08:51:30.895  6710  6710 D AndroidRuntime: CheckJNI is OFF
08-31 08:51:30.895  6710  6710 D AndroidRuntime: readGMSProperty: start
08-31 08:51:30.895  6710  6710 D AndroidRuntime: readGMSProperty: already setted!!
08-31 08:51:30.895  6710  6710 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 08:51:30.895  6710  6710 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 08:51:30.895  6710  6710 D AndroidRuntime: readGMSProperty: end
08-31 08:51:30.895  6710  6710 D AndroidRuntime: addProductProperty: start
08-31 08:51:31.045  6710  6710 E AffinityControl: AffinityControl: registerfunction enter
08-31 08:51:31.065  6710  6710 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 08:51:31.085  1017  1030 E PersonaManagerService: inState():  stateMachine is null !!
08-31 08:51:31.085  1017  1030 I PersonaManagerService: PersonaId don't exist
08-31 08:51:31.085  1017  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 08:51:31.085  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-31 08:51:31.105  1017  1030 W ActivityManager: mDVFSHelper.acquire()
08-31 08:51:31.105   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-31 08:51:31.105   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-31 08:51:31.115  1017  1030 D FocusedStackFrame: Set to : 0
08-31 08:51:31.125  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 08:51:31.125  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-31 08:51:31.125  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:31.125  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:31.125  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:31.125  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:31.135  6721  6721 E Zygote  : MountEmulatedStorage()
08-31 08:51:31.135  6721  6721 E Zygote  : v2
08-31 08:51:31.135  6721  6721 I libpersona: KNOX_SDCARD checking this for 10171
08-31 08:51:31.135  6721  6721 I libpersona: KNOX_SDCARD not a persona
08-31 08:51:31.135  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 08:51:31.135  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 08:51:31.145   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-31 08:51:31.145  6721  6721 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:51:31.145  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-31 08:51:31.145  1017  1030 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6721 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 08:51:31.145  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 08:51:31.145  1017  1030 D InputDispatcher: Focused application set to: xxxx
08-31 08:51:31.145  1017  1030 D InputDispatcher: Focus left window: 1480
08-31 08:51:31.145  6721  6721 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:51:31.145  6710  6710 D AndroidRuntime: Shutting down VM
08-31 08:51:31.145  6721  6721 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 08:51:31.155  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 08:51:31.155  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 08:51:31.165  6721  6721 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 08:51:31.165  6721  6721 D ActivityThread: Added TimaKeyStore provider
08-31 08:51:31.175  1017  1448 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-31 08:51:31.175  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 08:51:31.185  1017  1017 V ActivityManager: Display changed displayId=0
08-31 08:51:31.195  1017  1448 D PersonaManager: isKioskContainerExistOnDevice
08-31 08:51:31.205  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-31 08:51:31.225   258  5972 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-31 08:51:31.235   258   443 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-31 08:51:31.235  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{2bfc3749 token=android.os.BinderProxy@c8613fb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-31 08:51:31.235  1480  1480 D Launcher: onTrimMemory. Level: 20
08-31 08:51:31.305  6721  6721 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-31 08:51:31.325  6721  6721 I cr.library_loader: Time to load native libraries: 4 ms (timestamps 7758-7762)
08-31 08:51:31.325  6721  6721 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 08:51:31.355  6710  6710 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 08:51:31.375  6721  6721 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1adab566}
08-31 08:51:31.375  6721  6721 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 08:51:31.385  6721  6721 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 08:51:31.425  6721  6721 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-31 08:51:31.425  6721  6721 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 08:51:31.435  6721  6721 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 08:51:31.465  6721  6721 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 08:51:31.465  6721  6721 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 08:51:31.465  6721  6721 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 08:51:31.465  6721  6721 I Adreno-EGL: Local Branch: 
08-31 08:51:31.465  6721  6721 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 08:51:31.465  6721  6721 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 08:51:31.465  6721  6721 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-31 08:51:31.565  6721  6721 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 08:51:31.575  6721  6721 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-31 08:51:31.575  6721  6721 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-31 08:51:31.585  6721  6721 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-31 08:51:31.585  6721  6721 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-31 08:51:31.655  1017  1314 E Watchdog: !@Sync 3
08-31 08:51:31.705  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{1cd96ff3 u0 com.test.thalitest/.MainActivity t2}
08-31 08:51:31.705  6721  6721 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 08:51:31.715  6721  6721 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 08:51:31.725  6721  6721 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 08:51:31.725  6721  6721 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-31 08:51:31.735  6721  6721 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-31 08:51:31.745  6721  6721 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 08:51:31.745  6721  6721 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 08:51:31.785  6721  6761 D OpenGLRenderer: Render dirty regions requested: true
08-31 08:51:31.795  1017  1486 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 08:51:31.795  1017  1486 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 08:51:31.795  1017  1486 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 08:51:31.795  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 08:51:31.795  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-31 08:51:31.795  6721  6748 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-31 08:51:31.795  6721  6721 V ActivityThread: updateVisibility : ActivityRecord{3ce0dec6 token=android.os.BinderProxy@6f542ab {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-31 08:51:31.805  6721  6721 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 08:51:31.805  6721  6721 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 08:51:31.815   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-31 08:51:31.845  1017  1250 D InputDispatcher: Focus entered window: 6721
08-31 08:51:31.845  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 08:51:31.845  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 08:51:31.845  6721  6721 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-31 08:51:31.845  6721  6761 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 08:51:31.845  6721  6761 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-31 08:51:31.845  6721  6761 D OpenGLRenderer: Enabling debug mode 0
08-31 08:51:31.865  1017  1100 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-31 08:51:31.875  1175  1175 I StatusBar: Icon Only
08-31 08:51:31.875  1175  1175 D PanelView: There is/are notification(s) 
08-31 08:51:31.875  1017  6765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-31 08:51:31.885  1017  1047 I ActivityManager: Displayed Component not be shown by security: +687ms (total +765ms)
08-31 08:51:31.885  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1cd96ff3 u0 com.test.thalitest/.MainActivity t2} time:108328
08-31 08:51:31.885  1017  1047 W ActivityManager: mDVFSHelper.release()
08-31 08:51:31.895  6721  6721 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-31 08:51:31.895  6721  6721 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6f542ab time:108333
08-31 08:51:31.895   258  1878 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-31 08:51:31.895   258   443 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-31 08:51:31.935  1872  1872 I SamsungIME: getCurrentCandidateView
08-31 08:51:32.005  6721  6721 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6721
08-31 08:51:32.055  1872  1872 D SamsungIME: Dismiss ExpandCandiate
,08-31 08:51:32.225  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 08:51:32.265  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 08:51:32.275  1872  1872 I SamsungIME: KeybaordView init() : load resources
,08-31 08:51:32.285  6721  6721 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 08:51:32.305  1872  1872 I SamsungIME: getCurrentKeyboard
08-31 08:51:32.305  1872  1872 I SamsungIME: getTextKeyboard
,08-31 08:51:32.325  1872  1872 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 08:51:32.375  6721  6768 D jxcore_app_log: JniHelper::setJavaVM(0xb85d22b0), pthread_self() = -1196034376
,08-31 08:51:32.385  6721  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 08:51:32.385  6721  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 08:51:32.385  6721  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 08:51:32.385  6721  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 08:51:32.385  6721  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 08:51:32.385  6721  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ea6634c added. We now have 1 listener(s)
,08-31 08:51:32.385  6721  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-31 08:51:32.395  6721  6768 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 08:51:32.395  6721  6768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 08:51:32.395  6721  6768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 08:51:32.395  6721  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb02c9b added. We now have 1 listener(s)
,08-31 08:51:32.395  6721  6768 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:32.405  6721  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:51:32.405  6721  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 08:51:32.405  6721  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 08:51:32.405  6721  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 08:51:32.405  6721  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 08:51:32.405  6721  6768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:32.405  6721  6768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-31 08:51:32.415  6721  6768 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 08:51:32.415  6721  6768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:32.415  6721  6768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:32.415  6721  6768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:32.415  6721  6768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:32.415  6721  6768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:32.415  6721  6768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:32.415  6721  6768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:32.415  6721  6768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:32.415  6721  6768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 08:51:32.415  6721  6768 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:51:32.425  6721  6768 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 08:51:32.425  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:32.425  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:32.455  6721  6721 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 08:51:32.605   322   322 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-31 08:51:32.605   322   322 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-31 08:51:33.005  6721  6775 W jxcore-log: Initializing JXcore engine
08-31 08:51:33.005  6721  6775 W jxcore-log: JXcore engine is ready
,08-31 08:51:33.065  1979  1979 E audit   : type=1400 msg=audit(1472626293.055:205): avc:  denied  { ioctl } for  pid=6775 comm="Thread-1231" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 08:51:33.065  1979  1979 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:51:33.065  1979  1979 E audit   : type=1300 msg=audit(1472626293.055:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f4af8f8 items=0 ppid=309 ppcomm=main pid=6775 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1231" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-31 08:51:33.065  1979  1979 E audit   : type=1320 msg=audit(1472626293.055:205): 
,08-31 08:51:33.075  6721  6775 W jxcore-log: Starting JXcore engine
,08-31 08:51:33.185  6721  6775 W jxcore-log: Platform android,
08-31 08:51:33.185  6721  6775 W jxcore-log: 
08-31 08:51:33.185  6721  6775 W jxcore-log: Process ARCH arm
08-31 08:51:33.185  6721  6775 W jxcore-log: 
,08-31 08:51:33.375  6721  6775 I jxcore-log: JXcore Cordova bridge is ready!,
08-31 08:51:33.375  6721  6775 I jxcore-log: 
08-31 08:51:33.375  6721  6775 W jxcore-log: JXcore engine is started
,08-31 08:51:33.385  6721  6768 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 08:51:33.385  6721  6721 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 08:51:33.595   291   291 E SMD     : DCD OFF,
,08-31 08:51:35.605  1017  3387 D SSRM:n  : SIOP:: AP = 320
,08-31 08:51:35.715  1017  1049 I PowerManagerService: [PWL] Off : 50s ago,
,08-31 08:51:36.595   291   291 E SMD     : DCD OFF
,08-31 08:51:37.615   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 08:51:38.615   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 08:51:39.455  5635  5635 D FactoryTest: Not factory mode,
08-31 08:51:39.455  5635  5635 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-31 08:51:39.455  5635  5635 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-31 08:51:39.455  5635  5635 D MTPRx   : still no open session command from host, so toast,
,08-31 08:51:39.455  5635  5635 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-31 08:51:39.455  5635  5635 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 ,
08-31 08:51:39.465  5635  5635 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115900
08-31 08:51:39.465  1017  4350 E PersonaManagerService: inState():  stateMachine is null !!
08-31 08:51:39.465  1017  4350 I PersonaManagerService: PersonaId don't exist
,08-31 08:51:39.465  1017  4350 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-31 08:51:39.465  1017  4350 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-31 08:51:39.465  1017  4350 W ActivityManager: userId = 0, bbcId = -10000,
08-31 08:51:39.465  1017  4350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:39.465  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-31 08:51:39.475  1017  4350 W ActivityManager: mDVFSHelper.acquire()
,08-31 08:51:39.495  1017  4350 D PersonaManager: isKioskContainerExistOnDevice
,08-31 08:51:39.515  1017  4350 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest,
08-31 08:51:39.515  1017  4350 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-31 08:51:39.515  1017  4350 D InputDispatcher: Focused application set to: xxxx
08-31 08:51:39.515  1017  4350 D InputDispatcher: Focus left window: 6721
,08-31 08:51:39.515  5635  5635 E MTPRx   : started activity for popup
,08-31 08:51:39.515  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 08:51:39.515  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 08:51:39.535  5635  5635 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-31 08:51:39.545  5635  5635 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-31 08:51:39.545  5635  5635 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 08:51:39.545  5635  5635 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:51:39.545  5635  5635 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 08:51:39.545  5635  5635 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 08:51:39.565  5635  5635 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-31 08:51:39.565  1017  1440 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-31 08:51:39.565  1017  1440 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 08:51:39.565  1017  1440 D InputDispatcher: Focused application set to: xxxx
,08-31 08:51:39.565  1017  1440 D InputDispatcher: Focus entered window: 6721
,08-31 08:51:39.575  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 08:51:39.575  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 08:51:39.575  1017  1567 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 08:51:39.575  1017  1567 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1c669772 attribute=null, token = android.os.BinderProxy@1e0839c2
,08-31 08:51:39.605   291   291 E SMD     : DCD OFF
,08-31 08:51:39.615   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:51:39.615  5635  5635 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-31 08:51:39.625  5635  5635 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-31 08:51:39.625  5635  5635 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-31 08:51:39.645  6721  6721 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 08:51:39.645  6721  6721 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED,
08-31 08:51:39.645  6721  6721 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-31 08:51:39.645  6721  6721 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-31 08:51:39.645  1017  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-31 08:51:39.645  1017  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 08:51:39.655  1017  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-31 08:51:39.655  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 08:51:39.655  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 08:51:39.665  6721  6721 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 08:51:39.665  6721  6721 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-31 08:51:39.675  6721  6721 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@127ce197 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1183d2ec, 16908290=android.view.AbsSavedState$1@1183d2ec}, android:focusedViewId=100}]}]
08-31 08:51:39.675  6721  6721 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-31 08:51:39.675  6721  6721 V ActivityThread: updateVisibility : ActivityRecord{3ce0dec6 token=android.os.BinderProxy@6f542ab {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-31 08:51:39.675  6721  6721 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 08:51:39.675  6721  6721 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-31 08:51:39.675  6721  6721 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6f542ab time:116112
,08-31 08:51:39.685  1017  1100 D PersonaManager: isKioskContainerExistOnDevice
,08-31 08:51:39.775  1017  4347 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 08:51:39.775  1017  4347 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-31 08:51:39.775  1017  4347 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 08:51:39.775  1017  4347 D BatteryService: stay LED for fully charged
08-31 08:51:39.775  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 08:51:39.785  1017  1017 I MotionRecognitionService: Plugged
,08-31 08:51:39.785  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 08:51:39.785  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 08:51:39.785  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 08:51:39.785  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 08:51:39.785  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 08:51:39.795  3189  3189 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-31 08:51:39.795  3189  3301 D HeadsetStateMachine: Disconnected process message: 10
,08-31 08:51:39.815  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 08:51:39.815  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 08:51:39.815  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 08:51:39.815  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-31 08:51:39.815  1175  1175 D SViewCoverView: level :100 plugged : 2
,08-31 08:51:40.615   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:51:41.175  1017  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-31 08:51:41.615   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:51:42.475  1017  1042 W ActivityManager: mDVFSHelper.release(),
,08-31 08:51:42.605   291   291 E SMD     : DCD OFF,
,08-31 08:51:42.615   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-31 08:51:43.565  1017  1095 V AlarmManager: waitForAlarm result :4
,08-31 08:51:43.565  1017  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0,
,08-31 08:51:43.595  2003  2003 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-31 08:51:43.635  1017  1100 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:51:43.635  1017  1100 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-31 08:51:43.635  1017  1100 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:43.635  1017  1100 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:43.635  1017  1100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:43.685  4777  4777 D ConnectivityManager: CallingUid : 10011, CallingPid : 4777
,08-31 08:51:43.685  1017  1448 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 08:51:43.685  1017  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-31 08:51:43.685  1017  1128 D ConnectivityService: apparently satisfied.  currentScore=60
,08-31 08:51:43.685  1017  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-31 08:51:43.695  4777  6783 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 08:51:43.735  4777  6784 W DriveInitializer: Background init thread started
,08-31 08:51:43.775   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-31 08:51:43.775   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:43.775  4777  6784 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-31 08:51:43.845  1017  1561 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:51:43.845  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.MonitorService; callingUser = 0; userId(target) = 0
,08-31 08:51:43.855  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:43.855  1017  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:43.855  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:43.875  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.youtube
,08-31 08:51:43.875  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator; callingUser = 0; userId(target) = 0
,08-31 08:51:43.875  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:43.875  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:43.875  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.youtube
,08-31 08:51:43.875  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:43.875  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:43.875  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:43.875  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:43.885  6792  6792 E Zygote  : MountEmulatedStorage()
08-31 08:51:43.885  6792  6792 E Zygote  : v2,
08-31 08:51:43.885  6792  6792 I libpersona: KNOX_SDCARD checking this for 10161
08-31 08:51:43.885  6792  6792 I libpersona: KNOX_SDCARD not a persona
08-31 08:51:43.885  1017  1029 I ActivityManager: Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6792 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-31 08:51:43.895  6792  6792 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:43.895  6792  6792 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:43.895  6792  6792 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:51:43.915  6792  6792 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:43.915  6792  6792 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:43.935  4777  6784 W DriveInitializer: Background init thread ended
,08-31 08:51:44.005  1017  1029 W ActivityManager: getRunningAppProcesses: caller 10161 does not hold REAL_GET_TASKS; limiting output
,08-31 08:51:44.015  6792  6808 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 08:51:44.015  6792  6808 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 08:51:44.075  6792  6808 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 08:51:44.145  6792  6808 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 08:51:44.145  6792  6808 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e2f377c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-31 08:51:44.145  6792  6808 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-31 08:51:44.235  6792  6792 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-31 08:51:44.275  6792  6809 D ChimeraCfgMgr: Reading stored module config
,08-31 08:51:44.275  1017  1561 D ActivityManager: bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.gms, action: null
08-31 08:51:44.275  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 08:51:44.275  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:44.275  1017  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:44.275  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,08-31 08:51:44.285  2003  2003 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 08:51:44.285  2003  2003 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 08:51:44.305  6792  6809 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,08-31 08:51:44.305  6792  6809 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000006@DynamiteModulesA_GmsCore_prodlmp_hdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000006/DynamiteModulesA_GmsCore_prodlmp_hdpi_release.apk': Failed to open oat filename for reading: No such file or directory
,08-31 08:51:44.305  6792  6809 D ChimeraFileApk: Classloading successful. Optimized code found.
,08-31 08:51:44.315  6792  6809 D DynamitePackage: Instantiated singleton DynamitePackage.
08-31 08:51:44.315  6792  6809 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
,08-31 08:51:44.345  1017  1567 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:44.355  1017  1567 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:44.355  1017  1567 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:44.355  1017  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,08-31 08:51:44.365  1017  1561 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:44.365  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:44.365  1017  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:44.365  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,08-31 08:51:44.375   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
08-31 08:51:44.375   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:44.375  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,08-31 08:51:44.495  1017  1100 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:44.495  1017  1100 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:44.495  1017  1100 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 08:51:44.495  1017  1100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,08-31 08:51:44.515  1017  1250 W ActivityManager: getRunningAppProcesses: caller 10161 does not hold REAL_GET_TASKS; limiting output
,08-31 08:51:44.515  1017  1440 D ActivityManager: bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
,08-31 08:51:44.515  1017  1440 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,08-31 08:51:44.525  1017  1440 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:44.525  1017  1440 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:44.525  1017  1440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,08-31 08:51:44.645   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
08-31 08:51:44.645   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:44.645  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
08-31 08:51:44.645   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
08-31 08:51:44.645   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:51:44.645  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
08-31 08:51:44.645   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
08-31 08:51:44.645   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:51:44.645  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
08-31 08:51:44.655   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
08-31 08:51:44.655   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:51:44.655  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
08-31 08:51:44.655  1017  1448 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-31 08:51:44.655  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:44.655  1017  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:44.655  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
08-31 08:51:44.665   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
08-31 08:51:44.665   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:51:44.665  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
08-31 08:51:44.665   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
08-31 08:51:44.665   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:51:44.665  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
08-31 08:51:44.665   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
08-31 08:51:44.665   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:51:44.665  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
08-31 08:51:44.675   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
08-31 08:51:44.675   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:51:44.675  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,08-31 08:51:44.695   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
08-31 08:51:44.695   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:44.695  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,08-31 08:51:44.695   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
08-31 08:51:44.695   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:51:44.695  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
08-31 08:51:44.695   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
08-31 08:51:44.695   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:51:44.695  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,08-31 08:51:44.705  6792  6792 W InstanceID/Rpc: Found 10011
,08-31 08:51:44.715  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:44.715  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:44.715  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,08-31 08:51:44.735  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:44.735  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:44.735  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,08-31 08:51:44.735   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
08-31 08:51:44.735   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:44.735  6792  6792 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,08-31 08:51:44.755  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:44.755  1017  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:44.755  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,08-31 08:51:44.835  1017  1561 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
08-31 08:51:44.835  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,08-31 08:51:44.835  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:44.835  1017  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:44.835  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,08-31 08:51:44.865  1017  1100 W ActivityManager: getRunningAppProcesses: caller 10161 does not hold REAL_GET_TASKS; limiting output
,08-31 08:51:44.915  6792  6882 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,08-31 08:51:44.915  6792  6882 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,08-31 08:51:44.915  6792  6882 I System.out: Thread-1285(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,08-31 08:51:44.915  6792  6882 I System.out: Thread-1285(ApacheHTTPLog):isSBSettingEnabled false
,08-31 08:51:44.915  6792  6882 I System.out: Thread-1285(ApacheHTTPLog):isShipBuild true
,08-31 08:51:44.915  6792  6882 I System.out: Thread-1285(ApacheHTTPLog):SMARTBONDING_ENABLED is false
08-31 08:51:44.915  6792  6882 I System.out: Thread-1285(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-31 08:51:44.915   278   973 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:51:44.915   278   973 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,08-31 08:51:45.005  1017  4350 I art     : Explicit concurrent mark sweep GC freed 41001(2MB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 2.757ms total 158.091ms,
08-31 08:51:45.005  1017  4350 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:45.005  1017  4350 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:45.005  1017  4350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:45.005  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:45.045  6792  6865 I System.out: Thread-1268(ApacheHTTPLog):isSBSettingEnabled false
,08-31 08:51:45.045  6792  6865 I System.out: Thread-1268(ApacheHTTPLog):isShipBuild true
08-31 08:51:45.045  6792  6865 I System.out: Thread-1268(ApacheHTTPLog):SMARTBONDING_ENABLED is false
08-31 08:51:45.045  6792  6865 I System.out: Thread-1268(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-31 08:51:45.045   278   973 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:51:45.045   278   973 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,08-31 08:51:45.075  6792  6865 I qtaguid : Tagging socket 64 with tag 0{0,0} for uid -1, pid: 6792, getuid(): 10161
,08-31 08:51:45.095  6792  6882 I System.out: Thread-1285 calls detatch()
,08-31 08:51:45.465  6792  6865 I qtaguid : Untagging socket 64
,08-31 08:51:45.465  6792  6865 I System.out: Thread-1268 calls detatch()
,08-31 08:51:45.485  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:45.485  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:45.485  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,08-31 08:51:45.495  1017  1478 I ActivityManager: Killing 6394:com.samsung.helphub/1000 (adj 15): empty #21
,08-31 08:51:45.535  1017  1366 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:51:45.535  1017  1366 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,08-31 08:51:45.535  1017  1366 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:45.535  1017  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:45.535  1017  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:45.565  1017  4347 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:51:45.565  1017  4347 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-31 08:51:45.565  1017  4347 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:45.565  1017  4347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:45.565  1017  4347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:45.585  1017  1567 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-31 08:51:45.585  1017  1567 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-31 08:51:45.605   291   291 E SMD     : DCD OFF
,08-31 08:51:45.615  1017  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:45.625  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:45.625  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:45.625  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:45.625  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:45.625  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:45.625  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:45.625  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:45.635  1017  3387 D SSRM:n  : SIOP:: AP = 330,
,08-31 08:51:45.645  2003  2003 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory,
,08-31 08:51:45.655  2003  2003 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 08:51:45.685  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:45.685  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:45.685  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:45.765  1017  1561 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-31 08:51:45.775  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 08:51:45.775  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:45.775  1017  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:45.775  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:45.805  1017  1366 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-31 08:51:45.805  1017  1366 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-31 08:51:45.815  1017  1366 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:45.815  1017  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:45.815  1017  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:45.815  2003  6893 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 08:51:45.815   278   973 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:51:45.815   278   973 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 08:51:45.825  2003  6893 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 08:51:45.825  2003  6893 I qtaguid : Tagging socket 63 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2003, getuid(): 10011
,08-31 08:51:45.875  2003  6893 I qtaguid : Tagging socket 67 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2003, getuid(): 10011
,08-31 08:51:46.005  1017  3402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 08:51:46.105  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-31 08:51:46.105  6721  6775 I jxcore-log: 
,08-31 08:51:46.105  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-31 08:51:46.105  6721  6775 I jxcore-log: 
,08-31 08:51:46.105  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:46.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:46.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:46.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:46.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:46.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:46.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:46.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:46.105  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:51:46.115  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 08:51:46.115  6721  6775 I jxcore-log: 
,08-31 08:51:46.115  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 08:51:46.115  6721  6775 I jxcore-log: 
,08-31 08:51:46.195  1017  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:51:46.195  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-31 08:51:46.205  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:46.205  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:46.205  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:46.225  2003  6893 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 08:51:46.225   278   973 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:51:46.225   278   973 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 08:51:46.225  2003  6893 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-31 08:51:46.225  2003  6893 I qtaguid : Tagging socket 68 with tag 1000120300000000{268440067,0} for uid -1, pid: 2003, getuid(): 10011
,08-31 08:51:46.225  4777  6897 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-31 08:51:46.225  4777  6897 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-31 08:51:46.275  2003  6893 I qtaguid : Tagging socket 71 with tag 1000120300000000{268440067,0} for uid -1, pid: 2003, getuid(): 10011
,08-31 08:51:46.505  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:51:46.505  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-31 08:51:46.505  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:46.505  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:46.505  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:46.535  2003  6893 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 08:51:46.535  2003  6893 I qtaguid : Tagging socket 68 with tag 1000120300000000{268440067,0} for uid -1, pid: 2003, getuid(): 10011
,08-31 08:51:46.555  1017  4351 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:46.555  1017  4351 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:46.555  1017  4351 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:46.555  1017  4351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:46.605  1017  1440 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:46.605  1017  1440 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:46.605  1017  1440 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:46.605  1017  1440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:46.605  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:46.605  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:46.605  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:46.605  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:46.625  6901  6901 E Zygote  : MountEmulatedStorage(),
,08-31 08:51:46.625  6901  6901 E Zygote  : v2,
08-31 08:51:46.625  6901  6901 I libpersona: KNOX_SDCARD checking this for 10011
08-31 08:51:46.625  6901  6901 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:46.625  1017  1440 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6901 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
08-31 08:51:46.625  6901  6901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 08:51:46.625  6901  6901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:46.625  6901  6901 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:51:46.645  6901  6901 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:46.645  6901  6901 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:46.655   309   309 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 626us total 26.347ms
,08-31 08:51:46.675   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 846us total 20.567ms
,08-31 08:51:46.675  1017  4350 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:46.685  6901  6901 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 08:51:46.685  6901  6901 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 08:51:46.685  1017  4350 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:46.685  1017  4350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:46.685  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:46.695   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 19.371ms
,08-31 08:51:46.725  1017  1366 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:46.725  1017  1366 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:46.725  1017  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:46.725  1017  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:46.735  6901  6901 I MultiDex: VM with version 2.1.0 has multidex support
08-31 08:51:46.735  6901  6901 I MultiDex: install
08-31 08:51:46.735  6901  6901 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 08:51:46.745  2003  6893 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-31 08:51:46.755  1017  1448 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:46.755  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:46.755  1017  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:46.755  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:46.765  6901  6901 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 08:51:46.765  2003  6893 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,08-31 08:51:46.775  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:46.775  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:46.775  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:46.825  6901  6901 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 08:51:46.825  6901  6901 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@10ab8302: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-31 08:51:46.825  6901  6901 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-31 08:51:46.855  6901  6901 D ChimeraCfgMgr: Reading stored module config
,08-31 08:51:46.935  6721  6775 D executeNativeTests: Running unit tests
,08-31 08:51:46.955  6901  6919 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-31 08:51:46.955  6901  6901 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-31 08:51:46.955  6901  6901 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-31 08:51:47.025   286  1600 D WVCdm   : Instantiating CDM.
,08-31 08:51:47.025   286   685 I WVCdm   : CdmEngine::OpenSession
,08-31 08:51:47.025   286   685 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-31 08:51:47.055   286   685 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-31 08:51:47.065  6721  6734 I art     : Background sticky concurrent mark sweep GC freed 39227(1938KB) AllocSpace objects, 7(993KB) LOS objects, 19% free, 10MB/12MB, paused 5.854ms total 74.638ms
,08-31 08:51:47.075   286   685 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-31 08:51:47.085  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:51:47.085  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 added. We now have 2 listener(s)
,08-31 08:51:47.085  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 08:51:47.085  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:51:47.085  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:51:47.085  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:51:47.085  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa added. We now have 2 listener(s)
08-31 08:51:47.085  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:47.095  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:51:47.095  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:47.095  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:47.095  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:47.095  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:47.095  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:47.095  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:47.095  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:47.095  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:47.095  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:47.105  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:47.105  6721  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:51:47.105  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:47.105  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 08:51:47.105  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 08:51:47.105  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 08:51:47.105  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:47.115  6721  6775 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 08:51:47.115  6721  6775 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 08:51:47.115  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 08:51:47.115  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 08:51:47.115  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 08:51:47.115  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:51:47.115  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.115  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:51:47.115  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.115  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.115  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:47.115  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 08:51:47.115  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 removed from the list
08-31 08:51:47.115  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.115  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa removed from the list
08-31 08:51:47.115  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.115  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.115  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.115  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.115  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:51:47.115  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.115  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.115  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.125  6721  6775 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-31 08:51:47.125  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.125  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.125  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.125  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.125  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.125  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.125  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.125  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.125  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.125  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.125  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.125  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.125  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.125  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.125  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.125  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.125  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.125  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 08:51:47.135  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.135  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.135  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.135  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.135  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.135  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.135  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.135  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.135  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.135  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.135  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.135  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.135  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.135  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.135  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.135  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.135  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.135  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.135   286   685 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-31 08:51:47.135  6721  6775 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 08:51:47.135   286   286 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-31 08:51:47.135   286   286 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-31 08:51:47.135   286   286 I WVCdm   : CdmEngine::GenerateKeyRequest
08-31 08:51:47.145  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:47.145   286   286 D WVCdm   : PrepareKeyRequest: nonce=701001430
08-31 08:51:47.145  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:47.145  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:47.145  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:47.145  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:47.145  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:47.145  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:47.145  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:47.145  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:47.145  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:47.145  6721  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:51:47.145  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:51:47.145  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:51:47.145  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:51:47.145  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:47.145  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 08:51:47.155  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:47.155  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 08:51:47.155  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:47.165  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 08:51:47.175  6901  6909 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-31 08:51:47.175  6901  6909 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 08:51:47.175  6901  6909 I System.out: (HTTPLog)-Static: isShipBuild true
08-31 08:51:47.175  6901  6909 I System.out: (HTTPLog)-Thread-1209-356691047: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-31 08:51:47.175  6901  6909 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 08:51:47.175  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 08:51:47.175   278   973 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:51:47.175   278   973 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-31 08:51:47.175  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 08:51:47.175  6901  6909 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-31 08:51:47.185  6901  6909 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6901, getuid(): 10011
08-31 08:51:47.185  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-31 08:51:47.185  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 08:51:47.185  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:51:47.185  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:51:47.195  3189  3302 D BtGatt.GattService: registerClient() - UUID=2e41f1fc-5dc1-4345-bdff-e8eef2d4954c
,08-31 08:51:47.245  3189  3290 D BtGatt.GattService: onClientRegistered() - UUID=2e41f1fc-5dc1-4345-bdff-e8eef2d4954c, clientIf=6
,08-31 08:51:47.245  6721  6732 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 08:51:47.245  3189  3198 D BtGatt.GattService: start scan with filters
,08-31 08:51:47.245  3189  3299 D BtGatt.ScanManager: handling starting scan
,08-31 08:51:47.245  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:51:47.255  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 08:51:47.255  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-31 08:51:47.255  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
08-31 08:51:47.255  3189  3299 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:47.255  3189  3290 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-31 08:51:47.255  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:51:47.255  3189  3299 D BtGatt.ScanManager: allow scan with filters
08-31 08:51:47.255  3189  3299 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 08:51:47.255  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:51:47.255  3189  3299 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-31 08:51:47.255  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-31 08:51:47.255  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 08:51:47.255  3189  3290 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-31 08:51:47.255  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:51:47.255  3189  3299 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:51:47.255  3189  3299 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,08-31 08:51:47.265  3189  3290 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 08:51:47.265  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:51:47.265  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:51:47.265  3189  3290 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 08:51:47.265  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:51:47.265  6721  6775 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 08:51:47.275  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:51:47.275  6721  6775 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-31 08:51:47.275  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.275  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 08:51:47.275  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:47.275  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:51:47.275  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:51:47.275  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:51:47.275  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:51:47.275  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:51:47.285  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 08:51:47.285  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 08:51:47.285  3189  3198 D BtGatt.GattService: stopScan() - queue size =1
08-31 08:51:47.285  3189  3302 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 08:51:47.285  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:47.285  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:51:47.285  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:51:47.285  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:51:47.285  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-31 08:51:47.285  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:51:47.295  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 08:51:47.295  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:51:47.295  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:51:47.295  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:47.295  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:47.295  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:47.295  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:47.295  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.295  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.295  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:47.295  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.295  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.295  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.295  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.295  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.295  6721  6775 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 08:51:47.295  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:47.295  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:47.295  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:47.295  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:47.295  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:47.295  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:47.295  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:47.295  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:47.295  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:47.305  3189  3299 D BtGatt.ScanManager: filter size is 1
,08-31 08:51:47.305  3189  3299 D BtGatt.ScanManager: delete FilterIndex - 3
,08-31 08:51:47.305  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:51:47.305  6721  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:51:47.305  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:51:47.305  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:51:47.305  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:51:47.305  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:47.305  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:51:47.305  3189  3290 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 08:51:47.305  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:51:47.305  3189  3299 D BtGatt.ScanManager: stopping BLe Batch
,08-31 08:51:47.305  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:51:47.305  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:47.305  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:47.315  3189  3290 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 08:51:47.315  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:51:47.315  3189  3299 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 08:51:47.315  3189  3290 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 08:51:47.315  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:51:47.315  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:51:47.315  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:51:47.315  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:51:47.315  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:51:47.315  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:51:47.325  3189  3197 D BtGatt.GattService: registerClient() - UUID=e44f8254-eb23-40f8-b9d6-a23d329f1c2a
,08-31 08:51:47.365  3189  3290 D BtGatt.GattService: onClientRegistered() - UUID=e44f8254-eb23-40f8-b9d6-a23d329f1c2a, clientIf=6
,08-31 08:51:47.365  6721  6766 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 08:51:47.365  3189  3198 D BtGatt.GattService: start scan with filters
,08-31 08:51:47.365  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 08:51:47.365  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:51:47.365  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:51:47.365  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 08:51:47.365  3189  3299 D BtGatt.ScanManager: handling starting scan
,08-31 08:51:47.365  3189  3290 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 08:51:47.365  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:51:47.365  3189  3299 D BtGatt.ScanManager: allow scan with filters
,08-31 08:51:47.365  3189  3299 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 08:51:47.365  3189  3299 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-31 08:51:47.365  3189  3290 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 08:51:47.365  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:51:47.365  3189  3299 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 08:51:47.365  3189  3299 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 08:51:47.375  3189  3290 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 08:51:47.375  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:51:47.375  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:51:47.375  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:51:47.375  3189  3290 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 08:51:47.375  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:51:47.375  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:51:47.375  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:51:47.385  6721  6775 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 08:51:47.385  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:51:47.385  6721  6775 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:51:47.385  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:51:47.385  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 08:51:47.385  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.385  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:51:47.385  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 08:51:47.385  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:51:47.385  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:51:47.385  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 08:51:47.385  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:51:47.385  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:51:47.385  3189  3198 D BtGatt.GattService: stopScan() - queue size =1
,08-31 08:51:47.395  3189  3299 D BtGatt.ScanManager: filter size is 1
,08-31 08:51:47.395  3189  3299 D BtGatt.ScanManager: delete FilterIndex - 4
,08-31 08:51:47.395  3189  3197 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 08:51:47.395  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:47.395  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:51:47.395  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:51:47.395  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:51:47.395  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:51:47.395  3189  3290 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 08:51:47.395  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:51:47.395  3189  3299 D BtGatt.ScanManager: stopping BLe Batch
,08-31 08:51:47.395  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:51:47.395  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 08:51:47.395  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:51:47.395  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:51:47.395  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:51:47.395  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:47.395  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:47.395  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:47.395  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.395  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.395  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:47.395  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.395  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.395  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.395  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.395  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.395  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.395  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.395  3189  3290 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 08:51:47.395  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:51:47.405  3189  3299 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 08:51:47.405  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.405  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.405  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.405  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.405  6721  6775 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 08:51:47.405  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:47.405  3189  3290 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 08:51:47.405  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:51:47.405  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:47.405  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:47.405  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:47.405  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:47.405  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:47.405  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:47.405  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:47.405  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:47.415  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:51:47.415  6721  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:51:47.415  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:47.415  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:47.415  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 08:51:47.415  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:51:47.415  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:51:47.415  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:47.415  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:51:47.425  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:51:47.425  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:51:47.425  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:51:47.425  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:51:47.425  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:51:47.425  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:51:47.435  3189  3198 D BtGatt.GattService: registerClient() - UUID=d8de4fb7-ba6a-4dd6-839e-4232e7b33041
,08-31 08:51:47.465  6901  6909 I qtaguid : Untagging socket 30
,08-31 08:51:47.475  3189  3290 D BtGatt.GattService: onClientRegistered() - UUID=d8de4fb7-ba6a-4dd6-839e-4232e7b33041, clientIf=6,
,08-31 08:51:47.475  6721  6735 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-31 08:51:47.475  3189  3197 D BtGatt.GattService: start scan with filters
,08-31 08:51:47.475  3189  3299 D BtGatt.ScanManager: handling starting scan
,08-31 08:51:47.475  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 08:51:47.475  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:51:47.475  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:51:47.475  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 08:51:47.475  3189  3290 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 08:51:47.475  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:51:47.475  3189  3299 D BtGatt.ScanManager: allow scan with filters
,08-31 08:51:47.485  3189  3299 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 08:51:47.485  3189  3299 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-31 08:51:47.485  3189  3290 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 08:51:47.485  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:51:47.485  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:51:47.485  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:51:47.485  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:51:47.485  3189  3299 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:51:47.485  3189  3299 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 08:51:47.485  3189  3290 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 08:51:47.485  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:51:47.485  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:51:47.495  3189  3290 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 08:51:47.495  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:51:47.495  6721  6775 I io.jxcore.node.ConnectionHelper: start: OK
08-31 08:51:47.495  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.495  6721  6775 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:51:47.495  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.495  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 08:51:47.495  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.495  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:51:47.495  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:51:47.495  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:51:47.495  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:51:47.495  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 08:51:47.495  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:51:47.495  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:51:47.495  3189  3198 D BtGatt.GattService: stopScan() - queue size =1
,08-31 08:51:47.495  3189  3299 D BtGatt.ScanManager: filter size is 1
,08-31 08:51:47.495  3189  3299 D BtGatt.ScanManager: delete FilterIndex - 5
,08-31 08:51:47.505  3189  3290 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 08:51:47.505  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:51:47.505  3189  3299 D BtGatt.ScanManager: stopping BLe Batch
,08-31 08:51:47.505  3189  3197 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 08:51:47.505  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:47.505  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:51:47.505  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:51:47.505  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:51:47.505  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:51:47.505  3189  3290 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 08:51:47.505  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:51:47.505  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:47.505  3189  3299 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 08:51:47.505  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-31 08:51:47.505  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:51:47.505  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 08:51:47.505  3189  3290 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 08:51:47.505  3189  3290 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:51:47.505  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:51:47.505  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:47.505  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:47.505  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:51:47.505  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.505  6721  6775 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:51:47.505  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.505  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.505  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:51:47.505  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.515  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:47.515  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.515  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.515  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.515  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.515  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.515  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.515  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.515  6721  6775 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-31 08:51:47.515  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.515  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.515  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:51:47.515  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.515  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.515  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.515  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.515  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.515  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.515  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.515  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.515  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.515  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.515  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-31 08:51:47.515  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.515  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.515  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.515  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.515  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.515  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.515  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.515  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.515  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.515  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.515  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.515  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.515  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.515  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.515  6721  6775 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-31 08:51:47.525  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.525  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.525  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.525  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.525  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.525  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.525  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.525  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.525  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.525  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.525  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.525  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.525  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.525  6721  6775 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 08:51:47.525  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.525  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.525  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.525  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.525  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.525  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.525  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.525  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.525  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.525  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.525  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.525  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.525  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 08:51:47.525  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 08:51:47.525  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 08:51:47.525  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 08:51:47.525  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.525  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.525  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.525  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.525  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.525  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.525  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:51:47.525  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.525  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.525  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.525  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.525  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.525  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.535  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.535  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.535  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.535  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.535  6721  6775 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:47.535  6721  6775 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-31 08:51:47.535  6721  6775 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:47.535  6721  6775 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-31 08:51:47.535  6721  6775 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 08:51:47.535  6721  6775 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 08:51:47.535  6721  6775 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 08:51:47.535  6721  6775 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:47.535  6721  6775 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-31 08:51:47.535  6721  6775 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 08:51:47.535  6721  6775 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:47.535  6721  6775 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 08:51:47.535  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 08:51:47.535  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55,
08-31 08:51:47.535  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 08:51:47.535  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 08:51:47.535  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 08:51:47.535  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 08:51:47.535  6721  6775 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 08:51:47.535  6721  6775 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:47.535  6721  6775 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 08:51:47.535  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.535  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.535  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.535  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.535  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.535  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.535  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 08:51:47.535  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.535  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.535  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.535  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.535  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.535  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.535  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.535  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.545  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.545  6721  6929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1295
08-31 08:51:47.545  6721  6775 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported,
08-31 08:51:47.545  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.545  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.545  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.545  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.545  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.545  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.545  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.545  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:51:47.545  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.545  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.545  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.545  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.545  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.545  6721  6775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 08:51:47.545  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.545  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.545  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.545  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.545  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.545  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.545  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.545  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.545  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.545  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.545  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.545  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.545  6721  6928 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1295)
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.545  6721  6928 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1295)
08-31 08:51:47.545  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.545  6721  6775 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 08:51:47.545  6721  6775 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 08:51:47.545  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:51:47.545  6721  6775 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 08:51:47.545  6721  6775 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 08:51:47.545  6721  6775 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 08:51:47.545  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 08:51:47.545  6721  6775 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-31 08:51:47.545  6721  6775 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 08:51:47.545  6721  6775 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 08:51:47.545  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 08:51:47.545  6721  6775 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 08:51:47.545  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.545  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.545  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.545  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.545  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.545  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.545  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.545  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.545  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.545  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.545  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.545  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.545  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.545  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.555  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.555  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.555  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.555  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.555  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.555  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.555  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:51:47.555  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.555  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.555  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.555  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:51:47.555  6721  6721 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:51:47.555  6721  6721 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:51:47.555  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.555  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:47.555  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.555  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:47.555  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.555  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:47.555  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.555  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.555  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.555  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.555  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.555  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.555  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.555  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.565  6721  6775 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 08:51:47.565  6721  6775 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 08:51:47.565  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 08:51:47.565  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:51:47.565  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.565  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.565  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.565  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.565  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:47.565  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.565  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.565  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.565  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.565  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.565  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.565  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.565  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:47.565  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.565  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.565  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.565  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.565  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.565  6721  6930 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-31 08:51:47.565  6721  6930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-31 08:51:47.565  6721  6721 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-31 08:51:47.575  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.575  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.575  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.575  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.575  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.575  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.575  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.575  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.575  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.575  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.575  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.575  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.575  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.575  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.575  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.575  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.575  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.575  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.575  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:47.575  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:47.575  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:47.575  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:47.575  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:47.575  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.575  6721  6775 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1065e725 not in the list
08-31 08:51:47.575  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.575  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
08-31 08:51:47.575  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:47.575  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.575  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:47.575  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:47.575  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:47.575  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:47.575  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:47.575  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:47.575  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336ee0fa not in the list
,08-31 08:51:47.575  6721  6775 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 08:51:47.575  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:51:47.575  6721  6775 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 08:51:47.575  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:51:47.575  6721  6775 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 08:51:47.575  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-31 08:51:47.585  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-31 08:51:47.585  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-31 08:51:47.585  6721  6775 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 08:51:47.585  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 08:51:47.585  6721  6775 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 08:51:47.585  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 08:51:47.585  6721  6775 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 08:51:47.585  6721  6775 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-31 08:51:47.585  6721  6775 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-31 08:51:47.585  6721  6775 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-31 08:51:47.585  6721  6775 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 08:51:47.585  6721  6775 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 08:51:47.585  6721  6775 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 08:51:47.585  6721  6775 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-31 08:51:47.585  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-31 08:51:47.585  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e7b374c added. We now have 2 listener(s)
08-31 08:51:47.585  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:47.585  6721  6775 D BluetoothAdapter: enable()
,08-31 08:51:47.585  6721  6775 D BluetoothAdapter: enable(): BT is already enabled..!
,08-31 08:51:47.595  1017  1478 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 08:51:47.595  1017  1478 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 08:51:47.595  1017  1478 D SecContentProvider2: mCursor = null
,08-31 08:51:47.595  1017  1478 D WifiService: setWifiEnabled: true pid=6721, uid=10171
,08-31 08:51:47.605  1017  1478 W ActivityManager: Permission Denial: getCurrentUser() from pid=6721, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-31 08:51:47.605  1017  1478 W WifiService: Failed getting userId using ActivityManagerNative
08-31 08:51:47.605  1017  1478 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6721, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:51:47.605  1017  1478 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 08:51:47.605  1017  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 08:51:47.605  1017  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 08:51:47.605  1017  1478 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 08:51:47.605  1017  1478 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 08:51:47.605  1017  1478 D SettingsProvider: name = wifi_on
,08-31 08:51:47.605  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:51:47.605  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@617e395 added. We now have 3 listener(s)
08-31 08:51:47.605  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:47.615  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:51:47.615   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:51:47.615  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39c17caa added. We now have 4 listener(s)
08-31 08:51:47.615  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:47.615  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:51:47.615  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20da109b added. We now have 5 listener(s)
08-31 08:51:47.615  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:47.625  1017  1250 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 08:51:47.625  1017  1250 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 08:51:47.625  1017  1250 D SecContentProvider2: mCursor = null
,08-31 08:51:47.625  1017  1250 D WifiService: setWifiEnabled: false pid=6721, uid=10171
08-31 08:51:47.625  1017  1250 D SettingsProvider: name = wifi_on
,08-31 08:51:47.635  1017  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 08:51:47.635  1355  1355 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 08:51:47.635  1355  1355 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-31 08:51:47.635  1355  1355 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 08:51:47.635  1355  1355 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 08:51:47.635  6721  6775 D BluetoothAdapter: disable()
,08-31 08:51:47.635  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-31 08:51:47.655  1017  1448 D SettingsProvider: name = bluetooth_on
,08-31 08:51:47.655  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:47.665  3189  3287 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-31 08:51:47.665  3189  3287 D BluetoothAdapterProperties: Setting state to 13
08-31 08:51:47.665  3189  3287 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 08:51:47.665  1017  1126 E WifiNative-wlan0: do suspend true
08-31 08:51:47.665  3189  3287 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:51:47.665  3189  3287 D BluetoothAdapterService: updateAdapterState state is 13
,08-31 08:51:47.665  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:47.665  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:47.665  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:47.665  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-31 08:51:47.665  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:47.665  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:47.665  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:47.665  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:47.665  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:47.665  1017  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:47.665  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 08:51:47.665  1017  1561 W ActivityManager: userId = 0, bbcId = -10000,
08-31 08:51:47.665  1017  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:47.665  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:51:47.665  3189  3189 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-31 08:51:47.665  3189  3189 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@38f64f68, channel: 19, state: LISTENING
08-31 08:51:47.665  3189  3189 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@38f64f68, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c774049, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f81af81mSocket: android.net.LocalSocket@2c773826 impl:android.net.LocalSocketImpl@1542ac67 fd:FileDescriptor[74]
,08-31 08:51:47.665  3189  3189 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c773826 impl:android.net.LocalSocketImpl@1542ac67 fd:FileDescriptor[74]
08-31 08:51:47.665  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:47.665  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:47.665  6721  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:51:47.665  3189  3287 D BluetoothAdapterService: Autoconnection is available 
08-31 08:51:47.665  3189  3287 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-31 08:51:47.665  3189  3287 D BluetoothAdapterService: terminating service from this receiver
,08-31 08:51:47.675  1017  4351 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 08:51:47.675  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:47.675  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:47.675  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:47.675  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:47.675  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:47.675  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:47.675  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:47.675  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:47.675  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:47.675  3076  3076 D BluetoothPbap: Proxy object disconnected
08-31 08:51:47.675  1017  4351 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:47.675  3076  3076 D PbapServerProfile: Bluetooth service disconnected
08-31 08:51:47.675  1017  4351 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:47.675  1017  4351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:51:47.675  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:47.675  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:51:47.675  3189  3287 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 08:51:47.675  3189  3287 D BluetoothAdapterProperties: mDiscovering is false
,08-31 08:51:47.675  1017  1448 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-31 08:51:47.675  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:47.675  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-31 08:51:47.685  3189  3287 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-31 08:51:47.685  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:47.685  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-31 08:51:47.695  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 08:51:47.695  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:47.695  1175  1175 D BluetoothTile:  getBluetoothState : 13
,08-31 08:51:47.695  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:51:47.695  1872  1872 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:51:47.695  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:51:47.695  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 08:51:47.695  3076  3076 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:51:47.705  1017  1250 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:51:47.705  1017  1100 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 08:51:47.705  1017  3167 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 08:51:47.705  1017  3167 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 08:51:47.705  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:47.705  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:47.705  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:47.705  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:47.705  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:47.705  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:47.705  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:47.705  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:47.705  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:47.705  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:47.705  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:51:47.715  1017  3167 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:47.715  1017  3167 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:47.715  1017  3167 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:47.715  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 08:51:47.715  3189  3290 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 08:51:47.725  3189  3290 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:51:47.725  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:47.725  3189  3189 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f18c2bd, channel: 5, state: LISTENING
08-31 08:51:47.725  3189  3189 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f18c2bd, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2480650, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@140eb0b2mSocket: android.net.LocalSocket@1fc3a803 impl:android.net.LocalSocketImpl@18d1a380 fd:FileDescriptor[76]
08-31 08:51:47.725  3189  3189 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1fc3a803 impl:android.net.LocalSocketImpl@18d1a380 fd:FileDescriptor[76]
,08-31 08:51:47.725  3189  3189 I BtOppRfcommListener: stopping Accept Thread
08-31 08:51:47.725  3189  3189 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2613cdb9, channel: 12, state: LISTENING
08-31 08:51:47.725  3189  3189 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2613cdb9, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22b1728b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@153325femSocket: android.net.LocalSocket@3ccec15f impl:android.net.LocalSocketImpl@116d77ac fd:FileDescriptor[80]
08-31 08:51:47.725  3189  3189 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ccec15f impl:android.net.LocalSocketImpl@116d77ac fd:FileDescriptor[80]
08-31 08:51:47.725  3189  5209 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 08:51:47.725  3189  5209 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 08:51:47.725  3189  3287 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 08:51:47.725  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:47.725  3189  3287 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-31 08:51:47.725  3189  3287 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-31 08:51:47.725  3189  3287 E bt-btif : cmd socket is not created
08-31 08:51:47.725  3189  3189 V BluetoothOppManager: cleanUp...
,08-31 08:51:47.735  3189  3287 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 08:51:47.735  3189  3315 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-31 08:51:47.735  3189  3315 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-31 08:51:47.735  3189  3315 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:51:47.735  3189  3315 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:51:47.735  3189  3315 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 08:51:47.735  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:47.735  3076  3076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:51:47.745  1017  4347 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 08:51:47.745  1017  4347 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 08:51:47.745  1017  4347 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:47.745  1017  4347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:47.745  1017  4347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:51:47.755  3076  3076 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:51:47.775  3076  3076 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:51:47.775  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:47.775  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 08:51:47.775  1017  1569 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-31 08:51:47.775  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:47.775  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:47.775  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:47.775  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:47.795  6937  6937 E Zygote  : MountEmulatedStorage(),
08-31 08:51:47.795  6937  6937 I libpersona: KNOX_SDCARD checking this for 10055
08-31 08:51:47.795  6937  6937 E Zygote  : v2,
08-31 08:51:47.795  6937  6937 I libpersona: KNOX_SDCARD not a persona
08-31 08:51:47.795  6937  6937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:51:47.795  1017  1569 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6937 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-31 08:51:47.795  6937  6937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:47.795  6937  6937 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:51:47.825  6937  6937 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:47.825  6937  6937 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:47.865  6937  6937 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 08:51:47.875  4271  4354 I art     : Explicit concurrent mark sweep GC freed 1558(54KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 669us total 24.065ms
,08-31 08:51:47.895  6937  6937 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-31 08:51:47.905  6937  6937 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-31 08:51:47.905  6937  6937 D UserAnalysis: Create SecureDbHelper
,08-31 08:51:47.905  6937  6937 D IntelligenceServiceApplication: onCreate()
,08-31 08:51:47.915  1017  4351 I ActivityManager: Killing 6427:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-31 08:51:47.925  6937  6937 D IntelligenceServiceApplication: no applications having user consent for prediction
08-31 08:51:47.925  1017  4347 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-31 08:51:47.935  6937  6937 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-31 08:51:47.935  1017  4347 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 08:51:47.935  3189  3315 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:51:47.935  3189  3315 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:51:47.935  3189  3315 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:51:47.935  3189  3315 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 08:51:47.935  3189  3315 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:51:47.935  3189  3315 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:51:47.935  3189  3315 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:51:47.935  3189  3315 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:51:47.935  3189  3315 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:51:47.935  3189  3315 W bt-btif : ag scb idx 1 not allocated
,08-31 08:51:47.935  3189  3315 W bt-btif : ag scb idx 2 not allocated
08-31 08:51:47.935  3189  3315 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 08:51:47.935  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:47.935  3189  3352 I bt_userial_mct: exiting userial_read_thread
08-31 08:51:47.935  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:47.935  3189  3352 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 08:51:47.935  3189  3290 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 08:51:47.935  3189  3317 I bt_vendor: hw_epilog_process
,08-31 08:51:47.935  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:47.935  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:47.935  3189  3290 D bt_userial_mct: userial_close
08-31 08:51:47.935  3189  3290 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-31 08:51:47.945  6937  6937 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 08:51:47.945  6958  6958 E Zygote  : MountEmulatedStorage()
08-31 08:51:47.945  6958  6958 E Zygote  : v2
08-31 08:51:47.945  6958  6958 I libpersona: KNOX_SDCARD checking this for 10105
08-31 08:51:47.945  6958  6958 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:47.955  1017  4347 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6958 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-31 08:51:47.955  6958  6958 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 08:51:47.955  6958  6958 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:51:47.955  6958  6958 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:51:47.975  6958  6958 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:47.975  6958  6958 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:48.055  6721  6721 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 08:51:48.105   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 08:51:48.105   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:48.105  6958  6975 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 08:51:48.105   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 08:51:48.105   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:48.105  6958  6975 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 08:51:48.235  1355  1355 I wpa_supplicant: nl80211: Received scan results (12 BSSes)
,08-31 08:51:48.235  6980  6980 I dex2oat : ----------------------------------------------------
08-31 08:51:48.235  6980  6980 I dex2oat : <SS>: S T A R T I N G . . .
08-31 08:51:48.235  6980  6980 I dex2oat : <SS>: Zip is absent. Canceled.
08-31 08:51:48.245  6980  6980 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-31 08:51:48.245  1017  1125 D WifiP2pService: InactiveState{ what=147461 }
08-31 08:51:48.245  1017  1125 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-31 08:51:48.245  1017  1125 D WifiP2pService: DefaultState{ what=147461 }
,08-31 08:51:48.255  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-31 08:51:48.255  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 08:51:48.255   278   977 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:51:48.255  2003  3025 V NativeCrypto: Read error: ssl=0xb8ad1668: I/O error during system call, Connection timed out,
08-31 08:51:48.255  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 08:51:48.265  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:51:48.265  1017  1128 E ConnectivityService: updateNetworkInfo(),
08-31 08:51:48.265  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-31 08:51:48.265  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 08:51:48.265  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:51:48.265  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 08:51:48.265  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.265  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.265  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 08:51:48.265  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.265  2003  3025 V NativeCrypto: SSL shutdown failed: ssl=0xb8ad1668: I/O error during system call, Broken pipe
,08-31 08:51:48.265  2003  3025 E GCM     : Wifi connection closed with errorCode 20
,08-31 08:51:48.265  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
08-31 08:51:48.275  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-31 08:51:48.275  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 08:51:48.275  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-31 08:51:48.275  1017  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:51:48.275  1017  1150 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:51:48.275  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:51:48.275  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 08:51:48.275  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.275  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.275  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.275  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:51:48.275  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
,08-31 08:51:48.285  1017  4347 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-31 08:51:48.285  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-31 08:51:48.285  3189  3290 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
08-31 08:51:48.285  3189  3290 I bt_vendor: bluetooth satus is on
08-31 08:51:48.285  3189  3290 I bt_vendor: bt-vendor : resetting BT status
08-31 08:51:48.285  3189  3290 I bt_vendor: Starting hciattach daemon
,08-31 08:51:48.285  3189  3290 I bt_vendor: try to set false
,08-31 08:51:48.285  3189  3290 I bt_vendor: Starting hciattach daemon
,08-31 08:51:48.295  3189  3290 I bt_vendor: try to set false,
08-31 08:51:48.295  1017  1749 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-6ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:48.295  1017  1749 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-6ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:51:48.295  1017  1749 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 08:51:48.295  1017  1749 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:48.295  1017  1749 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-31 08:51:48.295  1017  1749 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 08:51:48.295  1017  1749 I qtaguid : Tagging socket 346 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,08-31 08:51:48.295  3189  3290 I bt_vendor: cleanup
08-31 08:51:48.295  1017  1749 I qtaguid : Untagging socket 346
,08-31 08:51:48.295  3189  3315 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 08:51:48.295  1017  1749 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 08:51:48.295  3189  3290 I GKI_LINUX: GKI_exit_task 0 done
,08-31 08:51:48.305  3189  3290 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-31 08:51:48.315  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-31 08:51:48.315  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-31 08:51:48.325  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 08:51:48.335  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 08:51:48.335  1017  1125 D WifiP2pService: P2pDisablingState
08-31 08:51:48.335  3189  3287 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 08:51:48.335  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-31 08:51:48.335  3189  3287 D BtConfig.SecureMode: isSecureModeOn:false
08-31 08:51:48.335  1017  1125 D WifiP2pService: p2p socket connection lost
08-31 08:51:48.335  3189  3287 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-31 08:51:48.335  1017  1125 D WifiP2pService: P2pDisabledState
08-31 08:51:48.335  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 08:51:48.335  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 08:51:48.335  3189  3287 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-31 08:51:48.335  1017  1126 E WifiNative-wlan0: do suspend true
,08-31 08:51:48.345  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:48.345  1017  1448 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:48.345  1017  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:48.345  1017  1448 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-31 08:51:48.345  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:51:48.345  1017  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:48.345  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 08:51:48.345  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 08:51:48.345  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 08:51:48.345  3189  3287 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 08:51:48.345  3189  3189 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 08:51:48.345  3189  3189 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 08:51:48.345  3189  3189 D BtGatt.GattService: stop()
08-31 08:51:48.345  3189  3189 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 08:51:48.345  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
08-31 08:51:48.345  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-31 08:51:48.345  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:48.345  1017  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:48.345  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:48.345  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 08:51:48.345  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 08:51:48.355  3189  3287 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 08:51:48.355  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 08:51:48.355  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 08:51:48.355  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-31 08:51:48.355  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:51:48.355  1017  1047 D WifiDisplayController: disconnect
08-31 08:51:48.355  1017  1047 D WifiDisplayController: updateConnection
08-31 08:51:48.355  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-31 08:51:48.355  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-31 08:51:48.355  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-31 08:51:48.355  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 08:51:48.355  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 08:51:48.355  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 08:51:48.355  1017  3167 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:48.355  1017  3167 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:51:48.355  1017  3167 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:48.355  1017  3167 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:48.355  1017  3167 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:51:48.355  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:51:48.355  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:51:48.355  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.355  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.355  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.355  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.365  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 08:51:48.365  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 08:51:48.365  3189  3287 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-31 08:51:48.365  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:48.375  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:48.375  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-31 08:51:48.375  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 08:51:48.375  1017  1366 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-31 08:51:48.375  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 08:51:48.385  1017  1029 W ActivityManager: userId = 0, bbcId = -10000,
08-31 08:51:48.385  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:48.385  1017  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:48.385  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:48.385  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-31 08:51:48.385  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 08:51:48.385  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService,
08-31 08:51:48.385  3189  3287 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-31 08:51:48.385  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-31 08:51:48.385  3189  3189 D HeadsetService: Received stop request...Stopping profile...
08-31 08:51:48.385  1017  1128 V NetworkStats: updateIfacesLocked()
08-31 08:51:48.385  6980  6980 I dex2oat : dex2oat took 147.103ms (threads: 4),
08-31 08:51:48.385  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:51:48.385   278   977 D CommandListener: Clearing all IP addresses on wlan0
08-31 08:51:48.385   278   973 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:51:48.385   278   973 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-31 08:51:48.385  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:48.385  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:51:48.385  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:51:48.395  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:48.395  1017  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:48.395  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:48.395  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 08:51:48.395  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 08:51:48.395  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:48.395  1355  1355 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-31 08:51:48.395  3189  3287 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 08:51:48.395  1017  1749 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-31 08:51:48.405  1017  1749 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-31 08:51:48.405  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 08:51:48.405  1017  1128 V NetworkStats: performPollLocked() took 19ms
,08-31 08:51:48.405  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:48.415  1017  1569 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:51:48.415  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 08:51:48.415  1017  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:51:48.415  3076  3076 D HeadsetProfile: Bluetooth service disconnected
,08-31 08:51:48.415  3189  3189 D A2dpService: Received stop request...Stopping profile...
,08-31 08:51:48.415  1017  1569 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:48.415  1017  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:48.415  1017  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:48.415  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 08:51:48.415  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 08:51:48.415  1175  1197 W art     : Suspending all threads took: 7.011ms
,08-31 08:51:48.415  3189  3287 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 08:51:48.415  3189  3305 D A2dpStateMachine: Exit Disconnected: -1
,08-31 08:51:48.425  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 08:51:48.425  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:51:48.425  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:51:48.425  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:51:48.425  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.425  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.425  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.425  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.425  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:51:48.425  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:51:48.425  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.425  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.425  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.425  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.425  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:51:48.425  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-31 08:51:48.425  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:48.425  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 08:51:48.425  1175  1175 D HotspotTile: onReceive : 0, 0
,08-31 08:51:48.435  3076  3076 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:48.435  6901  6909 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 08:51:48.435  6901  6909 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 08:51:48.435  6901  6909 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 08:51:48.435  6901  6909 I Adreno-EGL: Local Branch: 
08-31 08:51:48.435  6901  6909 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 08:51:48.435  6901  6909 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 08:51:48.435  6901  6909 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 08:51:48.435  1175  1197 I art     : Background partial concurrent mark sweep GC freed 3944(247KB) AllocSpace objects, 7(6MB) LOS objects, 40% free, 17MB/28MB, paused 13.293ms total 74.364ms
,08-31 08:51:48.435  1017  4347 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:48.435  1017  4347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 08:51:48.435  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-31 08:51:48.435  1175  1675 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 08:51:48.435  1017  1749 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:51:48.435  1017  4347 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:48.435  1017  4347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:48.435  1017  4347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:48.445  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-31 08:51:48.445  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 08:51:48.445  1017  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 08:51:48.445  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-31 08:51:48.445  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-31 08:51:48.445  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 08:51:48.445  1017  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-31 08:51:48.445  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-31 08:51:48.445  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 08:51:48.445  4777  6783 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-31 08:51:48.445  3189  3287 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 08:51:48.445  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:48.445  1458  1458 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-31 08:51:48.455  1458  1458 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 08:51:48.455  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:48.455  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:48.455  1017  1250 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:51:48.455  1017  1250 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-31 08:51:48.455  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:48.455  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:48.455  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:48.455  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:48.455  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:48.455  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:48.455  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:48.455  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:48.455  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:48.455  1017  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:48.455  1017  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:48.455  1017  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:48.465  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:51:48.465  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:51:48.465  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 08:51:48.465  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-31 08:51:48.465  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 08:51:48.465  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:51:48.465  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 08:51:48.465  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-31 08:51:48.475  3076  3076 D BluetoothA2dp: Proxy object disconnected
,08-31 08:51:48.475  3076  3076 D A2dpProfile: Bluetooth service disconnected
,08-31 08:51:48.475  3189  3287 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:51:48.475  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:51:48.475  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:51:48.475  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:51:48.475  3189  3287 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:51:48.475  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 08:51:48.475  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 08:51:48.475  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:51:48.485  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-31 08:51:48.485  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 08:51:48.485  3189  3287 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-31 08:51:48.485  3189  3287 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 08:51:48.485  3189  3287 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 08:51:48.485  3189  3287 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService,
08-31 08:51:48.485  3189  3287 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 08:51:48.485  3189  3189 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-31 08:51:48.485  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-31 08:51:48.485  1017  1130 D Tethering: MasterInitialState.processMessage what=3
,08-31 08:51:48.485  3189  3189 D HidService: Received stop request...Stopping profile...
,08-31 08:51:48.485  3189  3189 D HidService: Stopping Bluetooth HidService
,08-31 08:51:48.485  3189  3189 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 08:51:48.485  3189  3189 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 08:51:48.485  3189  3189 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-31 08:51:48.485  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:48.495  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:51:48.495  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:48.495  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:48.495  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:48.495  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:48.495  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:48.495  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:48.495  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:48.495  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:51:48.495  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:51:48.495  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:51:48.495  3189  3189 D HealthService: Received stop request...Stopping profile...
,08-31 08:51:48.505  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
08-31 08:51:48.505  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-31 08:51:48.505  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 08:51:48.505  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-31 08:51:48.505  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 08:51:48.505  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 08:51:48.505  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:48.505  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 08:51:48.505  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:48.505  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:48.505  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:48.505  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1,
,08-31 08:51:48.505  3189  3189 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-31 08:51:48.505  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 08:51:48.505  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 08:51:48.515  1355  1355 I wpa_supplicant: Blacklist: Clear (all) 
08-31 08:51:48.515  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-31 08:51:48.515  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-31 08:51:48.515  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-31 08:51:48.515  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:51:48.515  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:51:48.515  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.515  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.515  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:51:48.515  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:51:48.515  3189  3189 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-31 08:51:48.515  3189  3189 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 08:51:48.515  3189  3189 D PanService: Received stop request...Stopping profile...
08-31 08:51:48.515  1017  1123 V NetworkStats: updateIfacesLocked()
08-31 08:51:48.515  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:48.515  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-31 08:51:48.515  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:48.525  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:51:48.525  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:51:48.525  1017  1123 V NetworkStats: performPollLocked() took 4ms
08-31 08:51:48.525  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:48.525  3076  3076 D BluetoothInputDevice: Proxy object disconnected
08-31 08:51:48.525  3076  3076 D HidProfile: Bluetooth service disconnected
,08-31 08:51:48.525  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 08:51:48.525  3076  3076 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 08:51:48.525  3076  3076 D PanProfile: Bluetooth service disconnected
08-31 08:51:48.525  3189  3189 D BluetoothMapService: Received stop request...Stopping profile...
,08-31 08:51:48.525  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:48.525  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:48.525  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:48.535  3189  3189 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-31 08:51:48.535  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:51:48.535  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 08:51:48.535  3189  3189 D BluetoothA2dp: Proxy object disconnected
08-31 08:51:48.535  3189  3189 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-31 08:51:48.535  3189  3189 D SapService: Received stop request...Stopping profile...
,08-31 08:51:48.535  3189  3189 D SapService: Stopping Bluetooth SapService,
08-31 08:51:48.535  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
08-31 08:51:48.535  3076  3076 D BluetoothMap: Proxy object disconnected
08-31 08:51:48.535  3076  3076 D MapProfile: Bluetooth service disconnected
,08-31 08:51:48.535  3076  3076 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 08:51:48.535  3076  3076 D SapProfile: Bluetooth service disconnected
,08-31 08:51:48.535  3189  3307 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 08:51:48.535  3189  3189 I GKI_LINUX: GKI_exit_task 2 done
08-31 08:51:48.535  3189  3189 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-31 08:51:48.535  3189  3189 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 08:51:48.535  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:51:48.535  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 08:51:48.535  3189  3189 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-31 08:51:48.535  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:51:48.535  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 08:51:48.535  3189  3189 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 08:51:48.535  3189  3189 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 08:51:48.535  3189  3189 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 08:51:48.535  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 08:51:48.535  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 08:51:48.535  3189  3189 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 08:51:48.535  3189  3189 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 08:51:48.535  3189  3189 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-31 08:51:48.535  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 08:51:48.535  3189  3189 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-31 08:51:48.535  3189  3189 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true,
08-31 08:51:48.535  6901  6909 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 08:51:48.535  6901  6909 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 08:51:48.535  6901  6909 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 08:51:48.535  6901  6909 I Adreno-EGL: Local Branch: 
08-31 08:51:48.535  6901  6909 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 08:51:48.535  6901  6909 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 08:51:48.535  6901  6909 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-31 08:51:48.545  3189  3189 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-31 08:51:48.545  3189  3189 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-31 08:51:48.555  1355  1355 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 08:51:48.555  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 08:51:48.555  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-31 08:51:48.555  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:51:48.565  3189  3287 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-31 08:51:48.565  3189  3287 D BluetoothAdapterProperties: Setting state to 10
,08-31 08:51:48.565  3189  3287 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 08:51:48.565  3189  3287 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:51:48.565  2003  2003 I art     : Explicit concurrent mark sweep GC freed 84565(4MB) AllocSpace objects, 20(775KB) LOS objects, 39% free, 11MB/18MB, paused 1.871ms total 141.707ms
,08-31 08:51:48.565  3189  3287 D BluetoothAdapterService: updateAdapterState state is 10
,08-31 08:51:48.575  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:51:48.575  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-31 08:51:48.575  1355  1355 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-31 08:51:48.575  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:51:48.575  1355  1355 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-31 08:51:48.575  1355  1355 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 08:51:48.575  1355  1355 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-31 08:51:48.575  1355  1355 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 08:51:48.575  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:51:48.575  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:51:48.575  1017  1130 D Tethering: InitialState.processMessage what=4
,08-31 08:51:48.585  6901  6909 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 08:51:48.585  6901  6909 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 08:51:48.585  6901  6909 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 08:51:48.585  6901  6909 I Adreno-EGL: Local Branch: 
08-31 08:51:48.585  6901  6909 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 08:51:48.585  6901  6909 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 08:51:48.585  6901  6909 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 08:51:48.605  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:48.605  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:48.605  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:48.605  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:51:48.605  3189  3287 D BluetoothAdapterService: Autoconnection is available 
08-31 08:51:48.605  3189  3287 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-31 08:51:48.605  3189  3287 I BluetoothAdapterState: Entering OffState
08-31 08:51:48.605  1175  4438 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:51:48.605  1175  4438 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:51:48.605  1017  1130 E Tethering: No numeric data
08-31 08:51:48.605  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:51:48.605  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:51:48.605   291   291 E SMD     : DCD OFF
,08-31 08:51:48.605  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 08:51:48.605  1017  1130 D Tethering: clearTetheredNotification()
,08-31 08:51:48.615  2003  2163 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:51:48.615  2003  2163 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:51:48.615  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 08:51:48.615  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 08:51:48.615  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:51:48.615  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:51:48.615  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 08:51:48.615  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:51:48.615  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:51:48.615   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:51:48.625  1442  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:51:48.625  1442  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:51:48.625  3076  3087 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:51:48.625  3076  3087 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:51:48.625  1429  1450 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:51:48.625  1429  1450 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:51:48.635   269   269 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb71fe7c8
08-31 08:51:48.635   269   269 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-31 08:51:48.635   269   269 I rmt_storage: wakelock acquired: 1, error no: 42
08-31 08:51:48.635   269   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1222646472)
08-31 08:51:48.635  3076  3087 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 08:51:48.635  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:51:48.635  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:51:48.635  3076  3084 D Bluetoothsap: onBluetoothStateChange: up=false
08-31 08:51:48.635  3076  3084 D Bluetoothsap: Unbinding service...
,08-31 08:51:48.635  3189  6933 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:51:48.635  3189  6933 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:51:48.635  1458  1689 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:51:48.635  1458  1689 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:51:48.635  3076  3087 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 08:51:48.635  3076  3084 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 08:51:48.645  3076  3084 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 08:51:48.645  6721  6735 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:51:48.645  6721  6735 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:51:48.645  6721  6735 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-31 08:51:48.645  6721  6735 D BluetoothLeAdvertiser: Exit stop advertising
08-31 08:51:48.645  6721  6735 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-31 08:51:48.645  6721  6735 D BluetoothLeScanner: Exiting stopAllScan
08-31 08:51:48.645  3189  3197 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 08:51:48.645  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-31 08:51:48.665  6958  6958 D StrictMode: StrictMode policy violation; ~duration=552 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:48.665  6958  6958 D StrictMode: StrictMode policy violation; ~duration=551 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:48.665  6958  6958 D StrictMode: StrictMode policy violation; ~duration=551 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:48.665  6958  6958 D StrictMode: StrictMode policy violation; ~duration=550 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:48.665  6958  6958 D StrictMode: StrictMode policy violation; ~duration=546 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:48.665  6958  6958 D StrictMode: StrictMode policy violation; ~duration=519 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:48.665  6958  6958 D StrictMode: StrictMode policy violation; ~duration=518 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:48.665  6958  6958 D StrictMode: StrictMode policy violation; ~duration=517 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:48.665  6958  6958 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:48.685  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-31 08:51:48.695  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:48.695  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 08:51:48.695  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:51:48.695  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:51:48.695  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:51:48.695  1175  1175 D HotspotTile: updateTetherState():false, false
08-31 08:51:48.695  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:48.695  1017  1123 V NetworkStats: performPollLocked() took 5ms
08-31 08:51:48.705   269   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-31 08:51:48.705   269   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-31 08:51:48.705   269   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1222646472) wakelock released: 1, error no: 0
08-31 08:51:48.705   269   313 I rmt_storage: 
08-31 08:51:48.705   269   269 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb71fe7c8
,08-31 08:51:48.725  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:48.725  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:48.735  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:48.735  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-31 08:51:48.735  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-31 08:51:48.735  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-31 08:51:48.745  1175  1175 D BluetoothAdapter: 765140552: getState() :  mService = null. Returning STATE_OFF
08-31 08:51:48.745  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 08:51:48.745  1175  1722 D BluetoothAdapter: 765140552: getState() :  mService = null. Returning STATE_OFF
08-31 08:51:48.745  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:48.745  1175  1722 D BluetoothAdapter: 765140552: getState() :  mService = null. Returning STATE_OFF
08-31 08:51:48.745  1175  1175 D BluetoothTile:  getBluetoothState : 10
08-31 08:51:48.755  1175  1175 D BluetoothAdapter: 765140552: getState() :  mService = null. Returning STATE_OFF
08-31 08:51:48.755  1175  1175 D BluetoothAdapter: 765140552: getState() :  mService = null. Returning STATE_OFF
08-31 08:51:48.755  1017  4350 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:51:48.755  1017  1486 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 08:51:48.755  2003  2168 D BluetoothAdapter: 216578660: getState() :  mService = null. Returning STATE_OFF
08-31 08:51:48.755  1872  1872 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:51:48.755  2003  2168 D BluetoothAdapter: 216578660: getState() :  mService = null. Returning STATE_OFF
,08-31 08:51:48.765  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:48.765  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:48.765  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:48.765  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:48.765  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:48.765  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:48.765  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:48.765  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:48.765  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:51:48.765  1017  1448 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 08:51:48.765  1017  1448 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 08:51:48.765  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 08:51:48.765  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:48.765  1017  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:48.765  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:48.765  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:48.765  3076  3076 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:51:48.765  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 08:51:48.785  1355  1355 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 08:51:48.785  1017  3167 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:51:48.785  1017  3167 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:51:48.785  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.785  1017  3167 W ActivityManager: userId = 0, bbcId = -10000,
08-31 08:51:48.785  1017  3167 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:48.785  1017  3167 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:51:48.795  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.795  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.795  1606  1606 I Hs20UtilService: Starting #8
,08-31 08:51:48.805  1606  1643 I Hs20UtilService: Message received 5007
,08-31 08:51:48.805  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 08:51:48.815  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.815  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.815  3189  3290 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 08:51:48.815  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.815  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.815  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 08:51:48.825  1355  1355 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 08:51:48.825  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:51:48.825  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:51:48.825  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:51:48.825  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.835  3076  3076 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 08:51:48.835  3189  3189 I GKI_LINUX: GKI_exit_task 1 done
08-31 08:51:48.835  3189  3189 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 08:51:48.835  3189  3189 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 08:51:48.835  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-31 08:51:48.835  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 08:51:48.835  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.835  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.835  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 08:51:48.835  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 08:51:48.835  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:51:48.835  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:51:48.835  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.835  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.835  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:51:48.835  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:48.835  3189  3189 I art     : System.exit called, status: 0
08-31 08:51:48.845  3189  3189 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 08:51:48.845  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:51:48.845  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-31 08:51:48.845  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:48.845  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 08:51:48.845  1175  1175 D HotspotTile: onReceive : 1, 0
,08-31 08:51:48.845  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.845  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 08:51:48.845  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.845  2003  2168 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:51:48.845  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.845  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.845  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:48.845  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.845  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.845  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:48.855  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.855  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.855  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:51:48.855  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:51:48.855  3076  3076 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 08:51:48.855  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 08:51:48.855  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.855  3076  3076 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:48.855  3076  3799 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:51:48.855  6958  6976 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 08:51:48.865  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.865  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.865  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.865  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.875  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.875  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 08:51:48.875  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 08:51:48.885  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 08:51:48.885  3076  3076 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:51:48.885  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:51:48.885  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:51:48.885  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 08:51:48.895  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:48.895  3076  3076 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 08:51:48.895  3076  3799 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:51:48.895  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:48.895  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:48.895  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 08:51:48.895  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-31 08:51:48.895  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:48.895  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:48.895  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:48.895  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:48.905  7023  7023 E Zygote  : MountEmulatedStorage(),
08-31 08:51:48.905  7023  7023 E Zygote  : v2
08-31 08:51:48.905  7023  7023 I libpersona: KNOX_SDCARD checking this for 10064
08-31 08:51:48.905  7023  7023 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:48.915  1017  1030 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7023 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 08:51:48.915  7023  7023 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:48.915  1017  1250 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-31 08:51:48.915  7023  7023 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:48.915  7023  7023 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:51:48.915  1017  1250 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:48.915  1017  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:48.915  1017  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:48.935  1017  3167 I ActivityManager: Process com.android.bluetooth (pid 3189)(adj 0) has died(40,696)
08-31 08:51:48.935  2003  6900 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 08:51:48.935   278   973 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:51:48.935   278   973 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-31 08:51:48.935  7023  7023 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 08:51:48.935  2003  6900 W GLSUser : [AppCertManager] IOException while requesting key: 
,08-31 08:51:48.945  7023  7023 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:48.955  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:51:48.965  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-31 08:51:48.965  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:51:48.975  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:48.975  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:49.005  7023  7023 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 08:51:49.025  7023  7023 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:51:49.025  7023  7023 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 08:51:49.065  7023  7023 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 08:51:49.065  1017  4350 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-31 08:51:49.065  1017  4350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:49.065  1017  4350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:49.065  1017  4350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:49.065  1017  4350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:49.085  7040  7040 E Zygote  : MountEmulatedStorage()
,08-31 08:51:49.085  7040  7040 E Zygote  : v2
08-31 08:51:49.085  7040  7040 I libpersona: KNOX_SDCARD checking this for 10065
08-31 08:51:49.085  7040  7040 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:49.085  7040  7040 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:49.085  1017  4350 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7040 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 08:51:49.085  7040  7040 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 08:51:49.085  1017  4350 I ActivityManager: Killing 6454:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-31 08:51:49.085  7040  7040 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:51:49.115   286  1600 I WVCdm   : CdmEngine::CloseSession
,08-31 08:51:49.115  7040  7040 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:49.125  7040  7040 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:49.125   286  1600 I WVCdm   : L3 Terminate.
,08-31 08:51:49.145  7040  7040 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:51:49.155  1017  4351 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.155  1017  4351 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:49.155  1017  4351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-31 08:51:49.155  1017  4351 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-31 08:51:49.155  1017  4351 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:49.155  1017  4351 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:49.155  1017  4351 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:49.155  1017  4351 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:49.175  7057  7057 E Zygote  : MountEmulatedStorage()
,08-31 08:51:49.175  7057  7057 E Zygote  : v2
08-31 08:51:49.175  7057  7057 I libpersona: KNOX_SDCARD checking this for 10102
08-31 08:51:49.175  7057  7057 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:49.175  7057  7057 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:51:49.175  1017  4351 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7057 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 08:51:49.175  1017  4351 I ActivityManager: Killing 6484:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-31 08:51:49.185  7057  7057 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:49.185  7057  7057 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:51:49.205  7057  7057 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:49.205  7057  7057 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:49.225  7057  7057 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 08:51:49.315  1017  4350 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-31 08:51:49.325  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:49.325  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.325  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:49.325  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:49.335  1017  1044 D Tethering: interfaceRemoved wlan0
08-31 08:51:49.335  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 08:51:49.345  1017  1561 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:49.345  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.345  1017  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:49.345  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:49.395  2003  2003 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=5a2e6d0d-ea2a-4d68-9b3b-a74181f9732f
,08-31 08:51:49.395  1017  4350 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-31 08:51:49.395  1017  4350 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 08:51:49.395  1017  4350 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.395  1017  4350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:49.395  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:49.405  1017  1044 D Tethering: interfaceRemoved p2p0
08-31 08:51:49.405  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 08:51:49.485  2003  2156 W GCoreFlp: No location to return for getLastLocation()
,08-31 08:51:49.495  7057  7079 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-31 08:51:49.505  7057  7079 I Babel_SMS: MmsConfig.loadMmsSettings
08-31 08:51:49.505  7057  7079 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-31 08:51:49.505  7057  7079 I Babel_SMS: MmsConfig.loadFromDatabase
,08-31 08:51:49.525  7057  7079 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-31 08:51:49.525  7057  7079 I Babel_SMS: MmsConfig.loadFromResources
,08-31 08:51:49.525  7057  7079 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 08:51:49.525  7057  7079 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-31 08:51:49.625   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:51:49.655  1017  3167 I art     : Explicit concurrent mark sweep GC freed 51619(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 2.593ms total 161.106ms
,08-31 08:51:49.675  2003  2159 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 08:51:49.675  2003  2169 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-31 08:51:49.685  4777  7000 D UdcContextInitService: registered all accounts: true
,08-31 08:51:49.685  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:49.685  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.685  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:49.685  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:49.695  1017  4350 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-31 08:51:49.695  1017  4350 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-31 08:51:49.695  1017  4350 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.695  1017  4350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:49.695  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 08:51:49.695  1017  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:49.695  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.695  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:49.695  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:49.705  1017  1250 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:49.705  1017  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.705  1017  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:49.705  1017  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:49.715  7057  7057 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:51:49.715  7057  7057 I Babel_Crash: startup - clean
,08-31 08:51:49.745  2003  2169 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-31 08:51:49.765  1017  1448 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:51:49.765  1017  1448 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:51:49.765  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.765  1017  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.765  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:51:49.775  1606  1606 I Hs20UtilService: Starting #9
,08-31 08:51:49.775  1606  1643 I Hs20UtilService: Message received 5007
,08-31 08:51:49.775  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 08:51:49.775  3076  3076 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:51:49.785  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:51:49.785  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 08:51:49.785  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:51:49.785  3076  3076 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 08:51:49.785  3076  3799 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:51:49.785  7057  7057 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:51:49.785  7057  7057 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 08:51:49.785  7057  7057 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 08:51:49.795  1017  1366 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:51:49.795  1017  1366 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:51:49.795  1017  1366 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.795  1017  1366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.795  1017  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:51:49.795  1606  1606 I Hs20UtilService: Starting #10
,08-31 08:51:49.795  1606  1643 I Hs20UtilService: Message received 5011
,08-31 08:51:49.805  7057  7057 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-31 08:51:49.805  2003  2169 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,08-31 08:51:49.805  7057  7057 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-31 08:51:49.805  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 08:51:49.805  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 08:51:49.805  6523  6523 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 08:51:49.805  6523  6523 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:51:49.815  7057  7057 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-31 08:51:49.825  7057  7057 W AudioCapabilities: Unsupported mime audio/x-ima
,08-31 08:51:49.825  7057  7057 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 08:51:49.825  7057  7057 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 08:51:49.825  1017  1029 I ActivityManager: Killing 6504:com.samsung.android.sm/1000 (adj 15): empty #21
,08-31 08:51:49.825  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.825  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.825  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.835  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.835  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.835  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.835  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.835  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.835  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.845  1017  1366 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 08:51:49.845  1017  1366 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-31 08:51:49.845  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.845  1017  1366 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 08:51:49.845  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:51:49.845  1017  1366 D BatteryService: stay LED for fully charged
08-31 08:51:49.845  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.845  7057  7057 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 08:51:49.845  7057  7057 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 08:51:49.845  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 08:51:49.855  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 08:51:49.855  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 08:51:49.855  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 08:51:49.855  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 08:51:49.865  7057  7057 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-31 08:51:49.865  7057  7057 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 08:51:49.865  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.865  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:51:49.865  7057  7057 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-31 08:51:49.865  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.865  7057  7057 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-31 08:51:49.865  7057  7057 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-31 08:51:49.875  1017  1017 I MotionRecognitionService: Plugged
,08-31 08:51:49.875  7057  7057 W VideoCapabilities: Unsupported mime video/mp43
08-31 08:51:49.875  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 08:51:49.875  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.875  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.875  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.875  7057  7057 W VideoCapabilities: Unsupported mime video/sorenson
,08-31 08:51:49.875  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.875  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.875  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.875  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 08:51:49.885  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 08:51:49.885  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 08:51:49.885  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 08:51:49.885  1175  1175 D SViewCoverView: level :100 plugged : 2
,08-31 08:51:49.885  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.885  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.885  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.885  7057  7057 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-31 08:51:49.885  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.885  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.885  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.895  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:49.895  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.895  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.895  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.895  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.895  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.905  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.905  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.905  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.905  7057  7057 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 08:51:49.905  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.905  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.905  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:49.915  3076  3076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:51:49.915  1017  1567 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 08:51:49.915  1017  1567 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 08:51:49.915  1017  1567 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:49.915  1017  1567 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:49.915  1017  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:51:49.925  3076  3076 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:51:49.925  3076  3076 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:51:49.935  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:49.935  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 08:51:49.935  1017  3167 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-31 08:51:49.935  1017  3167 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:49.935  1017  3167 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:49.935  1017  3167 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:49.935  1017  3167 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:49.945  7057  7057 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:51:49.945  7057  7057 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:51:49.945  7057  7057 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:51:49.955  7057  7057 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:51:49.955  1017  3167 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7085 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-31 08:51:49.955  7085  7085 E Zygote  : MountEmulatedStorage()
08-31 08:51:49.955  7085  7085 I libpersona: KNOX_SDCARD checking this for 1002
08-31 08:51:49.955  7085  7085 E Zygote  : v2
08-31 08:51:49.955  7085  7085 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:49.955  7085  7085 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:51:49.955  1017  1100 I ActivityManager: Killing 6556:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-31 08:51:49.955  7057  7057 I vclib   : onServiceConnected
,08-31 08:51:49.965  7085  7085 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:49.965  7085  7085 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:51:49.985  7085  7085 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:49.985  7085  7085 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:49.995  7085  7085 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 08:51:49.995  7085  7085 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 08:51:50.025  7085  7085 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 08:51:50.055  7085  7085 D BtSettings.ProfileConfig: Adding GattService
,08-31 08:51:50.055  7085  7085 D BtSettings.ProfileConfig: Adding HeadsetService
,08-31 08:51:50.055  7085  7085 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 08:51:50.055  7085  7085 D BtSettings.ProfileConfig: Adding HidService
,08-31 08:51:50.055  7085  7085 D BtSettings.ProfileConfig: Adding HealthService
,08-31 08:51:50.055  7085  7085 D BtSettings.ProfileConfig: Adding PanService
,08-31 08:51:50.055  7085  7085 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-31 08:51:50.065  7085  7085 D BtSettings.ProfileConfig: Adding SapService
,08-31 08:51:50.065  7085  7085 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-31 08:51:50.065  7085  7085 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-31 08:51:50.065  7085  7085 D BtSettings.ProfileConfig: Adding SapClientService
,08-31 08:51:50.065  7085  7085 D BtSettings.ProfileConfig: Adding HidDevService
,08-31 08:51:50.065  7085  7085 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 08:51:50.065  1017  1366 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-31 08:51:50.065  1017  1366 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.065  1017  1366 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.065  1017  1366 D SettingsProvider: selectionArgs: false
08-31 08:51:50.065  1017  1366 D SettingsProvider: selectionArgs: 1002
08-31 08:51:50.065  1017  1366 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:50.065  1017  1366 D SettingsProvider: ret = -1
,08-31 08:51:50.065  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-31 08:51:50.065  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.065  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.065  1017  1029 D SettingsProvider: selectionArgs: false
,08-31 08:51:50.065  1017  1029 D SettingsProvider: selectionArgs: 1002
,08-31 08:51:50.065  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:50.065  1017  1029 D SettingsProvider: ret = -1
,08-31 08:51:50.075  1017  4347 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 08:51:50.075  1017  4347 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.075  1017  4347 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.075  1017  4347 D SettingsProvider: selectionArgs: false
08-31 08:51:50.075  1017  4347 D SettingsProvider: selectionArgs: 1002
08-31 08:51:50.075  1017  4347 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:50.075  1017  4347 D SettingsProvider: ret = -1
,08-31 08:51:50.075  1017  1486 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 08:51:50.075  1017  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.075  1017  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.075  1017  1486 D SettingsProvider: selectionArgs: false
08-31 08:51:50.075  1017  1486 D SettingsProvider: selectionArgs: 1002
08-31 08:51:50.075  1017  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:50.075  1017  1486 D SettingsProvider: ret = -1
,08-31 08:51:50.075  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 08:51:50.075  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.075  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.075  1017  1030 D SettingsProvider: selectionArgs: false
08-31 08:51:50.075  1017  1030 D SettingsProvider: selectionArgs: 1002
,08-31 08:51:50.075  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:50.075  1017  1030 D SettingsProvider: ret = -1
,08-31 08:51:50.075  1017  1567 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 08:51:50.075  1017  1567 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.075  1017  1567 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.075  1017  1567 D SettingsProvider: selectionArgs: false
08-31 08:51:50.075  1017  1567 D SettingsProvider: selectionArgs: 1002
,08-31 08:51:50.075  1017  1567 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:50.075  1017  1567 D SettingsProvider: ret = -1
,08-31 08:51:50.075  1017  3167 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 08:51:50.075  1017  3167 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.075  1017  3167 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.075  1017  3167 D SettingsProvider: selectionArgs: false
08-31 08:51:50.075  1017  3167 D SettingsProvider: selectionArgs: 1002
08-31 08:51:50.075  1017  3167 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:50.075  1017  3167 D SettingsProvider: ret = -1
,08-31 08:51:50.075  1017  1100 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-31 08:51:50.075  1017  1100 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.075  1017  1100 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.075  1017  1100 D SettingsProvider: selectionArgs: false
08-31 08:51:50.075  1017  1100 D SettingsProvider: selectionArgs: 1002
08-31 08:51:50.075  1017  1100 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:50.075  1017  1100 D SettingsProvider: ret = -1
,08-31 08:51:50.075  1017  4351 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService,
08-31 08:51:50.075  1017  4351 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.075  1017  4351 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.075  1017  4351 D SettingsProvider: selectionArgs: false
,08-31 08:51:50.075  1017  4351 D SettingsProvider: selectionArgs: 1002
,08-31 08:51:50.075  1017  4351 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-31 08:51:50.075  1017  4351 D SettingsProvider: ret = -1
08-31 08:51:50.075  1017  1448 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:51:50.075  1017  1448 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.075  1017  1448 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.075  1017  1448 D SettingsProvider: selectionArgs: false
08-31 08:51:50.075  1017  1448 D SettingsProvider: selectionArgs: 1002
08-31 08:51:50.075  1017  1448 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:50.075  1017  1448 D SettingsProvider: ret = -1,
08-31 08:51:50.075  1017  1366 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-31 08:51:50.075  1017  1366 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.075  1017  1366 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.075  1017  1366 D SettingsProvider: selectionArgs: false
,08-31 08:51:50.075  1017  1366 D SettingsProvider: selectionArgs: 1002
08-31 08:51:50.085  1017  1366 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:50.085  1017  1366 D SettingsProvider: ret = -1
08-31 08:51:50.085  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-31 08:51:50.085  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:50.085  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:50.085  1017  1029 D SettingsProvider: selectionArgs: false
08-31 08:51:50.085  1017  1029 D SettingsProvider: selectionArgs: 1002
08-31 08:51:50.085  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 08:51:50.085  1017  1029 D SettingsProvider: ret = -1
,08-31 08:51:50.095  1017  1486 I ActivityManager: Killing 6572:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-31 08:51:50.095  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-31 08:51:50.095  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 08:51:50.095  1017  1567 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:51:50.095  1017  1567 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 08:51:50.095  1017  1567 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:50.095  1017  1567 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:50.095  1017  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:50.105  2003  7101 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 08:51:50.105  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:50.115  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 08:51:50.115  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:50.115  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:50.115  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:50.125  1017  3167 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:50.125  1017  3167 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:50.125  1017  3167 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:50.135  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:50.135  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:50.135  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 08:51:50.135  1017  4351 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:50.135  1017  4351 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:50.135  1017  4351 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:50.135  1017  4351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:50.145  1017  4347 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:51:50.145  1017  4347 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:51:50.145  1017  4347 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:50.145  1017  4347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:50.145  1017  4347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:51:50.145  1606  1606 I Hs20UtilService: Starting #11
,08-31 08:51:50.145  1606  1643 I Hs20UtilService: Message received 5011
,08-31 08:51:50.145  2003  7101 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-31 08:51:50.155  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 08:51:50.155  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 08:51:50.155  6523  6523 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:51:50.155  6523  6523 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:51:50.155  1017  1486 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 08:51:50.165  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.165  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.165  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.165  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.175  7102  7102 E Zygote  : MountEmulatedStorage()
,08-31 08:51:50.175  7102  7102 E Zygote  : v2
08-31 08:51:50.175  7102  7102 I libpersona: KNOX_SDCARD checking this for 1000
08-31 08:51:50.175  7102  7102 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:50.175  7102  7102 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:50.175  7102  7102 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:51:50.185  7102  7102 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:51:50.185  1017  1486 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7102 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 08:51:50.205  7102  7102 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:50.205  7102  7102 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:50.225  7102  7102 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-31 08:51:50.225  7102  7102 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 08:51:50.225  7102  7102 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 08:51:50.245  7102  7102 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-31 08:51:50.245  7102  7102 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 08:51:50.245  7102  7102 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 08:51:50.245  7102  7102 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:51:50.245  1017  1030 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-31 08:51:50.245  1017  1030 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-31 08:51:50.245  7102  7117 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-31 08:51:50.255  1814  1814 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 08:51:50.255  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-31 08:51:50.255  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.255  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.255  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.255  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.275  7119  7119 E Zygote  : MountEmulatedStorage()
,08-31 08:51:50.275  7119  7119 E Zygote  : v2
08-31 08:51:50.275  7119  7119 I libpersona: KNOX_SDCARD checking this for 10121
08-31 08:51:50.275  7119  7119 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:50.275  7119  7119 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 08:51:50.275  7119  7119 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:51:50.275  1017  1042 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7119 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-31 08:51:50.275  7119  7119 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:51:50.275  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast,
08-31 08:51:50.275  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.275  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.275  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.275  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-31 08:51:50.285  2611  2622 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3,
,08-31 08:51:50.295  7129  7129 E Zygote  : MountEmulatedStorage(),
08-31 08:51:50.295  7129  7129 E Zygote  : v2
08-31 08:51:50.295  7129  7129 I libpersona: KNOX_SDCARD checking this for 10001
08-31 08:51:50.295  7129  7129 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:50.295  7129  7129 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:50.295  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7129 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 08:51:50.305  7129  7129 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:51:50.305  1814  1814 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-31 08:51:50.305  1814  1814 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-31 08:51:50.305  1814  1814 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-31 08:51:50.305  1814  1814 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
08-31 08:51:50.305  7129  7129 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:51:50.305  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-31 08:51:50.305  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.305  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.305  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.305  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.305  7119  7119 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:50.305  7119  7119 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:50.315  7129  7129 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:50.315  7129  7129 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:50.325  7146  7146 E Zygote  : MountEmulatedStorage()
,08-31 08:51:50.325  7146  7146 E Zygote  : v2
08-31 08:51:50.325  7146  7146 I libpersona: KNOX_SDCARD checking this for 10031
08-31 08:51:50.325  7146  7146 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:50.325  7146  7146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:50.325  7146  7146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:51:50.325  1017  1030 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7146 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-31 08:51:50.325  7146  7146 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:51:50.335  1814  1814 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 08:51:50.335  1814  1814 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-31 08:51:50.335  1017  1486 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-31 08:51:50.345  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.345  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.345  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.345  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.345  7119  7119 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:51:50.345  7119  7119 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 08:51:50.345  7119  7119 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 08:51:50.355  7146  7146 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:50.355  7146  7146 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:50.355  7164  7164 E Zygote  : MountEmulatedStorage()
08-31 08:51:50.355  7164  7164 E Zygote  : v2
08-31 08:51:50.355  7164  7164 I libpersona: KNOX_SDCARD checking this for 10077
08-31 08:51:50.355  7164  7164 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:50.355  7164  7164 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:50.355  7164  7164 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:50.355  7164  7164 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
08-31 08:51:50.365  1017  1486 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7164 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 08:51:50.365  7119  7119 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:51:50.365  7119  7119 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-31 08:51:50.375  7119  7119 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-31 08:51:50.375  1017  1478 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-31 08:51:50.375  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.375  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.375  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.375  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.385   309   309 I art     : Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 715us total 22.318ms
,08-31 08:51:50.385  7164  7164 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:50.395  7164  7164 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:50.405   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 16.775ms
,08-31 08:51:50.415   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.174ms
,08-31 08:51:50.425  7181  7181 E Zygote  : MountEmulatedStorage(),
08-31 08:51:50.425  7181  7181 E Zygote  : v2
08-31 08:51:50.425  7181  7181 I libpersona: KNOX_SDCARD checking this for 10141
08-31 08:51:50.425  7181  7181 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:50.425  7181  7181 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 08:51:50.435  7181  7181 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:50.435  7181  7181 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:51:50.435  1017  1478 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7181 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-31 08:51:50.435  1017  1478 I ActivityManager: Killing 6587:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-31 08:51:50.445  7146  7146 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-31 08:51:50.455  1017  1030 I ActivityManager: Killing 6607:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-31 08:51:50.455  7181  7181 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 08:51:50.455  7181  7181 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:50.465  1017  1486 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-31 08:51:50.475  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.475  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.475  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.475  1017  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.485  7181  7181 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-31 08:51:50.485  7196  7196 E Zygote  : MountEmulatedStorage()
,08-31 08:51:50.485  7196  7196 I libpersona: KNOX_SDCARD checking this for 1000
08-31 08:51:50.485  7196  7196 E Zygote  : v2
08-31 08:51:50.485  7196  7196 I libpersona: KNOX_SDCARD not a persona
08-31 08:51:50.485  7181  7181 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 08:51:50.485  7181  7181 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 08:51:50.485  7181  7181 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-31 08:51:50.485  7196  7196 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:50.485  1017  1486 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7196 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-31 08:51:50.485  1017  1486 I ActivityManager: Killing 6539:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-31 08:51:50.495  7196  7196 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:51:50.495  1017  1569 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-31 08:51:50.495  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.495  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.495  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.495  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.495  2784  7202 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
08-31 08:51:50.495  7196  7196 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:51:50.495  2784  7202 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-31 08:51:50.495  2784  7202 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-31 08:51:50.495  2784  7202 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-31 08:51:50.505  7211  7211 E Zygote  : MountEmulatedStorage()
08-31 08:51:50.505  2784  7202 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-31 08:51:50.505  7211  7211 E Zygote  : v2
08-31 08:51:50.505  7211  7211 I libpersona: KNOX_SDCARD checking this for 10032
08-31 08:51:50.505  7211  7211 I libpersona: KNOX_SDCARD not a persona
08-31 08:51:50.505  7211  7211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:50.515  1017  1569 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7211 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 08:51:50.515  7211  7211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:51:50.515  7211  7211 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-31 08:51:50.515  7196  7196 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:50.515  7196  7196 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:50.545  7211  7211 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:50.545  7211  7211 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:50.555  1017  1486 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:51:50.565  1017  1366 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:51:50.565  7196  7196 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 08:51:50.605  7211  7232 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-31 08:51:50.605  7211  7232 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-31 08:51:50.615  7211  7232 D SPPClientService: PushLog.txt file is not deleted.
,08-31 08:51:50.615  7211  7232 D SPPClientService: PushLog.txt file is not deleted.
08-31 08:51:50.615  7211  7232 D SPPClientService: ============PushLog. stop!
08-31 08:51:50.615  1017  1567 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:51:50.625   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 08:51:50.635  1017  4347 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:51:50.635  7211  7211 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-31 08:51:50.635  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-31 08:51:50.635  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.645  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 08:51:50.645  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.645  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.655  7237  7237 E Zygote  : MountEmulatedStorage(),
,08-31 08:51:50.665  1017  1030 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7237 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-31 08:51:50.665  7237  7237 E Zygote  : v2
08-31 08:51:50.665  7237  7237 I libpersona: KNOX_SDCARD checking this for 10036
08-31 08:51:50.665  7237  7237 I libpersona: KNOX_SDCARD not a persona
08-31 08:51:50.665  1017  1030 I ActivityManager: Killing 6036:com.android.mms/u0a41 (adj 15): empty #21
08-31 08:51:50.665  7237  7237 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:51:50.665  7237  7237 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 08:51:50.665  1017  1250 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-31 08:51:50.665  7237  7237 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 08:51:50.665  1017  1250 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-31 08:51:50.675  1017  1366 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 08:51:50.675  1017  1366 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 08:51:50.675  1017  1366 D SecContentProvider2: mCursor = null
,08-31 08:51:50.675  1017  1366 D WifiService: setWifiEnabled: true pid=6721, uid=10171,
08-31 08:51:50.675  1017  1250 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:50.675  1017  1366 W ActivityManager: Permission Denial: getCurrentUser() from pid=6721, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:51:50.675  1017  1250 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 08:51:50.675  1017  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-31 08:51:50.675  1017  1366 W WifiService: Failed getting userId using ActivityManagerNative,
08-31 08:51:50.675  1017  1366 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6721, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:51:50.675  1017  1366 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 08:51:50.675  1017  1366 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 08:51:50.675  1017  1366 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 08:51:50.675  1017  1366 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 08:51:50.675  1017  1366 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 08:51:50.675  1017  1366 D SettingsProvider: name = wifi_on,
,08-31 08:51:50.685  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################,
,08-31 08:51:50.695  7237  7237 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-31 08:51:50.695  7237  7237 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:50.725  7211  7247 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-31 08:51:50.755  1017  4347 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:51:50.755  1017  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-31 08:51:50.765  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.765  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.765  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.765  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.765  1017  1100 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:51:50.775  7258  7258 E Zygote  : MountEmulatedStorage()
08-31 08:51:50.775  7258  7258 E Zygote  : v2
08-31 08:51:50.775  7258  7258 I libpersona: KNOX_SDCARD checking this for 10068
08-31 08:51:50.775  7258  7258 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:50.775  7258  7258 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:50.785  7258  7258 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:50.785  7258  7258 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
08-31 08:51:50.785  1017  1030 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7258 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-31 08:51:50.785  7196  7196 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 08:51:50.805  1017  1486 D CountryDetector: No listener is left
,08-31 08:51:50.805  7196  7196 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-31 08:51:50.805  7196  7196 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:51:50.805  7196  7196 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 08:51:50.805  7196  7196 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-31 08:51:50.805  7196  7196 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-31 08:51:50.815  7258  7258 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:50.815  7258  7258 D ActivityThread: Added TimaKeyStore provider
08-31 08:51:50.815  1017  1561 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-31 08:51:50.815  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.815  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.815  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.815  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.815  1017  1250 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:51:50.825  7274  7274 E Zygote  : MountEmulatedStorage()
08-31 08:51:50.825  7274  7274 E Zygote  : v2
08-31 08:51:50.825  7274  7274 I libpersona: KNOX_SDCARD checking this for 10008
08-31 08:51:50.825  7274  7274 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:50.825  7274  7274 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:51:50.835  7274  7274 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:51:50.835  1017  1561 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7274 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 08:51:50.835  7274  7274 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 08:51:50.835  1017  1561 I ActivityManager: Killing 6632:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-31 08:51:50.865  7237  7237 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1bb0e28e
,08-31 08:51:50.875  7258  7258 D BadgeProvider: onCreate,
08-31 08:51:50.875  7274  7274 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 08:51:50.875  7258  7258 D BadgeProvider: DatabaseHelper
08-31 08:51:50.875  7274  7274 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:50.895  7258  7270 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-31 08:51:50.905  7237  7237 I SA      : [SSP] onCreated
,08-31 08:51:50.915  7258  7270 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-31 08:51:50.915  7258  7270 D BadgeProvider: sendNotify, [notify] : null
08-31 08:51:50.915  7258  7270 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-31 08:51:50.915  7258  7270 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-31 08:51:50.915  7258  7270 D BadgeProvider: update, [UpdateCount] : 1
,08-31 08:51:50.915  1480  1480 D Launcher.Model: reloadBadges entered.
,08-31 08:51:50.925  1017  1486 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 08:51:50.925  1017  3167 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-31 08:51:50.925  1017  3167 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.925  1017  3167 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.925  1017  3167 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.925  1017  3167 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.935  7291  7291 E Zygote  : MountEmulatedStorage()
,08-31 08:51:50.935  7291  7291 E Zygote  : v2
08-31 08:51:50.935  7291  7291 I libpersona: KNOX_SDCARD checking this for 10009
08-31 08:51:50.935  7291  7291 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:50.935  7291  7291 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:50.945  7237  7237 I SA      : [TPM] There is no property file
,08-31 08:51:50.945  7291  7291 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:50.945  7291  7291 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-31 08:51:50.945  7237  7237 I SA      : [SCU] isHaveSA() - false
,08-31 08:51:50.955  1017  3167 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7291 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,08-31 08:51:50.965  7237  7237 I SA      : [TPM] getModelProperty : null
08-31 08:51:50.965  7237  7237 I SA      : [TPM] getCSCProperty : null
08-31 08:51:50.965  1017  3167 I ActivityManager: Killing 6466:com.android.calendar/u0a131 (adj 15): empty #21
,08-31 08:51:50.965  1017  3167 I ActivityManager: Killing 6648:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #22
08-31 08:51:50.965  7237  7237 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-31 08:51:50.965  7237  7237 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-31 08:51:50.965  7237  7237 I SA      : [DM] TFT FEATURE: false
,08-31 08:51:50.965  1017  1478 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-31 08:51:50.965  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-31 08:51:50.965  7237  7237 I SA      : [DM] init START
,08-31 08:51:50.975  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:50.975  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:50.975  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 08:51:50.985  7237  7237 I SA      : [DM] This device is not a Vodafone
,08-31 08:51:50.985  7291  7291 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:50.985  7291  7291 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:50.995  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-31 08:51:50.995  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:50.995  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.995  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:50.995  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:51.015  7315  7315 E Zygote  : MountEmulatedStorage(),
08-31 08:51:51.015  7315  7315 E Zygote  : v2
08-31 08:51:51.015  7315  7315 I libpersona: KNOX_SDCARD checking this for 10110
08-31 08:51:51.015  7315  7315 I libpersona: KNOX_SDCARD not a persona
08-31 08:51:51.015  7315  7315 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:51.015  1017  1030 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7315 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 08:51:51.015  7315  7315 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:51.015  7315  7315 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:51:51.025  1017  1250 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-31 08:51:51.025  1017  1250 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-31 08:51:51.025  1017  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:51.025  1017  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:51.025  1017  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 08:51:51.035  7237  7237 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-31 08:51:51.035  7237  7237 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-31 08:51:51.035  7237  7237 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-31 08:51:51.035  7237  7237 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-31 08:51:51.035  7237  7237 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-31 08:51:51.045  7057  7314 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-31 08:51:51.045  7237  7237 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-31 08:51:51.045  7237  7237 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-31 08:51:51.045  7237  7237 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 08:51:51.055  2898  2898 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 08:51:51 GMT+02:00 2016
,08-31 08:51:51.055  1017  1030 I ActivityManager: Killing 6665:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-31 08:51:51.055  1017  1561 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-31 08:51:51.055  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-31 08:51:51.055  7315  7315 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:51.055  7315  7315 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:51.055  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:51.055  1017  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:51.055  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 08:51:51.055  7237  7237 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-31 08:51:51.065  7237  7237 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-31 08:51:51.065  1017  1250 I ActivityManager: Killing 5997:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-31 08:51:51.065  2898  2898 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 08:51:51.075  2898  2898 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 08:51:51.075  2898  2898 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 08:51:51.075  7237  7237 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-31 08:51:51.075  7237  7237 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-31 08:51:51.085  7237  7237 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-31 08:51:51.085  7237  7237 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-31 08:51:51.085  7237  7237 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-31 08:51:51.085  7237  7237 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-31 08:51:51.085  2898  2898 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 08:51:51.085  7237  7237 I SA      : [SCU] isHaveSA() - false
,08-31 08:51:51.085  7237  7237 I SA      : support phone number id : false
08-31 08:51:51.085  7237  7237 I SA      : [DM] Supports Ref Jpn : true
,08-31 08:51:51.085  7237  7237 I SA      : [DM] init END
08-31 08:51:51.085  7237  7237 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-31 08:51:51.085  2898  7330 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 08:51:51.095  2898  7330 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-31 08:51:51.095  7237  7237 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-31 08:51:51.095  7237  7237 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 08:51:51.095  2898  7330 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-31 08:51:51.095  2898  7330 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-31 08:51:51.105  2898  2898 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 08:51:51.135  1017  4347 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-31 08:51:51.135  1017  4347 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-31 08:51:51.135  1017  1366 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-31 08:51:51.135  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-31 08:51:51.225  1017  1100 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 08:51:51.235  1017  1250 I ActivityManager: Killing 5814:com.android.vending/u0a26 (adj 15): empty #21
,08-31 08:51:51.245  1017  4350 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:51:51.245  1017  4350 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
08-31 08:51:51.245  1017  1044 D Tethering: interfaceAdded wlan0
,08-31 08:51:51.245  7237  7237 I SA      : [SLFUCHKMGR] constructor called
08-31 08:51:51.245  1017  4350 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:51.245  1017  4350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:51.245  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 08:51:51.245  1017  1130 E Tethering: No numeric data
,08-31 08:51:51.255  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:51:51.255  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:51:51.255  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:51:51.255  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 08:51:51.255  1017  1130 D Tethering: clearTetheredNotification()
08-31 08:51:51.255  1017  1130 D Tethering: InitialState.processMessage what=4
,08-31 08:51:51.255  1017  1130 E Tethering: No numeric data,
,08-31 08:51:51.255  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:51:51.255  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:51.255  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:51:51.255  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 08:51:51.255  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:51:51.255  1175  1175 D HotspotTile: updateTetherState():false, false
08-31 08:51:51.255  1017  1044 D Tethering: interfaceAdded p2p0
,08-31 08:51:51.255  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 08:51:51.255  1017  1130 D Tethering: clearTetheredNotification()
08-31 08:51:51.255  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 08:51:51.265  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 08:51:51.265  1175  1175 D HotspotTile: updateTetherState():false, false
,08-31 08:51:51.265  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 08:51:51.265  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:51:51.265  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:51:51.265   278   977 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 08:51:51.265   278   977 D SoftapController: Softap fwReload - Ok
,08-31 08:51:51.265  1017  1123 V NetworkStats: performPollLocked() took 13ms
08-31 08:51:51.265  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:51.265   278   977 D CommandListener: Setting iface cfg
08-31 08:51:51.265   278   977 D CommandListener: Trying to bring down wlan0
08-31 08:51:51.265   278   977 D CommandListener: Clearing all IP addresses on wlan0
08-31 08:51:51.265  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:51.265  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:51.275  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:51.275  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-31 08:51:51.275  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 08:51:51.275  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:51:51.275  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:51:51.275  7237  7237 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 08:51:51.275  7237  7237 I SA      : [OR] == isSIMCardReady false ==
08-31 08:51:51.275  4777  4777 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-31 08:51:51.275  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 08:51:51.275  1017  1126 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-31 08:51:51.275  7237  7237 I SA      : [SCU] == networkStateCheck == false
08-31 08:51:51.275  7237  7237 I SA      : [OR] onReceive END
08-31 08:51:51.275  4777  7335 I iu.SyncManager: SYNC; picasa accounts
,08-31 08:51:51.285  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:51:51.285  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:51:51.285  1017  1123 V NetworkStats: performPollLocked() took 11ms
08-31 08:51:51.285  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:51.285  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:51.285  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:51.285  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:51.285  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:51:51.285  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:51:51.285  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-31 08:51:51.285  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:51.285  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 08:51:51.285  3076  3076 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:51.285  1175  1175 D HotspotTile: onReceive : 2, 0
,08-31 08:51:51.285  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:51.295  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:51.295  1017  1567 I ActivityManager: Killing 6792:com.google.android.youtube/u0a161 (adj 15): empty #21
,08-31 08:51:51.295  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:51.295  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:51.295  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:51:51.335  7337  7337 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 08:51:51.335  7337  7337 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 08:51:51.345  7337  7337 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 08:51:51.385  7337  7337 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-31 08:51:51.385   372   372 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7337
,08-31 08:51:51.385   372   372 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-31 08:51:51.385  7337  7337 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 08:51:51.385  7337  7337 I wpa_supplicant: ssSupport state is = 1
08-31 08:51:51.385  7337  7337 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 08:51:51.385  7337  7337 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-31 08:51:51.385   372   372 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7337
08-31 08:51:51.385   372   372 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-31 08:51:51.405   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 08:51:51.405   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:51.405  7315  7341 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 08:51:51.415   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 08:51:51.415   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:51.415  7315  7341 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 08:51:51.435   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 08:51:51.435   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:51.435  7315  7343 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 08:51:51.445   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 08:51:51.445   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:51.445  7315  7343 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
,08-31 08:51:51.465  7315  7315 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 08:51:51.465  7315  7315 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 08:51:51.465  7315  7315 I GAv4    :   adb logcat -s GAv4
,08-31 08:51:51.485  7315  7315 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 08:51:51.485  1017  3167 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output,
,08-31 08:51:51.495  7315  7315 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 08:51:51.505  7315  7345 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 08:51:51.575   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-31 08:51:51.585  7337  7337 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-31 08:51:51.605   291   291 E SMD     : DCD OFF
,08-31 08:51:51.625   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:51:51.635  7337  7337 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 08:51:51.635  7337  7337 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 08:51:51.645  7337  7337 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-31 08:51:51.645   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7337
08-31 08:51:51.645   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 08:51:51.645  7337  7337 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 08:51:51.645  7337  7337 I wpa_supplicant: ssSupport state is = 1
,08-31 08:51:51.645  7337  7337 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 08:51:51.645  7337  7337 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:51:51.645  7337  7337 E wpa_supplicant: SIM READ ERROR
08-31 08:51:51.645  7337  7337 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:51:51.645  7337  7337 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:51:51.645  7337  7337 E wpa_supplicant: SIM READ ERROR
08-31 08:51:51.645  7337  7337 I wpa_supplicant: Blacklist: Clear (all) 
08-31 08:51:51.645  7337  7337 I wpa_supplicant: wpa_default_ap_write_once
08-31 08:51:51.645  7337  7337 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 08:51:51.645  7337  7337 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:51:51.645  7337  7337 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 08:51:51.645  7337  7337 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:51:51.645  7337  7337 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:51:51.645  7337  7337 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 08:51:51.655  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:51:51.655  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:51:51.655  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:51:51.725  7337  7337 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-31 08:51:51.765  1017  1250 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:51.765  1017  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:51.765  1017  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:51.765  1017  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-31 08:51:51.795  7315  7315 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-31 08:51:51.815  7315  7315 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 8251-8254)
,08-31 08:51:51.815  7315  7315 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 08:51:51.825  7315  7315 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1f81af81}
,08-31 08:51:51.825  7315  7315 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 08:51:51.825  7315  7315 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 08:51:51.845  7315  7315 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 08:51:51.845  2003  2169 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-31 08:51:51.845  7315  7315 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 08:51:51.845  2003  2169 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-31 08:51:51.865  7337  7337 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-31 08:51:51.865  7337  7337 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 08:51:51.865  7315  7315 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 08:51:51.875  7337  7337 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-31 08:51:51.875   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7337
08-31 08:51:51.875   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 08:51:51.875  7337  7337 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 08:51:51.875  7337  7337 I wpa_supplicant: ssSupport state is = 1
,08-31 08:51:51.875  7337  7337 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 08:51:51.875  7337  7337 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 08:51:51.885  7315  7315 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 08:51:51.885  7315  7315 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 08:51:51.885  7315  7315 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 08:51:51.885  7315  7315 I Adreno-EGL: Local Branch: 
08-31 08:51:51.885  7315  7315 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 08:51:51.885  7315  7315 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 08:51:51.885  7315  7315 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 08:51:51.885  7337  7337 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-31 08:51:51.885   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7337,
08-31 08:51:51.885   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 08:51:51.885  7337  7337 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 08:51:51.885  7337  7337 I wpa_supplicant: ssSupport state is = 1
08-31 08:51:51.885  7337  7337 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:51:51.885  7337  7337 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:51:51.885  7337  7337 E wpa_supplicant: SIM READ ERROR
08-31 08:51:51.885  7337  7337 I wpa_supplicant: wpa_default_ap_write_once
08-31 08:51:51.885  7337  7337 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 08:51:51.885  7337  7337 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 08:51:51.895  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 08:51:51.895  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 08:51:51.895  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-31 08:51:51.895  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 08:51:51.895  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:51:51.895  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:51:51.945  7315  7376 W cr.media: Requires BLUETOOTH permission
,08-31 08:51:51.945  7315  7315 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 08:51:51.955  7315  7315 I NSApplication: Starting up...
,08-31 08:51:51.955  1017  1250 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 08:51:51.965  1017  4350 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 08:51:51.965  1017  1561 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-31 08:51:51.965  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:51.965  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:51.965  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:51.965  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:51.985  7381  7381 E Zygote  : MountEmulatedStorage()
08-31 08:51:51.985  7381  7381 E Zygote  : v2
08-31 08:51:51.985  7381  7381 I libpersona: KNOX_SDCARD checking this for 10117
08-31 08:51:51.985  7381  7381 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:51.985  7381  7381 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:51.985  7337  7337 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-31 08:51:51.985  7337  7337 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
08-31 08:51:51.985  1017  1561 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7381 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 08:51:51.985  7381  7381 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:51:51.985  1017  1561 I ActivityManager: Killing 7023:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-31 08:51:51.995  7381  7381 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:51:52.005  7381  7381 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:52.015  7381  7381 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:52.025  7381  7381 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 08:51:52.065  7337  7337 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-31 08:51:52.065  7337  7337 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-31 08:51:52.065  7337  7337 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 08:51:52.245  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 08:51:52.245  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:51:52.245  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:51:52.285  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-31 08:51:52.285  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 08:51:52.285  7337  7337 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 08:51:52.285  7337  7337 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:51:52.285  7337  7337 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:51:52.285  7337  7337 E wpa_supplicant: SIM READ ERROR
08-31 08:51:52.285  7337  7337 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 08:51:52.295  7337  7337 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 08:51:52.305  7337  7337 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 08:51:52.305  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-31 08:51:52.305  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:51:52.305  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:51:52.305  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:52.305  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:52.305  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:52.305  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:51:52.315  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:52.315  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-31 08:51:52.315  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:52.315  1175  1175 D HotspotTile: onReceive : 3, 0
,08-31 08:51:52.315  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 08:51:52.325  3076  3076 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-31 08:51:52.325  1017  1126 E WifiConfigStore: Not a HS20
,08-31 08:51:52.325  1017  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 08:51:52.325  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:51:52.325  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:52.325  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:51:52.325  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 08:51:52.325  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:52.325  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:51:52.325  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:52.325  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:51:52.325  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 08:51:52.325  7337  7337 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 08:51:52.325  7337  7337 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 08:51:52.325  7337  7337 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 08:51:52.325  7337  7337 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 08:51:52.325  7337  7337 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 08:51:52.325  7337  7337 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 08:51:52.325  7337  7337 I wpa_supplicant: First Scan Start
,08-31 08:51:52.335  7337  7337 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 08:51:52.335  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-31 08:51:52.335  7057  7057 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:51:52.335  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 08:51:52.335  1017  1126 I WifiNative-HAL: startHal
08-31 08:51:52.335  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9d45888c
08-31 08:51:52.335  1017  1126 I WifiNative-HAL: Could not start hal
,08-31 08:51:52.335  1017  1126 E WifiNative-wlan0: do suspend true
,08-31 08:51:52.335  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 08:51:52.335  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-31 08:51:52.345   278   977 D CommandListener: Setting iface cfg
08-31 08:51:52.345   278   977 D CommandListener: Trying to bring up p2p0
,08-31 08:51:52.345  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 08:51:52.345  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 08:51:52.345  1017  1126 E WifiNative-wlan0: invaild command id : 215
08-31 08:51:52.345  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 08:51:52.345  1017  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:52.345  1017  1149 I WifiNative-HAL: startHal
08-31 08:51:52.345  1017  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e0f09bc
08-31 08:51:52.345  1017  1149 I WifiNative-HAL: Could not start hal
08-31 08:51:52.345  1017  1149 E WifiScanningService: could not start HAL
,08-31 08:51:52.345  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 08:51:52.345  1017  1125 D WifiP2pService: P2pEnablingState
08-31 08:51:52.345  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-31 08:51:52.345  1017  1125 D WifiP2pService: P2p socket connection successful
,08-31 08:51:52.345  1017  1125 D WifiP2pService: P2pEnabledState
08-31 08:51:52.345  7337  7337 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 08:51:52.345  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 08:51:52.345  7337  7337 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 08:51:52.345  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 08:51:52.345  7337  7337 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-31 08:51:52.345  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-31 08:51:52.345  1017  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:52.345  1017  1126 E WifiStateMachine: Failed to set frequency band 0
08-31 08:51:52.345  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 08:51:52.345  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:51:52.345  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 08:51:52.345  1017  1126 D SecContentProvider2: mCursor = null
08-31 08:51:52.345  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:51:52.345  1017  1047 D WifiDisplayController: disconnect
,08-31 08:51:52.345  1017  1047 D WifiDisplayController: updateConnection
08-31 08:51:52.345  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:51:52.345  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 08:51:52.355  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:51:52.355  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:51:52.355  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:52.355  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-31 08:51:52.355  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 08:51:52.355  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 08:51:52.355  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,08-31 08:51:52.355  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-31 08:51:52.355  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 08:51:52.355  1017  1567 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 08:51:52.355  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 08:51:52.355  1017  1125 D WifiP2pService: DeviceAddress: 0a:76:28
,08-31 08:51:52.355  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  secondary type: null
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  wps: 0
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  grpcapab: 0
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  devcapab: 0
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  status: 3
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  wfdInfo: null
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-31 08:51:52.355  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-31 08:51:52.395  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 08:51:52.395  1017  1125 D WifiP2pService: InactiveState
,08-31 08:51:52.395  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
08-31 08:51:52.395  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 08:51:52.395  7337  7337 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 08:51:52.395  1017  1125 D WifiP2pService: InactiveState{ what=143376 },
08-31 08:51:52.395  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 08:51:52.425  1017  4350 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-31 08:51:52.435  1017  4350 I ActivityManager: Killing 7040:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-31 08:51:52.435  1017  1250 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:51:52.435  1017  1250 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:51:52.435  1017  1250 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:52.435  1017  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:52.435  1017  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:51:52.435  1606  1606 I Hs20UtilService: Starting #12
,08-31 08:51:52.435  1606  1643 I Hs20UtilService: Message received 5011
,08-31 08:51:52.445  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 08:51:52.445  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 08:51:52.445  6523  6523 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:51:52.445  6523  6523 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:51:52.455  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:51:52.455  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:51:52.455  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:52.455  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:51:52.455  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:51:52.465  1606  1606 I Hs20UtilService: Starting #13
,08-31 08:51:52.465  1606  1643 I Hs20UtilService: Message received 5011
,08-31 08:51:52.465  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 08:51:52.465  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 08:51:52.465  1017  1126 E WifiNative-wlan0: invaild command id : 215
,08-31 08:51:52.465  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 08:51:52.465  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 08:51:52.465  6523  6523 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:51:52.465  6523  6523 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:51:52.475  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 08:51:52.475  3076  3076 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:51:52.475  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:51:52.485  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:51:52.485  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 08:51:52.485  3076  3076 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 08:51:52.485  3076  3799 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:51:52.485  1017  1440 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-31 08:51:52.485  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:52.485  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:52.485  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:52.485  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:52.495  7407  7407 E Zygote  : MountEmulatedStorage()
,08-31 08:51:52.495  7407  7407 E Zygote  : v2
08-31 08:51:52.495  7407  7407 I libpersona: KNOX_SDCARD checking this for 10064
08-31 08:51:52.495  7407  7407 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:52.505  7407  7407 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 08:51:52.505  1017  1440 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7407 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 08:51:52.505  7407  7407 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:51:52.505  7407  7407 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:51:52.525  7407  7407 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:52.525  7407  7407 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:52.535  7407  7407 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 08:51:52.545  7407  7407 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:51:52.555  7407  7407 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 08:51:52.575  7407  7407 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 08:51:52.575  1017  1366 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-31 08:51:52.575  1017  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:52.575  1017  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:52.575  1017  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:52.575  1017  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:52.585  7422  7422 E Zygote  : MountEmulatedStorage(),
,08-31 08:51:52.595  7422  7422 E Zygote  : v2
08-31 08:51:52.595  7422  7422 I libpersona: KNOX_SDCARD checking this for 10065
08-31 08:51:52.595  7422  7422 I libpersona: KNOX_SDCARD not a persona
08-31 08:51:52.595  1017  1366 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7422 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 08:51:52.595  7422  7422 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:52.595  1017  1366 I ActivityManager: Killing 6937:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-31 08:51:52.605  7422  7422 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:51:52.605  7422  7422 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:51:52.615   309   309 I art     : Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 630us total 23.634ms
,08-31 08:51:52.615  7422  7422 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:52.615  7422  7422 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:52.625   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-31 08:51:52.635   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.598ms
08-31 08:51:52.635  7422  7422 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:51:52.645  1017  1561 I ActivityManager: Killing 7085:com.android.bluetooth/1002 (adj 15): empty #21
,08-31 08:51:52.645   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 567us total 17.153ms
,08-31 08:51:53.545  7337  7337 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
08-31 08:51:53.545  7337  7337 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 08:51:53.545  7337  7337 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-31 08:51:53.545  7337  7337 I wpa_supplicant: Trying to associate with  'G700'
08-31 08:51:53.545  7337  7337 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-31 08:51:53.545  7337  7337 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-31 08:51:53.545  1017  7400 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 08:51:53.565  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-31 08:51:53.565  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:51:53.675  7337  7337 E wpa_supplicant: Cmd 35605 not handled,
08-31 08:51:53.675  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:51:53.675  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 08:51:53.675  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:51:53.675  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 08:51:53.675  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:51:53.675  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:51:53.675  7337  7337 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
08-31 08:51:53.675  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:51:53.675  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 08:51:53.675  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:51:53.675  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 08:51:53.675  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 08:51:53.675  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-31 08:51:53.675  1017  1130 E Tethering: No numeric data
08-31 08:51:53.675  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 08:51:53.675  1017  1130 D Tethering: clearTetheredNotification()
,08-31 08:51:53.675  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:53.675  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:51:53.685  7337  7337 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-31 08:51:53.685  7337  7337 I wpa_supplicant: Associated with F4.99.3E
08-31 08:51:53.685  7337  7337 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-31 08:51:53.685  7337  7337 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-31 08:51:53.685  7337  7337 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-31 08:51:53.685  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:51:53.685  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:51:53.685  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 08:51:53.685  1017  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 08:51:53.685  1175  1175 D HotspotTile: updateTetherState():false, false
08-31 08:51:53.685  1017  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 08:51:53.685  1017  1029 D SecContentProvider2: mCursor = null
,08-31 08:51:53.685  1017  1029 D WifiService: setWifiEnabled: false pid=6721, uid=10171
,08-31 08:51:53.695  1017  1029 D SettingsProvider: name = wifi_on
08-31 08:51:53.695  1017  1123 V NetworkStats: performPollLocked() took 12ms
08-31 08:51:53.695  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:53.695  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:51:53.695  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:51:53.695  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:51:53.695  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:51:53.695  7337  7337 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 08:51:53.695  7337  7337 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-31 08:51:53.695  7337  7337 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-31 08:51:53.695  7337  7337 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 08:51:53.695  7337  7337 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 08:51:53.695  7337  7337 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 08:51:53.695  7337  7337 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-31 08:51:53.695  7337  7337 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 08:51:53.695  7337  7337 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-31 08:51:53.705  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 08:51:53.705  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 08:51:53.705  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-31 08:51:53.705  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 08:51:53.705  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 08:51:53.705  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-31 08:51:53.705  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 08:51:53.705  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:51:53.705  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 08:51:53.705  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:51:53.745  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-31 08:51:53.755   278   977 D CommandListener: Setting iface cfg,
08-31 08:51:53.755  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,08-31 08:51:53.765  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-31 08:51:53.765  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:51:53.765  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:51:53.775  1017  1126 E WifiNative-wlan0: do suspend true,
,08-31 08:51:53.775  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-31 08:51:53.775  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:53.775  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
08-31 08:51:53.775  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:53.785  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:51:53.785  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:51:53.785  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.785  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.785  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.785  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:51:53.785   278   977 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:51:53.795  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-31 08:51:53.795  1017  3167 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:51:53.795  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:51:53.795  1017  3167 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:51:53.795  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.795  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.795  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.795  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.795  1017  3167 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:53.795  1017  3167 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:53.795  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 08:51:53.795  1017  3167 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 08:51:53.795  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-31 08:51:53.795  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 08:51:53.795   278   977 E Netd    : no such netId 503
,08-31 08:51:53.795  1017  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-31 08:51:53.795  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-31 08:51:53.795  1017  1128 V NetworkStats: updateIfacesLocked()
08-31 08:51:53.795  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:53.795  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:51:53.795  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 08:51:53.805  3076  3076 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 08:51:53.805  1606  1606 I Hs20UtilService: Starting #14
08-31 08:51:53.805  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 08:51:53.805  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:51:53.805  1606  1643 I Hs20UtilService: Message received 5007
08-31 08:51:53.805  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 08:51:53.805  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 08:51:53.805  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:51:53.805  3076  3076 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 08:51:53.805  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 08:51:53.805  3076  3799 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 08:51:53.805  1017  1128 V NetworkStats: performPollLocked() took 4ms
,08-31 08:51:53.805  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:53.805  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:51:53.805  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:51:53.805  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
08-31 08:51:53.805  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 08:51:53.805  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-31 08:51:53.805  1017  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:51:53.805  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.805  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.815  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-31 08:51:53.805  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.805  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.805  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-31 08:51:53.815  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:51:53.815  1017  1126 D SecContentProvider2: mCursor = null
08-31 08:51:53.815  1017  1150 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:51:53.815  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 08:51:53.815  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-31 08:51:53.815  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-31 08:51:53.815  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 08:51:53.815  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 08:51:53.825  1017  1125 D WifiP2pService: P2pDisablingState
08-31 08:51:53.825  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-31 08:51:53.825  1017  1125 D WifiP2pService: p2p socket connection lost
,08-31 08:51:53.825  1017  1125 D WifiP2pService: P2pDisabledState
,08-31 08:51:53.825  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 08:51:53.825  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 08:51:53.825  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-31 08:51:53.825  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:51:53.825  1017  1047 D WifiDisplayController: disconnect
08-31 08:51:53.825  1017  1047 D WifiDisplayController: updateConnection
08-31 08:51:53.825  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:51:53.825  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 08:51:53.825  1017  1126 E WifiNative-wlan0: do suspend true
,08-31 08:51:53.825  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 },
08-31 08:51:53.825  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-31 08:51:53.835  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 08:51:53.835  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-31 08:51:53.835  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 08:51:53.835  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 08:51:53.835  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 08:51:53.835  1017  1100 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 08:51:53.835   278   977 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:51:53.835  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 08:51:53.835  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:51:53.835  1017  1366 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:51:53.835  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:51:53.835  1017  1366 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:51:53.835  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.835  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-31 08:51:53.835  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:51:53.835  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.835  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.835  1017  1366 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:53.835  1017  1366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:53.835  1017  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 08:51:53.835  1606  1606 I Hs20UtilService: Starting #15
,08-31 08:51:53.835  1017  7437 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:53.835  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 08:51:53.835  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 08:51:53.835  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-31 08:51:53.835  1017  7437 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 08:51:53.835  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:53.835  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:53.835  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 08:51:53.835  1017  1128 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-31 08:51:53.835  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 08:51:53.845  1606  1643 I Hs20UtilService: Message received 5007
,08-31 08:51:53.845  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 08:51:53.845  7337  7337 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-31 08:51:53.845  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:51:53.845  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:51:53.845  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.845  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.845  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.845  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:51:53.855  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 08:51:53.855  3076  3076 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:51:53.855  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:51:53.855  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:51:53.855  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:51:53.855  3076  3076 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 08:51:53.855  3076  3799 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 08:51:53.855  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:51:53.855  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:51:53.865  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:51:53.865  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:51:53.865  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.865  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 08:51:53.865  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.865  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.865  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:53.865  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:51:53.865  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-31 08:51:53.865  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:53.865  1175  1175 D HotspotTile: onReceive : 0, 0
08-31 08:51:53.865  3076  3076 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:53.865  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:51:53.865  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:53.865  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:51:53.865  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:53.865  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:51:53.865  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:53.865  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:51:53.875  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 08:51:53.875  3076  3076 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:51:53.875  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:51:53.885  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 08:51:53.885  1017  1030 I ActivityManager: Killing 6958:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-31 08:51:53.885  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:51:53.885  3076  3076 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 08:51:53.885  3076  3799 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:51:53.885  7407  7407 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:51:53.885  7407  7407 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-31 08:51:53.885  7407  7407 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 08:51:53.895  7422  7422 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:51:53.905  1017  4350 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:51:53.905  1017  4350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:51:53.905  1017  4350 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:53.905  1017  4350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:51:53.905  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:51:53.905  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 08:51:53.905  1606  1606 I Hs20UtilService: Starting #16
,08-31 08:51:53.905  1606  1643 I Hs20UtilService: Message received 5007
08-31 08:51:53.905  3076  3076 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:51:53.915  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:51:53.915  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:51:53.915  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:51:53.915  3076  3076 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 08:51:53.915  3076  3799 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:51:53.915  1017  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:51:53.915  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:51:53.925  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:53.925  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:53.925  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:51:53.925  1606  1606 I Hs20UtilService: Starting #17
,08-31 08:51:53.925  1606  1643 I Hs20UtilService: Message received 5011
,08-31 08:51:53.925  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 08:51:53.925  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 08:51:53.925  6523  6523 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 08:51:53.925  6523  6523 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:51:54.005  7337  7337 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 08:51:54.045  7337  7337 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-31 08:51:54.045  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-31 08:51:54.045  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-31 08:51:54.045  1017  1044 D Tethering: interfaceStatusChanged p2p0, false,
,08-31 08:51:54.085  7337  7337 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
,08-31 08:51:54.085  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:51:54.085  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 08:51:54.085  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:51:54.085  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:51:54.085  7337  7337 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED,
,08-31 08:51:54.085  7337  7337 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e,
08-31 08:51:54.085  7337  7337 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030,
,08-31 08:51:54.085  1017  1123 V NetworkStats: performPollLocked(flags=0x1),
08-31 08:51:54.085  7337  7337 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 08:51:54.085  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 08:51:54.085  1017  1130 D Tethering: InitialState.processMessage what=4
08-31 08:51:54.085  1175  1175 D HotspotTile: updateTetherState():false, false
08-31 08:51:54.085  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:51:54.095  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:51:54.085  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:51:54.085  1017  1130 E Tethering: No numeric data
08-31 08:51:54.085  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 08:51:54.085  1017  1130 D Tethering: clearTetheredNotification()
08-31 08:51:54.085  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:54.095  1017  1123 V NetworkStats: performPollLocked() took 7ms
,08-31 08:51:54.085  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 08:51:54.085  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:51:54.095  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 08:51:54.095  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:51:54.095  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:54.095  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:51:54.095  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:51:54.315  7337  7337 I wpa_supplicant: Blacklist: Clear (all) ,
,08-31 08:51:54.375  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-31 08:51:54.375  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 08:51:54.375  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:51:54.385  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 08:51:54.375  7337  7337 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 08:51:54.385  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 08:51:54.385  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
,08-31 08:51:54.485  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-31 08:51:54.485  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 08:51:54.485  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:51:54.485  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-31 08:51:54.485  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:51:54.485  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:51:54.495  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:54.495  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:51:54.495  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:51:54.495  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-31 08:51:54.495  7057  7057 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:51:54.495  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 08:51:54.495  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:54.495  1175  1175 D HotspotTile: onReceive : 1, 0
,08-31 08:51:54.495  2003  2168 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:51:54.505  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:54.505  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:54.505  3076  3076 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:54.515  1017  1569 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:51:54.515  1017  1569 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:51:54.515  1017  1569 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:54.515  1017  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:51:54.515  1017  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:51:54.515  1606  1606 I Hs20UtilService: Starting #18
,08-31 08:51:54.515  1606  1643 I Hs20UtilService: Message received 5011
,08-31 08:51:54.515  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 08:51:54.525  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 08:51:54.525  6523  6523 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:51:54.525  6523  6523 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:51:54.615   291   291 E SMD     : DCD OFF,
,08-31 08:51:55.155  1017  3167 I ActivityManager: Killing 7102:com.sec.pcw.device/1000 (adj 15): empty #21
,08-31 08:51:55.195  1017  1044 D Tethering: interfaceRemoved wlan0
08-31 08:51:55.195  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 08:51:55.435  1017  1044 D Tethering: interfaceRemoved p2p0
,08-31 08:51:55.435  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 08:51:55.665  1017  3387 D SSRM:n  : SIOP:: AP = 340,
,08-31 08:51:56.305  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-31 08:51:56.715  6721  6775 D BluetoothAdapter: enable(),
,08-31 08:51:56.715  1017  4350 W ActivityManager: Permission Denial: getCurrentUser() from pid=6721, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-31 08:51:56.715  1017  4350 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 08:51:56.715  1017  4350 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6721, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:51:56.715  1017  4350 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 08:51:56.715  1017  4350 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-31 08:51:56.715  1017  4350 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 08:51:56.715  1017  4350 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-31 08:51:56.715  1017  4350 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 08:51:56.715  1017  4350 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 08:51:56.715  1017  4350 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 08:51:56.725  1017  4350 D SettingsProvider: name = bluetooth_on
,08-31 08:51:56.725  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-31 08:51:56.725  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 08:51:56.735  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
08-31 08:51:56.735  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-31 08:51:56.735  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-31 08:51:56.735  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:56.735  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:56.735  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-31 08:51:56.755  7443  7443 E Zygote  : MountEmulatedStorage()
08-31 08:51:56.755  7443  7443 E Zygote  : v2
08-31 08:51:56.755  7443  7443 I libpersona: KNOX_SDCARD checking this for 1002
08-31 08:51:56.755  7443  7443 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:56.755  7443  7443 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:56.755  1017  1046 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7443 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-31 08:51:56.755  7443  7443 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:51:56.765  7443  7443 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 08:51:56.785  7443  7443 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:56.785  7443  7443 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:56.805  7443  7443 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 08:51:56.805  7443  7443 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 08:51:56.825  7443  7443 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding GattService
,08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding HeadsetService
08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding HidService
08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding HealthService
08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding PanService
,08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding SapService
,08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding SapClientService
08-31 08:51:56.865  7443  7443 D BtSettings.ProfileConfig: Adding HidDevService
08-31 08:51:56.865  7443  7443 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 08:51:56.865  1017  1440 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-31 08:51:56.865  1017  1440 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:56.865  1017  1440 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:56.865  1017  1440 D SettingsProvider: selectionArgs: false
08-31 08:51:56.865  1017  1440 D SettingsProvider: selectionArgs: 1002
08-31 08:51:56.865  1017  1440 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:56.865  1017  1440 D SettingsProvider: ret = -1
,08-31 08:51:56.865  1017  4347 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-31 08:51:56.865  1017  4347 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 08:51:56.865  1017  4347 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:56.865  1017  4347 D SettingsProvider: selectionArgs: false
08-31 08:51:56.865  1017  4347 D SettingsProvider: selectionArgs: 1002
08-31 08:51:56.865  1017  4347 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:56.865  1017  4347 D SettingsProvider: ret = -1
,08-31 08:51:56.865  1017  1366 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 08:51:56.875  1017  1366 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 08:51:56.875  1017  1366 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:56.875  1017  1366 D SettingsProvider: selectionArgs: false
08-31 08:51:56.875  1017  1366 D SettingsProvider: selectionArgs: 1002
08-31 08:51:56.875  1017  1366 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 08:51:56.875  1017  1366 D SettingsProvider: ret = -1
08-31 08:51:56.875  1017  1448 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 08:51:56.875  1017  1448 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 08:51:56.875  1017  1448 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:56.875  1017  1448 D SettingsProvider: selectionArgs: false
08-31 08:51:56.875  1017  1448 D SettingsProvider: selectionArgs: 1002
,08-31 08:51:56.875  1017  1448 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:56.875  1017  1448 D SettingsProvider: ret = -1
08-31 08:51:56.875  1017  1486 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 08:51:56.875  1017  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:56.875  1017  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 08:51:56.875  1017  1486 D SettingsProvider: selectionArgs: false
08-31 08:51:56.875  1017  1486 D SettingsProvider: selectionArgs: 1002
08-31 08:51:56.875  1017  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 08:51:56.875  1017  1486 D SettingsProvider: ret = -1
08-31 08:51:56.875  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 08:51:56.875  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 08:51:56.875  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:56.875  1017  1029 D SettingsProvider: selectionArgs: false
08-31 08:51:56.875  1017  1029 D SettingsProvider: selectionArgs: 1002
08-31 08:51:56.875  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 08:51:56.875  1017  1029 D SettingsProvider: ret = -1
08-31 08:51:56.875  1017  3167 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 08:51:56.875  1017  3167 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:56.875  1017  3167 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:56.875  1017  3167 D SettingsProvider: selectionArgs: false
,08-31 08:51:56.875  1017  3167 D SettingsProvider: selectionArgs: 1002
08-31 08:51:56.875  1017  3167 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:56.875  1017  3167 D SettingsProvider: ret = -1
08-31 08:51:56.875  1017  1561 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-31 08:51:56.875  1017  1561 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
,08-31 08:51:56.875  1017  1561 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:56.875  1017  1561 D SettingsProvider: selectionArgs: false
08-31 08:51:56.875  1017  1561 D SettingsProvider: selectionArgs: 1002
,08-31 08:51:56.875  1017  1561 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 08:51:56.875  1017  1561 D SettingsProvider: ret = -1
,08-31 08:51:56.885  1017  1569 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:51:56.885  1017  1569 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:56.885  1017  1569 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:56.885  1017  1569 D SettingsProvider: selectionArgs: false
08-31 08:51:56.885  1017  1569 D SettingsProvider: selectionArgs: 1002
,08-31 08:51:56.885  1017  1569 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:56.885  1017  1569 D SettingsProvider: ret = -1
,08-31 08:51:56.895  1017  1100 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:51:56.895  1017  1100 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:56.895  1017  1100 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:56.895  1017  1100 D SettingsProvider: selectionArgs: false
,08-31 08:51:56.895  1017  1100 D SettingsProvider: selectionArgs: 1002
08-31 08:51:56.895  1017  1100 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:56.895  1017  1100 D SettingsProvider: ret = -1
,08-31 08:51:56.895  1017  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-31 08:51:56.895  1017  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:56.895  1017  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 08:51:56.895  1017  1478 D SettingsProvider: selectionArgs: false,
08-31 08:51:56.895  1017  1478 D SettingsProvider: selectionArgs: 1002
08-31 08:51:56.895  1017  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-31 08:51:56.895  1017  1478 D SettingsProvider: ret = -1
08-31 08:51:56.895  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-31 08:51:56.895  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-31 08:51:56.895  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:56.895  1017  1030 D SettingsProvider: selectionArgs: false
08-31 08:51:56.895  1017  1030 D SettingsProvider: selectionArgs: 1002
08-31 08:51:56.895  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:56.895  1017  1030 D SettingsProvider: ret = -1
,08-31 08:51:56.915  7443  7443 D BluetoothAdapterState: make
,08-31 08:51:56.925  7443  7443 I bluedroid: init,
,08-31 08:51:56.925  7443  7458 I BluetoothAdapterState: Entering OffState
,08-31 08:51:56.925  7443  7443 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-31 08:51:56.925  7443  7443 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 08:51:56.925  7443  7443 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 08:51:56.925  7443  7443 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 08:51:56.935  7443  7443 E bt-btif : btif_fetch_local_ble_random_bdaddr,
,08-31 08:51:56.935  7443  7443 I bluedroid: get_profile_interface socket
08-31 08:51:56.935  7443  7443 I bluedroid: get_profile_interface map_client
08-31 08:51:56.935  7443  7461 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-31 08:51:56.935  7443  7443 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-31 08:51:56.935  7443  7461 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-31 08:51:56.935  7443  7461 E BluetoothServiceJni: populateRssiValuesNative
,08-31 08:51:56.935  7443  7461 I bluedroid: getModelRssiValues
08-31 08:51:56.935  7443  7461 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 08:51:56.935  7443  7461 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 08:51:56.935  7443  7461 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-31 08:51:56.945  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 08:51:56.945  7443  7443 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:51:56.945  1017  3167 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 08:51:56.945  1017  3167 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:51:56.945  1017  3167 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:56.945  1017  3167 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:56.945  1017  3167 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:56.945  7443  7451 I bluedroid: config_hci_snoop_log
,08-31 08:51:56.955  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-31 08:51:56.955  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-31 08:51:56.955  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-31 08:51:56.955  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-31 08:51:56.955  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 08:51:56.955  7443  7443 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-31 08:51:56.965  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 08:51:56.965  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 08:51:56.965  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 08:51:56.965  7443  7458 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-31 08:51:56.975  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 08:51:56.975  7443  7458 D BluetoothAdapterProperties: Setting state to 11
,08-31 08:51:56.975  7443  7458 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-31 08:51:56.975  7443  7458 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:51:56.975  7443  7458 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 08:51:56.975  7443  7458 D BluetoothAdapterService: Autoconnection is available 
,08-31 08:51:56.975  7443  7458 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 08:51:56.975  7443  7458 D BluetoothSecureManager: getInstant: null
,08-31 08:51:56.975  7443  7458 D BluetoothSecureManager: calling getMethod for getService
,08-31 08:51:56.975  7443  7458 D BluetoothSecureManager: calling getService
,08-31 08:51:56.985  7443  7458 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1a610b3e
,08-31 08:51:56.985  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:56.985  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-31 08:51:56.985  1017  4351 D BluetoothSecureManagerService: isSecureModeEnabled
,08-31 08:51:56.985  1017  4351 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-31 08:51:56.995  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 08:51:56.995  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:51:56.995  1872  1872 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:51:56.995  1175  1175 D BluetoothTile:  getBluetoothState : 11
,08-31 08:51:56.995  7443  7458 D BtConfig.SecureMode: isSecureModeOn:false
08-31 08:51:56.995  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 08:51:57.005  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 08:51:57.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 08:51:57.005  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 08:51:57.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 08:51:57.005  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 08:51:57.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 08:51:57.005  3076  3076 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:51:57.005  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 08:51:57.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 08:51:57.005  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
08-31 08:51:57.005  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-31 08:51:57.005  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 08:51:57.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 08:51:57.005  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 08:51:57.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 08:51:57.005  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 08:51:57.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 08:51:57.005  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-31 08:51:57.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:51:57.005  7443  7458 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:51:57.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:51:57.015  7443  7458 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:51:57.015  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.015  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 08:51:57.015  7443  7458 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 08:51:57.015  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 08:51:57.015  1017  4351 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:51:57.015  7443  7458 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService,
08-31 08:51:57.015  1017  1448 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 08:51:57.015  1017  1561 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 08:51:57.015  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.015  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.015  1017  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:57.015  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:57.015  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:57.015  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 08:51:57.025  3076  3076 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:51:57.025  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:57.025  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 08:51:57.035  1017  4350 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-31 08:51:57.035  1017  4350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:57.035  1017  4350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:57.035  1017  4350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:57.035  1017  4350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:57.035  7443  7458 D BluetoothBondStateMachine: make
,08-31 08:51:57.035  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 08:51:57.035  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 08:51:57.035  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-31 08:51:57.045  7443  7464 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 08:51:57.045  7465  7465 E Zygote  : MountEmulatedStorage(),
08-31 08:51:57.045  7465  7465 I libpersona: KNOX_SDCARD checking this for 10055
08-31 08:51:57.045  7465  7465 E Zygote  : v2
08-31 08:51:57.045  7465  7465 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:57.045  7465  7465 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:57.045  7465  7465 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:51:57.055  7465  7465 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:51:57.055  1017  4350 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7465 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-31 08:51:57.055  1017  4351 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:51:57.055  1017  4351 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.055  1017  4351 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:57.055  1017  4351 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.055  1017  4351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.055  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 08:51:57.055  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 08:51:57.055  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 08:51:57.055  1017  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:57.055  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 08:51:57.055  7443  7443 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 08:51:57.055  7443  7443 D BtGatt.GattService: Received start request. Starting profile...
08-31 08:51:57.055  7443  7443 D BtGatt.GattService: start()
08-31 08:51:57.055  7443  7443 D BtGatt.GattService: start()
08-31 08:51:57.055  7443  7443 I bluedroid: get_profile_interface gatt
08-31 08:51:57.065  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
08-31 08:51:57.065  7443  7443 D BtGatt.AdvertiseManager: advertise manager created
08-31 08:51:57.065  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.065  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.065  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.065  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 08:51:57.065  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 08:51:57.065  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-31 08:51:57.065  1017  1569 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:57.065  1017  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.065  1017  1569 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.065  1017  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.065  1017  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.075  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-31 08:51:57.075  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:51:57.075  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 08:51:57.075  1017  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:57.075  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.075  7443  7443 D BtGatt.GattService: mStartError = false
08-31 08:51:57.075  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
08-31 08:51:57.075  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.075  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.075  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:51:57.075  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 08:51:57.075  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 08:51:57.075  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-31 08:51:57.075  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:51:57.075  7443  7443 D HeadsetService: Received start request. Starting profile...
08-31 08:51:57.075  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-31 08:51:57.075  7443  7443 D HeadsetService: start()
,08-31 08:51:57.085  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.085  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.085  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:51:57.085  7443  7443 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 08:51:57.085  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 08:51:57.085  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 08:51:57.085  1017  1567 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:57.085  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-31 08:51:57.085  1017  1567 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.085  7443  7443 D HeadsetStateMachine: make
,08-31 08:51:57.085  1017  1567 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.085  1017  1567 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.085  1017  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.085  7443  7443 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 08:51:57.085  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:57.085  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 08:51:57.085  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-31 08:51:57.085  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:51:57.085  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-31 08:51:57.085  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.085  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.085  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.095  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-31 08:51:57.095  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 08:51:57.095  7443  7458 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 08:51:57.095  1017  4351 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:57.095  1017  4351 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.095  1017  4351 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.095  1017  4351 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.095  1017  4351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:51:57.095  7465  7465 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:57.095  7465  7465 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:57.095  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:51:57.095  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:51:57.095  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:51:57.095  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:51:57.095  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:51:57.095  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:51:57.095  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 08:51:57.095  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 08:51:57.095  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 08:51:57.095  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 08:51:57.095  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 08:51:57.095  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 08:51:57.095  7443  7458 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 08:51:57.105  1017  1486 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-31 08:51:57.105  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.105  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:57.105  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.105  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 08:51:57.105  1017  1100 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-31 08:51:57.105  1017  1100 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.105  1017  1100 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:57.105  1017  1100 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.105  1017  1100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-31 08:51:57.105  7443  7443 I bluedroid: get_profile_interface handsfree,
,08-31 08:51:57.125  7443  7443 I DualScoManager: Instantiating Dual Sco Manager
08-31 08:51:57.125  7443  7443 I DualScoManager: Set HeadsetServiceHelper
,08-31 08:51:57.125  7465  7465 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 08:51:57.125  7443  7443 D BluetoothAtMessage: createCMTIContentObservers
,08-31 08:51:57.135  1017  4351 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-31 08:51:57.135  1017  4351 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:57.135  1017  4351 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 08:51:57.135  1017  4351 D SettingsProvider: selectionArgs: false
08-31 08:51:57.135  1017  4351 D SettingsProvider: selectionArgs: 1002
08-31 08:51:57.135  1017  4351 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 08:51:57.135  1017  4351 D SettingsProvider: ret = -1
,08-31 08:51:57.135  7443  7485 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 08:51:57.135  7443  7443 D HeadsetService: mStartError = false
08-31 08:51:57.135  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:57.135  7443  7443 D A2dpService: Received start request. Starting profile...
08-31 08:51:57.135  7443  7443 D A2dpService: start()
,08-31 08:51:57.135  7443  7485 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-31 08:51:57.135  7443  7485 D HeadsetStateMachine: map size, before remove : 0
08-31 08:51:57.145  7443  7485 D HeadsetStateMachine: map size, after remove: 0
,08-31 08:51:57.145  7443  7443 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 08:51:57.145  7443  7443 I bluedroid: get_profile_interface avrcp
,08-31 08:51:57.145  7443  7443 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 08:51:57.145  7443  7443 D Avrcp   : Initialize Media Controller
,08-31 08:51:57.155  7443  7443 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-31 08:51:57.155  7443  7443 E Avrcp   : getActiveSessions
,08-31 08:51:57.155  7443  7443 D Avrcp   : pick active media Controller
,08-31 08:51:57.155  7443  7443 D Avrcp   : Get the active Media Controller 
,08-31 08:51:57.155  7465  7465 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-31 08:51:57.165  7465  7465 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() ,
08-31 08:51:57.165  7465  7465 D UserAnalysis: Create SecureDbHelper
,08-31 08:51:57.165  7465  7465 D IntelligenceServiceApplication: onCreate()
,08-31 08:51:57.175  7443  7443 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 08:51:57.175  7443  7486 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 08:51:57.175  7443  7443 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 08:51:57.175  7443  7443 D A2dpStateMachine: make
,08-31 08:51:57.175  1017  1569 I ActivityManager: Killing 7119:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-31 08:51:57.175  7443  7443 I bluedroid: get_profile_interface a2dp
,08-31 08:51:57.175  7443  7488 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 08:51:57.175  7443  7443 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 08:51:57.175  7443  7443 D A2dpService: mStartError = false
08-31 08:51:57.175  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:57.175  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-31 08:51:57.175  7443  7443 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 08:51:57.175  7443  7487 D A2dpStateMachine: Enter Disconnected: -2
,08-31 08:51:57.185  7465  7465 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 08:51:57.185  7443  7443 D HidService: Received start request. Starting profile...
08-31 08:51:57.185  7443  7443 D HidService: start()
08-31 08:51:57.185  7443  7443 I bluedroid: get_profile_interface hidhost
08-31 08:51:57.185  7443  7443 D HidService: setHidService(): set to: null
08-31 08:51:57.185  7443  7443 D HidService: mStartError = false
08-31 08:51:57.185  1017  1366 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-31 08:51:57.185  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:57.185  7443  7443 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 08:51:57.185  7465  7465 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 08:51:57.185  7443  7443 D HealthService: Received start request. Starting profile...
08-31 08:51:57.185  7443  7443 D HealthService: start()
,08-31 08:51:57.185  7443  7443 I bluedroid: get_profile_interface health
08-31 08:51:57.185  7443  7443 D HealthService: mStartError = false
08-31 08:51:57.185  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:57.185  7443  7443 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 08:51:57.195  7465  7465 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-31 08:51:57.195  7443  7443 D PanService: Received start request. Starting profile...
08-31 08:51:57.195  7443  7443 D PanService: start()
08-31 08:51:57.195  7443  7443 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 08:51:57.195  7443  7443 I bluedroid: get_profile_interface pan
,08-31 08:51:57.195  7443  7486 D BluetoothMediaBrowser: no now playing list
08-31 08:51:57.195  7443  7486 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-31 08:51:57.195  7443  7443 D PanService: mStartError = false
08-31 08:51:57.195  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:57.195  7443  7443 D BluetoothMapService: Received start request. Starting profile...
08-31 08:51:57.195  7443  7443 D BluetoothMapService: start()
,08-31 08:51:57.195  7443  7443 D BluetoothMapService: mStartError = false
08-31 08:51:57.195  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:57.195  7443  7443 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-31 08:51:57.205  7443  7443 D SapService: Received start request. Starting profile...,
08-31 08:51:57.205  7443  7443 D SapService: start()
08-31 08:51:57.205  7443  7443 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 08:51:57.205  7443  7443 I bluedroid: get_profile_interface sap
08-31 08:51:57.205  7443  7443 D SapService: mStartError = false
,08-31 08:51:57.205  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
08-31 08:51:57.205  7443  7443 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 08:51:57.205  1429  1450 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 08:51:57.205  7443  7443 D HeadsetStateMachine: Proxy object connected
08-31 08:51:57.205  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-31 08:51:57.205  7443  7443 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-31 08:51:57.205  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 08:51:57.205  1429  1450 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 08:51:57.205  7443  7443 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 08:51:57.205  7443  7443 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-31 08:51:57.205  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 08:51:57.205  7443  7443 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 08:51:57.205  7443  7443 D BluetoothA2dp: Proxy object connected
,08-31 08:51:57.205  7443  7443 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-31 08:51:57.205  7443  7485 D HeadsetStateMachine: Disconnected process message: 11
08-31 08:51:57.205  7443  7485 D HeadsetStateMachine: Disconnected process message: 18
08-31 08:51:57.205  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 08:51:57.205  7443  7485 D HeadsetStateMachine: Disconnected process message: 10
08-31 08:51:57.205  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 08:51:57.205  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 08:51:57.205  7443  7485 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 08:51:57.205  7443  7485 D HeadsetStateMachine: Disconnected process message: 11
,08-31 08:51:57.205  1017  1561 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 08:51:57.215  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:57.215  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:51:57.215  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:57.215  1017  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:51:57.225  7493  7493 E Zygote  : MountEmulatedStorage()
,08-31 08:51:57.225  7493  7493 E Zygote  : v2
08-31 08:51:57.225  7493  7493 I libpersona: KNOX_SDCARD checking this for 10105
08-31 08:51:57.225  7493  7493 I libpersona: KNOX_SDCARD not a persona
,08-31 08:51:57.225  7493  7493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:51:57.225  1017  1561 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7493 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-31 08:51:57.225  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-31 08:51:57.225  7493  7493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:51:57.235  7493  7493 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:51:57.255  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-31 08:51:57.255  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 08:51:57.255  7443  7458 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-31 08:51:57.255  7443  7458 I bluedroid: enable
08-31 08:51:57.255  7443  7458 I bt_hci_bdroid: init
,08-31 08:51:57.255  7443  7509 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 08:51:57.265  7493  7493 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:51:57.265  7493  7493 D ActivityThread: Added TimaKeyStore provider
,08-31 08:51:57.265  7443  7458 I bt_vendor: bt-vendor : init
08-31 08:51:57.265  7443  7458 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 08:51:57.265  7443  7458 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 08:51:57.265  7443  7458 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-31 08:51:57.265  7443  7458 D bt_userial_mct: userial_init
08-31 08:51:57.265  7443  7458 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 08:51:57.265  7443  7458 I bt_vendor: Starting hciattach daemon
08-31 08:51:57.265  7443  7458 I bt_vendor: try to set false
,08-31 08:51:57.265  7443  7458 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 08:51:57.265  7443  7458 I bt_vendor: Starting hciattach daemon
08-31 08:51:57.265  7443  7458 I bt_vendor: try to set true
,08-31 08:51:57.285  7513  7513 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-31 08:51:57.335  7519  7519 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-31 08:51:57.345  7520  7520 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 08:51:57.355  7524  7524 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 08:51:57.365  7525  7525 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-31 08:51:57.375  7526  7526 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 08:51:57.385  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 08:51:57.425   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 08:51:57.425   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:57.425  7493  7530 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 08:51:57.425   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 08:51:57.425   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 08:51:57.425  7493  7530 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 08:51:57.605  7493  7493 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
,08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:57.605  7493  7493 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.ma,in(ActivityThread.java:6145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:57.605  1017  1250 I ActivityManager: Killing 7129:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
08-31 08:51:57.605  7493  7493 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:57.605  7493  7493 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 08:51:57.6,05  7493  7493 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:57.605  7493  7493 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:57.605  7493  7493 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:57.605  7493  7493 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:57.605  7493  7493 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:51:57.605  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:51:57.605   291   291 E SMD     : DCD OFF
08-31 08:51:57.615  7542  7542 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
08-31 08:51:57.615  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-31 08:51:57.625  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-31 08:51:57.625  7543  7543 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 08:51:57.665  7443  7458 I bt_vendor: bluetooth satus is on
08-31 08:51:57.665  7443  7511 D bt_userial_mct: userial_open(port:0)
08-31 08:51:57.665  7443  7511 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-31 08:51:57.675  7443  7511 I bt_vendor: Done intiailizing UART
08-31 08:51:57.675  7493  7535 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-31 08:51:57.675  7443  7511 I bt_vendor: Done intiailizing UART
08-31 08:51:57.675  7443  7511 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-31 08:51:57.675  7443  7511 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 08:51:57.675  7443  7545 D bt_userial_mct: Entering userial_read_thread()
,08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_SAP
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 08:51:57.695  7443  7509 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 08:51:57.785  7443  7509 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-31 08:51:57.785  7443  7509 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41b5ed1 
,08-31 08:51:57.785  7443  7509 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41b5ed1 
,08-31 08:51:57.795  7443  7461 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-31 08:51:57.795  7443  7461 E bt-btif : Calling BTA_HhEnable
,08-31 08:51:57.805  7443  7461 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 08:51:57.805  7443  7461 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-31 08:51:57.805  7443  7461 E BluetoothServiceJni: populateRssiValuesNative
08-31 08:51:57.805  7443  7461 I bluedroid: getModelRssiValues
,08-31 08:51:57.805  7443  7461 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 08:51:57.805  7443  7461 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 08:51:57.855  1017  1448 I art     : Explicit concurrent mark sweep GC freed 74031(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.384ms total 148.923ms
,08-31 08:51:57.855  1017  1569 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:57.855  1017  1569 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:57.855  1017  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:57.855  1017  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 08:51:57.855  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 08:51:57.855  7443  7461 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-31 08:51:57.865  7443  7461 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 08:51:57.865  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:57.865  7443  7461 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:51:57.865  7443  7461 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 08:51:57.865  7443  7461 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-31 08:51:57.865  7443  7461 E bt-btif : HC lpm_result_cb 1
08-31 08:51:57.865  7443  7461 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-31 08:51:57.865  7443  7461 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 08:51:57.865  7443  7461 E bt-btif : btif_sock_init: !vhci_init
08-31 08:51:57.865  7443  7461 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 08:51:57.865  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.865  7443  7461 D IOP_DB_BT: db_open: db_open : handle 3028332560l, read 13894 bytes onto local cache
08-31 08:51:57.865  7443  7461 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-31 08:51:57.865  7443  7461 D IOP_DB_BT: db_query: result 1
08-31 08:51:57.865  7443  7461 I         : iop_db_open: iop_db_open status 0
,08-31 08:51:57.865  7443  7545 E bt_mct  : hci lib postload completed
08-31 08:51:57.865  7443  7461 D bte_conf: Device ID record 1 : primary
08-31 08:51:57.865  7443  7461 D bte_conf:   vendorId            = 0075
08-31 08:51:57.865  7443  7461 D bte_conf:   vendorIdSource      = 0001
08-31 08:51:57.865  7443  7461 D bte_conf:   product             = 0100
08-31 08:51:57.865  7443  7461 D bte_conf:   version             = 0200
08-31 08:51:57.865  7443  7461 D bte_conf:   clientExecutableURL = 
08-31 08:51:57.865  7443  7461 D bte_conf:   serviceDescription  = 
08-31 08:51:57.865  7443  7461 D bte_conf:   documentationURL    = 
08-31 08:51:57.865  7443  7461 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 08:51:57.865  7443  7461 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 08:51:57.875  7443  7458 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-31 08:51:57.875  7443  7458 D BluetoothAdapterProperties: ScanMode =  20
08-31 08:51:57.875  7443  7458 D BluetoothAdapterProperties: State =  11
,08-31 08:51:57.875  1017  1567 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 08:51:57.875  7443  7458 D BluetoothAdapterProperties: Setting state to 12
08-31 08:51:57.875  7443  7458 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 08:51:57.875  7443  7461 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 08:51:57.875  7443  7461 D BluetoothAdapterProperties: Scan Mode:21
08-31 08:51:57.875  7443  7461 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 08:51:57.875  1017  1569 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-31 08:51:57.875  1017  1569 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:51:57.875  1017  1569 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:51:57.875  1017  1569 D SettingsProvider: selectionArgs: false
08-31 08:51:57.875  1017  1569 D SettingsProvider: selectionArgs: 1002
08-31 08:51:57.875  1017  1569 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:51:57.875  1017  1569 D SettingsProvider: ret = -1
08-31 08:51:57.875  7443  7458 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:51:57.875  7443  7458 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 08:51:57.875  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:57.875  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.885  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.885  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.885  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.885  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:57.885  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:57.885  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:57.885  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:57.885  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:57.885  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:57.885  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:57.885  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:51:57.885  7443  7458 D BluetoothAdapterService: Autoconnection is available 
08-31 08:51:57.885  7443  7458 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 08:51:57.885  7443  7458 D BluetoothAdapterService: starting service from this receiver
,08-31 08:51:57.885  1017  1100 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:51:57.885  1017  1100 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.895  1175  1184 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:51:57.895  1175  1184 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:51:57.895  2003  2011 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:51:57.895  2003  2011 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:51:57.895  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 08:51:57.895  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:51:57.895  1017  1100 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.895  1017  1100 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.895  1017  1100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:51:57.895  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:51:57.895  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 08:51:57.895  7443  7458 I BluetoothAdapterState: Entering On State from state = 11
08-31 08:51:57.895  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.895  1017  1017 D BluetoothA2dp: Proxy object connected
,08-31 08:51:57.895  1442  1460 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:51:57.895  1442  1460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:51:57.895  3076  3084 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:51:57.895  3076  3084 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:51:57.905  1017  1046 D BluetoothPan: Binding service...
,08-31 08:51:57.905  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 08:51:57.905  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.905  1429  1441 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:51:57.905  1429  1441 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:51:57.905  3076  3087 D BluetoothPan: Binding service...
,08-31 08:51:57.905  7443  7443 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-31 08:51:57.905  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:57.905  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:57.905  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:57.905  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:57.905  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:57.905  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:57.905  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:57.905  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:51:57.905  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 08:51:57.905  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.905  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.905  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.905  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.915  3076  3084 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 08:51:57.915  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:51:57.915  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-31 08:51:57.915  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.915  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:57.915  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.915  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.915  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:51:57.915  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:51:57.915  3076  3087 D Bluetoothsap: onBluetoothStateChange: up=true
,08-31 08:51:57.915  3076  3087 D Bluetoothsap: Binding service...
,08-31 08:51:57.915  7443  7443 I BluetoothPbapService: Handler(): got msg=1
,08-31 08:51:57.925  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 08:51:57.925  3076  3087 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-31 08:51:57.925  1017  1100 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 08:51:57.925  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-31 08:51:57.925  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-31 08:51:57.925  3076  3076 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 08:51:57.925  3076  3076 D PanProfile: Bluetooth service connected
,08-31 08:51:57.925  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.925  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.925  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.925  3076  3087 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 08:51:57.925  1458  1479 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:51:57.925  1458  1479 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:51:57.925  3076  3087 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 08:51:57.925  7443  7553 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 08:51:57.925  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-31 08:51:57.925  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.935  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.935  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.935  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.935  3076  3076 D BluetoothMap: Proxy object connected
,08-31 08:51:57.935  3076  3076 D MapProfile: Bluetooth service connected
08-31 08:51:57.935  3076  3076 D BluetoothMap: getConnectedDevices()
,08-31 08:51:57.935  1429  3300 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 08:51:57.935  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:51:57.935  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:51:57.935  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.935  7443  7553 D BluetoothSocket: bindListen(): myUserId = 0
08-31 08:51:57.935  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.935  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.935  7443  7553 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:51:57.935  1429  3300 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:51:57.935  7443  7553 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-31 08:51:57.935  7443  7553 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:51:57.935  7443  7553 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:51:57.935  7443  7553 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@307d9413
,08-31 08:51:57.935  7443  7553 D BluetoothSocket: channel: 19
08-31 08:51:57.935  7443  7553 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 08:51:57.935  3076  3076 D Bluetoothsap: BluetoothSAP Proxy object connected
08-31 08:51:57.935  3076  3076 D SapProfile: Bluetooth service connected
08-31 08:51:57.935  3076  3076 D Bluetoothsap: getConnectedDevices()
,08-31 08:51:57.935  1458  1829 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:51:57.945  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:51:57.945  3076  3076 D BluetoothPbap: Proxy object connected
08-31 08:51:57.945  3076  3076 D PbapServerProfile: Bluetooth service connected
,08-31 08:51:57.945  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:51:57.945  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.945  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.945  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.945  1458  1829 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:51:57.945  7493  7503 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:51:57.945  7493  7503 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:51:57.945  3076  7552 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:51:57.945  3076  7552 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:51:57.945  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 08:51:57.945  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.945  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:57.945  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.945  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.945  3076  3076 D BluetoothA2dp: Proxy object connected
,08-31 08:51:57.945  3076  3076 D A2dpProfile: Bluetooth service connected
,08-31 08:51:57.955  3076  3084 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:51:57.955  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:51:57.955  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:51:57.955  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.955  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.955  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.955  3076  3084 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:51:57.955  3076  7552 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 08:51:57.955  3076  3076 D HeadsetProfile: Bluetooth service connected
,08-31 08:51:57.955  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-31 08:51:57.955  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.955  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.955  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.955  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.955  6721  6735 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:51:57.955  6721  6735 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:51:57.955  3076  3076 D BluetoothInputDevice: Proxy object connected
08-31 08:51:57.955  3076  3076 D HidProfile: Bluetooth service connected
08-31 08:51:57.955  7443  7550 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:51:57.955  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:51:57.965  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:51:57.965  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:51:57.965  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:51:57.965  1429  1441 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:51:57.965  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:51:57.965  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:51:57.965  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.965  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.965  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.965  1429  1441 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 08:51:57.965  7443  7451 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:51:57.965  7443  7451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:51:57.965  1429  3300 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:51:57.965  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 08:51:57.965  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:51:57.965  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:57.965  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:57.965  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:57.975  1429  3300 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:51:57.975  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-31 08:51:57.975  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 08:51:57.975  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:57.975  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-31 08:51:57.975  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 08:51:57.975  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-31 08:51:57.985  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 08:51:57.985  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:57.985  1175  1175 D BluetoothTile:  getBluetoothState : 12
08-31 08:51:57.985  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1b2f977f, true
,08-31 08:51:57.985  1872  1872 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 08:51:57.985  3076  3076 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:51:57.985  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:51:57.985  1429  1429 D BluetoothHeadset: registerMessageListener
,08-31 08:51:57.995  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:57.995  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:57.995  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:51:57.995  1017  1250 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:51:57.995  1017  1250 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 08:51:57.995  1017  1250 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:57.995  1017  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:51:57.995  1017  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:57.995  1017  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 08:51:57.995  1017  1478 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 08:51:57.995  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:51:58.005  7443  7550 D HeadsetService: registerMessageListener
,08-31 08:51:58.005  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:51:58.005  3076  3076 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-31 08:51:58.005  3076  3076 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-31 08:51:58.005  7443  7550 D HeadsetService: registerMessageListener
,08-31 08:51:58.005  7443  7485 D HeadsetStateMachine: Disconnected process message: 70
08-31 08:51:58.005  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-31 08:51:58.005  3076  3076 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 08:51:58.005  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 08:51:58.005  3076  3076 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-31 08:51:58.005  7443  7485 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2480650
,08-31 08:51:58.015  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-31 08:51:58.015  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 08:51:58.015  7443  7555 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-31 08:51:58.015  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 08:51:58.015  7443  7555 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 08:51:58.015  7443  7555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:51:58.025  7443  7555 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-31 08:51:58.025  7443  7555 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:51:58.025  7443  7555 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:51:58.025  7443  7555 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c774049
08-31 08:51:58.025  7443  7555 D BluetoothSocket: channel: 5
,08-31 08:51:58.025  3076  3076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 08:51:58.025  7443  7485 D HeadsetStateMachine: Disconnected process message: 9
,08-31 08:51:58.025  1017  1448 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 08:51:58.025  1017  1448 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-31 08:51:58.025  7443  7485 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 08:51:58.025  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:58.025  1017  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:58.025  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:51:58.035   286  1600 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-31 08:51:58.035   286  1600 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 08:51:58.035   286  1600 V voice   : voice_set_parameters: exit with code(-2)
08-31 08:51:58.035   286  1600 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 08:51:58.035   286  1600 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 08:51:58.035   286  1600 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 08:51:58.035   286  1600 V audio_hw_primary: adev_set_parameters: exit
,08-31 08:51:58.035  3076  3076 D DockEventReceiver: finishStartingService: stopping service
08-31 08:51:58.035  7443  7485 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 08:51:58.035  3076  3076 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:51:58.035  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:51:58.035  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 08:51:58.045  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:51:58.045  7443  7443 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 08:51:58.045  1017  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:51:58.055  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 08:51:58.055  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:58.055  1017  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:58.055  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:58.065  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 08:51:58.065  1017  1448 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:51:58.065  1017  1448 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 08:51:58.065  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:58.065  1017  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:58.065  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:58.075  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 08:51:58.075  2003  7561 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 08:51:58.085  1017  1250 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:58.085  1017  4351 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 08:51:58.085  1017  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:51:58.085  1017  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:58.085  1017  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:58.095  1017  4350 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:51:58.105  7443  7565 D BluetoothSocket: bindListen(): myUserId = 0
08-31 08:51:58.105  7443  7565 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:51:58.105  1017  4350 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:58.105  1017  4350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:58.105  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:51:58.105  7443  7565 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-31 08:51:58.105  7443  7565 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:51:58.105  7443  7565 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:51:58.105  7443  7565 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22b1728b
,08-31 08:51:58.105  7443  7565 D BluetoothSocket: channel: 12
08-31 08:51:58.105  7443  7565 I BtOppRfcommListener: Accept thread started.
,08-31 08:51:58.115  2003  7561 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-31 08:51:59.735  6721  6775 D BluetoothAdapter: disable()
,08-31 08:51:59.735  1017  1250 D SettingsProvider: name = bluetooth_on
,08-31 08:51:59.745  7443  7458 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-31 08:51:59.745  1017  3167 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:51:59.745  7443  7458 D BluetoothAdapterProperties: Setting state to 13
08-31 08:51:59.745  1017  3167 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-31 08:51:59.745  7443  7458 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 08:51:59.745  7443  7458 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:51:59.745  7443  7458 D BluetoothAdapterService: updateAdapterState state is 13
,08-31 08:51:59.745  1017  3167 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:59.745  1017  3167 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-31 08:51:59.745  1017  3167 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:51:59.745  7443  7443 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-31 08:51:59.745  7443  7443 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@38f64f68, channel: 19, state: LISTENING
08-31 08:51:59.745  7443  7443 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@38f64f68, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@307d9413, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f81af81mSocket: android.net.LocalSocket@2c773826 impl:android.net.LocalSocketImpl@1542ac67 fd:FileDescriptor[74]
08-31 08:51:59.745  7443  7443 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c773826 impl:android.net.LocalSocketImpl@1542ac67 fd:FileDescriptor[74]
,08-31 08:51:59.745  3076  3076 D BluetoothPbap: Proxy object disconnected
08-31 08:51:59.745  3076  3076 D PbapServerProfile: Bluetooth service disconnected
08-31 08:51:59.745  7443  7458 D BluetoothAdapterService: Autoconnection is available 
08-31 08:51:59.745  7443  7458 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-31 08:51:59.745  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:51:59.745  7443  7458 D BluetoothAdapterService: terminating service from this receiver
08-31 08:51:59.755  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-31 08:51:59.755  1175  1175 D BluetoothTile:  onBluetoothStateChange:
08-31 08:51:59.755  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
08-31 08:51:59.755  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:51:59.765  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:51:59.765  1175  1175 D BluetoothTile:  getBluetoothState : 13
08-31 08:51:59.765  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:51:59.765  1872  1872 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0,
08-31 08:51:59.765  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 08:51:59.765  1017  1567 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:51:59.765  7443  7443 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f18c2bd, channel: 5, state: LISTENING
08-31 08:51:59.765  3076  3076 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:59.775  7443  7443 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f18c2bd, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c774049, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@140eb0b2mSocket: android.net.LocalSocket@1fc3a803 impl:android.net.LocalSocketImpl@18d1a380 fd:FileDescriptor[76]
08-31 08:51:59.775  7443  7443 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1fc3a803 impl:android.net.LocalSocketImpl@18d1a380 fd:FileDescriptor[76]
,08-31 08:51:59.775  1017  4351 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 08:51:59.775  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 08:51:59.775  7443  7443 I BtOppRfcommListener: stopping Accept Thread
08-31 08:51:59.775  7443  7443 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2613cdb9, channel: 12, state: LISTENING
08-31 08:51:59.775  7443  7443 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2613cdb9, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22b1728b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@153325femSocket: android.net.LocalSocket@3ccec15f impl:android.net.LocalSocketImpl@116d77ac fd:FileDescriptor[79]
08-31 08:51:59.775  7443  7443 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ccec15f impl:android.net.LocalSocketImpl@116d77ac fd:FileDescriptor[79]
,08-31 08:51:59.775  7443  7565 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:51:59.775  7443  7565 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 08:51:59.775  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:59.775  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:59.775  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:59.775  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:59.775  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:59.775  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:59.775  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:59.775  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:59.775  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:51:59.785  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:59.785  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:51:59.785  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 08:51:59.785  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:59.785  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:59.785  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:51:59.785  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 08:51:59.785  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 08:51:59.785  7443  7458 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 08:51:59.785  7443  7458 D BluetoothAdapterProperties: mDiscovering is false
,08-31 08:51:59.785  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:59.785  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:51:59.785  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 08:51:59.785  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:59.785  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:59.785  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:59.785  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:59.785  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:59.785  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:59.785  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:59.785  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:59.785  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:51:59.795  1017  1567 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 08:51:59.795  7443  7458 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-31 08:51:59.795  6721  6721 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:59.795  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:51:59.795  3076  3076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:51:59.805  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:59.805  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:59.805  7443  7461 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 08:51:59.805  7443  7461 D BluetoothAdapterProperties: Scan Mode:20
,08-31 08:51:59.815  7443  7458 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-31 08:51:59.815  1017  1569 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 08:51:59.815  7443  7458 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-31 08:51:59.815  1017  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-31 08:51:59.815  1017  1569 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:51:59.815  1017  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:51:59.815  1017  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:51:59.815  7443  7458 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-31 08:51:59.815  7443  7458 E bt-btif : cmd socket is not created
,08-31 08:51:59.815  7443  7458 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 08:51:59.815  7443  7509 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-31 08:51:59.815  7443  7509 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-31 08:51:59.815  7443  7509 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 08:51:59.825  7443  7509 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 08:51:59.825  7443  7509 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 08:51:59.835  3076  3076 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:51:59.865  3076  3076 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:51:59.875  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:59.875  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 08:51:59.875  7443  7443 V BluetoothOppManager: cleanUp...
,08-31 08:51:59.895  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 08:51:59.905  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 08:51:59.905  1017  1440 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 08:51:59.915  1017  1440 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-31 08:51:59.915  1017  1440 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-31 08:51:59.915  1017  1440 D BatteryService: stay LED for fully charged
08-31 08:51:59.915  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 08:51:59.915  1017  1017 I MotionRecognitionService: Plugged
,08-31 08:51:59.915  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 08:51:59.915  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 08:51:59.915  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 08:51:59.925  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 08:51:59.925  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 08:51:59.925  7443  7443 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-31 08:51:59.925  7443  7485 D HeadsetStateMachine: Disconnected process message: 10
,08-31 08:51:59.935  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 08:51:59.935  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 08:51:59.945  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 08:51:59.945  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 08:51:59.945  1175  1175 D SViewCoverView: level :100 plugged : 2
,08-31 08:51:59.985  1017  1095 V AlarmManager: waitForAlarm result :8
,08-31 08:52:00.025  7443  7509 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 08:52:00.025  7443  7509 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 08:52:00.025  7443  7509 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:52:00.025  7443  7509 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 08:52:00.025  7443  7509 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 08:52:00.025  7443  7509 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:52:00.025  7443  7509 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 08:52:00.025  7443  7509 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 08:52:00.025  7443  7545 I bt_userial_mct: exiting userial_read_thread
08-31 08:52:00.025  7443  7545 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 08:52:00.025  7443  7461 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-31 08:52:00.025  7443  7511 I bt_vendor: hw_epilog_process
08-31 08:52:00.025  7443  7461 D bt_userial_mct: userial_close
08-31 08:52:00.025  7443  7509 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:52:00.025  7443  7509 W bt-btif : ag scb idx 1 not allocated
08-31 08:52:00.025  7443  7509 W bt-btif : ag scb idx 2 not allocated
08-31 08:52:00.025  7443  7509 E bt-btif : BTA AG is already disabled, ignoring ...
,08-31 08:52:00.025  7443  7461 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-31 08:52:00.625   291   291 E SMD     : DCD OFF
,08-31 08:52:00.715  1017  1049 I PowerManagerService: [PWL] Off : 75s ago
,08-31 08:52:00.715  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-31 08:52:00.715  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-31 08:52:00.715  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=12250)
08-31 08:52:00.715  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=7443, ws=null) (elapsedTime=3027)
08-31 08:52:00.715  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2683)
08-31 08:52:00.715  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2680)
,08-31 08:52:00.955  7443  7461 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-31 08:52:00.955  7443  7461 I bt_vendor: bluetooth satus is on
08-31 08:52:00.955  7443  7461 I bt_vendor: bt-vendor : resetting BT status
08-31 08:52:00.955  7443  7461 I bt_vendor: Starting hciattach daemon
08-31 08:52:00.955  7443  7461 I bt_vendor: try to set false
,08-31 08:52:00.955  7443  7461 I bt_vendor: Starting hciattach daemon
08-31 08:52:00.955  7443  7461 I bt_vendor: try to set false
,08-31 08:52:00.955  7443  7461 I bt_vendor: cleanup
08-31 08:52:00.955  7443  7509 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 08:52:00.955  7443  7461 I GKI_LINUX: GKI_exit_task 0 done
08-31 08:52:00.955  7443  7461 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 08:52:00.955  7443  7458 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 08:52:00.955  7443  7458 D BtConfig.SecureMode: isSecureModeOn:false
08-31 08:52:00.955  7443  7458 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-31 08:52:00.955  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 08:52:00.955  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 08:52:00.955  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-31 08:52:00.965  1017  1100 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:00.965  1017  1100 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 08:52:00.965  1017  1100 W ActivityManager: userId = 0, bbcId = -10000,
08-31 08:52:00.965  1017  1100 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:00.965  1017  1100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:00.965  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 08:52:00.965  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 08:52:00.965  7443  7443 D BtGatt.DebugUtils: handleDebugAction() action=null,
08-31 08:52:00.965  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 08:52:00.965  7443  7443 D BtGatt.GattService: Received stop request...Stopping profile...,
08-31 08:52:00.965  1017  4350 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:00.965  7443  7443 D BtGatt.GattService: stop(),
,08-31 08:52:00.965  1017  4350 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 08:52:00.965  7443  7443 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 08:52:00.975  1017  4350 W ActivityManager: userId = 0, bbcId = -10000,
08-31 08:52:00.975  1017  4350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:00.975  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-31 08:52:00.975  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
08-31 08:52:00.975  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 08:52:00.975  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 08:52:00.975  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 08:52:00.975  1017  1440 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:00.975  1017  1440 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:52:00.975  1017  1440 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:00.975  1017  1440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:00.975  1017  1440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:00.975  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-31 08:52:00.975  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 08:52:00.985  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 08:52:00.985  1017  1567 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:00.985  1017  1567 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 08:52:00.985  1017  1567 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:00.985  1017  1567 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:00.985  1017  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:00.985  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-31 08:52:00.985  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 08:52:00.985  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 08:52:00.985  1017  4351 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:00.985  1017  4351 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 08:52:00.985  1017  4351 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:00.985  1017  4351 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:00.985  1017  4351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:00.985  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 08:52:00.985  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 08:52:00.985  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 08:52:00.995  1017  4347 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:00.995  1017  4347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-31 08:52:00.995  1017  4347 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:00.995  1017  4347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:00.995  1017  4347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:00.995  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 08:52:00.995  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 08:52:00.995  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 08:52:00.995  1017  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:00.995  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 08:52:00.995  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:00.995  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:00.995  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:00.995  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-31 08:52:00.995  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 08:52:00.995  7443  7458 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 08:52:00.995  1017  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:00.995  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 08:52:01.005  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:01.005  1017  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:01.005  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:01.005  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:52:01.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:52:01.005  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:52:01.005  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:52:01.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:52:01.005  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:52:01.005  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,08-31 08:52:01.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 08:52:01.005  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 08:52:01.005  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-31 08:52:01.005  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 08:52:01.005  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 08:52:01.005  7443  7458 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 08:52:01.005  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-31 08:52:01.005  7443  7443 D HeadsetService: Received stop request...Stopping profile...,
08-31 08:52:01.005  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:52:01.015  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-31 08:52:01.015  3076  3076 D HeadsetProfile: Bluetooth service disconnected
,08-31 08:52:01.015  7443  7443 D A2dpService: Received stop request...Stopping profile...
,08-31 08:52:01.015  7443  7487 D A2dpStateMachine: Exit Disconnected: -1
,08-31 08:52:01.015  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:52:01.015  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-31 08:52:01.015  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 08:52:01.015  7443  7443 D HidService: Received stop request...Stopping profile...
,08-31 08:52:01.015  7443  7443 D HidService: Stopping Bluetooth HidService
,08-31 08:52:01.015  7443  7443 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 08:52:01.025  7443  7443 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 08:52:01.025  7443  7443 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 08:52:01.025  3076  3076 D BluetoothA2dp: Proxy object disconnected
08-31 08:52:01.025  3076  3076 D A2dpProfile: Bluetooth service disconnected
08-31 08:52:01.025  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:52:01.025  7443  7443 D HealthService: Received stop request...Stopping profile...
,08-31 08:52:01.025  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:52:01.025  7443  7443 D PanService: Received stop request...Stopping profile...
08-31 08:52:01.025  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:52:01.025  3076  3076 D BluetoothInputDevice: Proxy object disconnected
,08-31 08:52:01.025  3076  3076 D HidProfile: Bluetooth service disconnected
08-31 08:52:01.025  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 08:52:01.025  3076  3076 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 08:52:01.025  3076  3076 D PanProfile: Bluetooth service disconnected
,08-31 08:52:01.025  7443  7443 D BluetoothMapService: Received stop request...Stopping profile...
,08-31 08:52:01.025  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:52:01.035  7443  7443 D SapService: Received stop request...Stopping profile...
08-31 08:52:01.035  7443  7443 D SapService: Stopping Bluetooth SapService
08-31 08:52:01.035  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fbd9c1
,08-31 08:52:01.035  3076  3076 D BluetoothMap: Proxy object disconnected
08-31 08:52:01.035  3076  3076 D MapProfile: Bluetooth service disconnected
08-31 08:52:01.035  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-31 08:52:01.035  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:52:01.035  7443  7443 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 08:52:01.035  3076  3076 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-31 08:52:01.035  3076  3076 D SapProfile: Bluetooth service disconnected
,08-31 08:52:01.035  7443  7443 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 08:52:01.035  7443  7443 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 08:52:01.035  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-31 08:52:01.035  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:52:01.035  7443  7443 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 08:52:01.035  7443  7443 D BluetoothA2dp: Proxy object disconnected
08-31 08:52:01.035  7443  7443 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-31 08:52:01.035  7443  7488 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 08:52:01.035  7443  7443 I GKI_LINUX: GKI_exit_task 2 done
,08-31 08:52:01.035  7443  7443 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-31 08:52:01.035  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-31 08:52:01.035  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 08:52:01.035  7443  7443 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-31 08:52:01.045  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-31 08:52:01.045  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:52:01.045  7443  7443 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-31 08:52:01.045  7443  7443 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-31 08:52:01.045  7443  7443 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-31 08:52:01.045  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-31 08:52:01.045  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:52:01.045  7443  7443 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 08:52:01.045  7443  7443 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...,
08-31 08:52:01.045  7443  7443 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 08:52:01.045  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-31 08:52:01.045  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 08:52:01.045  7443  7443 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-31 08:52:01.045  7443  7443 E BluetoothAdapterService(66836929): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-31 08:52:01.045  7443  7443 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 08:52:01.045  7443  7443 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-31 08:52:01.045  7443  7458 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-31 08:52:01.045  7443  7458 D BluetoothAdapterProperties: Setting state to 10
08-31 08:52:01.045  7443  7458 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10,
08-31 08:52:01.045  7443  7458 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:52:01.045  7443  7458 D BluetoothAdapterService: updateAdapterState state is 10
08-31 08:52:01.045  7443  7458 D BluetoothAdapterService: Autoconnection is available 
08-31 08:52:01.045  7443  7458 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-31 08:52:01.045  7443  7458 I BluetoothAdapterState: Entering OffState,
,08-31 08:52:01.045  1175  1200 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:01.045  1175  1200 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:01.045  2003  2012 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:01.045  2003  2012 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:01.045  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 08:52:01.045  1442  1460 D BluetoothAdapter: onBluetoothStateChange: up=false,
08-31 08:52:01.045  1442  1460 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:01.045  3076  7552 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:01.045  3076  7552 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:01.055  1429  1450 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:01.055  1429  1450 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:52:01.055  3076  3084 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 08:52:01.055  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:01.055  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:01.055  3076  7552 D Bluetoothsap: onBluetoothStateChange: up=false
08-31 08:52:01.055  3076  7552 D Bluetoothsap: Unbinding service...
,08-31 08:52:01.055  1458  1479 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 08:52:01.055  1458  1479 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:01.055  3076  3087 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 08:52:01.055  7493  7503 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:52:01.055  7493  7503 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:52:01.055  3076  3084 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 08:52:01.055  3076  3087 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 08:52:01.055  6721  6732 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:52:01.055  6721  6732 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 08:52:01.055  6721  6732 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-31 08:52:01.055  6721  6732 D BluetoothLeAdvertiser: Exit stop advertising
08-31 08:52:01.055  6721  6732 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-31 08:52:01.055  6721  6732 D BluetoothLeScanner: Exiting stopAllScan
,08-31 08:52:01.055  7443  7550 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 08:52:01.065  7443  7452 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 08:52:01.065  7443  7452 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 08:52:01.065  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 08:52:01.065  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 08:52:01.075  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:01.075  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-31 08:52:01.075  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 08:52:01.075  1175  1175 D BluetoothAdapter: 765140552: getState() :  mService = null. Returning STATE_OFF
08-31 08:52:01.075  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 08:52:01.075  1175  1722 D BluetoothAdapter: 765140552: getState() :  mService = null. Returning STATE_OFF
,08-31 08:52:01.075  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:01.075  1175  1175 D BluetoothTile:  getBluetoothState : 10
,08-31 08:52:01.075  1175  1175 D BluetoothAdapter: 765140552: getState() :  mService = null. Returning STATE_OFF
08-31 08:52:01.075  1175  1175 D BluetoothAdapter: 765140552: getState() :  mService = null. Returning STATE_OFF
08-31 08:52:01.075  7443  7461 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-31 08:52:01.075  1017  3167 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 08:52:01.075  1175  1722 D BluetoothAdapter: 765140552: getState() :  mService = null. Returning STATE_OFF
,08-31 08:52:01.075  1872  1872 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:52:01.085  1017  4350 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 08:52:01.085  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 08:52:01.085  2003  2168 D BluetoothAdapter: 216578660: getState() :  mService = null. Returning STATE_OFF
,08-31 08:52:01.085  2003  2168 D BluetoothAdapter: 216578660: getState() :  mService = null. Returning STATE_OFF
,08-31 08:52:01.085  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:01.085  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:01.085  7443  7443 I GKI_LINUX: GKI_exit_task 1 done
08-31 08:52:01.085  7443  7443 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-31 08:52:01.085  7443  7443 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 08:52:01.085  1017  1440 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 08:52:01.085  1017  1440 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 08:52:01.085  1017  1440 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:01.085  3076  3076 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:01.085  1017  1440 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:01.085  1017  1440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:52:01.095  3076  3076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:52:01.095  1017  1448 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 08:52:01.095  1017  1448 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-31 08:52:01.095  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:01.095  1017  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:01.095  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:52:01.095  7443  7443 I art     : System.exit called, status: 0
08-31 08:52:01.095  7443  7443 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 08:52:01.105  3076  3076 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:52:01.105  3076  3076 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:52:01.105  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:01.105  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 08:52:01.115  1017  1029 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-31 08:52:01.115  1017  1029 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-31 08:52:01.115  1017  1029 W BroadcastQueue: android.os.TransactionTooLargeException
08-31 08:52:01.115  1017  1029 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 08:52:01.115  1017  1029 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 08:52:01.115  1017  1029 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-31 08:52:01.115  1017  1029 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-31 08:52:01.115  1017  1029 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-31 08:52:01.115  1017  1029 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-31 08:52:01.115  1017  1029 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-31 08:52:01.115  1017  1029 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-31 08:52:01.115  1017  1029 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 08:52:01.115  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-31 08:52:01.115  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:01.115  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:01.115  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:01.115  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:01.135  7582  7582 E Zygote  : MountEmulatedStorage(),
08-31 08:52:01.135  7582  7582 E Zygote  : v2
08-31 08:52:01.135  7582  7582 I libpersona: KNOX_SDCARD checking this for 1002
,08-31 08:52:01.135  7582  7582 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:01.135  7582  7582 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:01.135  1017  1029 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7582 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-31 08:52:01.135  7582  7582 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:01.135  7582  7582 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:52:01.155  7582  7582 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:01.155  7582  7582 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:01.165  7582  7582 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 08:52:01.165  7582  7582 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 08:52:01.185  7582  7582 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding GattService
,08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding HeadsetService
08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding HidService
08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding HealthService
,08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding PanService
08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding SapService
08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding A2dpSinkService,
08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding SapClientService
08-31 08:52:01.225  7582  7582 D BtSettings.ProfileConfig: Adding HidDevService
,08-31 08:52:01.225  7582  7582 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 08:52:01.225  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-31 08:52:01.225  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.225  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:01.225  1017  1030 D SettingsProvider: selectionArgs: false
08-31 08:52:01.225  1017  1030 D SettingsProvider: selectionArgs: 1002
08-31 08:52:01.225  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:52:01.225  1017  1030 D SettingsProvider: ret = -1
,08-31 08:52:01.225  1017  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-31 08:52:01.225  1017  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.225  1017  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 08:52:01.225  1017  1478 D SettingsProvider: selectionArgs: false
08-31 08:52:01.225  1017  1478 D SettingsProvider: selectionArgs: 1002
08-31 08:52:01.225  1017  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 08:52:01.225  1017  1478 D SettingsProvider: ret = -1
,08-31 08:52:01.235  1017  1440 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 08:52:01.235  1017  1440 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.235  1017  1440 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:01.235  1017  1440 D SettingsProvider: selectionArgs: false
08-31 08:52:01.235  1017  1440 D SettingsProvider: selectionArgs: 1002
08-31 08:52:01.235  1017  1440 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:52:01.235  1017  1440 D SettingsProvider: ret = -1
,08-31 08:52:01.235  1017  1561 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 08:52:01.235  1017  1561 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.235  1017  1561 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:01.235  1017  1561 D SettingsProvider: selectionArgs: false
08-31 08:52:01.235  1017  1561 D SettingsProvider: selectionArgs: 1002
08-31 08:52:01.235  1017  1561 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:52:01.235  1017  1561 D SettingsProvider: ret = -1
,08-31 08:52:01.235  1017  1100 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService,
08-31 08:52:01.235  1017  1100 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.235  1017  1100 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:01.235  1017  1100 D SettingsProvider: selectionArgs: false
08-31 08:52:01.235  1017  1100 D SettingsProvider: selectionArgs: 1002
08-31 08:52:01.235  1017  1100 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:52:01.235  1017  1100 D SettingsProvider: ret = -1
,08-31 08:52:01.235  1017  1366 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 08:52:01.235  1017  1366 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.235  1017  1366 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:01.235  1017  1366 D SettingsProvider: selectionArgs: false
08-31 08:52:01.235  1017  1366 D SettingsProvider: selectionArgs: 1002
08-31 08:52:01.235  1017  1366 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 08:52:01.235  1017  1366 D SettingsProvider: ret = -1,
08-31 08:52:01.235  1017  1567 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService,
08-31 08:52:01.235  1017  1567 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.235  1017  1567 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:01.235  1017  1567 D SettingsProvider: selectionArgs: false
08-31 08:52:01.235  1017  1567 D SettingsProvider: selectionArgs: 1002
08-31 08:52:01.235  1017  1567 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 08:52:01.235  1017  1567 D SettingsProvider: ret = -1
08-31 08:52:01.235  1017  4351 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-31 08:52:01.235  1017  4351 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.235  1017  4351 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:01.235  1017  4351 D SettingsProvider: selectionArgs: false
08-31 08:52:01.235  1017  4351 D SettingsProvider: selectionArgs: 1002
,08-31 08:52:01.235  1017  4351 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-31 08:52:01.235  1017  4351 D SettingsProvider: ret = -1
08-31 08:52:01.235  1017  1250 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:52:01.235  1017  1250 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.235  1017  1250 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 08:52:01.235  1017  1250 D SettingsProvider: selectionArgs: false
08-31 08:52:01.235  1017  1250 D SettingsProvider: selectionArgs: 1002
08-31 08:52:01.235  1017  1250 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:52:01.235  1017  1250 D SettingsProvider: ret = -1
,08-31 08:52:01.235  1017  1486 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:52:01.235  1017  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.235  1017  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:01.235  1017  1486 D SettingsProvider: selectionArgs: false
08-31 08:52:01.235  1017  1486 D SettingsProvider: selectionArgs: 1002
,08-31 08:52:01.235  1017  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:52:01.235  1017  1486 D SettingsProvider: ret = -1
08-31 08:52:01.235  1017  4350 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-31 08:52:01.235  1017  4350 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.235  1017  4350 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 08:52:01.235  1017  4350 D SettingsProvider: selectionArgs: false
08-31 08:52:01.235  1017  4350 D SettingsProvider: selectionArgs: 1002
08-31 08:52:01.235  1017  4350 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 08:52:01.235  1017  4350 D SettingsProvider: ret = -1
08-31 08:52:01.235  1017  1448 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
08-31 08:52:01.235  1017  1448 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:01.235  1017  1448 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:01.235  1017  1448 D SettingsProvider: selectionArgs: false
08-31 08:52:01.235  1017  1448 D SettingsProvider: selectionArgs: 1002
,08-31 08:52:01.235  1017  1448 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:52:01.235  1017  1448 D SettingsProvider: ret = -1
,08-31 08:52:01.245  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:01.245  1017  1440 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 08:52:01.245  1017  1440 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 08:52:01.245  1017  1440 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:01.245  1017  1440 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:01.255  1017  1440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:52:01.255  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 08:52:01.255  2003  7598 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 08:52:01.265  1017  1440 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:52:01.265  1017  1440 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:01.265  1017  1440 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:01.265  1017  1440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:52:01.275  2003  7598 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-31 08:52:01.665  1017  1314 E Watchdog: !@Sync 4
,08-31 08:52:02.635   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 08:52:02.745  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:52:02.745  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:03.615   291   291 E SMD     : DCD OFF,
,08-31 08:52:03.625   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:52:04.625   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:52:05.625   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 08:52:05.695  1017  3387 D SSRM:n  : SIOP:: AP = 320,
,08-31 08:52:05.745  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-31 08:52:05.745  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33602411 added. We now have 6 listener(s),
,08-31 08:52:05.745  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:05.745  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:05.745  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2112b976 added. We now have 7 listener(s)
,08-31 08:52:05.745  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:05.745  6721  6775 I System.out: IsBluetoothEnabled
08-31 08:52:05.745  6721  6775 D BluetoothAdapter: disable()
08-31 08:52:05.745  1017  1569 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
08-31 08:52:05.755  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:05.755  6721  6775 D BluetoothAdapter: enable()
08-31 08:52:05.755  1017  1478 W ActivityManager: Permission Denial: getCurrentUser() from pid=6721, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-31 08:52:05.755  1017  1478 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 08:52:05.755  1017  1478 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6721, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:52:05.755  1017  1478 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 08:52:05.755  1017  1478 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-31 08:52:05.755  1017  1478 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 08:52:05.755  1017  1478 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-31 08:52:05.755  1017  1478 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 08:52:05.755  1017  1478 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 08:52:05.755  1017  1478 D SettingsProvider: name = bluetooth_on
08-31 08:52:05.755  1017  1478 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 08:52:05.765  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-31 08:52:05.765  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 08:52:05.765  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-31 08:52:05.765  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2,
,08-31 08:52:05.795  7582  7582 D BluetoothAdapterState: make
,08-31 08:52:05.795  7582  7582 I bluedroid: init
,08-31 08:52:05.805  7582  7604 I BluetoothAdapterState: Entering OffState
,08-31 08:52:05.805  7582  7582 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 08:52:05.805  7582  7582 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 08:52:05.805  7582  7582 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 08:52:05.805  7582  7582 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 08:52:05.805  7582  7582 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-31 08:52:05.805  7582  7582 I bluedroid: get_profile_interface socket
08-31 08:52:05.805  7582  7582 I bluedroid: get_profile_interface map_client
08-31 08:52:05.805  7582  7607 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-31 08:52:05.805  7582  7607 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-31 08:52:05.805  7582  7607 E BluetoothServiceJni: populateRssiValuesNative
08-31 08:52:05.805  7582  7607 I bluedroid: getModelRssiValues
08-31 08:52:05.805  7582  7607 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 08:52:05.805  7582  7607 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 08:52:05.805  7582  7582 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-31 08:52:05.815  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 08:52:05.815  7582  7607 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-31 08:52:05.815  7582  7582 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:52:05.815  1017  4347 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 08:52:05.825  1017  4347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:52:05.825  1017  4347 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:05.825  1017  4347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:05.825  1017  4347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:05.825  7582  7593 I bluedroid: config_hci_snoop_log
,08-31 08:52:05.825  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 08:52:05.825  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-31 08:52:05.835  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-31 08:52:05.835  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-31 08:52:05.835  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 08:52:05.835  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 08:52:05.835  7582  7582 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-31 08:52:05.835  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 08:52:05.855  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 08:52:05.855  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 08:52:05.855  7582  7604 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-31 08:52:05.855  7582  7604 D BluetoothAdapterProperties: Setting state to 11
,08-31 08:52:05.855  7582  7604 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 08:52:05.855  7582  7604 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-31 08:52:05.855  7582  7604 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 08:52:05.855  7582  7604 D BluetoothAdapterService: Autoconnection is available 
,08-31 08:52:05.855  7582  7604 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 08:52:05.855  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:05.855  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-31 08:52:05.865  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 08:52:05.865  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:05.865  1175  1175 D BluetoothTile:  getBluetoothState : 11
,08-31 08:52:05.865  7582  7604 D BluetoothSecureManager: getInstant: null
08-31 08:52:05.865  7582  7604 D BluetoothSecureManager: calling getMethod for getService
08-31 08:52:05.865  7582  7604 D BluetoothSecureManager: calling getService
,08-31 08:52:05.865  7582  7604 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@f28a2b5
,08-31 08:52:05.865  1872  1872 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 08:52:05.865  1017  1569 D BluetoothSecureManagerService: isSecureModeEnabled
08-31 08:52:05.865  1017  1569 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-31 08:52:05.865  7582  7604 D BtConfig.SecureMode: isSecureModeOn:false
08-31 08:52:05.865  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 08:52:05.865  1017  4350 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:52:05.865  7582  7604 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 08:52:05.865  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 08:52:05.865  3076  3076 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:05.865  7582  7604 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 08:52:05.865  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 08:52:05.865  1017  4351 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 08:52:05.875  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
08-31 08:52:05.875  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-31 08:52:05.875  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:52:05.875  7582  7604 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 08:52:05.875  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 08:52:05.875  7582  7604 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 08:52:05.875  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 08:52:05.875  7582  7604 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 08:52:05.875  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 08:52:05.875  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:05.875  7582  7604 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 08:52:05.875  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 08:52:05.875  7582  7604 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 08:52:05.875  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 08:52:05.875  7582  7604 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-31 08:52:05.875  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:52:05.875  7582  7604 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 08:52:05.875  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:52:05.875  7582  7604 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:52:05.875  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 08:52:05.875  7582  7604 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 08:52:05.875  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 08:52:05.875  7582  7604 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-31 08:52:05.875  7582  7604 D BluetoothBondStateMachine: make
,08-31 08:52:05.875  1017  1100 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 08:52:05.875  1017  1100 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 08:52:05.875  1017  1100 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:05.875  1017  1100 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:05.885  1017  1100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:52:05.885  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 08:52:05.885  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 08:52:05.885  7582  7604 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-31 08:52:05.885  7582  7609 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 08:52:05.885  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:05.885  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-31 08:52:05.885  3076  3076 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:52:05.885  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 08:52:05.895  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:05.895  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:05.895  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:05.895  7582  7582 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 08:52:05.895  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 08:52:05.895  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 08:52:05.895  7582  7604 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 08:52:05.895  7582  7582 D BtGatt.GattService: Received start request. Starting profile...
08-31 08:52:05.895  7582  7582 D BtGatt.GattService: start()
08-31 08:52:05.895  7582  7582 D BtGatt.GattService: start()
08-31 08:52:05.895  7582  7582 I bluedroid: get_profile_interface gatt
,08-31 08:52:05.895  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54880a7
08-31 08:52:05.895  7582  7582 D BtGatt.AdvertiseManager: advertise manager created
,08-31 08:52:05.905  1017  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:05.905  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 08:52:05.905  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:05.905  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:05.905  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:05.905  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 08:52:05.905  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 08:52:05.905  7582  7604 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 08:52:05.905  1017  4351 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:05.905  1017  4351 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:52:05.915  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:05.915  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-31 08:52:05.915  1017  4351 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:05.915  1017  4351 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:05.915  1017  4351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 08:52:05.915  7582  7582 D BtGatt.GattService: mStartError = false
08-31 08:52:05.915  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54880a7
,08-31 08:52:05.915  7582  7582 D HeadsetService: Received start request. Starting profile...
,08-31 08:52:05.915  7582  7582 D HeadsetService: start()
,08-31 08:52:05.915  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-31 08:52:05.915  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 08:52:05.915  7582  7604 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 08:52:05.915  7582  7582 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 08:52:05.915  7582  7582 D HeadsetStateMachine: make
,08-31 08:52:05.925  7582  7582 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 08:52:05.935  1017  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:05.935  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 08:52:05.935  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:05.935  1017  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:05.935  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:05.935  1017  1478 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-31 08:52:05.935  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 08:52:05.935  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:05.935  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:05.935  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 08:52:05.935  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-31 08:52:05.935  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 08:52:05.945  7582  7604 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 08:52:05.945  1017  4351 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:05.945  1017  4351 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 08:52:05.945  1017  4351 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:05.945  1017  4351 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:05.945  1017  4351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:05.945  1017  1029 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-31 08:52:05.945  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 08:52:05.945  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:05.945  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:05.945  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 08:52:05.945  7582  7582 I bluedroid: get_profile_interface handsfree
,08-31 08:52:05.955  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 08:52:05.955  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 08:52:05.955  7582  7604 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 08:52:05.955  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:05.955  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:52:05.955  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:05.955  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:05.955  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:05.955  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 08:52:05.955  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 08:52:05.955  7582  7604 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-31 08:52:05.955  1017  1448 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:05.955  1017  1448 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 08:52:05.965  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:05.965  1017  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:05.965  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:05.965  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-31 08:52:05.965  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 08:52:05.965  7582  7604 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 08:52:05.965  7582  7582 I DualScoManager: Instantiating Dual Sco Manager
08-31 08:52:05.965  7582  7582 I DualScoManager: Set HeadsetServiceHelper
08-31 08:52:05.965  1017  1100 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 08:52:05.965  1017  1100 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 08:52:05.975  1017  1100 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:05.975  1017  1100 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:05.975  1017  1100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:05.975  7582  7582 D BluetoothAtMessage: createCMTIContentObservers
,08-31 08:52:05.975  1017  4347 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-31 08:52:05.975  1017  4347 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:05.975  1017  4347 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:05.975  1017  4347 D SettingsProvider: selectionArgs: false
08-31 08:52:05.975  1017  4347 D SettingsProvider: selectionArgs: 1002
08-31 08:52:05.975  1017  4347 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:52:05.975  1017  4347 D SettingsProvider: ret = -1
,08-31 08:52:05.975  7582  7613 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 08:52:05.975  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:52:05.975  7582  7582 D HeadsetService: mStartError = false
08-31 08:52:05.975  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54880a7
08-31 08:52:05.975  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:52:05.975  7582  7604 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 08:52:05.975  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-31 08:52:05.975  7582  7613 D HeadsetStateMachine: Clear mHeadsetBrsf
08-31 08:52:05.975  7582  7613 D HeadsetStateMachine: map size, before remove : 0
08-31 08:52:05.975  7582  7613 D HeadsetStateMachine: map size, after remove: 0
,08-31 08:52:05.975  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:52:05.975  7582  7604 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 08:52:05.975  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,08-31 08:52:05.975  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 08:52:05.975  7582  7604 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 08:52:05.975  7582  7604 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-31 08:52:05.975  7582  7604 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 08:52:05.975  7582  7604 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 08:52:05.975  7582  7582 E BluetoothAdapterService(88637607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-31 08:52:05.985  7582  7604 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 08:52:05.985  7582  7582 D A2dpService: Received start request. Starting profile...
,08-31 08:52:05.985  7582  7582 D A2dpService: start()
,08-31 08:52:05.985  7582  7582 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 08:52:05.985  7582  7582 I bluedroid: get_profile_interface avrcp
,08-31 08:52:05.995  7582  7582 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 08:52:05.995  7582  7582 D Avrcp   : Initialize Media Controller
,08-31 08:52:05.995  7582  7582 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-31 08:52:05.995  7582  7582 E Avrcp   : getActiveSessions
08-31 08:52:05.995  7582  7582 D Avrcp   : pick active media Controller
08-31 08:52:05.995  7582  7582 D Avrcp   : Get the active Media Controller 
,08-31 08:52:06.005  1017  3402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 08:52:06.005  7582  7582 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 08:52:06.015  7582  7617 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 08:52:06.015  7582  7582 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 08:52:06.015  7582  7582 D A2dpStateMachine: make
,08-31 08:52:06.015  1017  2045 V SAMP_SPCM_test: CSC File load.. 
,08-31 08:52:06.015  7582  7582 I bluedroid: get_profile_interface a2dp
08-31 08:52:06.015  7582  7619 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 08:52:06.015  7582  7582 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 08:52:06.015  7582  7582 D A2dpService: mStartError = false
08-31 08:52:06.015  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54880a7
,08-31 08:52:06.015  7582  7618 D A2dpStateMachine: Enter Disconnected: -2
08-31 08:52:06.015  7582  7582 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 08:52:06.025  7582  7582 D HidService: Received start request. Starting profile...
08-31 08:52:06.025  7582  7582 D HidService: start()
08-31 08:52:06.025  7582  7582 I bluedroid: get_profile_interface hidhost
08-31 08:52:06.025  7582  7582 D HidService: setHidService(): set to: null
08-31 08:52:06.025  7582  7582 D HidService: mStartError = false
08-31 08:52:06.025  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54880a7
,08-31 08:52:06.025  7582  7582 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 08:52:06.025  1429  3300 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 08:52:06.025  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-31 08:52:06.025  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 08:52:06.025  1429  3300 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 08:52:06.025  7582  7582 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 08:52:06.035  7582  7582 D HealthService: Received start request. Starting profile...
08-31 08:52:06.035  7582  7582 D HealthService: start()
,08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-31 08:52:06.035  7582  7582 I bluedroid: get_profile_interface health
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-31 08:52:06.035  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
08-31 08:52:06.035  7582  7582 D HealthService: mStartError = false
08-31 08:52:06.035  7582  7582 D BluetoothAdapterService: getAdapterService() - re,turning com.android.bluetooth.btservice.AdapterService@54880a7
08-31 08:52:06.035  7582  7582 D HeadsetStateMachine: Proxy object connected
08-31 08:52:06.035  7582  7582 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 08:52:06.035  7582  7582 D PanService: Received start request. Starting profile...
08-31 08:52:06.035  7582  7582 D PanService: start()
08-31 08:52:06.035  7582  7582 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 08:52:06.035  7582  7582 I bluedroid: get_profile_interface pan
,08-31 08:52:06.035  7582  7582 D PanService: mStartError = false
,08-31 08:52:06.035  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54880a7
08-31 08:52:06.035  7582  7582 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 08:52:06.035  7582  7582 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 08:52:06.035  7582  7613 D HeadsetStateMachine: Disconnected process message: 11
,08-31 08:52:06.035  7582  7582 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-31 08:52:06.045  7582  7613 D HeadsetStateMachine: Disconnected process message: 18
,08-31 08:52:06.045  7582  7582 D BluetoothMapService: Received start request. Starting profile...
08-31 08:52:06.045  7582  7582 D BluetoothMapService: start()
,08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-31 08:52:06.065  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-31 08:52:06.075  1017  2045 ,W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-31 08:52:06.075  1017  2045 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-31 08:52:06.075  7582  7582 D BluetoothMapService: mStartError = false
08-31 08:52:06.075  1017  2045 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-31 08:52:06.075  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54880a7
08-31 08:52:06.075  1017  2045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:06.075  1017  2045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:06.075  1017  2045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:06.075  7582  7582 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
08-31 08:52:06.075  1017  2045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:06.085  7582  7582 E BluetoothAdapterService(88637607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 08:52:06.085  7582  7582 D SapService: Received start request. Starting profile...
08-31 08:52:06.085  7582  7582 D SapService: start()
08-31 08:52:06.085  7582  7582 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 08:52:06.085  7582  7582 I bluedroid: get_profile_interface sap
08-31 08:52:06.085  7582  7582 D SapService: mStartError = false
08-31 08:52:06.085  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54880a7
08-31 08:52:06.085  7582  7582 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 08:52:06.085  7582  7582 D BluetoothA2dp: Proxy object connected
08-31 08:52:06.085  7582  7582 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-31 08:52:06.085  7582  7582 E BluetoothAdapterService(88637607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 08:52:06.085  7582  7582 E BluetoothAdapterService(88637607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 08:52:06.085  7582  7582 E BluetoothAdapterService(88637607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 08:52:06.085  7582  7582 E BluetoothAdapterService(88637607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-31 08:52:06.085  7582  7613 D HeadsetStateMachine: Disconnected process message: 10
08-31 08:52:06.085  7582  7613 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 08:52:06.085  7582  7613 D HeadsetStateMachine: Disconnected process message: 11
08-31 08:52:06.095  7623  7623 E Zygote  : MountEmulatedStorage()
08-31 08:52:06.095  7623  7623 I libpersona: KNOX_SDCARD checking this for 1000
08-31 08:52:06.095  7623  7623 E Zygote  : v2
08-31 08:52:06.095  7623  7623 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:06.095  7623  7623 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:52:06.095  1017  2045 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7623 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 08:52:06.095  7623  7623 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:52:06.095  7582  7617 D BluetoothMediaBrowser: no now playing list
08-31 08:52:06.095  7582  7617 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-31 08:52:06.095  7623  7623 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:52:06.115  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:06.125  7582  7582 E BluetoothAdapterService(88637607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-31 08:52:06.125  7582  7582 E BluetoothAdapterService(88637607): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
08-31 08:52:06.125  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-31 08:52:06.125  7582  7604 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-31 08:52:06.125  7582  7604 I bluedroid: enable
08-31 08:52:06.125  7582  7604 I bt_hci_bdroid: init
08-31 08:52:06.135  7582  7604 I bt_vendor: bt-vendor : init
08-31 08:52:06.135  7582  7604 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 08:52:06.135  7582  7604 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 08:52:06.135  7582  7604 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-31 08:52:06.135  7582  7604 D bt_userial_mct: userial_init
08-31 08:52:06.135  7582  7604 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 08:52:06.135  7582  7604 I bt_vendor: Starting hciattach daemon
08-31 08:52:06.135  7582  7604 I bt_vendor: try to set false
08-31 08:52:06.135  7582  7604 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 08:52:06.135  7582  7635 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 08:52:06.135  7582  7604 I bt_vendor: Starting hciattach daemon
08-31 08:52:06.135  7582  7604 I bt_vendor: try to set true
08-31 08:52:06.135  7623  7623 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 08:52:06.135  7623  7623 D ActivityThread: Added TimaKeyStore provider
08-31 08:52:06.155  7642  7642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 08:52:06.175  7623  7623 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,08-31 08:52:06.205  7648  7648 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-31 08:52:06.205  7649  7649 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 08:52:06.225  7651  7651 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 08:52:06.235  1017  2045 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-31 08:52:06.235  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 08:52:06.245  7653  7653 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 08:52:06.255  7654  7654 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-31 08:52:06.285  1017  1478 I ActivityManager: Killing 7146:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-31 08:52:06.485  7657  7657 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-31 08:52:06.495  7658  7658 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 08:52:06.545  7582  7604 I bt_vendor: bluetooth satus is on
08-31 08:52:06.545  7582  7639 D bt_userial_mct: userial_open(port:0)
08-31 08:52:06.545  7582  7639 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 08:52:06.545  7582  7639 I bt_vendor: Done intiailizing UART
,08-31 08:52:06.545  7582  7639 I bt_vendor: Done intiailizing UART
08-31 08:52:06.545  7582  7639 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 08:52:06.545  7582  7639 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 08:52:06.545  7582  7660 D bt_userial_mct: Entering userial_read_thread()
,08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_L2CAP,
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_AVRC,
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_BTM,
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_SAP,
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 08:52:06.545  7582  7635 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 08:52:06.615   291   291 E SMD     : DCD OFF,
,08-31 08:52:06.625   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 08:52:06.645  7582  7635 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-31 08:52:06.645  7582  7635 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41b5ed1 
,08-31 08:52:06.645  7582  7635 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41b5ed1 
,08-31 08:52:06.675  7582  7607 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-31 08:52:06.675  7582  7607 E bt-btif : Calling BTA_HhEnable
,08-31 08:52:06.675  7582  7607 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 08:52:06.675  7582  7607 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-31 08:52:06.675  7582  7607 E BluetoothServiceJni: populateRssiValuesNative
,08-31 08:52:06.675  7582  7607 I bluedroid: getModelRssiValues
08-31 08:52:06.675  7582  7607 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-31 08:52:06.675  7582  7607 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 08:52:06.675  7582  7607 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-31 08:52:06.675  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 08:52:06.675  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:06.685  7582  7607 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 08:52:06.685  7582  7607 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:52:06.685  7582  7607 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 08:52:06.685  7582  7607 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-31 08:52:06.685  7582  7607 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-31 08:52:06.685  7582  7607 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-31 08:52:06.685  7582  7607 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 08:52:06.685  7582  7607 E bt-btif : btif_sock_init: !vhci_init
,08-31 08:52:06.685  7582  7607 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 08:52:06.685  7582  7607 D IOP_DB_BT: db_open: db_open : handle 3028307984l, read 13894 bytes onto local cache
08-31 08:52:06.685  7582  7607 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-31 08:52:06.685  7582  7607 D IOP_DB_BT: db_query: result 1
08-31 08:52:06.685  7582  7660 E bt_mct  : hci lib postload completed
,08-31 08:52:06.685  7582  7607 I         : iop_db_open: iop_db_open status 0
08-31 08:52:06.685  7582  7607 D bte_conf: Device ID record 1 : primary
08-31 08:52:06.685  7582  7607 D bte_conf:   vendorId            = 0075
08-31 08:52:06.685  7582  7607 D bte_conf:   vendorIdSource      = 0001
08-31 08:52:06.685  7582  7607 D bte_conf:   product             = 0100
08-31 08:52:06.685  7582  7607 D bte_conf:   version             = 0200
08-31 08:52:06.685  7582  7607 D bte_conf:   clientExecutableURL = 
08-31 08:52:06.685  7582  7607 D bte_conf:   serviceDescription  = 
08-31 08:52:06.685  7582  7607 D bte_conf:   documentationURL    = 
08-31 08:52:06.685  7582  7607 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 08:52:06.685  7582  7607 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 08:52:06.695  7582  7604 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-31 08:52:06.695  7582  7604 D BluetoothAdapterProperties: ScanMode =  20
,08-31 08:52:06.695  7582  7604 D BluetoothAdapterProperties: State =  11
,08-31 08:52:06.695  1017  1567 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 08:52:06.695  7582  7604 D BluetoothAdapterProperties: Setting state to 12
08-31 08:52:06.695  7582  7604 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 08:52:06.695  7582  7607 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 08:52:06.695  7582  7607 D BluetoothAdapterProperties: Scan Mode:21
,08-31 08:52:06.695  7582  7607 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 08:52:06.705  1017  1030 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-31 08:52:06.705  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:06.705  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:06.705  1017  1030 D SettingsProvider: selectionArgs: false
08-31 08:52:06.705  1017  1030 D SettingsProvider: selectionArgs: 1002
08-31 08:52:06.705  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:52:06.705  1017  1030 D SettingsProvider: ret = -1
,08-31 08:52:06.705  7582  7604 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 08:52:06.705  7582  7604 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 08:52:06.705  1017  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:06.705  1017  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 08:52:06.705  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:06.705  1017  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:06.705  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:06.725  1175  1799 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:52:06.725  1175  1799 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:52:06.725  7582  7604 D BluetoothAdapterService: Autoconnection is available 
08-31 08:52:06.725  7582  7604 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 08:52:06.725  7582  7604 D BluetoothAdapterService: starting service from this receiver
,08-31 08:52:06.725  1017  3167 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:06.725  1017  3167 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 08:52:06.725  1017  3167 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:06.725  1017  3167 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:06.725  1017  3167 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:06.735  7582  7604 I BluetoothAdapterState: Entering On State from state = 11
08-31 08:52:06.735  2003  2011 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:52:06.735  2003  2011 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:52:06.735  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:52:06.735  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:52:06.735  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 08:52:06.735  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:52:06.735  1017  1017 D BluetoothA2dp: Proxy object connected
,08-31 08:52:06.735  1442  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:52:06.735  1442  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:52:06.735  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:06.735  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:06.735  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:06.735  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:06.735  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:06.735  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:06.735  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:06.735  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:06.735  3076  3087 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:52:06.735  3076  3087 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:52:06.745  1017  1046 D BluetoothPan: Binding service...
,08-31 08:52:06.745  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 08:52:06.745  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:52:06.745  1429  1450 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:52:06.745  1429  1450 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:52:06.745  7582  7582 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-31 08:52:06.745  7582  7590 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:52:06.745  7582  7590 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:52:06.745  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:06.745  3076  3084 D BluetoothPan: Binding service...
,08-31 08:52:06.755  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-31 08:52:06.755  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 08:52:06.755  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:06.755  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:06.755  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:06.755  3076  7552 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 08:52:06.755  7582  7582 I BluetoothPbapService: Handler(): got msg=1
,08-31 08:52:06.765  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-31 08:52:06.765  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 08:52:06.765  1017  1250 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 08:52:06.765  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:06.765  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:06.765  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:06.765  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:52:06.765  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:52:06.765  3076  3087 D Bluetoothsap: onBluetoothStateChange: up=true
08-31 08:52:06.765  3076  3087 D Bluetoothsap: Binding service...
,08-31 08:52:06.765  3076  3076 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 08:52:06.765  3076  3076 D PanProfile: Bluetooth service connected
,08-31 08:52:06.765  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 08:52:06.765  3076  3087 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-31 08:52:06.765  7582  7665 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 08:52:06.785  7582  7665 D BluetoothSocket: bindListen(): myUserId = 0
08-31 08:52:06.785  7582  7665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:52:06.785  7582  7665 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-31 08:52:06.785  7582  7665 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:52:06.785  7582  7665 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:52:06.785  7582  7665 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c774049
,08-31 08:52:06.785  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:06.785  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:06.785  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:06.785  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:06.785  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:06.785  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:06.785  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:06.785  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:06.785  7582  7665 D BluetoothSocket: channel: 19
,08-31 08:52:06.785  7582  7665 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 08:52:06.785  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:06.785  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:06.785  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30bf1b77 added. We now have 8 listener(s)
08-31 08:52:06.785  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:06.795  3076  3076 D BluetoothMap: Proxy object connected
08-31 08:52:06.795  3076  3076 D MapProfile: Bluetooth service connected
08-31 08:52:06.795  3076  3076 D BluetoothMap: getConnectedDevices()
,08-31 08:52:06.795  1017  1567 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 08:52:06.795  1017  1567 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 08:52:06.795  1017  1567 D SecContentProvider2: mCursor = null
,08-31 08:52:06.795  1017  1567 D WifiService: setWifiEnabled: false pid=6721, uid=10171
,08-31 08:52:06.795  1017  1567 D SettingsProvider: name = wifi_on
,08-31 08:52:06.805  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:06.805  1017  1448 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 08:52:06.805  1017  1448 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 08:52:06.805  1017  1448 D SecContentProvider2: mCursor = null
,08-31 08:52:06.805  1017  1448 D WifiService: setWifiEnabled: true pid=6721, uid=10171
,08-31 08:52:06.805  1017  1448 W ActivityManager: Permission Denial: getCurrentUser() from pid=6721, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-31 08:52:06.805  1017  1448 W WifiService: Failed getting userId using ActivityManagerNative
08-31 08:52:06.805  1017  1448 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6721, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 08:52:06.805  1017  1448 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 08:52:06.805  1017  1448 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 08:52:06.805  1017  1448 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 08:52:06.805  1017  1448 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 08:52:06.805  1017  1448 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 08:52:06.805  1017  1448 D SettingsProvider: name = wifi_on
,08-31 08:52:06.815  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 08:52:06.945  1017  1046 I art     : Explicit concurrent mark sweep GC freed 28595(1636KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.550ms total 176.190ms
08-31 08:52:06.945  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-31 08:52:06.945  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 08:52:06.945  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:06.945  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:06.945  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:06.945  3076  3087 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 08:52:06.955  1458  1472 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 08:52:06.955  1458  1472 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:52:06.955  3076  7552 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 08:52:06.955  3076  3076 D Bluetoothsap: BluetoothSAP Proxy object connected
08-31 08:52:06.955  3076  3076 D SapProfile: Bluetooth service connected
08-31 08:52:06.955  3076  3076 D Bluetoothsap: getConnectedDevices()
,08-31 08:52:06.955  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-31 08:52:06.955  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 08:52:06.955  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:06.955  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:06.955  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:06.955  3076  3076 D BluetoothPbap: Proxy object connected
08-31 08:52:06.955  1429  1441 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:52:06.955  3076  3076 D PbapServerProfile: Bluetooth service connected
08-31 08:52:06.955  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 08:52:06.955  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:52:06.955  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:06.955  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:06.955  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:06.965  1429  1441 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:52:06.965  1458  1829 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:52:06.965  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:52:06.965  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:52:06.965  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:06.965  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:06.965  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-31 08:52:06.965  1458  1829 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:52:06.965  7493  7502 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:52:06.965  7493  7502 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 08:52:06.965  7582  7608 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:52:06.965  3076  3084 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:52:06.965  3076  3084 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:52:06.965  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 08:52:06.965  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 08:52:06.965  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:06.965  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:06.965  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:06.965  3076  3076 D BluetoothA2dp: Proxy object connected
,08-31 08:52:06.965  3076  3087 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 08:52:06.975  3076  3076 D A2dpProfile: Bluetooth service connected
,08-31 08:52:06.975  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:52:06.975  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:52:06.975  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:06.975  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:06.975  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-31 08:52:06.975  3076  3087 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:52:06.975  3076  3084 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 08:52:06.975  3076  3076 D HeadsetProfile: Bluetooth service connected
08-31 08:52:06.975  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-31 08:52:06.975  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 08:52:06.975  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:06.975  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:06.975  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:06.975  6721  6766 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 08:52:06.975  6721  6766 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 08:52:06.975  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:52:06.975  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:52:06.975  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 08:52:06.975  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:52:06.975  1429  1450 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:52:06.975  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:52:06.975  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:52:06.975  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:06.985  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:06.985  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-31 08:52:06.985  1429  1450 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:52:06.985  1429  3300 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 08:52:06.985  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 08:52:06.985  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 08:52:06.985  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:06.985  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:06.985  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-31 08:52:06.985  3076  3076 D BluetoothInputDevice: Proxy object connected
08-31 08:52:06.985  3076  3076 D HidProfile: Bluetooth service connected
,08-31 08:52:06.985  1429  3300 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 08:52:06.985  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 08:52:06.985  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 08:52:06.985  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:06.985  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
,08-31 08:52:06.995  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 08:52:06.995  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3ea6634c, true
,08-31 08:52:07.005  1429  1429 D BluetoothHeadset: registerMessageListener
,08-31 08:52:07.005  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-31 08:52:07.005  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 08:52:07.005  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:52:07.005  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
,08-31 08:52:07.015  1175  1175 D BluetoothTile:  getBluetoothState : 12
,08-31 08:52:07.015  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:52:07.015  3076  3076 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:07.015  1872  1872 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 08:52:07.015  1175  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 08:52:07.025  1017  4351 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 08:52:07.025  1017  4351 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-31 08:52:07.025  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:07.025  7582  7663 D HeadsetService: registerMessageListener
,08-31 08:52:07.025  7582  7663 D HeadsetService: registerMessageListener
08-31 08:52:07.025  1017  1561 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 08:52:07.025  7582  7613 D HeadsetStateMachine: Disconnected process message: 70
08-31 08:52:07.025  7582  7613 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@35d2cd4e
,08-31 08:52:07.025  7582  7675 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-31 08:52:07.025  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 08:52:07.025  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 08:52:07.025  1017  3167 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 08:52:07.025  1017  4351 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:07.025  1017  4351 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:07.025  1017  4351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:52:07.025  3076  3076 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-31 08:52:07.025  3076  3076 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-31 08:52:07.025  3076  3076 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 08:52:07.025  3076  3076 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 08:52:07.025  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 08:52:07.025  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-31 08:52:07.025  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 08:52:07.035  7582  7675 D BluetoothSocket: bindListen(): myUserId = 0
08-31 08:52:07.035  7582  7675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:07.035  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 08:52:07.035  7582  7675 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-31 08:52:07.035  7582  7675 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:52:07.035  7582  7675 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:52:07.035  7582  7675 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3da35e6f
08-31 08:52:07.035  7582  7675 D BluetoothSocket: channel: 5
,08-31 08:52:07.035  7582  7613 D HeadsetStateMachine: Disconnected process message: 9
,08-31 08:52:07.035  7582  7613 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 08:52:07.035   286  1599 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-31 08:52:07.035   286  1599 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 08:52:07.035   286  1599 V voice   : voice_set_parameters: exit with code(-2)
08-31 08:52:07.035   286  1599 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 08:52:07.035   286  1599 V msm8974_platform: platform_set_parameters: exit with code(-2)
,08-31 08:52:07.035   286  1599 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 08:52:07.035   286  1599 V audio_hw_primary: adev_set_parameters: exit
08-31 08:52:07.035  7582  7613 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-31 08:52:07.045  3076  3076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:52:07.045  1017  1440 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 08:52:07.045  1017  1440 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 08:52:07.045  1017  1440 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:07.045  1017  1440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:07.045  1017  1440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 08:52:07.055  3076  3076 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:52:07.055  3076  3076 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 08:52:07.065  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:07.065  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 08:52:07.065  7582  7582 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54880a7
,08-31 08:52:07.065  7582  7582 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 08:52:07.075  1017  1567 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 08:52:07.075  1017  1567 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 08:52:07.075  1017  1567 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:07.075  1017  1567 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:07.075  1017  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 08:52:07.085  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:07.085  1017  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 08:52:07.085  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 08:52:07.085  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:07.085  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:07.085  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:52:07.095  2003  7682 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 08:52:07.095  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 08:52:07.095  1017  1569 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 08:52:07.105  1017  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:52:07.105  1017  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:07.105  1017  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:07.105  1017  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:52:07.115  1017  4347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 08:52:07.125  1017  4347 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:07.125  1017  4347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:07.125  1017  4347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 08:52:07.125  7582  7686 D BluetoothSocket: bindListen(): myUserId = 0
08-31 08:52:07.125  7582  7686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:52:07.125  7582  7686 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-31 08:52:07.125  7582  7686 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 08:52:07.125  7582  7686 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 08:52:07.125  7582  7686 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22b1728b
,08-31 08:52:07.125  7582  7686 D BluetoothSocket: channel: 12
08-31 08:52:07.125  7582  7686 I BtOppRfcommListener: Accept thread started.
,08-31 08:52:07.135  2003  7682 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-31 08:52:07.145  1017  1044 D Tethering: interfaceAdded wlan0
,08-31 08:52:07.155  1017  1130 E Tethering: No numeric data
,08-31 08:52:07.155  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 08:52:07.155  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-31 08:52:07.155  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:07.155  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 08:52:07.155  1017  1130 D Tethering: clearTetheredNotification()
,08-31 08:52:07.155  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 08:52:07.155  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:52:07.155  1175  1175 D HotspotTile: updateTetherState():false, false
,08-31 08:52:07.165  1017  1123 V NetworkStats: performPollLocked() took 7ms
,08-31 08:52:07.165  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:07.165  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:07.165  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:07.165  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:52:07.165  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:52:07.165  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:52:07.165  1017  1130 D Tethering: InitialState.processMessage what=4
,08-31 08:52:07.165  1017  1130 E Tethering: No numeric data
,08-31 08:52:07.165  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 08:52:07.165  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:52:07.165  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:07.175  1017  1130 D Tethering: clearTetheredNotification()
,08-31 08:52:07.175  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 08:52:07.175  1175  1175 D HotspotTile: updateTetherState():false, false
,08-31 08:52:07.175  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 08:52:07.175  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:52:07.175  1017  1044 D Tethering: interfaceAdded p2p0
,08-31 08:52:07.175  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 08:52:07.175  1017  1123 V NetworkStats: performPollLocked() took 6ms
,08-31 08:52:07.175  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:07.175  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 08:52:07.175  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:52:07.175  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:52:07.175  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:07.185   278   977 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 08:52:07.185  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:07.185   278   977 D SoftapController: Softap fwReload - Ok
,08-31 08:52:07.185   278   977 D CommandListener: Setting iface cfg
08-31 08:52:07.185   278   977 D CommandListener: Trying to bring down wlan0
,08-31 08:52:07.185   278   977 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:52:07.185  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant,
,08-31 08:52:07.185  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 08:52:07.185  1017  1126 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-31 08:52:07.195  3076  3076 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:52:07.195  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:07.195  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:52:07.195  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 08:52:07.205  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:07.205  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:07.205  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:07.205  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:07.205  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:52:07.205  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-31 08:52:07.205  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:52:07.205  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 08:52:07.205  1175  1175 D HotspotTile: onReceive : 2, 0
,08-31 08:52:07.205  1017  1100 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:52:07.205  1017  1100 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:52:07.205  1017  1100 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:07.205  1017  1100 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:07.205  1017  1100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:52:07.205  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 08:52:07.205  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 08:52:07.205  6523  6523 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:52:07.215  6523  6523 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:52:07.215  1606  1606 I Hs20UtilService: Starting #19
,08-31 08:52:07.215  1606  1643 I Hs20UtilService: Message received 5011
,08-31 08:52:07.235  7689  7689 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 08:52:07.235  7689  7689 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 08:52:07.235  7689  7689 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 08:52:07.245  7689  7689 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-31 08:52:07.255   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7689
08-31 08:52:07.255   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 08:52:07.255  7689  7689 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 08:52:07.255  7689  7689 I wpa_supplicant: ssSupport state is = 1
08-31 08:52:07.255  7689  7689 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 08:52:07.255  7689  7689 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-31 08:52:07.255   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7689
08-31 08:52:07.255   372   372 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-31 08:52:07.415   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-31 08:52:07.415  7689  7689 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-31 08:52:07.455  7689  7689 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 08:52:07.455  7689  7689 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 08:52:07.465  7689  7689 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 08:52:07.465   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7689
08-31 08:52:07.465   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 08:52:07.465  7689  7689 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-31 08:52:07.465  7689  7689 I wpa_supplicant: ssSupport state is = 1,
08-31 08:52:07.465  7689  7689 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:52:07.475  7689  7689 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:52:07.475  7689  7689 E wpa_supplicant: SIM READ ERROR
08-31 08:52:07.475  7689  7689 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:52:07.475  7689  7689 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 08:52:07.475  7689  7689 E wpa_supplicant: SIM READ ERROR
08-31 08:52:07.475  7689  7689 I wpa_supplicant: Blacklist: Clear (all) 
08-31 08:52:07.475  7689  7689 I wpa_supplicant: wpa_default_ap_write_once
08-31 08:52:07.475  7689  7689 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 08:52:07.475  7689  7689 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:52:07.475  7689  7689 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-31 08:52:07.475  7689  7689 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:52:07.475  7689  7689 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 08:52:07.475  7689  7689 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-31 08:52:07.475  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:52:07.475  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:52:07.475  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:52:07.575  7689  7689 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-31 08:52:07.625   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-31 08:52:07.765  7689  7689 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-31 08:52:07.765  7689  7689 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 08:52:07.775  7689  7689 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 08:52:07.775   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7689
08-31 08:52:07.775   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-31 08:52:07.775  7689  7689 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-31 08:52:07.775  7689  7689 I wpa_supplicant: ssSupport state is = 1
08-31 08:52:07.775  7689  7689 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 08:52:07.785  7689  7689 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 08:52:07.795  7689  7689 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 08:52:07.795   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7689
08-31 08:52:07.795   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 08:52:07.795  7689  7689 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-31 08:52:07.795  7689  7689 I wpa_supplicant: ssSupport state is = 1
08-31 08:52:07.795  7689  7689 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 08:52:07.795  7689  7689 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 08:52:07.795  7689  7689 E wpa_supplicant: SIM READ ERROR
08-31 08:52:07.795  7689  7689 I wpa_supplicant: wpa_default_ap_write_once,
08-31 08:52:07.795  7689  7689 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 08:52:07.795  7689  7689 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 08:52:07.795  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:52:07.795  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-31 08:52:07.795  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-31 08:52:07.805  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 08:52:07.805  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:52:07.805  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:52:07.915  7689  7689 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-31 08:52:07.915  7689  7689 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 08:52:08.035  7689  7689 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-31 08:52:08.035  7689  7689 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-31 08:52:08.035  7689  7689 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 08:52:08.165  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 08:52:08.165  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 08:52:08.165  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 08:52:08.195  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-31 08:52:08.195  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 08:52:08.195  7689  7689 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 08:52:08.195  7689  7689 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,08-31 08:52:08.195  7689  7689 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 08:52:08.195  7689  7689 E wpa_supplicant: SIM READ ERROR
,08-31 08:52:08.195  7689  7689 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 08:52:08.225  7689  7689 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-31 08:52:08.235  7689  7689 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 08:52:08.235  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-31 08:52:08.235  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-31 08:52:08.235  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:52:08.235  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:08.235  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:08.235  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:08.235  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:08.245  1175  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 08:52:08.245  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 08:52:08.245  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:52:08.245  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-31 08:52:08.245  1175  1175 D HotspotTile: onReceive : 3, 0
,08-31 08:52:08.255  3076  3076 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:52:08.255  1017  4350 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:52:08.255  1017  4350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:52:08.255  1017  1126 E WifiConfigStore: Not a HS20
,08-31 08:52:08.255  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:08.255  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:08.255  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:08.255  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:08.255  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:08.255  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:08.255  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:08.255  6721  6721 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:08.255  1017  4350 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:08.255  1017  4350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:08.255  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 08:52:08.255  1017  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 08:52:08.255  6721  6721 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:08.255  1606  1606 I Hs20UtilService: Starting #20
,08-31 08:52:08.255  1606  1643 I Hs20UtilService: Message received 5011
,08-31 08:52:08.265  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 08:52:08.265  6523  6523 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 08:52:08.265  6523  6523 D SecurityLogAgent: StateMachine : Current State = 1
08-31 08:52:08.265  6523  6523 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 08:52:08.265  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 08:52:08.265  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 08:52:08.265  7689  7689 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 08:52:08.265  7689  7689 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 08:52:08.265  7689  7689 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 08:52:08.265  7689  7689 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 08:52:08.265  7689  7689 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 08:52:08.265  7689  7689 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 08:52:08.265  7689  7689 I wpa_supplicant: First Scan Start
,08-31 08:52:08.265  7689  7689 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 08:52:08.275  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-31 08:52:08.275  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 08:52:08.275  1017  1126 I WifiNative-HAL: startHal
08-31 08:52:08.275  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9d45888c
08-31 08:52:08.275  1017  1126 I WifiNative-HAL: Could not start hal
,08-31 08:52:08.275  1017  1126 E WifiNative-wlan0: do suspend true
,08-31 08:52:08.275  7057  7057 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:08.275  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 08:52:08.275  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-31 08:52:08.275   278   977 D CommandListener: Setting iface cfg
08-31 08:52:08.275   278   977 D CommandListener: Trying to bring up p2p0
,08-31 08:52:08.275  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 08:52:08.275  1017  1125 D WifiP2pService: P2pEnablingState
08-31 08:52:08.275  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 08:52:08.275  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-31 08:52:08.275  1017  1125 D WifiP2pService: P2p socket connection successful
,08-31 08:52:08.285  1017  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:08.285  1017  1125 D WifiP2pService: P2pEnabledState
08-31 08:52:08.285  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 08:52:08.285  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 08:52:08.285  1017  1126 E WifiNative-wlan0: invaild command id : 215
,08-31 08:52:08.285  1017  1149 I WifiNative-HAL: startHal
08-31 08:52:08.285  1017  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e0f09bc
08-31 08:52:08.285  1017  1149 I WifiNative-HAL: Could not start hal
08-31 08:52:08.285  1017  1149 E WifiScanningService: could not start HAL
,08-31 08:52:08.285  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 08:52:08.285  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 08:52:08.285  1017  1126 E WifiNative-wlan0: invaild command id : 215
08-31 08:52:08.285  1017  1017 D RttService: SCAN_AVAILABLE : 3
,08-31 08:52:08.285  1017  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:08.285  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 08:52:08.285  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 08:52:08.285  7689  7689 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 08:52:08.285  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 08:52:08.285  7689  7689 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 08:52:08.285  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 08:52:08.285  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-31 08:52:08.285  1017  1047 D WifiDisplayController: disconnect
08-31 08:52:08.285  1017  1047 D WifiDisplayController: updateConnection
08-31 08:52:08.285  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 08:52:08.285  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 08:52:08.295  7689  7689 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-31 08:52:08.295  1017  1126 E WifiStateMachine: Failed to set frequency band 0
,08-31 08:52:08.295  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:52:08.295  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:52:08.295  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:08.295  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-31 08:52:08.295  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-31 08:52:08.295  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 08:52:08.295  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-31 08:52:08.295  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 08:52:08.295  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 08:52:08.295  1017  1250 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 08:52:08.295  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 08:52:08.305  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 08:52:08.305  3076  3076 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:52:08.305  1017  1125 D WifiP2pService: DeviceAddress: 0a:76:28
,08-31 08:52:08.305  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:52:08.305  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:52:08.305  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  secondary type: null
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  wps: 0
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  grpcapab: 0
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  devcapab: 0
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  status: 3
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  wfdInfo: null
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-31 08:52:08.305  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-31 08:52:08.305  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:52:08.305  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:52:08.305  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:52:08.305  3076  3076 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 08:52:08.315  3076  3799 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:52:08.315  7407  7407 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,08-31 08:52:08.315  7407  7407 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 08:52:08.315  7407  7407 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 08:52:08.315  7422  7422 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 08:52:08.325  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 08:52:08.325  1017  1125 D WifiP2pService: InactiveState
,08-31 08:52:08.325  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
08-31 08:52:08.325  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 08:52:08.325  7689  7689 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 08:52:08.325  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-31 08:52:08.325  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 08:52:08.835  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:08.835  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:08.835  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:08.835  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:08.835  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:08.835  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:08.835  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:08.835  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:08.835  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:08.835  6721  6775 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 08:52:08.835  6721  6775 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 08:52:08.835  6721  6775 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@127ce197 Bundle[{}]
,08-31 08:52:08.845  6721  6775 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 08:52:08.845  6721  6775 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-31 08:52:08.845  6721  6775 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 08:52:08.845  6721  6775 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 08:52:08.845  6721  6775 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-31 08:52:08.845  6721  6775 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 08:52:08.855  6721  6775 I System.out: Running OutgoingSocketThread
,08-31 08:52:08.855  6721  7698 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1325)
,08-31 08:52:08.855  6721  7698 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46937
,08-31 08:52:08.855  6721  7698 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 08:52:09.415  7689  7689 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
08-31 08:52:09.415  7689  7689 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 08:52:09.415  7689  7689 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-31 08:52:09.415  7689  7689 I wpa_supplicant: Trying to associate with  'G700'
08-31 08:52:09.415  7689  7689 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-31 08:52:09.415  7689  7689 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-31 08:52:09.415  1017  7695 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 08:52:09.435  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 08:52:09.435  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:52:09.545  7689  7689 E wpa_supplicant: Cmd 35605 not handled
,08-31 08:52:09.545  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 08:52:09.545  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:52:09.545  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 08:52:09.545  7689  7689 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 08:52:09.545  7689  7689 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 08:52:09.545  7689  7689 I wpa_supplicant: Associated with F4.99.3E
08-31 08:52:09.545  7689  7689 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 08:52:09.545  7689  7689 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 08:52:09.545  7689  7689 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-31 08:52:09.545  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 08:52:09.545  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:52:09.545  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:52:09.545  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 08:52:09.545  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 08:52:09.545  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 08:52:09.545  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:52:09.545  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:52:09.545  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 08:52:09.555  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 08:52:09.555  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:52:09.555  7689  7689 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-31 08:52:09.555  7689  7689 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-31 08:52:09.555  7689  7689 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-31 08:52:09.555  7689  7689 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
08-31 08:52:09.555  7689  7689 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 08:52:09.555  7689  7689 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 08:52:09.555  7689  7689 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-31 08:52:09.555  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 08:52:09.555  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-31 08:52:09.555  7689  7689 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 08:52:09.555  7689  7689 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-31 08:52:09.555  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 08:52:09.555  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 08:52:09.555  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-31 08:52:09.565  1017  1130 E Tethering: No numeric data
,08-31 08:52:09.565  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 08:52:09.565  1017  1130 D Tethering: clearTetheredNotification()
,08-31 08:52:09.565  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50],
08-31 08:52:09.565  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:52:09.565  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:09.565  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 08:52:09.565  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:52:09.565  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 08:52:09.565  1175  1175 D HotspotTile: updateTetherState():false, false
,08-31 08:52:09.575  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:09.575  1017  1123 V NetworkStats: performPollLocked() took 6ms
,08-31 08:52:09.575  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 08:52:09.585  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:52:09.585  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:52:09.585  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:09.585  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:09.585  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:09.585  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:09.585  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:09.585  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:09.585  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-31 08:52:09.585  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-31 08:52:09.585  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 08:52:09.585  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 08:52:09.595  1017  4350 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:52:09.595  1017  4350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:52:09.595  1017  4350 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:09.595  1017  4350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:09.595  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:52:09.605  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:52:09.605  1606  1606 I Hs20UtilService: Starting #21
,08-31 08:52:09.605  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 08:52:09.605  3076  3076 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 08:52:09.605  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 08:52:09.605  1606  1643 I Hs20UtilService: Message received 5007,
,08-31 08:52:09.605  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 08:52:09.605  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 08:52:09.605  3076  3076 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 08:52:09.605  3076  3799 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:52:09.615  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:52:09.615   291   291 E SMD     : DCD OFF
,08-31 08:52:09.625   278   977 D CommandListener: Setting iface cfg
,08-31 08:52:09.625  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 3
,08-31 08:52:09.625  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 08:52:09.625  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:52:09.635  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:52:09.635  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 08:52:09.635  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:09.645  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:09.645  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:09.645  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:09.645  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 08:52:09.645  1017  1126 D SecContentProvider2: mCursor = null
,08-31 08:52:09.655  1017  1126 E WifiNative-wlan0: do suspend false
,08-31 08:52:09.655  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-31 08:52:09.655  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 08:52:09.865  6721  6775 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1326)
08-31 08:52:09.865  6721  6775 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1326)
,08-31 08:52:09.865  6721  6775 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1331),
,08-31 08:52:09.865  6721  6775 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 08:52:09.865  6721  6775 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1332)
,08-31 08:52:09.865  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,08-31 08:52:09.865  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c723e4 added. We now have 2 listener(s)
,08-31 08:52:09.875  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 08:52:09.875  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:09.875  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 08:52:09.875  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:09.875  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1811f04d added. We now have 9 listener(s)
,08-31 08:52:09.875  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:09.875  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:52:09.875  7701  7701 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-31 08:52:09.875  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:09.885  7701  7701 I dhcpcd  : version 5.5.6 starting,
,08-31 08:52:09.885  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:09.885  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:09.885  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:09.885  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:09.885  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:09.885  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:09.885  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:09.885  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:09.885  7701  7701 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-31 08:52:09.885  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:09.885  6721  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:09.885  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:09.885  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@287ff813 added. We now have 3 listener(s)
,08-31 08:52:09.895  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 08:52:09.895  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:09.895  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:09.895  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:09.895  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:09.895  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dc49a50 added. We now have 10 listener(s)
08-31 08:52:09.895  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:09.895  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:09.895  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:09.895  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:09.895  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:09.895  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:09.895  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:52:09.895  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:09.895  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c723e4 removed from the list
08-31 08:52:09.895  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:09.895  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1811f04d removed from the list
,08-31 08:52:09.895  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:09.895  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:09.895  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:09.905  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:09.905  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:09.915  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:09.915  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:09.915  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:09.915  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1811f04d not in the list
08-31 08:52:09.915  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:09.915  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:09.915  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:09.915  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:09.915  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:09.915  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dc49a50 removed from the list
08-31 08:52:09.915  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:09.915  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:09.915  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:09.915  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:09.915  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@287ff813 removed from the list
08-31 08:52:09.915  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:09.915  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9a4449 added. We now have 2 listener(s)
,08-31 08:52:09.915  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 08:52:09.915  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:09.915  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:09.915  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:09.915  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24f3814e added. We now have 9 listener(s)
08-31 08:52:09.915  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:09.915  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:52:09.925  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:09.935  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:09.935  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:09.935  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:09.935  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:09.935  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:09.935  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:09.935  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:09.935  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:09.945  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-31 08:52:09.945  6721  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:09.945  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-31 08:52:09.945  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e10b7c added. We now have 3 listener(s)
,08-31 08:52:09.945  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:09.955  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 08:52:09.955  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:09.955  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:09.955  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:09.955  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d39dc05 added. We now have 10 listener(s)
08-31 08:52:09.955  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:09.955  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:09.955  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:52:09.955  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 08:52:09.955  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:09.955  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:52:09.955  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:09.955  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:52:09.975  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:52:09.975  7701  7701 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-31 08:52:09.975  7701  7701 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,08-31 08:52:09.975  7701  7701 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-31 08:52:09.975  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 08:52:09.975  7701  7701 I dhcpcd  : bssid match
08-31 08:52:09.975  7701  7701 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-31 08:52:09.975  1017  1561 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 08:52:09.975  1017  1561 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-31 08:52:09.975  1017  1561 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-31 08:52:09.985  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-31 08:52:09.985  1017  1561 D BatteryService: stay LED for fully charged
,08-31 08:52:09.985  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 08:52:09.985  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:52:09.985  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:52:09.985  1017  1017 I MotionRecognitionService: Plugged
,08-31 08:52:09.985  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 08:52:09.985  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 08:52:09.985  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 08:52:09.985  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 08:52:09.985  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 08:52:09.995  7582  7663 D BtGatt.GattService: registerClient() - UUID=7c3a8aae-0122-40b4-a72a-8982179c23e8,
08-31 08:52:09.995  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 08:52:09.995  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-31 08:52:09.995  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 08:52:10.005  7582  7582 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 08:52:10.005  7582  7613 D HeadsetStateMachine: Disconnected process message: 10
,08-31 08:52:10.025  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-31 08:52:10.025  1175  1175 D SViewCoverView: level :100 plugged : 2
,08-31 08:52:10.035  7582  7607 D BtGatt.GattService: onClientRegistered() - UUID=7c3a8aae-0122-40b4-a72a-8982179c23e8, clientIf=6
,08-31 08:52:10.035  6721  6766 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 08:52:10.045  7582  7608 D BtGatt.GattService: start scan with filters
,08-31 08:52:10.045  7582  7612 D BtGatt.ScanManager: handling starting scan
,08-31 08:52:10.045  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 08:52:10.045  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:52:10.045  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:52:10.045  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 08:52:10.045  7582  7612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@54880a7
,08-31 08:52:10.045  7582  7607 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 08:52:10.045  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.045  7582  7612 D BtGatt.ScanManager: allow scan with filters
08-31 08:52:10.045  7582  7612 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 08:52:10.045  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:52:10.055  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:52:10.055  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:10.055  7582  7612 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-31 08:52:10.055  7582  7607 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 08:52:10.055  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.055  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:52:10.055  7582  7612 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:52:10.055  7582  7612 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 08:52:10.055  7582  7607 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 08:52:10.055  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.065  6721  6775 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:52:10.065  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:10.065  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 08:52:10.065  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.065  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:52:10.065  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:52:10.065  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:52:10.065  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:52:10.065  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:52:10.065  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:52:10.065  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:52:10.065  7582  7607 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 08:52:10.065  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.065  7582  7676 D BtGatt.GattService: stopScan() - queue size =1
,08-31 08:52:10.065  7582  7593 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 08:52:10.065  7582  7612 D BtGatt.ScanManager: filter size is 1
,08-31 08:52:10.065  7582  7612 D BtGatt.ScanManager: delete FilterIndex - 3
,08-31 08:52:10.075  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:52:10.075  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:52:10.075  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:52:10.075  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:52:10.075  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:52:10.075  7582  7607 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 08:52:10.075  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.075  7582  7612 D BtGatt.ScanManager: stopping BLe Batch
,08-31 08:52:10.075  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:10.075  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 08:52:10.075  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:52:10.075  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 08:52:10.075  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:52:10.075  7582  7607 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 08:52:10.075  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.075  7582  7612 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 08:52:10.075  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 08:52:10.075  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 08:52:10.085  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:10.085  7582  7607 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 08:52:10.085  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.085  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:52:10.085  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:10.085  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:10.085  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:10.085  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.085  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:10.085  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:10.085  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9a4449 removed from the list
08-31 08:52:10.085  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:10.085  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24f3814e removed from the list
08-31 08:52:10.085  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:10.085  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:10.085  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.085  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:10.085  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:10.085  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:10.085  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:10.085  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24f3814e not in the list
08-31 08:52:10.085  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:10.085  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:10.085  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 08:52:10.085  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:10.095  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:10.095  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d39dc05 removed from the list
08-31 08:52:10.095  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:10.095  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.095  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:10.095  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:10.095  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e10b7c removed from the list
,08-31 08:52:10.095  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 08:52:10.095  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29813381 added. We now have 2 listener(s)
,08-31 08:52:10.095  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 08:52:10.095  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:10.095  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 08:52:10.095  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:10.095  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@207a6c26 added. We now have 9 listener(s)
,08-31 08:52:10.095  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:10.095  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:52:10.095  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:10.105  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:10.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:10.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:10.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:10.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:10.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:10.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:10.105  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:10.105  7701  7701 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-31 08:52:10.105  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:10.105  6721  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:10.105  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:10.105  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72d4e14 added. We now have 3 listener(s)
,08-31 08:52:10.105  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:10.105  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 08:52:10.105  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:10.105  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:10.105  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:10.105  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@138c86bd added. We now have 10 listener(s)
08-31 08:52:10.105  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:10.105  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:10.105  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:10.105  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:52:10.105  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:52:10.105  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:10.105  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:52:10.105  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:10.115  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:52:10.115  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:52:10.115  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:52:10.115  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:52:10.115  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:52:10.115  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:52:10.125  7582  7590 D BtGatt.GattService: registerClient() - UUID=c35e70c3-062d-4b11-9fae-a5cbf75023af
,08-31 08:52:10.175  7582  7607 D BtGatt.GattService: onClientRegistered() - UUID=c35e70c3-062d-4b11-9fae-a5cbf75023af, clientIf=6
,08-31 08:52:10.175  6721  6732 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 08:52:10.175  7582  7676 D BtGatt.GattService: start scan with filters
,08-31 08:52:10.175  7582  7612 D BtGatt.ScanManager: handling starting scan
,08-31 08:52:10.175  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:52:10.175  7582  7607 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 08:52:10.175  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:52:10.175  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:52:10.175  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 08:52:10.175  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.175  7582  7612 D BtGatt.ScanManager: allow scan with filters
,08-31 08:52:10.175  7582  7612 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 08:52:10.175  7582  7612 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-31 08:52:10.175  7582  7607 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 08:52:10.175  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.175  7582  7612 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 08:52:10.175  7582  7612 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 08:52:10.185  7582  7607 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 08:52:10.185  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.185  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:10.185  7582  7607 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 08:52:10.185  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.195  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 08:52:10.195  7701  7701 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-31 08:52:10.195  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:10.195  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:52:10.195  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
08-31 08:52:10.195  6721  6775 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 08:52:10.195  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:10.195  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:52:10.195  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:10.195  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:10.195  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.195  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 08:52:10.195  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:10.195  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29813381 removed from the list
,08-31 08:52:10.195  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:10.195  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@207a6c26 removed from the list
08-31 08:52:10.195  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:10.195  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:10.195  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
08-31 08:52:10.195  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 08:52:10.195  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.195  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:10.205  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:10.205  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:10.205  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:10.205  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@207a6c26 not in the list
08-31 08:52:10.205  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 08:52:10.205  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:52:10.205  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:52:10.205  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:52:10.205  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:52:10.205  7582  7663 D BtGatt.GattService: stopScan() - queue size =1
,08-31 08:52:10.205  7582  7612 D BtGatt.ScanManager: filter size is 1
08-31 08:52:10.205  7582  7612 D BtGatt.ScanManager: delete FilterIndex - 4
08-31 08:52:10.205  7582  7590 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 08:52:10.205  7582  7607 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 08:52:10.205  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:52:10.205  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-31 08:52:10.205  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:52:10.205  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:52:10.205  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:52:10.205  7582  7612 D BtGatt.ScanManager: stopping BLe Batch
08-31 08:52:10.205  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:52:10.215  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:10.215  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 08:52:10.215  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:52:10.215  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:52:10.215  7582  7607 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 08:52:10.215  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:52:10.215  7582  7612 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 08:52:10.215  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:10.215  7582  7607 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 08:52:10.215  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-31 08:52:10.215  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-31 08:52:10.215  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:10.215  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:10.215  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@138c86bd removed from the list
08-31 08:52:10.215  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:10.215  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.215  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 08:52:10.215  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:10.215  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:10.215  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:10.215  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72d4e14 removed from the list
08-31 08:52:10.215  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:10.225  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:10.225  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37ffd1b9 added. We now have 2 listener(s)
,08-31 08:52:10.225  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 08:52:10.225  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:10.225  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:10.225  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:10.225  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e8d9fe added. We now have 9 listener(s)
08-31 08:52:10.225  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:10.235  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:52:10.245  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:10.245  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:10.245  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:10.245  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:10.245  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-31 08:52:10.245  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:10.245  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:10.245  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:10.245  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:10.245  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:10.245  6721  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:10.245  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:10.245  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43c4bac added. We now have 3 listener(s),
,08-31 08:52:10.255  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:10.255  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:10.255  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 08:52:10.255  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:10.255  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:10.255  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:10.255  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fc2d075 added. We now have 10 listener(s)
08-31 08:52:10.255  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:10.255  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:10.255  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:52:10.255  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:52:10.255  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:10.255  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:52:10.255  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-31 08:52:10.265  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-31 08:52:10.275  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:52:10.285  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 08:52:10.285  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:52:10.285  6721  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 08:52:10.285  7582  7608 D BtGatt.GattService: registerClient() - UUID=33eb9e02-d952-446e-9404-35a014e2981a
,08-31 08:52:10.325  7582  7607 D BtGatt.GattService: onClientRegistered() - UUID=33eb9e02-d952-446e-9404-35a014e2981a, clientIf=6
,08-31 08:52:10.325  6721  6732 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
,08-31 08:52:10.325  7582  7593 D BtGatt.GattService: start scan with filters
,08-31 08:52:10.325  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 08:52:10.325  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:52:10.325  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:52:10.325  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
08-31 08:52:10.335  7582  7612 D BtGatt.ScanManager: handling starting scan
08-31 08:52:10.335  7582  7607 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-31 08:52:10.335  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:52:10.335  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:52:10.335  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 08:52:10.335  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:52:10.335  7582  7612 D BtGatt.ScanManager: allow scan with filters
08-31 08:52:10.335  7582  7612 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 08:52:10.335  7582  7612 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-31 08:52:10.335  7582  7607 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 08:52:10.335  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:52:10.335  7582  7612 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:52:10.335  7582  7612 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 08:52:10.335  7582  7607 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 08:52:10.335  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.335  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:52:10.345  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:52:10.345  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:10.345  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:52:10.345  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-31 08:52:10.345  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 08:52:10.345  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:52:10.345  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:10.345  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37ffd1b9 removed from the list
08-31 08:52:10.345  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 08:52:10.345  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e8d9fe removed from the list
08-31 08:52:10.345  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:10.345  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:10.345  7582  7607 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 08:52:10.345  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:52:10.355  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:10.355  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 08:52:10.355  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.355  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:52:10.355  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:10.355  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:10.355  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:10.355  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e8d9fe not in the list
08-31 08:52:10.355  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:52:10.355  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:52:10.355  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:52:10.355  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:52:10.355  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:52:10.355  7582  7676 D BtGatt.GattService: stopScan() - queue size =1
08-31 08:52:10.355  7582  7663 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 08:52:10.355  7582  7612 D BtGatt.ScanManager: filter size is 1
08-31 08:52:10.355  7582  7612 D BtGatt.ScanManager: delete FilterIndex - 5
,08-31 08:52:10.365  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:52:10.365  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:52:10.365  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:52:10.365  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:52:10.365  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 08:52:10.365  7582  7607 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 08:52:10.365  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.365  7582  7612 D BtGatt.ScanManager: stopping BLe Batch
,08-31 08:52:10.365  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:10.365  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-31 08:52:10.365  6721  6775 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:52:10.365  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:52:10.365  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:10.365  7582  7607 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 08:52:10.365  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 08:52:10.365  7582  7612 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 08:52:10.365  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:10.365  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:10.365  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:10.365  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fc2d075 removed from the list
08-31 08:52:10.365  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:10.365  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.365  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:10.365  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:10.365  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43c4bac removed from the list,
08-31 08:52:10.365  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:10.365  6721  6721 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:10.365  6721  6721 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:52:10.365  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:10.365  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cfef1 added. We now have 2 listener(s)
08-31 08:52:10.365  7582  7607 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-31 08:52:10.365  7582  7607 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 08:52:10.375  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 08:52:10.375  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:10.375  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:10.375  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:10.375  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a4c2ad6 added. We now have 9 listener(s)
08-31 08:52:10.375  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:10.375  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:52:10.375  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:10.375  6721  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:10.375  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:10.375  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:10.375  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:10.375  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:10.375  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:10.375  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:10.375  6721  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:10.385  6721  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:10.385  6721  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:52:10.385  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:10.385  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64a6444 added. We now have 3 listener(s)
,08-31 08:52:10.385  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:10.385  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 08:52:10.385  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:10.385  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:10.385  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:10.385  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28d1992d added. We now have 10 listener(s)
08-31 08:52:10.385  6721  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:10.385  6721  6775 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:10.385  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:10.385  6721  6775 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:10.385  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:10.385  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.385  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:10.385  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:10.385  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cfef1 removed from the list
08-31 08:52:10.385  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:10.385  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a4c2ad6 removed from the list
,08-31 08:52:10.385  6721  6721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:10.385  6721  6775 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:10.385  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:10.385  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.385  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:10.385  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:10.385  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:10.385  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:10.385  6721  6775 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a4c2ad6 not in the list
08-31 08:52:10.385  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.385  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:10.395  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:10.395  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:10.395  6721  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:10.395  6721  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28d1992d removed from the list
08-31 08:52:10.395  6721  6775 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:10.395  6721  6775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:10.395  6721  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:10.395  6721  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:10.395  6721  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64a6444 removed from the list
,08-31 08:52:10.395  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 08:52:10.395  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 08:52:10.395  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-31 08:52:10.395  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:10.395  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 08:52:10.395  6721  6775 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:52:10.395  6721  7731 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1339, name: My test thread name)
,08-31 08:52:10.395  6721  7731 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1339, thread name: My test thread name)
08-31 08:52:10.395  6721  7731 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1339, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 08:52:10.405  6721  7732 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1341, name: My test thread name)
,08-31 08:52:10.405  6721  7732 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1341, thread name: My test thread name)
08-31 08:52:10.405  6721  7732 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1341, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 08:52:10.405  6721  6775 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
08-31 08:52:10.405  6721  6775 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 08:52:10.405  6721  6775 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 08:52:10.405  6721  6775 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0,
08-31 08:52:10.405  6721  6775 D com.test.thalitest.ThaliTestRunner: Total duration: 23324 ms
08-31 08:52:10.405  6721  6775 I jxcore-log: *Native tests were executed*
08-31 08:52:10.405  6721  6775 I jxcore-log: 
08-31 08:52:10.405  6721  6775 I jxcore-log: Total number of executed tests:  80,
08-31 08:52:10.405  6721  6775 I jxcore-log: 
08-31 08:52:10.405  6721  6775 I jxcore-log: Number of passed tests:  80
08-31 08:52:10.405  6721  6775 I jxcore-log: 
08-31 08:52:10.405  6721  6775 I jxcore-log: Number of failed tests:  0
08-31 08:52:10.405  6721  6775 I jxcore-log: 
,08-31 08:52:10.405  6721  6775 I jxcore-log: Number of ignored tests:  0
08-31 08:52:10.405  6721  6775 I jxcore-log: 
08-31 08:52:10.405  6721  6775 I jxcore-log: Total duration:  23324
08-31 08:52:10.405  6721  6775 I jxcore-log: 
08-31 08:52:10.405  6721  6775 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,08-31 08:52:10.405  6721  6775 I jxcore-log: 
08-31 08:52:10.415  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:10.415  6721  6775 I jxcore-log: 
08-31 08:52:10.415  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:10.415  6721  6775 I jxcore-log: 
08-31 08:52:10.415  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:10.415  6721  6775 I jxcore-log: 
08-31 08:52:10.415  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:10.415  6721  6775 I jxcore-log: 
08-31 08:52:10.415  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:10.415  6721  6775 I jxcore-log: 
08-31 08:52:10.415  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:10.415  6721  6775 I jxcore-log: 
08-31 08:52:10.425  6721  6721 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 08:52:10.425  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:10.425  6721  6775 I jxcore-log: 
08-31 08:52:10.425  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:10.425  6721  6775 I jxcore-log: 
08-31 08:52:10.425  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:52:10.425  6721  6775 I jxcore-log: 
08-31 08:52:10.425  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:10.425  6721  6775 I jxcore-log: 
08-31 08:52:10.425  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:10.425  6721  6775 I jxcore-log: 
08-31 08:52:10.425  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 08:52:10.425  6721  6775 I jxcore-log: 
08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
,08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
,08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
,08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
,08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
,08-31 08:52:10.435  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:52:10.435  6721  6775 I jxcore-log: 
,08-31 08:52:10.475  1017  1126 E WifiNative-wlan0: do suspend true,
,08-31 08:52:10.485  1017  1125 D WifiP2pService: InactiveState{ what=143375 },
08-31 08:52:10.485  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 },
08-31 08:52:10.495  1017  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
08-31 08:52:10.495  1017  1126 E WifiStateMachine: VerifyingLinkState enter,
,08-31 08:52:10.505  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:52:10.505  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:52:10.505  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.505  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.505  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.505  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.505  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-31 08:52:10.505  1017  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-31 08:52:10.505  1017  1128 D ConnectivityService: Adding iface wlan0 to network 504
,08-31 08:52:10.515  1017  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-31 08:52:10.515  1017  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 08:52:10.515  1017  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 08:52:10.515  1017  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 08:52:10.515  1017  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 08:52:10.525  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:52:10.525  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:52:10.525  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.525  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.525  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.525  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:10.545  1017  4351 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:10.545  1017  4351 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:52:10.545  1017  4351 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:10.545  1017  4351 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:52:10.545  1017  4351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:52:10.545  1017  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-31 08:52:10.545  1606  1606 I Hs20UtilService: Starting #22
,08-31 08:52:10.545  1606  1643 I Hs20UtilService: Message received 5007
,08-31 08:52:10.555  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 08:52:10.555  3076  3076 I NearbySettings: MountReceiver.onReceive - Keep current state,
,08-31 08:52:10.565  1017  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-31 08:52:10.565  1017  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504,
,08-31 08:52:10.565  1017  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-31 08:52:10.575  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 08:52:10.575  1017  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 08:52:10.575  1017  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1],
08-31 08:52:10.575  1017  1128 D ConnectivityService: LTETest block dns file not exists,
08-31 08:52:10.575  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 08:52:10.575  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 08:52:10.575  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.575  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.575  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.575  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.585  6721  6721 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 08:52:10.585  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:52:10.585  6721  6775 I jxcore-log: 
,08-31 08:52:10.585  1017  1128 V NetworkStats: updateIfacesLocked()
08-31 08:52:10.585  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 08:52:10.585  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:52:10.585  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 08:52:10.585  1017  4350 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 08:52:10.585  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.585  1017  4350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 08:52:10.585  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:52:10.585  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:52:10.585  1017  4350 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:10.585  1017  4350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:10.585  1017  4350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:52:10.595  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.595  1017  1128 V NetworkStats: performPollLocked() took 5ms
,08-31 08:52:10.595  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 08:52:10.595  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-31 08:52:10.595  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
08-31 08:52:10.595  1606  1606 I Hs20UtilService: Starting #23
,08-31 08:52:10.595  1606  1643 I Hs20UtilService: Message received 5007
,08-31 08:52:10.595  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:52:10.605  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 08:52:10.605  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:10.605  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 08:52:10.605  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-31 08:52:10.605  1017  1128 E ConnectivityService: updateNetworkInfo()
08-31 08:52:10.605  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:52:10.605  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.605  1017  1128 V NetworkStats: updateIfacesLocked()
08-31 08:52:10.605  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:52:10.605  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:52:10.605  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:52:10.615  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.615  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.615  1017  1128 V NetworkStats: performPollLocked() took 6ms
08-31 08:52:10.615  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.615  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.615  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.615  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 08:52:10.615  3076  3076 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 08:52:10.615  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:10.615  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.615  1017  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
,08-31 08:52:10.615  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.615  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-31 08:52:10.615  1017  7699 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:10.615  1017  7699 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-31 08:52:10.615  1017  1128 D ConnectivityService:    accepting network in place of null
08-31 08:52:10.615  1017  7699 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:10.615  1017  7699 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-31 08:52:10.615  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 08:52:10.615  1017  7699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 08:52:10.615  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 08:52:10.615  3076  3076 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 08:52:10.615  3076  3076 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 08:52:10.615  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 08:52:10.615  3076  3799 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 08:52:10.615  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 08:52:10.625  1458  1458 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 08:52:10.625  1458  1458 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 08:52:10.625  1017  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 08:52:10.625   278   973 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 08:52:10.625   278   973 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-31 08:52:10.625  1017  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,08-31 08:52:10.625  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 08:52:10.625  1017  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-31 08:52:10.625  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504],
08-31 08:52:10.625  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE,
08-31 08:52:10.625  1017  1130 D Tethering: MasterInitialState.processMessage what=3
08-31 08:52:10.625  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-31 08:52:10.625  1175  1675 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 08:52:10.635  4777  6783 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 08:52:10.635  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 08:52:10.635  1017  1123 V NetworkStats: updateIfacesLocked()
08-31 08:52:10.635  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:52:10.635  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-31 08:52:10.635  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 08:52:10.635  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
08-31 08:52:10.635  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-31 08:52:10.635  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 08:52:10.635  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-31 08:52:10.635  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 08:52:10.635  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 08:52:10.645  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.645  1017  1123 V NetworkStats: performPollLocked() took 7ms
08-31 08:52:10.645  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.645  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 08:52:10.645  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.645  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.645  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 08:52:10.645  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.645  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-31 08:52:10.645  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.645  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:10.645  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-31 08:52:10.645  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:52:10.645  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 08:52:10.645  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.645  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.645  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.645  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:10.645  1017  1561 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 08:52:10.645  1017  1561 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 08:52:10.655  1017  1561 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:10.655  1017  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:10.655  1017  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 08:52:10.655  1606  1606 I Hs20UtilService: Starting #24
08-31 08:52:10.655  1606  1643 I Hs20UtilService: Message received 5007
08-31 08:52:10.655  3076  3076 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 08:52:10.655  3076  3076 I NearbySettings: MountReceiver.onReceive - Keep current state,
,08-31 08:52:10.665  1017  1030 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-31 08:52:10.665  1017  1100 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-31 08:52:10.665  1017  1100 D SecContentProvider2: mCursor = null
,08-31 08:52:10.665  1017  4351 D SecContentProvider2: uri = 15 selection = getToastGravity
08-31 08:52:10.665  1017  4351 D SecContentProvider2: mCursor = null
,08-31 08:52:10.665  1017  1029 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-31 08:52:10.665  1017  1029 D SecContentProvider2: mCursor = null
,08-31 08:52:10.665  1017  1567 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-31 08:52:10.665  1017  1567 D SecContentProvider2: mCursor = null
08-31 08:52:10.675  1017  1478 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-31 08:52:10.675  1017  1478 D SecContentProvider2: mCursor = null
,08-31 08:52:10.675  1017  1561 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-31 08:52:10.675  1017  1561 D SecContentProvider2: mCursor = null
,08-31 08:52:10.695   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast,
,08-31 08:52:10.705  1017  1486 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017,
,08-31 08:52:10.705  1175  1175 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 08:52:10.715  6721  6721 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-31 08:52:10.725  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:52:10.725  6721  6775 I jxcore-log: 
08-31 08:52:10.725  1017  7699 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 08:52:10.725  7734  7734 D AndroidRuntime: ,
08-31 08:52:10.725  7734  7734 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 08:52:10.735  7734  7734 D AndroidRuntime: CheckJNI is OFF,
08-31 08:52:10.735  7734  7734 D AndroidRuntime: readGMSProperty: start
,08-31 08:52:10.735  7734  7734 D AndroidRuntime: readGMSProperty: already setted!!
08-31 08:52:10.735  7734  7734 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 08:52:10.735  7734  7734 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,08-31 08:52:10.735  7734  7734 D AndroidRuntime: readGMSProperty: end
08-31 08:52:10.735  7734  7734 D AndroidRuntime: addProductProperty: start
,08-31 08:52:10.795  1017  7699 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 06:52:10 GMT], X-Android-Received-Millis=[1472626330806], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472626330758]},
08-31 08:52:10.795  1017  7699 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 08:52:10.795  1017  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-31 08:52:10.795  1017  7699 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-31 08:52:10.795  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-31 08:52:10.795  1017  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.,
08-31 08:52:10.795  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-31 08:52:10.795  1175  1675 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 08:52:10.795  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 08:52:10.795  4777  6783 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 08:52:10.795  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
,08-31 08:52:10.795  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-31 08:52:10.795  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 08:52:10.795  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-31 08:52:10.795  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 08:52:10.795  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 08:52:10.795  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-31 08:52:10.795  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-31 08:52:10.795  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal,
08-31 08:52:10.795  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 08:52:10.795  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-31 08:52:10.805  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.805  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:10.805  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 08:52:10.805  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 08:52:10.855  7734  7734 E AffinityControl: AffinityControl: registerfunction enter,
,08-31 08:52:10.865  6721  6721 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 08:52:10.875  6721  6775 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:52:10.875  6721  6775 I jxcore-log: 
,08-31 08:52:10.875  7734  7734 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 08:52:10.895  1017  1440 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
,08-31 08:52:10.895  1017  1440 D PackageManager: START PACKAGE DELETE: observer{933621966}
,08-31 08:52:10.895  1017  1440 D PackageManager: pkg{<packageName>},
08-31 08:52:10.895  1017  1440 D PackageManager: user{0}
08-31 08:52:10.895  1017  1440 D PackageManager: caller{2000}
,08-31 08:52:10.895  1017  1440 D PackageManager: flags{2}
,08-31 08:52:10.895  1017  1440 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-31 08:52:10.895  1017  1440 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
08-31 08:52:10.905  1017  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-31 08:52:10.895  1017  1440 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 08:52:10.895  1017  1440 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 08:52:10.905  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-31 08:52:10.905  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 08:52:10.905  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-31 08:52:10.905  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 08:52:10.905  1017  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-31 08:52:10.935  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-31 08:52:10.935  1017  1042 I ActivityManager: Killing 6721:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-31 08:52:11.005  1017  1056 W PackageSettings: Skipping PackageSetting{3deb7436 com.example.hello/10168} due to missing metadata
,08-31 08:52:11.035  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{1cd96ff3 u0 com.test.thalitest/.MainActivity t2}
,08-31 08:52:11.035  1017  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-31 08:52:11.045  1017  1056 I ActivityManager:   Force finishing activity ActivityRecord{1cd96ff3 u0 com.test.thalitest/.MainActivity t2 f}
,08-31 08:52:11.045  1017  1056 W ActivityManager: Duplicate finish request for ActivityRecord{1cd96ff3 u0 com.test.thalitest/.MainActivity t2 f}
,08-31 08:52:11.045  1017  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-31 08:52:11.055  1017  1042 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-31 08:52:11.065  1017  1042 D InputDispatcher: Focus left window: 6721
,08-31 08:52:11.065   258   450 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-31 08:52:11.065   258   443 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-31 08:52:11.085  1017  1042 D InputDispatcher: Focused application released
,08-31 08:52:11.085  2646  2646 I art     : Explicit concurrent mark sweep GC freed 19542(1115KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 775us total 31.596ms
,08-31 08:52:11.085  1017  1047 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-31 08:52:11.085  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 08:52:11.085  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 08:52:11.085  1017  1042 D FocusedStackFrame: Set to : 0
,08-31 08:52:11.085  1017  1042 W ActivityManager: mDVFSHelper.acquire()
,08-31 08:52:11.095  1017  1042 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-31 08:52:11.125  4777  4777 I art     : Explicit concurrent mark sweep GC freed 23278(1421KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 12MB/21MB, paused 1.271ms total 76.318ms
,08-31 08:52:11.125  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:11.125  1017  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 08:52:11.125  1480  1480 D Launcher: onRestart, Launcher: 329994493
,08-31 08:52:11.135  1872  1872 E SamsungIME: mOCRHelper is null
,08-31 08:52:11.145  1480  1480 D Launcher: onStart, Launcher: 329994493
,08-31 08:52:11.155  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-31 08:52:11.155  1480  1480 D Launcher.HomeView: onStart
,08-31 08:52:11.155  1480  1480 D Launcher: onResume, Launcher: 329994493
,08-31 08:52:11.155  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 08:52:11.155  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 08:52:11.155  1017  1569 D SettingsProvider: name = kids_home_mode
08-31 08:52:11.155  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-31 08:52:11.155  1017  1569 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 08:52:11.155  1017  1569 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 08:52:11.155  1017  1569 D SettingsProvider: selectionArgs: false
08-31 08:52:11.155  1017  1569 D SettingsProvider: selectionArgs: 10006
08-31 08:52:11.155  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
08-31 08:52:11.155  1017  1569 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 08:52:11.155  1017  1569 D SettingsProvider: ret = -1
,08-31 08:52:11.155  1480  1480 D Launcher.HomeView: onResume
,08-31 08:52:11.165  2898  2898 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 08:52:11 GMT+02:00 2016
,08-31 08:52:11.165  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,08-31 08:52:11.175  1458  1458 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 08:52:11.185  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 08:52:11.185  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-31 08:52:11.195  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-31 08:52:11.205  1017  1448 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-31 08:52:11.205  1017  1448 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 08:52:11.205  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:11.205  1017  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 08:52:11.205  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 08:52:11.215  1442  1442 D RegisteredServicesCache: empty dynamic service
,08-31 08:52:11.215  1480  1480 D MenuAppsGridFragment: onResume
,08-31 08:52:11.215  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-31 08:52:11.215  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:11.215  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-31 08:52:11.215  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:52:11.215  1480  1480 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-31 08:52:11.215  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:52:11.215  1480  1480 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-31 08:52:11.215  2898  2898 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 08:52:11.225  1017  1569 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,08-31 08:52:11.225  1017  1569 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-31 08:52:11.225  1017  1569 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-31 08:52:11.225  2898  2898 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 08:52:11.225  2898  2898 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 08:52:11.235  1017  1123 V NetworkStats: performPollLocked() took 17ms
,08-31 08:52:11.235  2898  2898 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 08:52:11.235  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:11.235  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.235  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.235  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.235  1017  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.245  2898  7753 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 08:52:11.245  2898  7753 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-31 08:52:11.245  2898  7753 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-31 08:52:11.245  2898  7753 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-31 08:52:11.255  1017  1569 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7755 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-31 08:52:11.265  7755  7755 E Zygote  : MountEmulatedStorage()
08-31 08:52:11.265  7755  7755 I libpersona: KNOX_SDCARD checking this for 10090
08-31 08:52:11.265  7755  7755 E Zygote  : v2
08-31 08:52:11.265  7755  7755 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:11.265  7755  7755 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:11.265  7755  7755 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:52:11.265  7755  7755 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:52:11.275  2003  2003 I art     : Explicit concurrent mark sweep GC freed 36421(1880KB) AllocSpace objects, 6(93KB) LOS objects, 39% free, 11MB/19MB, paused 1.383ms total 137.437ms
,08-31 08:52:11.275  2003  2159 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 08:52:11.285  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-31 08:52:11.285  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.285  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.285  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.285  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.295  1017  4351 I TactileAssist: enable value -1
,08-31 08:52:11.295  1017  4351 I TactileAssist: internal enable value -1
08-31 08:52:11.295  1017  4351 I TactileAssist: intensity value -1
08-31 08:52:11.295  1017  4351 I TactileAssist: saveAppList value true
,08-31 08:52:11.305  1017  4351 I TactileAssist: List of disabled apps :
,08-31 08:52:11.305  1017  4347 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-31 08:52:11.305  1017  4347 D SecContentProvider2: mCursor = null
,08-31 08:52:11.315  1017  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7764 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 08:52:11.315  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-31 08:52:11.315  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.315  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.315  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.315  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.315  7764  7764 E Zygote  : MountEmulatedStorage()
08-31 08:52:11.315  7764  7764 I libpersona: KNOX_SDCARD checking this for 1000
08-31 08:52:11.315  7764  7764 E Zygote  : v2
08-31 08:52:11.315  7764  7764 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:11.325  7764  7764 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:52:11.335  7770  7770 E Zygote  : MountEmulatedStorage()
08-31 08:52:11.335  7770  7770 E Zygote  : v2
08-31 08:52:11.335  7770  7770 I libpersona: KNOX_SDCARD checking this for 1000
08-31 08:52:11.335  7770  7770 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:11.335  7764  7764 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:52:11.335  7770  7770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:52:11.335  7764  7764 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:52:11.335  7770  7770 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:11.345  7770  7770 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:52:11.345  1017  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7770 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 08:52:11.345  1017  1567 D ActivityManager: handle home activity for 0
08-31 08:52:11.345  1017  1567 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-31 08:52:11.345  1017  1567 D KnoxTimeoutHandler: post home show event for user 0
08-31 08:52:11.345  1017  1567 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 08:52:11.345  1017  1567 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 08:52:11.345  1017  1567 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 08:52:11.345  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
08-31 08:52:11.345  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-31 08:52:11.345  2898  7753 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-31 08:52:11.345  1480  1480 D Launcher.HomeView: onPause
08-31 08:52:11.345  1017  1041 W TextServicesManagerService: no available spell checker services found
08-31 08:52:11.345  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-31 08:52:11.365  7755  7755 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:11.365  7755  7755 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:11.385  7770  7770 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:11.385  7770  7770 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:11.385  7764  7764 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:11.395  7764  7764 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:11.395   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-31 08:52:11.405  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-31 08:52:11.405  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-31 08:52:11.405  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 08:52:11.405  2898  7753 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-31 08:52:11.405  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-31 08:52:11.405  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-31 08:52:11.405  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-31 08:52:11.405  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
,08-31 08:52:11.415  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 08:52:11.415  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 08:52:11.415  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 08:52:11.415  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 08:52:11.415  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 08:52:11.415  2898  7753 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-31 08:52:11.415  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 08:52:11.415  1017  4347 D InputDispatcher: Focus entered window: 1480
,08-31 08:52:11.435  1017  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-31 08:52:11.435  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 08:52:11.435  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 08:52:11.435  1480  1480 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 08:52:11.435  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:11.435  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:11.435  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 08:52:11.435  2898  2898 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 08:52:11.445  1442  1442 D RegisteredComponentCache: Collect Tech packages for Knox
,08-31 08:52:11.445  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 08:52:11.445  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-31 08:52:11.445  1017  3387 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-31 08:52:11.445  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 08:52:11.445  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 08:52:11.445  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 08:52:11.445  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 08:52:11.445  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 08:52:11.445  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 08:52:11.445  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 08:52:11.445  1017  1017 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-31 08:52:11.445  1017  1567 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-31 08:52:11.445  1017  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.445  1017  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.445  1017  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.445  1017  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.455  1017  1128 V NetworkStats: updateIfacesLocked()
08-31 08:52:11.455  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:11.455  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-31 08:52:11.455  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 08:52:11.455  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 08:52:11.455  1017  1128 V NetworkStats: performPollLocked() took 4ms
,08-31 08:52:11.455  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:11.465  7801  7801 E Zygote  : MountEmulatedStorage()
08-31 08:52:11.465  7801  7801 E Zygote  : v2
08-31 08:52:11.465  7801  7801 I libpersona: KNOX_SDCARD checking this for 10048
08-31 08:52:11.465  7801  7801 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:11.465  7801  7801 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 08:52:11.465  7801  7801 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:11.465  7801  7801 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-31 08:52:11.485  1017  1567 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7801 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-31 08:52:11.485  1017  1160 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-31 08:52:11.485  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,08-31 08:52:11.495  7801  7801 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:11.495  7801  7801 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:11.505  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:52:11.505  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-31 08:52:11.505  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-31 08:52:11.505  4777  6783 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 08:52:11.505  1175  1675 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 08:52:11.505  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-31 08:52:11.515  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,08-31 08:52:11.515  1175  1675 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 08:52:11.515  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,08-31 08:52:11.515  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-31 08:52:11.515  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 08:52:11.515  4777  6783 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 08:52:11.515  1017  1056 I art     : Explicit concurrent mark sweep GC freed 77498(5MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 25MB/37MB, paused 17.164ms total 367.209ms
,08-31 08:52:11.515  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:52:11.525  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 08:52:11.525  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 08:52:11.535  7770  7770 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-31 08:52:11.535  1017  1440 D SecContentProvider2: uri = -1 selection = getSealedState
08-31 08:52:11.535  1017  1440 D SecContentProvider2: mCursor = null
,08-31 08:52:11.535  7770  7770 I PopupuiReceiver_KNOX: getSealedState : true
,08-31 08:52:11.535  1017  4351 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-31 08:52:11.535  1017  4351 D SecContentProvider2: mCursor = null
,08-31 08:52:11.545  7755  7755 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-31 08:52:11.545  7755  7755 D elm:15121: ELMEngine.ELMEngine( context ).
,08-31 08:52:11.555  7770  7770 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-31 08:52:11.555  7755  7755 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-31 08:52:11.555  1017  1561 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-31 08:52:11.555  1017  1561 D SecContentProvider2: mCursor = null
,08-31 08:52:11.555  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:52:11.555  1017  1056 D PackageManager: delete codoeFile: 
08-31 08:52:11.555  1017  1250 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-31 08:52:11.555  1017  1250 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-31 08:52:11.555  7770  7770 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
,08-31 08:52:11.555  7770  7770 D PopupuiReceiver: Action package removed
,08-31 08:52:11.565  1017  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-31 08:52:11.565  1017  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-31 08:52:11.565  1017  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:11.565  1017  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-31 08:52:11.565  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:52:11.565  1017  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
08-31 08:52:11.575  1017  1056 D PackageManager: result of delete: 1{933621966}
,08-31 08:52:11.575  1017  1366 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-31 08:52:11.575  1017  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.575  1017  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.575  1017  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.575  1017  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.585  7816  7816 E Zygote  : MountEmulatedStorage()
08-31 08:52:11.585  7816  7816 E Zygote  : v2
08-31 08:52:11.585  7816  7816 I libpersona: KNOX_SDCARD checking this for 10145
08-31 08:52:11.585  7816  7816 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:11.585  7816  7816 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 08:52:11.595  7816  7816 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 08:52:11.595  1017  1366 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7816 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 08:52:11.595  1017  1042 W ActivityManager: mDVFSHelper.release()
,08-31 08:52:11.595  7816  7816 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:52:11.595  7734  7734 D AndroidRuntime: Shutting down VM
,08-31 08:52:11.605  7801  7801 D Compatibility: onReceive() it will make start service
,08-31 08:52:11.605  1017  1440 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-31 08:52:11.615  1017  1440 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-31 08:52:11.615  1017  1440 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:11.615  1017  1440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:11.615  1017  1440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-31 08:52:11.615  7755  7755 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-31 08:52:11.615  1017  1440 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-31 08:52:11.625  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.625  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.625  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.625  1017  1440 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.625  7801  7829 D Compatibility: onHandleIntent()
,08-31 08:52:11.625  7801  7829 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-31 08:52:11.625  7801  7829 D Compatibility: found: 2
,08-31 08:52:11.635  7755  7755 D elm:15121: ElmAgentService : onCreate()
,08-31 08:52:11.635  7816  7816 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:11.635  7816  7816 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:11.635  7834  7834 E Zygote  : MountEmulatedStorage()
08-31 08:52:11.635  7834  7834 E Zygote  : v2
08-31 08:52:11.635  7834  7834 I libpersona: KNOX_SDCARD checking this for 10052
08-31 08:52:11.635  1017  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
08-31 08:52:11.635  7834  7834 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:11.635  7834  7834 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:11.635  7755  7830 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-31 08:52:11.635  7834  7834 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:11.645  7834  7834 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 08:52:11.645  1017  1440 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7834 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-31 08:52:11.645  7755  7830 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-31 08:52:11.645  1017  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 08:52:11.645  1017  1056 D PackageManager: userId{-1}
08-31 08:52:11.645  1017  1056 D PackageManager: andCode{true}
,08-31 08:52:11.645  7755  7830 D elm:15121: MDMBridge.getInstance()
08-31 08:52:11.645  7755  7830 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-31 08:52:11.655  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 08:52:11.655  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.655  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.655  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.655  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.665  7755  7830 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-31 08:52:11.665  1017  3167 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-31 08:52:11.665  1017  3167 D SecContentProvider2: mCursor = null
,08-31 08:52:11.665   309   309 I art     : Explicit concurrent mark sweep GC freed 8730(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 625us total 25.622ms,
,08-31 08:52:11.675  7764  7764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 ,
,08-31 08:52:11.675  7834  7834 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 08:52:11.675  7834  7834 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:11.685  7801  7829 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-31 08:52:11.685   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 20.552ms
,08-31 08:52:11.685  7801  7829 D Compatibility: skipping ResolveInfo{118e6ebc com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-31 08:52:11.685  7801  7829 D Compatibility: considering ResolveInfo{ca9e45 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-31 08:52:11.685  7801  7829 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-31 08:52:11.695  7801  7829 D Compatibility: enabling receiver ResolveInfo{dc999a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-31 08:52:11.695  7801  7829 D Compatibility: enabling receiver ResolveInfo{3bd682cb com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-31 08:52:11.705   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 17.704ms
,08-31 08:52:11.705  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-31 08:52:11.705  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:52:11.715  7801  7829 D Compatibility: enabling receiver ResolveInfo{a31baa8 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-31 08:52:11.715  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:52:11.715  7801  7829 D Compatibility: enabling receiver ResolveInfo{3fbd9c1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-31 08:52:11.715  7850  7850 E Zygote  : MountEmulatedStorage()
08-31 08:52:11.715  7850  7850 I libpersona: KNOX_SDCARD checking this for 1000
08-31 08:52:11.715  7850  7850 E Zygote  : v2
08-31 08:52:11.715  7850  7850 I libpersona: KNOX_SDCARD not a persona
08-31 08:52:11.725  7850  7850 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:11.725  7850  7850 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:11.725  7850  7850 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:52:11.725  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7850 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 08:52:11.725  7801  7829 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-31 08:52:11.725  1017  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-31 08:52:11.725  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.725  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.725  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.725  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.735  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:52:11.735  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 08:52:11.735  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:52:11.735  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 08:52:11.735  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:52:11.745  7859  7859 E Zygote  : MountEmulatedStorage()
,08-31 08:52:11.745  7859  7859 E Zygote  : v2
08-31 08:52:11.745  7859  7859 I libpersona: KNOX_SDCARD checking this for 10003
08-31 08:52:11.745  7859  7859 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:11.745  7859  7859 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:52:11.745  1017  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7859 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 08:52:11.755  7859  7859 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:11.755  7859  7859 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 08:52:11.755  7850  7850 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:11.755  7850  7850 D ActivityThread: Added TimaKeyStore provider,
,08-31 08:52:11.765  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:52:11.765  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:52:11.765  7755  7755 D elm:15121: ElmAgentService : onDestroy().
,08-31 08:52:11.765  1017  1478 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-31 08:52:11.765  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-31 08:52:11.765  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:52:11.765  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 08:52:11.775  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:11.775  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 08:52:11.775  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-31 08:52:11.775  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 08:52:11.775  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:52:11.775  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 08:52:11.785  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:52:11.785  7816  7816 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-31 08:52:11.785  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-31 08:52:11.785  7816  7816 D ThemeInfoUtil: isCurrentFestival = false
08-31 08:52:11.785  1017  1561 I ActivityManager: Killing 7196:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-31 08:52:11.785  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 08:52:11.785  1017  1561 I ActivityManager: Killing 7211:com.sec.spp.push/u0a32 (adj 15): empty #21
08-31 08:52:11.785  7859  7859 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:11.785  7859  7859 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:11.795  1017  4347 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-31 08:52:11.795  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.795  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.795  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.795  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.805  7734  7734 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 08:52:11.815  7881  7881 E Zygote  : MountEmulatedStorage()
08-31 08:52:11.815  7881  7881 I libpersona: KNOX_SDCARD checking this for 1000
08-31 08:52:11.815  7881  7881 E Zygote  : v2
08-31 08:52:11.815  7881  7881 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:11.815  7881  7881 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:52:11.815  1017  4347 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7881 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 08:52:11.815  7881  7881 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 08:52:11.825  1017  4347 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-31 08:52:11.825  7881  7881 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:52:11.825  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.825  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.825  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.825  1017  4347 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.835  7850  7850 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-31 08:52:11.835  7850  7850 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 08:52:11.835  7850  7850 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 08:52:11.845  7890  7890 E Zygote  : MountEmulatedStorage(),
08-31 08:52:11.845  7890  7890 E Zygote  : v2
08-31 08:52:11.845  7890  7890 I libpersona: KNOX_SDCARD checking this for 10148
,08-31 08:52:11.845  7890  7890 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:11.845  7890  7890 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 08:52:11.845  1017  4347 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7890 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a,
08-31 08:52:11.845  1017  4347 I ActivityManager: Killing 7237:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-31 08:52:11.845  7890  7890 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:11.845  7890  7890 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:52:11.865  1017  1478 D PersonaManager: isKioskContainerExistOnDevice
,08-31 08:52:11.865  7881  7881 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:11.865  7881  7881 D ActivityThread: Added TimaKeyStore provider
,08-31 08:52:11.875  7890  7890 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 08:52:11.875  7850  7850 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-31 08:52:11.875  7890  7890 D ActivityThread: Added TimaKeyStore provider
08-31 08:52:11.875  7850  7850 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 08:52:11.875  7850  7850 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 08:52:11.875  7850  7850 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-31 08:52:11.885  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-31 08:52:11.895  1017  1561 I ActivityManager: Killing 7258:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-31 08:52:11.895  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-31 08:52:11.895  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-31 08:52:11.905  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.905  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.905  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.905  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:11.915  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:11.915  7913  7913 E Zygote  : MountEmulatedStorage()
08-31 08:52:11.915  7913  7913 E Zygote  : v2
08-31 08:52:11.915  7913  7913 I libpersona: KNOX_SDCARD checking this for 10029
08-31 08:52:11.915  7913  7913 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:11.915  7913  7913 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 08:52:11.915  7881  7881 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 08:52:11.925  1017  1030 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7913 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-31 08:52:11.925  7913  7913 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:11.925  7913  7913 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 08:52:11.925  1017  1030 I ActivityManager: Killing 7164:com.android.chrome/u0a77 (adj 15): empty #21
,08-31 08:52:11.925  1017  1366 I ActivityManager: Killing 7057:com.google.android.talk/u0a102 (adj 15): empty #21
,08-31 08:52:11.945  1017  1569 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-31 08:52:11.945  1017  1569 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-31 08:52:11.945  1017  1569 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:11.945  1017  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:11.945  1017  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-31 08:52:11.955  7890  7890 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
,08-31 08:52:11.955  7890  7890 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:11.955  7890  7890 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:52:11.955  7890  7890 D AndroidRuntime: Shutting down, VM
08-31 08:52:11.955  1017  1448 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-31 08:52:11.955  1017  1448 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-31 08:52:11.955  7890  7890 E AndroidRuntime: FATAL EXCEPTION: main
08-31 08:52:11.955  7890  7890 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 7890
08-31 08:52:11.955  7890  7890 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.databas,e.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-31 08:52:11.955  7890  7890 E AndroidRuntime: 	... 11 more
08-31 08:52:11.955  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
08-31 08:52:11.955  1017  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 08:52:11.955  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-31 08:52:11.965  7881  7881 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-31 08:52:11.965  7913  7913 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 08:52:11.965  7913  7913 D ActivityThread: Added TimaKeyStore provider
08-31 08:52:11.975  1017  1478 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
08-31 08:52:11.975  1017  1029 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-31 08:52:11.975  1017  1029 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
08-31 08:52:11.975  1017  4351 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-31 08:52:11.985  1017  4351 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.985  1017  4351 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.985  1017  4351 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.985  1017  4351 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:11.985  7465  7465 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-31 08:52:11.995  7930  7930 E Zygote  : MountEmulatedStorage()
08-31 08:52:11.995  7930  7930 E Zygote  : v2
08-31 08:52:11.995  7930  7930 I libpersona: KNOX_SDCARD checking this for 10087
08-31 08:52:11.995  7930  7930 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:11.995  7465  7465 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,08-31 08:52:11.995  1017  4351 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7930 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a,
,08-31 08:52:12.005  1017  1100 I ActivityManager: Killing 7291:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-31 08:52:12.015  7930  7930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:12.015  7465  7465 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:12.015  7465  7465 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 08:52:12.015  7465  7465 D AndroidRuntime: Shutting down VM
08-31 08:52:12.015  7465  7465 E AndroidRuntime: FATAL EXCEPTION: main
08-31 08:52:12.015  7465  7465 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 7465
08-31 08:52:12.015  7465  7465 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206),
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145),
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 08:52:12.015  7465  7465 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 08:52:12.015  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-31 08:52:12.015  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:12.015  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:12.015  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 08:52:12.015  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 08:52:12.025  7930  7930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 08:52:12.025  7930  7930 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-31 08:52:12.025  1017  7929 E DropBoxManagerService: Can't write: system_app_crash,
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop198.tmp: open failed: EROFS (Read-only file system)
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: ,	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 08:52:12.025  1017  7929 E DropBoxManagerService: 	... 5 more
,08-31 08:52:12.035  7939  7939 E Zygote  : MountEmulatedStorage()
08-31 08:52:12.035  7939  7939 E Zygote  : v2
08-31 08:52:12.035  7939  7939 I libpersona: KNOX_SDCARD checking this for 10152
08-31 08:52:12.035  7939  7939 I libpersona: KNOX_SDCARD not a persona
,08-31 08:52:12.035  7939  7939 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 08:52:12.035  7939  7939 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051

```
