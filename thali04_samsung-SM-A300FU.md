#### Test 82728424ebd9a7c_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
08-25 17:38:51.102   288   288 E SMD     : DCD OFF
,08-25 17:38:52.002  6758  6758 D AndroidRuntime: 
08-25 17:38:52.002  6758  6758 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 17:38:52.012  6758  6758 D AndroidRuntime: CheckJNI is OFF
08-25 17:38:52.012  6758  6758 D AndroidRuntime: readGMSProperty: start
08-25 17:38:52.012  6758  6758 D AndroidRuntime: readGMSProperty: already setted!!
08-25 17:38:52.012  6758  6758 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-25 17:38:52.012  6758  6758 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-25 17:38:52.012  6758  6758 D AndroidRuntime: readGMSProperty: end
08-25 17:38:52.012  6758  6758 D AndroidRuntime: addProductProperty: start
08-25 17:38:52.152  6758  6758 E AffinityControl: AffinityControl: registerfunction enter
08-25 17:38:52.182  6758  6758 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-25 17:38:52.192  1017  1029 E PersonaManagerService: inState():  stateMachine is null !!
08-25 17:38:52.192  1017  1029 I PersonaManagerService: PersonaId don't exist
08-25 17:38:52.192  1017  1029 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-25 17:38:52.202  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-25 17:38:52.212  1017  1029 W ActivityManager: mDVFSHelper.acquire()
08-25 17:38:52.222   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-25 17:38:52.222   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-25 17:38:52.232  1017  1029 D FocusedStackFrame: Set to : 0
08-25 17:38:52.232  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:38:52.232  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:38:52.232  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:38:52.232  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:38:52.232  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-25 17:38:52.232  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-25 17:38:52.252  6770  6770 E Zygote  : MountEmulatedStorage()
08-25 17:38:52.252  6770  6770 E Zygote  : v2
08-25 17:38:52.252  6770  6770 I libpersona: KNOX_SDCARD checking this for 10171
08-25 17:38:52.252  6770  6770 I libpersona: KNOX_SDCARD not a persona
08-25 17:38:52.252  6770  6770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 17:38:52.252  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-25 17:38:52.252  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-25 17:38:52.252  6770  6770 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:38:52.252   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-25 17:38:52.252  6770  6770 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-25 17:38:52.262  1017  1029 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6770 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 17:38:52.262  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-25 17:38:52.262  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 17:38:52.262  1017  1029 D InputDispatcher: Focused application set to: xxxx
08-25 17:38:52.262  1017  1029 D InputDispatcher: Focus left window: 1482
08-25 17:38:52.262  6758  6758 D AndroidRuntime: Shutting down VM
08-25 17:38:52.262  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 17:38:52.262  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-25 17:38:52.282  6770  6770 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 17:38:52.282  6770  6770 D ActivityThread: Added TimaKeyStore provider
08-25 17:38:52.282  1017  1327 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-25 17:38:52.282  1017  1017 V ActivityManager: Display changed displayId=0
08-25 17:38:52.292  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-25 17:38:52.312  1017  1327 D PersonaManager: isKioskContainerExistOnDevice
08-25 17:38:52.322  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-25 17:38:52.342   258  1097 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-25 17:38:52.342  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{210cdb7 token=android.os.BinderProxy@1c142679 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-25 17:38:52.342   258   455 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-25 17:38:52.342  1482  1482 D Launcher: onTrimMemory. Level: 20
08-25 17:38:52.402  1017  1324 E Watchdog: !@Sync 3
08-25 17:38:52.422  6770  6770 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-25 17:38:52.442  6770  6770 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 8334-8336)
08-25 17:38:52.442  6770  6770 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-25 17:38:52.472  6758  6758 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-25 17:38:52.482  6770  6770 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b691ce8}
08-25 17:38:52.482  6770  6770 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-25 17:38:52.492  6770  6770 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 17:38:52.532  6770  6770 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-25 17:38:52.532  6770  6770 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 17:38:52.532  6770  6770 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 17:38:52.572  6770  6770 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 17:38:52.572  6770  6770 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 17:38:52.572  6770  6770 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 17:38:52.572  6770  6770 I Adreno-EGL: Local Branch: 
08-25 17:38:52.572  6770  6770 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 17:38:52.572  6770  6770 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 17:38:52.572  6770  6770 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 17:38:52.662  6770  6770 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 17:38:52.682  6770  6770 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-25 17:38:52.682  6770  6770 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-25 17:38:52.692  6770  6770 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-25 17:38:52.692  6770  6770 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-25 17:38:52.802  6770  6770 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 17:38:52.822  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{37eb7145 u0 com.test.thalitest/.MainActivity t2}
,08-25 17:38:52.822  6770  6770 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 17:38:52.832  6770  6770 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-25 17:38:52.832  6770  6770 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-25 17:38:52.832  6770  6770 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-25 17:38:52.842  6770  6770 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 17:38:52.842  6770  6770 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 17:38:52.972  6770  6810 D OpenGLRenderer: Render dirty regions requested: true,
,08-25 17:38:52.972  1017  1463 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-25 17:38:52.972  1017  1463 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 17:38:52.972  1017  1463 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-25 17:38:52.982  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 17:38:52.982  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-25 17:38:52.982  6770  6797 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-25 17:38:52.982  6770  6770 V ActivityThread: updateVisibility : ActivityRecord{34152f48 token=android.os.BinderProxy@2efc465 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-25 17:38:52.992  6770  6770 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-25 17:38:52.992  6770  6770 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-25 17:38:53.002   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-25 17:38:53.022  1017  1497 D InputDispatcher: Focus entered window: 6770
,08-25 17:38:53.032  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-25 17:38:53.032  6770  6770 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-25 17:38:53.032  6770  6810 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 17:38:53.032  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 17:38:53.032  6770  6810 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-25 17:38:53.032  6770  6810 D OpenGLRenderer: Enabling debug mode 0
,08-25 17:38:53.062  1017  1456 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-25 17:38:53.072  1179  1179 I StatusBar: Icon Only
,08-25 17:38:53.072  1179  1179 D PanelView: There is/are notification(s) 
,08-25 17:38:53.072  1017  6816 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 17:38:53.082  1017  1047 I ActivityManager: Displayed Component not be shown by security: +766ms (total +850ms)
,08-25 17:38:53.082  1017  1047 W ActivityManager: mDVFSHelper.release()
08-25 17:38:53.082  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{37eb7145 u0 com.test.thalitest/.MainActivity t2} time:108976
,08-25 17:38:53.092   258  6024 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-25 17:38:53.092   258   455 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-25 17:38:53.092  6770  6770 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-25 17:38:53.092  6770  6770 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2efc465 time:108986
,08-25 17:38:53.102  1873  1873 I SamsungIME: getCurrentCandidateView
,08-25 17:38:53.122  6770  6770 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6770
,08-25 17:38:53.132   314   314 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-25 17:38:53.132   314   314 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-25 17:38:53.202  1873  1873 D SamsungIME: Dismiss ExpandCandiate
,08-25 17:38:53.312  6770  6770 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 17:38:53.352  1873  1873 I SamsungIME: getDebugLevel  : 0x4f4c
,08-25 17:38:53.392  6770  6814 D jxcore_app_log: JniHelper::setJavaVM(0xb80a52b0), pthread_self() = -1201472504
,08-25 17:38:53.392  1873  1873 I SamsungIME: getDebugLevel  : 0x4f4c
,08-25 17:38:53.402  6770  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 17:38:53.402  6770  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 17:38:53.402  6770  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 17:38:53.402  6770  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 17:38:53.402  6770  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 17:38:53.402  6770  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b6d34de added. We now have 1 listener(s)
,08-25 17:38:53.402  1873  1873 I SamsungIME: KeybaordView init() : load resources
,08-25 17:38:53.412  6770  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-25 17:38:53.412  6770  6814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 17:38:53.412  6770  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 17:38:53.412  6770  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 17:38:53.422  6770  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e7390d5 added. We now have 1 listener(s)
,08-25 17:38:53.422  6770  6814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:38:53.422  6770  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:38:53.422  6770  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 17:38:53.422  6770  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-25 17:38:53.422  6770  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 17:38:53.422  6770  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 17:38:53.432  6770  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:38:53.432  6770  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-25 17:38:53.442  1873  1873 I SamsungIME: getCurrentKeyboard
08-25 17:38:53.442  1873  1873 I SamsungIME: getTextKeyboard
08-25 17:38:53.442  6770  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-25 17:38:53.442  6770  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:38:53.442  6770  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:38:53.442  6770  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:38:53.442  6770  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:38:53.442  6770  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:38:53.442  6770  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:38:53.442  6770  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:38:53.442  6770  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:38:53.442  6770  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-25 17:38:53.442  6770  6814 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:38:53.442  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:38:53.452  6770  6814 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 17:38:53.452  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:38:53.462  1873  1873 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-25 17:38:53.482  6770  6770 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 17:38:54.012  6770  6823 W jxcore-log: Initializing JXcore engine
08-25 17:38:54.012  6770  6823 W jxcore-log: JXcore engine is ready
,08-25 17:38:54.062  2020  2020 E audit   : type=1400 msg=audit(1472139534.062:205): avc:  denied  { ioctl } for  pid=6823 comm="Thread-1250" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-25 17:38:54.062  2020  2020 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:38:54.062  2020  2020 E audit   : type=1300 msg=audit(1472139534.062:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e3fb8f8 items=0 ppid=303 ppcomm=main pid=6823 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1250" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-25 17:38:54.062  2020  2020 E audit   : type=1320 msg=audit(1472139534.062:205): 
,08-25 17:38:54.072  6770  6823 W jxcore-log: Starting JXcore engine
,08-25 17:38:54.102   288   288 E SMD     : DCD OFF
,08-25 17:38:54.182  6770  6823 W jxcore-log: Platform android
08-25 17:38:54.182  6770  6823 W jxcore-log: 
08-25 17:38:54.182  6770  6823 W jxcore-log: Process ARCH arm
08-25 17:38:54.182  6770  6823 W jxcore-log: 
,08-25 17:38:54.392  6770  6823 I jxcore-log: JXcore Cordova bridge is ready!
08-25 17:38:54.392  6770  6823 I jxcore-log: 
,08-25 17:38:54.392  6770  6823 W jxcore-log: JXcore engine is started
,08-25 17:38:54.392  6770  6814 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 17:38:54.392  6770  6770 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 17:38:57.102   288   288 E SMD     : DCD OFF,
,08-25 17:38:57.742  1017  1049 I PowerManagerService: [PWL] Off : 50s ago
,08-25 17:38:57.862  1017  3362 D SSRM:n  : SIOP:: AP = 340
,08-25 17:38:58.132   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 17:38:59.132   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 17:38:59.992  1017  1095 V AlarmManager: waitForAlarm result :8
,08-25 17:39:00.102   288   288 E SMD     : DCD OFF
,08-25 17:39:00.132   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 17:39:00.312  1017  4787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 17:39:00.312  1017  4787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 17:39:00.312  1017  4787 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 17:39:00.312  1017  4787 D BatteryService: stay LED for fully charged
08-25 17:39:00.312  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-25 17:39:00.322  1017  1017 I MotionRecognitionService: Plugged
08-25 17:39:00.322  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-25 17:39:00.322  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-25 17:39:00.322  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-25 17:39:00.322  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-25 17:39:00.332  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 17:39:00.342  3158  3158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 17:39:00.342  3158  3265 D HeadsetStateMachine: Disconnected process message: 10
,08-25 17:39:00.352  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-25 17:39:00.352  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-25 17:39:00.352  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 17:39:00.352  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 17:39:00.352  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 17:39:00.632  5677  5677 D FactoryTest: Not factory mode
,08-25 17:39:00.632  5677  5677 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-25 17:39:00.632  5677  5677 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-25 17:39:00.632  5677  5677 D MTPRx   : still no open session command from host, so toast
,08-25 17:39:00.642  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-25 17:39:00.642  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-25 17:39:00.642  5677  5677 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116533
,08-25 17:39:00.642  1017  1497 E PersonaManagerService: inState():  stateMachine is null !!
,08-25 17:39:00.642  1017  1497 I PersonaManagerService: PersonaId don't exist
08-25 17:39:00.642  1017  1497 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-25 17:39:00.642  1017  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-25 17:39:00.652  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:00.652  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:00.652  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-25 17:39:00.652  1017  1497 W ActivityManager: mDVFSHelper.acquire()
,08-25 17:39:00.672  1017  1497 D PersonaManager: isKioskContainerExistOnDevice
,08-25 17:39:00.672  1017  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 17:39:00.672  1017  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-25 17:39:00.672  1017  1497 D InputDispatcher: Focused application set to: xxxx
08-25 17:39:00.672  1017  1497 D InputDispatcher: Focus left window: 6770
,08-25 17:39:00.672  5677  5677 E MTPRx   : started activity for popup
,08-25 17:39:00.692  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-25 17:39:00.692  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 17:39:00.712  5677  5677 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-25 17:39:00.712  5677  5677 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-25 17:39:00.712  5677  5677 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-25 17:39:00.712  5677  5677 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:39:00.712  5677  5677 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 17:39:00.712  5677  5677 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 17:39:00.732  5677  5677 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-25 17:39:00.742  1017  4787 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-25 17:39:00.742  1017  4787 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-25 17:39:00.742  1017  4787 D InputDispatcher: Focused application set to: xxxx
,08-25 17:39:00.742  1017  4787 D InputDispatcher: Focus entered window: 6770
,08-25 17:39:00.742  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-25 17:39:00.742  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 17:39:00.742  1017  1480 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-25 17:39:00.752  1017  1480 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@b43e24c attribute=null, token = android.os.BinderProxy@2d0fba1c
,08-25 17:39:00.792  5677  5677 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-25 17:39:00.802  5677  5677 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-25 17:39:00.802  5677  5677 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-25 17:39:00.822  6770  6770 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 17:39:00.822  6770  6770 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-25 17:39:00.822  6770  6770 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 17:39:00.822  6770  6770 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-25 17:39:00.822  1017  1456 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-25 17:39:00.822  1017  1456 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 17:39:00.822  1017  1456 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-25 17:39:00.822  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 17:39:00.822  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-25 17:39:00.842  6770  6770 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 17:39:00.842  6770  6770 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 17:39:00.842  6770  6770 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3e71da71 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1a35d37e, 16908290=android.view.AbsSavedState$1@1a35d37e}, android:focusedViewId=100}]}]
,08-25 17:39:00.842  6770  6770 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-25 17:39:00.842  6770  6770 V ActivityThread: updateVisibility : ActivityRecord{34152f48 token=android.os.BinderProxy@2efc465 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-25 17:39:00.842  6770  6770 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 17:39:00.842  6770  6770 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-25 17:39:00.842  6770  6770 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2efc465 time:116737
,08-25 17:39:00.852  1017  4786 D PersonaManager: isKioskContainerExistOnDevice
,08-25 17:39:01.132   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 17:39:02.132   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 17:39:02.282  1017  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-25 17:39:03.102   288   288 E SMD     : DCD OFF
,08-25 17:39:03.132   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-25 17:39:03.652  1017  1042 W ActivityManager: mDVFSHelper.release()
,08-25 17:39:04.112  1017  1095 V AlarmManager: waitForAlarm result :4
,08-25 17:39:04.132  1017  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-25 17:39:04.142  1017  1017 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
08-25 17:39:04.142  1017  1017 V AlarmManagerEXT: <AppSync3 Whitelist>
08-25 17:39:04.142  1017  1017 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-25 17:39:04.142  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-25 17:39:04.142  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 17:39:04.152  1993  1993 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-25 17:39:04.162  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-25 17:39:04.162  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,08-25 17:39:04.162  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 17:39:04.172  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-25 17:39:04.172  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,08-25 17:39:04.172  1179  1179 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-25 17:39:04.192  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 17:39:04.192  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 17:39:04.202  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 17:39:04.202  1017  4790 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:04.212  1017  4790 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-25 17:39:04.212  1017  4790 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:04.212  1017  4790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:04.212  1017  4790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:04.232  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 17:39:04.282  4732  4732 D ConnectivityManager: CallingUid : 10011, CallingPid : 4732
,08-25 17:39:04.292  1017  1481 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-25 17:39:04.292  1017  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-25 17:39:04.292  1017  1129 D ConnectivityService: apparently satisfied.  currentScore=60
,08-25 17:39:04.292  1017  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-25 17:39:04.292  4732  6833 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 17:39:04.342  4732  6834 W DriveInitializer: Background init thread started
,08-25 17:39:04.382   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-25 17:39:04.382   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 17:39:04.382  4732  6834 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-25 17:39:04.422  1993  1993 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-25 17:39:04.462  4732  6834 W DriveInitializer: Background init thread ended
,08-25 17:39:04.572  1017  1463 I art     : Explicit concurrent mark sweep GC freed 34302(1902KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.512ms total 152.247ms
,08-25 17:39:04.612  1017  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:04.612  1017  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-25 17:39:04.612  1017  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:04.612  1017  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:04.622  1017  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:04.632  1017  1481 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-25 17:39:04.632  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-25 17:39:04.652  1017  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:04.652  1017  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-25 17:39:04.652  1017  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:04.652  1017  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:04.652  1017  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:04.672  4732  6842 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-25 17:39:04.672  4732  6842 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-25 17:39:04.712  1993  1993 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 17:39:04.732  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:04.732  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:04.732  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:04.842  1017  1327 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:04.842  1017  1327 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-25 17:39:04.842  1017  1327 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:04.842  1017  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:04.842  1017  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:04.872  1017  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:04.872  1017  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-25 17:39:04.872  1017  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:04.872  1017  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:04.872  1017  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:04.922  1017  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:04.932  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:04.932  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:04.932  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:04.972  1017  1463 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:04.972  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:04.972  1017  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:04.972  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:05.032  1993  2007 I art     : Explicit concurrent mark sweep GC freed 72565(4MB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 10MB/17MB, paused 1.233ms total 74.408ms
,08-25 17:39:05.082  1017  1248 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:05.092  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:05.092  1017  1248 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:05.092  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:05.092  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:05.092  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:05.092  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:05.092  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:05.102  6847  6847 E Zygote  : MountEmulatedStorage(),
08-25 17:39:05.102  6847  6847 E Zygote  : v2
,08-25 17:39:05.102  6847  6847 I libpersona: KNOX_SDCARD checking this for 10011
08-25 17:39:05.102  6847  6847 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:05.112  1017  1248 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6847 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-25 17:39:05.112  6847  6847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:05.112  6847  6847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 17:39:05.112  6847  6847 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 17:39:05.152  6847  6847 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:05.152  6847  6847 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:05.192  6847  6847 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-25 17:39:05.192  6847  6847 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 17:39:05.232  6847  6847 I MultiDex: VM with version 2.1.0 has multidex support
08-25 17:39:05.232  6847  6847 I MultiDex: install
08-25 17:39:05.232  6847  6847 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 17:39:05.262  6847  6847 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-25 17:39:05.322  6847  6847 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fd4624: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-25 17:39:05.322  6847  6847 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-25 17:39:05.322  6847  6847 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-25 17:39:05.332  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-25 17:39:05.332  1017  4787 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:05.342  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:05.342  1017  4787 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:05.342  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:05.342  6847  6847 D ChimeraCfgMgr: Reading stored module config
,08-25 17:39:05.352  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:05.352  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:05.352  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:05.352  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:05.402  1017  4789 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-25 17:39:05.412  1017  4789 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-25 17:39:05.412  1993  1993 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=920acf36-cf4f-4852-9b62-444b39bed7c6
08-25 17:39:05.412  1017  4789 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:05.412  1017  4789 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:05.412  1017  4789 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:05.422  6847  6861 I art     : Background sticky concurrent mark sweep GC freed 21447(1038KB) AllocSpace objects, 2(32KB) LOS objects, 1% free, 7MB/7MB, paused 19.024ms total 65.818ms
,08-25 17:39:05.432  1993  1993 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 17:39:05.432  1993  1993 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 17:39:05.462  6847  6847 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-25 17:39:05.462  6847  6847 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-25 17:39:05.472  1017  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:05.472  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:05.472  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:05.472  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:05.482  6847  6861 W art     : Suspending all threads took: 17.375ms
,08-25 17:39:05.492  6847  6861 I art     : Background partial concurrent mark sweep GC freed 1374(159KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 7MB/12MB, paused 20.127ms total 53.569ms
,08-25 17:39:05.512  6847  6867 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-25 17:39:05.542   283   709 D WVCdm   : Instantiating CDM.
,08-25 17:39:05.542   283   283 I WVCdm   : CdmEngine::OpenSession
,08-25 17:39:05.542   283   283 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-25 17:39:05.552  4327  4386 I art     : Explicit concurrent mark sweep GC freed 1403(47KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 665us total 22.386ms
,08-25 17:39:05.572   283   283 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-25 17:39:05.602   283   283 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-25 17:39:05.652   283   283 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-25 17:39:05.662   283  1538 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-25 17:39:05.662   283  1538 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,08-25 17:39:05.662   283  1538 I WVCdm   : CdmEngine::GenerateKeyRequest
08-25 17:39:05.662  6847  6855 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-25 17:39:05.662  6847  6855 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-25 17:39:05.662  6847  6855 I System.out: (HTTPLog)-Static: isShipBuild true
08-25 17:39:05.662  6847  6855 I System.out: (HTTPLog)-Thread-1224-947733697: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-25 17:39:05.662  6847  6855 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 17:39:05.672   278   983 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 17:39:05.672   278   983 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 17:39:05.672   283  1538 D WVCdm   : PrepareKeyRequest: nonce=4096065381
,08-25 17:39:05.712  1993  2148 W GCoreFlp: No location to return for getLastLocation()
,08-25 17:39:05.722  6847  6855 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 17:39:05.722  6847  6855 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6847, getuid(): 10011
,08-25 17:39:05.742  1017  1761 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:05.742  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:05.742  1017  1761 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:05.742  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:05.752  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:05.752  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:05.752  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:05.752  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-25 17:39:05.772  1017  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-25 17:39:05.772  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:05.772  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:05.772  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-25 17:39:05.782  4732  6843 D UdcContextInitService: registered all accounts: true
,08-25 17:39:05.802  1993  2151 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 17:39:05.832  1993  2170 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-25 17:39:05.972  6847  6855 I qtaguid : Untagging socket 30
,08-25 17:39:06.022  1017  1463 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-25 17:39:06.022  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-25 17:39:06.022  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:06.022  1017  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 17:39:06.022  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:06.102   288   288 E SMD     : DCD OFF
,08-25 17:39:06.312  6877  6877 I dex2oat : ----------------------------------------------------
08-25 17:39:06.312  6877  6877 I dex2oat : <SS>: S T A R T I N G . . .
08-25 17:39:06.312  6877  6877 I dex2oat : <SS>: Zip is absent. Canceled.
08-25 17:39:06.312  6877  6877 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-25 17:39:06.372  6877  6877 I dex2oat : dex2oat took 58.626ms (threads: 4)
,08-25 17:39:06.382  6847  6855 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 17:39:06.382  6847  6855 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 17:39:06.382  6847  6855 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 17:39:06.382  6847  6855 I Adreno-EGL: Local Branch: 
08-25 17:39:06.382  6847  6855 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 17:39:06.382  6847  6855 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 17:39:06.382  6847  6855 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 17:39:06.792  6847  6855 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 17:39:06.792  6847  6855 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 17:39:06.792  6847  6855 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 17:39:06.792  6847  6855 I Adreno-EGL: Local Branch: 
08-25 17:39:06.792  6847  6855 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 17:39:06.792  6847  6855 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 17:39:06.792  6847  6855 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 17:39:06.802  1017  3397 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 17:39:06.842  6847  6855 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 17:39:06.842  6847  6855 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 17:39:06.842  6847  6855 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 17:39:06.842  6847  6855 I Adreno-EGL: Local Branch: 
08-25 17:39:06.842  6847  6855 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 17:39:06.842  6847  6855 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 17:39:06.842  6847  6855 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 17:39:06.952  1017  1497 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-25 17:39:06.952  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-25 17:39:06.952  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:06.952  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:06.952  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:06.982  1993  6845 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-25 17:39:06.982  1993  6845 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 17:39:06.982  1993  6845 I System.out: (HTTPLog)-Static: isShipBuild true
,08-25 17:39:06.982  1993  6845 I System.out: (HTTPLog)-Thread-265-827503362: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-25 17:39:06.982  1993  6845 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 17:39:06.992   278   983 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 17:39:06.992   278   983 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 17:39:06.992  1993  6845 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 17:39:06.992  1993  6845 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1993, getuid(): 10011
,08-25 17:39:07.032  1993  6845 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1993, getuid(): 10011
,08-25 17:39:07.172  1993  2170 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-25 17:39:07.172  1993  2170 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-25 17:39:07.202  1993  2170 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-25 17:39:05.922+0200, stopTime=2016-08-25 17:39:07.207+0200, duration=1285ms
,08-25 17:39:07.202  1993  6886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 17:39:07.212   278   983 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 17:39:07.212   278   983 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 17:39:07.212  1993  6886 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-25 17:39:07.212  1993  6886 I qtaguid : Tagging socket 65 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1993, getuid(): 10011
,08-25 17:39:07.232   283   709 I WVCdm   : CdmEngine::CloseSession
,08-25 17:39:07.232   283   709 I WVCdm   : L3 Terminate.
,08-25 17:39:07.242  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 17:39:07.242  6770  6823 I jxcore-log: 
,08-25 17:39:07.242  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 17:39:07.242  6770  6823 I jxcore-log: 
,08-25 17:39:07.252  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:07.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:07.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:07.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:07.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:07.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:07.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:07.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:07.252  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:07.252  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 17:39:07.252  6770  6823 I jxcore-log: 
08-25 17:39:07.252  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 17:39:07.252  6770  6823 I jxcore-log: 
08-25 17:39:07.252  1993  6886 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1993, getuid(): 10011
08-25 17:39:07.262  1017  4789 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-25 17:39:07.492  1993  6886 I qtaguid : Untagging socket 65,
,08-25 17:39:07.522  1017  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:07.522  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-25 17:39:07.522  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:07.522  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:07.522  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:07.552  1993  2170 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-25 17:39:07.662  1993  6893 I art     : Explicit concurrent mark sweep GC freed 43508(2MB) AllocSpace objects, 12(500KB) LOS objects, 40% free, 11MB/19MB, paused 1.460ms total 67.816ms
,08-25 17:39:07.682  1017  4787 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:07.682  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:07.682  1017  4787 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:07.682  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:07.702  1017  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:07.712  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:07.712  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:07.712  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:07.752  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:07.752  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:07.752  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:07.752  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:07.752  1993  6895 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-25 17:39:07.752  1993  6893 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-25 17:39:07.752  1017  4790 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:07.752  1017  4790 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:07.752  1017  4790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:07.752  1017  4790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:07.782  1017  1463 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:07.782  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:07.782  1017  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:07.782  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:07.782  1993  6895 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-25 17:39:07.782  1993  6893 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-25 17:39:07.782  1017  1327 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:07.782  1017  1327 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:07.782  1017  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:07.782  1017  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:07.812  1017  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:07.812  1017  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:07.812  1017  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:07.812  1017  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:07.812  1993  6895 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-25 17:39:07.812  1993  6893 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-25 17:39:07.812  1993  6893 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-25 17:39:07.832  1993  6893 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-25 17:39:07.882  1017  1761 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-25 17:39:07.882  1017  3362 D SSRM:n  : SIOP:: AP = 370
,08-25 17:39:07.922  1993  6893 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 17:39:07.922   278   983 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 17:39:07.922   278   983 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 17:39:07.922  1993  6893 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 17:39:07.922  1993  6893 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1993, getuid(): 10011
,08-25 17:39:07.962  1993  6893 I qtaguid : Tagging socket 80 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1993, getuid(): 10011
,08-25 17:39:07.982  6770  6823 D executeNativeTests: Running unit tests
,08-25 17:39:08.072  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:08.072  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf added. We now have 2 listener(s)
,08-25 17:39:08.072  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 17:39:08.072  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:08.072  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:08.072  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:08.072  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c added. We now have 2 listener(s)
08-25 17:39:08.072  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:08.072  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:39:08.072  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:08.082  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:08.082  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:08.082  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:08.082  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:08.082  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:08.082  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:08.082  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:08.082  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:39:08.082  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:08.082  6770  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:39:08.082  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:08.082  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 17:39:08.082  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 17:39:08.082  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 17:39:08.082  6770  6823 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 17:39:08.082  6770  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 17:39:08.082  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 17:39:08.082  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:39:08.082  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:39:08.082  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.092  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.092  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.092  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.092  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.092  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:08.092  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:08.092  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf removed from the list
08-25 17:39:08.092  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.092  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c removed from the list
08-25 17:39:08.092  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:08.092  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.092  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.092  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.092  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.092  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.092  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.092  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.092  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.092  6770  6823 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 17:39:08.092  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.092  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.102  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.102  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.102  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.102  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.102  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.102  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.102  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.102  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.102  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.102  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.102  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.102  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 17:39:08.102  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 17:39:08.102  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<,no peer name> 37:2710:2710:2710:2710:2710]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 17:39:08.112  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.112  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.112  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.112  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.112  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.112  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.112  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.112  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.112  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.112  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.112  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.112  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.112  6770  6823 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 17:39:08.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:08.112  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:08.112  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:08.112  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:08.112  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:08.112  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:08.112  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:08.112  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:08.112  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:39:08.112  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:08.112  6770  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:39:08.112  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:08.112  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:39:08.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:39:08.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:08.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:39:08.122  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:08.122  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 17:39:08.122  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:08.132  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 17:39:08.132  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 17:39:08.132   314   314 I ServiceManager: Waiting for service AtCmdFwd...
08-25 17:39:08.132  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-25 17:39:08.142  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-25 17:39:08.142  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 17:39:08.142  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:39:08.142  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:39:08.152  3158  3367 D BtGatt.GattService: registerClient() - UUID=f01b3c81-a872-49ac-913b-edcc6f7b546f
,08-25 17:39:08.192  3158  3255 D BtGatt.GattService: onClientRegistered() - UUID=f01b3c81-a872-49ac-913b-edcc6f7b546f, clientIf=6
,08-25 17:39:08.202  6770  6780 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 17:39:08.202  3158  3171 D BtGatt.GattService: start scan with filters
,08-25 17:39:08.202  3158  3262 D BtGatt.ScanManager: handling starting scan
08-25 17:39:08.202  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 17:39:08.202  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:39:08.202  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:39:08.202  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:39:08.202  3158  3262 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:08.202  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:08.212  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 17:39:08.212  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,08-25 17:39:08.212  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:39:08.212  3158  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 17:39:08.212  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.212  3158  3262 D BtGatt.ScanManager: allow scan with filters
08-25 17:39:08.212  3158  3262 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-25 17:39:08.212  3158  3262 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-25 17:39:08.222  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 17:39:08.222  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.222  3158  3262 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:39:08.222  3158  3262 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 17:39:08.222  3158  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 17:39:08.222  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.222  6770  6823 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 17:39:08.222  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 17:39:08.222  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.232  1017  1456 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-25 17:39:08.232  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.232  6770  6823 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 17:39:08.232  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.232  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 17:39:08.232  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.232  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:39:08.232  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 17:39:08.232  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:39:08.232  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:08.232  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 17:39:08.232  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:39:08.232  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 17:39:08.232  3158  3174 D BtGatt.GattService: stopScan() - queue size =1
,08-25 17:39:08.232  3158  3262 D BtGatt.ScanManager: filter size is 1
,08-25 17:39:08.242  3158  3262 D BtGatt.ScanManager: delete FilterIndex - 3
,08-25 17:39:08.242  3158  3171 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 17:39:08.242  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 17:39:08.242  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:08.242  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:39:08.242  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:39:08.242  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:39:08.242  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:39:08.242  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:39:08.242  3158  3262 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:39:08.242  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:08.242  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 17:39:08.242  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:39:08.242  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 17:39:08.242  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:08.242  1993  6893 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 17:39:08.242  1993  6893 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1993, getuid(): 10011
,08-25 17:39:08.242  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 17:39:08.242  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.242  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.242  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.242  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:08.242  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.242  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.242  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.242  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.242  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.242  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:08.242  6770  6823 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 17:39:08.242  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:08.242  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:08.242  3158  3262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 17:39:08.252  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:08.252  3158  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-25 17:39:08.252  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.252  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:08.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:08.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:08.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:08.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:08.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:08.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:08.252  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:08.252  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:08.252  6770  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:39:08.252  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:08.252  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:39:08.252  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:39:08.252  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:08.252  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 17:39:08.262  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:08.262  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:39:08.262  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:08.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:39:08.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:39:08.272  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:39:08.272  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 17:39:08.272  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:39:08.272  3158  3171 D BtGatt.GattService: registerClient() - UUID=ac1cbfdc-52da-4621-9018-d2fd3af916eb
,08-25 17:39:08.312  3158  3255 D BtGatt.GattService: onClientRegistered() - UUID=ac1cbfdc-52da-4621-9018-d2fd3af916eb, clientIf=6
,08-25 17:39:08.312  6770  6780 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 17:39:08.312  3158  3367 D BtGatt.GattService: start scan with filters
,08-25 17:39:08.322  3158  3262 D BtGatt.ScanManager: handling starting scan,
08-25 17:39:08.322  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 17:39:08.322  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-25 17:39:08.322  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:39:08.322  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:39:08.322  3158  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 17:39:08.322  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:08.322  3158  3262 D BtGatt.ScanManager: allow scan with filters
08-25 17:39:08.322  3158  3262 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 17:39:08.322  3158  3262 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-25 17:39:08.322  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 17:39:08.322  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:08.322  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:39:08.322  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 17:39:08.322  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:39:08.322  3158  3262 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 17:39:08.322  3158  3262 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 17:39:08.332  3158  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 17:39:08.332  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.332  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:39:08.332  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 17:39:08.332  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.342  6770  6823 I io.jxcore.node.ConnectionHelper: start: OK,
08-25 17:39:08.342  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.342  6770  6823 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 17:39:08.342  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.342  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 17:39:08.342  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.342  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:39:08.342  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 17:39:08.342  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:39:08.342  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:08.342  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:39:08.342  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:39:08.342  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 17:39:08.342  3158  3171 D BtGatt.GattService: stopScan() - queue size =1
08-25 17:39:08.342  3158  3262 D BtGatt.ScanManager: filter size is 1
,08-25 17:39:08.342  3158  3262 D BtGatt.ScanManager: delete FilterIndex - 4
08-25 17:39:08.352  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 17:39:08.352  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:08.352  3158  3262 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:39:08.352  3158  3367 D BtGatt.GattService: unregisterClient() - clientIf=6
08-25 17:39:08.352  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 17:39:08.352  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:39:08.352  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:39:08.352  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:39:08.352  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-25 17:39:08.352  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:08.352  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 17:39:08.352  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:08.352  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:39:08.352  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 17:39:08.352  3158  3262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-25 17:39:08.352  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:39:08.352  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:08.352  3158  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-25 17:39:08.352  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.352  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:08.352  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.352  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.352  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:08.352  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.352  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.352  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.352  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.352  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.362  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:08.362  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:08.362  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.362  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.362  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.362  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:39:08.362  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.362  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
,08-25 17:39:08.362  6770  6823 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 17:39:08.362  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:08.372  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:08.372  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:08.372  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:08.372  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:08.372  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:08.372  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:08.372  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:08.372  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:08.372  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:08.372  6770  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:39:08.372  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:08.372  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:39:08.372  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:39:08.372  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:08.372  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 17:39:08.372  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:08.372  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:39:08.372  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:08.382  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:39:08.382  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:39:08.382  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:39:08.382  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 17:39:08.382  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:39:08.392  3158  3174 D BtGatt.GattService: registerClient() - UUID=7ae6dc27-c91a-4e90-8219-7ef786dced97
,08-25 17:39:08.412  1017  1029 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-25 17:39:08.422  1993  6893 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 17:39:08.422  1993  6893 I qtaguid : Tagging socket 77 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1993, getuid(): 10011
,08-25 17:39:08.432  3158  3255 D BtGatt.GattService: onClientRegistered() - UUID=7ae6dc27-c91a-4e90-8219-7ef786dced97, clientIf=6
,08-25 17:39:08.432  6770  6780 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 17:39:08.432  3158  3368 D BtGatt.GattService: start scan with filters
,08-25 17:39:08.432  3158  3262 D BtGatt.ScanManager: handling starting scan
,08-25 17:39:08.432  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:39:08.432  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 17:39:08.432  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:39:08.432  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:39:08.442  3158  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-25 17:39:08.442  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.442  3158  3262 D BtGatt.ScanManager: allow scan with filters
,08-25 17:39:08.442  3158  3262 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-25 17:39:08.442  3158  3262 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-25 17:39:08.442  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 17:39:08.442  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.442  3158  3262 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 17:39:08.442  3158  3262 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 17:39:08.452  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:39:08.452  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 17:39:08.452  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:08.452  3158  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 17:39:08.452  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.452  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:39:08.452  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 17:39:08.452  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.462  6770  6823 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 17:39:08.462  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.462  6770  6823 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 17:39:08.462  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.462  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 17:39:08.462  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.462  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:39:08.462  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 17:39:08.462  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:39:08.462  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:08.462  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:39:08.462  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:39:08.462  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 17:39:08.462  3158  3174 D BtGatt.GattService: stopScan() - queue size =1
,08-25 17:39:08.462  3158  3262 D BtGatt.ScanManager: filter size is 1
,08-25 17:39:08.462  3158  3262 D BtGatt.ScanManager: delete FilterIndex - 5
,08-25 17:39:08.472  3158  3368 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 17:39:08.472  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 17:39:08.472  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:08.472  3158  3262 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:39:08.472  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 17:39:08.472  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:39:08.472  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:39:08.472  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:39:08.472  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 17:39:08.472  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-25 17:39:08.472  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.472  3158  3262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-25 17:39:08.472  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:08.482  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:39:08.482  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:39:08.482  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 17:39:08.482  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:39:08.482  3158  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 17:39:08.482  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:08.482  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:08.482  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.482  6770  6823 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 17:39:08.482  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.482  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.482  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.482  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.482  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:08.482  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.482  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.482  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.482  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.482  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.482  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:08.482  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:08.482  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.482  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.482  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:08.482  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:39:08.482  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.482  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
,08-25 17:39:08.482  6770  6823 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-25 17:39:08.492  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:39:08.492  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.492  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 17:39:08.492  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:39:08.492  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.492  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.492  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.492  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:08.492  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.492  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.492  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:08.492  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.492  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.492  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.492  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:08.492  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.492  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:08.492  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
,08-25 17:39:08.502  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 17:39:08.502  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.502  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.502  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.502  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.502  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.502  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.502  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.502  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.502  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.502  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.502  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.502  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:08.502  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
,08-25 17:39:08.502  6770  6823 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-25 17:39:08.502  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:39:08.502  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.502  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.502  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.502  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.502  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.502  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.502  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.502  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.502  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.502  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.502  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.502  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
,08-25 17:39:08.502  6770  6823 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-25 17:39:08.502  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.502  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.502  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.502  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.502  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.502  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.502  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.502  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.502  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.502  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.502  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.502  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.502  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.512  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
,08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 17:39:08.512  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-25 17:39:08.512  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 17:39:08.512  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 17:39:08.512  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.512  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.512  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.512  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.512  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.512  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.512  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
,08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.512  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.512  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:08.512  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.512  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.512  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list,
08-25 17:39:08.512  6770  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:39:08.512  6770  6823 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 17:39:08.512  6770  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:39:08.512  6770  6823 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 17:39:08.512  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 17:39:08.512  6770  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 17:39:08.512  6770  6823 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:39:08.512  6770  6823 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 17:39:08.512  6770  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:39:08.512  6770  6823 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:39:08.512  6770  6823 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 17:39:08.512  6770  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:39:08.512  6770  6823 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:39:08.512  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 17:39:08.522  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 17:39:08.522  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 17:39:08.522  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 17:39:08.522  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 17:39:08.522  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 17:39:08.522  6770  6823 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 17:39:08.522  6770  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:39:08.522  6770  6823 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 17:39:08.522  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.522  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.522  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.522  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.522  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.522  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.522  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 17:39:08.522  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.522  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.522  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.522  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.522  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.522  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.522  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.522  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.522  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.522  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.522  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.522  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.522  6770  6903 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1314
08-25 17:39:08.522  6770  6823 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 17:39:08.522  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.522  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.522  6770  6902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1314)
08-25 17:39:08.522  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.522  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.522  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.522  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.522  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.522  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.522  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.522  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.522  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.522  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.522  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.522  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1314)
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.532  6770  6823 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 17:39:08.532  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.532  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.532  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.532  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.532  6770  6823 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 17:39:08.532  6770  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 17:39:08.532  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:39:08.532  6770  6823 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 17:39:08.532  6770  6823 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 17:39:08.532  6770  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 17:39:08.532  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:39:08.532  6770  6823 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 17:39:08.532  6770  6823 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 17:39:08.532  6770  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 17:39:08.532  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:39:08.532  6770  6823 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 17:39:08.532  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.532  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.532  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.532  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.532  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.532  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.532  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.532  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.532  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.532  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.532  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.532  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 17:39:08.542  6770  6770 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 17:39:08.542  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:39:08.542  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.542  6770  6770 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:08.542  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.542  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:08.542  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.542  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:08.542  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.542  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:08.542  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.542  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.542  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.542  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.542  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.542  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.542  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.542  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.542  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.542  6770  6904 D BluetoothSocket: bindListen(): myUserId = 0
08-25 17:39:08.542  6770  6904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:39:08.542  6770  6823 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 17:39:08.542  6770  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 17:39:08.542  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 17:39:08.542  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:39:08.542  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.552  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.552  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.552  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.552  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.552  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.552  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.552  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.552  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.552  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.552  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.552  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.552  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.552  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.552  6770  6904 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-25 17:39:08.552  6770  6904 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 17:39:08.552  6770  6904 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 17:39:08.552  6770  6904 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3874e8de
08-25 17:39:08.552  6770  6904 D BluetoothSocket: channel: 6
08-25 17:39:08.552  6770  6904 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@226efabf, channel: 6, state: LISTENING
08-25 17:39:08.552  6770  6904 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@226efabf, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3874e8de, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2861258cmSocket: android.net.LocalSocket@2115d4d5 impl:android.net.LocalSocketImpl@2ee2b4ea fd:FileDescriptor[106]
08-25 17:39:08.552  6770  6904 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2115d4d5 impl:android.net.LocalSocketImpl@2ee2b4ea fd:FileDescriptor[106]
08-25 17:39:08.552  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.552  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.552  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.552  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.552  6770  6904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 17:39:08.552  6770  6904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 17:39:08.552  6770  6904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 17:39:08.552  6770  6770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 17:39:08.552  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.552  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.552  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.552  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.552  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.552  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.552  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.552  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.552  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.552  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.552  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.552  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.552  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.552  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.562  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.562  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.562  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.562  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
,08-25 17:39:08.562  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:08.562  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:08.562  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:08.562  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:08.562  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.562  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.562  6770  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f887fcf not in the list
08-25 17:39:08.562  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.562  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.562  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:08.562  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.562  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.562  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:08.562  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:08.562  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:08.562  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:08.562  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:08.562  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d29ad5c not in the list
08-25 17:39:08.562  6770  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 17:39:08.562  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:39:08.562  6770  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 17:39:08.562  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:39:08.562  6770  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 17:39:08.562  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:39:08.562  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 17:39:08.562  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 17:39:08.562  6770  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 17:39:08.562  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 17:39:08.562  6770  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 17:39:08.562  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 17:39:08.562  6770  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 17:39:08.562  6770  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 17:39:08.572  6770  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 17:39:08.572  6770  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 17:39:08.572  6770  6823 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 17:39:08.572  6770  6823 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 17:39:08.572  6770  6823 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 17:39:08.572  6770  6823 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 17:39:08.572  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:08.572  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20a283db added. We now have 2 listener(s)
08-25 17:39:08.572  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:08.572  6770  6823 D BluetoothAdapter: enable()
08-25 17:39:08.572  6770  6823 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 17:39:08.582  1017  1135 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-25 17:39:08.582  1017  1135 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 17:39:08.582  1017  1135 D SecContentProvider2: mCursor = null
08-25 17:39:08.582  1017  1135 D WifiService: setWifiEnabled: true pid=6770, uid=10171
08-25 17:39:08.582  1017  1135 W ActivityManager: Permission Denial: getCurrentUser() from pid=6770, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 17:39:08.592  1017  1135 W WifiService: Failed getting userId using ActivityManagerNative
08-25 17:39:08.592  1017  1135 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6770, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 17:39:08.592  1017  1135 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 17:39:08.592  1017  1135 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 17:39:08.592  1017  1135 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 17:39:08.592  1017  1135 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 17:39:08.592  1017  1135 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-25 17:39:08.592  1017  1135 D SettingsProvider: name = wifi_on
08-25 17:39:08.592  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:08.592  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fc10e78 added. We now have 3 listener(s)
08-25 17:39:08.592  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:08.592  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:08.592  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@206be951 added. We now have 4 listener(s)
08-25 17:39:08.592  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:08.602  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:08.602  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34af35b6 added. We now have 5 listener(s)
08-25 17:39:08.602  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:08.602  1017  1248 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 17:39:08.602  1017  1248 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-25 17:39:08.602  1017  1248 D SecContentProvider2: mCursor = null
,08-25 17:39:08.602  1017  1248 D WifiService: setWifiEnabled: false pid=6770, uid=10171
,08-25 17:39:08.602  1017  1248 D SettingsProvider: name = wifi_on
,08-25 17:39:08.612  1017  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 17:39:08.612  6770  6823 D BluetoothAdapter: disable()
08-25 17:39:08.612  1389  1389 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 17:39:08.612  1389  1389 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-25 17:39:08.612  1017  1761 D SettingsProvider: name = bluetooth_on
08-25 17:39:08.612  1389  1389 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 17:39:08.622  1389  1389 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 17:39:08.622  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:39:08.632  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:08.632  3158  3252 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-25 17:39:08.632  3158  3252 D BluetoothAdapterProperties: Setting state to 13
08-25 17:39:08.632  3158  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 17:39:08.632  3158  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 17:39:08.632  3158  3252 D BluetoothAdapterService: updateAdapterState state is 13
,08-25 17:39:08.632  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:08.632  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-25 17:39:08.632  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:08.632  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:08.632  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-25 17:39:08.632  3158  3158 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-25 17:39:08.632  3158  3252 D BluetoothAdapterService: Autoconnection is available 
08-25 17:39:08.632  3158  3252 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-25 17:39:08.632  3158  3252 D BluetoothAdapterService: terminating service from this receiver
08-25 17:39:08.632  3158  3158 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3916389a, channel: 19, state: LISTENING
08-25 17:39:08.632  3158  3158 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3916389a, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2bb78342, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@34d135cbmSocket: android.net.LocalSocket@2179f1a8 impl:android.net.LocalSocketImpl@387d44c1 fd:FileDescriptor[74]
08-25 17:39:08.632  3158  3158 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2179f1a8 impl:android.net.LocalSocketImpl@387d44c1 fd:FileDescriptor[74]
,08-25 17:39:08.632  1017  1248 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 17:39:08.632  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:08.632  1017  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:08.632  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:08.632  3158  3252 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 17:39:08.632  3158  3252 D BluetoothAdapterProperties: mDiscovering is false
,08-25 17:39:08.632  3293  3293 D BluetoothPbap: Proxy object disconnected
08-25 17:39:08.632  1017  1248 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 17:39:08.642  3293  3293 D PbapServerProfile: Bluetooth service disconnected
08-25 17:39:08.642  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:08.642  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:08.642  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:08.642  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:08.642  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:08.642  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:08.642  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:08.642  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:08.642  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:08.642  3158  3252 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-25 17:39:08.642  1017  1127 E WifiNative-wlan0: do suspend true
,08-25 17:39:08.642  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:08.642  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-25 17:39:08.642  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:08.642  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:08.642  6770  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:39:08.642  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-25 17:39:08.652  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:08.652  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 17:39:08.652  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:08.652  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:08.652  1179  1179 D BluetoothTile:  getBluetoothState : 13
,08-25 17:39:08.652  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 17:39:08.652  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 17:39:08.652  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 17:39:08.662  1873  1873 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 17:39:08.662  1017  4789 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 17:39:08.662  1017  1248 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 17:39:08.662  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-25 17:39:08.662  3293  3293 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:08.672  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:08.672  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:08.672  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:08.672  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:08.672  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:08.672  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:08.672  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:08.672  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:08.672  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:08.672  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:08.672  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:08.672  3158  3255 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 17:39:08.672  3158  3255 D BluetoothAdapterProperties: Scan Mode:20
,08-25 17:39:08.682  3158  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 17:39:08.682  3158  3252 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-25 17:39:08.682  3158  3158 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ebb63a7, channel: 5, state: LISTENING
08-25 17:39:08.682  3158  3158 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ebb63a7, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e2d2f53, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28508054mSocket: android.net.LocalSocket@6586bfd impl:android.net.LocalSocketImpl@273b40f2 fd:FileDescriptor[76]
08-25 17:39:08.682  3158  3158 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@6586bfd impl:android.net.LocalSocketImpl@273b40f2 fd:FileDescriptor[76]
,08-25 17:39:08.682  3158  3252 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-25 17:39:08.682  3158  3158 I BtOppRfcommListener: stopping Accept Thread
08-25 17:39:08.682  3158  3158 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f309343, channel: 12, state: LISTENING
08-25 17:39:08.682  3158  3158 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f309343, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b7b5945, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d5f4dc0mSocket: android.net.LocalSocket@1dc4caf9 impl:android.net.LocalSocketImpl@18387a3e fd:FileDescriptor[79]
08-25 17:39:08.682  3158  3158 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1dc4caf9 impl:android.net.LocalSocketImpl@18387a3e fd:FileDescriptor[79]
,08-25 17:39:08.682  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:08.682  3158  5235 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:39:08.682  3158  3252 E bt-btif : cmd socket is not created
08-25 17:39:08.682  3158  5235 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 17:39:08.682  3293  3293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 17:39:08.682  3158  3282 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-25 17:39:08.682  3158  3282 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-25 17:39:08.682  3158  3252 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 17:39:08.692  1017  1135 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings,
08-25 17:39:08.692  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 17:39:08.692  3158  3282 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:39:08.692  3158  3282 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:39:08.692  3158  3282 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:39:08.692  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:08.692  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:08.692  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:08.692  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 17:39:08.692  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:08.692  3158  3158 V BluetoothOppManager: cleanUp...
,08-25 17:39:08.702  3293  3293 D DockEventReceiver: finishStartingService: stopping service,
,08-25 17:39:08.702  3293  3293 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 17:39:08.712  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:08.712  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-25 17:39:08.712  1017  1248 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-25 17:39:08.712  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:08.712  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:08.712  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:08.712  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:08.722  6909  6909 E Zygote  : MountEmulatedStorage()
08-25 17:39:08.722  6909  6909 I libpersona: KNOX_SDCARD checking this for 10055
08-25 17:39:08.722  6909  6909 E Zygote  : v2
08-25 17:39:08.722  6909  6909 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:08.732  6909  6909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-25 17:39:08.732  6909  6909 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 17:39:08.732  1017  1248 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6909 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-25 17:39:08.732  6909  6909 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:08.762  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:08.762  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 17:39:08.762  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:08.762  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:08.762  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:08.772  6909  6909 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:08.772  6909  6909 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:08.812  6909  6909 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-25 17:39:08.842  6909  6909 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-25 17:39:08.842  6909  6909 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-25 17:39:08.842  6909  6909 D UserAnalysis: Create SecureDbHelper
,08-25 17:39:08.852  6909  6909 D IntelligenceServiceApplication: onCreate()
,08-25 17:39:08.852  1017  4786 I ActivityManager: Killing 6473:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-25 17:39:08.862  6909  6909 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-25 17:39:08.862  1017  1481 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-25 17:39:08.862  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:08.862  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:08.862  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:08.862  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:08.872  6928  6928 E Zygote  : MountEmulatedStorage()
,08-25 17:39:08.872  1017  1481 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6928 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-25 17:39:08.872  6928  6928 E Zygote  : v2
08-25 17:39:08.872  6928  6928 I libpersona: KNOX_SDCARD checking this for 10105
08-25 17:39:08.872  6928  6928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 17:39:08.872  6928  6928 I libpersona: KNOX_SDCARD not a persona
08-25 17:39:08.872  1017  4786 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-25 17:39:08.882  6909  6909 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
,08-25 17:39:08.882  6928  6928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:39:08.882  6928  6928 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 17:39:08.882  6909  6909 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-25 17:39:08.882  3158  3282 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:39:08.882  3158  3282 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:39:08.882  3158  3282 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:39:08.882  3158  3282 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:39:08.882  3158  3282 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:39:08.882  3158  3282 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:39:08.882  3158  3282 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:39:08.882  3158  3282 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:39:08.882  3158  3282 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:39:08.882  3158  3282 W bt-btif : ag scb idx 1 not allocated
08-25 17:39:08.882  3158  3282 W bt-btif : ag scb idx 2 not allocated
08-25 17:39:08.882  3158  3282 E bt-btif : BTA AG is already disabled, ignoring ...
,08-25 17:39:08.892  3158  3357 I bt_userial_mct: exiting userial_read_thread
08-25 17:39:08.892  3158  3357 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 17:39:08.892  3158  3255 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 17:39:08.892  3158  3284 I bt_vendor: hw_epilog_process
08-25 17:39:08.892  3158  3255 D bt_userial_mct: userial_close
,08-25 17:39:08.892  3158  3255 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 17:39:08.902  6928  6928 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:08.902  6928  6928 D ActivityThread: Added TimaKeyStore provider,
,08-25 17:39:09.022   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 17:39:09.022   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 17:39:09.022  6928  6948 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 17:39:09.032   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 17:39:09.032   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 17:39:09.032  6928  6948 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 17:39:09.042  6770  6770 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 17:39:09.102  1389  1389 I wpa_supplicant: nl80211: Received scan results (6 BSSes)
,08-25 17:39:09.102   288   288 E SMD     : DCD OFF
08-25 17:39:09.102  1017  1126 D WifiP2pService: InactiveState{ what=147461 }
08-25 17:39:09.102  1017  1126 D WifiP2pService: P2pEnabledState{ what=147461 }
08-25 17:39:09.102  1017  1126 D WifiP2pService: DefaultState{ what=147461 }
,08-25 17:39:09.102   278   987 D CommandListener: Clearing all IP addresses on wlan0
,08-25 17:39:09.112  1993  3043 V NativeCrypto: Read error: ssl=0xb85a48e8: I/O error during system call, Connection timed out
,08-25 17:39:09.122  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
08-25 17:39:09.122  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 17:39:09.132  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:09.132  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 17:39:09.132  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:09.132  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.132  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.132  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:09.132  1017  1129 E ConnectivityService: updateNetworkInfo()
08-25 17:39:09.132  1017  1129 E ConnectivityService: updateNetworkInfo()
08-25 17:39:09.132  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 17:39:09.132  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-25 17:39:09.132  1017  1126 D WifiP2pService: InactiveState{ what=131204 }
08-25 17:39:09.132  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-25 17:39:09.132   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
08-25 17:39:09.132  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-25 17:39:09.142  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-25 17:39:09.142  1017  1126 D WifiP2pService: P2pDisablingState
08-25 17:39:09.142  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-25 17:39:09.142  1017  1126 D WifiP2pService: p2p socket connection lost
08-25 17:39:09.142  1017  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-25 17:39:09.142  1017  1126 D WifiP2pService: P2pDisabledState,
,08-25 17:39:09.152  3158  3255 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 17:39:09.152  3158  3255 I bt_vendor: bluetooth satus is on
08-25 17:39:09.152  3158  3255 I bt_vendor: bt-vendor : resetting BT status
08-25 17:39:09.152  3158  3255 I bt_vendor: Starting hciattach daemon
,08-25 17:39:09.152  3158  3255 I bt_vendor: try to set false
08-25 17:39:09.152  3158  3255 I bt_vendor: Starting hciattach daemon
08-25 17:39:09.152  3158  3255 I bt_vendor: try to set false
08-25 17:39:09.152  3158  3255 I bt_vendor: cleanup
08-25 17:39:09.152  3158  3282 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-25 17:39:09.152  3158  3255 I GKI_LINUX: GKI_exit_task 0 done
08-25 17:39:09.152  3158  3255 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-25 17:39:09.152  3158  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 17:39:09.152  3158  3252 D BtConfig.SecureMode: isSecureModeOn:false
08-25 17:39:09.152  3158  3252 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
08-25 17:39:09.152  1017  1127 E WifiNative-wlan0: do suspend true
08-25 17:39:09.152  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 17:39:09.152  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-25 17:39:09.152  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-25 17:39:09.162  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
08-25 17:39:09.162  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-25 17:39:09.182   278   987 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:39:09.182  1017  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-25 17:39:09.182  1017  1129 V NetworkStats: updateIfacesLocked()
08-25 17:39:09.182  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:09.182  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-25 17:39:09.182  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:09.182  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 17:39:09.192  1389  1389 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-25 17:39:09.192  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 17:39:09.192  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:09.192  1017  1129 V NetworkStats: performPollLocked() took 10ms
,08-25 17:39:09.192  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:09.202  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 17:39:09.202  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:09.202  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 17:39:09.202  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-25 17:39:09.202  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:39:09.202  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 17:39:09.202  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-25 17:39:09.202  1017  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:39:09.202  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-25 17:39:09.212  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 17:39:09.212  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.212  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:09.212  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.212  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:09.222  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-25 17:39:09.222  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-25 17:39:09.222  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-25 17:39:09.222  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 17:39:09.222  1017  1047 D WifiDisplayController: disconnect
08-25 17:39:09.222  1017  1047 D WifiDisplayController: updateConnection
08-25 17:39:09.222  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 17:39:09.222  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 17:39:09.222  3293  3293 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:39:09.232  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:09.232  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:09.232  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:09.232  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:09.232  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:09.232  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:09.232  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:09.232  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:09.232  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 17:39:09.232  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 17:39:09.232  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 17:39:09.232  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.232  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.232  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:09.232  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:09.232  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-25 17:39:09.232  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 17:39:09.232  1179  1179 D HotspotTile: onReceive : 0, 0
,08-25 17:39:09.232  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:09.232  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:09.242  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:09.242  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:09.242  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 17:39:09.242  1017  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-25 17:39:09.242  1017  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-25 17:39:09.242  1017  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-25 17:39:09.242  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 17:39:09.242  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-25 17:39:09.242  1017  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-25 17:39:09.242  1017  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,08-25 17:39:09.242  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:09.242  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:09.242  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:09.242  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:09.242  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:09.242  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:09.242  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:09.242  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:09.242  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:39:09.242  1455  1455 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-25 17:39:09.242  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-25 17:39:09.242  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:09.242  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:39:09.242  4732  6833 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-25 17:39:09.252  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:09.252  1017  1124 V NetworkStats: updateIfacesLocked()
08-25 17:39:09.252  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:09.252  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 17:39:09.252  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 17:39:09.262  1017  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-20ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:39:09.262  1017  1124 V NetworkStats: performPollLocked() took 9ms
,08-25 17:39:09.262  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:09.272  1179  1737 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-25 17:39:09.272  1017  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 17:39:09.272  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 17:39:09.272  1179  1201 I art     : Background sticky concurrent mark sweep GC freed 1118(73KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 24MB/24MB, paused 31.970ms total 46.001ms
,08-25 17:39:09.282  1389  1389 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: EthernetConnected: false
08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: updateDataNetType()
08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-25 17:39:09.312  1179  1179 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 17:39:09.312  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.312  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:09.332  1017  4786 I art     : Explicit concurrent mark sweep GC freed 34870(1881KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 8.655ms total 223.651ms
,08-25 17:39:09.332  1993  3043 V NativeCrypto: SSL shutdown failed: ssl=0xb85a48e8: I/O error during system call, Broken pipe
08-25 17:39:09.332  1017  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:09.332  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-25 17:39:09.332  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:09.332  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:09.332  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:09.342  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 17:39:09.342  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 17:39:09.342  3158  3158 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 17:39:09.342  6928  6928 D StrictMode: StrictMode policy violation; ~duration=312 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:09.342  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 17:39:09.342  1389  1389 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 17:39:09.342  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:09.342  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 17:39:09.342  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-25 17:39:09.342  6928  6928 D StrictMode: StrictMode policy violation; ~duration=311 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190),
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:09.342  6928  6928 D StrictMode: 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:09.342  6928  6928 D StrictMode: StrictMode policy violation; ~duration=310 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
,08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 17:39:09.342  6928  6928 D StrictMode: StrictMode policy violation; ~duration=307 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 17:39:09.342  6928  6928 D StrictMode: 	,at com.google.q.v.a(PG:1161)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 17:39:09.342  6928  6928 D StrictMode: StrictMode policy violation; ~duration=306 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.k.d(PG:583)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:09.342  6928  6928 D StrictMode: ,	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:09.342  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:39:09.342  6928  6928 D StrictMode: StrictMode policy violation; ~duration=278 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 17:39:09.342  6928  6928 D StrictMode: StrictMode policy violation; ~duration=278 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:09.342  6928  6928 D StrictMode: ,	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:09.352  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-25 17:39:09.342  6928  6928 D StrictMode: StrictMode policy violation; ~duration=277 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
,08-25 17:39:09.342  6928  6928 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:09.342  6928  6928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:09.342  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 17:39:09.342  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-25 17:39:09.342  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-25 17:39:09.342  1017  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-25 17:39:09.342  1017  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-25 17:39:09.342  1017  1129 E ConnectivityService: updateNetworkInfo()
08-25 17:39:09.342  1017  1129 E ConnectivityService: updateNetworkInfo()
08-25 17:39:09.342  3158  3158 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 17:39:09.342  3158  3158 D BtGatt.GattService: stop()
08-25 17:39:09.342  3158  3158 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 17:39:09.352  1993  3043 E GCM     : Wifi connection closed with errorCode 20
08-25 17:39:09.352  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:09.352  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:09.352  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:09.352  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 17:39:09.352  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-25 17:39:09.352  1017  1130 D Tethering: MasterInitialState.processMessage what=3
08-25 17:39:09.352  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:09.352  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:09.352  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:09.352  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:09.352  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:09.352  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:09.352  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-25 17:39:09.362  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 17:39:09.362  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 17:39:09.362  1389  1389 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-25 17:39:09.362  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-25 17:39:09.362  1389  1389 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-25 17:39:09.362  1389  1389 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-25 17:39:09.362  1389  1389 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-25 17:39:09.362  1389  1389 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-25 17:39:09.362  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:09.362  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:09.362  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:09.362  1017  1130 D Tethering: InitialState.processMessage what=4
,08-25 17:39:09.372  1017  1029 I ActivityManager: Killing 6367:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-25 17:39:09.372  1017  1456 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:09.372  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 17:39:09.372  1017  1130 E Tethering: No numeric data
08-25 17:39:09.372  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
08-25 17:39:09.372  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:09.372  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:09.372  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-25 17:39:09.372  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:09.372  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:09.372  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:09.372  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-25 17:39:09.372  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 17:39:09.372  1993  1993 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-25 17:39:09.372  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-25 17:39:09.372  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:09.372  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:09.372  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:09.382  1993  1993 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 17:39:09.382  1017  1248 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:09.382  1017  1248 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 17:39:09.382  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:09.382  1017  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:09.382  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:09.382  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 17:39:09.392  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-25 17:39:09.392  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 17:39:09.392  1017  1130 D Tethering: clearTetheredNotification()
,08-25 17:39:09.392  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 17:39:09.392  3158  3158 D HeadsetService: Received stop request...Stopping profile...
,08-25 17:39:09.392  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:09.392  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-25 17:39:09.392  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:09.392  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 17:39:09.392  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 17:39:09.392  1179  1179 D HotspotTile: updateTetherState():false, false
,08-25 17:39:09.402  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:09.402  1017  1124 V NetworkStats: performPollLocked() took 6ms
,08-25 17:39:09.402  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:09.402  1017  1761 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:09.402  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-25 17:39:09.402  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:09.412  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:09.412  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:09.412  1017  1761 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:09.412  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:09.412  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 17:39:09.412  1017  1248 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:09.412  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 17:39:09.412  1017  1248 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 17:39:09.412  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-25 17:39:09.412  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:09.412  1017  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:09.412  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:09.412  1620  1620 I Hs20UtilService: Starting #8
08-25 17:39:09.412  1620  1652 I Hs20UtilService: Message received 5007
,08-25 17:39:09.422  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-25 17:39:09.422   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb75797c8
08-25 17:39:09.422  6928  6961 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-25 17:39:09.422   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,08-25 17:39:09.422   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-25 17:39:09.422   273   356 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1218996936)
,08-25 17:39:09.422  3293  3293 D HeadsetProfile: Bluetooth service disconnected
08-25 17:39:09.422  1017  4790 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:09.422  1017  4790 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 17:39:09.432  1017  4790 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:09.432  1017  4790 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:09.432  1017  4790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:09.432  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-25 17:39:09.432  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:09.432  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 17:39:09.442  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 17:39:09.442  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:09.442  1017  1248 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:09.442  1017  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:09.442  1017  1248 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-25 17:39:09.442  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:09.442  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-25 17:39:09.442  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 17:39:09.452  3158  3252 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 17:39:09.452  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:09.462  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 17:39:09.462  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:09.462  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:09.462  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:09.462  1017  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:09.462  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:09.462  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 17:39:09.462  3158  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:09.462  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:09.462  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:09.462  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-25 17:39:09.462  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:09.462  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 17:39:09.462  3158  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:09.472  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 17:39:09.472  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 17:39:09.472  3293  3293 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 17:39:09.472  3158  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 17:39:09.472  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 17:39:09.472  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-25 17:39:09.472  3158  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 17:39:09.472  3158  3252 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 17:39:09.472  3158  3158 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-25 17:39:09.472  3158  3158 D A2dpService: Received stop request...Stopping profile...
,08-25 17:39:09.472  3158  3272 D A2dpStateMachine: Exit Disconnected: -1
08-25 17:39:09.472  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 17:39:09.472  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 17:39:09.472  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 17:39:09.472  3293  3293 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 17:39:09.472  3293  3905 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 17:39:09.482  1389  1389 I wpa_supplicant: Blacklist: Clear (all) 
08-25 17:39:09.482   273   356 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-25 17:39:09.482   273   356 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,08-25 17:39:09.482   273   356 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1218996936) wakelock released: 1, error no: 0
08-25 17:39:09.482   273   356 I rmt_storage: 
,08-25 17:39:09.492   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb75797c8
,08-25 17:39:09.492  1993  2170 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-25 17:39:09.492  1993  2170 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-25 17:39:09.492  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 17:39:09.492  3293  3293 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 17:39:09.502  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
08-25 17:39:09.502  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 17:39:09.502  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 17:39:09.502  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 17:39:09.502  3293  3293 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 17:39:09.502  3293  3905 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 17:39:09.502  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-25 17:39:09.502  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-25 17:39:09.502  3158  3158 D HidService: Received stop request...Stopping profile...
08-25 17:39:09.502  1017  1761 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-25 17:39:09.502  3158  3158 D HidService: Stopping Bluetooth HidService
08-25 17:39:09.502  3293  3293 D BluetoothA2dp: Proxy object disconnected
08-25 17:39:09.502  3293  3293 D A2dpProfile: Bluetooth service disconnected
08-25 17:39:09.502  3158  3158 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 17:39:09.502  3158  3158 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-25 17:39:09.502  3158  3158 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 17:39:09.502  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:09.502  1017  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:09.502  1017  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:09.502  1017  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:09.502  1017  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:09.522  6967  6967 E Zygote  : MountEmulatedStorage(),
08-25 17:39:09.522  6967  6967 E Zygote  : v2
08-25 17:39:09.522  6967  6967 I libpersona: KNOX_SDCARD checking this for 10064
08-25 17:39:09.522  6967  6967 I libpersona: KNOX_SDCARD not a persona,
,08-25 17:39:09.522  6967  6967 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:09.522  1017  1761 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6967 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-25 17:39:09.522  6967  6967 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:39:09.522  3158  3158 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-25 17:39:09.522  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 17:39:09.522  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-25 17:39:09.522  3293  3293 D BluetoothInputDevice: Proxy object disconnected
08-25 17:39:09.522  3293  3293 D HidProfile: Bluetooth service disconnected
08-25 17:39:09.522  3158  3158 D HealthService: Received stop request...Stopping profile...
08-25 17:39:09.532  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:09.532  6967  6967 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:09.532  1389  1389 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-25 17:39:09.532  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:09.532  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:09.532  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:09.542  3158  3158 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 17:39:09.542  3158  3158 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 17:39:09.542  3158  3158 D PanService: Received stop request...Stopping profile...,
08-25 17:39:09.542  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:09.552  3158  3158 D BluetoothMapService: Received stop request...Stopping profile...
08-25 17:39:09.552  3293  3293 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 17:39:09.552  3293  3293 D PanProfile: Bluetooth service disconnected
08-25 17:39:09.552  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 17:39:09.552  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:09.552  3293  3293 D BluetoothMap: Proxy object disconnected
08-25 17:39:09.562  3293  3293 D MapProfile: Bluetooth service disconnected
,08-25 17:39:09.562  3158  3158 D SapService: Received stop request...Stopping profile...
08-25 17:39:09.562  3158  3158 D SapService: Stopping Bluetooth SapService
08-25 17:39:09.562  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:09.562  3158  3158 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-25 17:39:09.562  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 17:39:09.562  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 17:39:09.562  3158  3158 D BluetoothA2dp: Proxy object disconnected
08-25 17:39:09.562  3158  3158 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-25 17:39:09.562  3158  3273 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 17:39:09.562  3293  3293 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-25 17:39:09.562  3293  3293 D SapProfile: Bluetooth service disconnected
08-25 17:39:09.562  3158  3158 I GKI_LINUX: GKI_exit_task 2 done
08-25 17:39:09.562  3158  3158 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-25 17:39:09.562  6967  6967 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 17:39:09.562  6967  6967 D ActivityThread: Added TimaKeyStore provider
08-25 17:39:09.562  3158  3158 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-25 17:39:09.562  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:09.562  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-25 17:39:09.562  3158  3158 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-25 17:39:09.562  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:09.562  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:09.562  3158  3158 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 17:39:09.562  3158  3158 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:39:09.562  3158  3158 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-25 17:39:09.562  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:09.562  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:09.562  3158  3158 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 17:39:09.562  3158  3158 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-25 17:39:09.572  3158  3158 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-25 17:39:09.572  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 17:39:09.572  3158  3158 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-25 17:39:09.572  3158  3158 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-25 17:39:09.572  3158  3158 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-25 17:39:09.572  3158  3158 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-25 17:39:09.572  3158  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-25 17:39:09.572  3158  3252 D BluetoothAdapterProperties: Setting state to 10
08-25 17:39:09.572  3158  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 17:39:09.572  3158  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 17:39:09.572  3158  3252 D BluetoothAdapterService: updateAdapterState state is 10
,08-25 17:39:09.572  3158  3252 D BluetoothAdapterService: Autoconnection is available 
08-25 17:39:09.572  3158  3252 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-25 17:39:09.572  3158  3252 I BluetoothAdapterState: Entering OffState
,08-25 17:39:09.572  3293  3304 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 17:39:09.582  1439  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:09.582  1439  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 17:39:09.582  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 17:39:09.582  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:39:09.582  3158  3368 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:09.582  3158  3368 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 17:39:09.582  6770  6780 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:09.582  6770  6780 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 17:39:09.582  6770  6780 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-25 17:39:09.582  6770  6780 D BluetoothLeAdvertiser: Exit stop advertising
08-25 17:39:09.582  6770  6780 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-25 17:39:09.582  6770  6780 D BluetoothLeScanner: Exiting stopAllScan
,08-25 17:39:09.582  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:09.582  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 17:39:09.582  1993  2010 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:09.582  1993  2010 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 17:39:09.582  3293  3304 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 17:39:09.582  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 17:39:09.592  3158  3367 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:39:09.592  6967  6967 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-25 17:39:09.592  3293  3301 D Bluetoothsap: onBluetoothStateChange: up=false
08-25 17:39:09.592  3293  3301 D Bluetoothsap: Unbinding service...
08-25 17:39:09.592  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 17:39:09.592  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 17:39:09.592  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 17:39:09.592  3293  3304 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:09.592  3293  3304 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 17:39:09.592  6928  6938 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 17:39:09.592  6928  6938 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 17:39:09.592  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 17:39:09.592  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 17:39:09.592  3293  3301 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:39:09.592  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 17:39:09.592  1424  3263 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:09.592  1424  3263 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 17:39:09.592  1455  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:09.592  1455  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 17:39:09.592  3293  3304 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 17:39:09.592  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 17:39:09.592  1179  3358 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:09.592  1179  3358 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 17:39:09.602  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-25 17:39:09.602  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-25 17:39:09.602  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 17:39:09.602  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 17:39:09.602  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 17:39:09.602  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 17:39:09.602  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,08-25 17:39:09.602  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 17:39:09.612  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 17:39:09.612  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 17:39:09.612  6967  6967 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 17:39:09.612  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 17:39:09.612  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 17:39:09.612  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 17:39:09.612  6967  6967 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-25 17:39:09.612  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 17:39:09.612  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 17:39:09.612  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 17:39:09.612  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 17:39:09.612  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 17:39:09.622  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 17:39:09.622  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 17:39:09.622  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 17:39:09.622  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 17:39:09.622  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 17:39:09.622  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:09.622  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-25 17:39:09.622  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 17:39:09.632  3158  3255 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 17:39:09.632  3158  3158 I GKI_LINUX: GKI_exit_task 1 done
08-25 17:39:09.632  3158  3158 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-25 17:39:09.632  1179  1179 D BluetoothAdapter: 557880363: getState() :  mService = null. Returning STATE_OFF
,08-25 17:39:09.632  3158  3158 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 17:39:09.632  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 17:39:09.632  1179  1760 D BluetoothAdapter: 557880363: getState() :  mService = null. Returning STATE_OFF
,08-25 17:39:09.632  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:09.632  1179  1179 D BluetoothTile:  getBluetoothState : 10
,08-25 17:39:09.632  1179  1760 D BluetoothAdapter: 557880363: getState() :  mService = null. Returning STATE_OFF
,08-25 17:39:09.632  1179  1179 D BluetoothAdapter: 557880363: getState() :  mService = null. Returning STATE_OFF
,08-25 17:39:09.632  1873  1873 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 17:39:09.642  1179  1179 D BluetoothAdapter: 557880363: getState() :  mService = null. Returning STATE_OFF
,08-25 17:39:09.642  1993  2157 D BluetoothAdapter: 80648906: getState() :  mService = null. Returning STATE_OFF
08-25 17:39:09.642  1017  1327 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 17:39:09.642  1993  2157 D BluetoothAdapter: 80648906: getState() :  mService = null. Returning STATE_OFF
08-25 17:39:09.642  1017  1480 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 17:39:09.642  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-25 17:39:09.642  3293  3293 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:09.642  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-25 17:39:09.642  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 17:39:09.642  1017  4790 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 17:39:09.642  1017  4790 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-25 17:39:09.642  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:09.642  3158  3158 I art     : System.exit called, status: 0
08-25 17:39:09.642  3158  3158 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 17:39:09.642  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:09.642  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:09.642  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:09.642  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:09.642  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:09.642  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:09.642  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:09.642  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:09.642  1017  4790 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:09.642  1017  4790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:09.642  1017  4790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:09.652  6967  6967 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 17:39:09.652  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:09.652  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:09.652  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:09.652  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:09.652  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:09.652  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:09.652  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:09.652  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:09.652  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:09.652  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 17:39:09.652  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 17:39:09.652  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.652  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.652  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.652  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:09.652  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:09.652  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-25 17:39:09.652  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 17:39:09.652  1993  2157 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 17:39:09.652  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:39:09.652  1179  1179 D HotspotTile: onReceive : 1, 0
,08-25 17:39:09.652  3293  3293 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:39:09.662  1017  1456 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
08-25 17:39:09.662  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:09.662  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:09.662  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:09.662  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:09.662  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:09.662  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:09.672  6999  6999 E Zygote  : MountEmulatedStorage(),
,08-25 17:39:09.672  6999  6999 E Zygote  : v2
08-25 17:39:09.672  6999  6999 I libpersona: KNOX_SDCARD checking this for 10065
08-25 17:39:09.672  6999  6999 I libpersona: KNOX_SDCARD not a persona,
08-25 17:39:09.682  6999  6999 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 17:39:09.672  1017  1456 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6999 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-25 17:39:09.682  6999  6999 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:39:09.682  1017  1456 I ActivityManager: Killing 6503:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-25 17:39:09.682  6999  6999 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:09.692  6999  6999 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:09.692  6999  6999 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:09.702  1017  1327 I ActivityManager: Process com.android.bluetooth (pid 3158)(adj 0) has died(35,710)
,08-25 17:39:09.722  6999  6999 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 17:39:09.732  1017  4790 I ActivityManager: Killing 6518:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-25 17:39:09.742  1017  1456 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:09.742  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:09.742  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:09.742  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:09.742  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:09.742  1620  1620 I Hs20UtilService: Starting #9
08-25 17:39:09.742  1620  1652 I Hs20UtilService: Message received 5007
,08-25 17:39:09.742  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 17:39:09.742  3293  3293 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 17:39:09.742  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 17:39:09.742  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 17:39:09.742  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false,
08-25 17:39:09.742  3293  3293 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 17:39:09.742  3293  3905 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 17:39:09.752  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:09.752  1017  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 17:39:09.752  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:09.762  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:09.762  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:09.762  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:09.762  1620  1620 I Hs20UtilService: Starting #10
,08-25 17:39:09.762  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-25 17:39:09.762  1620  1652 I Hs20UtilService: Message received 5011
,08-25 17:39:09.772  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:09.772  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:09.782  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 17:39:09.782  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 17:39:09.782  6587  6587 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 17:39:09.782  6587  6587 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 17:39:09.792  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:09.792  1017  4787 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:09.792  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:09.902  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:10.132   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 17:39:10.182  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.182  1017  1017 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:10.182  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-25 17:39:10.182  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-25 17:39:10.182  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:10.182  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:10.182  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:10.182  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:10.202  1017  1017 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7017 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 17:39:10.202  7017  7017 E Zygote  : MountEmulatedStorage()
08-25 17:39:10.202  7017  7017 I libpersona: KNOX_SDCARD checking this for 10102
,08-25 17:39:10.202  7017  7017 E Zygote  : v2
08-25 17:39:10.202  7017  7017 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:10.202  7017  7017 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:10.212  7017  7017 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:10.212  7017  7017 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-25 17:39:10.232  7017  7017 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:10.232  7017  7017 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:10.252  1017  1044 D Tethering: interfaceRemoved wlan0
08-25 17:39:10.252  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-25 17:39:10.262  7017  7017 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 17:39:10.372  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 17:39:10.412  1017  1044 D Tethering: interfaceRemoved p2p0,
08-25 17:39:10.412  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-25 17:39:10.472  7017  7038 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-25 17:39:10.472  7017  7038 I Babel_SMS: MmsConfig.loadMmsSettings
,08-25 17:39:10.472  7017  7038 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-25 17:39:10.472  7017  7038 I Babel_SMS: MmsConfig.loadFromDatabase
,08-25 17:39:10.502  7017  7038 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-25 17:39:10.502  7017  7038 I Babel_SMS: MmsConfig.loadFromResources
,08-25 17:39:10.502  7017  7038 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-25 17:39:10.502  7017  7038 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-25 17:39:10.512  1017  1761 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-25 17:39:10.512  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-25 17:39:10.512  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:10.512  1017  1761 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:10.512  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 17:39:10.532  7017  7017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 17:39:10.542  7017  7017 I Babel_Crash: startup - clean
,08-25 17:39:10.572  1017  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:10.572  1017  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.572  1017  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.582  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:10.582  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.582  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.582  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:10.582  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.582  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.592  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.592  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.592  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.592  7017  7017 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 17:39:10.592  7017  7017 W AudioCapabilities: Unsupported mime audio/evrc
,08-25 17:39:10.592  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:10.592  7017  7017 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 17:39:10.592  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.592  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.602  7017  7017 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-25 17:39:10.602  7017  7017 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-25 17:39:10.602  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.602  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.602  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.602  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:10.602  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:10.602  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-25 17:39:10.602  7017  7017 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-25 17:39:10.602  7017  7017 W AudioCapabilities: Unsupported mime audio/x-ima
,08-25 17:39:10.602  7017  7017 W AudioCapabilities: Unsupported mime audio/qcelp
,08-25 17:39:10.602  7017  7017 W AudioCapabilities: Unsupported mime audio/evrc
,08-25 17:39:10.612  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:10.612  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.612  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.612  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.612  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.612  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.612  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.612  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.612  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.622  7017  7017 W VideoCapabilities: Unsupported mime video/wvc1
,08-25 17:39:10.622  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.622  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.622  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.622  7017  7017 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-25 17:39:10.622  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.622  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.622  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.622  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.622  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.622  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.632  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.632  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.632  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 17:39:10.632  7017  7017 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-25 17:39:10.632  7017  7017 W VideoCapabilities: Unsupported mime video/wvc1
,08-25 17:39:10.632  7017  7017 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-25 17:39:10.632  3293  3293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 17:39:10.632  7017  7017 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-25 17:39:10.632  1017  1481 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 17:39:10.632  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 17:39:10.642  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.642  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.642  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 17:39:10.642  7017  7017 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-25 17:39:10.642  7017  7017 W VideoCapabilities: Unsupported mime video/mp43
,08-25 17:39:10.642  3293  3293 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:39:10.652  3293  3293 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 17:39:10.652  7017  7017 W VideoCapabilities: Unsupported mime video/sorenson
,08-25 17:39:10.652  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:10.652  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-25 17:39:10.662  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-25 17:39:10.662  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:10.662  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:10.662  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:10.662  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:10.662  7017  7017 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-25 17:39:10.672  7043  7043 E Zygote  : MountEmulatedStorage()
,08-25 17:39:10.672  7043  7043 I libpersona: KNOX_SDCARD checking this for 1002
08-25 17:39:10.672  7043  7043 E Zygote  : v2
08-25 17:39:10.672  7043  7043 I libpersona: KNOX_SDCARD not a persona
08-25 17:39:10.672  7043  7043 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:10.672  1017  1135 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7043 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
08-25 17:39:10.672  7043  7043 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:10.672  7043  7043 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:10.682  7017  7017 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 17:39:10.702  7043  7043 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:10.702  7043  7043 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:10.712  7043  7043 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 17:39:10.712  7017  7017 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-25 17:39:10.712  7043  7043 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 17:39:10.712  7017  7017 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 17:39:10.712  7017  7017 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 17:39:10.722  7017  7017 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 17:39:10.722  1017  1248 I ActivityManager: Killing 6553:com.samsung.android.sm/1000 (adj 15): empty #21
,08-25 17:39:10.722  7017  7017 I vclib   : onServiceConnected
,08-25 17:39:10.742  7043  7043 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding GattService
,08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding HeadsetService
08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding A2dpService
,08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding HidService
08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding HealthService
,08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding PanService
08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding SapService
,08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding SapClientService
,08-25 17:39:10.772  7043  7043 D BtSettings.ProfileConfig: Adding HidDevService
08-25 17:39:10.772  7043  7043 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-25 17:39:10.772  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-25 17:39:10.772  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:10.772  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:10.772  1017  1029 D SettingsProvider: selectionArgs: false
,08-25 17:39:10.772  1017  1029 D SettingsProvider: selectionArgs: 1002
08-25 17:39:10.782  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 17:39:10.782  1017  1029 D SettingsProvider: ret = -1
,08-25 17:39:10.782  1017  4787 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-25 17:39:10.782  1017  4787 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:10.782  1017  4787 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:10.782  1017  4787 D SettingsProvider: selectionArgs: false
08-25 17:39:10.782  1017  4787 D SettingsProvider: selectionArgs: 1002
08-25 17:39:10.782  1017  4787 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:10.782  1017  4787 D SettingsProvider: ret = -1
,08-25 17:39:10.782  1017  4790 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-25 17:39:10.782  1017  4790 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:10.782  1017  4790 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:10.782  1017  4790 D SettingsProvider: selectionArgs: false
08-25 17:39:10.782  1017  4790 D SettingsProvider: selectionArgs: 1002
08-25 17:39:10.782  1017  4790 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:10.782  1017  4790 D SettingsProvider: ret = -1
,08-25 17:39:10.782  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-25 17:39:10.782  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:10.782  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:10.782  1017  1030 D SettingsProvider: selectionArgs: false
08-25 17:39:10.782  1017  1030 D SettingsProvider: selectionArgs: 1002
08-25 17:39:10.782  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:10.782  1017  1030 D SettingsProvider: ret = -1
,08-25 17:39:10.782  1017  1456 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-25 17:39:10.782  1017  1456 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:10.782  1017  1456 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:10.782  1017  1456 D SettingsProvider: selectionArgs: false
,08-25 17:39:10.782  1017  1456 D SettingsProvider: selectionArgs: 1002
08-25 17:39:10.782  1017  1456 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:10.782  1017  1456 D SettingsProvider: ret = -1
,08-25 17:39:10.782  1017  1327 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-25 17:39:10.782  1017  1327 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:10.782  1017  1327 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:10.782  1017  1327 D SettingsProvider: selectionArgs: false
,08-25 17:39:10.782  1017  1327 D SettingsProvider: selectionArgs: 1002
08-25 17:39:10.782  1017  1327 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:10.782  1017  1327 D SettingsProvider: ret = -1
,08-25 17:39:10.782  1017  1463 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-25 17:39:10.782  1017  1463 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 17:39:10.782  1017  1463 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:10.782  1017  1463 D SettingsProvider: selectionArgs: false
08-25 17:39:10.782  1017  1463 D SettingsProvider: selectionArgs: 1002
08-25 17:39:10.782  1017  1463 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:10.782  1017  1463 D SettingsProvider: ret = -1
,08-25 17:39:10.792  1017  4789 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-25 17:39:10.792  1017  4789 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:10.792  1017  4789 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:10.792  1017  4789 D SettingsProvider: selectionArgs: false
08-25 17:39:10.792  1017  4789 D SettingsProvider: selectionArgs: 1002
08-25 17:39:10.792  1017  4789 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 17:39:10.792  1017  4789 D SettingsProvider: ret = -1
,08-25 17:39:10.792  1017  1135 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:10.792  1017  1135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:10.792  1017  1135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:10.792  1017  1135 D SettingsProvider: selectionArgs: false
08-25 17:39:10.792  1017  1135 D SettingsProvider: selectionArgs: 1002
08-25 17:39:10.792  1017  1135 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:10.792  1017  1135 D SettingsProvider: ret = -1
,08-25 17:39:10.792  1017  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:10.792  1017  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:10.792  1017  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:10.792  1017  1474 D SettingsProvider: selectionArgs: false
08-25 17:39:10.792  1017  1474 D SettingsProvider: selectionArgs: 1002
08-25 17:39:10.792  1017  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:10.792  1017  1474 D SettingsProvider: ret = -1
,08-25 17:39:10.792  1017  1248 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-25 17:39:10.792  1017  1248 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 17:39:10.792  1017  1248 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:10.792  1017  1248 D SettingsProvider: selectionArgs: false
,08-25 17:39:10.792  1017  1248 D SettingsProvider: selectionArgs: 1002
,08-25 17:39:10.802  1017  1248 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:10.802  1017  1248 D SettingsProvider: ret = -1
,08-25 17:39:10.802  1017  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-25 17:39:10.802  1017  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:10.802  1017  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 17:39:10.802  1017  1480 D SettingsProvider: selectionArgs: false
,08-25 17:39:10.802  1017  1480 D SettingsProvider: selectionArgs: 1002
08-25 17:39:10.802  1017  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-25 17:39:10.802  1017  1480 D SettingsProvider: ret = -1
,08-25 17:39:10.812  1017  1481 I ActivityManager: Killing 6604:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-25 17:39:10.822  1993  1993 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 17:39:10.822  1017  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 17:39:10.822  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 17:39:10.822  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.822  1017  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:10.822  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:10.842  1993  7059 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 17:39:10.842  1993  1993 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 17:39:10.852  1017  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:10.852  1017  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:10.852  1017  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:10.852  1017  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:10.862  1017  1761 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 17:39:10.862  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:10.862  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:10.862  1017  1761 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:10.862  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:10.872  1620  1620 I Hs20UtilService: Starting #11
,08-25 17:39:10.872  1620  1652 I Hs20UtilService: Message received 5011
,08-25 17:39:10.872  1017  4790 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:10.872  1017  4790 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:10.872  1017  4790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:10.872  1017  4790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
08-25 17:39:10.882  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 17:39:10.882  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 17:39:10.882  6587  6587 D SecurityLogAgent: StateMachine : Current State = 1
08-25 17:39:10.882  6587  6587 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 17:39:10.882  1017  1474 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-25 17:39:10.892  1993  7059 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-25 17:39:10.892  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:10.892  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:10.892  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:10.892  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:10.902  7060  7060 E Zygote  : MountEmulatedStorage()
,08-25 17:39:10.902  7060  7060 E Zygote  : v2
08-25 17:39:10.902  7060  7060 I libpersona: KNOX_SDCARD checking this for 1000
08-25 17:39:10.902  7060  7060 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:10.902  7060  7060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:10.902  7060  7060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:10.902  1017  1474 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7060 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 17:39:10.912  7060  7060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:10.932  7060  7060 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:10.932  7060  7060 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:10.962  7060  7060 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-25 17:39:10.962  7060  7060 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,08-25 17:39:10.962  7060  7060 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-25 17:39:10.972  7060  7060 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-25 17:39:10.972  7060  7060 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-25 17:39:10.972  7060  7060 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-25 17:39:10.982  7060  7060 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:10.982  1017  1474 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-25 17:39:10.982  1017  1474 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-25 17:39:10.982  7060  7075 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-25 17:39:10.992  1781  1781 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-25 17:39:10.992  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-25 17:39:11.002  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.002  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.002  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.002  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.012  7077  7077 E Zygote  : MountEmulatedStorage()
,08-25 17:39:11.012  7077  7077 E Zygote  : v2
08-25 17:39:11.012  7077  7077 I libpersona: KNOX_SDCARD checking this for 10121
08-25 17:39:11.012  7077  7077 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:11.012  7077  7077 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:11.012  1017  1042 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7077 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-25 17:39:11.012  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-25 17:39:11.012  7077  7077 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:11.012  7077  7077 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:11.012  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.012  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.012  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.012  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-25 17:39:11.032   303   303 I art     : Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 23.809ms
,08-25 17:39:11.042  7077  7077 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 17:39:11.042  7077  7077 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:11.052   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 16.325ms
,08-25 17:39:11.072   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 16.386ms
,08-25 17:39:11.082  7092  7092 E Zygote  : MountEmulatedStorage(),
08-25 17:39:11.082  7092  7092 E Zygote  : v2
08-25 17:39:11.082  7092  7092 I libpersona: KNOX_SDCARD checking this for 10001
08-25 17:39:11.082  7092  7092 I libpersona: KNOX_SDCARD not a persona
08-25 17:39:11.082  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7092 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 17:39:11.082  7092  7092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:11.082  7092  7092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:11.082  7092  7092 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:11.092  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-25 17:39:11.092  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.092  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.092  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.092  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.092  2464  2474 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,08-25 17:39:11.102  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-25 17:39:11.102  7092  7092 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:11.102  7092  7092 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:11.112  7107  7107 E Zygote  : MountEmulatedStorage()
,08-25 17:39:11.112  7107  7107 E Zygote  : v2
08-25 17:39:11.112  7107  7107 I libpersona: KNOX_SDCARD checking this for 10031
08-25 17:39:11.112  7107  7107 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:11.112  7107  7107 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:11.112  1017  1029 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7107 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-25 17:39:11.112  7107  7107 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:39:11.112  7077  7077 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:39:11.112  7077  7077 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-25 17:39:11.112  7077  7077 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 17:39:11.112  7107  7107 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 17:39:11.122  1781  1781 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-25 17:39:11.122  1781  1781 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-25 17:39:11.122  1781  1781 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-25 17:39:11.122  1781  1781 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-25 17:39:11.132  1781  1781 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-25 17:39:11.132  1781  1781 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-25 17:39:11.132  1017  1456 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-25 17:39:11.132  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.132  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.132  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.132  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.132  7107  7107 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 17:39:11.132  7077  7077 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
08-25 17:39:11.132  7107  7107 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:11.142   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 17:39:11.152  7122  7122 E Zygote  : MountEmulatedStorage(),
08-25 17:39:11.152  7122  7122 E Zygote  : v2
08-25 17:39:11.152  7122  7122 I libpersona: KNOX_SDCARD checking this for 10077
08-25 17:39:11.152  7122  7122 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:11.152  7122  7122 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:11.152  1017  1456 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7122 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 17:39:11.152  7122  7122 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 17:39:11.152  7122  7122 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-25 17:39:11.162  7077  7077 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-25 17:39:11.162  7077  7077 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-25 17:39:11.162  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-25 17:39:11.172  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.172  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.172  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.172  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.182  7122  7122 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:11.182  7122  7122 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:11.182  7137  7137 E Zygote  : MountEmulatedStorage()
,08-25 17:39:11.182  7137  7137 E Zygote  : v2
08-25 17:39:11.182  7137  7137 I libpersona: KNOX_SDCARD checking this for 10141
08-25 17:39:11.182  7137  7137 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:11.182  7137  7137 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:11.192  7137  7137 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:11.192  1017  1030 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7137 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-25 17:39:11.192  1017  1030 I ActivityManager: Killing 6621:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-25 17:39:11.192  7137  7137 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:11.202  7107  7107 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-25 17:39:11.212  1017  1481 I ActivityManager: Killing 6635:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-25 17:39:11.212  7137  7137 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:11.212  7137  7137 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:11.232  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-25 17:39:11.232  2798  7154 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
08-25 17:39:11.232  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.232  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.232  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.232  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.232  7137  7137 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-25 17:39:11.232  7137  7137 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:39:11.232  7137  7137 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-25 17:39:11.232  7137  7137 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-25 17:39:11.232  2798  7154 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-25 17:39:11.242  2798  7154 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-25 17:39:11.242  2798  7154 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-25 17:39:11.242  2798  7154 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-25 17:39:11.242  7155  7155 E Zygote  : MountEmulatedStorage()
08-25 17:39:11.242  7155  7155 E Zygote  : v2
08-25 17:39:11.242  7155  7155 I libpersona: KNOX_SDCARD checking this for 10032
08-25 17:39:11.242  7155  7155 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:11.242  7155  7155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:11.252  1017  1029 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7155 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 17:39:11.252  7155  7155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:11.252  7155  7155 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-25 17:39:11.262  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-25 17:39:11.262  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.262  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.262  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.262  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.282  7167  7167 E Zygote  : MountEmulatedStorage()
08-25 17:39:11.282  7167  7167 E Zygote  : v2
,08-25 17:39:11.282  7167  7167 I libpersona: KNOX_SDCARD checking this for 1000
08-25 17:39:11.282  7167  7167 I libpersona: KNOX_SDCARD not a persona
08-25 17:39:11.282  7167  7167 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-25 17:39:11.282  7167  7167 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:39:11.282  1017  1135 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7167 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 17:39:11.292  1017  1135 I ActivityManager: Killing 6658:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-25 17:39:11.292  7167  7167 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:11.292  1017  1481 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 17:39:11.302  7155  7155 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:11.302  7155  7155 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:11.312  7167  7167 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:11.312  7167  7167 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:11.322  1017  4786 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 17:39:11.372  7167  7167 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] ,
,08-25 17:39:11.372  1017  4787 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 17:39:11.382  1017  1248 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 17:39:11.382  7155  7190 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-25 17:39:11.382  7155  7190 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-25 17:39:11.392  7155  7155 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-25 17:39:11.392  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-25 17:39:11.392  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.392  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.392  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.392  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.412  7155  7190 D SPPClientService: PushLog.txt file is not deleted.,
08-25 17:39:11.412  7155  7190 D SPPClientService: PushLog.txt file is not deleted.
08-25 17:39:11.412  7155  7190 D SPPClientService: ============PushLog. stop!,
,08-25 17:39:11.412  7193  7193 E Zygote  : MountEmulatedStorage(),
,08-25 17:39:11.412  1017  1135 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7193 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 17:39:11.412  1017  1135 I ActivityManager: Killing 6079:com.android.mms/u0a41 (adj 15): empty #21
08-25 17:39:11.412  7193  7193 E Zygote  : v2,
08-25 17:39:11.412  7193  7193 I libpersona: KNOX_SDCARD checking this for 10036
08-25 17:39:11.412  7193  7193 I libpersona: KNOX_SDCARD not a persona,
,08-25 17:39:11.422  7193  7193 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-25 17:39:11.422  7193  7193 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 17:39:11.432  7193  7193 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
08-25 17:39:11.432  1017  1463 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-25 17:39:11.432  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:11.432  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0,
08-25 17:39:11.432  1017  1463 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-25 17:39:11.432  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push,
,08-25 17:39:11.452  7193  7193 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:11.452  7193  7193 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:11.472  7155  7201 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-25 17:39:11.472  1017  1474 D CountryDetector: No listener is left
,08-25 17:39:11.512  1017  1497 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-25 17:39:11.512  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.512  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.512  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.512  1017  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.522  7193  7193 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@2a74a3d0
,08-25 17:39:11.522  1017  4787 D RCPManagerService: exchangeData() failure , invalid userId,
,08-25 17:39:11.532  1017  1327 D RCPManagerService: exchangeData() failure , invalid userId,
08-25 17:39:11.532  7193  7193 I SA      : [SSP] onCreated
,08-25 17:39:11.532  7213  7213 E Zygote  : MountEmulatedStorage()
08-25 17:39:11.532  7213  7213 I libpersona: KNOX_SDCARD checking this for 10068
08-25 17:39:11.532  7213  7213 E Zygote  : v2
,08-25 17:39:11.532  7213  7213 I libpersona: KNOX_SDCARD not a persona
08-25 17:39:11.542  7213  7213 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 17:39:11.542  1017  1497 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7213 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-25 17:39:11.542  7213  7213 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:11.542  7213  7213 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-25 17:39:11.562  7193  7193 I SA      : [TPM] There is no property file
,08-25 17:39:11.562  7213  7213 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:11.562  7213  7213 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:11.562  7167  7167 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
08-25 17:39:11.562  7193  7193 I SA      : [SCU] isHaveSA() - false
,08-25 17:39:11.572  7193  7193 I SA      : [TPM] getModelProperty : null
08-25 17:39:11.572  7193  7193 I SA      : [TPM] getCSCProperty : null
,08-25 17:39:11.572  7193  7193 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-25 17:39:11.572  7193  7193 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-25 17:39:11.572  7193  7193 I SA      : [DM] TFT FEATURE: false
,08-25 17:39:11.572  7193  7193 I SA      : [DM] init START
,08-25 17:39:11.572  7167  7167 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-25 17:39:11.582  7167  7167 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:11.582  7167  7167 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-25 17:39:11.582  7167  7167 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-25 17:39:11.582  7167  7167 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-25 17:39:11.582  1017  4790 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-25 17:39:11.582  7193  7193 I SA      : [DM] This device is not a Vodafone
,08-25 17:39:11.582  1017  4790 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.582  1017  4790 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.582  1017  4790 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.582  1017  4790 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.592  1017  1463 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 17:39:11.592  7213  7213 D BadgeProvider: onCreate
,08-25 17:39:11.602  7213  7213 D BadgeProvider: DatabaseHelper
,08-25 17:39:11.602  7232  7232 E Zygote  : MountEmulatedStorage()
08-25 17:39:11.602  7232  7232 E Zygote  : v2
08-25 17:39:11.602  7232  7232 I libpersona: KNOX_SDCARD checking this for 10008
08-25 17:39:11.602  7232  7232 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:11.602  7232  7232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:11.602  7232  7232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:11.612  1017  4790 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7232 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-25 17:39:11.612  1017  4790 I ActivityManager: Killing 6572:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-25 17:39:11.612  7232  7232 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 17:39:11.632  7193  7193 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-25 17:39:11.632  7193  7193 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-25 17:39:11.632  7193  7193 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-25 17:39:11.632  7193  7193 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-25 17:39:11.632  7193  7193 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-25 17:39:11.632  7193  7193 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-25 17:39:11.632  7193  7193 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-25 17:39:11.632  1017  1480 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 17:39:11.632  7193  7193 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:39:11.632  7193  7193 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-25 17:39:11.642  1017  4789 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-25 17:39:11.642  1017  4789 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.642  1017  4789 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.642  1017  4789 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.642  1017  4789 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.642  7213  7223 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-25 17:39:11.642  1017  1463 D WifiService: setWifiEnabled: true pid=6770, uid=10171
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-25 17:39:11.642  1017  1463 W ActivityManager: Permission Denial: getCurrentUser() from pid=6770, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-25 17:39:11.642  1017  1463 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-25 17:39:11.642  1017  1463 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-25 17:39:11.642  1017  1463 D SecContentProvider2: mCursor = null
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-25 17:39:11.642  7193  7193 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-25 17:39:11.652  1017  1463 W WifiService: Failed getting userId using ActivityManagerNative
08-25 17:39:11.652  1017  1463 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6770, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 17:39:11.652  1017  1463 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 17:39:11.652  1017  1463 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 17:39:11.652  1017  1463 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 17:39:11.652  1017  1463 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 17:39:11.652  1017  1463 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-25 17:39:11.652  1017  1463 D SettingsProvider: name = wifi_on
,08-25 17:39:11.652  7193  7193 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-25 17:39:11.652  7193  7193 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-25 17:39:11.652  7193  7193 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-25 17:39:11.652  7193  7193 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-25 17:39:11.652  7193  7193 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-25 17:39:11.652  7193  7193 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-25 17:39:11.652  7232  7232 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:11.652  7232  7232 D ActivityThread: Added TimaKeyStore provider
08-25 17:39:11.652  7249  7249 E Zygote  : MountEmulatedStorage()
08-25 17:39:11.652  7249  7249 I libpersona: KNOX_SDCARD checking this for 10009
08-25 17:39:11.652  7249  7249 E Zygote  : v2
08-25 17:39:11.652  7249  7249 I libpersona: KNOX_SDCARD not a persona
08-25 17:39:11.652  7249  7249 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 17:39:11.652  1017  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-25 17:39:11.662  7249  7249 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:11.662  7249  7249 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-25 17:39:11.662  1017  4789 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7249 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-25 17:39:11.662  1017  4789 I ActivityManager: Killing 6714:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-25 17:39:11.662  1017  4789 I ActivityManager: Killing 6695:com.sec.esdk.elm/u0a90 (adj 15): empty #22
08-25 17:39:11.662  1017  1497 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-25 17:39:11.662  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-25 17:39:11.662  7193  7193 I SA      : [SCU] isHaveSA() - false
08-25 17:39:11.662  7193  7193 I SA      : support phone number id : false
08-25 17:39:11.662  7193  7193 I SA      : [DM] Supports Ref Jpn : true
08-25 17:39:11.662  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:11.662  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:11.662  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-25 17:39:11.662  7193  7193 I SA      : [DM] init END
,08-25 17:39:11.672  7193  7193 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-25 17:39:11.672  7193  7193 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-25 17:39:11.672  7193  7193 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-25 17:39:11.682  7249  7249 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:11.682  1017  4787 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
08-25 17:39:11.682  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.682  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.682  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:11.682  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:11.682  7249  7249 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:11.692  7266  7266 E Zygote  : MountEmulatedStorage()
08-25 17:39:11.692  7266  7266 I libpersona: KNOX_SDCARD checking this for 10110
08-25 17:39:11.692  7266  7266 E Zygote  : v2
08-25 17:39:11.692  7266  7266 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:11.692  7266  7266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:11.702  7213  7227 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-25 17:39:11.702  7213  7227 D BadgeProvider: sendNotify, [notify] : null
08-25 17:39:11.702  7266  7266 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:11.702  7213  7227 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,08-25 17:39:11.702  7213  7227 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-25 17:39:11.702  7213  7227 D BadgeProvider: update, [UpdateCount] : 1
08-25 17:39:11.702  1482  1482 D Launcher.Model: reloadBadges entered.
08-25 17:39:11.702  7266  7266 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 17:39:11.702  1017  4787 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7266 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 17:39:11.732   303   303 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 721us total 24.867ms
,08-25 17:39:11.732  1017  4786 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-25 17:39:11.732  1017  4786 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-25 17:39:11.742  1017  4786 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:11.742  1017  4786 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:11.742  1017  4786 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 17:39:11.742  7266  7266 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 17:39:11.742  7266  7266 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:11.752   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 18.432ms
08-25 17:39:11.752  7017  7265 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-25 17:39:11.772   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 2.177ms total 24.495ms
08-25 17:39:11.772  7193  7193 I SA      : [SLFUCHKMGR] constructor called
,08-25 17:39:11.782  1017  1497 I ActivityManager: Killing 6530:com.android.calendar/u0a131 (adj 15): empty #21
,08-25 17:39:11.812  7193  7193 I SA      : [TPMU]  strSIMState ,	:SIM_STATE_ABSENT
08-25 17:39:11.812  7193  7193 I SA      : [OR] == isSIMCardReady false ==
,08-25 17:39:11.832  7193  7193 I SA      : [SCU] == networkStateCheck == false,
08-25 17:39:11.832  7193  7193 I SA      : [OR] onReceive END
,08-25 17:39:11.832  1017  1029 I ActivityManager: Killing 6680:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-25 17:39:11.842  1017  1029 I ActivityManager: Killing 6042:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-25 17:39:11.842  1017  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 17:39:11.842  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-25 17:39:11.842  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:11.842  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:11.842  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:11.852  1225  1225 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:11.862  1017  1327 I ActivityManager: Killing 5889:com.android.vending/u0a26 (adj 15): empty #21
,08-25 17:39:11.872  2913  2913 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Aug 25 17:39:11 GMT+02:00 2016
08-25 17:39:11.872  4732  7283 I iu.SyncManager: SYNC; picasa accounts
,08-25 17:39:11.872  1017  1480 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-25 17:39:11.872  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-25 17:39:11.872  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:11.872  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:11.872  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-25 17:39:11.882  4732  4732 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-25 17:39:11.882  2913  2913 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-25 17:39:11.892  2913  2913 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-25 17:39:11.892  2913  2913 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-25 17:39:11.902  2913  2913 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-25 17:39:11.902  2913  7284 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-25 17:39:11.902  2913  7284 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-25 17:39:11.912  2913  7284 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-25 17:39:11.912  2913  7284 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-25 17:39:11.912  2913  2913 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-25 17:39:11.942  1017  4789 I ActivityManager: Killing 6967:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-25 17:39:11.972  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-25 17:39:11.972  1017  1761 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-25 17:39:11.972  1017  1248 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-25 17:39:11.972  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-25 17:39:12.002  1017  4789 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 17:39:12.102   288   288 E SMD     : DCD OFF
,08-25 17:39:12.112  1017  1044 D Tethering: interfaceAdded wlan0
,08-25 17:39:12.122  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 17:39:12.122  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-25 17:39:12.122  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:12.122  1017  1130 E Tethering: No numeric data
,08-25 17:39:12.132  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-25 17:39:12.132  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 17:39:12.132  1017  1130 D Tethering: clearTetheredNotification()
08-25 17:39:12.132  1017  1130 D Tethering: InitialState.processMessage what=4,
08-25 17:39:12.132   278   987 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-25 17:39:12.132  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:12.132   278   987 D SoftapController: Softap fwReload - Ok
08-25 17:39:12.132  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-25 17:39:12.132  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 17:39:12.132  1017  1124 V NetworkStats: performPollLocked() took 5ms
,08-25 17:39:12.132  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:12.132  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 17:39:12.132  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 17:39:12.132  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-25 17:39:12.132   278   987 D CommandListener: Setting iface cfg
08-25 17:39:12.132   278   987 D CommandListener: Trying to bring down wlan0
08-25 17:39:12.132  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 17:39:12.132  1179  1179 D HotspotTile: updateTetherState():false, false
08-25 17:39:12.132  1017  1130 E Tethering: No numeric data
,08-25 17:39:12.142   278   987 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:39:12.142  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 17:39:12.142  1017  1130 D Tethering: clearTetheredNotification()
08-25 17:39:12.142  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:12.142  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:12.142   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 17:39:12.142  1017  1044 D Tethering: interfaceAdded p2p0
08-25 17:39:12.142  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 17:39:12.142  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
08-25 17:39:12.142  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 17:39:12.142  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:12.142  1179  1179 D HotspotTile: updateTetherState():false, false
08-25 17:39:12.142  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:12.142  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 17:39:12.142  1017  1127 E WifiHW  : supplicant_name : p2p_supplicant
08-25 17:39:12.142   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-25 17:39:12.142   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 17:39:12.142  7266  7295 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-25 17:39:12.152  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:12.152  1017  1124 V NetworkStats: performPollLocked() took 6ms
,08-25 17:39:12.152   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-25 17:39:12.152   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 17:39:12.152  7266  7295 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-25 17:39:12.152  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:12.152  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:12.172   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-25 17:39:12.172   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 17:39:12.172  7266  7298 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-25 17:39:12.172  7266  7266 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 17:39:12.172  7266  7266 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 17:39:12.172  7266  7266 I GAv4    :   adb logcat -s GAv4
08-25 17:39:12.172   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-25 17:39:12.172   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 17:39:12.172  7266  7298 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-25 17:39:12.202  7266  7266 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
08-25 17:39:12.202  1017  1248 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 17:39:12.212  7266  7266 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 17:39:12.222  7266  7300 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 17:39:12.222  7297  7297 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-25 17:39:12.222  7297  7297 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 17:39:12.222  7297  7297 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-25 17:39:12.242  1017  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-25 17:39:12.252  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:12.252  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 17:39:12.252  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:12.252  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:12.252  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:12.252  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:12.252  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:12.252  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-25 17:39:12.252  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:39:12.252  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 17:39:12.262  1179  1179 D HotspotTile: onReceive : 2, 0
,08-25 17:39:12.262  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:12.262  3293  3293 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:39:12.262  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-25 17:39:12.282  7297  7297 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-25 17:39:12.282   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7297
08-25 17:39:12.282   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-25 17:39:12.282  7297  7297 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-25 17:39:12.282  7297  7297 I wpa_supplicant: ssSupport state is = 1
08-25 17:39:12.282  7297  7297 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-25 17:39:12.282  7297  7297 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-25 17:39:12.282   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7297
08-25 17:39:12.282   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-25 17:39:12.462   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-25 17:39:12.472  7297  7297 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-25 17:39:12.492  1017  4787 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:12.492  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:12.492  1017  4787 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:12.492  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-25 17:39:12.512  7266  7266 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-25 17:39:12.532  7297  7297 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 17:39:12.532  7297  7297 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 17:39:12.532  7266  7266 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 8422-8424),
08-25 17:39:12.532  7266  7266 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-25 17:39:12.542  7266  7266 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34d135cb},
08-25 17:39:12.542  7266  7266 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-25 17:39:12.542  7266  7266 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 17:39:12.542  7297  7297 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-25 17:39:12.542   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7297
08-25 17:39:12.542   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-25 17:39:12.542  7297  7297 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 17:39:12.542  7297  7297 I wpa_supplicant: ssSupport state is = 1,
08-25 17:39:12.542  7297  7297 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 17:39:12.542  7297  7297 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-25 17:39:12.542  7297  7297 E wpa_supplicant: SIM READ ERROR
08-25 17:39:12.542  7297  7297 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 17:39:12.542  7297  7297 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 17:39:12.542  7297  7297 E wpa_supplicant: SIM READ ERROR
,08-25 17:39:12.552  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:12.542  7297  7297 I wpa_supplicant: Blacklist: Clear (all) 
08-25 17:39:12.542  7297  7297 I wpa_supplicant: wpa_default_ap_write_once
08-25 17:39:12.542  7297  7297 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 17:39:12.542  7297  7297 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 17:39:12.542  7297  7297 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-25 17:39:12.542  7297  7297 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-25 17:39:12.542  7297  7297 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 17:39:12.542  7297  7297 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 17:39:12.552  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:12.552  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:12.562  7266  7266 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
08-25 17:39:12.562  7266  7266 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 17:39:12.562  7266  7266 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-25 17:39:12.582  7266  7266 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 17:39:12.582  7266  7266 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 17:39:12.582  7266  7266 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 17:39:12.582  7266  7266 I Adreno-EGL: Local Branch: 
08-25 17:39:12.582  7266  7266 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 17:39:12.582  7266  7266 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 17:39:12.582  7266  7266 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 17:39:12.642  7266  7330 W cr.media: Requires BLUETOOTH permission,
08-25 17:39:12.642  7266  7266 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 17:39:12.652  7266  7266 I NSApplication: Starting up...
,08-25 17:39:12.652  1017  1474 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 17:39:12.652  1017  1135 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 17:39:12.662  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-25 17:39:12.662  7297  7297 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-25 17:39:12.662  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:12.662  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:12.662  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:12.662  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:12.672  7335  7335 E Zygote  : MountEmulatedStorage(),
08-25 17:39:12.672  7335  7335 E Zygote  : v2
08-25 17:39:12.672  7335  7335 I libpersona: KNOX_SDCARD checking this for 10117
,08-25 17:39:12.672  7335  7335 I libpersona: KNOX_SDCARD not a persona
08-25 17:39:12.672  1017  1030 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7335 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-25 17:39:12.672  7335  7335 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:12.672  1017  1030 I ActivityManager: Killing 6999:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-25 17:39:12.682  7335  7335 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:12.682  7335  7335 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 17:39:12.692  7335  7335 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:12.692  7335  7335 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:12.712  7335  7335 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 17:39:12.862  7297  7297 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-25 17:39:12.862  7297  7297 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 17:39:12.872  7297  7297 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-25 17:39:12.872   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7297
08-25 17:39:12.872   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-25 17:39:12.872  7297  7297 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 17:39:12.872  7297  7297 I wpa_supplicant: ssSupport state is = 1
,08-25 17:39:12.872  7297  7297 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 17:39:12.872  7297  7297 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 17:39:12.882  7297  7297 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-25 17:39:12.892   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7297
08-25 17:39:12.892   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-25 17:39:12.892  7297  7297 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 17:39:12.892  7297  7297 I wpa_supplicant: ssSupport state is = 1
08-25 17:39:12.892  7297  7297 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 17:39:12.892  7297  7297 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 17:39:12.892  7297  7297 E wpa_supplicant: SIM READ ERROR
08-25 17:39:12.892  7297  7297 I wpa_supplicant: wpa_default_ap_write_once
08-25 17:39:12.892  7297  7297 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-25 17:39:12.892  7297  7297 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 17:39:12.892  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 17:39:12.892  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 17:39:12.892  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-25 17:39:12.892  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 17:39:12.892  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 17:39:12.892  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-25 17:39:12.972  7297  7297 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-25 17:39:12.972  7297  7297 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-25 17:39:13.012  7297  7297 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-25 17:39:13.012  7297  7297 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-25 17:39:13.012  7297  7297 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 17:39:13.022  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-25 17:39:13.022  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 17:39:13.022  7297  7297 I wpa_supplicant: HOTSPOT20_ENABLE called
08-25 17:39:13.022  7297  7297 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 17:39:13.022  7297  7297 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 17:39:13.022  7297  7297 E wpa_supplicant: SIM READ ERROR
08-25 17:39:13.022  7297  7297 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 17:39:13.052  7297  7297 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-25 17:39:13.092  7297  7297 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 17:39:13.092  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 17:39:13.092  1017  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-25 17:39:13.102  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-25 17:39:13.102  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:13.102  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:13.102  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:13.102  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 17:39:13.102  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:13.102  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:13.102  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-25 17:39:13.102  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:13.102  1179  1179 D HotspotTile: onReceive : 3, 0
,08-25 17:39:13.102  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:13.102  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:13.102  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:13.102  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:13.102  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:13.102  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:13.102  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:13.102  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:13.102  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:13.102  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:13.102  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:13.112  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 17:39:13.112  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 17:39:13.112  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-25 17:39:13.112  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:13.112  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:13.112  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:13.112  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:13.112  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:13.112  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:13.112  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:13.112  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:13.112  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:13.112  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:13.112  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:13.112  3293  3293 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:39:13.112  1017  1127 E WifiConfigStore: Not a HS20
,08-25 17:39:13.112  1017  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 17:39:13.112  1017  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-25 17:39:13.122  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-25 17:39:13.122  7297  7297 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-25 17:39:13.122  7297  7297 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 17:39:13.122  7297  7297 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 17:39:13.122  7297  7297 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 17:39:13.122  7297  7297 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-25 17:39:13.122  7297  7297 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-25 17:39:13.122  7297  7297 I wpa_supplicant: First Scan Start
,08-25 17:39:13.122  7297  7297 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 17:39:13.122  1017  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-25 17:39:13.122  1017  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 17:39:13.122  1017  1127 I WifiNative-HAL: startHal
08-25 17:39:13.122  1017  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d56688c
08-25 17:39:13.122  1017  1127 I WifiNative-HAL: Could not start hal
,08-25 17:39:13.122  7017  7017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 17:39:13.122  1017  1127 E WifiNative-wlan0: do suspend true
,08-25 17:39:13.132  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-25 17:39:13.132  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-25 17:39:13.132  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 17:39:13.132  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:39:13.132  1017  1150 I WifiNative-HAL: startHal
08-25 17:39:13.132   278   987 D CommandListener: Setting iface cfg
08-25 17:39:13.132   278   987 D CommandListener: Trying to bring up p2p0
,08-25 17:39:13.132  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9ea249bc
08-25 17:39:13.132  1017  1150 I WifiNative-HAL: Could not start hal
08-25 17:39:13.132  1017  1150 E WifiScanningService: could not start HAL
,08-25 17:39:13.132  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 17:39:13.132  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-25 17:39:13.132  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 17:39:13.132  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 17:39:13.132  1017  1127 E WifiNative-wlan0: invaild command id : 215
08-25 17:39:13.132  1017  1151 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:39:13.132  1017  1126 D WifiP2pService: P2pEnablingState
,08-25 17:39:13.132  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-25 17:39:13.132  1017  1126 D WifiP2pService: P2p socket connection successful
08-25 17:39:13.132  1017  1126 D WifiP2pService: P2pEnabledState
,08-25 17:39:13.132  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-25 17:39:13.132  1017  1129 E ConnectivityService: updateNetworkInfo()
08-25 17:39:13.132  7297  7297 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-25 17:39:13.132  7297  7297 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 17:39:13.132  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 17:39:13.142  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-25 17:39:13.142  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 17:39:13.142  1017  1047 D WifiDisplayController: disconnect
08-25 17:39:13.142  1017  1047 D WifiDisplayController: updateConnection
08-25 17:39:13.142  7297  7297 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-25 17:39:13.142  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 17:39:13.142  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 17:39:13.142  1017  1127 E WifiStateMachine: Failed to set frequency band 0
,08-25 17:39:13.142  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 17:39:13.142  1017  1127 D SecContentProvider2: mCursor = null
08-25 17:39:13.142   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-25 17:39:13.142  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 17:39:13.142  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:13.142  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:39:13.142  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress
08-25 17:39:13.142  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-25 17:39:13.142  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 17:39:13.142  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-25 17:39:13.142  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 17:39:13.142  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 17:39:13.142  1017  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 17:39:13.152  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 17:39:13.152  1017  1126 D WifiP2pService: DeviceAddress: 0a:76:28
,08-25 17:39:13.152  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  secondary type: null
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  wps: 0
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  grpcapab: 0
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  devcapab: 0
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  status: 3
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  wfdInfo: null
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-25 17:39:13.152  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-25 17:39:13.162  1017  4787 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-25 17:39:13.162  1017  4787 I ActivityManager: Killing 6909:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-25 17:39:13.162  1017  1456 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:13.162  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:13.172  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:13.172  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:13.172  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:13.172  1620  1620 I Hs20UtilService: Starting #12
,08-25 17:39:13.172  1620  1652 I Hs20UtilService: Message received 5011
,08-25 17:39:13.172  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 17:39:13.172  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 17:39:13.172  6587  6587 D SecurityLogAgent: StateMachine : Current State = 1
08-25 17:39:13.172  6587  6587 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 17:39:13.182  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 17:39:13.182  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:13.182  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:13.182  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:13.182  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:13.182  1620  1620 I Hs20UtilService: Starting #13
,08-25 17:39:13.182  1620  1652 I Hs20UtilService: Message received 5011
,08-25 17:39:13.192  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-25 17:39:13.192  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 17:39:13.192  1017  1127 E WifiNative-wlan0: invaild command id : 215
,08-25 17:39:13.192  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-25 17:39:13.192  1017  1126 D WifiP2pService: InactiveState
08-25 17:39:13.192  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-25 17:39:13.192  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 17:39:13.192  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 17:39:13.192  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 17:39:13.192  6587  6587 D SecurityLogAgent: StateMachine : Current State = 1
08-25 17:39:13.192  6587  6587 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-25 17:39:13.192  7297  7297 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 17:39:13.192  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
08-25 17:39:13.192  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 17:39:13.202  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 17:39:13.202  3293  3293 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 17:39:13.202  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 17:39:13.212  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 17:39:13.212  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-25 17:39:13.212  3293  3293 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 17:39:13.212  3293  3905 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 17:39:13.212  1017  1327 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-25 17:39:13.212  1017  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:13.212  1017  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:13.212  1017  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:13.212  1017  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:13.222  7362  7362 E Zygote  : MountEmulatedStorage()
,08-25 17:39:13.232  7362  7362 E Zygote  : v2
08-25 17:39:13.232  7362  7362 I libpersona: KNOX_SDCARD checking this for 10064
08-25 17:39:13.232  7362  7362 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:13.232  7362  7362 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:13.232  7362  7362 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:39:13.232  1017  1327 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7362 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 17:39:13.232  7362  7362 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:13.252  7362  7362 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:13.252  7362  7362 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:13.262  7362  7362 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-25 17:39:13.272  7362  7362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 17:39:13.282  7362  7362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 17:39:13.302  7362  7362 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 17:39:13.302  1017  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-25 17:39:13.302  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:13.302  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:13.302  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:13.302  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:13.322  7378  7378 E Zygote  : MountEmulatedStorage(),
08-25 17:39:13.322  7378  7378 E Zygote  : v2
08-25 17:39:13.322  7378  7378 I libpersona: KNOX_SDCARD checking this for 10065
08-25 17:39:13.322  7378  7378 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:13.322  7378  7378 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-25 17:39:13.322  1017  1481 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7378 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 17:39:13.322  1017  1481 I ActivityManager: Killing 7043:com.android.bluetooth/1002 (adj 15): empty #21
08-25 17:39:13.322  7378  7378 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:13.322  7378  7378 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:13.342  7378  7378 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:13.352  7378  7378 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:13.362  7378  7378 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 17:39:13.372  1017  1030 I ActivityManager: Killing 6928:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-25 17:39:14.382  7297  7297 I wpa_supplicant: nl80211: Received scan results (35 BSSes)
08-25 17:39:14.382  7297  7297 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 17:39:14.382  7297  7297 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-25 17:39:14.392  7297  7297 I wpa_supplicant: Trying to associate with  'G700'
,08-25 17:39:14.392  7297  7297 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-25 17:39:14.392  1017  7357 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-25 17:39:14.392  7297  7297 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-25 17:39:14.412  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 17:39:14.412  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:14.502  7297  7297 E wpa_supplicant: Cmd 35605 not handled
,08-25 17:39:14.502  7297  7297 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 17:39:14.502  7297  7297 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-25 17:39:14.502  7297  7297 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-25 17:39:14.502  7297  7297 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-25 17:39:14.502  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:14.502  7297  7297 I wpa_supplicant: Associated with F4.99.3E
08-25 17:39:14.502  7297  7297 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 17:39:14.502  7297  7297 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-25 17:39:14.502  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:14.502  7297  7297 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-25 17:39:14.502  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:14.512  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 17:39:14.512  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:14.512  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-25 17:39:14.512  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 17:39:14.512  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:14.512  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:14.512  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 17:39:14.512  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 17:39:14.512  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-25 17:39:14.522  7297  7297 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 17:39:14.522  1017  1130 E Tethering: No numeric data
08-25 17:39:14.522  7297  7297 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-25 17:39:14.522  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 17:39:14.522  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 17:39:14.522  1017  1127 D SecContentProvider2: mCursor = null
08-25 17:39:14.522  1017  1130 D Tethering: clearTetheredNotification()
08-25 17:39:14.522  7297  7297 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-25 17:39:14.522  7297  7297 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-25 17:39:14.522  7297  7297 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 17:39:14.522  7297  7297 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-25 17:39:14.522  7297  7297 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-25 17:39:14.522  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 17:39:14.522  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:14.522  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-25 17:39:14.522  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:14.522  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 17:39:14.522  1179  1179 D HotspotTile: updateTetherState():false, false
08-25 17:39:14.522  7297  7297 I wpa_supplicant: Blacklist: Clear (temp) 
08-25 17:39:14.522  7297  7297 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-25 17:39:14.532  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 17:39:14.532  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 17:39:14.532  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-25 17:39:14.532  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 17:39:14.532  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:14.532  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:14.532  1017  1124 V NetworkStats: performPollLocked() took 11ms,
,08-25 17:39:14.542  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 17:39:14.542  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:14.542  1017  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-25 17:39:14.542  1017  1127 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-25 17:39:14.552  1017  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-25 17:39:14.552  1017  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-25 17:39:14.552  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:39:14.552  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:14.552  1017  1129 E ConnectivityService: updateNetworkInfo()
08-25 17:39:14.552  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 17:39:14.552  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.552  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.552  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.552  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.552  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:39:14.552  1017  1248 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:14.552  1017  1248 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:14.552  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:14.552  1017  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:14.552  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:14.562  1620  1620 I Hs20UtilService: Starting #14
08-25 17:39:14.562  1620  1652 I Hs20UtilService: Message received 5007
,08-25 17:39:14.562  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 17:39:14.562  3293  3293 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 17:39:14.562  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 17:39:14.562  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 17:39:14.562  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 17:39:14.562  3293  3293 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 17:39:14.562  3293  3905 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 17:39:14.572  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-25 17:39:14.582   278   987 D CommandListener: Setting iface cfg,
08-25 17:39:14.582  1017  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,08-25 17:39:14.582  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 17:39:14.582  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:14.592  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:14.592  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 17:39:14.592  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:14.592  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:14.602  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.602  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-25 17:39:14.602  1017  1127 E WifiNative-wlan0: do suspend false
,08-25 17:39:14.602  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 17:39:14.602  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
08-25 17:39:14.602  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:14.602  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 17:39:14.662  1017  1135 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-25 17:39:14.662  1017  1135 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 17:39:14.662  1017  1135 D SecContentProvider2: mCursor = null
,08-25 17:39:14.662  1017  1135 D WifiService: setWifiEnabled: false pid=6770, uid=10171
,08-25 17:39:14.662  1017  1135 D SettingsProvider: name = wifi_on
,08-25 17:39:14.672  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-25 17:39:14.682  1017  1127 E WifiNative-wlan0: do suspend true,
,08-25 17:39:14.702  1017  1126 D WifiP2pService: InactiveState{ what=143375 },
08-25 17:39:14.702  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 17:39:14.702   278   987 D CommandListener: Clearing all IP addresses on wlan0
,08-25 17:39:14.712  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 17:39:14.712  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 17:39:14.712  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:14.712  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.712  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.712  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:14.712  1017  1129 E ConnectivityService: updateNetworkInfo()
08-25 17:39:14.712  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:39:14.712  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-25 17:39:14.712  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-25 17:39:14.712   278   987 E Netd    : no such netId 503
08-25 17:39:14.722  1017  1126 D WifiP2pService: InactiveState{ what=131204 }
08-25 17:39:14.722  1017  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-25 17:39:14.722  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-25 17:39:14.722  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 17:39:14.722  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-25 17:39:14.732  1017  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
,08-25 17:39:14.732  1017  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-25 17:39:14.732  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 17:39:14.732  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 17:39:14.732  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.732  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.732  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.732  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:14.742  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 17:39:14.742  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:39:14.742  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-25 17:39:14.742  1017  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:39:14.742  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:14.742  1017  1129 V NetworkStats: updateIfacesLocked()
08-25 17:39:14.742  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-25 17:39:14.742  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:14.742  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 17:39:14.742  1017  1129 V NetworkStats: performPollLocked() took 4ms
08-25 17:39:14.742  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:14.752  1017  7393 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler },
08-25 17:39:14.752  1017  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-25 17:39:14.752  1017  7393 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-25 17:39:14.752  1017  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-25 17:39:14.752  1017  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-25 17:39:14.752  1017  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-25 17:39:14.752  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-25 17:39:14.752  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,08-25 17:39:14.752  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 17:39:14.752  1017  1047 D WifiDisplayAdapter: onP2pDisconnected,
08-25 17:39:14.752  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 17:39:14.752  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 17:39:14.752  1017  1129 E ConnectivityService: updateNetworkInfo()
08-25 17:39:14.752  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null,
08-25 17:39:14.752  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-25 17:39:14.752  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 17:39:14.762  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-25 17:39:14.762  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-25 17:39:14.762  1017  1047 D WifiDisplayController: disconnect
08-25 17:39:14.762  1017  1047 D WifiDisplayController: updateConnection
,08-25 17:39:14.762  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 17:39:14.762  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 17:39:14.762  1017  1126 D WifiP2pService: P2pDisablingState
08-25 17:39:14.762  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-25 17:39:14.762  1017  1126 D WifiP2pService: p2p socket connection lost
08-25 17:39:14.762  1017  1126 D WifiP2pService: P2pDisabledState
,08-25 17:39:14.762  1017  1127 E WifiNative-wlan0: do suspend true
,08-25 17:39:14.762  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 17:39:14.762  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-25 17:39:14.762  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-25 17:39:14.762  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 17:39:14.762  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 17:39:14.762  1017  1474 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:14.762  1017  1761 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 17:39:14.762  1017  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:14.762  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 17:39:14.772  1017  1474 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:14.772  1017  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:14.772  1017  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:14.772  1620  1620 I Hs20UtilService: Starting #15
,08-25 17:39:14.772  1620  1652 I Hs20UtilService: Message received 5007
,08-25 17:39:14.772  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 17:39:14.772  3293  3293 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 17:39:14.772  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 17:39:14.772  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 17:39:14.772  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-25 17:39:14.782  3293  3293 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 17:39:14.782  3293  3905 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 17:39:14.782  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 17:39:14.782  3293  3293 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 17:39:14.782  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 17:39:14.782  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 17:39:14.792  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 17:39:14.792  3293  3293 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 17:39:14.792  3293  3905 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 17:39:14.792  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-25 17:39:14.792  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-25 17:39:14.792  7362  7362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 17:39:14.792  7362  7362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-25 17:39:14.802  7362  7362 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 17:39:14.802  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:14.802  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 17:39:14.802  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:14.802  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:14.802  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:14.802  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:14.802   278   987 D CommandListener: Clearing all IP addresses on wlan0
,08-25 17:39:14.812  7378  7378 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 17:39:14.812  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 17:39:14.812  7297  7297 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-25 17:39:14.822  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-25 17:39:14.822  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 17:39:14.822  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.822  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.822  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.822  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:14.822  7397  7397 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 17:39:14.832  1017  1497 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:14.832  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:14.832  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:14.832  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:14.832  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:14.832  7397  7397 I dhcpcd  : version 5.5.6 starting
,08-25 17:39:14.832  1620  1620 I Hs20UtilService: Starting #16
,08-25 17:39:14.832  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 17:39:14.832  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:14.832  1620  1652 I Hs20UtilService: Message received 5007
,08-25 17:39:14.832  7397  7397 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 17:39:14.842  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 17:39:14.842  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:14.842  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 17:39:14.842  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 17:39:14.842  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.842  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.842  1179  1179 D HotspotTile: onReceive : 0, 0
08-25 17:39:14.842  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:14.842  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:14.842  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:14.842  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-25 17:39:14.842  3293  3293 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:39:14.842  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:14.842  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:14.842  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-25 17:39:14.842  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:14.842  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:14.842  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:14.842  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:14.842  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:14.842  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:14.842  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:14.842  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:14.852  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-25 17:39:14.852  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:14.852  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:14.852  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:14.852  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:14.852  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:14.852  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:14.852  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:14.852  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:14.852  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:14.852  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:14.852  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 17:39:14.852  3293  3293 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 17:39:14.852  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-25 17:39:14.852  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 17:39:14.852  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 17:39:14.852  3293  3293 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 17:39:14.852  3293  3905 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 17:39:14.862  1017  1761 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:14.862  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:14.872  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:14.872  1017  1761 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:14.872  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 17:39:14.872  1620  1620 I Hs20UtilService: Starting #17
,08-25 17:39:14.872  1620  1652 I Hs20UtilService: Message received 5011
,08-25 17:39:14.872  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 17:39:14.872  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 17:39:14.872  6587  6587 D SecurityLogAgent: StateMachine : Current State = 1
08-25 17:39:14.872  6587  6587 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 17:39:14.902  7397  7397 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-25 17:39:14.902  7397  7397 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
08-25 17:39:14.902  7397  7397 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-25 17:39:14.902  7397  7397 I dhcpcd  : bssid match,
,08-25 17:39:14.902  7397  7397 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-25 17:39:15.062  7297  7297 I wpa_supplicant: Blacklist: Clear (all) ,
,08-25 17:39:15.072  7397  7397 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-25 17:39:15.112   288   288 E SMD     : DCD OFF
,08-25 17:39:15.122  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 17:39:15.122  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-25 17:39:15.122  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-25 17:39:15.122  7297  7297 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-25 17:39:15.152  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 17:39:15.152  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 17:39:15.152  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-25 17:39:15.152  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-25 17:39:15.152  1017  1130 D Tethering: InitialState.processMessage what=4,
08-25 17:39:15.152  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:15.152  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-25 17:39:15.152  1017  1130 E Tethering: No numeric data
08-25 17:39:15.152  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 17:39:15.152  1017  1130 D Tethering: clearTetheredNotification()
08-25 17:39:15.162  7297  7297 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-25 17:39:15.162  7297  7297 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-25 17:39:15.162  7297  7297 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e,
08-25 17:39:15.162  7297  7297 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-25 17:39:15.162  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:15.162  7297  7297 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-25 17:39:15.162  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-25 17:39:15.162  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:15.162  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-25 17:39:15.162  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:15.162  1179  1179 D HotspotTile: updateTetherState():false, false
08-25 17:39:15.162  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:15.162  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:15.162  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 17:39:15.172  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:15.172  1017  1124 V NetworkStats: performPollLocked() took 7ms
,08-25 17:39:15.172  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:15.172  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:15.212  7397  7397 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-25 17:39:15.452  7297  7297 I wpa_supplicant: Blacklist: Clear (all) ,
,08-25 17:39:15.502  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 17:39:15.502  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:15.502  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:15.512  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 17:39:15.512  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:15.512  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:15.512  7297  7297 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-25 17:39:15.622  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-25 17:39:15.622  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 17:39:15.632  7017  7017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-25 17:39:15.632  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:15.632  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-25 17:39:15.632  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:15.632  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:15.642  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 17:39:15.642  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:15.642  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:15.642  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 17:39:15.642  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:15.642  1179  1179 D HotspotTile: onReceive : 1, 0,
08-25 17:39:15.642  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-25 17:39:15.642  1993  2157 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 17:39:15.642  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:15.642  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:15.652  3293  3293 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:39:15.652  1017  4786 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 17:39:15.652  1017  4786 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:15.652  1017  4786 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:15.652  1017  4786 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:15.652  1017  4786 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:15.652  1620  1620 I Hs20UtilService: Starting #18
,08-25 17:39:15.652  1620  1652 I Hs20UtilService: Message received 5011
,08-25 17:39:15.652  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 17:39:15.662  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-25 17:39:15.662  6587  6587 D SecurityLogAgent: StateMachine : Current State = 1
08-25 17:39:15.662  6587  6587 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 17:39:15.902  1017  1135 I ActivityManager: Killing 7060:com.sec.pcw.device/1000 (adj 15): empty #21,
,08-25 17:39:16.302   278   981 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-25 17:39:16.302  1017  1044 D Tethering: interfaceRemoved wlan0
,08-25 17:39:16.302  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-25 17:39:16.472  1017  1044 D Tethering: interfaceRemoved p2p0
,08-25 17:39:16.472  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-25 17:39:17.212  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-25 17:39:17.672  6770  6823 D BluetoothAdapter: enable(),
,08-25 17:39:17.672  1017  4789 W ActivityManager: Permission Denial: getCurrentUser() from pid=6770, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-25 17:39:17.672  1017  4789 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-25 17:39:17.672  1017  4789 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6770, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 17:39:17.672  1017  4789 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 17:39:17.672  1017  4789 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
,08-25 17:39:17.672  1017  4789 W BluetoothManagerService: 	,at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688),
08-25 17:39:17.672  1017  4789 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-25 17:39:17.672  1017  4789 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-25 17:39:17.672  1017  4789 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-25 17:39:17.672  1017  4789 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 17:39:17.682  1017  4789 D SettingsProvider: name = bluetooth_on
,08-25 17:39:17.682  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-25 17:39:17.682  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 17:39:17.692  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-25 17:39:17.692  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-25 17:39:17.692  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-25 17:39:17.692  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:17.692  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:17.692  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-25 17:39:17.702  7428  7428 E Zygote  : MountEmulatedStorage()
08-25 17:39:17.702  7428  7428 E Zygote  : v2
08-25 17:39:17.702  7428  7428 I libpersona: KNOX_SDCARD checking this for 1002
08-25 17:39:17.702  7428  7428 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:17.712  7428  7428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:17.712  7428  7428 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:17.712  1017  1046 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7428 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-25 17:39:17.712  7428  7428 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:17.742  7428  7428 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:17.742  7428  7428 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:17.762  7428  7428 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 17:39:17.762  7428  7428 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 17:39:17.792  7428  7428 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-25 17:39:17.832  7428  7428 D BtSettings.ProfileConfig: Adding GattService
,08-25 17:39:17.832  7428  7428 D BtSettings.ProfileConfig: Adding HeadsetService
,08-25 17:39:17.832  7428  7428 D BtSettings.ProfileConfig: Adding A2dpService
,08-25 17:39:17.832  7428  7428 D BtSettings.ProfileConfig: Adding HidService
,08-25 17:39:17.832  7428  7428 D BtSettings.ProfileConfig: Adding HealthService
,08-25 17:39:17.832  7428  7428 D BtSettings.ProfileConfig: Adding PanService
,08-25 17:39:17.832  7428  7428 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-25 17:39:17.832  7428  7428 D BtSettings.ProfileConfig: Adding SapService
,08-25 17:39:17.832  7428  7428 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-25 17:39:17.842  7428  7428 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-25 17:39:17.842  7428  7428 D BtSettings.ProfileConfig: Adding SapClientService
,08-25 17:39:17.842  7428  7428 D BtSettings.ProfileConfig: Adding HidDevService
,08-25 17:39:17.842  7428  7428 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-25 17:39:17.842  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-25 17:39:17.842  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:17.842  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 17:39:17.842  1017  1030 D SettingsProvider: selectionArgs: false
08-25 17:39:17.842  1017  1030 D SettingsProvider: selectionArgs: 1002
,08-25 17:39:17.842  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.842  1017  1030 D SettingsProvider: ret = -1
,08-25 17:39:17.842  1017  1761 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService,
08-25 17:39:17.842  1017  1761 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:17.842  1017  1761 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:17.842  1017  1761 D SettingsProvider: selectionArgs: false,
08-25 17:39:17.842  1017  1761 D SettingsProvider: selectionArgs: 1002
08-25 17:39:17.842  1017  1761 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.842  1017  1761 D SettingsProvider: ret = -1
08-25 17:39:17.842  1017  4790 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-25 17:39:17.842  1017  4790 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:17.842  1017  4790 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:17.842  1017  4790 D SettingsProvider: selectionArgs: false
08-25 17:39:17.842  1017  4790 D SettingsProvider: selectionArgs: 1002
08-25 17:39:17.842  1017  4790 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.842  1017  4790 D SettingsProvider: ret = -1
08-25 17:39:17.842  1017  1456 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-25 17:39:17.842  1017  1456 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:17.842  1017  1456 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:17.842  1017  1456 D SettingsProvider: selectionArgs: false
08-25 17:39:17.842  1017  1456 D SettingsProvider: selectionArgs: 1002
08-25 17:39:17.842  1017  1456 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.842  1017  1456 D SettingsProvider: ret = -1
,08-25 17:39:17.852  1017  4786 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-25 17:39:17.852  1017  4786 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:17.852  1017  4786 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
,08-25 17:39:17.852  1017  4786 D SettingsProvider: selectionArgs: false
08-25 17:39:17.852  1017  4786 D SettingsProvider: selectionArgs: 1002
08-25 17:39:17.852  1017  4786 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.852  1017  4786 D SettingsProvider: ret = -1
08-25 17:39:17.852  1017  1327 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-25 17:39:17.852  1017  1327 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:17.852  1017  1327 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:17.852  1017  1327 D SettingsProvider: selectionArgs: false
,08-25 17:39:17.852  1017  1327 D SettingsProvider: selectionArgs: 1002
08-25 17:39:17.852  1017  1327 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.852  1017  1327 D SettingsProvider: ret = -1
08-25 17:39:17.852  1017  1463 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-25 17:39:17.852  1017  1463 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 17:39:17.852  1017  1463 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 17:39:17.852  1017  1463 D SettingsProvider: selectionArgs: false
08-25 17:39:17.852  1017  1463 D SettingsProvider: selectionArgs: 1002
08-25 17:39:17.852  1017  1463 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.852  1017  1463 D SettingsProvider: ret = -1
08-25 17:39:17.852  1017  1029 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-25 17:39:17.852  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 17:39:17.852  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:17.852  1017  1029 D SettingsProvider: selectionArgs: false,
08-25 17:39:17.852  1017  1029 D SettingsProvider: selectionArgs: 1002
08-25 17:39:17.852  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.852  1017  1029 D SettingsProvider: ret = -1
08-25 17:39:17.852  1017  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:17.852  1017  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:17.852  1017  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 17:39:17.852  1017  1481 D SettingsProvider: selectionArgs: false
08-25 17:39:17.852  1017  1481 D SettingsProvider: selectionArgs: 1002
08-25 17:39:17.852  1017  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.852  1017  1481 D SettingsProvider: ret = -1
08-25 17:39:17.852  1017  1248 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:17.852  1017  1248 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:17.852  1017  1248 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:17.852  1017  1248 D SettingsProvider: selectionArgs: false
,08-25 17:39:17.852  1017  1248 D SettingsProvider: selectionArgs: 1002
08-25 17:39:17.852  1017  1248 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.852  1017  1248 D SettingsProvider: ret = -1
08-25 17:39:17.852  1017  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-25 17:39:17.852  1017  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:17.852  1017  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:17.852  1017  1480 D SettingsProvider: selectionArgs: false
08-25 17:39:17.852  1017  1480 D SettingsProvider: selectionArgs: 1002
,08-25 17:39:17.852  1017  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.852  1017  1480 D SettingsProvider: ret = -1
08-25 17:39:17.852  1017  4787 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-25 17:39:17.852  1017  4787 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:17.852  1017  4787 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:17.852  1017  4787 D SettingsProvider: selectionArgs: false
08-25 17:39:17.852  1017  4787 D SettingsProvider: selectionArgs: 1002
08-25 17:39:17.852  1017  4787 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:17.852  1017  4787 D SettingsProvider: ret = -1
,08-25 17:39:17.872  7428  7428 D BluetoothAdapterState: make,
,08-25 17:39:17.872  7428  7428 I bluedroid: init
,08-25 17:39:17.872  7428  7443 I BluetoothAdapterState: Entering OffState
,08-25 17:39:17.882  7428  7428 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,08-25 17:39:17.882  7428  7428 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 17:39:17.882  7428  7428 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 17:39:17.882  7428  7428 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 17:39:17.882  7428  7428 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-25 17:39:17.882  7428  7428 I bluedroid: get_profile_interface socket
08-25 17:39:17.882  7428  7428 I bluedroid: get_profile_interface map_client
,08-25 17:39:17.882  7428  7446 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-25 17:39:17.882  7428  7428 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-25 17:39:17.882  7428  7446 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 17:39:17.882  7428  7446 E BluetoothServiceJni: populateRssiValuesNative
08-25 17:39:17.882  7428  7446 I bluedroid: getModelRssiValues
08-25 17:39:17.882  7428  7446 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-25 17:39:17.882  7428  7446 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 17:39:17.882  7428  7446 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 17:39:17.892  1017  1017 D SettingsProvider: name = bluetooth_name
,08-25 17:39:17.892  7428  7428 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 17:39:17.892  1017  1029 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-25 17:39:17.892  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 17:39:17.892  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:17.892  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:17.892  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:17.902  7428  7438 I bluedroid: config_hci_snoop_log
,08-25 17:39:17.902  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-25 17:39:17.902  1017  3362 D SSRM:n  : SIOP:: AP = 360
,08-25 17:39:17.902  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-25 17:39:17.902  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-25 17:39:17.902  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-25 17:39:17.902  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 17:39:17.912  7428  7428 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-25 17:39:17.912  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 17:39:17.912  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 17:39:17.922  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-25 17:39:17.922  7428  7443 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-25 17:39:17.922  7428  7443 D BluetoothAdapterProperties: Setting state to 11
,08-25 17:39:17.922  7428  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 17:39:17.922  7428  7443 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-25 17:39:17.922  7428  7443 D BluetoothAdapterService: updateAdapterState state is 11
,08-25 17:39:17.922  7428  7443 D BluetoothAdapterService: Autoconnection is available 
08-25 17:39:17.922  7428  7443 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-25 17:39:17.922  7428  7443 D BluetoothSecureManager: getInstant: null
,08-25 17:39:17.922  7428  7443 D BluetoothSecureManager: calling getMethod for getService
,08-25 17:39:17.932  7428  7443 D BluetoothSecureManager: calling getService
08-25 17:39:17.932  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 17:39:17.932  7428  7443 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1220a100
,08-25 17:39:17.932  1017  1474 D BluetoothSecureManagerService: isSecureModeEnabled
08-25 17:39:17.932  1017  1474 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-25 17:39:17.932  7428  7443 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 17:39:17.932  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 17:39:17.932  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:17.932  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-25 17:39:17.932  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-25 17:39:17.932  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 17:39:17.932  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-25 17:39:17.932  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-25 17:39:17.932  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-25 17:39:17.932  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 17:39:17.932  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-25 17:39:17.932  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 17:39:17.932  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-25 17:39:17.932  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-25 17:39:17.932  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-25 17:39:17.932  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 17:39:17.942  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-25 17:39:17.942  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 17:39:17.942  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-25 17:39:17.942  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 17:39:17.942  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:17.942  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 17:39:17.942  1179  1179 D BluetoothTile:  getBluetoothState : 11
08-25 17:39:17.942  7428  7443 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:17.942  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 17:39:17.942  7428  7443 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:17.942  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 17:39:17.942  7428  7443 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-25 17:39:17.942  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-25 17:39:17.942  7428  7443 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-25 17:39:17.942  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
08-25 17:39:17.942  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 17:39:17.942  3293  3293 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:17.942  1873  1873 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 17:39:17.952  1017  1497 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 17:39:17.952  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:17.952  1017  1327 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 17:39:17.952  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:17.952  7428  7443 D BluetoothBondStateMachine: make
,08-25 17:39:17.952  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 17:39:17.952  1017  1463 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:17.952  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 17:39:17.952  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 17:39:17.952  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 17:39:17.952  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-25 17:39:17.952  7428  7448 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 17:39:17.952  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:17.962  1017  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:17.962  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:17.962  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:17.962  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-25 17:39:17.962  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:17.962  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:17.962  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:17.962  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 17:39:17.962  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 17:39:17.962  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-25 17:39:17.962  7428  7428 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 17:39:17.962  7428  7428 D BtGatt.GattService: Received start request. Starting profile...
08-25 17:39:17.962  7428  7428 D BtGatt.GattService: start()
08-25 17:39:17.962  7428  7428 D BtGatt.GattService: start()
08-25 17:39:17.962  7428  7428 I bluedroid: get_profile_interface gatt
,08-25 17:39:17.962  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
08-25 17:39:17.962  7428  7428 D BtGatt.AdvertiseManager: advertise manager created
,08-25 17:39:17.972  3293  3293 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 17:39:17.972  1017  4787 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:17.972  1017  4787 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 17:39:17.972  7428  7428 D BtGatt.GattService: mStartError = false
08-25 17:39:17.972  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:17.972  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:17.972  1017  4787 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:17.972  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:17.982  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 17:39:17.982  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 17:39:17.982  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-25 17:39:17.982  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:17.982  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-25 17:39:17.982  1017  4787 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:17.992  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:17.992  1017  4787 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 17:39:17.992  1017  4787 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:17.992  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:17.992  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-25 17:39:17.992  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 17:39:17.992  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 17:39:17.992  1017  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:17.992  1017  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 17:39:17.992  1017  1327 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:17.992  1017  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:17.992  1017  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:17.992  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-25 17:39:17.992  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 17:39:17.992  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 17:39:18.002  1017  4786 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-25 17:39:18.002  1017  4786 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:18.002  1017  4786 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:18.002  1017  4786 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:18.002  1017  4786 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:18.012  7452  7452 E Zygote  : MountEmulatedStorage()
,08-25 17:39:18.012  7452  7452 E Zygote  : v2
08-25 17:39:18.012  7452  7452 I libpersona: KNOX_SDCARD checking this for 10055
08-25 17:39:18.012  7452  7452 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:18.012  7452  7452 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:18.012  1017  4786 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7452 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-25 17:39:18.012  1017  4789 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-25 17:39:18.012  1017  4789 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 17:39:18.022  1017  4789 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:18.022  1017  4789 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:18.022  1017  4789 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:18.022  7452  7452 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:39:18.022  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 17:39:18.022  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 17:39:18.022  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 17:39:18.022  7452  7452 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 17:39:18.022  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:18.022  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 17:39:18.022  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:18.022  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:18.022  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 17:39:18.032  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 17:39:18.032  1017  4787 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:18.032  1017  4787 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 17:39:18.032  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:18.032  1017  4787 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:18.032  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-25 17:39:18.032  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-25 17:39:18.032  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:18.032  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 17:39:18.032  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:18.032  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:18.032  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:18.032  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:18.032  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 17:39:18.032  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 17:39:18.032  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 17:39:18.032  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 17:39:18.032  7428  7443 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-25 17:39:18.032  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-25 17:39:18.042  7428  7428 D HeadsetService: Received start request. Starting profile...
08-25 17:39:18.042  7428  7428 D HeadsetService: start()
,08-25 17:39:18.042  7428  7428 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-25 17:39:18.042  7428  7428 D HeadsetStateMachine: make
,08-25 17:39:18.042  7452  7452 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:18.042  7452  7452 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:18.052  7428  7428 E HeadsetStateMachine: # of Max HF connection is 2
,08-25 17:39:18.052  1017  1480 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-25 17:39:18.052  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-25 17:39:18.062  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:18.062  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:18.062  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 17:39:18.062  1017  1030 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-25 17:39:18.062  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-25 17:39:18.062  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:18.062  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:18.062  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 17:39:18.062  7428  7428 I bluedroid: get_profile_interface handsfree
,08-25 17:39:18.082  7428  7428 I DualScoManager: Instantiating Dual Sco Manager
,08-25 17:39:18.082  7428  7428 I DualScoManager: Set HeadsetServiceHelper
,08-25 17:39:18.082  7428  7428 D BluetoothAtMessage: createCMTIContentObservers
,08-25 17:39:18.092  1017  4789 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-25 17:39:18.092  1017  4789 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 17:39:18.092  1017  4789 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:18.092  1017  4789 D SettingsProvider: selectionArgs: false
08-25 17:39:18.092  1017  4789 D SettingsProvider: selectionArgs: 1002
,08-25 17:39:18.092  1017  4789 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 17:39:18.092  1017  4789 D SettingsProvider: ret = -1
,08-25 17:39:18.092  7428  7470 D HeadsetStateMachine: Enter Disconnected: -2
,08-25 17:39:18.092  7428  7428 D HeadsetService: mStartError = false
08-25 17:39:18.092  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:18.092  7452  7452 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-25 17:39:18.092  7428  7428 D A2dpService: Received start request. Starting profile...
08-25 17:39:18.092  7428  7428 D A2dpService: start()
,08-25 17:39:18.102  7428  7470 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-25 17:39:18.102  7428  7470 D HeadsetStateMachine: map size, before remove : 0
,08-25 17:39:18.102  7428  7428 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 17:39:18.102  7428  7470 D HeadsetStateMachine: map size, after remove: 0
,08-25 17:39:18.102  7428  7428 I bluedroid: get_profile_interface avrcp
,08-25 17:39:18.102  7428  7428 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 17:39:18.102  7428  7428 D Avrcp   : Initialize Media Controller
08-25 17:39:18.102  7428  7428 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-25 17:39:18.112  7428  7428 E Avrcp   : getActiveSessions
08-25 17:39:18.112  7428  7428 D Avrcp   : pick active media Controller
08-25 17:39:18.112  7428  7428 D Avrcp   : Get the active Media Controller 
,08-25 17:39:18.112   288   288 E SMD     : DCD OFF
,08-25 17:39:18.122  7428  7428 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-25 17:39:18.122  7428  7471 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-25 17:39:18.122  7428  7428 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:39:18.122  7428  7428 D A2dpStateMachine: make
,08-25 17:39:18.132  7428  7428 I bluedroid: get_profile_interface a2dp
,08-25 17:39:18.132  7452  7452 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-25 17:39:18.132  7452  7452 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-25 17:39:18.132  7452  7452 D UserAnalysis: Create SecureDbHelper
,08-25 17:39:18.132  7428  7473 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 17:39:18.132  7428  7428 E bt-btif : warning : media task started media_task_refcnt 1 
,08-25 17:39:18.142  7428  7428 D A2dpService: mStartError = false
,08-25 17:39:18.142  7428  7472 D A2dpStateMachine: Enter Disconnected: -2
08-25 17:39:18.142  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:18.142  7428  7428 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 17:39:18.142  7452  7452 D IntelligenceServiceApplication: onCreate()
,08-25 17:39:18.142  7428  7428 D HidService: Received start request. Starting profile...
08-25 17:39:18.142  7428  7428 D HidService: start()
08-25 17:39:18.142  7428  7428 I bluedroid: get_profile_interface hidhost
,08-25 17:39:18.142  7428  7428 D HidService: setHidService(): set to: null
08-25 17:39:18.142  7428  7428 D HidService: mStartError = false
08-25 17:39:18.142  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:18.142  7428  7428 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 17:39:18.142  1017  1463 I ActivityManager: Killing 7077:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-25 17:39:18.142  7428  7428 D HealthService: Received start request. Starting profile...
,08-25 17:39:18.142  7428  7428 D HealthService: start()
,08-25 17:39:18.152  7428  7471 D BluetoothMediaBrowser: no now playing list
08-25 17:39:18.152  7428  7428 I bluedroid: get_profile_interface health
,08-25 17:39:18.152  7428  7428 D HealthService: mStartError = false
08-25 17:39:18.152  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
08-25 17:39:18.152  7428  7471 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-25 17:39:18.152  7428  7428 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 17:39:18.152  7428  7428 D PanService: Received start request. Starting profile...
,08-25 17:39:18.152  7428  7428 D PanService: start()
08-25 17:39:18.152  7428  7428 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 17:39:18.152  7428  7428 I bluedroid: get_profile_interface pan
,08-25 17:39:18.152  7452  7452 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-25 17:39:18.152  7428  7428 D PanService: mStartError = false
08-25 17:39:18.152  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:18.152  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-25 17:39:18.152  7428  7428 D BluetoothMapService: Received start request. Starting profile...
08-25 17:39:18.152  7428  7428 D BluetoothMapService: start()
,08-25 17:39:18.152  7452  7452 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-25 17:39:18.152  7428  7428 D BluetoothMapService: mStartError = false
,08-25 17:39:18.162  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:18.162  7428  7428 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-25 17:39:18.162  7428  7428 D SapService: Received start request. Starting profile...
,08-25 17:39:18.162  7428  7428 D SapService: start()
08-25 17:39:18.162  7428  7428 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-25 17:39:18.162  7428  7428 I bluedroid: get_profile_interface sap
,08-25 17:39:18.162  7428  7428 D SapService: mStartError = false
08-25 17:39:18.162  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:18.162  7428  7428 D HeadsetStateMachine: Try to query the phonestate on bind
,08-25 17:39:18.162  1424  3263 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 17:39:18.162  1424  1424 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-25 17:39:18.162  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 17:39:18.162  1424  3263 I Telecom : BluetoothPhoneService: Result of Message : true
,08-25 17:39:18.172  7428  7428 D HeadsetStateMachine: Proxy object connected
,08-25 17:39:18.172  7428  7428 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-25 17:39:18.172  7428  7428 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-25 17:39:18.172  7428  7470 D HeadsetStateMachine: Disconnected process message: 11
08-25 17:39:18.172  7428  7428 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-25 17:39:18.172  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-25 17:39:18.172  7428  7428 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 17:39:18.172  7428  7470 D HeadsetStateMachine: Disconnected process message: 18
08-25 17:39:18.172  7428  7470 D HeadsetStateMachine: Disconnected process message: 10
08-25 17:39:18.172  7428  7428 D BluetoothA2dp: Proxy object connected
08-25 17:39:18.172  7428  7428 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-25 17:39:18.172  7428  7470 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 17:39:18.172  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-25 17:39:18.172  7428  7470 D HeadsetStateMachine: Disconnected process message: 11
08-25 17:39:18.172  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-25 17:39:18.172  1017  4789 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-25 17:39:18.172  1017  4789 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:18.172  1017  4789 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:18.172  7452  7452 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-25 17:39:18.172  1017  4789 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:18.172  1017  4789 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:18.192  7478  7478 E Zygote  : MountEmulatedStorage()
,08-25 17:39:18.192  7478  7478 E Zygote  : v2
08-25 17:39:18.192  7478  7478 I libpersona: KNOX_SDCARD checking this for 10105
08-25 17:39:18.192  7478  7478 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:18.192  1017  4789 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7478 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-25 17:39:18.192  7478  7478 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:18.192  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-25 17:39:18.192  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-25 17:39:18.192  7478  7478 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:18.192  7478  7478 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-25 17:39:18.212  7478  7478 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:18.212  7478  7478 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:18.222  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-25 17:39:18.222  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-25 17:39:18.232  7428  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-25 17:39:18.232  7428  7443 I bluedroid: enable
,08-25 17:39:18.232  7428  7443 I bt_hci_bdroid: init
,08-25 17:39:18.232  7428  7494 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-25 17:39:18.232  7428  7443 I bt_vendor: bt-vendor : init
,08-25 17:39:18.232  7428  7443 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 17:39:18.232  7428  7443 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 17:39:18.232  7428  7443 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-25 17:39:18.232  7428  7443 D bt_userial_mct: userial_init
08-25 17:39:18.232  7428  7443 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 17:39:18.232  7428  7443 I bt_vendor: Starting hciattach daemon
08-25 17:39:18.232  7428  7443 I bt_vendor: try to set false
,08-25 17:39:18.232  7428  7443 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 17:39:18.232  7428  7443 I bt_vendor: Starting hciattach daemon
,08-25 17:39:18.232  7428  7443 I bt_vendor: try to set true
,08-25 17:39:18.252  7498  7498 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 17:39:18.302  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-25 17:39:18.312  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 17:39:18.322  7509  7509 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 17:39:18.332  7510  7510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 17:39:18.342  7511  7511 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 17:39:18.352  7512  7512 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-25 17:39:18.382   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 17:39:18.382   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 17:39:18.382  7478  7516 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 17:39:18.382   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 17:39:18.382   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 17:39:18.382  7478  7516 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 17:39:18.542  7478  7478 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:18.542  7478  7478 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:18.542  7478  7478 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:18.542  7478  7478 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:18.542  7478  7478 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.k.d(PG:583)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:18.542  7478  7478 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:18.542  7478  7478 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:18.542  7478  7478 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:18.542  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:18.552  1017  1463 I ActivityManager: Killing 7092:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
08-25 17:39:18.552  1993  1993 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-25 17:39:18.552  1993  1993 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 17:39:18.592  7478  7520 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-25 17:39:18.612  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
08-25 17:39:18.622  7528  7528 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 17:39:18.642  7428  7443 I bt_vendor: bluetooth satus is on
,08-25 17:39:18.642  7428  7496 D bt_userial_mct: userial_open(port:0)
08-25 17:39:18.642  7428  7496 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 17:39:18.642  7428  7496 I bt_vendor: Done intiailizing UART
,08-25 17:39:18.652  7428  7496 I bt_vendor: Done intiailizing UART
,08-25 17:39:18.652  7428  7496 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-25 17:39:18.652  7428  7496 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-25 17:39:18.652  7428  7531 D bt_userial_mct: Entering userial_read_thread()
,08-25 17:39:18.782  1017  4790 I art     : Explicit concurrent mark sweep GC freed 88776(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.321ms total 149.700ms
,08-25 17:39:18.792  1017  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:18.792  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:18.792  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:18.792  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_SAP
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 17:39:18.792  7428  7494 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-25 17:39:18.882  7428  7494 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-25 17:39:18.892  7428  7494 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41bced1 
,08-25 17:39:18.892  7428  7494 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41bced1 
,08-25 17:39:18.912  7428  7446 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-25 17:39:18.912  7428  7446 E bt-btif : Calling BTA_HhEnable
,08-25 17:39:18.912  7428  7446 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-25 17:39:18.912  7428  7446 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 17:39:18.922  7428  7446 E BluetoothServiceJni: populateRssiValuesNative
08-25 17:39:18.922  7428  7446 I bluedroid: getModelRssiValues
08-25 17:39:18.922  7428  7446 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-25 17:39:18.922  7428  7446 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 17:39:18.922  7428  7446 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 17:39:18.922  1017  1017 D SettingsProvider: name = bluetooth_name
,08-25 17:39:18.922  7428  7446 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 17:39:18.922  7428  7446 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:39:18.922  7428  7446 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 17:39:18.922  7428  7446 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-25 17:39:18.922  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:18.922  7428  7446 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-25 17:39:18.922  7428  7446 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-25 17:39:18.922  7428  7446 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-25 17:39:18.922  7428  7446 E bt-btif : btif_sock_init: !vhci_init
,08-25 17:39:18.932  7428  7446 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-25 17:39:18.932  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:18.932  7428  7446 D IOP_DB_BT: db_open: db_open : handle 3023880208l, read 13894 bytes onto local cache
,08-25 17:39:18.932  7428  7531 E bt_mct  : hci lib postload completed
,08-25 17:39:18.932  7428  7446 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-25 17:39:18.932  7428  7446 D IOP_DB_BT: db_query: result 1
,08-25 17:39:18.932  7428  7446 I         : iop_db_open: iop_db_open status 0
,08-25 17:39:18.932  7428  7446 D bte_conf: Device ID record 1 : primary
,08-25 17:39:18.932  7428  7446 D bte_conf:   vendorId            = 0075
08-25 17:39:18.932  7428  7446 D bte_conf:   vendorIdSource      = 0001
,08-25 17:39:18.932  7428  7446 D bte_conf:   product             = 0100
,08-25 17:39:18.942  7428  7446 D bte_conf:   version             = 0200
08-25 17:39:18.942  7428  7446 D bte_conf:   clientExecutableURL = 
,08-25 17:39:18.942  7428  7446 D bte_conf:   serviceDescription  = 
,08-25 17:39:18.942  7428  7446 D bte_conf:   documentationURL    = 
,08-25 17:39:18.942  7428  7446 D bte_conf: bte_load_did_conf no section named DID2.
,08-25 17:39:18.942  7428  7446 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 17:39:18.942  7428  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-25 17:39:18.942  7428  7443 D BluetoothAdapterProperties: ScanMode =  20
08-25 17:39:18.942  7428  7443 D BluetoothAdapterProperties: State =  11
,08-25 17:39:18.942  1017  4786 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 17:39:18.942  7428  7443 D BluetoothAdapterProperties: Setting state to 12
,08-25 17:39:18.952  7428  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 17:39:18.952  7428  7446 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 17:39:18.952  7428  7446 D BluetoothAdapterProperties: Scan Mode:21
08-25 17:39:18.952  7428  7446 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 17:39:18.952  1017  4787 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-25 17:39:18.952  1017  4787 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:18.952  1017  4787 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:18.952  1017  4787 D SettingsProvider: selectionArgs: false
08-25 17:39:18.952  1017  4787 D SettingsProvider: selectionArgs: 1002
08-25 17:39:18.952  1017  4787 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:18.952  1017  4787 D SettingsProvider: ret = -1
,08-25 17:39:18.952  7428  7443 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 17:39:18.952  7428  7443 D BluetoothAdapterService: updateAdapterState state is 12
,08-25 17:39:18.952  1017  4787 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:18.952  1017  4787 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 17:39:18.962  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:18.962  1017  4787 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:18.962  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:18.962  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:18.962  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:18.962  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:18.962  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:18.962  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:18.962  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:18.962  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:18.962  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:18.972  7428  7443 D BluetoothAdapterService: Autoconnection is available 
08-25 17:39:18.972  7428  7443 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-25 17:39:18.972  7428  7443 D BluetoothAdapterService: starting service from this receiver
,08-25 17:39:18.972  1017  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:18.972  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 17:39:18.972  3293  3301 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 17:39:18.972  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:18.972  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:18.972  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:18.982  7428  7443 I BluetoothAdapterState: Entering On State from state = 11
08-25 17:39:18.982  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-25 17:39:18.982  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-25 17:39:18.982  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:18.982  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:18.982  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:18.982  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:18.982  1439  1464 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 17:39:18.982  1439  1464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 17:39:18.982  7428  7438 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 17:39:18.992  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:18.992  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:18.992  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:18.992  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:18.992  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:18.992  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:18.992  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:18.992  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:18.992  1424  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 17:39:18.992  7428  7428 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-25 17:39:18.992  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:19.002  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 17:39:19.002  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 17:39:19.002  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:19.002  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.002  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:19.002  1424  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 17:39:19.002  3293  3304 D BluetoothPan: Binding service...
,08-25 17:39:19.002  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-25 17:39:19.002  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 17:39:19.002  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:19.002  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.002  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:19.002  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 17:39:19.002  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 17:39:19.012  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 17:39:19.012  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 17:39:19.012  1017  1017 D BluetoothA2dp: Proxy object connected
,08-25 17:39:19.012  6770  6964 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 17:39:19.012  6770  6964 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:19.012  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:19.012  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:19.012  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-25 17:39:19.012  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 17:39:19.012  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 17:39:19.012  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 17:39:19.012  1993  2007 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:19.012  1993  2007 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 17:39:19.012  1017  1046 D BluetoothPan: Binding service...
,08-25 17:39:19.012  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 17:39:19.012  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 17:39:19.012  7428  7428 I BluetoothPbapService: Handler(): got msg=1
,08-25 17:39:19.012  1017  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 17:39:19.022  3293  3301 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 17:39:19.022  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:39:19.022  3293  3293 D BluetoothMap: Proxy object connected
08-25 17:39:19.022  3293  3293 D MapProfile: Bluetooth service connected
08-25 17:39:19.022  3293  3293 D BluetoothMap: getConnectedDevices()
,08-25 17:39:19.022  7428  7537 V BluetoothPbapService: PBAP Service initSocket try: 0
08-25 17:39:19.032  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-25 17:39:19.032  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 17:39:19.032  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:19.032  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.032  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:19.032  3293  3304 D Bluetoothsap: onBluetoothStateChange: up=true
,08-25 17:39:19.032  3293  3304 D Bluetoothsap: Binding service...
,08-25 17:39:19.032  3293  3293 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:39:19.032  3293  3293 D PanProfile: Bluetooth service connected
,08-25 17:39:19.032  7428  7537 D BluetoothSocket: bindListen(): myUserId = 0
08-25 17:39:19.032  7428  7537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:19.032  7428  7537 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-25 17:39:19.032  7428  7537 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 17:39:19.032  7428  7537 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 17:39:19.032  7428  7537 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@280e058d
08-25 17:39:19.032  3293  3304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-25 17:39:19.032  7428  7537 D BluetoothSocket: channel: 19
08-25 17:39:19.032  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-25 17:39:19.032  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-25 17:39:19.032  7428  7537 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-25 17:39:19.032  1017  1046 W ActivityManager: userId = 0, bbcId = -10000,
08-25 17:39:19.032  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.032  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-25 17:39:19.042  3293  3293 D BluetoothPbap: Proxy object connected
,08-25 17:39:19.042  3293  3293 D PbapServerProfile: Bluetooth service connected
08-25 17:39:19.042  3293  3304 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-25 17:39:19.042  3293  3293 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-25 17:39:19.042  3293  3293 D SapProfile: Bluetooth service connected
,08-25 17:39:19.042  1424  3263 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 17:39:19.042  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 17:39:19.042  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 17:39:19.042  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:19.042  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.042  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-25 17:39:19.042  3293  3293 D Bluetoothsap: getConnectedDevices()
,08-25 17:39:19.042  1424  3263 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 17:39:19.042  1455  1473 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 17:39:19.052  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 17:39:19.052  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 17:39:19.052  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:19.052  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.052  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:19.052  1455  1473 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 17:39:19.052  7478  7493 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 17:39:19.052  7478  7493 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 17:39:19.052  3293  7536 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 17:39:19.052  3293  7536 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:19.052  3293  3304 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 17:39:19.052  3293  3304 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 17:39:19.052  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-25 17:39:19.062  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 17:39:19.062  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:19.062  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.062  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:19.062  3293  3293 D BluetoothA2dp: Proxy object connected
08-25 17:39:19.062  3293  3293 D A2dpProfile: Bluetooth service connected
,08-25 17:39:19.062  1424  1445 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 17:39:19.062  1424  1445 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 17:39:19.062  1455  1863 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 17:39:19.062  1455  1863 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 17:39:19.062  3293  7536 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 17:39:19.062  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-25 17:39:19.062  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 17:39:19.062  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:19.062  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.062  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:19.072  1179  1837 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:19.072  1179  1837 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 17:39:19.072  3293  3293 D BluetoothInputDevice: Proxy object connected
08-25 17:39:19.072  3293  3293 D HidProfile: Bluetooth service connected
,08-25 17:39:19.072  1424  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 17:39:19.072  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 17:39:19.072  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 17:39:19.072  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:19.072  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.072  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:19.072  1424  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 17:39:19.072  7428  7447 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 17:39:19.072  7428  7447 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 17:39:19.082  3293  3304 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 17:39:19.082  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 17:39:19.082  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 17:39:19.082  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:19.082  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.082  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:19.082  3293  3293 D HeadsetProfile: Bluetooth service connected
,08-25 17:39:19.082  3293  3304 E BluetoothHeadset: BluetoothHeadset service is binded,
,08-25 17:39:19.082  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-25 17:39:19.082  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 17:39:19.082  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:19.082  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
,08-25 17:39:19.082  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 17:39:19.092  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-25 17:39:19.092  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 17:39:19.092  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 17:39:19.102  1424  1424 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@36834c19, true
,08-25 17:39:19.102  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:19.102  1179  1179 D BluetoothTile:  getBluetoothState : 12
,08-25 17:39:19.102  1873  1873 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 17:39:19.102  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
08-25 17:39:19.102  1424  1424 D BluetoothHeadset: registerMessageListener
,08-25 17:39:19.102  1017  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 17:39:19.102  3293  3293 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:19.102  1017  1761 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-25 17:39:19.102  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 17:39:19.112  7428  7438 D HeadsetService: registerMessageListener
,08-25 17:39:19.112  1017  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 17:39:19.112  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 17:39:19.112  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:19.112  7428  7438 D HeadsetService: registerMessageListener
,08-25 17:39:19.112  7428  7470 D HeadsetStateMachine: Disconnected process message: 70
08-25 17:39:19.112  7428  7470 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2bb78342
08-25 17:39:19.112  1424  1424 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-25 17:39:19.112  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-25 17:39:19.112  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:19.112  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:19.112  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:19.112  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:19.112  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 17:39:19.122  1424  1424 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-25 17:39:19.122  1424  1424 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-25 17:39:19.122  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-25 17:39:19.122  7428  7540 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-25 17:39:19.122  3293  3293 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-25 17:39:19.122  3293  3293 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-25 17:39:19.122  3293  3293 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-25 17:39:19.122  7428  7470 D HeadsetStateMachine: Disconnected process message: 9
08-25 17:39:19.122  3293  3293 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-25 17:39:19.122  7428  7470 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-25 17:39:19.132  7428  7540 D BluetoothSocket: bindListen(): myUserId = 0
08-25 17:39:19.132  7428  7540 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:39:19.132   283   709 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-25 17:39:19.132   283   709 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-25 17:39:19.132   283   709 V voice   : voice_set_parameters: exit with code(-2)
08-25 17:39:19.132   283   709 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-25 17:39:19.132   283   709 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-25 17:39:19.132   283   709 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-25 17:39:19.132   283   709 V audio_hw_primary: adev_set_parameters: exit
08-25 17:39:19.132  7428  7470 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-25 17:39:19.132  7428  7540 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-25 17:39:19.132  7428  7540 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 17:39:19.132  7428  7540 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 17:39:19.132  7428  7540 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e2d2f53
,08-25 17:39:19.132  3293  3293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 17:39:19.132  7428  7540 D BluetoothSocket: channel: 5
08-25 17:39:19.132  1017  1463 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 17:39:19.132  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 17:39:19.142  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:19.142  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.142  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 17:39:19.152  3293  3293 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:39:19.152  3293  3293 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 17:39:19.152  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:19.152  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-25 17:39:19.162  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:19.162  7428  7428 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 17:39:19.162  1017  1761 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:19.162  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-25 17:39:19.172  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:19.172  1017  1761 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:19.172  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:19.192  1993  1993 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 17:39:19.192  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:19.192  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 17:39:19.192  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:19.192  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 17:39:19.192  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:19.202  1017  1135 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 17:39:19.202  1993  7549 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 17:39:19.202  1993  1993 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-25 17:39:19.202  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:19.212  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:19.212  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:19.212  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:19.222  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:19.222  7428  7550 D BluetoothSocket: bindListen(): myUserId = 0
08-25 17:39:19.222  7428  7550 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:19.232  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:19.232  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:19.232  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:19.232  7428  7550 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-25 17:39:19.232  7428  7550 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 17:39:19.232  7428  7550 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 17:39:19.232  7428  7550 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b7b5945
,08-25 17:39:19.232  7428  7550 D BluetoothSocket: channel: 12
08-25 17:39:19.232  7428  7550 I BtOppRfcommListener: Accept thread started.
,08-25 17:39:19.242  1993  7549 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-25 17:39:20.432  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-25 17:39:20.432  1017  1135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 17:39:20.432  1017  1135 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 17:39:20.432  1017  1135 D BatteryService: stay LED for fully charged
08-25 17:39:20.432  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 17:39:20.442  1017  1017 I MotionRecognitionService: Plugged
,08-25 17:39:20.442  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 17:39:20.442  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 17:39:20.452  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 17:39:20.452  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 17:39:20.452  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 17:39:20.462  7428  7428 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 17:39:20.462  7428  7470 D HeadsetStateMachine: Disconnected process message: 10
,08-25 17:39:20.472  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-25 17:39:20.472  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-25 17:39:20.472  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 17:39:20.472  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 17:39:20.482  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 17:39:20.682  6770  6823 D BluetoothAdapter: disable()
,08-25 17:39:20.692  1017  1481 D SettingsProvider: name = bluetooth_on
,08-25 17:39:20.702  7428  7443 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-25 17:39:20.702  1017  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:20.702  7428  7443 D BluetoothAdapterProperties: Setting state to 13,
08-25 17:39:20.702  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-25 17:39:20.702  7428  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 17:39:20.702  7428  7443 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-25 17:39:20.702  7428  7443 D BluetoothAdapterService: updateAdapterState state is 13
08-25 17:39:20.702  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:20.702  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:20.702  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:20.702  7428  7428 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-25 17:39:20.712  7428  7443 D BluetoothAdapterService: Autoconnection is available ,
08-25 17:39:20.712  7428  7443 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-25 17:39:20.712  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 17:39:20.712  7428  7443 D BluetoothAdapterService: terminating service from this receiver
08-25 17:39:20.712  7428  7428 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3916389a, channel: 19, state: LISTENING
08-25 17:39:20.712  7428  7428 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3916389a, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@280e058d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@34d135cbmSocket: android.net.LocalSocket@2179f1a8 impl:android.net.LocalSocketImpl@387d44c1 fd:FileDescriptor[74]
08-25 17:39:20.712  7428  7428 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2179f1a8 impl:android.net.LocalSocketImpl@387d44c1 fd:FileDescriptor[74]
08-25 17:39:20.712  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:20.712  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:20.712  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:20.712  7428  7443 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 17:39:20.712  7428  7443 D BluetoothAdapterProperties: mDiscovering is false
,08-25 17:39:20.712  1017  1456 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-25 17:39:20.712  7428  7443 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 17:39:20.712  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:20.712  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-25 17:39:20.722  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-25 17:39:20.722  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 17:39:20.722  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:20.722  1179  1179 D BluetoothTile:  getBluetoothState : 13
,08-25 17:39:20.722  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 17:39:20.722  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 17:39:20.722  1873  1873 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 17:39:20.722  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 17:39:20.732  3293  3293 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:20.732  1017  1480 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 17:39:20.732  1017  1474 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 17:39:20.732  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-25 17:39:20.732  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:20.732  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:20.732  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:20.732  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:20.732  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:20.732  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:20.732  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:20.732  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:20.732  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:20.732  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:20.732  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:20.742  7428  7446 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 17:39:20.742  7428  7446 D BluetoothAdapterProperties: Scan Mode:20
,08-25 17:39:20.742  1017  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:20.742  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 17:39:20.742  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:20.742  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:20.742  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:20.742  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:20.742  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:20.742  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:20.742  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:20.742  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:20.742  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:20.742  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:20.742  1017  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:20.742  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:20.742  6770  6770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:20.742  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:20.752  3293  3293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 17:39:20.752  7428  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 17:39:20.752  7428  7443 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-25 17:39:20.752  7428  7443 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-25 17:39:20.752  7428  7443 E bt-btif : cmd socket is not created
08-25 17:39:20.752  7428  7550 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:39:20.752  7428  7443 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 17:39:20.752  7428  7494 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-25 17:39:20.752  7428  7494 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-25 17:39:20.752  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:39:20.752  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:39:20.752  7428  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-25 17:39:20.752  1017  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 17:39:20.752  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 17:39:20.752  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:20.752  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:20.752  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 17:39:20.762  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:20.762  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:20.772  7428  7428 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@268f4466, channel: 5, state: LISTENING
,08-25 17:39:20.772  7428  7428 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@268f4466, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e2d2f53, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ebb63a7mSocket: android.net.LocalSocket@28508054 impl:android.net.LocalSocketImpl@6586bfd fd:FileDescriptor[76]
,08-25 17:39:20.772  3293  3293 D BluetoothPbap: Proxy object disconnected
08-25 17:39:20.772  3293  3293 D PbapServerProfile: Bluetooth service disconnected
08-25 17:39:20.772  7428  7428 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@28508054 impl:android.net.LocalSocketImpl@6586bfd fd:FileDescriptor[76]
,08-25 17:39:20.772  7428  7428 I BtOppRfcommListener: stopping Accept Thread
08-25 17:39:20.772  7428  7428 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@273b40f2, channel: 12, state: LISTENING
08-25 17:39:20.772  7428  7428 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@273b40f2, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b7b5945, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f309343mSocket: android.net.LocalSocket@d5f4dc0 impl:android.net.LocalSocketImpl@1dc4caf9 fd:FileDescriptor[79]
08-25 17:39:20.772  7428  7428 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d5f4dc0 impl:android.net.LocalSocketImpl@1dc4caf9 fd:FileDescriptor[79]
,08-25 17:39:20.772  7428  7550 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 17:39:20.782  3293  3293 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:39:20.782  3293  3293 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 17:39:20.782  7428  7428 V BluetoothOppManager: cleanUp...
,08-25 17:39:20.792  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:20.792  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-25 17:39:20.812  1993  1993 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 17:39:20.822  1993  1993 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 17:39:20.952  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 17:39:20.952  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 17:39:20.952  7428  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:39:20.952  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 17:39:20.952  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:39:20.952  7428  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:39:20.952  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 17:39:20.952  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:39:20.952  7428  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-25 17:39:20.952  7428  7494 W bt-btif : ag scb idx 1 not allocated
08-25 17:39:20.952  7428  7494 W bt-btif : ag scb idx 2 not allocated
08-25 17:39:20.952  7428  7494 E bt-btif : BTA AG is already disabled, ignoring ...,
08-25 17:39:20.962  7428  7531 I bt_userial_mct: exiting userial_read_thread
08-25 17:39:20.962  7428  7531 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 17:39:20.962  7428  7446 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-25 17:39:20.962  7428  7496 I bt_vendor: hw_epilog_process
08-25 17:39:20.962  7428  7446 D bt_userial_mct: userial_close
,08-25 17:39:20.962  7428  7446 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 17:39:21.112   288   288 E SMD     : DCD OFF
,08-25 17:39:21.342  7428  7446 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-25 17:39:21.342  7428  7446 I bt_vendor: bluetooth satus is on
,08-25 17:39:21.342  7428  7446 I bt_vendor: bt-vendor : resetting BT status
08-25 17:39:21.342  7428  7446 I bt_vendor: Starting hciattach daemon
,08-25 17:39:21.342  7428  7446 I bt_vendor: try to set false
,08-25 17:39:21.342  7428  7446 I bt_vendor: Starting hciattach daemon
,08-25 17:39:21.342  7428  7446 I bt_vendor: try to set false
,08-25 17:39:21.352  7428  7446 I bt_vendor: cleanup
,08-25 17:39:21.352  7428  7494 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-25 17:39:21.352  7428  7446 I GKI_LINUX: GKI_exit_task 0 done
08-25 17:39:21.352  7428  7446 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-25 17:39:21.352  7428  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 17:39:21.352  1017  4787 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-25 17:39:21.352  7428  7443 D BtConfig.SecureMode: isSecureModeOn:false
08-25 17:39:21.352  1017  4787 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-25 17:39:21.352  7428  7443 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-25 17:39:21.352  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:21.352  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 17:39:21.352  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-25 17:39:21.352  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 17:39:21.352  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-25 17:39:21.352  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:21.352  1017  4787 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:21.352  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:21.352  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 17:39:21.352  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 17:39:21.352  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 17:39:21.352  7428  7428 D BtGatt.DebugUtils: handleDebugAction() action=null,
,08-25 17:39:21.352  7428  7428 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 17:39:21.352  7428  7428 D BtGatt.GattService: stop()
08-25 17:39:21.352  7428  7428 D BtGatt.AdvertiseManager: advertise clients cleared,
,08-25 17:39:21.362  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:21.362  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:21.362  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-25 17:39:21.362  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:21.362  1017  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:21.362  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 17:39:21.362  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
08-25 17:39:21.362  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 17:39:21.362  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-25 17:39:21.362  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:21.372  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:21.362  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:21.372  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-25 17:39:21.362  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:21.372  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService,
08-25 17:39:21.372  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 17:39:21.372  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-25 17:39:21.372  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:21.372  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,08-25 17:39:21.372  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:21.372  1017  1456 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:21.372  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-25 17:39:21.372  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 17:39:21.372  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 17:39:21.372  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-25 17:39:21.372  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:21.372  1017  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:21.372  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:21.372  1017  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-25 17:39:21.372  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:21.372  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 17:39:21.372  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 17:39:21.372  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 17:39:21.382  1017  1327 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:21.382  1017  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:21.382  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:21.382  1017  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:21.382  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 17:39:21.382  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 17:39:21.382  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:21.382  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:21.382  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-25 17:39:21.382  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 17:39:21.382  1017  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:21.382  1017  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-25 17:39:21.382  1017  1474 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:21.382  1017  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:21.382  1017  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:21.382  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:21.382  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 17:39:21.382  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 17:39:21.382  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 17:39:21.382  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-25 17:39:21.382  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-25 17:39:21.392  7428  7443 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-25 17:39:21.392  7428  7428 D HeadsetService: Received stop request...Stopping profile...
08-25 17:39:21.392  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:21.392  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-25 17:39:21.392  3293  3293 D HeadsetProfile: Bluetooth service disconnected
,08-25 17:39:21.392  7428  7428 D A2dpService: Received stop request...Stopping profile...
08-25 17:39:21.392  7428  7472 D A2dpStateMachine: Exit Disconnected: -1
,08-25 17:39:21.392  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:21.392  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-25 17:39:21.392  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-25 17:39:21.392  3293  3293 D BluetoothA2dp: Proxy object disconnected
08-25 17:39:21.402  3293  3293 D A2dpProfile: Bluetooth service disconnected
,08-25 17:39:21.402  7428  7428 D HidService: Received stop request...Stopping profile...
08-25 17:39:21.402  7428  7428 D HidService: Stopping Bluetooth HidService
08-25 17:39:21.402  7428  7428 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 17:39:21.402  7428  7428 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-25 17:39:21.402  7428  7428 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 17:39:21.402  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:21.402  7428  7428 D HealthService: Received stop request...Stopping profile...
,08-25 17:39:21.402  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:21.402  3293  3293 D BluetoothInputDevice: Proxy object disconnected
08-25 17:39:21.402  3293  3293 D HidProfile: Bluetooth service disconnected
,08-25 17:39:21.402  7428  7428 D PanService: Received stop request...Stopping profile...
,08-25 17:39:21.402  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
,08-25 17:39:21.402  7428  7428 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 17:39:21.402  3293  3293 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 17:39:21.412  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 17:39:21.412  3293  3293 D PanProfile: Bluetooth service disconnected
,08-25 17:39:21.412  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b,
,08-25 17:39:21.412  7428  7428 D SapService: Received stop request...Stopping profile...
,08-25 17:39:21.412  3293  3293 D BluetoothMap: Proxy object disconnected
08-25 17:39:21.412  7428  7428 D SapService: Stopping Bluetooth SapService
08-25 17:39:21.412  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e21060b
08-25 17:39:21.412  3293  3293 D MapProfile: Bluetooth service disconnected
,08-25 17:39:21.412  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-25 17:39:21.412  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 17:39:21.412  7428  7428 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-25 17:39:21.412  7428  7428 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 17:39:21.412  7428  7428 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:39:21.422  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-25 17:39:21.422  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 17:39:21.422  7428  7428 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 17:39:21.422  7428  7428 D BluetoothA2dp: Proxy object disconnected
08-25 17:39:21.422  7428  7428 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-25 17:39:21.422  3293  3293 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-25 17:39:21.422  3293  3293 D SapProfile: Bluetooth service disconnected,
08-25 17:39:21.422  7428  7473 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-25 17:39:21.422  7428  7428 I GKI_LINUX: GKI_exit_task 2 done
,08-25 17:39:21.422  7428  7428 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-25 17:39:21.422  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-25 17:39:21.422  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 17:39:21.422  7428  7428 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:21.422  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-25 17:39:21.422  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:21.422  7428  7428 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:21.422  7428  7428 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...,
08-25 17:39:21.422  7428  7428 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:39:21.422  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-25 17:39:21.422  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:21.422  7428  7428 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:21.422  7428  7428 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 17:39:21.422  7428  7428 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-25 17:39:21.422  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-25 17:39:21.422  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 17:39:21.422  7428  7428 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-25 17:39:21.422  7428  7428 E BluetoothAdapterService(1042351627): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-25 17:39:21.422  7428  7428 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-25 17:39:21.422  7428  7428 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-25 17:39:21.432  7428  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-25 17:39:21.432  7428  7443 D BluetoothAdapterProperties: Setting state to 10
08-25 17:39:21.432  7428  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 17:39:21.432  7428  7443 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 17:39:21.432  7428  7443 D BluetoothAdapterService: updateAdapterState state is 10
08-25 17:39:21.432  7428  7443 D BluetoothAdapterService: Autoconnection is available 
08-25 17:39:21.432  7428  7443 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-25 17:39:21.432  7428  7443 I BluetoothAdapterState: Entering OffState
,08-25 17:39:21.432  3293  3304 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 17:39:21.432  1439  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:21.432  1439  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 17:39:21.432  7428  7438 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 17:39:21.432  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 17:39:21.432  6770  6780 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 17:39:21.432  6770  6780 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 17:39:21.432  6770  6780 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-25 17:39:21.432  6770  6780 D BluetoothLeAdvertiser: Exit stop advertising
08-25 17:39:21.432  6770  6780 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-25 17:39:21.432  6770  6780 D BluetoothLeScanner: Exiting stopAllScan
,08-25 17:39:21.432  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:21.432  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 17:39:21.442  1993  6872 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 17:39:21.442  1993  6872 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 17:39:21.442  3293  7536 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 17:39:21.442  3293  3304 D Bluetoothsap: onBluetoothStateChange: up=false
,08-25 17:39:21.442  3293  3304 D Bluetoothsap: Unbinding service...
,08-25 17:39:21.442  7478  7491 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 17:39:21.442  7478  7491 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 17:39:21.442  3293  3301 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:21.442  3293  3301 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 17:39:21.442  3293  7536 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 17:39:21.442  1424  1445 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 17:39:21.442  1424  1445 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 17:39:21.442  1455  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:21.442  1455  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 17:39:21.442  3293  3304 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 17:39:21.452  1179  2370 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 17:39:21.452  1179  2370 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 17:39:21.452  7428  7440 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 17:39:21.452  7428  7440 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 17:39:21.452  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 17:39:21.452  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 17:39:21.462  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:21.462  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-25 17:39:21.462  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 17:39:21.462  1179  1179 D BluetoothAdapter: 557880363: getState() :  mService = null. Returning STATE_OFF
,08-25 17:39:21.462  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 17:39:21.462  1179  1760 D BluetoothAdapter: 557880363: getState() :  mService = null. Returning STATE_OFF
,08-25 17:39:21.462  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:21.462  1179  1179 D BluetoothTile:  getBluetoothState : 10
,08-25 17:39:21.462  1179  1760 D BluetoothAdapter: 557880363: getState() :  mService = null. Returning STATE_OFF
,08-25 17:39:21.472  1179  1179 D BluetoothAdapter: 557880363: getState() :  mService = null. Returning STATE_OFF
08-25 17:39:21.472  1017  4790 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 17:39:21.472  1179  1179 D BluetoothAdapter: 557880363: getState() :  mService = null. Returning STATE_OFF
08-25 17:39:21.472  1873  1873 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 17:39:21.472  1017  1481 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 17:39:21.472  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 17:39:21.472  1993  2157 D BluetoothAdapter: 80648906: getState() :  mService = null. Returning STATE_OFF
08-25 17:39:21.472  1993  2157 D BluetoothAdapter: 80648906: getState() :  mService = null. Returning STATE_OFF
,08-25 17:39:21.472  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:21.472  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:21.472  3293  3293 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:21.482  1017  4789 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:21.482  1017  4789 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 17:39:21.482  1017  4789 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:21.482  1017  4789 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:21.482  1017  4789 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:21.482  3293  3293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 17:39:21.492  7428  7446 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 17:39:21.492  7428  7428 I GKI_LINUX: GKI_exit_task 1 done
08-25 17:39:21.492  7428  7428 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-25 17:39:21.492  7428  7428 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 17:39:21.492  1017  4787 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 17:39:21.492  1017  4787 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 17:39:21.492  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:21.492  1017  4787 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:21.492  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 17:39:21.492  7428  7428 I art     : System.exit called, status: 0
,08-25 17:39:21.492  7428  7428 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 17:39:21.502  3293  3293 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:39:21.502  3293  3293 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 17:39:21.512  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:21.512  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-25 17:39:21.512  1017  1135 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-25 17:39:21.522  1017  1135 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-25 17:39:21.522  1017  1135 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-25 17:39:21.522  1017  1135 W BroadcastQueue: android.os.TransactionTooLargeException
08-25 17:39:21.522  1017  1135 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 17:39:21.522  1017  1135 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 17:39:21.522  1017  1135 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-25 17:39:21.522  1017  1135 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-25 17:39:21.522  1017  1135 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-25 17:39:21.522  1017  1135 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-25 17:39:21.522  1017  1135 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-25 17:39:21.522  1017  1135 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-25 17:39:21.522  1017  1135 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 17:39:21.522  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-25 17:39:21.522  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:21.522  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:21.522  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:21.522  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:21.532  7567  7567 E Zygote  : MountEmulatedStorage()
08-25 17:39:21.532  7567  7567 I libpersona: KNOX_SDCARD checking this for 1002
08-25 17:39:21.532  7567  7567 E Zygote  : v2
,08-25 17:39:21.532  7567  7567 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:21.532  7567  7567 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 17:39:21.532  1017  1135 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7567 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-25 17:39:21.542  7567  7567 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:21.542  7567  7567 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:21.562  7567  7567 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:21.562  7567  7567 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:21.572  7567  7567 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 17:39:21.572  7567  7567 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 17:39:21.592  7567  7567 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-25 17:39:21.622  7567  7567 D BtSettings.ProfileConfig: Adding GattService
,08-25 17:39:21.622  7567  7567 D BtSettings.ProfileConfig: Adding HeadsetService
08-25 17:39:21.622  7567  7567 D BtSettings.ProfileConfig: Adding A2dpService
,08-25 17:39:21.622  7567  7567 D BtSettings.ProfileConfig: Adding HidService
08-25 17:39:21.622  7567  7567 D BtSettings.ProfileConfig: Adding HealthService
08-25 17:39:21.622  7567  7567 D BtSettings.ProfileConfig: Adding PanService
,08-25 17:39:21.622  7567  7567 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-25 17:39:21.622  7567  7567 D BtSettings.ProfileConfig: Adding SapService
08-25 17:39:21.622  7567  7567 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-25 17:39:21.632  7567  7567 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-25 17:39:21.632  7567  7567 D BtSettings.ProfileConfig: Adding SapClientService
08-25 17:39:21.632  7567  7567 D BtSettings.ProfileConfig: Adding HidDevService
08-25 17:39:21.632  7567  7567 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-25 17:39:21.632  1017  4787 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-25 17:39:21.632  1017  4787 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:21.632  1017  4787 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:21.632  1017  4787 D SettingsProvider: selectionArgs: false
08-25 17:39:21.632  1017  4787 D SettingsProvider: selectionArgs: 1002
08-25 17:39:21.632  1017  4787 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:21.632  1017  4787 D SettingsProvider: ret = -1
08-25 17:39:21.632  1017  1135 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-25 17:39:21.632  1017  1135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:21.632  1017  1135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:21.632  1017  1135 D SettingsProvider: selectionArgs: false
08-25 17:39:21.632  1017  1135 D SettingsProvider: selectionArgs: 1002
08-25 17:39:21.632  1017  1135 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:21.632  1017  1135 D SettingsProvider: ret = -1
08-25 17:39:21.632  1017  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-25 17:39:21.632  1017  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:21.632  1017  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:21.632  1017  1474 D SettingsProvider: selectionArgs: false
08-25 17:39:21.632  1017  1474 D SettingsProvider: selectionArgs: 1002
08-25 17:39:21.632  1017  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:21.632  1017  1474 D SettingsProvider: ret = -1
08-25 17:39:21.632  1017  1456 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-25 17:39:21.632  1017  1456 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:21.632  1017  1456 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-25 17:39:21.632  1017  1456 D SettingsProvider: selectionArgs: false
08-25 17:39:21.632  1017  1456 D SettingsProvider: selectionArgs: 1002
08-25 17:39:21.632  1017  1456 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:21.632  1017  1456 D SettingsProvider: ret = -1,
,08-25 17:39:21.632  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-25 17:39:21.632  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:21.632  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:21.632  1017  1029 D SettingsProvider: selectionArgs: false
,08-25 17:39:21.632  1017  1029 D SettingsProvider: selectionArgs: 1002
08-25 17:39:21.632  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:21.632  1017  1029 D SettingsProvider: ret = -1
08-25 17:39:21.632  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-25 17:39:21.632  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 17:39:21.632  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:21.632  1017  1030 D SettingsProvider: selectionArgs: false
08-25 17:39:21.632  1017  1030 D SettingsProvider: selectionArgs: 1002
08-25 17:39:21.632  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:21.632  1017  1030 D SettingsProvider: ret = -1
08-25 17:39:21.632  1017  4789 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-25 17:39:21.632  1017  4789 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:21.632  1017  4789 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:21.632  1017  4789 D SettingsProvider: selectionArgs: false
08-25 17:39:21.632  1017  4789 D SettingsProvider: selectionArgs: 1002
08-25 17:39:21.632  1017  4789 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-25 17:39:21.632  1017  4789 D SettingsProvider: ret = -1
08-25 17:39:21.632  1017  1497 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-25 17:39:21.632  1017  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:21.632  1017  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:21.632  1017  1497 D SettingsProvider: selectionArgs: false,
08-25 17:39:21.632  1017  1497 D SettingsProvider: selectionArgs: 1002
08-25 17:39:21.632  1017  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:21.642  1017  1497 D SettingsProvider: ret = -1
08-25 17:39:21.642  1017  1327 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:21.642  1017  1327 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-25 17:39:21.642  1017  1327 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:21.642  1017  1327 D SettingsProvider: selectionArgs: false
08-25 17:39:21.642  1017  1327 D SettingsProvider: selectionArgs: 1002
08-25 17:39:21.642  1017  1327 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 17:39:21.642  1017  1327 D SettingsProvider: ret = -1
08-25 17:39:21.642  1017  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:21.642  1017  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:21.642  1017  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:21.642  1017  1481 D SettingsProvider: selectionArgs: false,
08-25 17:39:21.642  1017  1481 D SettingsProvider: selectionArgs: 1002
08-25 17:39:21.642  1017  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:21.642  1017  1481 D SettingsProvider: ret = -1
08-25 17:39:21.642  1017  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService,
08-25 17:39:21.642  1017  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:21.642  1017  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:21.642  1017  1480 D SettingsProvider: selectionArgs: false
,08-25 17:39:21.642  1017  1480 D SettingsProvider: selectionArgs: 1002
08-25 17:39:21.642  1017  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:21.642  1017  1480 D SettingsProvider: ret = -1
08-25 17:39:21.642  1017  1248 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
08-25 17:39:21.642  1017  1248 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
,08-25 17:39:21.642  1017  1248 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:21.642  1017  1248 D SettingsProvider: selectionArgs: false
08-25 17:39:21.642  1017  1248 D SettingsProvider: selectionArgs: 1002
,08-25 17:39:21.642  1017  1248 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-25 17:39:21.642  1017  1248 D SettingsProvider: ret = -1
,08-25 17:39:21.652  1993  1993 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 17:39:21.652  1017  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:21.652  1017  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 17:39:21.652  1017  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:21.652  1017  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:21.652  1017  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:21.662  1993  7584 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 17:39:21.662  1993  1993 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 17:39:21.662  1017  1463 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:21.672  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:21.672  1017  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 17:39:21.672  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:21.672  1993  7584 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-25 17:39:22.412  1017  1324 E Watchdog: !@Sync 4
,08-25 17:39:22.742  1017  1049 I PowerManagerService: [PWL] Off : 75s ago,
08-25 17:39:22.742  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-25 17:39:22.742  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1,
08-25 17:39:22.742  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=13399)
,08-25 17:39:23.142   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 17:39:23.702  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:39:23.702  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:24.112   288   288 E SMD     : DCD OFF
,08-25 17:39:24.142   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 17:39:25.142   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 17:39:26.142   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 17:39:26.692  1017  4790 I ActivityManager: Killing 7107:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-25 17:39:26.702  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:26.702  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f349a24 added. We now have 6 listener(s)
,08-25 17:39:26.702  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:26.702  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:26.702  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c34c98d added. We now have 7 listener(s)
,08-25 17:39:26.702  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:26.712  6770  6823 I System.out: IsBluetoothEnabled
,08-25 17:39:26.712  6770  6823 D BluetoothAdapter: disable()
,08-25 17:39:26.712  1017  1135 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-25 17:39:26.712  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:26.712  6770  6823 D BluetoothAdapter: enable()
,08-25 17:39:26.712  1017  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=6770, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 17:39:26.722  1017  1029 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-25 17:39:26.722  1017  1029 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6770, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 17:39:26.722  1017  1029 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 17:39:26.722  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-25 17:39:26.722  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-25 17:39:26.722  1017  1029 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-25 17:39:26.722  1017  1029 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 17:39:26.722  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 17:39:26.722  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 17:39:26.722  1017  1029 D SettingsProvider: name = bluetooth_on
,08-25 17:39:26.722  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 17:39:26.722  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 17:39:26.732  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-25 17:39:26.732  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-25 17:39:26.752  7567  7567 D BluetoothAdapterState: make
,08-25 17:39:26.752  7567  7567 I bluedroid: init
,08-25 17:39:26.762  7567  7590 I BluetoothAdapterState: Entering OffState,
08-25 17:39:26.762  7567  7567 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 17:39:26.762  7567  7567 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 17:39:26.762  7567  7567 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 17:39:26.762  7567  7567 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 17:39:26.762  7567  7567 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-25 17:39:26.762  7567  7567 I bluedroid: get_profile_interface socket
08-25 17:39:26.762  7567  7567 I bluedroid: get_profile_interface map_client
,08-25 17:39:26.762  7567  7593 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-25 17:39:26.762  7567  7593 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-25 17:39:26.762  7567  7593 E BluetoothServiceJni: populateRssiValuesNative
08-25 17:39:26.762  7567  7593 I bluedroid: getModelRssiValues
08-25 17:39:26.762  7567  7593 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-25 17:39:26.762  7567  7593 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 17:39:26.762  7567  7567 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-25 17:39:26.772  7567  7593 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 17:39:26.772  1017  1017 D SettingsProvider: name = bluetooth_name
,08-25 17:39:26.772  7567  7567 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 17:39:26.772  1017  1463 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-25 17:39:26.772  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 17:39:26.782  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:26.782  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:26.782  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:26.782  7567  7580 I bluedroid: config_hci_snoop_log
,08-25 17:39:26.782  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 17:39:26.782  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-25 17:39:26.782  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-25 17:39:26.782  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-25 17:39:26.792  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 17:39:26.792  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 17:39:26.792  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 17:39:26.792  7567  7567 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-25 17:39:26.792  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-25 17:39:26.802  7567  7590 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-25 17:39:26.802  7567  7590 D BluetoothAdapterProperties: Setting state to 11
,08-25 17:39:26.802  7567  7590 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 17:39:26.802  1017  3397 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 17:39:26.802  7567  7590 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 17:39:26.802  7567  7590 D BluetoothAdapterService: updateAdapterState state is 11
,08-25 17:39:26.802  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:26.802  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
08-25 17:39:26.802  7567  7590 D BluetoothAdapterService: Autoconnection is available 
08-25 17:39:26.802  7567  7590 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-25 17:39:26.812  7567  7590 D BluetoothSecureManager: getInstant: null
08-25 17:39:26.812  7567  7590 D BluetoothSecureManager: calling getMethod for getService
08-25 17:39:26.812  7567  7590 D BluetoothSecureManager: calling getService
,08-25 17:39:26.812  7567  7590 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@6181f7e
,08-25 17:39:26.812  1017  4790 D BluetoothSecureManagerService: isSecureModeEnabled
,08-25 17:39:26.812  1017  4790 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-25 17:39:26.812  7567  7590 D BtConfig.SecureMode: isSecureModeOn:false
08-25 17:39:26.812  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-25 17:39:26.812  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 17:39:26.812  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:26.812  1179  1179 D BluetoothTile:  getBluetoothState : 11
,08-25 17:39:26.812  7567  7590 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-25 17:39:26.812  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 17:39:26.812  7567  7590 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-25 17:39:26.812  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-25 17:39:26.812  7567  7590 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-25 17:39:26.812  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 17:39:26.812  1873  1873 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 17:39:26.822  7567  7590 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-25 17:39:26.822  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 17:39:26.822  7567  7590 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-25 17:39:26.822  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-25 17:39:26.822  1017  1135 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 17:39:26.822  7567  7590 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-25 17:39:26.822  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 17:39:26.822  7567  7590 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-25 17:39:26.822  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 17:39:26.822  3293  3293 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:26.822  1017  1327 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 17:39:26.822  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
08-25 17:39:26.822  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 17:39:26.822  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 17:39:26.822  7567  7590 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-25 17:39:26.822  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 17:39:26.822  7567  7590 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:26.822  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 17:39:26.822  7567  7590 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:26.822  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 17:39:26.832  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:26.832  7567  7590 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-25 17:39:26.832  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 17:39:26.832  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 17:39:26.832  1017  1761 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 17:39:26.832  7567  7590 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-25 17:39:26.832  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 17:39:26.832  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:26.832  7567  7590 D BluetoothBondStateMachine: make
08-25 17:39:26.832  1017  1761 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:26.832  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:26.832  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 17:39:26.832  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 17:39:26.832  7567  7590 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-25 17:39:26.832  7567  7594 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 17:39:26.842  3293  3293 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 17:39:26.842  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 17:39:26.842  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:26.842  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-25 17:39:26.842  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:26.852  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:26.852  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:26.852  7567  7567 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 17:39:26.852  7567  7567 D BtGatt.GattService: Received start request. Starting profile...
08-25 17:39:26.852  7567  7567 D BtGatt.GattService: start()
08-25 17:39:26.852  7567  7567 D BtGatt.GattService: start()
08-25 17:39:26.852  7567  7567 I bluedroid: get_profile_interface gatt
,08-25 17:39:26.852  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16002f01
08-25 17:39:26.852  7567  7567 D BtGatt.AdvertiseManager: advertise manager created
,08-25 17:39:26.852  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 17:39:26.852  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 17:39:26.852  7567  7590 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-25 17:39:26.852  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:26.852  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-25 17:39:26.852  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:26.852  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:26.852  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:26.862  7567  7567 D BtGatt.GattService: mStartError = false
,08-25 17:39:26.862  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16002f01
08-25 17:39:26.862  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:26.862  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11,
,08-25 17:39:26.862  7567  7567 D HeadsetService: Received start request. Starting profile...
08-25 17:39:26.862  7567  7567 D HeadsetService: start()
,08-25 17:39:26.872  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 17:39:26.872  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 17:39:26.872  7567  7590 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-25 17:39:26.872  7567  7567 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:39:26.872  7567  7567 D HeadsetStateMachine: make
,08-25 17:39:26.872  7567  7567 E HeadsetStateMachine: # of Max HF connection is 2
,08-25 17:39:26.882  1017  4787 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:26.882  1017  4787 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 17:39:26.882  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:26.882  1017  4787 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:26.882  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:26.882  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-25 17:39:26.882  1017  1248 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-25 17:39:26.882  1017  1248 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-25 17:39:26.882  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 17:39:26.882  7567  7590 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-25 17:39:26.882  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:26.882  1017  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:26.882  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 17:39:26.882  1017  1456 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:26.882  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 17:39:26.882  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:26.882  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:26.882  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:26.892  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-25 17:39:26.892  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 17:39:26.892  7567  7590 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 17:39:26.892  1017  1463 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-25 17:39:26.892  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-25 17:39:26.892  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:26.892  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:26.892  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 17:39:26.892  1017  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:26.892  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 17:39:26.892  7567  7567 I bluedroid: get_profile_interface handsfree
08-25 17:39:26.892  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:26.892  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:26.892  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:26.902  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 17:39:26.902  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 17:39:26.902  7567  7590 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 17:39:26.902  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:26.902  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 17:39:26.902  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:26.902  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:26.902  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:26.902  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-25 17:39:26.902  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 17:39:26.902  7567  7590 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 17:39:26.902  1017  4789 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:26.902  1017  4789 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 17:39:26.912  1017  4789 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:26.912  1017  4789 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:26.912  1017  4789 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:26.912  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-25 17:39:26.912  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 17:39:26.912  7567  7590 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 17:39:26.912  1017  1248 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:26.912  1017  1248 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 17:39:26.912  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:26.912  1017  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:26.912  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 17:39:26.912  7567  7567 I DualScoManager: Instantiating Dual Sco Manager
08-25 17:39:26.912  7567  7567 I DualScoManager: Set HeadsetServiceHelper
,08-25 17:39:26.912  7567  7567 D BluetoothAtMessage: createCMTIContentObservers
,08-25 17:39:26.912  1017  1474 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-25 17:39:26.912  1017  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:26.912  1017  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:26.912  1017  1474 D SettingsProvider: selectionArgs: false
08-25 17:39:26.912  1017  1474 D SettingsProvider: selectionArgs: 1002
08-25 17:39:26.912  1017  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:26.912  1017  1474 D SettingsProvider: ret = -1
,08-25 17:39:26.912  7567  7598 D HeadsetStateMachine: Enter Disconnected: -2
,08-25 17:39:26.912  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 17:39:26.912  7567  7567 D HeadsetService: mStartError = false
08-25 17:39:26.912  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16002f01
08-25 17:39:26.912  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 17:39:26.922  7567  7590 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 17:39:26.922  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:26.922  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:26.922  7567  7590 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 17:39:26.922  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 17:39:26.922  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 17:39:26.922  7567  7590 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 17:39:26.922  7567  7590 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 17:39:26.922  7567  7590 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 17:39:26.922  7567  7590 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 17:39:26.922  7567  7590 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 17:39:26.922  7567  7567 E BluetoothAdapterService(369110785): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-25 17:39:26.922  7567  7598 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-25 17:39:26.922  7567  7598 D HeadsetStateMachine: map size, before remove : 0
,08-25 17:39:26.922  7567  7598 D HeadsetStateMachine: map size, after remove: 0
,08-25 17:39:26.932  7567  7567 D A2dpService: Received start request. Starting profile...
08-25 17:39:26.932  7567  7567 D A2dpService: start()
,08-25 17:39:26.932  7567  7567 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 17:39:26.932  7567  7567 I bluedroid: get_profile_interface avrcp
,08-25 17:39:26.932  1017  2069 V SAMP_SPCM_test: CSC File load.. 
,08-25 17:39:26.942  1993  1993 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 17:39:26.942  7567  7567 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 17:39:26.942  7567  7567 D Avrcp   : Initialize Media Controller
08-25 17:39:26.942  7567  7567 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-25 17:39:26.942  7567  7567 E Avrcp   : getActiveSessions
,08-25 17:39:26.952  7567  7567 D Avrcp   : pick active media Controller
08-25 17:39:26.952  7567  7567 D Avrcp   : Get the active Media Controller 
,08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-25 17:39:26.952  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-25 17:39:26.982  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
,08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
,08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
,08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-25 17:39:26.992  1017  2069 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-25 17:39:26.992  1993  1993 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 17:39:27.012  1017  2069 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-25 17:39:27.012  1017  2069 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:27.012  1017  2069 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:27.012  1017  2069 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:27.012  1017  2069 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:27.012  7567  7567 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-25 17:39:27.012  7567  7602 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-25 17:39:27.012  7567  7567 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:39:27.012  7567  7567 D A2dpStateMachine: make
,08-25 17:39:27.022  7567  7567 I bluedroid: get_profile_interface a2dp
,08-25 17:39:27.022  7605  7605 E Zygote  : MountEmulatedStorage(),
08-25 17:39:27.022  7605  7605 I libpersona: KNOX_SDCARD checking this for 1000,
08-25 17:39:27.022  7605  7605 E Zygote  : v2
08-25 17:39:27.022  7605  7605 I libpersona: KNOX_SDCARD not a persona,
,08-25 17:39:27.022  7567  7604 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 17:39:27.022  7605  7605 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 17:39:27.022  7605  7605 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:27.032  7605  7605 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 17:39:27.032  1017  2069 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7605 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 17:39:27.032  7567  7567 E bt-btif : warning : media task started media_task_refcnt 1 
,08-25 17:39:27.032  7567  7567 D A2dpService: mStartError = false
08-25 17:39:27.032  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16002f01
,08-25 17:39:27.032  7567  7567 D HeadsetStateMachine: Try to query the phonestate on bind
08-25 17:39:27.032  1424  1445 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 17:39:27.032  1424  1424 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-25 17:39:27.032  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 17:39:27.032  7567  7603 D A2dpStateMachine: Enter Disconnected: -2
08-25 17:39:27.032  1424  1445 I Telecom : BluetoothPhoneService: Result of Message : true
,08-25 17:39:27.032  7567  7567 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 17:39:27.042  7567  7567 D HidService: Received start request. Starting profile...
08-25 17:39:27.042  7567  7567 D HidService: start()
08-25 17:39:27.042  7567  7567 I bluedroid: get_profile_interface hidhost
08-25 17:39:27.042  7567  7567 D HidService: setHidService(): set to: null
08-25 17:39:27.042  7567  7567 D HidService: mStartError = false
08-25 17:39:27.042  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16002f01
,08-25 17:39:27.042  7567  7567 D HeadsetStateMachine: Proxy object connected
08-25 17:39:27.042  7567  7567 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 17:39:27.042  7567  7567 D HealthService: Received start request. Starting profile...
08-25 17:39:27.042  7567  7567 D HealthService: start()
,08-25 17:39:27.042  7567  7602 D BluetoothMediaBrowser: no now playing list
,08-25 17:39:27.042  7567  7602 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-25 17:39:27.042  7567  7567 I bluedroid: get_profile_interface health
08-25 17:39:27.042  7567  7567 D HealthService: mStartError = false
08-25 17:39:27.042  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16002f01
,08-25 17:39:27.052  7567  7567 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 17:39:27.052  7567  7567 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0,
08-25 17:39:27.052  7567  7598 D HeadsetStateMachine: Disconnected process message: 11
,08-25 17:39:27.052  7567  7567 D PanService: Received start request. Starting profile...
08-25 17:39:27.052  7567  7567 D PanService: start()
08-25 17:39:27.052  7567  7567 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-25 17:39:27.052  7567  7567 I bluedroid: get_profile_interface pan
,08-25 17:39:27.052  7567  7567 D PanService: mStartError = false
,08-25 17:39:27.052  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16002f01
08-25 17:39:27.052  7567  7567 D HeadsetPhoneState: sendDeviceDataStateChanged
08-25 17:39:27.052  7567  7598 D HeadsetStateMachine: Disconnected process message: 18
08-25 17:39:27.052  7567  7567 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-25 17:39:27.052  7567  7567 D BluetoothMapService: Received start request. Starting profile...
,08-25 17:39:27.052  7567  7567 D BluetoothMapService: start()
,08-25 17:39:27.052  7567  7567 D BluetoothMapService: mStartError = false
08-25 17:39:27.052  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16002f01
,08-25 17:39:27.052  7567  7567 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-25 17:39:27.062  7567  7567 D SapService: Received start request. Starting profile...
08-25 17:39:27.062  7567  7567 D SapService: start()
08-25 17:39:27.062  7567  7567 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-25 17:39:27.062  7567  7567 I bluedroid: get_profile_interface sap
08-25 17:39:27.062  7567  7567 D SapService: mStartError = false
08-25 17:39:27.062  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16002f01
08-25 17:39:27.062  7567  7567 E BluetoothAdapterService(369110785): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-25 17:39:27.062  7567  7567 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 17:39:27.062  7567  7567 D BluetoothA2dp: Proxy object connected
08-25 17:39:27.062  7567  7598 D HeadsetStateMachine: Disconnected process message: 10
08-25 17:39:27.062  7567  7567 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-25 17:39:27.062  7567  7567 E BluetoothAdapterService(369110785): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-25 17:39:27.062  7567  7598 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 17:39:27.062  7567  7567 E BluetoothAdapterService(369110785): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-25 17:39:27.062  7567  7598 D HeadsetStateMachine: Disconnected process message: 11
08-25 17:39:27.062  7605  7605 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:27.062  7605  7605 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:27.062  7567  7567 E BluetoothAdapterService(369110785): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-25 17:39:27.062  7567  7567 E BluetoothAdapterService(369110785): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-25 17:39:27.082  7605  7605 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 17:39:27.082  7567  7567 E BluetoothAdapterService(369110785): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-25 17:39:27.082  7567  7567 E BluetoothAdapterService(369110785): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-25 17:39:27.092  7567  7590 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-25 17:39:27.092  7567  7590 I bluedroid: enable
,08-25 17:39:27.092  7567  7590 I bt_hci_bdroid: init
,08-25 17:39:27.092  7567  7590 I bt_vendor: bt-vendor : init
,08-25 17:39:27.092  7567  7590 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 17:39:27.092  7567  7590 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 17:39:27.092  7567  7590 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-25 17:39:27.092  7567  7590 D bt_userial_mct: userial_init
,08-25 17:39:27.092  7567  7623 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 17:39:27.092  7567  7590 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-25 17:39:27.092  7567  7590 I bt_vendor: Starting hciattach daemon
08-25 17:39:27.092  7567  7590 I bt_vendor: try to set false
,08-25 17:39:27.092  7567  7590 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
08-25 17:39:27.092  7567  7590 I bt_vendor: Starting hciattach daemon
08-25 17:39:27.092  7567  7590 I bt_vendor: try to set true
,08-25 17:39:27.112  7627  7627 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 17:39:27.112   288   288 E SMD     : DCD OFF
,08-25 17:39:27.142   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 17:39:27.142  1017  2069 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72,
,08-25 17:39:27.162  7633  7633 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-25 17:39:27.172  7634  7634 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-25 17:39:27.192  7636  7636 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 17:39:27.192  7637  7637 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-25 17:39:27.202  7638  7638 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 17:39:27.212  7639  7639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-25 17:39:27.552  7642  7642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-25 17:39:27.562  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-25 17:39:27.602  7567  7590 I bt_vendor: bluetooth satus is on,
08-25 17:39:27.602  7567  7625 D bt_userial_mct: userial_open(port:0)
08-25 17:39:27.602  7567  7625 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 17:39:27.602  7567  7625 I bt_vendor: Done intiailizing UART
,08-25 17:39:27.602  7567  7625 I bt_vendor: Done intiailizing UART,
08-25 17:39:27.602  7567  7625 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 17:39:27.602  7567  7625 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
08-25 17:39:27.612  7567  7645 D bt_userial_mct: Entering userial_read_thread()
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_L2CAP,
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_A2D,
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_SAP
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_GATT,
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 17:39:27.612  7567  7623 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-25 17:39:27.702  7567  7623 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-25 17:39:27.702  7567  7623 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40beed1 
,08-25 17:39:27.702  7567  7623 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40beed1 
,08-25 17:39:27.722  7567  7593 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-25 17:39:27.722  7567  7593 E bt-btif : Calling BTA_HhEnable
,08-25 17:39:27.722  7567  7593 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-25 17:39:27.732  7567  7593 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-25 17:39:27.732  7567  7593 E BluetoothServiceJni: populateRssiValuesNative
08-25 17:39:27.732  7567  7593 I bluedroid: getModelRssiValues
08-25 17:39:27.732  7567  7593 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-25 17:39:27.732  7567  7593 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 17:39:27.732  7567  7593 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 17:39:27.732  1017  1017 D SettingsProvider: name = bluetooth_name
,08-25 17:39:27.742  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:27.742  7567  7593 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-25 17:39:27.742  7567  7593 D BluetoothAdapterProperties: Scan Mode:20
,08-25 17:39:27.742  7567  7593 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 17:39:27.742  7567  7593 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-25 17:39:27.742  7567  7593 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-25 17:39:27.742  7567  7593 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-25 17:39:27.742  7567  7593 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-25 17:39:27.742  7567  7593 E bt-btif : btif_sock_init: !vhci_init
,08-25 17:39:27.752  7567  7593 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-25 17:39:27.752  7567  7593 D IOP_DB_BT: db_open: db_open : handle 3028238352l, read 13894 bytes onto local cache
08-25 17:39:27.752  7567  7593 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-25 17:39:27.752  7567  7645 E bt_mct  : hci lib postload completed
,08-25 17:39:27.752  7567  7593 D IOP_DB_BT: db_query: result 1
08-25 17:39:27.752  7567  7593 I         : iop_db_open: iop_db_open status 0
08-25 17:39:27.752  7567  7593 D bte_conf: Device ID record 1 : primary
,08-25 17:39:27.752  7567  7593 D bte_conf:   vendorId            = 0075
08-25 17:39:27.752  7567  7593 D bte_conf:   vendorIdSource      = 0001
08-25 17:39:27.752  7567  7593 D bte_conf:   product             = 0100
08-25 17:39:27.752  7567  7593 D bte_conf:   version             = 0200
08-25 17:39:27.752  7567  7593 D bte_conf:   clientExecutableURL = 
08-25 17:39:27.752  7567  7593 D bte_conf:   serviceDescription  = 
08-25 17:39:27.752  7567  7593 D bte_conf:   documentationURL    = 
08-25 17:39:27.752  7567  7593 D bte_conf: bte_load_did_conf no section named DID2.
,08-25 17:39:27.752  7567  7593 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 17:39:27.752  7567  7590 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-25 17:39:27.752  7567  7590 D BluetoothAdapterProperties: ScanMode =  20
,08-25 17:39:27.762  7567  7590 D BluetoothAdapterProperties: State =  11
,08-25 17:39:27.762  1017  1030 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 17:39:27.762  7567  7590 D BluetoothAdapterProperties: Setting state to 12
,08-25 17:39:27.762  7567  7590 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 17:39:27.762  7567  7593 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 17:39:27.762  7567  7593 D BluetoothAdapterProperties: Scan Mode:21
08-25 17:39:27.762  7567  7593 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 17:39:27.762  1017  1761 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-25 17:39:27.772  1017  1761 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:27.772  1017  1761 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:27.772  1017  1761 D SettingsProvider: selectionArgs: false
08-25 17:39:27.772  1017  1761 D SettingsProvider: selectionArgs: 1002
08-25 17:39:27.772  1017  1761 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:27.772  1017  1761 D SettingsProvider: ret = -1
,08-25 17:39:27.772  7567  7590 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 17:39:27.772  7567  7590 D BluetoothAdapterService: updateAdapterState state is 12
,08-25 17:39:27.772  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:27.772  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 17:39:27.772  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:27.772  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:27.772  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:27.782  7567  7590 D BluetoothAdapterService: Autoconnection is available 
,08-25 17:39:27.782  7567  7590 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-25 17:39:27.782  7567  7590 D BluetoothAdapterService: starting service from this receiver
,08-25 17:39:27.782  3293  3301 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 17:39:27.782  1017  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 17:39:27.782  1017  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 17:39:27.792  1017  1327 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:27.792  1017  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:27.792  1017  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:27.792  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-25 17:39:27.792  7567  7590 I BluetoothAdapterState: Entering On State from state = 11
,08-25 17:39:27.792  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 17:39:27.792  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:27.792  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:27.792  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:27.802  1439  1464 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:27.802  1439  1464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 17:39:27.802  7567  7577 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 17:39:27.802  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:27.802  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:27.802  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:27.802  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:27.802  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:27.802  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:27.802  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:27.802  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:27.802  1424  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 17:39:27.802  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 17:39:27.802  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 17:39:27.802  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:27.802  7567  7567 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-25 17:39:27.802  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:27.802  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:27.802  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:27.802  1424  1453 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 17:39:27.812  3293  7536 D BluetoothPan: Binding service...
,08-25 17:39:27.812  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-25 17:39:27.812  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 17:39:27.812  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:27.812  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:27.812  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 17:39:27.812  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 17:39:27.812  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-25 17:39:27.812  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-25 17:39:27.812  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 17:39:27.812  6770  6964 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:27.812  6770  6964 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:27.812  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:27.812  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:27.812  1017  1017 D BluetoothA2dp: Proxy object connected
08-25 17:39:27.812  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 17:39:27.812  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 17:39:27.812  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-25 17:39:27.812  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 17:39:27.812  1993  2007 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:27.812  1993  2007 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:27.812  1017  1046 D BluetoothPan: Binding service...
,08-25 17:39:27.812  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 17:39:27.812  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 17:39:27.812  3293  3304 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 17:39:27.932  1017  3362 D SSRM:n  : SIOP:: AP = 340
,08-25 17:39:27.972  1017  1046 I art     : Explicit concurrent mark sweep GC freed 28762(1652KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.380ms total 150.915ms
08-25 17:39:27.972  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-25 17:39:27.972  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-25 17:39:27.972  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:27.972  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:27.972  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-25 17:39:27.972  7567  7567 I BluetoothPbapService: Handler(): got msg=1
08-25 17:39:27.972  3293  3293 D BluetoothMap: Proxy object connected
08-25 17:39:27.972  3293  7536 D Bluetoothsap: onBluetoothStateChange: up=true
08-25 17:39:27.972  3293  7536 D Bluetoothsap: Binding service...
08-25 17:39:27.972  3293  3293 D MapProfile: Bluetooth service connected
08-25 17:39:27.972  3293  3293 D BluetoothMap: getConnectedDevices()
08-25 17:39:27.972  1017  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-25 17:39:27.972  3293  7536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-25 17:39:27.982  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-25 17:39:27.982  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-25 17:39:27.982  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:27.982  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:27.982  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-25 17:39:27.982  3293  7536 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-25 17:39:27.982  1424  3263 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-25 17:39:27.982  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 17:39:27.982  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:27.982  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-25 17:39:27.982  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:27.982  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-25 17:39:27.982  1424  3263 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 17:39:27.982  7567  7580 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:27.982  7567  7580 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:27.982  7567  7650 V BluetoothPbapService: PBAP Service initSocket try: 0
08-25 17:39:27.982  3293  3293 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:39:27.982  3293  3293 D PanProfile: Bluetooth service connected
08-25 17:39:27.982  1455  1473 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-25 17:39:27.992  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 17:39:27.992  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-25 17:39:27.992  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:27.992  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:27.992  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-25 17:39:27.992  1455  1473 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 17:39:27.992  7478  7493 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:27.992  7478  7493 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:27.992  3293  3304 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:27.992  3293  3304 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:27.992  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:39:27.992  3293  7536 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:39:27.992  3293  7536 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-25 17:39:27.992  7567  7650 D BluetoothSocket: bindListen(): myUserId = 0
08-25 17:39:27.992  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 17:39:27.992  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 17:39:27.992  7567  7650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:39:27.992  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:27.992  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:27.992  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-25 17:39:27.992  3293  3293 D BluetoothPbap: Proxy object connected
08-25 17:39:27.992  1424  3263 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:27.992  3293  3293 D PbapServerProfile: Bluetooth service connected
08-25 17:39:27.992  3293  3293 D Bluetoothsap: BluetoothSAP Proxy object connected
08-25 17:39:27.992  3293  3293 D SapProfile: Bluetooth service connected
08-25 17:39:27.992  3293  3293 D Bluetoothsap: getConnectedDevices()
08-25 17:39:27.992  1424  3263 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:27.992  7567  7650 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-25 17:39:27.992  7567  7650 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 17:39:27.992  7567  7650 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 17:39:27.992  7567  7650 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e2d2f53
08-25 17:39:27.992  1455  1672 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:27.992  1455  1672 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:28.002  3293  3304 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 17:39:28.002  7567  7650 D BluetoothSocket: channel: 19
08-25 17:39:28.002  7567  7650 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-25 17:39:28.002  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-25 17:39:28.002  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-25 17:39:28.002  3293  3293 D BluetoothA2dp: Proxy object connected
08-25 17:39:28.002  3293  3293 D A2dpProfile: Bluetooth service connected
08-25 17:39:28.002  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:28.002  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:28.002  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-25 17:39:28.002  1179  3906 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 17:39:28.002  1179  3906 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 17:39:28.002  1424  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-25 17:39:28.002  3293  3293 D BluetoothInputDevice: Proxy object connected
08-25 17:39:28.002  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 17:39:28.002  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-25 17:39:28.002  3293  3293 D HidProfile: Bluetooth service connected
08-25 17:39:28.002  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:28.002  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:28.002  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-25 17:39:28.002  1424  1445 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 17:39:28.002  3293  7536 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-25 17:39:28.002  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 17:39:28.002  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-25 17:39:28.012  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:28.012  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:28.012  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-25 17:39:28.012  3293  3293 D HeadsetProfile: Bluetooth service connected
08-25 17:39:28.012  3293  7536 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 17:39:28.012  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-25 17:39:28.012  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-25 17:39:28.012  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:28.012  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-25 17:39:28.012  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 17:39:28.022  1424  1424 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2b6d34de, true
,08-25 17:39:28.022  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-25 17:39:28.022  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 17:39:28.022  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 17:39:28.022  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 17:39:28.022  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:28.032  1179  1179 D BluetoothTile:  getBluetoothState : 12
,08-25 17:39:28.032  1424  1424 D BluetoothHeadset: registerMessageListener
,08-25 17:39:28.032  1873  1873 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 17:39:28.032  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 17:39:28.032  1179  1760 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 17:39:28.032  1017  1497 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-25 17:39:28.032  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 17:39:28.032  3293  3293 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:28.042  1017  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:28.042  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 17:39:28.042  7567  7575 D HeadsetService: registerMessageListener
,08-25 17:39:28.042  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:28.042  7567  7575 D HeadsetService: registerMessageListener
,08-25 17:39:28.042  1424  1424 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-25 17:39:28.042  7567  7598 D HeadsetStateMachine: Disconnected process message: 70
08-25 17:39:28.042  7567  7598 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3adaa090
08-25 17:39:28.042  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 17:39:28.042  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:28.042  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:28.042  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:28.052  1424  1424 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-25 17:39:28.052  1424  1424 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-25 17:39:28.052  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-25 17:39:28.052  3293  3293 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-25 17:39:28.052  3293  3293 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-25 17:39:28.052  3293  3293 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-25 17:39:28.052  3293  3293 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-25 17:39:28.052  7567  7598 D HeadsetStateMachine: Disconnected process message: 9
,08-25 17:39:28.052  7567  7598 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-25 17:39:28.052  7567  7651 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-25 17:39:28.062   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-25 17:39:28.062   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-25 17:39:28.062   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-25 17:39:28.062   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-25 17:39:28.062   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-25 17:39:28.062   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-25 17:39:28.062   283   283 V audio_hw_primary: adev_set_parameters: exit
,08-25 17:39:28.062  7567  7598 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-25 17:39:28.072  7567  7651 D BluetoothSocket: bindListen(): myUserId = 0
,08-25 17:39:28.072  7567  7651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:28.072  3293  3293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 17:39:28.072  7567  7651 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-25 17:39:28.072  7567  7651 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 17:39:28.072  7567  7651 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 17:39:28.072  7567  7651 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b626d89
08-25 17:39:28.072  1017  1481 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 17:39:28.072  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 17:39:28.072  7567  7651 D BluetoothSocket: channel: 5
08-25 17:39:28.072  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:28.072  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:28.072  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 17:39:28.082  3293  3293 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:39:28.082  3293  3293 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 17:39:28.092  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:28.092  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-25 17:39:28.092  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16002f01
,08-25 17:39:28.092  7567  7567 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 17:39:28.102  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 17:39:28.102  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-25 17:39:28.102  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:28.102  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:28.102  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-25 17:39:28.112  1993  1993 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 17:39:28.112  1017  4787 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:28.112  1017  4787 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 17:39:28.112  1017  4787 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:28.112  1017  4787 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 17:39:28.122  1017  4787 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:28.122  1017  4790 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 17:39:28.132  1993  1993 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 17:39:28.132  1993  7660 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 17:39:28.132  1017  1463 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:28.142  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:28.142  1017  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 17:39:28.142  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:28.142   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-25 17:39:28.152  7567  7661 D BluetoothSocket: bindListen(): myUserId = 0
,08-25 17:39:28.152  7567  7661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:28.152  7567  7661 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,08-25 17:39:28.152  7567  7661 D BluetoothSocket: bindListen(), new LocalSocket 
,08-25 17:39:28.152  7567  7661 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 17:39:28.162  7567  7661 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b7b5945
,08-25 17:39:28.162  7567  7661 D BluetoothSocket: channel: 12
,08-25 17:39:28.162  1017  1248 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 17:39:28.162  7567  7661 I BtOppRfcommListener: Accept thread started.
,08-25 17:39:28.162  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:28.162  1017  1248 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:28.162  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:28.172  1993  7660 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-25 17:39:28.742  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:28.742  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:28.742  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:28.742  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:28.742  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:28.742  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:28.742  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:28.742  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:28.742  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:28.742  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:28.742  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37f0f742 added. We now have 8 listener(s)
,08-25 17:39:28.742  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:28.752  1017  1456 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 17:39:28.752  1017  1456 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-25 17:39:28.752  1017  1456 D SecContentProvider2: mCursor = null
,08-25 17:39:28.752  1017  1456 D WifiService: setWifiEnabled: false pid=6770, uid=10171
,08-25 17:39:28.752  1017  1456 D SettingsProvider: name = wifi_on
,08-25 17:39:28.762  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:28.762  1017  1497 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 17:39:28.762  1017  1497 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-25 17:39:28.762  1017  1497 D SecContentProvider2: mCursor = null
,08-25 17:39:28.762  1017  1497 D WifiService: setWifiEnabled: true pid=6770, uid=10171
,08-25 17:39:28.762  1017  1497 W ActivityManager: Permission Denial: getCurrentUser() from pid=6770, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 17:39:28.762  1017  1497 W WifiService: Failed getting userId using ActivityManagerNative
08-25 17:39:28.762  1017  1497 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6770, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 17:39:28.762  1017  1497 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 17:39:28.762  1017  1497 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 17:39:28.762  1017  1497 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 17:39:28.762  1017  1497 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 17:39:28.762  1017  1497 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 17:39:28.762  1017  1497 D SettingsProvider: name = wifi_on
,08-25 17:39:28.772  1017  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-25 17:39:29.102  1017  1044 D Tethering: interfaceAdded wlan0
,08-25 17:39:29.102  1017  1130 E Tethering: No numeric data
,08-25 17:39:29.112  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 17:39:29.112  1017  1130 D Tethering: clearTetheredNotification()
,08-25 17:39:29.112  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 17:39:29.112  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:29.112  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:29.112  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 17:39:29.112  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 17:39:29.112  1017  1124 V NetworkStats: performPollLocked() took 6ms
08-25 17:39:29.112  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 17:39:29.112  1179  1179 D HotspotTile: updateTetherState():false, false
08-25 17:39:29.122  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:29.122  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-25 17:39:29.122  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:29.122  1017  1130 D Tethering: InitialState.processMessage what=4
,08-25 17:39:29.122  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:29.122  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:29.132  1017  1130 E Tethering: No numeric data
,08-25 17:39:29.132  1017  1044 D Tethering: interfaceAdded p2p0,
08-25 17:39:29.132  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-25 17:39:29.132  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 17:39:29.132  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-25 17:39:29.132  1179  1179 D HotspotTile: updateTetherState():false, false
08-25 17:39:29.142  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 17:39:29.142  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 17:39:29.142  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-25 17:39:29.142  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 17:39:29.142  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:29.142  1017  1130 D Tethering: clearTetheredNotification()
,08-25 17:39:29.142   278   987 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-25 17:39:29.142  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:29.142  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 17:39:29.142   278   987 D SoftapController: Softap fwReload - Ok
,08-25 17:39:29.142   278   987 D CommandListener: Setting iface cfg
08-25 17:39:29.142   278   987 D CommandListener: Trying to bring down wlan0
,08-25 17:39:29.142   278   987 D CommandListener: Clearing all IP addresses on wlan0
,08-25 17:39:29.152  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:29.152  1017  1124 V NetworkStats: performPollLocked() took 6ms
,08-25 17:39:29.152  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:29.152  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:29.152  1017  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-25 17:39:29.162  1017  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-25 17:39:29.162  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:29.162  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 17:39:29.162  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:29.162  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:29.162  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 17:39:29.162  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:29.162  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:29.162  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:29.162  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:29.162  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-25 17:39:29.162  1179  1179 D HotspotTile: onReceive : 2, 0
,08-25 17:39:29.172  3293  3293 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:39:29.182  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:29.182  1017  1481 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 17:39:29.182  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:29.182  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:29.182  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:29.182  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:29.192  1620  1620 I Hs20UtilService: Starting #19
08-25 17:39:29.192  1620  1652 I Hs20UtilService: Message received 5011
,08-25 17:39:29.192  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 17:39:29.192  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 17:39:29.192  6587  6587 D SecurityLogAgent: StateMachine : Current State = 1
08-25 17:39:29.192  6587  6587 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 17:39:29.202  7673  7673 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-25 17:39:29.202  7673  7673 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 17:39:29.202  7673  7673 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-25 17:39:29.212  7673  7673 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-25 17:39:29.212   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7673,
08-25 17:39:29.212   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-25 17:39:29.212  7673  7673 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-25 17:39:29.212  7673  7673 I wpa_supplicant: ssSupport state is = 1
08-25 17:39:29.212  7673  7673 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-25 17:39:29.212  7673  7673 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-25 17:39:29.212   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7673
08-25 17:39:29.212   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-25 17:39:29.352   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-25 17:39:29.352  7673  7673 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-25 17:39:29.402  7673  7673 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 17:39:29.402  7673  7673 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-25 17:39:29.412  7673  7673 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-25 17:39:29.412   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7673
08-25 17:39:29.412   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-25 17:39:29.412  7673  7673 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-25 17:39:29.412  7673  7673 I wpa_supplicant: ssSupport state is = 1
,08-25 17:39:29.412  7673  7673 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 17:39:29.412  7673  7673 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 17:39:29.412  7673  7673 E wpa_supplicant: SIM READ ERROR
08-25 17:39:29.412  7673  7673 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 17:39:29.412  7673  7673 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-25 17:39:29.412  7673  7673 E wpa_supplicant: SIM READ ERROR
08-25 17:39:29.412  7673  7673 I wpa_supplicant: Blacklist: Clear (all) 
08-25 17:39:29.412  7673  7673 I wpa_supplicant: wpa_default_ap_write_once
08-25 17:39:29.412  7673  7673 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 17:39:29.412  7673  7673 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 17:39:29.412  7673  7673 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-25 17:39:29.412  7673  7673 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 17:39:29.412  7673  7673 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 17:39:29.412  7673  7673 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-25 17:39:29.412  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 17:39:29.412  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:29.412  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:29.452  7673  7673 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-25 17:39:29.582  7673  7673 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-25 17:39:29.582  7673  7673 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-25 17:39:29.592  7673  7673 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-25 17:39:29.592   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7673
08-25 17:39:29.592   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-25 17:39:29.592  7673  7673 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-25 17:39:29.592  7673  7673 I wpa_supplicant: ssSupport state is = 1
,08-25 17:39:29.592  7673  7673 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 17:39:29.602  7673  7673 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-25 17:39:29.612  7673  7673 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-25 17:39:29.612   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7673
08-25 17:39:29.612   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-25 17:39:29.612  7673  7673 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-25 17:39:29.612  7673  7673 I wpa_supplicant: ssSupport state is = 1
,08-25 17:39:29.612  7673  7673 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 17:39:29.612  7673  7673 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 17:39:29.612  7673  7673 E wpa_supplicant: SIM READ ERROR,
08-25 17:39:29.612  7673  7673 I wpa_supplicant: wpa_default_ap_write_once
08-25 17:39:29.622  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 17:39:29.612  7673  7673 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 17:39:29.622  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 17:39:29.612  7673  7673 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 17:39:29.622  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 17:39:29.622  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-25 17:39:29.622  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-25 17:39:29.622  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-25 17:39:29.662  7673  7673 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-25 17:39:29.662  7673  7673 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-25 17:39:30.112   288   288 E SMD     : DCD OFF
,08-25 17:39:30.122  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 17:39:30.122  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 17:39:30.122  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-25 17:39:30.202  7673  7673 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-25 17:39:30.202  7673  7673 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-25 17:39:30.202  7673  7673 I wpa_supplicant: Skip scan - bUseNetwork false
08-25 17:39:30.202  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-25 17:39:30.212  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21],
,08-25 17:39:30.212  7673  7673 I wpa_supplicant: HOTSPOT20_ENABLE called
08-25 17:39:30.212  7673  7673 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-25 17:39:30.212  7673  7673 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 17:39:30.212  7673  7673 E wpa_supplicant: SIM READ ERROR
,08-25 17:39:30.212  7673  7673 I wpa_supplicant: Blacklist: Clear (all) ,
,08-25 17:39:30.232  7673  7673 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
08-25 17:39:30.242  7673  7673 I wpa_supplicant: Skip scan - bUseNetwork false
08-25 17:39:30.242  1017  1127 D WifiConfigStore: Loading config and enabling all networks 
08-25 17:39:30.242  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 17:39:30.242  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 17:39:30.242  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:30.242  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:30.242  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:30.242  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:30.242  1179  1760 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 17:39:30.242  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:30.252  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:30.242  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-25 17:39:30.252  1179  1179 D HotspotTile: onReceive : 3, 0
08-25 17:39:30.252  3293  3293 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-25 17:39:30.252  1017  1127 E WifiConfigStore: Not a HS20
08-25 17:39:30.252  1017  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 17:39:30.262  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:30.262  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:30.262  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:30.262  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:30.262  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:30.262  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:30.262  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:30.262  6770  6770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:30.262  1017  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
08-25 17:39:30.262  1017  1135 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:30.262  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 17:39:30.262  6770  6770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:39:30.262  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:30.262  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:30.262  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 17:39:30.262  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-25 17:39:30.262  7673  7673 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-25 17:39:30.262  7673  7673 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-25 17:39:30.262  7673  7673 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 17:39:30.262  7673  7673 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 17:39:30.262  7673  7673 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-25 17:39:30.262  7673  7673 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-25 17:39:30.262  7673  7673 I wpa_supplicant: First Scan Start
08-25 17:39:30.262  7673  7673 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-25 17:39:30.262  1017  1127 D WifiNative-wlan0: Setting external_sim to 1
08-25 17:39:30.262  1620  1620 I Hs20UtilService: Starting #20
08-25 17:39:30.272  1017  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 17:39:30.272  1017  1127 I WifiNative-HAL: startHal
08-25 17:39:30.272  1017  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d56688c
08-25 17:39:30.272  1017  1127 I WifiNative-HAL: Could not start hal
08-25 17:39:30.272  7017  7017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:39:30.272  1620  1652 I Hs20UtilService: Message received 5011
08-25 17:39:30.272  1017  1127 E WifiNative-wlan0: do suspend true
08-25 17:39:30.272  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
08-25 17:39:30.272  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-25 17:39:30.272  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 17:39:30.272   278   987 D CommandListener: Setting iface cfg
08-25 17:39:30.272   278   987 D CommandListener: Trying to bring up p2p0
08-25 17:39:30.272  1017  1150 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:39:30.272  1017  1150 I WifiNative-HAL: startHal
08-25 17:39:30.272  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9ea249bc
08-25 17:39:30.272  1017  1150 I WifiNative-HAL: Could not start hal
08-25 17:39:30.272  1017  1150 E WifiScanningService: could not start HAL
08-25 17:39:30.272  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 17:39:30.272  6587  6587 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 17:39:30.272  6587  6587 D SecurityLogAgent: StateMachine : Current State = 1
08-25 17:39:30.272  1017  1126 D WifiP2pService: P2pEnablingState
08-25 17:39:30.272  6587  6587 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-25 17:39:30.272  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 17:39:30.282  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 17:39:30.282  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 17:39:30.282  1017  1127 E WifiNative-wlan0: invaild command id : 215
08-25 17:39:30.282  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-25 17:39:30.282  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-25 17:39:30.282  1017  1126 D WifiP2pService: P2p socket connection successful
08-25 17:39:30.282  1017  1151 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:39:30.282  1017  1126 D WifiP2pService: P2pEnabledState
08-25 17:39:30.282  7673  7673 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-25 17:39:30.282  7673  7673 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-25 17:39:30.282  7673  7673 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-25 17:39:30.282  1017  1127 E WifiStateMachine: Failed to set frequency band 0
08-25 17:39:30.282  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 17:39:30.282  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 17:39:30.282  1017  1127 E WifiNative-wlan0: invaild command id : 215
08-25 17:39:30.282  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 17:39:30.282  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:30.292  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-25 17:39:30.292  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-25 17:39:30.292  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 17:39:30.292  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-25 17:39:30.292  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 17:39:30.292  1017  1047 D WifiDisplayController: disconnect
,08-25 17:39:30.292  1017  1047 D WifiDisplayController: updateConnection
08-25 17:39:30.292  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-25 17:39:30.292  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 17:39:30.292  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 17:39:30.292  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:30.302  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-25 17:39:30.302  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-25 17:39:30.302  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 17:39:30.302  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 17:39:30.302  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-25 17:39:30.302  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-25 17:39:30.302  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 17:39:30.302  1017  1248 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 17:39:30.302  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 17:39:30.302  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 17:39:30.312  1017  1126 D WifiP2pService: DeviceAddress: 0a:76:28
,08-25 17:39:30.312  3293  3293 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 17:39:30.312  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  secondary type: null
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  wps: 0
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  grpcapab: 0
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  devcapab: 0
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  status: 3
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  wfdInfo: null
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-25 17:39:30.312  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-25 17:39:30.312  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 17:39:30.312  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-25 17:39:30.312  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 17:39:30.312  3293  3293 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 17:39:30.312  3293  3905 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 17:39:30.312  7362  7362 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 17:39:30.322  7362  7362 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-25 17:39:30.322  7362  7362 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 17:39:30.322  7378  7378 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 17:39:30.332  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-25 17:39:30.332  1017  1126 D WifiP2pService: InactiveState
,08-25 17:39:30.332  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-25 17:39:30.332  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 17:39:30.332  7673  7673 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 17:39:30.332  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-25 17:39:30.332  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 17:39:30.502  1017  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 17:39:30.782  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:30.782  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:30.782  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:30.782  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:30.782  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:30.782  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:30.782  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:30.782  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:30.792  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:30.792  6770  6823 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 17:39:30.792  6770  6823 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 17:39:30.792  6770  6823 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3e71da71 Bundle[{}]
,08-25 17:39:30.792  6770  6823 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 17:39:30.792  6770  6823 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-25 17:39:30.802  6770  6823 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 17:39:30.802  6770  6823 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 17:39:30.802  6770  6823 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed,
08-25 17:39:30.802  6770  6823 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 17:39:30.802  6770  6823 I System.out: Running OutgoingSocketThread
,08-25 17:39:30.802  6770  7682 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1345)
,08-25 17:39:30.812  6770  7682 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54853
,08-25 17:39:30.812  6770  7682 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 17:39:31.502  7673  7673 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
08-25 17:39:31.502  7673  7673 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 17:39:31.502  7673  7673 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-25 17:39:31.502  7673  7673 I wpa_supplicant: Trying to associate with  'G700'
08-25 17:39:31.502  7673  7673 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-25 17:39:31.502  7673  7673 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-25 17:39:31.512  1017  7679 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-25 17:39:31.522  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 17:39:31.522  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:31.622  7673  7673 E wpa_supplicant: Cmd 35605 not handled
08-25 17:39:31.622  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:31.622  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:31.622  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-25 17:39:31.632  7673  7673 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-25 17:39:31.632  7673  7673 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-25 17:39:31.632  7673  7673 I wpa_supplicant: Associated with F4.99.3E
,08-25 17:39:31.632  7673  7673 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-25 17:39:31.632  7673  7673 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
,08-25 17:39:31.632  7673  7673 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-25 17:39:31.632  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 17:39:31.632  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 17:39:31.632  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
,08-25 17:39:31.632  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 17:39:31.632  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-25 17:39:31.632  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-25 17:39:31.632  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 17:39:31.632  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,08-25 17:39:31.632  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-25 17:39:31.642  1017  1130 E Tethering: No numeric data
08-25 17:39:31.642  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 17:39:31.642  1017  1130 D Tethering: clearTetheredNotification(),
08-25 17:39:31.642  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:31.642  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-25 17:39:31.642  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-25 17:39:31.642  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-25 17:39:31.642  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 17:39:31.642  1179  1179 D HotspotTile: updateTetherState():false, false
,08-25 17:39:31.652  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:31.652  1017  1124 V NetworkStats: performPollLocked() took 7ms
08-25 17:39:31.652  7673  7673 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 17:39:31.652  7673  7673 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-25 17:39:31.652  7673  7673 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-25 17:39:31.652  7673  7673 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-25 17:39:31.652  7673  7673 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 17:39:31.652  7673  7673 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-25 17:39:31.652  7673  7673 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-25 17:39:31.652  7673  7673 I wpa_supplicant: Blacklist: Clear (temp) 
08-25 17:39:31.652  7673  7673 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-25 17:39:31.652  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 17:39:31.652  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 17:39:31.652  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-25 17:39:31.652  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:31.652  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:31.662  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 17:39:31.662  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:31.662  1017  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-25 17:39:31.672  1017  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-25 17:39:31.672  1017  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-25 17:39:31.672  1017  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-25 17:39:31.672  1017  1129 E ConnectivityService: updateNetworkInfo()
08-25 17:39:31.672  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 17:39:31.672  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:31.672  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 17:39:31.682  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:31.682  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:31.682  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:31.682  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:31.682  1017  1761 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:31.682  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:31.682  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:31.682  1017  1761 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:31.682  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:31.682  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:39:31.692  1620  1620 I Hs20UtilService: Starting #21
,08-25 17:39:31.692  1620  1652 I Hs20UtilService: Message received 5007
,08-25 17:39:31.692  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 17:39:31.702  3293  3293 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 17:39:31.702  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:39:31.702  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 17:39:31.702  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-25 17:39:31.702  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-25 17:39:31.702  3293  3293 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 17:39:31.702  3293  3905 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 17:39:31.712   278   987 D CommandListener: Setting iface cfg
,08-25 17:39:31.712  1017  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,08-25 17:39:31.722  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-25 17:39:31.722  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:31.722  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-25 17:39:31.722  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:31.732  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:31.732  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 17:39:31.732  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:31.732  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:31.732  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:31.732  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:31.742  1017  1127 E WifiNative-wlan0: do suspend false
,08-25 17:39:31.742  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-25 17:39:31.752  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 17:39:31.752  1017  1127 D SecContentProvider2: mCursor = null
,08-25 17:39:31.752  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 17:39:31.812  6770  6823 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1346)
08-25 17:39:31.812  6770  6823 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1346)
,08-25 17:39:31.812  6770  6823 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1351)
,08-25 17:39:31.812  6770  6823 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 17:39:31.812  6770  6823 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1352)
,08-25 17:39:31.812  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 17:39:31.812  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bfb9353 added. We now have 2 listener(s)
,08-25 17:39:31.812  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 17:39:31.812  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:31.812  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:31.812  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:31.812  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36333490 added. We now have 9 listener(s)
08-25 17:39:31.812  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:31.822  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:39:31.832  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:31.832  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:31.832  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:31.832  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:31.832  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:31.832  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:31.832  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:31.832  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:31.832  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:31.832  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:31.842  6770  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:39:31.842  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:31.842  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f9b458e added. We now have 3 listener(s)
,08-25 17:39:31.842  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 17:39:31.842  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:31.842  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:31.842  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:31.842  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e2211af added. We now have 10 listener(s)
08-25 17:39:31.842  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:31.842  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:31.842  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:31.842  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:31.842  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:31.842  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:31.842  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:31.842  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:31.842  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bfb9353 removed from the list
08-25 17:39:31.842  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:31.842  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36333490 removed from the list
08-25 17:39:31.842  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:31.842  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:31.842  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:31.842  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:31.842  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:31.842  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:31.842  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:31.842  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36333490 not in the list
08-25 17:39:31.842  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:31.842  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:31.842  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:31.842  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:31.842  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:31.842  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e2211af removed from the list
08-25 17:39:31.842  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:31.842  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:31.842  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:31.842  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:31.842  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f9b458e removed from the list
,08-25 17:39:31.852  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 17:39:31.852  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@323f09bc added. We now have 2 listener(s)
,08-25 17:39:31.852  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 17:39:31.852  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:31.852  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:31.852  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:31.852  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d369d45 added. We now have 9 listener(s)
08-25 17:39:31.852  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:31.852  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:39:31.852  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:31.862  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:31.862  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:31.862  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:31.862  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:31.862  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:31.862  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:31.862  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:31.862  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:31.862  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:31.862  6770  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:39:31.862  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 17:39:31.862  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@398819cb added. We now have 3 listener(s)
,08-25 17:39:31.872  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 17:39:31.872  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 17:39:31.872  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:39:31.872  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:31.872  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34d105a8 added. We now have 10 listener(s)
08-25 17:39:31.872  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:31.872  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:31.872  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:39:31.872  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:39:31.872  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:31.872  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 17:39:31.882  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:39:31.882  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:39:31.882  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:39:31.892  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-25 17:39:31.892  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:39:31.892  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:39:31.892  7567  7649 D BtGatt.GattService: registerClient() - UUID=7eac9cff-77a4-4982-8297-884a7d33aa68
,08-25 17:39:31.902  1017  1042 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{59de116 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{f6b083e 6770 com.test.thalitest/10171/u0 remote:2b10d0f9}: filter unregistered
,08-25 17:39:31.902  1017  1042 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{2bd1ba97 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{f6b083e 6770 com.test.thalitest/10171/u0 remote:2b10d0f9}: filter unregistered
,08-25 17:39:31.902  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:31.902  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:31.942  7567  7593 D BtGatt.GattService: onClientRegistered() - UUID=7eac9cff-77a4-4982-8297-884a7d33aa68, clientIf=6
,08-25 17:39:31.942  6770  6780 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 17:39:31.942  7567  7577 D BtGatt.GattService: start scan with filters
,08-25 17:39:31.942  7567  7597 D BtGatt.ScanManager: handling starting scan
,08-25 17:39:31.942  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:39:31.942  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:39:31.942  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 17:39:31.942  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:39:31.952  7567  7597 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16002f01
,08-25 17:39:31.952  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:39:31.952  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 17:39:31.952  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:39:31.952  7567  7593 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-25 17:39:31.952  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:31.952  7567  7597 D BtGatt.ScanManager: allow scan with filters
08-25 17:39:31.952  7567  7597 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-25 17:39:31.952  7567  7597 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-25 17:39:31.952  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:39:31.962  6770  6823 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 17:39:31.962  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:39:31.962  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 17:39:31.962  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:31.962  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:39:31.962  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
08-25 17:39:31.962  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:39:31.962  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:31.962  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:39:31.962  7567  7593 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 17:39:31.962  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:31.962  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:39:31.962  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
08-25 17:39:31.962  7567  7597 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:39:31.962  7567  7597 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-25 17:39:31.962  7567  7649 D BtGatt.GattService: stopScan() - queue size =1
08-25 17:39:31.962  7567  7593 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 17:39:31.962  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:31.962  7687  7687 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 17:39:31.972  7567  7577 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 17:39:31.972  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,08-25 17:39:31.972  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:39:31.972  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 17:39:31.972  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:39:31.972  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:39:31.972  7567  7593 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 17:39:31.972  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:31.972  7687  7687 I dhcpcd  : version 5.5.6 starting
08-25 17:39:31.972  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:31.972  7687  7687 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 17:39:31.982  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:39:31.982  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:39:31.982  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 17:39:31.982  7567  7597 D BtGatt.ScanManager: filter size is 1
08-25 17:39:31.982  7567  7597 D BtGatt.ScanManager: delete FilterIndex - 3
,08-25 17:39:31.982  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:39:31.982  7567  7593 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 17:39:31.982  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:31.982  7567  7597 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:39:31.982  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:31.982  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:31.982  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:31.982  7567  7593 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 17:39:31.982  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:31.982  7567  7597 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 17:39:31.992  7567  7593 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 17:39:31.992  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:31.992  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:39:31.992  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:31.992  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:31.992  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:31.992  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:31.992  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:31.992  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 17:39:31.992  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@323f09bc removed from the list
08-25 17:39:31.992  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:31.992  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d369d45 removed from the list
08-25 17:39:31.992  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:31.992  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:31.992  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:31.992  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:31.992  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:31.992  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:31.992  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:31.992  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d369d45 not in the list
08-25 17:39:31.992  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:31.992  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:32.002  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:39:32.002  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:32.002  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:32.002  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34d105a8 removed from the list
08-25 17:39:32.002  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:32.002  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.002  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:32.002  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:32.002  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@398819cb removed from the list
,08-25 17:39:32.002  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:32.002  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c04d454 added. We now have 2 listener(s)
,08-25 17:39:32.002  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-25 17:39:32.002  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:32.002  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:32.002  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:32.002  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b82ffd added. We now have 9 listener(s)
08-25 17:39:32.002  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:32.002  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:39:32.012  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:32.012  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:32.012  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:32.012  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:32.012  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:32.012  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:32.012  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:32.012  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:32.012  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:32.022  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:32.022  6770  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:39:32.022  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:32.022  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f5ff743 added. We now have 3 listener(s)
,08-25 17:39:32.022  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-25 17:39:32.022  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 17:39:32.022  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:32.022  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:32.022  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:32.022  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a04e1c0 added. We now have 10 listener(s)
08-25 17:39:32.022  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:32.022  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:32.022  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:32.022  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:39:32.022  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:32.022  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:39:32.022  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-25 17:39:32.022  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 17:39:32.022  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:39:32.032  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:39:32.032  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:39:32.032  7687  7687 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-25 17:39:32.032  7687  7687 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-25 17:39:32.032  7687  7687 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-25 17:39:32.032  7687  7687 I dhcpcd  : bssid match
08-25 17:39:32.032  7687  7687 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-25 17:39:32.032  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:39:32.032  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:39:32.032  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 17:39:32.032  7567  7577 D BtGatt.GattService: registerClient() - UUID=088d375d-f92e-420a-9170-fd85913bd998
,08-25 17:39:32.082  7567  7593 D BtGatt.GattService: onClientRegistered() - UUID=088d375d-f92e-420a-9170-fd85913bd998, clientIf=6
,08-25 17:39:32.082  6770  6964 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-25 17:39:32.082  7567  7575 D BtGatt.GattService: start scan with filters
,08-25 17:39:32.082  7567  7597 D BtGatt.ScanManager: handling starting scan
08-25 17:39:32.082  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 17:39:32.082  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:39:32.082  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:39:32.082  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:39:32.082  7567  7593 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-25 17:39:32.082  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:32.082  7567  7597 D BtGatt.ScanManager: allow scan with filters
,08-25 17:39:32.082  7567  7597 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
08-25 17:39:32.082  7567  7597 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-25 17:39:32.082  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:39:32.082  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
08-25 17:39:32.082  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:39:32.082  7567  7593 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 17:39:32.082  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:32.082  7567  7597 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:39:32.082  7567  7597 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-25 17:39:32.082  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 17:39:32.082  7567  7593 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-25 17:39:32.082  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:32.082  7567  7593 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 17:39:32.092  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:32.092  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 17:39:32.092  6770  6823 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 17:39:32.092  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:32.092  7687  7687 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-25 17:39:32.092  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:32.092  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 17:39:32.092  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:32.092  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.092  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:39:32.092  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:32.092  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c04d454 removed from the list
08-25 17:39:32.092  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:32.092  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b82ffd removed from the list
08-25 17:39:32.092  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:32.092  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:39:32.092  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.092  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 17:39:32.092  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.092  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:39:32.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:32.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:32.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:32.102  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b82ffd not in the list
08-25 17:39:32.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:39:32.102  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:32.102  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:39:32.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:39:32.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 17:39:32.102  7567  7575 D BtGatt.GattService: stopScan() - queue size =1
,08-25 17:39:32.102  7567  7649 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 17:39:32.102  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:39:32.102  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:39:32.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:39:32.102  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:39:32.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 17:39:32.102  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:32.102  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:39:32.102  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:39:32.102  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 17:39:32.112  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:32.112  7567  7597 D BtGatt.ScanManager: filter size is 1
08-25 17:39:32.112  7567  7597 D BtGatt.ScanManager: delete FilterIndex - 4
,08-25 17:39:32.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:39:32.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:32.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:32.112  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a04e1c0 removed from the list
08-25 17:39:32.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:32.112  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.112  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:32.112  7567  7593 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 17:39:32.112  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:32.112  7567  7597 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:39:32.112  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:32.112  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:32.112  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:32.112  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:32.112  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f5ff743 removed from the list
,08-25 17:39:32.112  7567  7593 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 17:39:32.112  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:32.112  7567  7597 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 17:39:32.122  7567  7593 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 17:39:32.122  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:32.122  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@173659ec added. We now have 2 listener(s)
,08-25 17:39:32.122  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:32.122  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 17:39:32.122  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 17:39:32.122  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:39:32.132  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:32.132  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a1261b5 added. We now have 9 listener(s)
,08-25 17:39:32.132  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:32.132  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:39:32.132  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:32.142  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:32.142  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:32.142  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:32.142  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:32.142  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:32.142  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:32.142  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:32.142  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:32.152  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:32.152  6770  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:39:32.152  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:32.152  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22b70bbb added. We now have 3 listener(s)
,08-25 17:39:32.152  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:32.152  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 17:39:32.152  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:32.152  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:32.152  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:32.152  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2528d8 added. We now have 10 listener(s)
08-25 17:39:32.152  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:32.152  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:32.152  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:39:32.152  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:39:32.152  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:32.152  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 17:39:32.152  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:32.152  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:39:32.162  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:39:32.162  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:39:32.162  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:39:32.162  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 17:39:32.162  6770  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:39:32.172  7687  7687 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-25 17:39:32.172  7567  7649 D BtGatt.GattService: registerClient() - UUID=2951b72c-ebda-4027-80eb-7f036da55877
,08-25 17:39:32.212  7567  7593 D BtGatt.GattService: onClientRegistered() - UUID=2951b72c-ebda-4027-80eb-7f036da55877, clientIf=6,
08-25 17:39:32.212  6770  6964 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-25 17:39:32.212  7567  7575 D BtGatt.GattService: start scan with filters
08-25 17:39:32.212  7567  7597 D BtGatt.ScanManager: handling starting scan
,08-25 17:39:32.212  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 17:39:32.212  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:39:32.212  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-25 17:39:32.212  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 17:39:32.222  7567  7593 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 17:39:32.222  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:32.222  7567  7597 D BtGatt.ScanManager: allow scan with filters
08-25 17:39:32.222  7567  7597 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 17:39:32.222  7567  7597 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-25 17:39:32.222  7567  7593 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-25 17:39:32.222  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:32.222  7567  7597 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:39:32.222  7567  7597 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 17:39:32.222  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:39:32.222  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:32.232  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 17:39:32.232  7567  7593 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 17:39:32.232  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:32.232  7567  7593 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 17:39:32.232  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:32.242  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:39:32.262  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:32.262  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:32.262  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:32.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:32.262  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.262  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:39:32.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:32.262  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@173659ec removed from the list
08-25 17:39:32.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:32.262  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a1261b5 removed from the list
08-25 17:39:32.262  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:32.262  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:32.262  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.262  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 17:39:32.262  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.262  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:39:32.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:32.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:32.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:32.262  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a1261b5 not in the list
08-25 17:39:32.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:39:32.262  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:32.262  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:39:32.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-25 17:39:32.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 17:39:32.262  7567  7575 D BtGatt.GattService: stopScan() - queue size =1
08-25 17:39:32.262  7567  7597 D BtGatt.ScanManager: filter size is 1
,08-25 17:39:32.262  7567  7597 D BtGatt.ScanManager: delete FilterIndex - 5
08-25 17:39:32.262  7567  7577 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 17:39:32.262  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:39:32.262  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 17:39:32.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:39:32.262  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:39:32.262  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:39:32.262  7567  7593 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,08-25 17:39:32.262  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:32.262  7567  7597 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:39:32.262  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:32.272  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:39:32.272  6770  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:39:32.272  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:39:32.272  7567  7593 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 17:39:32.272  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 17:39:32.272  7567  7597 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 17:39:32.272  7567  7593 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 17:39:32.272  7567  7593 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 17:39:32.272  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:32.282  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:39:32.282  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:32.282  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:32.282  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2528d8 removed from the list
08-25 17:39:32.282  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:32.282  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:32.282  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:32.282  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:32.282  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22b70bbb removed from the list
,08-25 17:39:32.282  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:32.282  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@182ffa84 added. We now have 2 listener(s)
08-25 17:39:32.282  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:32.282  6770  6770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:32.282  6770  6770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:32.282  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 17:39:32.282  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:32.282  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-25 17:39:32.282  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:32.282  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30da126d added. We now have 9 listener(s)
08-25 17:39:32.282  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:32.282  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:39:32.282  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-25 17:39:32.292  6770  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:32.292  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:32.292  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:32.292  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:32.292  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:32.292  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:32.292  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:32.292  6770  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:32.292  6770  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-25 17:39:32.292  6770  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:39:32.292  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:32.292  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5d3733 added. We now have 3 listener(s)
,08-25 17:39:32.292  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:32.302  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:32.302  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 17:39:32.302  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:32.302  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:32.302  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:32.302  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f43af0 added. We now have 10 listener(s)
08-25 17:39:32.302  6770  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:32.302  6770  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:32.302  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:32.302  6770  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:32.302  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:32.302  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.302  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:32.302  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:32.302  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@182ffa84 removed from the list
08-25 17:39:32.302  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:32.302  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30da126d removed from the list
08-25 17:39:32.302  6770  6823 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:32.302  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:32.302  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.302  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:32.302  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:32.302  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:32.302  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:32.302  6770  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30da126d not in the list
08-25 17:39:32.302  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.302  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:32.312  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-25 17:39:32.312  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:32.312  6770  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:32.312  6770  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f43af0 removed from the list
08-25 17:39:32.312  6770  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:32.312  6770  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:32.312  6770  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:32.312  6770  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:32.312  6770  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5d3733 removed from the list,
08-25 17:39:32.312  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 17:39:32.312  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 17:39:32.312  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 17:39:32.312  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:32.312  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 17:39:32.312  6770  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:39:32.322  6770  7712 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1359, name: My test thread name)
08-25 17:39:32.322  6770  7712 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1359, thread name: My test thread name)
08-25 17:39:32.322  6770  7712 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1359, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 17:39:32.322  6770  7713 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1361, name: My test thread name)
08-25 17:39:32.322  6770  7713 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1361, thread name: My test thread name)
08-25 17:39:32.322  6770  7713 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1361, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 17:39:32.332  6770  6823 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 17:39:32.332  6770  6823 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 17:39:32.332  6770  6823 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 17:39:32.332  6770  6823 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 17:39:32.332  6770  6823 D com.test.thalitest.ThaliTestRunner: Total duration: 24262 ms
08-25 17:39:32.332  6770  6823 I jxcore-log: Total number of executed tests:  80
08-25 17:39:32.332  6770  6823 I jxcore-log: 
08-25 17:39:32.332  6770  6823 I jxcore-log: Number of passed tests:  80
08-25 17:39:32.332  6770  6823 I jxcore-log: 
08-25 17:39:32.332  6770  6823 I jxcore-log: Number of failed tests:  0
08-25 17:39:32.332  6770  6823 I jxcore-log: 
08-25 17:39:32.332  6770  6823 I jxcore-log: Number of ignored tests:  0
08-25 17:39:32.332  6770  6823 I jxcore-log: 
08-25 17:39:32.332  6770  6823 I jxcore-log: Total duration:  24262
08-25 17:39:32.332  6770  6823 I jxcore-log: 
08-25 17:39:32.332  6770  6823 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 17:39:32.332  6770  6823 I jxcore-log: 
08-25 17:39:32.332  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:32.332  6770  6823 I jxcore-log: 
08-25 17:39:32.332  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:32.332  6770  6823 I jxcore-log: 
08-25 17:39:32.342  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:32.342  6770  6823 I jxcore-log: 
08-25 17:39:32.342  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:32.342  6770  6823 I jxcore-log: 
08-25 17:39:32.342  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:32.342  6770  6823 I jxcore-log: 
08-25 17:39:32.342  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:32.342  6770  6823 I jxcore-log: 
08-25 17:39:32.342  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:32.342  6770  6823 I jxcore-log: 
08-25 17:39:32.352  6770  6770 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 17:39:32.352  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:39:32.352  6770  6823 I jxcore-log: 
08-25 17:39:32.352  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:32.352  6770  6823 I jxcore-log: 
08-25 17:39:32.352  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:32.352  6770  6823 I jxcore-log: 
08-25 17:39:32.352  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:39:32.352  6770  6823 I jxcore-log: 
08-25 17:39:32.352  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:39:32.352  6770  6823 I jxcore-log: 
08-25 17:39:32.352  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:32.352  6770  6823 I jxcore-log: 
08-25 17:39:32.352  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:32.352  6770  6823 I jxcore-log: 
08-25 17:39:32.352  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:39:32.352  6770  6823 I jxcore-log: 
08-25 17:39:32.352  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:39:32.352  6770  6823 I jxcore-log: 
08-25 17:39:32.362  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:32.362  6770  6823 I jxcore-log: 
08-25 17:39:32.362  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:32.362  6770  6823 I jxcore-log: 
,08-25 17:39:32.362  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:39:32.362  6770  6823 I jxcore-log: 
08-25 17:39:32.362  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:39:32.362  6770  6823 I jxcore-log: 
08-25 17:39:32.362  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:39:32.362  6770  6823 I jxcore-log: 
08-25 17:39:32.362  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:39:32.362  6770  6823 I jxcore-log: 
08-25 17:39:32.362  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:39:32.362  6770  6823 I jxcore-log: 
08-25 17:39:32.362  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:39:32.362  6770  6823 I jxcore-log: 
08-25 17:39:32.362  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:39:32.362  6770  6823 I jxcore-log: 
08-25 17:39:32.362  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:39:32.362  6770  6823 I jxcore-log: 
08-25 17:39:32.362  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:39:32.362  6770  6823 I jxcore-log: 
,08-25 17:39:32.482  6770  6770 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-25 17:39:32.482  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:39:32.482  6770  6823 I jxcore-log: 
,08-25 17:39:32.552  1017  1127 E WifiNative-wlan0: do suspend true,
,08-25 17:39:32.602  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
08-25 17:39:32.602  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 17:39:32.612  1017  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 17:39:32.612  1017  1127 E WifiStateMachine: VerifyingLinkState enter
,08-25 17:39:32.612  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:32.612  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 17:39:32.612  6770  6770 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 17:39:32.612  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:32.612  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.612  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.612  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:32.612  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-25 17:39:32.612  1017  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-25 17:39:32.612  1017  1129 D ConnectivityService: Adding iface wlan0 to network 504
,08-25 17:39:32.622  1017  1144 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
08-25 17:39:32.622  1017  1144 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-25 17:39:32.622  1017  1144 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-25 17:39:32.622  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:39:32.622  6770  6823 I jxcore-log: 
08-25 17:39:32.622  1017  1144 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 17:39:32.622  1017  1144 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 17:39:32.632  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-25 17:39:32.632  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 17:39:32.632  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.632  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.632  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.632  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:32.632  1017  1463 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:32.632  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:32.632  1017  1463 W ActivityManager: userId = 0, bbcId = -10000,
08-25 17:39:32.632  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:32.632  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 17:39:32.642  1620  1620 I Hs20UtilService: Starting #22
,08-25 17:39:32.642  1017  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-25 17:39:32.642  1620  1652 I Hs20UtilService: Message received 5007
08-25 17:39:32.642  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 17:39:32.642  3293  3293 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-25 17:39:32.642  1017  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-25 17:39:32.642  1017  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-25 17:39:32.642  7719  7719 D AndroidRuntime: 
08-25 17:39:32.642  7719  7719 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 17:39:32.642  1017  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-25 17:39:32.652  1017  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 17:39:32.652  1017  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-25 17:39:32.652  1017  1129 D ConnectivityService: LTETest block dns file not exists
08-25 17:39:32.652  7719  7719 D AndroidRuntime: CheckJNI is OFF
08-25 17:39:32.652  7719  7719 D AndroidRuntime: readGMSProperty: start
08-25 17:39:32.652  1017  1129 V NetworkStats: updateIfacesLocked()
08-25 17:39:32.652  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.652  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
08-25 17:39:32.652  7719  7719 D AndroidRuntime: readGMSProperty: already setted!!
08-25 17:39:32.652  7719  7719 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-25 17:39:32.652  7719  7719 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-25 17:39:32.652  7719  7719 D AndroidRuntime: readGMSProperty: end
08-25 17:39:32.652  7719  7719 D AndroidRuntime: addProductProperty: start
,08-25 17:39:32.652  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:32.652  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 17:39:32.652  1017  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 17:39:32.652  1017  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 17:39:32.652  1017  1129 V NetworkStats: performPollLocked() took 5ms,
08-25 17:39:32.652  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:32.662  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 17:39:32.672  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:32.672  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 17:39:32.672  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.672  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.672  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.672  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:32.672  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 17:39:32.672  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-25 17:39:32.672  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,08-25 17:39:32.682  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 17:39:32.682  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 17:39:32.682  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:32.682  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.682  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.682  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:32.682  1017  1129 E ConnectivityService: updateNetworkInfo()
08-25 17:39:32.682  1017  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-25 17:39:32.682  1017  1129 E ConnectivityService: updateNetworkInfo()
08-25 17:39:32.682  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:39:32.682  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.682  1017  1129 V NetworkStats: updateIfacesLocked()
08-25 17:39:32.682  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
08-25 17:39:32.682  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:32.682  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 17:39:32.682  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.682  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.692  1017  4790 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:32.692  1017  4790 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:32.692  1017  4790 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:32.692  1017  1129 V NetworkStats: performPollLocked() took 3ms
08-25 17:39:32.692  1017  4790 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:32.692  1017  4790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 17:39:32.692  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 17:39:32.692  1017  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-25 17:39:32.692  1017  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-25 17:39:32.692  1017  7684 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:39:32.692  1017  7684 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-25 17:39:32.692  1017  7684 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:39:32.692  1620  1620 I Hs20UtilService: Starting #23
08-25 17:39:32.692  1017  7684 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-25 17:39:32.692  1620  1652 I Hs20UtilService: Message received 5007
08-25 17:39:32.692  1017  7684 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 17:39:32.692   278   983 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 17:39:32.692   278   983 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-25 17:39:32.692  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.692  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.702  1017  1129 D ConnectivityService:    accepting network in place of null,
08-25 17:39:32.702  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 17:39:32.702  1017  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-25 17:39:32.702  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-25 17:39:32.702  1455  1455 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:39:32.702  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 17:39:32.702  3293  3293 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 17:39:32.702  1017  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 17:39:32.702  1017  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-25 17:39:32.702  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-25 17:39:32.702  1017  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-25 17:39:32.702  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-25 17:39:32.702  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-25 17:39:32.702  1017  1130 D Tethering: MasterInitialState.processMessage what=3
,08-25 17:39:32.702  1017  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504],
08-25 17:39:32.712  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 17:39:32.712  3293  3293 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-25 17:39:32.712  3293  3293 I NearbySettings: MountReceiver.onReceive - Keep current state
08-25 17:39:32.712  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-25 17:39:32.712  1179  1737 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 17:39:32.712  1017  1124 V NetworkStats: updateIfacesLocked()
08-25 17:39:32.712  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.712  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-25 17:39:32.712  1179  1179 D StatusBar.NetworkController: EthernetConnected: false
08-25 17:39:32.712  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 17:39:32.712  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-25 17:39:32.712  1179  1179 D StatusBar.NetworkController: updateDataNetType()
08-25 17:39:32.712  1179  1179 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-25 17:39:32.712  1179  1179 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-25 17:39:32.712  4732  6833 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 17:39:32.712  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 17:39:32.712  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 17:39:32.722  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:32.722  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.722  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.722  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-25 17:39:32.722  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.722  1017  1124 V NetworkStats: performPollLocked() took 10ms
08-25 17:39:32.722  1179  1179 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 17:39:32.722  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.722  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-25 17:39:32.722  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-25 17:39:32.722  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 17:39:32.722  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 17:39:32.722  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.722  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.722  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.722  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:32.722  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:32.722  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:32.732  1017  1248 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 17:39:32.732  1017  1248 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 17:39:32.732  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:32.732  1017  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:32.732  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 17:39:32.732  1620  1620 I Hs20UtilService: Starting #24
,08-25 17:39:32.732  1620  1652 I Hs20UtilService: Message received 5007
,08-25 17:39:32.732  3293  3293 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 17:39:32.732  3293  3293 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-25 17:39:32.742  1017  1030 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0,
08-25 17:39:32.742  1017  1481 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-25 17:39:32.742  1017  1481 D SecContentProvider2: mCursor = null
,08-25 17:39:32.742  1017  1029 D SecContentProvider2: uri = 15 selection = getToastGravity,
08-25 17:39:32.742  1017  1029 D SecContentProvider2: mCursor = null
08-25 17:39:32.742  1017  1497 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset,
08-25 17:39:32.742  1017  1497 D SecContentProvider2: mCursor = null
08-25 17:39:32.742  1017  1463 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-25 17:39:32.742  1017  1463 D SecContentProvider2: mCursor = null
08-25 17:39:32.752  1017  4790 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-25 17:39:32.752  1017  4790 D SecContentProvider2: mCursor = null
,08-25 17:39:32.752  1017  4786 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-25 17:39:32.752  1017  4786 D SecContentProvider2: mCursor = null
,08-25 17:39:32.772   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-25 17:39:32.782  6770  6770 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 17:39:32.782  6770  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:39:32.782  6770  6823 I jxcore-log: 
,08-25 17:39:32.792  1017  7684 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,08-25 17:39:32.792  1017  1135 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017,
,08-25 17:39:32.792  7719  7719 E AffinityControl: AffinityControl: registerfunction enter,
,08-25 17:39:32.802  1179  1179 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-25 17:39:32.822  7719  7719 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 17:39:32.832  1017  1463 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-25 17:39:32.832  1017  1463 D PackageManager: START PACKAGE DELETE: observer{365693472}
08-25 17:39:32.832  1017  1463 D PackageManager: pkg{<packageName>}
08-25 17:39:32.832  1017  1463 D PackageManager: user{0}
08-25 17:39:32.832  1017  1463 D PackageManager: caller{2000}
08-25 17:39:32.832  1017  1463 D PackageManager: flags{2}
08-25 17:39:32.832  1017  1463 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-25 17:39:32.832  1017  1463 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-25 17:39:32.842  1017  1463 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
08-25 17:39:32.842  1017  1463 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-25 17:39:32.842  1017  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-25 17:39:32.842  1017  7684 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 15:39:32 GMT], X-Android-Received-Millis=[1472139572846], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472139572819]}
08-25 17:39:32.842  1017  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-25 17:39:32.842  1017  7684 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 17:39:32.842  1017  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-25 17:39:32.842  1017  7684 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated,
08-25 17:39:32.842  1017  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-25 17:39:32.842  1179  1737 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 17:39:32.842  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 17:39:32.842  4732  6833 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 17:39:32.842  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-25 17:39:32.842  1017  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-25 17:39:32.842  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-25 17:39:32.842  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-25 17:39:32.842  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: EthernetConnected: false
08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: updateDataNetType()
08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-25 17:39:32.852  1179  1179 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-25 17:39:32.852  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 17:39:32.852  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 17:39:32.862  1017  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-25 17:39:32.872  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-25 17:39:32.882  1017  1042 I ActivityManager: Killing 6770:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-25 17:39:32.952  1017  1056 W PackageSettings: Skipping PackageSetting{3368f2e4 com.example.hello/10168} due to missing metadata
,08-25 17:39:32.982  1017  4787 I WindowState: WIN DEATH: Window{80ef625 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 17:39:32.982   258   455 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-25 17:39:32.982   258   450 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-25 17:39:32.982  1017  4787 D InputDispatcher: Focus left window: 6770,
08-25 17:39:32.982  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{37eb7145 u0 com.test.thalitest/.MainActivity t2}
,08-25 17:39:32.992   258  6024 I SurfaceFlinger: id=13 Removed NainActivit (-2/9),
08-25 17:39:32.992  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 17:39:32.992  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 17:39:33.002  1017  1042 D InputDispatcher: Focused application released,
08-25 17:39:33.002  1017  1042 D FocusedStackFrame: Set to : 0
,08-25 17:39:33.012  1017  1042 W ActivityManager: mDVFSHelper.acquire(),
,08-25 17:39:33.012  1017  1042 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-25 17:39:33.022  1017  1135 W ActivityManager: Spurious death for ProcessRecord{27b63fd9 6770:com.test.thalitest/u0a171}, curProc for 6770: null
,08-25 17:39:33.022  1017  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-25 17:39:33.042  1482  1482 D Launcher: onRestart, Launcher: 920123367
,08-25 17:39:33.042  1017  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-25 17:39:33.062  1482  1482 D Launcher: onStart, Launcher: 920123367
,08-25 17:39:33.062  1482  1482 D Launcher.HomeView: onStart
,08-25 17:39:33.062  1482  1482 D Launcher: onResume, Launcher: 920123367
,08-25 17:39:33.062  1017  1497 D SettingsProvider: name = kids_home_mode
08-25 17:39:33.062  1017  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 17:39:33.062  1017  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 17:39:33.062  1017  1497 D SettingsProvider: selectionArgs: false
08-25 17:39:33.062  1017  1497 D SettingsProvider: selectionArgs: 10006
08-25 17:39:33.062  1017  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 17:39:33.062  1017  1497 D SettingsProvider: ret = -1
,08-25 17:39:33.062  1482  1482 D Launcher.HomeView: onResume
,08-25 17:39:33.082  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-25 17:39:33.092  2677  2677 I art     : Explicit concurrent mark sweep GC freed 21062(1179KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 997us total 46.285ms
,08-25 17:39:33.102  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 17:39:33.112  1873  1873 E SamsungIME: mOCRHelper is null
,08-25 17:39:33.112  1993  2151 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 17:39:33.112  4732  4732 I art     : Explicit concurrent mark sweep GC freed 22990(1393KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 12MB/21MB, paused 1.277ms total 87.917ms
,08-25 17:39:33.122   288   288 E SMD     : DCD OFF,
,08-25 17:39:33.142  1017  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-25 17:39:33.142  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 17:39:33.142  1017  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-25 17:39:33.142  1455  1455 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 17:39:33.142  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-25 17:39:33.152  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 17:39:33.152  1017  1124 V NetworkStats: performPollLocked() took 13ms
08-25 17:39:33.152  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:33.162  1482  1482 D MenuAppsGridFragment: onResume
,08-25 17:39:33.162  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:33.162  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 17:39:33.162  1482  1482 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-25 17:39:33.162  2913  2913 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Aug 25 17:39:33 GMT+02:00 2016
,08-25 17:39:33.162  1017  4786 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-25 17:39:33.162  1017  4786 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-25 17:39:33.162  1482  1482 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-25 17:39:33.172  1017  4786 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:33.172  1017  4786 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:33.172  1017  4786 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-25 17:39:33.182  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,08-25 17:39:33.182  1439  1439 D RegisteredServicesCache: empty dynamic service
,08-25 17:39:33.182  1017  4786 D ActivityManager: handle home activity for 0
08-25 17:39:33.182  1017  4786 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-25 17:39:33.182  1017  4786 D KnoxTimeoutHandler: post home show event for user 0
08-25 17:39:33.192  1017  4786 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-25 17:39:33.192  1017  1041 W TextServicesManagerService: no available spell checker services found
08-25 17:39:33.192  1017  4786 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 17:39:33.192  1017  4786 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-25 17:39:33.192  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
08-25 17:39:33.192  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-25 17:39:33.192  2913  2913 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
08-25 17:39:33.192  1482  1482 D Launcher.HomeView: onPause
,08-25 17:39:33.192  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-25 17:39:33.192  1017  1474 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-25 17:39:33.192  1017  1474 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-25 17:39:33.192  1017  1474 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-25 17:39:33.192  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.192  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.192  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.192  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.202  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 17:39:33.202  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:33.202  2913  2913 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-25 17:39:33.212  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-25 17:39:33.212  1017  1474 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7737 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-25 17:39:33.212  7737  7737 E Zygote  : MountEmulatedStorage()
08-25 17:39:33.212  7737  7737 E Zygote  : v2
08-25 17:39:33.212  7737  7737 I libpersona: KNOX_SDCARD checking this for 10090
08-25 17:39:33.212  7737  7737 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:33.222  7737  7737 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:33.222  7737  7737 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 17:39:33.222  7737  7737 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-25 17:39:33.232  2913  2913 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-25 17:39:33.232  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-25 17:39:33.232  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.232  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.232  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.232  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.242  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 17:39:33.242  1017  1029 I TactileAssist: enable value -1
,08-25 17:39:33.242  1017  1029 I TactileAssist: internal enable value -1
08-25 17:39:33.242  1017  1029 I TactileAssist: intensity value -1
08-25 17:39:33.242  1017  1029 I TactileAssist: saveAppList value true,
,08-25 17:39:33.252  1017  1017 I art     : Explicit concurrent mark sweep GC freed 66861(4MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/37MB, paused 6.674ms total 204.350ms
,08-25 17:39:33.252  7753  7753 E Zygote  : MountEmulatedStorage()
08-25 17:39:33.252  7753  7753 E Zygote  : v2
08-25 17:39:33.252  7753  7753 I libpersona: KNOX_SDCARD checking this for 1000
08-25 17:39:33.252  7753  7753 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:33.252  7753  7753 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:33.252  1017  1029 I TactileAssist: List of disabled apps :
,08-25 17:39:33.262  1017  1056 I art     : WaitForGcToComplete blocked for 196.646ms for cause Explicit
,08-25 17:39:33.262  7753  7753 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:33.262  7753  7753 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:33.282  1017  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7753 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 17:39:33.282  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-25 17:39:33.292  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.292  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.292  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.292  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.292  7737  7737 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 17:39:33.292  7737  7737 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:33.292  2913  2913 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-25 17:39:33.292  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 17:39:33.292  2913  7736 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-25 17:39:33.302  7753  7753 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:33.302  7753  7753 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:33.302  2913  7736 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-25 17:39:33.302  2913  7736 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-25 17:39:33.312  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-25 17:39:33.312  2913  7736 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-25 17:39:33.312  7768  7768 E Zygote  : MountEmulatedStorage()
08-25 17:39:33.312  7768  7768 E Zygote  : v2
08-25 17:39:33.312  7768  7768 I libpersona: KNOX_SDCARD checking this for 1000
08-25 17:39:33.312  7768  7768 I libpersona: KNOX_SDCARD not a persona
08-25 17:39:33.312  7768  7768 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:33.312  7768  7768 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:33.312  7768  7768 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:33.312  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-25 17:39:33.312  1017  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7768 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 17:39:33.322  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-25 17:39:33.322  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-25 17:39:33.322  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-25 17:39:33.342   303   303 I art     : Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 762us total 25.253ms
,08-25 17:39:33.342   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-25 17:39:33.352  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
,08-25 17:39:33.352  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-25 17:39:33.362  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-25 17:39:33.362  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-25 17:39:33.362  1017  1480 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-25 17:39:33.362  1017  1480 D SecContentProvider2: mCursor = null
,08-25 17:39:33.372  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-25 17:39:33.372   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.162ms total 20.793ms
,08-25 17:39:33.372  1017  1029 D InputDispatcher: Focus entered window: 1482
,08-25 17:39:33.372  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-25 17:39:33.372  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-25 17:39:33.372  1482  1482 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-25 17:39:33.382  7768  7768 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-25 17:39:33.382  7768  7768 D ActivityThread: Added TimaKeyStore provider
08-25 17:39:33.382  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{210cdb7 token=android.os.BinderProxy@1c142679 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-25 17:39:33.382  1482  1482 D Launcher.HomeView: onStop
,08-25 17:39:33.392   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 564us total 24.036ms
,08-25 17:39:33.392  1017  1480 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-25 17:39:33.412  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,08-25 17:39:33.412  1017  1480 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6770 uid 10171
,08-25 17:39:33.412  1017  7784 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-25 17:39:33.412  1017  1474 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-25 17:39:33.422  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.422  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.422  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.422  1017  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.422  1873  1873 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-25 17:39:33.422  7753  7753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-25 17:39:33.442  2913  7736 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-25 17:39:33.442  7786  7786 E Zygote  : MountEmulatedStorage()
,08-25 17:39:33.442  7786  7786 E Zygote  : v2
08-25 17:39:33.442  7786  7786 I libpersona: KNOX_SDCARD checking this for 10048
08-25 17:39:33.442  7786  7786 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:33.442  1017  1474 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7786 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a,
08-25 17:39:33.442  1017  1481 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-25 17:39:33.442  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-25 17:39:33.452  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:33.452  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 17:39:33.452  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-25 17:39:33.452  7786  7786 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:33.452  7786  7786 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:33.452  7786  7786 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 17:39:33.462  1017  1248 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-25 17:39:33.462  7737  7737 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
08-25 17:39:33.462  7737  7737 D elm:15121: ELMEngine.ELMEngine( context ).
,08-25 17:39:33.462  7737  7737 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-25 17:39:33.482  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.492  7768  7768 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
08-25 17:39:33.492  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.492  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.492  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.492  2913  7736 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-25 17:39:33.492  2913  7736 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-25 17:39:33.502  7786  7786 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:33.502  7786  7786 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:33.502  7802  7802 E Zygote  : MountEmulatedStorage()
,08-25 17:39:33.502  7802  7802 E Zygote  : v2
08-25 17:39:33.502  7802  7802 I libpersona: KNOX_SDCARD checking this for 1000
08-25 17:39:33.502  7802  7802 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:33.502  7802  7802 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:33.512  1017  1042 W ActivityManager: mDVFSHelper.release(),
08-25 17:39:33.512  7802  7802 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:39:33.512  7802  7802 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:33.512  1017  1248 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7802 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 17:39:33.522  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-25 17:39:33.522  1017  4789 D SecContentProvider2: uri = -1 selection = getSealedState
08-25 17:39:33.532  1017  1463 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-25 17:39:33.522  1017  4789 D SecContentProvider2: mCursor = null
08-25 17:39:33.532  1017  1463 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-25 17:39:33.532  7768  7768 I PopupuiReceiver_KNOX: getSealedState : true
08-25 17:39:33.532  1017  1463 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:33.532  1017  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:33.532  1017  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-25 17:39:33.532  2913  2913 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-25 17:39:33.532  1017  1480 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-25 17:39:33.532  1017  1480 D SecContentProvider2: mCursor = null
,08-25 17:39:33.532  1017  1030 I ActivityManager: Killing 7167:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-25 17:39:33.542  7737  7737 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-25 17:39:33.542  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 17:39:33.542  7737  7737 D elm:15121: ElmAgentService : onCreate()
,08-25 17:39:33.542  7737  7817 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-25 17:39:33.542  7737  7817 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-25 17:39:33.542  7737  7817 D elm:15121: MDMBridge.getInstance()
08-25 17:39:33.542  7737  7817 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-25 17:39:33.542  7768  7768 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-25 17:39:33.542  7737  7817 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-25 17:39:33.552  7802  7802 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:33.552  7802  7802 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:33.552  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8169e12 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:149442
,08-25 17:39:33.552  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 17:39:33.552  1017  1481 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-25 17:39:33.552  1017  1481 D SecContentProvider2: mCursor = null
,08-25 17:39:33.562  7768  7768 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-25 17:39:33.562  7768  7768 D PopupuiReceiver: Action package removed
,08-25 17:39:33.572  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-25 17:39:33.572  7786  7786 D Compatibility: onReceive() it will make start service
,08-25 17:39:33.582  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.582  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.582  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.582  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.592  7802  7802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 17:39:33.592  7819  7819 E Zygote  : MountEmulatedStorage()
08-25 17:39:33.592  7819  7819 I libpersona: KNOX_SDCARD checking this for 10145
08-25 17:39:33.592  7819  7819 E Zygote  : v2
08-25 17:39:33.592  7819  7819 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:33.592  7819  7819 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:33.602  7819  7819 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:33.602  7819  7819 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 17:39:33.602  1017  1030 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7819 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 17:39:33.602  1017  1030 I ActivityManager: Killing 7155:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-25 17:39:33.612  7737  7737 D elm:15121: ElmAgentService : onDestroy().
,08-25 17:39:33.622  7802  7802 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-25 17:39:33.632  1017  1463 D PersonaManager: isKioskContainerExistOnDevice
,08-25 17:39:33.632  7819  7819 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:33.632  7819  7819 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:33.642  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 17:39:33.642  1017  1456 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-25 17:39:33.642  1017  1456 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-25 17:39:33.642  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-25 17:39:33.642  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:39:33.642  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 17:39:33.642  1017  4786 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,08-25 17:39:33.652  1017  4786 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-25 17:39:33.652  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 17:39:33.652  1017  4786 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:33.652  1017  4786 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:33.652  1017  4786 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-25 17:39:33.652  1017  1056 I art     : Explicit concurrent mark sweep GC freed 15731(1007KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/37MB, paused 18.438ms total 396.419ms
,08-25 17:39:33.662  1017  1135 I ActivityManager: Killing 7193:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-25 17:39:33.662  7786  7834 D Compatibility: onHandleIntent()
,08-25 17:39:33.662  7786  7834 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-25 17:39:33.672  1017  4787 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-25 17:39:33.672  7786  7834 D Compatibility: found: 2
,08-25 17:39:33.672  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.672  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.672  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.672  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.682  7786  7834 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-25 17:39:33.682  7786  7834 D Compatibility: skipping ResolveInfo{31de66ce com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-25 17:39:33.682  7786  7834 D Compatibility: considering ResolveInfo{1058b9ef com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-25 17:39:33.682  7786  7834 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-25 17:39:33.682  7786  7834 D Compatibility: enabling receiver ResolveInfo{3c482cfc com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-25 17:39:33.682  7836  7836 E Zygote  : MountEmulatedStorage()
08-25 17:39:33.682  7836  7836 I libpersona: KNOX_SDCARD checking this for 10087
08-25 17:39:33.682  7836  7836 E Zygote  : v2
08-25 17:39:33.682  7836  7836 I libpersona: KNOX_SDCARD not a persona
08-25 17:39:33.682  7836  7836 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:33.692  7836  7836 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:39:33.692  1017  4787 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7836 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-25 17:39:33.692  7836  7836 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 17:39:33.692  7786  7834 D Compatibility: enabling receiver ResolveInfo{2f581f85 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-25 17:39:33.702  1017  4787 I ActivityManager: Killing 7213:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-25 17:39:33.702  7786  7834 D Compatibility: enabling receiver ResolveInfo{27fe21da com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-25 17:39:33.702  1017  4787 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-25 17:39:33.702  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 17:39:33.702  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-25 17:39:33.702  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.702  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.702  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.702  1017  4787 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.712  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-25 17:39:33.712  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-25 17:39:33.712  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-25 17:39:33.712  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-25 17:39:33.712  1017  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-25 17:39:33.712  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-25 17:39:33.712  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-25 17:39:33.712  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-25 17:39:33.712  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-25 17:39:33.712  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-25 17:39:33.712  7786  7834 D Compatibility: enabling receiver ResolveInfo{3e21060b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-25 17:39:33.722  7849  7849 E Zygote  : MountEmulatedStorage()
,08-25 17:39:33.722  7849  7849 E Zygote  : v2
08-25 17:39:33.722  7849  7849 I libpersona: KNOX_SDCARD checking this for 10052
08-25 17:39:33.722  7849  7849 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 17:39:33.722  7849  7849 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:33.722  7849  7849 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:33.722  7849  7849 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 17:39:33.722  1017  4787 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7849 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-25 17:39:33.732  7836  7836 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:33.732  7836  7836 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:33.742  7786  7834 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-25 17:39:33.752  7849  7849 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:33.752  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 17:39:33.752  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-25 17:39:33.752  7849  7849 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:33.752  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-25 17:39:33.752  1017  3362 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-25 17:39:33.762  1017  1017 V EnterpriseBillingPolicy: uID is 10171
,08-25 17:39:33.762  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-25 17:39:33.762  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 17:39:33.762  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-25 17:39:33.762  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-25 17:39:33.762  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,08-25 17:39:33.762  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-25 17:39:33.762  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-25 17:39:33.762  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-25 17:39:33.762  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-25 17:39:33.762  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-25 17:39:33.762  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-25 17:39:33.762  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-25 17:39:33.762  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-25 17:39:33.762  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 17:39:33.762  1017  1017 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-25 17:39:33.762  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 17:39:33.762  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-25 17:39:33.762  7567  7591 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 17:39:33.772  1017  4787 I ActivityManager: Killing 7122:com.android.chrome/u0a77 (adj 15): empty #21
,08-25 17:39:33.772  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 17:39:33.782  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 17:39:33.782  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-25 17:39:33.782  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 17:39:33.782  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-25 17:39:33.782  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 17:39:33.782  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-25 17:39:33.792  1017  1056 D PackageManager: delete codoeFile: 
,08-25 17:39:33.802  1017  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-25 17:39:33.802  1017  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-25 17:39:33.802  1017  1056 D PackageManager: result of delete: 1{365693472}
,08-25 17:39:33.802  7819  7819 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-25 17:39:33.802  7819  7819 D ThemeInfoUtil: isCurrentFestival = false
,08-25 17:39:33.802  7719  7719 D AndroidRuntime: Shutting down VM
08-25 17:39:33.802  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-25 17:39:33.812  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.812  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.812  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.812  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.812  1017  1497 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-25 17:39:33.812  1017  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-25 17:39:33.812  1017  1056 D PackageManager: userId{-1}
08-25 17:39:33.812  1017  1056 D PackageManager: andCode{true}
,08-25 17:39:33.822  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest,
08-25 17:39:33.822  7866  7866 I libpersona: KNOX_SDCARD checking this for 10148
08-25 17:39:33.822  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 17:39:33.822  7866  7866 I libpersona: KNOX_SDCARD not a persona
08-25 17:39:33.822  7866  7866 E Zygote  : MountEmulatedStorage()
08-25 17:39:33.822  7866  7866 E Zygote  : v2
08-25 17:39:33.822  7866  7866 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:33.822  1017  1029 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7866 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-25 17:39:33.822  1017  1029 I ActivityManager: Killing 7017:com.google.android.talk/u0a102 (adj 15): empty #21
,08-25 17:39:33.822  7866  7866 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 17:39:33.822  1017  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-25 17:39:33.822  7866  7866 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:33.832  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.832  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.832  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.832  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.842  7879  7879 E Zygote  : MountEmulatedStorage()
08-25 17:39:33.842  7879  7879 I libpersona: KNOX_SDCARD checking this for 10003
08-25 17:39:33.842  7879  7879 E Zygote  : v2
08-25 17:39:33.842  7879  7879 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:33.842  7879  7879 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:33.852  1017  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7879 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-25 17:39:33.852  7879  7879 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:33.852  7879  7879 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 17:39:33.852  7866  7866 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 17:39:33.852  1017  4789 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-25 17:39:33.852  7866  7866 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:33.872  7879  7879 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 17:39:33.872  7879  7879 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:33.882  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-25 17:39:33.882  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.882  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.882  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.882  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.902  1179  1179 I StatusBar: Icon Only
,08-25 17:39:33.902  1179  1179 D PanelView: There is/are notification(s) 
,08-25 17:39:33.902  7897  7897 E Zygote  : MountEmulatedStorage(),
08-25 17:39:33.902  7897  7897 E Zygote  : v2
08-25 17:39:33.902  7897  7897 I libpersona: KNOX_SDCARD checking this for 1000
08-25 17:39:33.902  7897  7897 I libpersona: KNOX_SDCARD not a persona,
,08-25 17:39:33.902  7897  7897 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-25 17:39:33.902  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7897 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 17:39:33.912  7897  7897 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 17:39:33.912  7897  7897 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 17:39:33.952  7897  7897 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 17:39:33.952  1017  1480 I ActivityManager: Killing 7249:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-25 17:39:33.952  7866  7866 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
08-25 17:39:33.952  7897  7897 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:33.972  1017  1135 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-25 17:39:33.972  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-25 17:39:33.972  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:33.972  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 17:39:33.972  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-25 17:39:33.972  1017  1029 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-25 17:39:33.972  1017  1029 D SecContentProvider2: mCursor = null
,08-25 17:39:33.972  1017  1456 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-25 17:39:33.972  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-25 17:39:33.982  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:33.982  1017  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:33.982  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-25 17:39:33.982  1017  4786 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-25 17:39:33.982  1482  1482 I Choreographer: Skipped 33 frames!  The application may be doing too much work on its main thread.
,08-25 17:39:33.982  1482  1482 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1c142679 time:149876
,08-25 17:39:33.982  1017  4786 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:33.982  1017  4786 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.982  1017  4786 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:33.982  1017  4786 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:34.002  7914  7914 E Zygote  : MountEmulatedStorage()
,08-25 17:39:34.002  7914  7914 E Zygote  : v2
08-25 17:39:34.002  7914  7914 I libpersona: KNOX_SDCARD checking this for 10152
08-25 17:39:34.002  7914  7914 I libpersona: KNOX_SDCARD not a persona
08-25 17:39:34.002  7897  7897 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-25 17:39:34.002  7897  7897 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-25 17:39:34.002  7897  7897 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-25 17:39:34.002  7914  7914 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-25 17:39:34.002  7914  7914 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 17:39:34.002  1017  4786 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7914 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-25 17:39:34.002  7914  7914 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 17:39:34.012  7719  7719 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-25 17:39:34.012  1017  4790 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-25 17:39:34.012  1017  4790 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-25 17:39:34.022  1017  4790 W ActivityManager: userId = 0, bbcId = -10000
08-25 17:39:34.022  1017  4790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:34.022  1017  4790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-25 17:39:34.022  7897  7897 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-25 17:39:34.022  7897  7897 I PCWCLIENTTRACE_PushUtil: sales region : global
08-25 17:39:34.022  7897  7897 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-25 17:39:34.022  7897  7897 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-25 17:39:34.022  1017  1761 I ActivityManager: Killing 7266:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,08-25 17:39:34.032  1017  1761 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-25 17:39:34.032  1017  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:34.032  1017  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:34.032  1017  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:34.032  1017  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:34.042  7914  7914 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-25 17:39:34.042  7914  7914 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:34.052  7930  7930 E Zygote  : MountEmulatedStorage()
08-25 17:39:34.052  7930  7930 E Zygote  : v2
08-25 17:39:34.052  7930  7930 I libpersona: KNOX_SDCARD checking this for 10029
08-25 17:39:34.052  7930  7930 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:34.052  7930  7930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-25 17:39:34.052  7930  7930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 17:39:34.052  1017  1761 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7930 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-25 17:39:34.052  7930  7930 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 17:39:34.052  1017  1761 I ActivityManager: Killing 7232:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-25 17:39:34.082  7452  7452 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-25 17:39:34.082  7930  7930 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 17:39:34.082  7930  7930 D ActivityThread: Added TimaKeyStore provider
,08-25 17:39:34.122  7914  7914 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-25 17:39:34.122  7914  7914 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,08-25 17:39:34.132  7452  7452 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/predictor.db" with flag (131138) and mode_t (0) due to error (30)
,08-25 17:39:34.132  7914  7914 I TapandpayWidget:Utils: Clear T&P info.
,08-25 17:39:34.132  7605  7605 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
,08-25 17:39:34.142  7605  7605 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.android.sm/databases/history.db'.
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:34.142  7605  7605 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 17:39:34.142  1017  4786 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
08-25 17:39:34.152  7605  7605 D AndroidRuntime: Shutting down VM
,08-25 17:39:34.152  7605  7605 E AndroidRuntime: FATAL EXCEPTION: main
08-25 17:39:34.152  7605  7605 E AndroidRuntime: Process: com.samsung.android.sm, PID: 7605
08-25 17:39:34.152  7605  7605 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125),
08-25 17:39:34.152  7605  7605 E AndroidRuntime: 	... 9 more
,08-25 17:39:34.162  7914  7914 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-25 17:39:34.162  1017  1761 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 17:39:34.162  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,08-25 17:39:34.172  1017  1248 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,08-25 17:39:34.172  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
,08-25 17:39:34.172  1017  1761 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 17:39:34.172  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 17:39:34.182  7930  7948 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-25 17:39:34.182  7452  7452 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/predictor.db'.
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:65)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:34.182  7452  7452 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 17:39:34.182  7452  7452 D AndroidRuntime: Shutting down VM
,08-25 17:39:34.182  7452  7452 E AndroidRuntime: FATAL EXCEPTION: main
08-25 17:39:34.182  7452  7452 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 7452
08-25 17:39:34.182  7452  7452 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:65)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 17:39:34.182  7452  7452 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 17:39:34.192  7605  7946 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-25 17:39:34.192  7605  7605 I Process : Sending signal. PID: 7605 SIG: 9
,08-25 17:39:34.192  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
,08-25 17:39:34.192  1017  1327 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-25 17:39:34.192  4732  7953 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-25 17:39:34.192  4732  7953 D AccountUtils: Clearing selected account for com.test.thalitest
,08-25 17:39:34.202  1017  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:34.202  1017  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:34.202  1017  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 17:39:34.202  1017  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 17:39:34.202  4732  7953 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-25 17:39:34.212  7955  7955 E Zygote  : MountEmulatedStorage()
08-25 17:39:34.212  7955  7955 E Zygote  : v2
08-25 17:39:34.212  7955  7955 I libpersona: KNOX_SDCARD checking this for 10032
08-25 17:39:34.212  7955  7955 I libpersona: KNOX_SDCARD not a persona
,08-25 17:39:34.212  1017  1327 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7955 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 17:39:34.212  1017  1327 I ActivityManager: Killing 6847:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
08-25 17:39:34.212  7955  7955 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 17:39:34.222  7955  7955 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 17:39:34.222  7955  7955 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL

```
