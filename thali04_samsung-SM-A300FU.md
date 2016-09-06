#### Test 82914073d0f9b46_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main,
09-06 19:15:56.390   287   287 E SMD     : DCD OFF
09-06 19:15:56.670  6678  6678 D AndroidRuntime: 
09-06 19:15:56.670  6678  6678 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:15:56.670  6678  6678 D AndroidRuntime: CheckJNI is OFF
09-06 19:15:56.670  6678  6678 D AndroidRuntime: readGMSProperty: start
09-06 19:15:56.670  6678  6678 D AndroidRuntime: readGMSProperty: already setted!!
09-06 19:15:56.670  6678  6678 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 19:15:56.670  6678  6678 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:15:56.670  6678  6678 D AndroidRuntime: readGMSProperty: end
09-06 19:15:56.670  6678  6678 D AndroidRuntime: addProductProperty: start
09-06 19:15:56.800  6678  6678 E AffinityControl: AffinityControl: registerfunction enter
09-06 19:15:56.820  6678  6678 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-06 19:15:56.840  1013  4116 E PersonaManagerService: inState():  stateMachine is null !!
09-06 19:15:56.840  1013  4116 I PersonaManagerService: PersonaId don't exist
09-06 19:15:56.840  1013  4116 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-06 19:15:56.840  1013  4116 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-06 19:15:56.860  1013  4116 W ActivityManager: mDVFSHelper.acquire()
09-06 19:15:56.860   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-06 19:15:56.860   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-06 19:15:56.870  1013  4116 D FocusedStackFrame: Set to : 0
09-06 19:15:56.870  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:56.870  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:56.870  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:56.870  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:15:56.890  1013  1043 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 19:15:56.890  1013  1043 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-06 19:15:56.890  6690  6690 E Zygote  : MountEmulatedStorage()
09-06 19:15:56.890  6690  6690 E Zygote  : v2
09-06 19:15:56.890  6690  6690 I libpersona: KNOX_SDCARD checking this for 10171
09-06 19:15:56.890  6690  6690 I libpersona: KNOX_SDCARD not a persona
09-06 19:15:56.890  6690  6690 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:15:56.890  1013  4116 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6690 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:15:56.890  1013  4116 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-06 19:15:56.890  1013  4116 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:15:56.890  1013  4116 D InputDispatcher: Focused application set to: xxxx
09-06 19:15:56.890  1013  4116 D InputDispatcher: Focus left window: 1479
09-06 19:15:56.900  1013  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 19:15:56.900  1013  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 19:15:56.900  6678  6678 D AndroidRuntime: Shutting down VM
09-06 19:15:56.900   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-06 19:15:56.900  6690  6690 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:56.900  6690  6690 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-06 19:15:56.910  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:15:56.910  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 19:15:56.920  6690  6690 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:15:56.920  6690  6690 D ActivityThread: Added TimaKeyStore provider
09-06 19:15:56.920  1013  1227 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-06 19:15:56.920  1013  1013 V ActivityManager: Display changed displayId=0
09-06 19:15:56.940  1013  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-06 19:15:56.950  1013  1227 D PersonaManager: isKioskContainerExistOnDevice
09-06 19:15:56.970  1013  1013 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-06 19:15:57.000   257  1495 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
09-06 19:15:57.000   257   448 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
09-06 19:15:57.010  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{3d718ec9 token=android.os.BinderProxy@19c34d6b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-06 19:15:57.010  1479  1479 D Launcher: onTrimMemory. Level: 20
09-06 19:15:57.090  6690  6690 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-06 19:15:57.100  6678  6678 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-06 19:15:57.140  6690  6690 I cr.library_loader: Time to load native libraries: 22 ms (timestamps 7837-7859)
09-06 19:15:57.140  6690  6690 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-06 19:15:57.160  6690  6690 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34ca92ed}
09-06 19:15:57.160  6690  6690 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-06 19:15:57.170  6690  6690 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:15:57.210  6690  6690 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-06 19:15:57.210  6690  6690 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:15:57.220  6690  6690 E SysUtils: ApplicationContext is null in ApplicationStatus
09-06 19:15:57.280  6690  6690 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:15:57.280  6690  6690 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:15:57.280  6690  6690 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:15:57.280  6690  6690 I Adreno-EGL: Local Branch: 
09-06 19:15:57.280  6690  6690 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:15:57.280  6690  6690 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:15:57.280  6690  6690 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-06 19:15:57.380  6690  6690 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:15:57.400  6690  6690 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-06 19:15:57.400  6690  6690 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-06 19:15:57.410  6690  6690 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-06 19:15:57.410  6690  6690 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-06 19:15:57.460  1013  1038 W ActivityManager: Activity pause timeout for ActivityRecord{12471a88 u0 com.test.thalitest/.MainActivity t2}
09-06 19:15:57.520  6690  6690 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:15:57.530  6690  6690 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-06 19:15:57.540  6690  6690 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 19:15:57.540  6690  6690 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-06 19:15:57.550  6690  6690 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-06 19:15:57.550  6690  6690 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:15:57.550  6690  6690 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:15:57.660  6690  6730 D OpenGLRenderer: Render dirty regions requested: true
09-06 19:15:57.660  1013  1477 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 19:15:57.660  1013  1477 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:15:57.660  1013  1477 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 19:15:57.660  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:15:57.660  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
09-06 19:15:57.670  6690  6717 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
09-06 19:15:57.670  6690  6690 V ActivityThread: updateVisibility : ActivityRecord{27500bcd token=android.os.BinderProxy@2ddd16f6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 19:15:57.680  6690  6690 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 19:15:57.680  6690  6690 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 19:15:57.690   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
09-06 19:15:57.700  1013  1302 E Watchdog: !@Sync 3
09-06 19:15:57.710  1013  1494 D InputDispatcher: Focus entered window: 6690
09-06 19:15:57.710  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:15:57.710  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 19:15:57.710  6690  6690 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-06 19:15:57.710  6690  6730 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 19:15:57.720  6690  6730 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-06 19:15:57.720  6690  6730 D OpenGLRenderer: Enabling debug mode 0
09-06 19:15:57.730  1013  1466 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-06 19:15:57.740  1013  6734 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-06 19:15:57.740  1173  1173 I StatusBar: Icon Only
09-06 19:15:57.740  1173  1173 D PanelView: There is/are notification(s) 
09-06 19:15:57.750  1013  1043 I ActivityManager: Displayed Component not be shown by security: +796ms (total +882ms)
09-06 19:15:57.750  1013  1043 W ActivityManager: mDVFSHelper.release()
09-06 19:15:57.750  1013  1043 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12471a88 u0 com.test.thalitest/.MainActivity t2} time:108479
09-06 19:15:57.760   257  1495 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
09-06 19:15:57.760   257  1986 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
09-06 19:15:57.760  6690  6690 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-06 19:15:57.760  6690  6690 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ddd16f6 time:108489
09-06 19:15:57.770  1876  1876 I SamsungIME: getCurrentCandidateView
09-06 19:15:57.860  6690  6690 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6690
09-06 19:15:57.870  1876  1876 D SamsungIME: Dismiss ExpandCandiate
,09-06 19:15:58.050  1876  1876 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 19:15:58.060  6690  6690 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 19:15:58.090  1876  1876 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 19:15:58.100  1876  1876 I SamsungIME: KeybaordView init() : load resources
,09-06 19:15:58.120  1876  1876 I SamsungIME: getCurrentKeyboard
,09-06 19:15:58.120  1876  1876 I SamsungIME: getTextKeyboard
,09-06 19:15:58.140  1876  1876 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-06 19:15:58.150  6690  6735 D jxcore_app_log: JniHelper::setJavaVM(0xb77f62b0), pthread_self() = -1210569232
,09-06 19:15:58.160  6690  6735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:15:58.160  6690  6735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:15:58.160  6690  6735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:15:58.160  6690  6735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:15:58.160  6690  6735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-06 19:15:58.160  6690  6735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c720e0b added. We now have 1 listener(s)
,09-06 19:15:58.160  6690  6735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-06 19:15:58.160  6690  6735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:15:58.160  6690  6735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:15:58.160  6690  6735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 19:15:58.170  6690  6735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15729a6 added. We now have 1 listener(s)
,09-06 19:15:58.170  6690  6735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:15:58.170  6690  6735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:15:58.170  6690  6735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-06 19:15:58.180  6690  6735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:15:58.180  6690  6735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:15:58.180  6690  6735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 19:15:58.180  6690  6735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:15:58.180  6690  6735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-06 19:15:58.190  6690  6735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-06 19:15:58.190  6690  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:15:58.190  6690  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:15:58.190  6690  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:15:58.190  6690  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:15:58.190  6690  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:15:58.190  6690  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:15:58.190  6690  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:15:58.190  6690  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:15:58.190  6690  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:15:58.190  6690  6735 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:15:58.190  6690  6735 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:15:58.190  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:15:58.190  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:15:58.220  6690  6690 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:15:58.390   320   320 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-06 19:15:58.390   320   320 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-06 19:15:58.760  6690  6743 W jxcore-log: Initializing JXcore engine
09-06 19:15:58.760  6690  6743 W jxcore-log: JXcore engine is ready
,09-06 19:15:58.820  1990  1990 E audit   : type=1400 msg=audit(1473182158.820:205): avc:  denied  { ioctl } for  pid=6743 comm="Thread-1235" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-06 19:15:58.820  1990  1990 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:15:58.820  1990  1990 E audit   : type=1300 msg=audit(1473182158.820:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e8fb8f8 items=0 ppid=309 ppcomm=main pid=6743 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1235" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-06 19:15:58.820  1990  1990 E audit   : type=1320 msg=audit(1473182158.820:205): 
,09-06 19:15:58.830  6690  6743 W jxcore-log: Starting JXcore engine
,09-06 19:15:58.940  6690  6743 W jxcore-log: Platform android
09-06 19:15:58.940  6690  6743 W jxcore-log: 
09-06 19:15:58.940  6690  6743 W jxcore-log: Process ARCH arm
09-06 19:15:58.940  6690  6743 W jxcore-log: 
,09-06 19:15:59.150  6690  6743 I jxcore-log: JXcore Cordova bridge is ready!,
09-06 19:15:59.150  6690  6743 I jxcore-log: 
09-06 19:15:59.150  6690  6743 W jxcore-log: JXcore engine is started
,09-06 19:15:59.160  6690  6735 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:15:59.160  6690  6690 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:15:59.380   287   287 E SMD     : DCD OFF,
,09-06 19:15:59.990  1013  1091 V AlarmManager: waitForAlarm result :8,
,09-06 19:16:01.450  1013  1045 I PowerManagerService: [PWL] Off : 50s ago
,09-06 19:16:01.740  1013  3354 D SSRM:n  : SIOP:: AP = 330,
,09-06 19:16:02.390   287   287 E SMD     : DCD OFF,
,09-06 19:16:03.390   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:04.390   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:05.240  5625  5625 D FactoryTest: Not factory mode
,09-06 19:16:05.240  5625  5625 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-06 19:16:05.250  5625  5625 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-06 19:16:05.250  5625  5625 D MTPRx   : still no open session command from host, so toast
,09-06 19:16:05.250  5625  5625 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-06 19:16:05.250  5625  5625 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-06 19:16:05.250  5625  5625 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115979
,09-06 19:16:05.260  1013  1452 E PersonaManagerService: inState():  stateMachine is null !!
,09-06 19:16:05.260  1013  1452 I PersonaManagerService: PersonaId don't exist
09-06 19:16:05.260  1013  1452 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-06 19:16:05.260  1013  1452 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:16:05.260  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:05.260  1013  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:05.260  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-06 19:16:05.270  1013  1452 W ActivityManager: mDVFSHelper.acquire()
,09-06 19:16:05.280  1013  1452 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:16:05.290  1013  1452 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:16:05.290  1013  1452 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:16:05.290  1013  1452 D InputDispatcher: Focused application set to: xxxx
,09-06 19:16:05.290  1013  1452 D InputDispatcher: Focus left window: 6690
,09-06 19:16:05.290  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:16:05.290  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:16:05.300  5625  5625 E MTPRx   : started activity for popup
,09-06 19:16:05.320  5625  5625 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-06 19:16:05.320  5625  5625 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-06 19:16:05.320  5625  5625 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:16:05.320  5625  5625 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:16:05.320  5625  5625 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:16:05.320  5625  5625 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:16:05.350  5625  5625 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-06 19:16:05.350  1013  1130 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:16:05.350  1013  1130 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 19:16:05.350  1013  1130 D InputDispatcher: Focused application set to: xxxx
,09-06 19:16:05.350  1013  1130 D InputDispatcher: Focus entered window: 6690
,09-06 19:16:05.350  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:16:05.360  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:16:05.360  1013  1494 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 19:16:05.360  1013  1494 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@31e67fb attribute=null, token = android.os.BinderProxy@43e60b
,09-06 19:16:05.390   287   287 E SMD     : DCD OFF
,09-06 19:16:05.390   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:05.410  5625  5625 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-06 19:16:05.410  5625  5625 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-06 19:16:05.410  5625  5625 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-06 19:16:05.450  6690  6690 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-06 19:16:05.450  6690  6690 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
09-06 19:16:05.450  6690  6690 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-06 19:16:05.450  6690  6690 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-06 19:16:05.450  1013  1466 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-06 19:16:05.450  1013  1466 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:16:05.450  1013  1466 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-06 19:16:05.450  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:16:05.450  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 19:16:05.460  6690  6690 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:16:05.460  6690  6690 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-06 19:16:05.470  6690  6690 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f06ead2 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1a93022b, 16908290=android.view.AbsSavedState$1@1a93022b}, android:focusedViewId=100}]}]
,09-06 19:16:05.470  6690  6690 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-06 19:16:05.470  6690  6690 V ActivityThread: updateVisibility : ActivityRecord{27500bcd token=android.os.BinderProxy@2ddd16f6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 19:16:05.470  6690  6690 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:16:05.470  6690  6690 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-06 19:16:05.470  6690  6690 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ddd16f6 time:116195
,09-06 19:16:05.480  1013  1568 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:16:05.500  1013  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:16:05.500  1013  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-06 19:16:05.500  1013  1359 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:16:05.500  1013  1359 D BatteryService: stay LED for fully charged
09-06 19:16:05.500  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:16:05.500  1013  1013 I MotionRecognitionService: Plugged
09-06 19:16:05.500  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:16:05.510  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:16:05.510  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:16:05.510  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-06 19:16:05.510  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 19:16:05.520  3177  3177 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:16:05.520  3177  3282 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:16:05.530  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:16:05.530  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:16:05.530  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:16:05.540  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-06 19:16:05.540  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-06 19:16:06.390   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:06.930  1013  1052 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,09-06 19:16:07.390   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:16:08.270  1013  1038 W ActivityManager: mDVFSHelper.release(),
,09-06 19:16:08.390   287   287 E SMD     : DCD OFF,
,09-06 19:16:08.390   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-06 19:16:09.280  1013  1091 V AlarmManager: waitForAlarm result :4
,09-06 19:16:09.290  1013  1091 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-06 19:16:09.300  1013  1013 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-06 19:16:09.300  1013  1013 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-06 19:16:09.300  1013  1013 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-06 19:16:09.310  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-06 19:16:09.310  1173  1173 D KeyguardUpdateMonitor: handleTimeUpdate
,09-06 19:16:09.320  1173  1173 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-06 19:16:09.330  1173  1173 D SecKeyguardClockView: HomeTimezone(): 1
,09-06 19:16:09.330  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:16:09.330  1173  1173 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-06 19:16:09.330  1173  1173 I KeyguardEffectViewController: *** don't update sliding image ***
,09-06 19:16:09.340  1992  1992 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-06 19:16:09.370  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:16:09.370  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:16:09.380  1013  1494 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:09.380  1013  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-06 19:16:09.380  1013  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:09.380  1013  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:09.380  1013  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:09.390  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:16:09.400  1173  1173 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,09-06 19:16:09.410  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:16:09.440  4757  4757 D ConnectivityManager: CallingUid : 10011, CallingPid : 4757
,09-06 19:16:09.440  1013  1469 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:16:09.440  1013  1124 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-06 19:16:09.440  1013  1124 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,09-06 19:16:09.440  1013  1124 D ConnectivityService: apparently satisfied.  currentScore=60
,09-06 19:16:09.450  4757  6753 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 19:16:09.490  4757  6754 W DriveInitializer: Background init thread started
,09-06 19:16:09.520   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-06 19:16:09.520   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:09.520  4757  6754 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-06 19:16:09.580  1013  1494 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:09.580  1013  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-06 19:16:09.580  1013  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:09.580  1013  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:09.580  1013  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:09.610  1013  1026 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-06 19:16:09.610  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-06 19:16:09.620  1013  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:09.620  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-06 19:16:09.620  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:09.620  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:09.620  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:09.620  4757  6754 W DriveInitializer: Background init thread ended
,09-06 19:16:09.650  4757  6762 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-06 19:16:09.650  4757  6762 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-06 19:16:09.670  1992  1992 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:16:09.690  1013  1038 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:09.690  1013  1038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:09.700  1013  1038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:09.810  1013  1494 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:09.810  1013  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-06 19:16:09.810  1013  1494 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:09.810  1013  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:09.810  1013  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:09.850  1013  1025 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:09.850  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-06 19:16:09.850  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:09.850  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:09.850  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:09.900  1013  1469 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:09.900  1013  1469 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:09.900  1013  1469 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:09.900  1013  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:09.920  1013  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:09.920  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:09.920  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:09.920  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:10.010  1992  6765 I art     : Explicit concurrent mark sweep GC freed 72001(4MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 10MB/17MB, paused 1.239ms total 67.869ms
,09-06 19:16:10.170  1013  1569 I art     : Explicit concurrent mark sweep GC freed 37575(1966KB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 2.440ms total 151.051ms
09-06 19:16:10.170  1013  1130 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-06 19:16:10.170  1013  1130 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:10.170  1013  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:10.170  1013  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:10.180  1013  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:10.180  1013  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:10.180  1013  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:10.180  1013  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:10.190  6767  6767 E Zygote  : MountEmulatedStorage()
09-06 19:16:10.190  6767  6767 E Zygote  : v2
09-06 19:16:10.190  6767  6767 I libpersona: KNOX_SDCARD checking this for 10011
09-06 19:16:10.190  6767  6767 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:10.190  6767  6767 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:10.200  6767  6767 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:10.200  6767  6767 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:16:10.200  1013  1130 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6767 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-06 19:16:10.220   309   309 I art     : Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 660us total 23.902ms
,09-06 19:16:10.230  6767  6767 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:10.230  6767  6767 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:10.240   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 17.686ms
,09-06 19:16:10.250  6767  6767 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-06 19:16:10.250  6767  6767 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 19:16:10.260   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 18.663ms,
,09-06 19:16:10.290  6767  6767 I MultiDex: VM with version 2.1.0 has multidex support
09-06 19:16:10.300  6767  6767 I MultiDex: install
09-06 19:16:10.300  6767  6767 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 19:16:10.330  6767  6767 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-06 19:16:10.390  6767  6767 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 19:16:10.390  6767  6767 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29400539: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-06 19:16:10.390  6767  6767 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-06 19:16:10.430  6767  6767 D ChimeraCfgMgr: Reading stored module config
,09-06 19:16:10.480  6767  6780 I art     : Background sticky concurrent mark sweep GC freed 28430(1332KB) AllocSpace objects, 3(133KB) LOS objects, 3% free, 7MB/7MB, paused 9.989ms total 68.433ms
,09-06 19:16:10.490  1013  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-06 19:16:10.500  1013  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:10.500  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:10.500  1013  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:10.500  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:10.520  1013  1469 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:10.520  6767  6784 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
09-06 19:16:10.520  1013  1469 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:10.520  1013  1469 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:10.520  1013  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:10.540  6767  6767 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-06 19:16:10.540  6767  6767 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-06 19:16:10.560  1992  1992 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=c2fdbc96-215a-4780-a2ac-114f27c859e8
,09-06 19:16:10.560  6767  6780 W art     : Suspending all threads took: 16.814ms
,09-06 19:16:10.570  6767  6780 I art     : Background partial concurrent mark sweep GC freed 1256(241KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 21.540ms total 55.403ms
,09-06 19:16:10.580  1013  1227 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-06 19:16:10.580  1013  1227 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
09-06 19:16:10.580  1013  1227 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:10.580  1013  1227 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:10.580  1013  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:10.620  1992  1992 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:16:10.620  1992  1992 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:16:10.640  1013  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:10.650  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:10.650   282  1011 D WVCdm   : Instantiating CDM.
,09-06 19:16:10.650  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:10.650   282   689 I WVCdm   : CdmEngine::OpenSession
09-06 19:16:10.650   282   689 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-06 19:16:10.650  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:10.670   282   689 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-06 19:16:10.700   282   689 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,09-06 19:16:10.710  4302  4312 I art     : Explicit concurrent mark sweep GC freed 1409(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 700us total 31.694ms
,09-06 19:16:10.750   282   689 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-06 19:16:10.750   282   282 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-06 19:16:10.750   282   282 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-06 19:16:10.750   282   282 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-06 19:16:10.760   282   282 D WVCdm   : PrepareKeyRequest: nonce=2995679398
,09-06 19:16:10.760  1992  2151 W GCoreFlp: No location to return for getLastLocation()
,09-06 19:16:10.790  6767  6777 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-06 19:16:10.790  6767  6777 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:16:10.790  6767  6777 I System.out: (HTTPLog)-Static: isShipBuild true
09-06 19:16:10.790  6767  6777 I System.out: (HTTPLog)-Thread-1214-252941282: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-06 19:16:10.790  6767  6777 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:16:10.790   277   996 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:16:10.790   277   996 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-06 19:16:10.820  4757  6763 D UdcContextInitService: registered all accounts: true
,09-06 19:16:10.820  1013  1569 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:10.820  1013  1569 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:10.820  1013  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:10.820  1013  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:10.830  1013  1469 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:10.830  1992  2154 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:16:10.830  1013  1469 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:10.830  1013  1469 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:10.830  1013  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:10.830  1013  1466 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:10.830  1013  1466 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:10.830  1013  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:10.830  1013  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:10.840  6767  6777 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:16:10.840  6767  6777 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6767, getuid(): 10011
,09-06 19:16:10.850  1992  2176 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-06 19:16:10.990  1013  1469 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-06 19:16:10.990  1013  1469 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-06 19:16:11.000  1013  1469 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:11.000  1013  1469 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:11.000  1013  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:11.190  6767  6777 I qtaguid : Untagging socket 33
,09-06 19:16:11.390   287   287 E SMD     : DCD OFF
,09-06 19:16:11.520  6795  6795 I dex2oat : ----------------------------------------------------
09-06 19:16:11.520  6795  6795 I dex2oat : <SS>: S T A R T I N G . . .
09-06 19:16:11.520  6795  6795 I dex2oat : <SS>: Zip is absent. Canceled.
,09-06 19:16:11.520  6795  6795 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-06 19:16:11.580  6795  6795 I dex2oat : dex2oat took 55.999ms (threads: 4)
,09-06 19:16:11.590  6767  6777 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:16:11.590  6767  6777 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:16:11.590  6767  6777 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:16:11.590  6767  6777 I Adreno-EGL: Local Branch: 
09-06 19:16:11.590  6767  6777 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:16:11.590  6767  6777 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:16:11.590  6767  6777 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:16:11.670  6767  6777 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:16:11.670  6767  6777 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:16:11.670  6767  6777 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:16:11.670  6767  6777 I Adreno-EGL: Local Branch: 
09-06 19:16:11.670  6767  6777 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:16:11.670  6767  6777 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:16:11.670  6767  6777 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:16:11.780  1013  3354 D SSRM:n  : SIOP:: AP = 360,
,09-06 19:16:11.830  6767  6777 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:16:11.830  6767  6777 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:16:11.830  6767  6777 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:16:11.830  6767  6777 I Adreno-EGL: Local Branch: 
09-06 19:16:11.830  6767  6777 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:16:11.830  6767  6777 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:16:11.830  6767  6777 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:16:11.900  1013  3383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:16:12.120  1013  1494 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-06 19:16:12.120  1013  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-06 19:16:12.120  1013  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:12.120  1013  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:12.130  1013  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:12.140  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:16:12.140  6690  6743 I jxcore-log: 
,09-06 19:16:12.140  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:16:12.140  6690  6743 I jxcore-log: 
,09-06 19:16:12.150  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:12.150  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:12.150  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:12.150  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:12.150  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:12.150  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:12.150  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:12.150  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:12.150  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:12.150  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:16:12.150  6690  6743 I jxcore-log: 
,09-06 19:16:12.150  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:16:12.150  6690  6743 I jxcore-log: 
,09-06 19:16:12.160  1992  6765 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-06 19:16:12.160  1992  6765 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:16:12.160  1992  6765 I System.out: (HTTPLog)-Static: isShipBuild true
,09-06 19:16:12.160  1992  6765 I System.out: (HTTPLog)-Thread-266-127689104: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-06 19:16:12.160  1992  6765 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:16:12.170   277   996 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:16:12.170   277   996 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-06 19:16:12.170  1992  6765 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:16:12.170  1992  6765 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1992, getuid(): 10011
,09-06 19:16:12.220  1992  6765 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1992, getuid(): 10011
,09-06 19:16:12.310   282  1011 I WVCdm   : CdmEngine::CloseSession
,09-06 19:16:12.320   282  1011 I WVCdm   : L3 Terminate.
,09-06 19:16:12.470  1992  2176 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-06 19:16:12.470  1992  2176 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-06 19:16:12.480  1992  2176 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-06 19:16:10.915+0200, stopTime=2016-09-06 19:16:12.490+0200, duration=1575ms
,09-06 19:16:12.490  1992  6806 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:16:12.490   277   996 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:16:12.490   277   996 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-06 19:16:12.490  1992  6806 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-06 19:16:12.490  1992  6806 I qtaguid : Tagging socket 69 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1992, getuid(): 10011
,09-06 19:16:12.560  1992  6806 I qtaguid : Tagging socket 67 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1992, getuid(): 10011
,09-06 19:16:12.570  1013  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-06 19:16:12.820  1992  6806 I qtaguid : Untagging socket 69
,09-06 19:16:12.860  6690  6743 D executeNativeTests: Running unit tests
,09-06 19:16:12.860  1013  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:12.860  1013  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-06 19:16:12.860  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:12.860  1013  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:12.860  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:12.890  1992  2176 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-06 19:16:12.960  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:12.960  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 added. We now have 2 listener(s)
,09-06 19:16:12.960  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:16:12.960  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:12.960  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:12.960  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:12.960  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 added. We now have 2 listener(s)
09-06 19:16:12.960  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:12.960  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:12.960  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:12.970  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:12.970  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:12.970  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:12.970  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:12.970  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:12.970  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:12.970  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:12.970  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:12.970  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:12.970  6690  6743 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:12.970  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:12.980  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:16:12.980  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:16:12.980  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 19:16:12.980  6690  6743 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-06 19:16:12.980  6690  6743 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:16:12.980  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:16:12.980  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:16:12.980  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 19:16:12.980  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:12.980  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:12.980  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:16:12.980  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:12.980  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:12.980  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:12.980  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:12.980  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:12.980  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 removed from the list
09-06 19:16:12.980  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:12.980  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 removed from the list
,09-06 19:16:12.980  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:12.980  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:12.980  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:12.980  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:12.990  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:12.990  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:12.990  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:12.990  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:12.990  6690  6743 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 19:16:12.990  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:12.990  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:12.990  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:12.990  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:12.990  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:12.990  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:12.990  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:12.990  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:12.990  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:12.990  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:12.990  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:12.990  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:12.990  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:12.990  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:12.990  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:12.990  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:12.990  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:12.990  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.000  1013  1568 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-06 19:16:13.000  1013  1568 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:13.000  1013  1568 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:13.000  1013  1568 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:16:13.000  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.000  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.000  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.000  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.000  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.000  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.000  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.000  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.000  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.000  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.000  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.000  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.000  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.000  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.010  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.010  6690  6743 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:16:13.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:13.020  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:13.020  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:13.020  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:13.020  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:13.020  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:13.020  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:13.020  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:13.020  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:13.020  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:13.020  6690  6743 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:13.020  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:13.020  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:13.020  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:13.020  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:13.020  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:16:13.020  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:13.030  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:13.030  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:16:13.030  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:16:13.040  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:16:13.040  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-06 19:16:13.050  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-06 19:16:13.050  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:16:13.050  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:16:13.050  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:13.070  3177  3367 D BtGatt.GattService: registerClient() - UUID=f1a06e5f-48a4-4718-a06b-0c7dff777931
,09-06 19:16:13.080  1992  6812 I art     : Explicit concurrent mark sweep GC freed 55277(2MB) AllocSpace objects, 13(516KB) LOS objects, 39% free, 11MB/19MB, paused 1.391ms total 72.963ms
,09-06 19:16:13.100  1013  1569 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:13.100  1013  1569 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:13.100  1013  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:13.100  1013  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:13.110  3177  3273 D BtGatt.GattService: onClientRegistered() - UUID=f1a06e5f-48a4-4718-a06b-0c7dff777931, clientIf=6
,09-06 19:16:13.120  6690  6700 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:13.120  3177  5322 D BtGatt.GattService: start scan with filters
,09-06 19:16:13.120  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:16:13.120  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:16:13.120  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:16:13.120  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:16:13.120  3177  3279 D BtGatt.ScanManager: handling starting scan
,09-06 19:16:13.130  3177  3279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:13.130  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:13.130  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:16:13.130  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:13.130  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:16:13.140  3177  3273 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:16:13.140  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.140  3177  3279 D BtGatt.ScanManager: allow scan with filters
09-06 19:16:13.140  3177  3279 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:16:13.140  3177  3279 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-06 19:16:13.140  3177  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:16:13.140  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.140  3177  3279 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:16:13.140  3177  3279 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:16:13.140  3177  3273 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:16:13.140  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.150  6690  6743 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:16:13.150  3177  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:16:13.150  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.150  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:13.150  6690  6743 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:16:13.150  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:16:13.150  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:16:13.160  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:16:13.160  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:16:13.160  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:16:13.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:13.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:16:13.160  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:13.160  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:16:13.160  3177  3200 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:16:13.160  3177  3367 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:16:13.160  3177  3279 D BtGatt.ScanManager: filter size is 1
09-06 19:16:13.160  3177  3279 D BtGatt.ScanManager: delete FilterIndex - 3
,09-06 19:16:13.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:13.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:13.160  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:16:13.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:16:13.160  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:16:13.160  3177  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:16:13.160  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:13.160  3177  3279 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:16:13.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:13.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:16:13.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:16:13.160  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:16:13.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:13.170  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:16:13.170  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:13.170  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:13.170  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:13.170  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.170  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:13.170  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.170  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.170  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.170  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.170  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.170  6690  6743 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:16:13.170  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:13.170  3177  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:16:13.170  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.170  3177  3279 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:16:13.170  3177  3273 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:16:13.170  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.170  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:13.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:13.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:13.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:13.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:13.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:13.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:13.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:13.180  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:13.180  6690  6743 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:13.180  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.180  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.180  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:13.180  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:13.180  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:13.180  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:13.180  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:16:13.190  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:16:13.190  1013  1466 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:13.190  1013  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:13.190  1013  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:13.190  1013  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:13.190  1992  6815 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-06 19:16:13.190  1992  6812 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-06 19:16:13.190  1013  1130 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:13.190  1013  1130 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:13.190  1013  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:13.190  1013  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:13.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:16:13.200  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:16:13.200  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:16:13.200  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:16:13.200  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:13.200  3177  3367 D BtGatt.GattService: registerClient() - UUID=5deeafb7-42f9-47b7-b96b-1716ea90edbb
,09-06 19:16:13.220  1013  1452 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:13.220  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:13.220  1013  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:13.220  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:13.220  1992  6815 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-06 19:16:13.220  1992  6812 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-06 19:16:13.220  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-06 19:16:13.220  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:13.220  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:13.220  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:13.240  3177  3273 D BtGatt.GattService: onClientRegistered() - UUID=5deeafb7-42f9-47b7-b96b-1716ea90edbb, clientIf=6
,09-06 19:16:13.240  6690  6698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:13.250  3177  5322 D BtGatt.GattService: start scan with filters
,09-06 19:16:13.250  3177  3279 D BtGatt.ScanManager: handling starting scan
,09-06 19:16:13.250  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:16:13.250  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:16:13.250  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:16:13.250  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:16:13.250  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:13.250  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:13.250  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:16:13.250  3177  3273 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:16:13.250  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:13.250  3177  3279 D BtGatt.ScanManager: allow scan with filters
,09-06 19:16:13.250  3177  3279 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:16:13.250  3177  3279 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 19:16:13.260  1013  4422 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:13.260  1013  4422 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:13.260  1013  4422 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:13.260  1013  4422 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:16:13.260  1992  6815 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-06 19:16:13.260  1992  6812 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-06 19:16:13.260  1992  6812 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-06 19:16:13.260  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:16:13.260  3177  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:16:13.260  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:13.260  3177  3279 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:16:13.260  3177  3279 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:16:13.260  6690  6743 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:16:13.260  1992  6812 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-06 19:16:13.270  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.270  6690  6743 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:16:13.270  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.270  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:16:13.270  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.270  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:16:13.270  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:16:13.270  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:13.270  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:13.270  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:13.270  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:13.270  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:16:13.270  3177  3273 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:16:13.270  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.270  3177  3200 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:16:13.270  3177  3367 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:16:13.280  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:16:13.280  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:13.280  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:16:13.280  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:16:13.280  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:16:13.280  3177  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:16:13.280  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:13.280  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:13.280  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:16:13.280  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:16:13.280  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:16:13.280  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:13.280  3177  3279 D BtGatt.ScanManager: filter size is 1
09-06 19:16:13.280  3177  3279 D BtGatt.ScanManager: delete FilterIndex - 4
,09-06 19:16:13.280  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.280  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.280  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:13.280  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:13.280  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:13.280  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:13.280  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.280  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.280  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.280  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.280  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.280  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.280  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.280  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:13.290  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.290  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.290  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
,09-06 19:16:13.290  6690  6743 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:16:13.290  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:13.290  3177  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:16:13.290  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.290  3177  3279 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:16:13.290  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-06 19:16:13.290  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:13.290  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:13.290  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:13.290  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:13.290  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:13.290  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:13.290  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:13.300  3177  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:16:13.300  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:13.300  3177  3279 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:16:13.300  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:13.300  6690  6743 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:13.300  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:13.300  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:13.300  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:13.300  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:13.300  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:16:13.300  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.300  3177  3273 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:16:13.300  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.300  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:16:13.310  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.310  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:16:13.310  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:16:13.310  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:16:13.310  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:16:13.310  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:13.320  3177  3200 D BtGatt.GattService: registerClient() - UUID=a47c1b89-40ff-4405-88eb-af7fc82f9799
,09-06 19:16:13.340  1013  1569 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 19:16:13.360  3177  3273 D BtGatt.GattService: onClientRegistered() - UUID=a47c1b89-40ff-4405-88eb-af7fc82f9799, clientIf=6
,09-06 19:16:13.360  6690  6698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:13.360  3177  3191 D BtGatt.GattService: start scan with filters
,09-06 19:16:13.360  3177  3279 D BtGatt.ScanManager: handling starting scan
09-06 19:16:13.360  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:16:13.360  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:16:13.360  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:16:13.360  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:16:13.360  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:13.360  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:13.360  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:16:13.370  3177  3273 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:16:13.370  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.370  3177  3279 D BtGatt.ScanManager: allow scan with filters
09-06 19:16:13.370  3177  3279 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:16:13.370  3177  3279 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 19:16:13.370  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:16:13.370  6690  6743 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:16:13.370  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.370  6690  6743 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:16:13.370  3177  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:16:13.370  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:13.370  3177  3279 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:16:13.370  3177  3279 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:16:13.380  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.380  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:16:13.380  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.380  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:16:13.380  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:16:13.380  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:13.380  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:13.380  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:13.380  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:13.380  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:16:13.380  3177  3200 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:16:13.380  3177  3191 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:16:13.380  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:13.380  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:13.380  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:16:13.380  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:16:13.380  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:16:13.380  3177  3273 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:16:13.380  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.380  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:13.390  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:16:13.390  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:16:13.390  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:16:13.390  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:13.390  3177  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:16:13.390  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.390  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:16:13.390  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.390  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:13.390  6690  6743 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:16:13.390  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.390  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.390  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.390  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.390  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:13.390  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.390  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.390  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.390  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.390  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.390  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:13.390   320   320 I ServiceManager: Waiting for service AtCmdFwd...
09-06 19:16:13.390  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.390  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.390  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.390  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.390  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.390  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
,09-06 19:16:13.390  6690  6743 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-06 19:16:13.400  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.400  3177  3279 D BtGatt.ScanManager: filter size is 1
09-06 19:16:13.400  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:16:13.400  3177  3279 D BtGatt.ScanManager: delete FilterIndex - 5
09-06 19:16:13.400  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.400  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.400  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.400  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list,
09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.400  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.400  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.400  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.400  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.400  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.400  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.400  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.400  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
09-06 19:16:13.400  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.400  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.400  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.400  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.400  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.400  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list,
09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.400  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.400  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.400  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.400  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.400  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.400  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.400  3177  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:16:13.400  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:13.400  3177  3279 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.400  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
,09-06 19:16:13.400  6690  6743 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-06 19:16:13.400  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.400  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.400  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.400  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.400  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.400  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.400  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.400  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.400  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.400  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.400  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.400  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.410  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.410  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.410  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.410  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:13.410  3177  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:16:13.410  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.410  3177  3279 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:16:13.410  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
,09-06 19:16:13.410  3177  3273 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:16:13.410  3177  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:13.410  6690  6743 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-06 19:16:13.410  1992  6812 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:16:13.410  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:13.410  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.410  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.410  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.410  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.410  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.410  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.410  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:13.410  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.410  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.410  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.410  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.410  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.410  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.410   277   996 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:16:13.410   277   996 D Netd    : getNetworkForDns: using netid 502 for uid 10011,
09-06 19:16:13.410  1992  6812 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-06 19:16:13.410  1992  6812 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1992, getuid(): 10011
,09-06 19:16:13.410  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.410  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.410  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-06 19:16:13.410  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
,09-06 19:16:13.420  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:16:13.420  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:16:13.420  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:16:13.420  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:16:13.420  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:16:13.420  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:16:13.420  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.420  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.420  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:16:13.420  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.420  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.420  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.420  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.420  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.420  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.420  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.420  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.420  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.420  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.420  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.420  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.420  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.420  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
,09-06 19:16:13.420  6690  6743 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:13.420  6690  6743 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-06 19:16:13.420  6690  6743 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-06 19:16:13.420  6690  6743 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010],
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:16:13.420  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:16:13.420  6690  6743 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:16:13.420  6690  6743 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:16:13.420  6690  6743 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-06 19:16:13.420  6690  6743 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:13.420  6690  6743 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:16:13.420  6690  6743 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:16:13.420  6690  6743 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:13.420  6690  6743 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:16:13.420  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-06 19:16:13.430  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-06 19:16:13.430  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:16:13.430  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-06 19:16:13.430  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:16:13.430  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:16:13.430  6690  6743 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:16:13.430  6690  6743 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:13.430  6690  6743 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-06 19:16:13.430  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.430  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.430  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.430  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.430  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.430  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.430  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-06 19:16:13.430  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.430  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.430  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.430  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.430  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.430  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.430  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.430  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.430  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.430  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.430  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.430  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
,09-06 19:16:13.430  6690  6743 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:16:13.430  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.430  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.430  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.430  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.430  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.430  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.430  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.430  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.430  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.430  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.430  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.430  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.430  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.430  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.440  6690  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1299
09-06 19:16:13.440  6690  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1299)
,09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
,09-06 19:16:13.440  6690  6743 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-06 19:16:13.440  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.440  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.440  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.440  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.440  6690  6743 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:16:13.440  6690  6743 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:16:13.440  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:16:13.440  6690  6743 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:16:13.440  6690  6743 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:16:13.440  6690  6743 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-06 19:16:13.440  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:16:13.440  6690  6743 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:16:13.440  6690  6743 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:16:13.440  6690  6743 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:16:13.440  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:16:13.440  6690  6743 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:16:13.440  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.440  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.440  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list,
09-06 19:16:13.440  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.440  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.440  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.440  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.440  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.440  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.440  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.440  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.440  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.440  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.450  6690  6820 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.450  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.450  6690  6820 D BluetoothSocket: connect(): myUserId = 0
09-06 19:16:13.450  6690  6820 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:16:13.450  3177  3200 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:16:13.450  6690  6690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:16:13.450  6690  6820 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:16:13.450  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.450  6690  6690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:13.450  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:13.450  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.450  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:13.450  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.450  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:13.450  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising:, false - Stop operation: Should start/stop everything
09-06 19:16:13.450  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:13.450  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.450  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.450  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.450  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.450  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.450  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.450  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.450  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.450  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:13.450  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.460  6690  6822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:16:13.460  6690  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 19:16:13.460  6690  6743 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:16:13.460  6690  6743 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:16:13.460  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:16:13.460  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:16:13.460  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:13.460  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.460  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.460  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.460  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.460  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.460  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.460  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:13.460  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.460  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.460  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.460  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.460  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:16:13.460  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.460  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.460  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.460  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.460  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.460  6690  6690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-06 19:16:13.460  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.460  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.460  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:13.460  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:13.460  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.460  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.460  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.460  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.460  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.460  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.460  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.460  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.460  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.460  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:13.460  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:13.460  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.460  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.460  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
,09-06 19:16:13.460  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:13.460  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:13.460  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:16:13.470  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:16:13.470  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.470  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.470  6690  6743 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b551b8 not in the list
09-06 19:16:13.470  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.470  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
,09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:13.470  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.470  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.470  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:13.470  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:13.470  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:13.470  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:13.470  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:13.470  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a0b91 not in the list
09-06 19:16:13.470  1992  6812 I qtaguid : Tagging socket 80 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1992, getuid(): 10011
09-06 19:16:13.470  6690  6743 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:16:13.470  6690  6743 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:16:13.470  6690  6743 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:16:13.470  6690  6743 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:16:13.470  6690  6743 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:16:13.470  6690  6743 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:16:13.470  6690  6743 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 19:16:13.470  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:13.470  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@124f20b added. We now have 2 listener(s)
09-06 19:16:13.470  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:13.470  6690  6743 D BluetoothAdapter: enable()
,09-06 19:16:13.480  6690  6743 D BluetoothAdapter: enable(): BT is already enabled..!
,09-06 19:16:13.480  1013  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-06 19:16:13.480  1013  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:16:13.480  1013  1026 D SecContentProvider2: mCursor = null
,09-06 19:16:13.480  1013  1026 D WifiService: setWifiEnabled: true pid=6690, uid=10171,
,09-06 19:16:13.490  1013  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=6690, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:16:13.490  1013  1026 W WifiService: Failed getting userId using ActivityManagerNative,
09-06 19:16:13.490  1013  1026 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6690, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:13.490  1013  1026 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:16:13.490  1013  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:16:13.490  1013  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:16:13.490  1013  1026 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:16:13.490  1013  1026 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 19:16:13.490  1013  1026 D SettingsProvider: name = wifi_on
09-06 19:16:13.490  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:13.490  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3dfc98e8 added. We now have 3 listener(s)
,09-06 19:16:13.490  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:13.500  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:13.500  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@693fb01 added. We now have 4 listener(s),
09-06 19:16:13.500  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:13.500  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:13.500  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7425da6 added. We now have 5 listener(s)
,09-06 19:16:13.500  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:13.500  1013  1130 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 19:16:13.500  1013  1130 D WifiService: setWifiEnabled: false pid=6690, uid=10171
09-06 19:16:13.500  1013  1130 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:16:13.500  1013  1130 D SecContentProvider2: mCursor = null
09-06 19:16:13.500  1013  1130 D SettingsProvider: name = wifi_on
,09-06 19:16:13.510  1013  1122 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-06 19:16:13.510  1369  1369 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:16:13.510  1369  1369 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-06 19:16:13.510  1369  1369 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:16:13.510  6690  6743 D BluetoothAdapter: disable()
09-06 19:16:13.510  1369  1369 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:16:13.520  1013  1494 D SettingsProvider: name = bluetooth_on,
,09-06 19:16:13.520  3177  3270 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-06 19:16:13.520  3177  3270 D BluetoothAdapterProperties: Setting state to 13
09-06 19:16:13.520  3177  3270 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:16:13.520  3177  3270 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:13.520  3177  3270 D BluetoothAdapterService: updateAdapterState state is 13
09-06 19:16:13.520  1013  1466 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:13.520  1013  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:16:13.520  1013  1466 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:13.520  1013  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:13.520  1013  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:13.530  3177  3177 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-06 19:16:13.530  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:13.530  3177  3270 D BluetoothAdapterService: Autoconnection is available 
09-06 19:16:13.530  3177  3270 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:16:13.530  3177  3270 D BluetoothAdapterService: terminating service from this receiver
09-06 19:16:13.530  3177  3177 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3f4430d7, channel: 19, state: LISTENING
,09-06 19:16:13.530  1013  1122 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:16:13.530  3177  3177 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3f4430d7, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25484df, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14347dc4mSocket: android.net.LocalSocket@224374ad impl:android.net.LocalSocketImpl@f1393e2 fd:FileDescriptor[74]
,09-06 19:16:13.530  3177  3177 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@224374ad impl:android.net.LocalSocketImpl@f1393e2 fd:FileDescriptor[74]
09-06 19:16:13.530  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:16:13.530  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:13.530  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:13.530  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:13.530  3177  3270 D BluetoothAdapterProperties: onBluetoothDisable(),
09-06 19:16:13.530  3177  3270 D BluetoothAdapterProperties: mDiscovering is false
09-06 19:16:13.540  1013  1569 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:16:13.540  3177  3270 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 19:16:13.540  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:13.540  1013  1013 I InputMethodManagerService: [BT Setting State] State =13
09-06 19:16:13.540  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:13.540  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:13.540  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:13.540  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:13.540  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:13.540  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:13.540  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:13.540  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:13.540  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:13.540  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:13.540  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:13.540  6690  6743 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:13.550  1013  1122 E WifiNative-wlan0: do suspend true
,09-06 19:16:13.550  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:16:13.550  1876  1876 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:16:13.550  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.560  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:16:13.560  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:13.560  1173  1173 D BluetoothTile:  getBluetoothState : 13
,09-06 19:16:13.560  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:13.560  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:13.560  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:13.560  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:13.560  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:13.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:13.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:13.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:13.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:13.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:13.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:13.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:13.560  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:13.560  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:13.560  1013  1130 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:13.570  3064  3064 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:13.570  1013  1477 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 19:16:13.570  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:16:13.570  1013  1466 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:13.570  1013  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:16:13.570  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:16:13.570  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-06 19:16:13.570  1013  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:13.570  3177  3273 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:16:13.570  3177  3273 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:16:13.580  1013  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:13.580  1013  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:13.580  3064  3064 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:16:13.580  3177  3270 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:16:13.580  3177  3270 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-06 19:16:13.580  1013  1026 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:16:13.580  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-06 19:16:13.580  3177  3270 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-06 19:16:13.580  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:13.580  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:13.580  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:16:13.580  3177  3270 E bt-btif : cmd socket is not created
09-06 19:16:13.580  3177  5198 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 19:16:13.580  3177  3297 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-06 19:16:13.580  3177  3297 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-06 19:16:13.580  6690  6820 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9765b94, channel: -1, state: INIT
,09-06 19:16:13.580  6690  6820 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9765b94, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3fc4463d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@426ae32mSocket: android.net.LocalSocket@3a379783 impl:android.net.LocalSocketImpl@2c279d00 fd:FileDescriptor[106]
09-06 19:16:13.580  6690  6820 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3a379783 impl:android.net.LocalSocketImpl@2c279d00 fd:FileDescriptor[106]
09-06 19:16:13.580  6690  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1299)
,09-06 19:16:13.590  3177  3270 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:16:13.590  3177  3297 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 19:16:13.590  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:13.590  3177  3297 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:13.590  3177  3297 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:16:13.590  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-06 19:16:13.590  3064  3064 D BluetoothPbap: Proxy object disconnected
09-06 19:16:13.590  3177  3177 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@25310373, channel: 5, state: LISTENING
09-06 19:16:13.590  3064  3064 D PbapServerProfile: Bluetooth service disconnected
,09-06 19:16:13.590  3177  3177 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@25310373, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21f2b52c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22ddb230mSocket: android.net.LocalSocket@25cfaea9 impl:android.net.LocalSocketImpl@205b0c2e fd:FileDescriptor[76]
09-06 19:16:13.590  3177  3177 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@25cfaea9 impl:android.net.LocalSocketImpl@205b0c2e fd:FileDescriptor[76]
,09-06 19:16:13.600  3177  3177 I BtOppRfcommListener: stopping Accept Thread
,09-06 19:16:13.600  3177  3177 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e0e63cf, channel: 12, state: LISTENING
,09-06 19:16:13.600  3177  3177 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e0e63cf, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38934856, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2fa3c15cmSocket: android.net.LocalSocket@16cb8c65 impl:android.net.LocalSocketImpl@348fbd3a fd:FileDescriptor[80]
,09-06 19:16:13.600  3177  3177 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@16cb8c65 impl:android.net.LocalSocketImpl@348fbd3a fd:FileDescriptor[80]
,09-06 19:16:13.600  3177  5198 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:16:13.600  3177  3177 V BluetoothOppManager: cleanUp...
,09-06 19:16:13.600  3064  3064 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:13.610  3064  3064 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:13.610  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:13.610  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:16:13.620  1013  1130 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 19:16:13.620  1013  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:13.620  1013  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:13.620  1013  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:13.620  1013  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:13.630  6828  6828 E Zygote  : MountEmulatedStorage()
09-06 19:16:13.630  6828  6828 E Zygote  : v2
09-06 19:16:13.630  6828  6828 I libpersona: KNOX_SDCARD checking this for 10055
09-06 19:16:13.630  6828  6828 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:13.630  6828  6828 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:13.630  1013  1130 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6828 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-06 19:16:13.630  6828  6828 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:16:13.640  6828  6828 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:13.660  6828  6828 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:13.670  6828  6828 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:13.690  6828  6828 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-06 19:16:13.720  6828  6828 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-06 19:16:13.720  6828  6828 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-06 19:16:13.720  6828  6828 D UserAnalysis: Create SecureDbHelper
,09-06 19:16:13.730  6828  6828 D IntelligenceServiceApplication: onCreate()
,09-06 19:16:13.730  1013  1477 I ActivityManager: Killing 6396:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-06 19:16:13.740  1013  1494 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 19:16:13.740  6828  6828 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 19:16:13.740  1013  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:13.740  1013  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:13.740  1013  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:13.740  1013  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:13.760  6846  6846 E Zygote  : MountEmulatedStorage()
09-06 19:16:13.760  6846  6846 E Zygote  : v2
09-06 19:16:13.760  6846  6846 I libpersona: KNOX_SDCARD checking this for 10105
09-06 19:16:13.760  6846  6846 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:13.760  6846  6846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:13.760  1013  1494 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6846 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-06 19:16:13.760  6846  6846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:13.760  1013  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-06 19:16:13.770  6846  6846 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-06 19:16:13.770  6828  6828 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-06 19:16:13.780  3177  3297 W bt-l2cap: HC lib lpm enable=0 return 0
,09-06 19:16:13.780  3177  3346 I bt_userial_mct: exiting userial_read_thread
09-06 19:16:13.780  3177  3346 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:16:13.790  3177  3273 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:16:13.790  3177  3297 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-06 19:16:13.790  3177  3297 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:13.790  3177  3297 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:13.790  3177  3297 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:13.790  3177  3297 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:13.790  3177  3297 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:13.790  3177  3297 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:13.790  3177  3297 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:13.790  3177  3297 W bt-btif : ag scb idx 1 not allocated
09-06 19:16:13.790  3177  3297 W bt-btif : ag scb idx 2 not allocated
09-06 19:16:13.790  3177  3297 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:16:13.790  6828  6828 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-06 19:16:13.790  3177  3299 I bt_vendor: hw_epilog_process
09-06 19:16:13.790  3177  3273 D bt_userial_mct: userial_close
09-06 19:16:13.790  3177  3273 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 19:16:13.810  6846  6846 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:13.810  6846  6846 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:13.950  6690  6690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:16:13.960   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:16:13.960   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:16:13.960  6846  6866 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:16:13.960   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:16:13.960   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:13.960  6846  6866 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:16:14.000  3177  3273 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-06 19:16:14.000  3177  3273 I bt_vendor: bluetooth satus is on
09-06 19:16:14.000  3177  3273 I bt_vendor: bt-vendor : resetting BT status
09-06 19:16:14.000  3177  3273 I bt_vendor: Starting hciattach daemon
,09-06 19:16:14.000  3177  3273 I bt_vendor: try to set false
,09-06 19:16:14.000  3177  3273 I bt_vendor: Starting hciattach daemon
09-06 19:16:14.000  3177  3273 I bt_vendor: try to set false
,09-06 19:16:14.000  3177  3273 I bt_vendor: cleanup
09-06 19:16:14.000  3177  3297 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 19:16:14.000  3177  3273 I GKI_LINUX: GKI_exit_task 0 done
,09-06 19:16:14.000  3177  3273 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:16:14.000  3177  3270 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:16:14.000  3177  3270 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:16:14.000  3177  3270 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-06 19:16:14.000  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
09-06 19:16:14.000  1013  1466 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.000  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:16:14.000  1013  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-06 19:16:14.000  3177  3270 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService,
09-06 19:16:14.010  1013  1569 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:14.000  1013  1466 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.010  1013  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-06 19:16:14.000  1013  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.000  1013  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:14.010  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:16:14.010  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:16:14.010  3177  3270 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 19:16:14.010  3177  3177 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:16:14.010  3177  3177 D BtGatt.GattService: Received stop request...Stopping profile...
,09-06 19:16:14.010  3177  3177 D BtGatt.GattService: stop()
09-06 19:16:14.010  3177  3177 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:16:14.010  1013  1569 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.010  1013  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.010  1013  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:14.020  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:16:14.020  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:14.020  3177  3177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
09-06 19:16:14.020  3177  3270 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-06 19:16:14.020  1013  1452 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.020  1013  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.020  3177  3177 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:16:14.030  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:14.030  1013  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:14.030  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:14.030  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:16:14.030  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:16:14.030  3177  3270 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:16:14.030  1013  1466 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.030  1013  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.040  3177  3177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
09-06 19:16:14.040  1013  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:14.040  1013  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.040  1013  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:14.040  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-06 19:16:14.040  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 19:16:14.050  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:16:14.050  3177  3270 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:16:14.050  1013  1568 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:14.050  1013  1568 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.050  1013  1568 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:14.050  1013  1568 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.050  1013  1568 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:14.050  3064  3064 D HeadsetProfile: Bluetooth service disconnected
09-06 19:16:14.060  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 19:16:14.060  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:16:14.060  3177  3270 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService,
09-06 19:16:14.060  1013  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.060  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.060  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:14.060  1013  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.060  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:14.060  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:14.060  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:14.060  3177  3270 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:14.060  1013  1452 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:14.060  1013  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.070  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:14.070  1013  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:14.070  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:14.070  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:16:14.070  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:16:14.070  3177  3270 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:16:14.070  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:14.070  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.070  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.070  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.070  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:14.070  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:14.070  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:14.070  3177  3270 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:14.070  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:14.070  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:16:14.070  3177  3270 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:14.070  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:16:14.070  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:16:14.070  3177  3270 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:16:14.070  3177  3270 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:16:14.070  3177  3270 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 19:16:14.070  3177  3270 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:16:14.070  3177  3270 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:16:14.070  3177  3177 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-06 19:16:14.080  3177  3177 D A2dpService: Received stop request...Stopping profile...
09-06 19:16:14.080  3177  3289 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:16:14.080  3177  3177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:14.080  1013  1013 D BluetoothA2dp: Proxy object disconnected
,09-06 19:16:14.080  3064  3064 D BluetoothA2dp: Proxy object disconnected
09-06 19:16:14.080  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:16:14.080  3064  3064 D A2dpProfile: Bluetooth service disconnected
,09-06 19:16:14.080  3177  3177 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 19:16:14.080  3177  3177 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:14.080  3177  3177 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 19:16:14.080  3177  3177 D HidService: Received stop request...Stopping profile...
09-06 19:16:14.080  3177  3177 D HidService: Stopping Bluetooth HidService
09-06 19:16:14.080  3177  3177 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:16:14.080  3177  3177 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 19:16:14.080  3177  3177 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:16:14.090  3177  3177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:14.090  3064  3064 D BluetoothInputDevice: Proxy object disconnected
09-06 19:16:14.090  3064  3064 D HidProfile: Bluetooth service disconnected
,09-06 19:16:14.090  3177  3177 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:16:14.090  3177  3177 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:16:14.090  3177  3177 D HealthService: Received stop request...Stopping profile...
09-06 19:16:14.090  3177  3177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:14.090  3177  3177 D PanService: Received stop request...Stopping profile...
09-06 19:16:14.090  3177  3177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:14.090  1013  1013 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:16:14.090  3177  3177 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:16:14.090  3064  3064 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:16:14.090  3064  3064 D PanProfile: Bluetooth service disconnected
,09-06 19:16:14.100  3177  3177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:14.100  3064  3064 D BluetoothMap: Proxy object disconnected
09-06 19:16:14.100  3064  3064 D MapProfile: Bluetooth service disconnected
,09-06 19:16:14.100  3177  3177 D SapService: Received stop request...Stopping profile...
09-06 19:16:14.100  3177  3177 D SapService: Stopping Bluetooth SapService
09-06 19:16:14.100  3177  3177 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:14.100  3064  3064 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:16:14.100  3064  3064 D SapProfile: Bluetooth service disconnected
,09-06 19:16:14.100  3177  3177 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 19:16:14.100  3177  3177 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:14.100  3177  3177 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:16:14.100  3177  3290 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:16:14.100  3177  3177 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:16:14.100  3177  3177 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:16:14.100  3177  3177 D BluetoothA2dp: Proxy object disconnected
09-06 19:16:14.100  3177  3177 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-06 19:16:14.100  3177  3177 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 19:16:14.100  3177  3177 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.100  3177  3177 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:14.100  3177  3177 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 19:16:14.100  3177  3177 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.100  3177  3177 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.100  3177  3177 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:16:14.100  3177  3177 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-06 19:16:14.100  3177  3177 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 19:16:14.100  3177  3177 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.100  3177  3177 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.100  3177  3177 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:16:14.100  3177  3177 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:16:14.100  3177  3177 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-06 19:16:14.100  3177  3177 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:16:14.110  3177  3177 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-06 19:16:14.110  3177  3177 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-06 19:16:14.110  3177  3177 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:16:14.110  3177  3177 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-06 19:16:14.110  3177  3270 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:16:14.110  3177  3270 D BluetoothAdapterProperties: Setting state to 10
09-06 19:16:14.110  3177  3270 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:16:14.110  3177  3270 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:14.110  3177  3270 D BluetoothAdapterService: updateAdapterState state is 10
09-06 19:16:14.110  3177  3270 D BluetoothAdapterService: Autoconnection is available 
09-06 19:16:14.110  3177  3270 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 19:16:14.110  3177  3270 I BluetoothAdapterState: Entering OffState
,09-06 19:16:14.110  3064  3075 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:16:14.110  1992  2001 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.110  1992  2001 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.120  3064  3072 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:16:14.120  3064  3075 D Bluetoothsap: onBluetoothStateChange: up=false
09-06 19:16:14.120  3064  3075 D Bluetoothsap: Unbinding service...
,09-06 19:16:14.120  3064  3072 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:16:14.120  3177  3200 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:16:14.120  3177  3367 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.120  3177  3367 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.120  1436  1458 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.120  1436  1458 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.120  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:16:14.130  6690  6698 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.130  6690  6698 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:16:14.130  6690  6698 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-06 19:16:14.130  6690  6698 D BluetoothLeAdvertiser: Exit stop advertising
09-06 19:16:14.130  6690  6698 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 19:16:14.130  6690  6698 D BluetoothLeScanner: Exiting stopAllScan
09-06 19:16:14.130  3064  3072 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.130  3064  3072 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.130  1427  1438 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.130  1427  1438 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.130  1173  1783 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.130  1173  1783 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.130  1459  4117 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:14.130  1459  4117 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.140  3064  3072 D BluetoothInputDevice: onBluetoothStateChange: up=false,
09-06 19:16:14.140  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:14.140  1013  1042 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:14.140  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-06 19:16:14.150  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:16:14.150  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:14.150  1013  1013 I InputMethodManagerService: [BT Setting State] State =10
09-06 19:16:14.150  1013  1013 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:16:14.160  1173  1173 D BluetoothAdapter: 1008569655: getState() :  mService = null. Returning STATE_OFF
,09-06 19:16:14.160  1173  1713 D BluetoothAdapter: 1008569655: getState() :  mService = null. Returning STATE_OFF
09-06 19:16:14.160  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:16:14.160  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:14.160  1173  1173 D BluetoothTile:  getBluetoothState : 10
,09-06 19:16:14.160  1173  1713 D BluetoothAdapter: 1008569655: getState() :  mService = null. Returning STATE_OFF
09-06 19:16:14.160  1173  1173 D BluetoothAdapter: 1008569655: getState() :  mService = null. Returning STATE_OFF
09-06 19:16:14.160  1173  1173 D BluetoothAdapter: 1008569655: getState() :  mService = null. Returning STATE_OFF
,09-06 19:16:14.160  1013  1568 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:14.160  1876  1876 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:16:14.160  1013  1130 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 19:16:14.160  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 19:16:14.160  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:16:14.170  1992  2161 D BluetoothAdapter: 211007839: getState() :  mService = null. Returning STATE_OFF
,09-06 19:16:14.170  1992  2161 D BluetoothAdapter: 211007839: getState() :  mService = null. Returning STATE_OFF
,09-06 19:16:14.170  3064  3064 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:14.170  1013  1359 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:14.170  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.170  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:14.170  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:14.170  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:14.170  1013  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:14.170  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:14.180  6846  6846 D StrictMode: StrictMode policy violation; ~duration=213 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:14.180  6846  6846 D StrictMode: StrictMode policy violation; ~duration=213 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:14.180  6846  6846 D StrictMode: StrictMode policy violation; ~duration=210 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:14.180  6846  6846 D StrictMode: StrictMode policy violation; ~duration=208 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:14.180  6846  6846 D StrictMode: StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.k.d(PG:583)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:14.180  1013  1452 I ActivityManager: Killing 6289:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
09-06 19:16:14.180  6846  6846 D StrictMode: StrictMode policy violation; ~duration=185 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:14.180  6846  6846 D StrictMode: StrictMode policy violation; ~duration=184 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:14.180  6846  6846 D StrictMode: StrictMode policy violation; ~duration=184 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:14.180  6846  6846 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:14.180  3177  3273 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-06 19:16:14.180  3177  3177 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:16:14.180  3177  3177 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:16:14.190  3177  3177 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:16:14.190  3177  3177 I art     : System.exit called, status: 0
09-06 19:16:14.190  3177  3177 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 19:16:14.190  1992  1992 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 19:16:14.200  1992  1992 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-06 19:16:14.210  3064  3064 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 19:16:14.210  1013  1568 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:16:14.210  1013  1568 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-06 19:16:14.210  1013  1568 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.210  1013  1568 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:14.210  1013  1568 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-06 19:16:14.210  3064  3064 D DockEventReceiver: finishStartingService: stopping service
09-06 19:16:14.210  3064  3064 D BluetoothNotiBroadcastReceiver: onReceive
09-06 19:16:14.220  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:14.220  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 19:16:14.220  1013  1359 I ActivityManager: Process com.android.bluetooth (pid 3177)(adj 0) has died(30,713)
09-06 19:16:14.220  1013  1452 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
09-06 19:16:14.230  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.230  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.230  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.230  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.250  6885  6885 E Zygote  : MountEmulatedStorage()
09-06 19:16:14.250  6885  6885 E Zygote  : v2
09-06 19:16:14.250  6885  6885 I libpersona: KNOX_SDCARD checking this for 1002
09-06 19:16:14.250  6885  6885 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:14.250  6885  6885 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:14.250  1013  1452 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6885 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
09-06 19:16:14.260  6885  6885 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:14.260  6885  6885 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:14.270  6846  6874 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:16:14.300  1013  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:14.300  1013  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:14.300  1013  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:14.300  1013  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-06 19:16:14.300  6885  6885 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:14.300  6885  6885 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:14.320  6885  6885 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 19:16:14.320  6885  6885 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:16:14.320  1369  1369 I wpa_supplicant: nl80211: Received scan results (11 BSSes)
,09-06 19:16:14.320  1013  1121 D WifiP2pService: InactiveState{ what=147461 }
,09-06 19:16:14.320  1013  1121 D WifiP2pService: P2pEnabledState{ what=147461 }
,09-06 19:16:14.320  1013  1121 D WifiP2pService: DefaultState{ what=147461 }
09-06 19:16:14.320  1013  1121 D WifiP2pService: InactiveState{ what=143375 }
09-06 19:16:14.320  1013  1121 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:16:14.330   277  1000 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:16:14.340  1013  1124 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
,09-06 19:16:14.330  1992  3018 V NativeCrypto: Read error: ssl=0xb7cc9018: I/O error during system call, Connection timed out
09-06 19:16:14.340  1013  1124 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-06 19:16:14.340  1013  1124 E ConnectivityService: updateNetworkInfo()
09-06 19:16:14.340  1013  1121 D WifiP2pService: InactiveState{ what=131204 }
,09-06 19:16:14.340  1013  1124 E ConnectivityService: updateNetworkInfo()
09-06 19:16:14.340  1013  1121 D WifiP2pService: P2pEnabledState{ what=131204 }
09-06 19:16:14.340  1992  3018 V NativeCrypto: SSL shutdown failed: ssl=0xb7cc9018: I/O error during system call, Broken pipe
,09-06 19:16:14.340  1992  3018 E GCM     : Wifi connection closed with errorCode 20,
09-06 19:16:14.340  1013  1121 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-06 19:16:14.340  1013  1122 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-06 19:16:14.350  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:14.350  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-06 19:16:14.350  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.350  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:16:14.350  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.350  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.350  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.360  1013  1469 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,09-06 19:16:14.360  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:14.360  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:16:14.360  1013  1013 D RttService: SCAN_AVAILABLE : 1
09-06 19:16:14.360  1013  1145 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:14.360  1013  1146 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:14.360  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:14.360  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.370  1992  6812 I qtaguid : Untagging socket 77
,09-06 19:16:14.370  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.370  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.370  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.370  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-06 19:16:14.370  1013  1743 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-13ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:14.370  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:16:14.370  1013  1743 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-14ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:14.370  1013  1121 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:16:14.370  1013  1743 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 19:16:14.370  6885  6885 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
09-06 19:16:14.370  1013  1743 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:14.370  1013  1743 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-06 19:16:14.380  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 19:16:14.380  1013  1121 D WifiP2pService: P2pDisablingState
09-06 19:16:14.380  1013  1121 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 19:16:14.380  1013  1121 D WifiP2pService: p2p socket connection lost
09-06 19:16:14.380  1013  1121 D WifiP2pService: P2pDisabledState
,09-06 19:16:14.380  1013  1743 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:16:14.380  1013  1743 I qtaguid : Tagging socket 346 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1013, getuid(): 1000
09-06 19:16:14.380  1013  1122 E WifiNative-wlan0: do suspend true
,09-06 19:16:14.380  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:16:14.380  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:16:14.380  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-06 19:16:14.380  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:16:14.380  1013  1043 D WifiDisplayController: disconnect,
09-06 19:16:14.380  1013  1043 D WifiDisplayController: updateConnection
,09-06 19:16:14.380  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:16:14.380  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:16:14.380  1013  1121 D WifiP2pService: P2pDisabledState{ what=143375 }
09-06 19:16:14.380  1013  1121 D WifiP2pService: DefaultState{ what=143375 }
09-06 19:16:14.380  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,09-06 19:16:14.380  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:16:14.380  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:16:14.380  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:16:14.390  1992  6812 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
09-06 19:16:14.390  1992  6812 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-06 19:16:14.390  1992  6812 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1992, getuid(): 10011
,09-06 19:16:14.390  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-06 19:16:14.390  1013  1743 I qtaguid : Untagging socket 346
,09-06 19:16:14.390  1013  1743 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:16:14.390   287   287 E SMD     : DCD OFF
,09-06 19:16:14.390   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:14.400  1013  1452 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:16:14.400  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:16:14.400  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:14.400  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:14.400  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.400  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.400  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.400  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding GattService,
09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding HeadsetService
09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding A2dpService
09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding HidService
,09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding HealthService
09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding PanService
09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding SapService,
09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding SapClientService
09-06 19:16:14.410  6885  6885 D BtSettings.ProfileConfig: Adding HidDevService
09-06 19:16:14.410  6885  6885 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******,
,09-06 19:16:14.420  1013  1025 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 19:16:14.420  1013  1025 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.420  1013  1025 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:14.420  1013  1025 D SettingsProvider: selectionArgs: false
,09-06 19:16:14.420  1013  1025 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.420  1013  1025 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.420  1013  1025 D SettingsProvider: ret = -1
,09-06 19:16:14.420  1013  1359 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-06 19:16:14.420  1013  1359 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.420  1013  1359 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:14.420  1013  1359 D SettingsProvider: selectionArgs: false
09-06 19:16:14.420  1013  1359 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.420  1013  1359 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.420  1013  1359 D SettingsProvider: ret = -1
,09-06 19:16:14.420  1013  1569 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-06 19:16:14.420  1013  1569 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.420  1013  1569 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:14.420  1013  1569 D SettingsProvider: selectionArgs: false
09-06 19:16:14.420  1013  1569 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.420  1013  1569 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.420  1013  1569 D SettingsProvider: ret = -1
09-06 19:16:14.420  1013  1130 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-06 19:16:14.420  1013  1130 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.420  1013  1130 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:14.420  1013  1130 D SettingsProvider: selectionArgs: false
,09-06 19:16:14.420  1013  1130 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.420  1013  1130 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.420  1013  1130 D SettingsProvider: ret = -1,
09-06 19:16:14.420   277   996 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:16:14.420   277   996 D Netd    : getNetworkForDns: using netid 0 for uid 1000,
09-06 19:16:14.430  1013  1124 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-06 19:16:14.420   277  1000 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:16:14.430  1013  1124 V NetworkStats: updateIfacesLocked()
09-06 19:16:14.420  1013  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-06 19:16:14.430  1013  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:14.420  1013  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.420  1013  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:14.420  1013  1026 D SettingsProvider: selectionArgs: false
09-06 19:16:14.420  1013  1026 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.420  1013  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.420  1013  1026 D SettingsProvider: ret = -1
09-06 19:16:14.420  1992  6812 I qtaguid : Untagging socket 47
09-06 19:16:14.430  1992  6812 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:16:14.430  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.430  1992  6812 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-06 19:16:14.430  1992  6812 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1992, getuid(): 10011
09-06 19:16:14.430  1013  1743 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-06 19:16:14.430  1013  1743 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-06 19:16:14.430  1992  6812 I qtaguid : Untagging socket 47
09-06 19:16:14.430  1992  6812 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:16:14.430  1013  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:14.430  1013  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:16:14.430  1992  6812 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-06 19:16:14.430  1992  6812 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1992, getuid(): 10011
09-06 19:16:14.430  1013  1227 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-06 19:16:14.430  1013  1227 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.430  1013  1227 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:14.430  1013  1227 D SettingsProvider: selectionArgs: false
09-06 19:16:14.430  1013  1227 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.430  1013  1227 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.430  1013  1227 D SettingsProvider: ret = -1
09-06 19:16:14.430  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:16:14.430  1992  6812 I qtaguid : Untagging socket 47
09-06 19:16:14.430  1369  1369 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-06 19:16:14.430  1013  1466 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 19:16:14.430  1013  1466 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.430  1013  1466 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:14.430  1013  1466 D SettingsProvider: selectionArgs: false
09-06 19:16:14.430  1013  1466 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.430  1013  1466 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.430  1013  1466 D SettingsProvider: ret = -1
09-06 19:16:14.430  1992  6812 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:16:14.430  1013  1478 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-06 19:16:14.430  1013  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.430  1013  1478 D SettingsProvider: projectionArgs: isSettingsCh,angesAllowed
09-06 19:16:14.430  1013  1478 D SettingsProvider: selectionArgs: false
09-06 19:16:14.430  1013  1478 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.430  1013  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.430  1013  1478 D SettingsProvider: ret = -1
09-06 19:16:14.430  1013  1452 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:14.430  1013  1452 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.430  1013  1452 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:14.430  1013  1452 D SettingsProvider: selectionArgs: false
09-06 19:16:14.430  1013  1452 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.430  1013  1452 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.430  1013  1452 D SettingsProvider: ret = -1
09-06 19:16:14.430  1013  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:14.430  1013  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.430  1013  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:14.430  1013  1477 D SettingsProvider: selectionArgs: false
09-06 19:16:14.430  1013  1477 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.430  1013  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.430  1013  1477 D SettingsProvider: ret = -1
,09-06 19:16:14.430  1992  6812 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-06 19:16:14.430  1013  1124 V NetworkStats: performPollLocked() took 8ms
09-06 19:16:14.430  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.430  1013  1124 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-06 19:16:14.430  1013  4422 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 19:16:14.430  1013  4422 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.430  1013  4422 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:14.430  1013  4422 D SettingsProvider: selectionArgs: false
09-06 19:16:14.430  1013  4422 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.430  1013  4422 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.430  1013  4422 D SettingsProvider: ret = -1
09-06 19:16:14.430  1992  6812 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1992, getuid(): 10011
09-06 19:16:14.430  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.430  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.440  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:14.440  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:14.440  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.440  1013  1568 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-06 19:16:14.440  1013  1568 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:14.440  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.440  1013  1568 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:14.440  1013  1568 D SettingsProvider: selectionArgs: false
09-06 19:16:14.440  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.440  1013  1568 D SettingsProvider: selectionArgs: 1002
09-06 19:16:14.440  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.440  1013  1568 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:14.440  1013  1568 D SettingsProvider: ret = -1
09-06 19:16:14.440  1173  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:16:14.440  1013  1743 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:14.440  1013  1042 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-06 19:16:14.440  4757  6753 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:16:14.440  1013  1124 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:14.440  1013  1121 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:16:14.440  1992  6812 I qtaguid : Untagging socket 47
09-06 19:16:14.440  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:14.440  1013  1122 D SecContentProvider2: mCursor = null
09-06 19:16:14.440  1459  1459 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:16:14.440  1459  1459 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:16:14.440  1013  1124 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-06 19:16:14.440  1013  1124 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,09-06 19:16:14.440  1013  1124 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-06 19:16:14.450  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:14.450  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:16:14.450  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.450  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.450  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.450  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.450  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:14.450  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-06 19:16:14.450  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:16:14.450  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:14.450  3064  3064 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:14.450  1173  1173 D HotspotTile: onReceive : 0, 0
,09-06 19:16:14.460  1013  1122 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 19:16:14.460  1013  1124 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 19:16:14.460  1013  1124 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 19:16:14.460  1013  1124 E ConnectivityService: updateNetworkInfo()
09-06 19:16:14.460  1013  1124 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:14.460  1013  1124 E ConnectivityService: updateNetworkInfo()
,09-06 19:16:14.460  1992  6812 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/74.125.133.95 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
09-06 19:16:14.460  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.460  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:14.460  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:14.460  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:14.460  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:14.460  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:14.460  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:14.460  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:14.460  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:14.460  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.460  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:14.470  1013  1042 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 19:16:14.470  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.470  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:14.470  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:14.470  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:14.470  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:14.470  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:14.470  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:14.470  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:14.470  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:14.470  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.470  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:14.470  1013  1013 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 19:16:14.470  1013  1125 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:16:14.470  1013  1119 V NetworkStats: updateIfacesLocked()
,09-06 19:16:14.470  1013  1119 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:14.470  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.470  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:14.470  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
,09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0,
09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:16:14.480  1013  1119 V NetworkStats: performPollLocked() took 5ms
09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: updateDataNetType()
,09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 19:16:14.480  1013  1025 I ActivityManager: Killing 6424:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
09-06 19:16:14.480  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-06 19:16:14.480  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:14.480  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:14.480  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.480  1013  1120 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 19:16:14.480  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.480  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:14.480  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:14.480  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:14.500  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.500  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:14.520  1992  1992 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:14.520  1013  1025 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:14.520  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:16:14.520  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:14.520  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:14.520  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:14.570  1369  1369 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:14.580  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,09-06 19:16:14.580  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.580  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.580  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.580  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.590  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.590  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.590  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.590  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.590  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.590  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.600  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.600  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.600  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.600  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.600  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.600  1992  6914 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:16:14.600  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.600  1992  1992 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:16:14.600  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.600  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.610  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.610  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.610  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.610  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.610  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.620  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.620  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.620  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:16:14.620  1992  2176 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-06 19:16:14.620  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:16:14.620  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:16:14.620  1992  2159 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,09-06 19:16:14.620  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:16:14.630  1369  1369 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-06 19:16:14.630  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:14.630  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:14.630  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:16:14.650  1369  1369 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-06 19:16:14.650  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.650  1369  1369 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 19:16:14.650  1369  1369 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 19:16:14.650  1369  1369 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:16:14.650  1369  1369 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-06 19:16:14.650  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:14.650  1013  1125 D Tethering: InitialState.processMessage what=4
09-06 19:16:14.650  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.650  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.650  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:14.710   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7cc47c8
09-06 19:16:14.710   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-06 19:16:14.710   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-06 19:16:14.710   272   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1211348856)
,09-06 19:16:14.750   272   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
09-06 19:16:14.750   272   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-06 19:16:14.750   272   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1211348856) wakelock released: 1, error no: 0
09-06 19:16:14.750   272   341 I rmt_storage: 
09-06 19:16:14.750   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7cc47c8
,09-06 19:16:14.780  1013  1025 I art     : Explicit concurrent mark sweep GC freed 40855(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 2.574ms total 174.006ms
09-06 19:16:14.780  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:14.790  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.790  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.790  1013  1125 E Tethering: No numeric data
09-06 19:16:14.790  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:14.790  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:14.790  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.790  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:14.790  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:16:14.790  1013  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:14.790  1013  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:14.790  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:14.790  1013  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:14.790  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:14.800  1013  1125 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 19:16:14.800  1013  1125 D Tethering: clearTetheredNotification()
,09-06 19:16:14.800  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.800  1013  1119 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:14.800  1587  1587 I Hs20UtilService: Starting #8
09-06 19:16:14.800  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:14.800  1587  1630 I Hs20UtilService: Message received 5007
09-06 19:16:14.800  1173  1173 D HotspotTile: updateTetherState():false, false
09-06 19:16:14.800  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:14.800  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:14.810  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.810  1013  1119 V NetworkStats: performPollLocked() took 4ms
,09-06 19:16:14.810  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:14.810  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:14.810  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:16:14.820  1013  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:14.820  3064  3064 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
09-06 19:16:14.820  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:14.820  1013  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:14.820  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:16:14.820  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:16:14.820  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:14.820  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:14.820  3064  3064 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:16:14.830  3064  3832 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:14.830  1992  6914 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-06 19:16:14.840  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:16:14.840  3064  3064 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:16:14.840  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:14.840  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:16:14.850  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:14.850  3064  3064 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:16:14.850  3064  3832 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:14.850  1013  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-06 19:16:14.850  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.850  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.850  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.850  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:14.860  6926  6926 E Zygote  : MountEmulatedStorage(),
09-06 19:16:14.860  1013  1477 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6926 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:14.860  6926  6926 E Zygote  : v2
09-06 19:16:14.860  6926  6926 I libpersona: KNOX_SDCARD checking this for 10064
09-06 19:16:14.860  6926  6926 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:14.870  6926  6926 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:14.870  6926  6926 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:16:14.870  6926  6926 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:14.880  1369  1369 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:14.890  6926  6926 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-06 19:16:14.890  6926  6926 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:14.900  6926  6926 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 19:16:14.920  6926  6926 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:14.920  6926  6926 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:16:14.950  1369  1369 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 19:16:14.950  1013  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
09-06 19:16:14.950  6926  6926 D FileShare-Client: Outbound.stopDelayTimer - 
09-06 19:16:14.950  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.950  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:14.950  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.950  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:14.950  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.950  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:14.950  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:16:14.960  1013  1124 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:14.970  6941  6941 E Zygote  : MountEmulatedStorage()
09-06 19:16:14.970  6941  6941 E Zygote  : v2
09-06 19:16:14.970  6941  6941 I libpersona: KNOX_SDCARD checking this for 10065
09-06 19:16:14.970  6941  6941 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:14.970  1013  1477 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6941 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:14.970  6941  6941 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:14.970  6941  6941 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:14.980  1013  1013 I ApplicationPolicy: updateDataUsageMap
09-06 19:16:14.980  6941  6941 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:14.990  1013  1037 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:14.990  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:14.990  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:14.990  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:14.990  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:14.990  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:14.990  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:14.990  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:14.990  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:14.990  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:15.000  6941  6941 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:15.000  6941  6941 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:15.000  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:15.020  6941  6941 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:15.030  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.030  1013  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:15.030  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-06 19:16:15.030  1013  1452 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-06 19:16:15.030  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.030  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.030  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.030  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.040  6956  6956 E Zygote  : MountEmulatedStorage(),
,09-06 19:16:15.040  6956  6956 E Zygote  : v2,
09-06 19:16:15.040  1013  1452 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6956 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-06 19:16:15.040  6956  6956 I libpersona: KNOX_SDCARD checking this for 10102
,09-06 19:16:15.050  6956  6956 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:15.050  1013  1452 I ActivityManager: Killing 6474:com.samsung.android.sm/1000 (adj 15): empty #21
,09-06 19:16:15.050  6956  6956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:15.050  6956  6956 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:15.050  6956  6956 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:16:15.060  1013  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-06 19:16:15.060  1013  1122 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:16:15.060  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:15.060  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-06 19:16:15.060  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:15.070  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:15.070  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:15.070  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:15.070  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:15.070  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-06 19:16:15.070  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:16:15.070  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:15.070  1173  1173 D HotspotTile: onReceive : 1, 0
,09-06 19:16:15.070  1992  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:15.070  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:15.080  3064  3064 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:15.080  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:15.090  6956  6956 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:15.090  6956  6956 D ActivityThread: Added TimaKeyStore provider,
,09-06 19:16:15.100  6956  6956 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:16:15.320  6956  6976 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-06 19:16:15.320  6956  6976 I Babel_SMS: MmsConfig.loadMmsSettings
,09-06 19:16:15.320  6956  6976 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-06 19:16:15.320  6956  6976 I Babel_SMS: MmsConfig.loadFromDatabase
,09-06 19:16:15.340  6956  6976 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-06 19:16:15.340  6956  6976 I Babel_SMS: MmsConfig.loadFromResources
,09-06 19:16:15.340  6956  6976 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-06 19:16:15.340  6956  6976 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-06 19:16:15.360  1013  1227 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-06 19:16:15.360  1013  1227 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-06 19:16:15.360  1013  1227 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.360  1013  1227 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:15.360  1013  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:16:15.370  6956  6956 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:15.380  6956  6956 I Babel_Crash: startup - clean
,09-06 19:16:15.390   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:15.410  1013  1568 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:15.410  1013  1568 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:15.420  1013  1568 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.420  1013  1568 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.420  1013  1568 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:15.420  1587  1587 I Hs20UtilService: Starting #9
09-06 19:16:15.420  1587  1630 I Hs20UtilService: Message received 5007
,09-06 19:16:15.420  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:16:15.420  3064  3064 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:16:15.420  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:15.430  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:15.430  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:15.430  3064  3064 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:16:15.430  3064  3832 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:15.430  6956  6956 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:16:15.440  1013  1359 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:15.440  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:16:15.440  6956  6956 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:16:15.440  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.440  1013  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.440  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:15.450  6956  6956 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:16:15.450  1587  1587 I Hs20UtilService: Starting #10
,09-06 19:16:15.450  1587  1630 I Hs20UtilService: Message received 5011
,09-06 19:16:15.450  6956  6956 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-06 19:16:15.450  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:16:15.450  6956  6956 W AudioCapabilities: Unsupported mime audio/mpeg-L2
09-06 19:16:15.450  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:15.450  6503  6503 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:16:15.450  6503  6503 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:15.460  6956  6956 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-06 19:16:15.460  6956  6956 W AudioCapabilities: Unsupported mime audio/x-ima
,09-06 19:16:15.460  6956  6956 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:16:15.460  6956  6956 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:16:15.470  1013  4116 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.470  1013  4116 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.470  1013  4116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.470  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.470  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.470  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.470  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.470  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.470  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.480  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.480  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.480  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-06 19:16:15.480  6956  6956 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:16:15.480  6956  6956 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:16:15.480  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.480  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.480  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.490  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.490  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.490  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.490  6956  6956 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-06 19:16:15.490  6956  6956 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:16:15.490  6956  6956 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:16:15.490  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:15.490  6956  6956 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
09-06 19:16:15.490  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.490  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.500  6956  6956 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-06 19:16:15.500  6956  6956 W VideoCapabilities: Unsupported mime video/mp43
09-06 19:16:15.500  6956  6956 W VideoCapabilities: Unsupported mime video/sorenson
,09-06 19:16:15.510  6956  6956 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 19:16:15.520  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.520  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.520  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.520  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.520  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.520  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.520  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.520  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.520  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.520  6956  6956 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 19:16:15.530  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.530  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.530  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.530  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.530  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.530  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.530  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.530  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.530  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.530  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:15.530  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.530  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.540  1013  1013 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:16:15.540  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:15.540  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:16:15.540  1013  1013 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 19:16:15.540  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:16:15.540  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.540  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.540  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.550  1013  1040 D Tethering: interfaceRemoved wlan0,
09-06 19:16:15.550  1013  1040 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:16:15.560  6979  6979 E Zygote  : MountEmulatedStorage()
09-06 19:16:15.560  6979  6979 E Zygote  : v2
09-06 19:16:15.560  6979  6979 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:15.560  6979  6979 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:15.560  1013  1013 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6979 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:16:15.560  6956  6956 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-06 19:16:15.560  6979  6979 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:15.560  6956  6956 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:16:15.570  6979  6979 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:15.570  6956  6956 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
09-06 19:16:15.570  1013  1569 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-06 19:16:15.570  1013  1569 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:16:15.570  1013  1569 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:16:15.570  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-06 19:16:15.570  1013  1569 D BatteryService: stay LED for fully charged
,09-06 19:16:15.570  6979  6979 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:16:15.570  1013  1013 I MotionRecognitionService: Plugged
09-06 19:16:15.570  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:16:15.570  6956  6956 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-06 19:16:15.570  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-06 19:16:15.570  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:16:15.580  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-06 19:16:15.580  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 19:16:15.580  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:16:15.580  1013  1025 I ActivityManager: Killing 6452:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-06 19:16:15.590  6956  6956 I vclib   : onServiceConnected
,09-06 19:16:15.600  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:16:15.600  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:16:15.600  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-06 19:16:15.600  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-06 19:16:15.600  6979  6979 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:15.600  6979  6979 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:15.620  6979  6979 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-06 19:16:15.620  6979  6979 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-06 19:16:15.620  6979  6979 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-06 19:16:15.640  6979  6979 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-06 19:16:15.640  6979  6979 I PCWCLIENTTRACE_PushUtil: sales region : global
09-06 19:16:15.640  6979  6979 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-06 19:16:15.640  6979  6979 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:15.640  1013  1568 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-06 19:16:15.640  6979  6994 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
09-06 19:16:15.640  1013  1568 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-06 19:16:15.640  1013  1568 I ActivityManager: Killing 6524:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-06 19:16:15.650  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-06 19:16:15.650  1787  1787 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:16:15.650  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.650  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.650  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.650  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.680  6997  6997 E Zygote  : MountEmulatedStorage(),
09-06 19:16:15.680  6997  6997 E Zygote  : v2
09-06 19:16:15.680  6997  6997 I libpersona: KNOX_SDCARD checking this for 10121
09-06 19:16:15.680  6997  6997 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:15.680  6997  6997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:15.680  1013  1038 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6997 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
09-06 19:16:15.680  6997  6997 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:15.680  6997  6997 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:15.690  1013  1568 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-06 19:16:15.690  1013  1568 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.690  1013  1568 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.690  1013  1568 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.690  1013  1568 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.700  7008  7008 E Zygote  : MountEmulatedStorage()
,09-06 19:16:15.700  7008  7008 E Zygote  : v2
09-06 19:16:15.700  7008  7008 I libpersona: KNOX_SDCARD checking this for 10031
09-06 19:16:15.700  7008  7008 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:15.700  7008  7008 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:15.700  1013  1568 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7008 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-06 19:16:15.710  7008  7008 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:15.710  6997  6997 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:15.710  6997  6997 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:15.710  7008  7008 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-06 19:16:15.710  1013  1013 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-06 19:16:15.710  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:16:15.710  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.710  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.710  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.720  1013  1040 D Tethering: interfaceRemoved p2p0
,09-06 19:16:15.720  1013  1040 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:16:15.720  7022  7022 E Zygote  : MountEmulatedStorage(),
09-06 19:16:15.720  7022  7022 E Zygote  : v2
09-06 19:16:15.730  7022  7022 I libpersona: KNOX_SDCARD checking this for 10001
09-06 19:16:15.730  7022  7022 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:15.730  7022  7022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:15.730  7022  7022 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:15.730  1013  1013 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7022 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:15.730  7022  7022 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:15.740  7008  7008 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:15.740  7008  7008 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:15.740  6997  6997 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:15.740  6997  6997 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-06 19:16:15.740  6997  6997 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:16:15.750  2465  2485 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,09-06 19:16:15.750  7022  7022 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:15.750  7022  7022 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:15.750  1787  1787 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
09-06 19:16:15.750  1787  1787 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-06 19:16:15.760  1787  1787 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-06 19:16:15.760  1787  1787 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-06 19:16:15.760  6997  6997 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:15.770  6997  6997 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-06 19:16:15.770  1787  1787 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:16:15.770  1787  1787 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-06 19:16:15.770  1013  4422 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-06 19:16:15.770  1013  4422 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.770  1013  4422 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.770  1013  4422 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.770  1013  4422 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.780  7042  7042 E Zygote  : MountEmulatedStorage(),
09-06 19:16:15.780  7042  7042 E Zygote  : v2
09-06 19:16:15.780  7042  7042 I libpersona: KNOX_SDCARD checking this for 10077
09-06 19:16:15.780  7042  7042 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:15.790  7042  7042 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:15.790  7042  7042 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 19:16:15.790  1013  4422 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7042 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:15.790  7042  7042 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-06 19:16:15.790  6997  6997 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-06 19:16:15.800  1013  1026 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-06 19:16:15.800  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.800  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.800  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.800  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.800  7008  7008 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-06 19:16:15.810   309   309 I art     : Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 20.875ms,
,09-06 19:16:15.810  7042  7042 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-06 19:16:15.810  7042  7042 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:15.830   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 640us total 16.364ms
,09-06 19:16:15.840   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.166ms
,09-06 19:16:15.850  7059  7059 E Zygote  : MountEmulatedStorage(),
09-06 19:16:15.850  7059  7059 E Zygote  : v2
09-06 19:16:15.850  7059  7059 I libpersona: KNOX_SDCARD checking this for 10141
09-06 19:16:15.850  7059  7059 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:15.850  1013  1026 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7059 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
09-06 19:16:15.860  7059  7059 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:15.860  1013  1026 I ActivityManager: Killing 6541:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-06 19:16:15.860  7059  7059 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:15.860  7059  7059 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:16:15.860  1013  1026 I ActivityManager: Killing 6556:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-06 19:16:15.880  1013  1478 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-06 19:16:15.880  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.880  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.880  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.880  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.880  2754  7069 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-06 19:16:15.880  2754  7069 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-06 19:16:15.890  2754  7069 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-06 19:16:15.890  2754  7069 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
09-06 19:16:15.890  2754  7069 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-06 19:16:15.890  7059  7059 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:15.900  7074  7074 E Zygote  : MountEmulatedStorage()
,09-06 19:16:15.900  7074  7074 I libpersona: KNOX_SDCARD checking this for 10032
09-06 19:16:15.900  7074  7074 E Zygote  : v2
,09-06 19:16:15.900  7074  7074 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:15.900  7059  7059 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:15.900  7074  7074 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:15.900  7074  7074 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:16:15.900  7074  7074 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-06 19:16:15.900  1013  1478 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7074 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:15.900  1013  1478 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
09-06 19:16:15.910  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.910  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.910  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:15.910  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:15.920  1013  1478 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7088 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:16:15.920  1013  1478 I ActivityManager: Killing 6492:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-06 19:16:15.920  7088  7088 E Zygote  : MountEmulatedStorage()
09-06 19:16:15.920  7088  7088 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:15.920  7088  7088 E Zygote  : v2
09-06 19:16:15.920  7088  7088 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:15.930  7088  7088 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:15.930  7088  7088 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:15.930  7088  7088 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:15.940  7074  7074 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:15.940  7074  7074 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:15.960  7059  7059 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-06 19:16:15.960  7059  7059 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:15.960  7059  7059 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:16:15.960  7059  7059 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-06 19:16:15.960  7088  7088 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:15.960  7088  7088 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:16.000  7074  7106 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-06 19:16:16.000  7088  7088 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-06 19:16:16.000  7074  7106 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-06 19:16:16.010  7074  7074 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true,
,09-06 19:16:16.010  1013  1026 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-06 19:16:16.010  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.010  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.010  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.010  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.020  7074  7106 D SPPClientService: PushLog.txt file is not deleted.
,09-06 19:16:16.020  7074  7106 D SPPClientService: PushLog.txt file is not deleted.
09-06 19:16:16.020  7074  7106 D SPPClientService: ============PushLog. stop!,
,09-06 19:16:16.020  1013  4116 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:16.030  1013  1026 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7108 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:16.040  1013  1026 I ActivityManager: Killing 6579:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-06 19:16:16.040  1013  1359 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push,
09-06 19:16:16.040  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-06 19:16:16.040  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:16.040  1013  1359 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-06 19:16:16.040  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-06 19:16:16.040  7108  7108 E Zygote  : MountEmulatedStorage()
09-06 19:16:16.040  7108  7108 E Zygote  : v2
09-06 19:16:16.040  7108  7108 I libpersona: KNOX_SDCARD checking this for 10036
09-06 19:16:16.040  7108  7108 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:16.040  7108  7108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:16.040  7108  7108 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:16.040  7108  7108 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-06 19:16:16.050  1013  1477 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:16.060  7108  7108 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:16.060  7108  7108 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:16.090  7074  7115 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-06 19:16:16.110  7108  7108 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1da55235
,09-06 19:16:16.110  1013  1359 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:16.120  1013  1569 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:16.130  7108  7108 I SA      : [SSP] onCreated
,09-06 19:16:16.140  7108  7108 I SA      : [TPM] There is no property file
,09-06 19:16:16.140  7108  7108 I SA      : [SCU] isHaveSA() - false
,09-06 19:16:16.150  7108  7108 I SA      : [TPM] getModelProperty : null
09-06 19:16:16.150  7108  7108 I SA      : [TPM] getCSCProperty : null
,09-06 19:16:16.150  7108  7108 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-06 19:16:16.150  7108  7108 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-06 19:16:16.150  7108  7108 I SA      : [DM] TFT FEATURE: false
,09-06 19:16:16.160  7108  7108 I SA      : [DM] init START
,09-06 19:16:16.160  7108  7108 I SA      : [DM] This device is not a Vodafone
,09-06 19:16:16.160  7088  7088 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-06 19:16:16.170  7108  7108 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-06 19:16:16.170  7108  7108 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-06 19:16:16.170  7108  7108 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-06 19:16:16.170  7108  7108 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-06 19:16:16.170  7108  7108 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-06 19:16:16.170  7108  7108 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-06 19:16:16.170  7108  7108 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-06 19:16:16.170  7088  7088 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-06 19:16:16.180  7088  7088 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:16.180  7108  7108 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 19:16:16.180  7088  7088 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-06 19:16:16.180  7088  7088 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
09-06 19:16:16.180  7108  7108 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-06 19:16:16.180  7088  7088 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-06 19:16:16.180  7108  7108 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-06 19:16:16.180  1013  1466 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
09-06 19:16:16.180  7108  7108 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-06 19:16:16.180  7108  7108 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-06 19:16:16.180  1013  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.180  7108  7108 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-06 19:16:16.180  1013  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.180  7108  7108 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-06 19:16:16.180  1013  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.180  1013  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.180  7108  7108 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-06 19:16:16.180  7108  7108 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-06 19:16:16.180  7108  7108 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-06 19:16:16.180  7108  7108 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-06 19:16:16.180  7108  7108 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-06 19:16:16.190  7108  7108 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-06 19:16:16.190  7108  7108 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-06 19:16:16.190  7108  7108 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-06 19:16:16.190  7108  7108 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-06 19:16:16.190  7108  7108 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-06 19:16:16.190  7108  7108 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-06 19:16:16.190  7108  7108 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-06 19:16:16.190  7108  7108 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-06 19:16:16.190  7108  7108 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
09-06 19:16:16.190  7108  7108 I SA      : [SCU] isHaveSA() - false
09-06 19:16:16.190  7108  7108 I SA      : support phone number id : false,
09-06 19:16:16.190  7108  7108 I SA      : [DM] Supports Ref Jpn : true
09-06 19:16:16.190  7108  7108 I SA      : [DM] init END
09-06 19:16:16.190  7108  7108 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ],
,09-06 19:16:16.200  7108  7108 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-06 19:16:16.200  7108  7108 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-06 19:16:16.200  7138  7138 E Zygote  : MountEmulatedStorage()
09-06 19:16:16.200  7138  7138 I libpersona: KNOX_SDCARD checking this for 10008
09-06 19:16:16.200  7138  7138 E Zygote  : v2
09-06 19:16:16.200  7138  7138 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:16.200  1013  1466 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7138 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:16.200  7138  7138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:16.200  1013  1466 I ActivityManager: Killing 6024:com.android.mms/u0a41 (adj 15): empty #21
,09-06 19:16:16.200  7138  7138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:16.200  7138  7138 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-06 19:16:16.200  7108  7108 I SA      : [SLFUCHKMGR] constructor called
,09-06 19:16:16.210  1013  1466 D RCPManagerService: exchangeData() failure , invalid userId
09-06 19:16:16.210  1013  4116 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
09-06 19:16:16.210  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.210  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.210  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.210  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.210  1013  1478 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:16.230  7149  7149 E Zygote  : MountEmulatedStorage()
09-06 19:16:16.230  7149  7149 E Zygote  : v2
09-06 19:16:16.230  7149  7149 I libpersona: KNOX_SDCARD checking this for 10068
09-06 19:16:16.230  7149  7149 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:16.230  7149  7149 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:16.230  1013  4116 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7149 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-06 19:16:16.230  7149  7149 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:16.230  7149  7149 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-06 19:16:16.240  7108  7108 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-06 19:16:16.240  1013  1227 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-06 19:16:16.240  7108  7108 I SA      : [OR] == isSIMCardReady false ==
09-06 19:16:16.240  1013  1227 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 19:16:16.240  1013  1227 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:16.240  1013  1478 D CountryDetector: No listener is left
09-06 19:16:16.240  1013  1227 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:16.240  1013  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:16:16.240  7108  7108 I SA      : [SCU] == networkStateCheck == false
09-06 19:16:16.240  7108  7108 I SA      : [OR] onReceive END
,09-06 19:16:16.250  1013  4422 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-06 19:16:16.250  1013  4422 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.250  1013  4422 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.250  1013  4422 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.250  1013  4422 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.250  7149  7149 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:16.250  7149  7149 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:16.250  7138  7138 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:16.250  7138  7138 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:16.260  1013  1568 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:16:16.270  7171  7171 E Zygote  : MountEmulatedStorage()
09-06 19:16:16.270  7171  7171 E Zygote  : v2
09-06 19:16:16.270  7171  7171 I libpersona: KNOX_SDCARD checking this for 10110
09-06 19:16:16.270  7171  7171 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:16.270  1013  1130 D RCPManagerService: exchangeData() failure , invalid userId
09-06 19:16:16.270  7171  7171 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:16.270  7171  7171 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:16.270  7171  7171 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:16:16.270  1013  4422 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7171 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:16.280  1013  1494 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-06 19:16:16.280  1013  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 19:16:16.280  1013  1494 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:16.280  1013  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:16.280  1013  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:16:16.290  1013  4422 I ActivityManager: Killing 6601:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-06 19:16:16.290  6956  7162 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-06 19:16:16.290  1013  1477 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
09-06 19:16:16.290  1224  1224 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:16.300  7171  7171 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:16.300  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.300  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.300  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:16.300  1013  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:16.300  7171  7171 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:16.310  7186  7186 E Zygote  : MountEmulatedStorage()
09-06 19:16:16.310  7149  7149 D BadgeProvider: onCreate
,09-06 19:16:16.310  7149  7149 D BadgeProvider: DatabaseHelper
,09-06 19:16:16.310  7186  7186 E Zygote  : v2
09-06 19:16:16.310  7186  7186 I libpersona: KNOX_SDCARD checking this for 10009
09-06 19:16:16.310  7186  7186 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:16.320  7186  7186 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:16.320  7186  7186 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:16.320  1013  1477 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7186 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-06 19:16:16.320  7186  7186 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-06 19:16:16.320  1013  1477 I ActivityManager: Killing 6435:com.android.calendar/u0a131 (adj 15): empty #21
09-06 19:16:16.320  1013  1477 I ActivityManager: Killing 6618:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #22
,09-06 19:16:16.340  1013  1227 I ActivityManager: Killing 6633:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-06 19:16:16.350  7186  7186 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:16.350  7186  7186 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:16.350  7149  7168 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-06 19:16:16.370  7149  7168 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-06 19:16:16.370  7149  7168 D BadgeProvider: sendNotify, [notify] : null
09-06 19:16:16.370  7149  7168 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-06 19:16:16.370  7149  7168 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-06 19:16:16.370  7149  7168 D BadgeProvider: update, [UpdateCount] : 1
,09-06 19:16:16.380  1479  1479 D Launcher.Model: reloadBadges entered.
,09-06 19:16:16.400   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:16.410  1013  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 19:16:16.420  1013  1452 I ActivityManager: Killing 5986:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-06 19:16:16.420  2907  2907 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 19:16:16 GMT+02:00 2016
,09-06 19:16:16.420  1013  1025 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:16:16.420  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 19:16:16.420  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:16.430  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:16.430  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 19:16:16.430  2907  2907 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-06 19:16:16.430  2907  2907 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-06 19:16:16.440  2907  2907 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 19:16:16.440  2907  2907 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 19:16:16.440  2907  7203 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 19:16:16.440  2907  7203 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:16.450  2907  7203 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-06 19:16:16.450  2907  7203 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-06 19:16:16.450  2907  2907 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-06 19:16:16.470  1013  1026 I ActivityManager: Killing 5787:com.android.vending/u0a26 (adj 15): empty #21
,09-06 19:16:16.470  1013  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-06 19:16:16.470  1013  1478 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-06 19:16:16.480  1013  1569 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:16.480  1013  1569 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
09-06 19:16:16.480  1013  1569 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:16.480  1013  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:16.480  1013  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:16.480  1013  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-06 19:16:16.480  1013  1227 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-06 19:16:16.500  4757  7204 I iu.SyncManager: SYNC; picasa accounts
,09-06 19:16:16.540  1013  1130 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:16:16.550  1013  4116 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:16:16.550  1013  4116 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:16:16.550  1013  4116 D SecContentProvider2: mCursor = null
,09-06 19:16:16.550  1013  4116 D WifiService: setWifiEnabled: true pid=6690, uid=10171
,09-06 19:16:16.550  1013  4116 W ActivityManager: Permission Denial: getCurrentUser() from pid=6690, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:16.550  1013  4116 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:16:16.550  1013  4116 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6690, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:16.550  1013  4116 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:16:16.550  1013  4116 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:16:16.550  1013  4116 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:16:16.550  1013  4116 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:16:16.550  1013  4116 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:16:16.550  1013  4116 D SettingsProvider: name = wifi_on
,09-06 19:16:16.550  4757  4757 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-06 19:16:16.560  1013  1122 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 19:16:16.680   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 19:16:16.680   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:16.680  7171  7210 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:16:16.680   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:16:16.680   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:16.680  7171  7210 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 19:16:16.690   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 19:16:16.690   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:16.700  7171  7211 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:16:16.700   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:16:16.700   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:16.700  7171  7211 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 19:16:16.710  7171  7171 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 19:16:16.710  7171  7171 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 19:16:16.710  7171  7171 I GAv4    :   adb logcat -s GAv4
,09-06 19:16:16.730  7171  7171 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:16:16.730  1013  1130 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:16:16.740  7171  7171 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:16:16.750  7171  7213 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:16:16.940  1013  1040 D Tethering: interfaceAdded wlan0
,09-06 19:16:16.940  1013  1125 E Tethering: No numeric data
,09-06 19:16:16.940  1013  1119 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:16:16.950  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:16.950  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:16.950  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:16.950  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:16.950  1173  1173 D HotspotTile: updateTetherState():false, false
,09-06 19:16:16.950  1013  1119 V NetworkStats: performPollLocked() took 5ms
,09-06 19:16:16.950  1013  1125 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:16:16.950  1013  1125 D Tethering: clearTetheredNotification()
09-06 19:16:16.950  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:16.950  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:16.950  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:16.960  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:16.960  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:16.960  1013  1125 D Tethering: InitialState.processMessage what=4
09-06 19:16:16.960  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:16:16.960  1013  1125 E Tethering: No numeric data
09-06 19:16:16.960  1013  1125 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:16:16.960  1013  1125 D Tethering: clearTetheredNotification()
,09-06 19:16:16.960  1013  1119 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:16.960  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:16.960  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:16.960  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:16.960  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:16.960  1173  1173 D HotspotTile: updateTetherState():false, false
,09-06 19:16:16.970  1013  1040 D Tethering: interfaceAdded p2p0
09-06 19:16:16.970  1013  1040 D Tethering: p2p0 is not a tetherable iface, ignoring
09-06 19:16:16.970  1013  1119 V NetworkStats: performPollLocked() took 4ms
09-06 19:16:16.970  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:16.970  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:16.970  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:16.970  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:16.970  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:16.970  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:16:16.970   277  1000 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-06 19:16:16.970   277  1000 D SoftapController: Softap fwReload - Ok
,09-06 19:16:16.980   277  1000 D CommandListener: Setting iface cfg,
09-06 19:16:16.980   277  1000 D CommandListener: Trying to bring down wlan0
09-06 19:16:16.980   277  1000 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:16:16.980  1013  1122 E WifiHW  : supplicant_name : p2p_supplicant
,09-06 19:16:16.980  1013  1122 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 19:16:16.980  1013  1122 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-06 19:16:16.990  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:16.990  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-06 19:16:16.990  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:16.990  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:16.990  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:16.990  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:16.990  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:17.000  3064  3064 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:17.000  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:17.000  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-06 19:16:17.000  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:17.000  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:16:17.000  1173  1173 D HotspotTile: onReceive : 2, 0
,09-06 19:16:17.000  1013  1569 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:17.000  1013  1569 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:17.000  1013  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:17.000  1013  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-06 19:16:17.000  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:17.010  7171  7171 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-06 19:16:17.030  7171  7171 I cr.library_loader: Time to load native libraries: 4 ms (timestamps 7753-7757)
09-06 19:16:17.030  7171  7171 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:16:17.050  7171  7171 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {14347dc4},
09-06 19:16:17.050  7171  7171 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-06 19:16:17.050  7171  7171 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:16:17.060  7235  7235 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-06 19:16:17.060  7235  7235 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:16:17.060  7235  7235 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 19:16:17.080  7171  7171 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-06 19:16:17.080  7171  7171 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:16:17.080  7171  7171 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-06 19:16:17.090  7235  7235 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-06 19:16:17.090   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7235
,09-06 19:16:17.090   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-06 19:16:17.090  7235  7235 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-06 19:16:17.100  7235  7235 I wpa_supplicant: ssSupport state is = 1
09-06 19:16:17.100  7235  7235 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:16:17.100  7235  7235 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-06 19:16:17.100   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7235,
09-06 19:16:17.100   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-06 19:16:17.100  7171  7171 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-06 19:16:17.100  7171  7171 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:16:17.100  7171  7171 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:16:17.100  7171  7171 I Adreno-EGL: Local Branch: 
09-06 19:16:17.100  7171  7171 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:16:17.100  7171  7171 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:16:17.100  7171  7171 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:16:17.160  7171  7171 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:16:17.170  7171  7171 I NSApplication: Starting up...
,09-06 19:16:17.170  7171  7250 W cr.media: Requires BLUETOOTH permission
09-06 19:16:17.170  1013  1025 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:16:17.180  1013  1469 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:16:17.180  1013  1026 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-06 19:16:17.200  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:17.200  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:17.200  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:17.200  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:17.210  1013  1026 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7255 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:17.210  7255  7255 E Zygote  : MountEmulatedStorage()
09-06 19:16:17.210  7255  7255 I libpersona: KNOX_SDCARD checking this for 10117
09-06 19:16:17.210  7255  7255 E Zygote  : v2,
09-06 19:16:17.210  7255  7255 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:17.210  7255  7255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:17.220  1013  1026 I ActivityManager: Killing 6885:com.android.bluetooth/1002 (adj 15): empty #21
09-06 19:16:17.220  1013  1026 I ActivityManager: Killing 6828:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #22
09-06 19:16:17.220  7255  7255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:17.220  7255  7255 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:16:17.250  7255  7255 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:17.250  7255  7255 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:17.270  7255  7255 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:16:17.300   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-06 19:16:17.300  7235  7235 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-06 19:16:17.370  7235  7235 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:16:17.370  7235  7235 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,09-06 19:16:17.380  7235  7235 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-06 19:16:17.380   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7235
09-06 19:16:17.380   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:16:17.380  7235  7235 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,09-06 19:16:17.380  7235  7235 I wpa_supplicant: ssSupport state is = 1
,09-06 19:16:17.380  7235  7235 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:17.380  7235  7235 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 19:16:17.380  7235  7235 E wpa_supplicant: SIM READ ERROR
09-06 19:16:17.380  7235  7235 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:17.380  7235  7235 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:17.380  7235  7235 E wpa_supplicant: SIM READ ERROR
09-06 19:16:17.380  7235  7235 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:16:17.380  7235  7235 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:16:17.380  7235  7235 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-06 19:16:17.380  7235  7235 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:17.380  7235  7235 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 19:16:17.380  7235  7235 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:17.380  7235  7235 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:17.380  7235  7235 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:16:17.390  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:16:17.390  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:17.390  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:17.390   287   287 E SMD     : DCD OFF,
,09-06 19:16:17.400   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:16:17.470  7235  7235 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-06 19:16:17.630  1013  1568 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.,
,09-06 19:16:17.630  7235  7235 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-06 19:16:17.630  7235  7235 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:16:17.630  1013  1568 I ActivityManager: Killing 6846:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-06 19:16:17.640  1013  1025 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:17.640  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:17.640  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:17.640  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,09-06 19:16:17.650  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:17.650  7235  7235 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-06 19:16:17.650  1587  1587 I Hs20UtilService: Starting #11
,09-06 19:16:17.650  1587  1630 I Hs20UtilService: Message received 5011
09-06 19:16:17.650   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7235
09-06 19:16:17.650   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:16:17.650  7235  7235 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 19:16:17.650  7235  7235 I wpa_supplicant: ssSupport state is = 1
,09-06 19:16:17.650  7235  7235 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:16:17.650  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:16:17.650  7235  7235 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
09-06 19:16:17.650  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:17.650  6503  6503 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:16:17.650  6503  6503 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:17.660  1013  1359 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:17.660  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:17.660  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:17.660  1013  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:17.660  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:17.670  1587  1587 I Hs20UtilService: Starting #12
,09-06 19:16:17.670  1587  1630 I Hs20UtilService: Message received 5011
09-06 19:16:17.670  7235  7235 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-06 19:16:17.670   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7235
09-06 19:16:17.670   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:16:17.670  7235  7235 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 19:16:17.670  7235  7235 I wpa_supplicant: ssSupport state is = 1
09-06 19:16:17.670  7235  7235 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:17.670  7235  7235 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:17.670  7235  7235 E wpa_supplicant: SIM READ ERROR
09-06 19:16:17.670  7235  7235 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:16:17.670  7235  7235 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:16:17.670  7235  7235 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:16:17.670  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:17.670  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:17.670  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:16:17.670  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:17.670  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:17.670  6503  6503 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:16:17.670  6503  6503 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:17.670  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:17.670  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false,
09-06 19:16:17.670  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:17.750  7235  7235 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-06 19:16:17.750  7235  7235 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:16:17.830  7235  7235 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-06 19:16:17.830  7235  7235 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-06 19:16:17.830  7235  7235 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-06 19:16:17.960  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
,09-06 19:16:17.960  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:17.960  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:16:17.990  1013  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-06 19:16:17.990  1013  1122 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-06 19:16:17.990  7235  7235 I wpa_supplicant: HOTSPOT20_ENABLE called
09-06 19:16:17.990  7235  7235 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-06 19:16:17.990  7235  7235 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:17.990  7235  7235 E wpa_supplicant: SIM READ ERROR
,09-06 19:16:17.990  7235  7235 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:18.030  7235  7235 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-06 19:16:18.040  7235  7235 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:16:18.040  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:18.040  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:18.040  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:18.040  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:18.040  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:18.050  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:18.050  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:18.050  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-06 19:16:18.050  1013  1122 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:16:18.050  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:18.050  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:16:18.050  1173  1173 D HotspotTile: onReceive : 3, 0
,09-06 19:16:18.050  3064  3064 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:18.060  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:18.060  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:18.060  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:18.060  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:18.060  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:18.060  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:18.060  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:18.060  1013  1122 E WifiConfigStore: Not a HS20
,09-06 19:16:18.060  1013  1025 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:18.060  1013  1122 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:16:18.060  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:18.060  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:18.070  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:18.070  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:18.070  1013  1122 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-06 19:16:18.070  1013  1122 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-06 19:16:18.070  7235  7235 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 19:16:18.070  7235  7235 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:16:18.070  1587  1587 I Hs20UtilService: Starting #13
09-06 19:16:18.070  7235  7235 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:16:18.070  7235  7235 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:16:18.070  7235  7235 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:16:18.070  7235  7235 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:16:18.070  7235  7235 I wpa_supplicant: First Scan Start
09-06 19:16:18.070  7235  7235 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:16:18.070  1587  1630 I Hs20UtilService: Message received 5011
,09-06 19:16:18.080  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:16:18.080  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 19:16:18.080  1013  1122 D WifiNative-wlan0: Setting external_sim to 1
,09-06 19:16:18.080  6956  6956 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:18.080  1013  1122 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:16:18.080  1013  1122 I WifiNative-HAL: startHal
09-06 19:16:18.080  1013  1122 E wifi    : getStaticLongField sWifiHalHandle 0x9d69888c
09-06 19:16:18.080  1013  1122 I WifiNative-HAL: Could not start hal
09-06 19:16:18.080  6503  6503 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:16:18.080  6503  6503 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:18.080  1013  1122 E WifiNative-wlan0: do suspend true
,09-06 19:16:18.080  1013  1121 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 19:16:18.080   277  1000 D CommandListener: Setting iface cfg
09-06 19:16:18.080   277  1000 D CommandListener: Trying to bring up p2p0
,09-06 19:16:18.090  1013  1121 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:16:18.090  1013  1121 D WifiP2pService: P2pEnablingState
09-06 19:16:18.090  1013  1121 D WifiP2pService: P2pEnablingState{ what=147457 }
09-06 19:16:18.090  1013  1121 D WifiP2pService: P2p socket connection successful
,09-06 19:16:18.090  1013  1121 D WifiP2pService: P2pEnabledState
,09-06 19:16:18.090  1013  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-06 19:16:18.090  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 3
,09-06 19:16:18.090  1013  1145 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:18.090  1013  1145 I WifiNative-HAL: startHal
,09-06 19:16:18.090  1013  1145 E wifi    : getStaticLongField sWifiHalHandle 0x9eb569bc
09-06 19:16:18.090  1013  1145 I WifiNative-HAL: Could not start hal
09-06 19:16:18.090  1013  1145 E WifiScanningService: could not start HAL
09-06 19:16:18.100  1013  1013 D RttService: SCAN_AVAILABLE : 3
,09-06 19:16:18.100  1013  1122 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:16:18.100  1013  1122 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:16:18.100  1013  1122 E WifiNative-wlan0: invaild command id : 215
,09-06 19:16:18.100  1013  1146 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:18.100  1013  1121 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-06 19:16:18.100  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:16:18.100  1013  1124 E ConnectivityService: updateNetworkInfo()
09-06 19:16:18.100  1013  1122 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:16:18.100  1013  1122 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:16:18.100  1013  1122 E WifiNative-wlan0: invaild command id : 215
,09-06 19:16:18.100  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 19:16:18.100  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:16:18.100  1013  1043 D WifiDisplayController: disconnect
,09-06 19:16:18.100  1013  1043 D WifiDisplayController: updateConnection
09-06 19:16:18.100  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-06 19:16:18.100  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:16:18.100  7235  7235 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:16:18.100  7235  7235 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:16:18.100  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:16:18.100  7235  7235 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-06 19:16:18.100  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:16:18.100  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:16:18.110  1013  1122 E WifiStateMachine: Failed to set frequency band 0
,09-06 19:16:18.100  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:16:18.110  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:18.110  1013  1122 D SecContentProvider2: mCursor = null,
09-06 19:16:18.110  1013  1121 D WifiNative-p2p0: p2pGetDeviceAddress
09-06 19:16:18.110  1013  1121 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-06 19:16:18.110  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
09-06 19:16:18.110  1013  1026 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:16:18.110  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:16:18.110  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
09-06 19:16:18.110  3064  3064 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:16:18.110  1013  1121 D WifiP2pService: DeviceAddress: 0a:76:28
,09-06 19:16:18.110  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:16:18.110  1013  1043 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  secondary type: null
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  wps: 0
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  grpcapab: 0
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  devcapab: 0
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  status: 3
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  wfdInfo: null
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  groupownerAddress: null
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  GOdeviceName: null
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  interfaceAddress: 
09-06 19:16:18.110  1013  1043 D WifiDisplayController:  SConnectInfo : null
09-06 19:16:18.110  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:18.110  1013  1122 D SecContentProvider2: mCursor = null
,09-06 19:16:18.120  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:18.120  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:18.120  3064  3064 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:16:18.120  3064  3832 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:18.120  6926  6926 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:18.120  6926  6926 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 19:16:18.120  6926  6926 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:16:18.120  6941  6941 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:18.140  1013  1121 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 19:16:18.140  1013  1121 D WifiP2pService: InactiveState
,09-06 19:16:18.140  1013  1121 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:16:18.140  1013  1121 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:16:18.140  7235  7235 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:16:18.140  1013  1121 D WifiP2pService: InactiveState{ what=143376 },
09-06 19:16:18.140  1013  1121 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:16:18.400   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-06 19:16:19.410  7235  7235 I wpa_supplicant: nl80211: Received scan results (27 BSSes),
09-06 19:16:19.410  7235  7235 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:16:19.410  7235  7235 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-06 19:16:19.410  7235  7235 I wpa_supplicant: Trying to associate with  'G700'
,09-06 19:16:19.410  7235  7235 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
09-06 19:16:19.410  7235  7235 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-06 19:16:19.420  1013  7281 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
09-06 19:16:19.420  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:19.420  1013  1122 D SecContentProvider2: mCursor = null
,09-06 19:16:19.550  7235  7235 E wpa_supplicant: Cmd 35605 not handled
,09-06 19:16:19.550  7235  7235 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:16:19.550  7235  7235 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-06 19:16:19.550  7235  7235 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-06 19:16:19.550  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:19.550  7235  7235 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 19:16:19.550  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:19.550  7235  7235 I wpa_supplicant: Associated with F4.99.3E
09-06 19:16:19.550  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:19.550  7235  7235 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:16:19.550  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:19.550  7235  7235 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 19:16:19.550  7235  7235 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-06 19:16:19.550  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:19.550  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:19.560  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:19.560  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:19.560  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:16:19.560  1013  4422 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:16:19.560  1013  4422 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:16:19.560  1013  4422 D SecContentProvider2: mCursor = null
,09-06 19:16:19.560  1013  4422 D SettingsProvider: name = wifi_on
,09-06 19:16:19.560  1013  4422 D WifiService: setWifiEnabled: false pid=6690, uid=10171
09-06 19:16:19.560  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:19.560  1013  1122 D SecContentProvider2: mCursor = null
,09-06 19:16:19.570  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:16:19.570  1013  1040 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:16:19.570  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:19.570  1013  1122 D SecContentProvider2: mCursor = null
,09-06 19:16:19.570  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-06 19:16:19.570  1013  1125 E Tethering: No numeric data,
09-06 19:16:19.570  1013  1125 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
09-06 19:16:19.570  1013  1125 D Tethering: clearTetheredNotification()
,09-06 19:16:19.580  1013  1119 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:19.580  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:19.580  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:19.580  1173  1173 D HotspotTile: updateTetherState():false, false
,09-06 19:16:19.580  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:19.580  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:19.580  1013  1121 D WifiP2pService: InactiveState{ what=131204 }
,09-06 19:16:19.580  1013  1121 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-06 19:16:19.580  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 1
,09-06 19:16:19.590  1013  1013 D RttService: SCAN_AVAILABLE : 1
09-06 19:16:19.590  1013  1146 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:19.590  1013  1145 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:19.590  1013  1119 V NetworkStats: performPollLocked() took 11ms
09-06 19:16:19.590  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:19.590  1013  1121 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-06 19:16:19.590  1013  1124 E ConnectivityService: updateNetworkInfo()
,09-06 19:16:19.590  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:19.590  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:19.590  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:19.590  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
,09-06 19:16:19.590  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:16:19.590  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:16:19.600  1013  1124 E ConnectivityService: updateNetworkInfo()
09-06 19:16:19.600  1013  1121 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:16:19.600  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:16:19.600  1013  1121 D WifiP2pService: P2pDisablingState
,09-06 19:16:19.600  3064  3064 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:16:19.600  1013  1121 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 19:16:19.600  1013  1121 D WifiP2pService: p2p socket connection lost
09-06 19:16:19.600  1013  1121 D WifiP2pService: P2pDisabledState
,09-06 19:16:19.600  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:19.600  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:16:19.600   277  1000 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:16:19.600  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-06 19:16:19.600  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:16:19.600  1013  1043 D WifiDisplayController: disconnect
09-06 19:16:19.600  1013  1043 D WifiDisplayController: updateConnection
09-06 19:16:19.600  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-06 19:16:19.600  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:16:19.610  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:16:19.610  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:16:19.610  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:16:19.610  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:16:19.610  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:19.610  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:19.610  3064  3064 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:16:19.610  3064  3832 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:19.610  7235  7235 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:16:19.610  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-06 19:16:19.610  7235  7235 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-06 19:16:19.610  1013  1227 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:16:19.610  7235  7235 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-06 19:16:19.610  7235  7235 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
09-06 19:16:19.610  7235  7235 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:16:19.620  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:16:19.610  7235  7235 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 19:16:19.610  7235  7235 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 19:16:19.610  7235  7235 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 19:16:19.610  7235  7235 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-06 19:16:19.620  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:16:19.620  1013  1040 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:16:19.620  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:16:19.620  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:16:19.620  7235  7235 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:16:19.620  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:19.620  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:19.620  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:19.620  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:19.620  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:19.620  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:19.620  6926  6926 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:19.630  6926  6926 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 19:16:19.630  6926  6926 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:16:19.640  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:19.640  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:16:19.640  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:19.640  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:19.640  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:19.640  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:19.640  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:16:19.640  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:19.640  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-06 19:16:19.640  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:16:19.640  1173  1173 D HotspotTile: onReceive : 0, 0
09-06 19:16:19.640  3064  3064 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:19.650  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:19.650  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:19.650  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:19.650  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:19.650  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:19.650  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:19.650  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:19.650  6941  6941 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:19.660  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:16:19.660  3064  3064 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:16:19.660  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:19.660  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:16:19.660  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:19.660  3064  3064 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:16:19.660  3064  3832 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:19.670  6926  6926 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-06 19:16:19.670  6926  6926 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 19:16:19.670  6926  6926 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:16:19.670  6941  6941 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:19.680  1013  1452 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:19.680  1013  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:19.680  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:19.680  1013  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:19.680  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:19.680  1587  1587 I Hs20UtilService: Starting #14
,09-06 19:16:19.680  1587  1630 I Hs20UtilService: Message received 5007,
09-06 19:16:19.680  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:16:19.680  3064  3064 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:16:19.690  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:16:19.690  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:19.690  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-06 19:16:19.690  3064  3064 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:16:19.690  3064  3832 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:19.700  1013  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:19.700  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:19.700  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:19.700  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:19.700  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:19.710  1587  1587 I Hs20UtilService: Starting #15
,09-06 19:16:19.710  1587  1630 I Hs20UtilService: Message received 5011
,09-06 19:16:19.710  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:16:19.710  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:19.710  6503  6503 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:16:19.710  6503  6503 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:19.790  7235  7235 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:19.830  7235  7235 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-06 19:16:19.830  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
,09-06 19:16:19.830  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:16:19.830  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:16:19.850  1013  4422 I ActivityManager: Killing 6979:com.sec.pcw.device/1000 (adj 15): empty #21
,09-06 19:16:19.870  7235  7235 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-06 19:16:19.870  7235  7235 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 19:16:19.870  7235  7235 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 19:16:19.870  7235  7235 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 19:16:19.870  7235  7235 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:16:19.870  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:19.870  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:19.870  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:19.870  1013  1125 D Tethering: InitialState.processMessage what=4
,09-06 19:16:19.870  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:16:19.870  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:19.870  1013  1125 E Tethering: No numeric data
,09-06 19:16:19.870  1013  1125 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:16:19.870  1013  1125 D Tethering: clearTetheredNotification()
,09-06 19:16:19.880  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:16:19.880  1013  1119 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:19.880  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:19.880  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:19.880  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:19.880  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:16:19.880  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:16:19.880  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:16:19.880  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-06 19:16:19.880  1173  1173 D HotspotTile: updateTetherState():false, false
,09-06 19:16:19.890  1013  1119 V NetworkStats: performPollLocked() took 9ms
09-06 19:16:19.890  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:19.890  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:19.890  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:20.190  7235  7235 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:20.350  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:16:20.350  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:20.350  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:20.350  7235  7235 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 19:16:20.350  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:20.350  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:20.350  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:20.390   287   287 E SMD     : DCD OFF,
,09-06 19:16:20.460  1013  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-06 19:16:20.460  1013  1122 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:16:20.460  6956  6956 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:20.470  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:20.470  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-06 19:16:20.470  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:20.470  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:20.470  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:20.480  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:20.480  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-06 19:16:20.480  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:20.480  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-06 19:16:20.480  1173  1173 D HotspotTile: onReceive : 1, 0
,09-06 19:16:20.480  1992  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:20.480  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:16:20.490  3064  3064 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:20.490  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 19:16:20.490  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:20.490  1013  1568 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:20.490  1013  1568 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:20.490  1013  1568 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:20.490  1013  1568 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:20.490  1013  1568 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:20.500  1587  1587 I Hs20UtilService: Starting #16
09-06 19:16:20.500  1587  1630 I Hs20UtilService: Message received 5011
,09-06 19:16:20.500  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:16:20.500  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:20.500  6503  6503 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:16:20.500  6503  6503 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:21.050  1013  1040 D Tethering: interfaceRemoved wlan0
,09-06 19:16:21.050  1013  1040 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:16:21.230  1013  1040 D Tethering: interfaceRemoved p2p0
,09-06 19:16:21.230  1013  1040 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:16:21.790  1013  3354 D SSRM:n  : SIOP:: AP = 360
,09-06 19:16:22.010  1013  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 19:16:22.590  6690  6743 D BluetoothAdapter: enable()
,09-06 19:16:22.590  1013  1025 W ActivityManager: Permission Denial: getCurrentUser() from pid=6690, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:16:22.590  1013  1025 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 19:16:22.590  1013  1025 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6690, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:22.590  1013  1025 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:16:22.590  1013  1025 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-06 19:16:22.590  1013  1025 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 19:16:22.590  1013  1025 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 19:16:22.590  1013  1025 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:16:22.590  1013  1025 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:22.590  1013  1025 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:22.590  1013  1025 D SettingsProvider: name = bluetooth_on,
,09-06 19:16:22.600  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-06 19:16:22.600  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:22.600  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
09-06 19:16:22.600  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-06 19:16:22.600  1013  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:22.600  1013  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:22.600  1013  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:22.600  1013  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:22.620  1013  1042 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7290 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-06 19:16:22.620  7290  7290 E Zygote  : MountEmulatedStorage(),
09-06 19:16:22.620  7290  7290 E Zygote  : v2
09-06 19:16:22.620  7290  7290 I libpersona: KNOX_SDCARD checking this for 1002
09-06 19:16:22.620  7290  7290 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:22.620  7290  7290 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:22.630  7290  7290 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:16:22.630  7290  7290 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:16:22.650  7290  7290 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:22.660  7290  7290 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:22.680  7290  7290 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 19:16:22.680  7290  7290 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:16:22.700  7290  7290 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding GattService
,09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding HeadsetService
,09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding A2dpService
09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding HidService
,09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding HealthService
09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding PanService
,09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding SapService
09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding SapClientService
09-06 19:16:22.740  7290  7290 D BtSettings.ProfileConfig: Adding HidDevService
,09-06 19:16:22.750  7290  7290 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 19:16:22.750  1013  1469 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 19:16:22.750  1013  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.750  1013  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:22.750  1013  1469 D SettingsProvider: selectionArgs: false
09-06 19:16:22.750  1013  1469 D SettingsProvider: selectionArgs: 1002
09-06 19:16:22.750  1013  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:16:22.750  1013  1469 D SettingsProvider: ret = -1
09-06 19:16:22.750  1013  1452 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-06 19:16:22.750  1013  1452 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.750  1013  1452 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:16:22.750  1013  1452 D SettingsProvider: selectionArgs: false
09-06 19:16:22.750  1013  1452 D SettingsProvider: selectionArgs: 1002
09-06 19:16:22.750  1013  1452 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:22.750  1013  1452 D SettingsProvider: ret = -1
,09-06 19:16:22.750  1013  1494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-06 19:16:22.750  1013  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:16:22.750  1013  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:16:22.750  1013  1494 D SettingsProvider: selectionArgs: false
09-06 19:16:22.750  1013  1494 D SettingsProvider: selectionArgs: 1002
09-06 19:16:22.750  1013  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:22.750  1013  1494 D SettingsProvider: ret = -1,
,09-06 19:16:22.750  1013  1466 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-06 19:16:22.750  1013  1466 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.750  1013  1466 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:22.750  1013  1466 D SettingsProvider: selectionArgs: false
,09-06 19:16:22.750  1013  1466 D SettingsProvider: selectionArgs: 1002
09-06 19:16:22.750  1013  1466 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:22.750  1013  1466 D SettingsProvider: ret = -1
09-06 19:16:22.750  1013  4422 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-06 19:16:22.750  1013  4422 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.750  1013  4422 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-06 19:16:22.750  1013  4422 D SettingsProvider: selectionArgs: false
,09-06 19:16:22.750  1013  4422 D SettingsProvider: selectionArgs: 1002
09-06 19:16:22.750  1013  4422 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:22.750  1013  4422 D SettingsProvider: ret = -1
09-06 19:16:22.760  1013  1359 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-06 19:16:22.760  1013  1359 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.760  1013  1359 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:22.760  1013  1359 D SettingsProvider: selectionArgs: false
09-06 19:16:22.760  1013  1359 D SettingsProvider: selectionArgs: 1002
09-06 19:16:22.760  1013  1359 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:22.760  1013  1359 D SettingsProvider: ret = -1
,09-06 19:16:22.760  1013  1569 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 19:16:22.760  1013  1569 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.760  1013  1569 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:22.760  1013  1569 D SettingsProvider: selectionArgs: false
09-06 19:16:22.760  1013  1569 D SettingsProvider: selectionArgs: 1002
,09-06 19:16:22.760  1013  1569 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:22.760  1013  1569 D SettingsProvider: ret = -1
09-06 19:16:22.760  1013  1478 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-06 19:16:22.760  1013  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.760  1013  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:16:22.760  1013  1478 D SettingsProvider: selectionArgs: false
09-06 19:16:22.760  1013  1478 D SettingsProvider: selectionArgs: 1002
09-06 19:16:22.760  1013  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:22.760  1013  1478 D SettingsProvider: ret = -1
09-06 19:16:22.760  1013  1568 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:16:22.760  1013  1568 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.760  1013  1568 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:22.760  1013  1568 D SettingsProvider: selectionArgs: false
09-06 19:16:22.760  1013  1568 D SettingsProvider: selectionArgs: 1002
09-06 19:16:22.760  1013  1568 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:22.760  1013  1568 D SettingsProvider: ret = -1,
09-06 19:16:22.760  1013  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:22.760  1013  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.760  1013  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:22.760  1013  1026 D SettingsProvider: selectionArgs: false
09-06 19:16:22.760  1013  1026 D SettingsProvider: selectionArgs: 1002
,09-06 19:16:22.760  1013  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:22.760  1013  1026 D SettingsProvider: ret = -1
09-06 19:16:22.760  1013  1227 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 19:16:22.760  1013  1227 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.760  1013  1227 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:16:22.760  1013  1227 D SettingsProvider: selectionArgs: false
09-06 19:16:22.760  1013  1227 D SettingsProvider: selectionArgs: 1002
09-06 19:16:22.760  1013  1227 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:22.760  1013  1227 D SettingsProvider: ret = -1
09-06 19:16:22.760  1013  4116 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
09-06 19:16:22.760  1013  4116 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.760  1013  4116 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:22.760  1013  4116 D SettingsProvider: selectionArgs: false
09-06 19:16:22.760  1013  4116 D SettingsProvider: selectionArgs: 1002
09-06 19:16:22.760  1013  4116 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
09-06 19:16:22.760  1013  4116 D SettingsProvider: ret = -1
,09-06 19:16:22.780  7290  7290 D BluetoothAdapterState: make
,09-06 19:16:22.780  7290  7290 I bluedroid: init,
,09-06 19:16:22.780  7290  7305 I BluetoothAdapterState: Entering OffState
,09-06 19:16:22.780  7290  7290 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
09-06 19:16:22.780  7290  7290 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 19:16:22.780  7290  7290 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:16:22.780  7290  7290 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-06 19:16:22.790  7290  7290 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-06 19:16:22.790  7290  7290 I bluedroid: get_profile_interface socket
09-06 19:16:22.790  7290  7290 I bluedroid: get_profile_interface map_client
09-06 19:16:22.790  7290  7308 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-06 19:16:22.790  7290  7290 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-06 19:16:22.790  7290  7308 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-06 19:16:22.790  7290  7308 E BluetoothServiceJni: populateRssiValuesNative
,09-06 19:16:22.790  7290  7308 I bluedroid: getModelRssiValues
09-06 19:16:22.790  7290  7308 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-06 19:16:22.790  7290  7308 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:16:22.800  7290  7308 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 19:16:22.800  7290  7290 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:22.800  1013  1013 D SettingsProvider: name = bluetooth_name
,09-06 19:16:22.800  1013  1026 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:16:22.800  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:22.800  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:22.800  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:22.800  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:22.800  7290  7299 I bluedroid: config_hci_snoop_log
,09-06 19:16:22.800  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-06 19:16:22.810  1013  1042 D BluetoothManagerService: Ble is always on enable gatt
,09-06 19:16:22.810  1013  1042 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-06 19:16:22.810  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:16:22.810  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:16:22.810  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:22.810  7290  7290 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
09-06 19:16:22.810  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:22.820  1013  1042 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:16:22.820  7290  7305 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 19:16:22.820  7290  7305 D BluetoothAdapterProperties: Setting state to 11
09-06 19:16:22.820  7290  7305 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:16:22.820  7290  7305 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-06 19:16:22.820  7290  7305 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 19:16:22.820  7290  7305 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:16:22.820  7290  7305 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 19:16:22.830  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:16:22.830  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:22.830  1013  1013 I InputMethodManagerService: [BT Setting State] State =11
,09-06 19:16:22.840  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:16:22.840  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:22.840  1173  1173 D BluetoothTile:  getBluetoothState : 11
,09-06 19:16:22.840  7290  7305 D BluetoothSecureManager: getInstant: null
09-06 19:16:22.840  7290  7305 D BluetoothSecureManager: calling getMethod for getService
,09-06 19:16:22.840  7290  7305 D BluetoothSecureManager: calling getService
,09-06 19:16:22.840  7290  7305 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1ab2067a
09-06 19:16:22.840  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:16:22.840  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:16:22.840  1876  1876 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:16:22.840  1013  1478 D BluetoothSecureManagerService: isSecureModeEnabled
09-06 19:16:22.840  1013  1478 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-06 19:16:22.840  7290  7305 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:16:22.840  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:16:22.840  7290  7305 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 19:16:22.840  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:16:22.840  7290  7305 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-06 19:16:22.840  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:22.840  7290  7305 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-06 19:16:22.840  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:16:22.840  7290  7305 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-06 19:16:22.840  3064  3064 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:22.840  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 19:16:22.850  7290  7305 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-06 19:16:22.850  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 19:16:22.850  7290  7305 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 19:16:22.850  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:22.850  7290  7305 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 19:16:22.850  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:16:22.850  7290  7305 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-06 19:16:22.850  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:16:22.850  7290  7305 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:22.850  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:16:22.850  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.850  7290  7305 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:22.850  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:16:22.850  7290  7305 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:16:22.850  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 19:16:22.850  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.850  1013  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:22.850  7290  7305 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-06 19:16:22.850  1013  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 19:16:22.850  1013  1494 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:22.850  1013  1452 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:16:22.860  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:22.860  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:22.860  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:16:22.860  1013  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:22.860  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:22.860  7290  7305 D BluetoothBondStateMachine: make
,09-06 19:16:22.870  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:16:22.870  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:16:22.870  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 19:16:22.870  7290  7311 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:16:22.870  3064  3064 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:22.880  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-06 19:16:22.880  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-06 19:16:22.880  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:22.880  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:22.880  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:22.880  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:16:22.880  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:16:22.880  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:16:22.880  7290  7290 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:16:22.880  7290  7290 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:16:22.880  7290  7290 D BtGatt.GattService: start()
09-06 19:16:22.880  7290  7290 D BtGatt.GattService: start()
09-06 19:16:22.880  7290  7290 I bluedroid: get_profile_interface gatt
,09-06 19:16:22.880  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:22.880  7290  7290 D BtGatt.AdvertiseManager: advertise manager created
09-06 19:16:22.880  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:22.880  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
09-06 19:16:22.880  1013  1569 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:22.880  1013  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:16:22.890  1013  1569 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:22.890  1013  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:22.890  1013  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:22.890  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:22.890  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:16:22.890  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:22.890  1013  1478 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 19:16:22.890  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:22.890  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:22.890  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:22.890  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:22.910  7314  7314 E Zygote  : MountEmulatedStorage(),
09-06 19:16:22.910  7314  7314 I libpersona: KNOX_SDCARD checking this for 10055
09-06 19:16:22.910  7314  7314 E Zygote  : v2
09-06 19:16:22.910  7314  7314 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:22.910  7314  7314 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:22.910  7314  7314 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:22.910  1013  1478 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7314 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-06 19:16:22.910  7314  7314 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:22.920  1013  1227 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:22.920  1013  1227 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:22.920  1013  1227 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:22.920  1013  1227 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:22.920  1013  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:22.920  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:16:22.920  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:22.920  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:22.920  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:16:22.920  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:16:22.920  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:22.920  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:22.920  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:22.930  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:16:22.930  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:16:22.930   309   309 I art     : Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 20.035ms
09-06 19:16:22.930  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:16:22.930  1013  4422 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:22.930  1013  4422 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:16:22.930  1013  4422 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:22.930  1013  4422 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:22.930  1013  4422 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:22.930  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-06 19:16:22.930  7290  7290 D BtGatt.GattService: mStartError = false
09-06 19:16:22.930  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:22.930  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:16:22.940  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-06 19:16:22.940  1013  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:22.940  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-06 19:16:22.940  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:22.940  1013  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:22.940  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:22.940  7290  7290 D HeadsetService: Received start request. Starting profile...
09-06 19:16:22.940  7290  7290 D HeadsetService: start()
,09-06 19:16:22.940  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:16:22.940  1013  1466 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:22.940  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:22.940  1013  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-06 19:16:22.940  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-06 19:16:22.940  7290  7290 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:16:22.940  7290  7290 D HeadsetStateMachine: make
09-06 19:16:22.940  1013  1466 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:22.940  1013  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:22.940  1013  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:22.940  7290  7290 E HeadsetStateMachine: # of Max HF connection is 2
09-06 19:16:22.940  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:16:22.940  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
09-06 19:16:22.940  7290  7305 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-06 19:16:22.940   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.521ms
09-06 19:16:22.940  1013  1569 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:22.940  1013  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:22.950  1013  1569 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:22.950  1013  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:22.950  1013  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:22.950  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:22.950  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:22.950  7290  7305 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:22.950  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:22.950  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:22.950  7290  7305 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:22.950  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:16:22.950  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:16:22.950  7290  7305 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:16:22.950  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:16:22.950  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:16:22.950  7290  7305 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:16:22.950  7290  7305 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 19:16:22.950  1013  1026 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-06 19:16:22.950  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:22.950  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-06 19:16:22.950  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:22.950  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-06 19:16:22.960  7314  7314 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:22.960  7314  7314 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:22.960   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.671ms
,09-06 19:16:22.960  1013  1478 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 19:16:22.960  1013  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-06 19:16:22.960  1013  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:22.960  1013  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:22.960  1013  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-06 19:16:22.960  7290  7290 I bluedroid: get_profile_interface handsfree
,09-06 19:16:22.980  7290  7290 I DualScoManager: Instantiating Dual Sco Manager
09-06 19:16:22.980  7290  7290 I DualScoManager: Set HeadsetServiceHelper
,09-06 19:16:22.980  7314  7314 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-06 19:16:22.980  7290  7290 D BluetoothAtMessage: createCMTIContentObservers
09-06 19:16:22.980  1013  1469 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-06 19:16:22.980  1013  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:22.980  1013  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:22.980  1013  1469 D SettingsProvider: selectionArgs: false
09-06 19:16:22.980  1013  1469 D SettingsProvider: selectionArgs: 1002
09-06 19:16:22.980  1013  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:22.980  1013  1469 D SettingsProvider: ret = -1
,09-06 19:16:22.980  7290  7329 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 19:16:22.990  7290  7290 D HeadsetService: mStartError = false
09-06 19:16:22.990  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:22.990  7290  7290 D A2dpService: Received start request. Starting profile...
09-06 19:16:22.990  7290  7290 D A2dpService: start()
,09-06 19:16:22.990  7290  7290 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:16:22.990  7290  7290 I bluedroid: get_profile_interface avrcp
09-06 19:16:22.990  7290  7329 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 19:16:22.990  7290  7329 D HeadsetStateMachine: map size, before remove : 0
09-06 19:16:22.990  7290  7329 D HeadsetStateMachine: map size, after remove: 0
,09-06 19:16:23.000  7290  7290 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 19:16:23.000  7290  7290 D Avrcp   : Initialize Media Controller
09-06 19:16:23.000  7290  7290 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 19:16:23.000  7290  7290 E Avrcp   : getActiveSessions
,09-06 19:16:23.000  7290  7290 D Avrcp   : pick active media Controller
09-06 19:16:23.000  7290  7290 D Avrcp   : Get the active Media Controller 
,09-06 19:16:23.020  7290  7290 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 19:16:23.020  7290  7334 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
09-06 19:16:23.020  7290  7290 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:16:23.020  7290  7290 D A2dpStateMachine: make
,09-06 19:16:23.020  7290  7290 I bluedroid: get_profile_interface a2dp
,09-06 19:16:23.020  7290  7336 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 19:16:23.020  7314  7314 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-06 19:16:23.020  7290  7290 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 19:16:23.020  7314  7314 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-06 19:16:23.020  7314  7314 D UserAnalysis: Create SecureDbHelper
,09-06 19:16:23.020  7290  7290 D A2dpService: mStartError = false
09-06 19:16:23.020  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:23.030  7290  7335 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:16:23.030  7290  7290 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:16:23.030  7290  7290 D HidService: Received start request. Starting profile...
,09-06 19:16:23.030  7290  7290 D HidService: start()
09-06 19:16:23.030  7290  7290 I bluedroid: get_profile_interface hidhost
09-06 19:16:23.030  7290  7290 D HidService: setHidService(): set to: null
,09-06 19:16:23.030  7290  7290 D HidService: mStartError = false
09-06 19:16:23.030  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:23.030  7290  7290 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 19:16:23.030  7290  7290 D HealthService: Received start request. Starting profile...
,09-06 19:16:23.030  7290  7290 D HealthService: start()
,09-06 19:16:23.030  7290  7290 I bluedroid: get_profile_interface health
,09-06 19:16:23.030  7290  7290 D HealthService: mStartError = false
09-06 19:16:23.030  7314  7314 D IntelligenceServiceApplication: onCreate()
,09-06 19:16:23.030  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
09-06 19:16:23.030  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
09-06 19:16:23.030  7290  7290 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:16:23.040  7290  7334 D BluetoothMediaBrowser: no now playing list
09-06 19:16:23.040  7290  7334 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 19:16:23.040  7290  7290 D PanService: Received start request. Starting profile...
09-06 19:16:23.040  7290  7290 D PanService: start()
09-06 19:16:23.040  7290  7290 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:16:23.040  7290  7290 I bluedroid: get_profile_interface pan
,09-06 19:16:23.040  7290  7290 D PanService: mStartError = false
09-06 19:16:23.040  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:23.040  1013  1568 I ActivityManager: Killing 6997:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,09-06 19:16:23.040  7290  7290 D BluetoothMapService: Received start request. Starting profile...
09-06 19:16:23.040  7290  7290 D BluetoothMapService: start()
,09-06 19:16:23.040  7290  7290 D BluetoothMapService: mStartError = false
09-06 19:16:23.040  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:23.040  7314  7314 D IntelligenceServiceApplication: no applications having user consent for prediction
09-06 19:16:23.040  7290  7290 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-06 19:16:23.050  7290  7290 D SapService: Received start request. Starting profile...
,09-06 19:16:23.050  7290  7290 D SapService: start()
09-06 19:16:23.050  7290  7290 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 19:16:23.050  7290  7290 I bluedroid: get_profile_interface sap
09-06 19:16:23.050  7290  7290 D SapService: mStartError = false
09-06 19:16:23.050  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:23.050  7290  7290 D HeadsetStateMachine: Try to query the phonestate on bind
09-06 19:16:23.050  1013  1569 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-06 19:16:23.050  7314  7314 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-06 19:16:23.050  1427  1438 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 19:16:23.050  7290  7290 D HeadsetStateMachine: Proxy object connected
09-06 19:16:23.050  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-06 19:16:23.050  7290  7290 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-06 19:16:23.050  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-06 19:16:23.050  7290  7290 D HeadsetPhoneState: sendDeviceDataStateChanged
09-06 19:16:23.050  1427  1438 I Telecom : BluetoothPhoneService: Result of Message : true
09-06 19:16:23.050  7290  7290 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-06 19:16:23.050  7290  7290 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:16:23.050  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 19:16:23.050  7290  7290 D BluetoothA2dp: Proxy object connected
09-06 19:16:23.050  7290  7290 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-06 19:16:23.050  7290  7329 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:16:23.050  7290  7329 D HeadsetStateMachine: Disconnected process message: 18
09-06 19:16:23.050  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 19:16:23.050  7290  7329 D HeadsetStateMachine: Disconnected process message: 10
09-06 19:16:23.050  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 19:16:23.050  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-06 19:16:23.050  7290  7329 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:16:23.050  7290  7329 D HeadsetStateMachine: Disconnected process message: 11
,09-06 19:16:23.060  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:16:23.060  7314  7314 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 19:16:23.060  1013  1478 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 19:16:23.060  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:23.060  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:23.060  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:23.060  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:23.080  7341  7341 E Zygote  : MountEmulatedStorage()
09-06 19:16:23.080  7341  7341 E Zygote  : v2
09-06 19:16:23.080  7341  7341 I libpersona: KNOX_SDCARD checking this for 10105
09-06 19:16:23.080  7341  7341 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:23.080  7341  7341 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:23.080  1013  1478 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7341 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-06 19:16:23.090  7341  7341 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:23.090  7341  7341 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:16:23.110  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-06 19:16:23.110  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 19:16:23.120  7290  7305 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:16:23.120  7290  7305 I bluedroid: enable
,09-06 19:16:23.120  7290  7305 I bt_hci_bdroid: init
09-06 19:16:23.120  7341  7341 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:23.120  7341  7341 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:23.120  7290  7356 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-06 19:16:23.120  7290  7305 I bt_vendor: bt-vendor : init
,09-06 19:16:23.120  7290  7305 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:16:23.120  7290  7305 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:16:23.120  7290  7305 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-06 19:16:23.120  7290  7305 D bt_userial_mct: userial_init
,09-06 19:16:23.130  7290  7305 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:16:23.130  7290  7305 I bt_vendor: Starting hciattach daemon
09-06 19:16:23.130  7290  7305 I bt_vendor: try to set false
,09-06 19:16:23.130  7290  7305 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:16:23.130  7290  7305 I bt_vendor: Starting hciattach daemon
09-06 19:16:23.130  7290  7305 I bt_vendor: try to set true
,09-06 19:16:23.150  7360  7360 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-06 19:16:23.210  7366  7366 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-06 19:16:23.230  7367  7367 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 19:16:23.250  7369  7369 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:16:23.260  7370  7370 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-06 19:16:23.270  7373  7373 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:16:23.280  7374  7374 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-06 19:16:23.330   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:16:23.330   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:23.330  7341  7377 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:16:23.330   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:16:23.330   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:23.330  7341  7377 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:16:23.400   287   287 E SMD     : DCD OFF
,09-06 19:16:23.470  7341  7341 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:16:23.470  7341  7341 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:23.470  7341  7341 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:23.470  7341  7341 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:23.470  7341  7341 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.k.d(PG:583)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:23.470  7341  7341 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:23.470  7341  7341 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:23.480  1013  4422 I ActivityManager: Killing 7008:com.sec.android.soagent/u0a31 (adj 15): empty #21
09-06 19:16:23.470  7341  7341 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:16:23.470  7341  7341 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:16:23.480  1992  1992 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 19:16:23.480  1992  1992 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:16:23.530  7389  7389 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
09-06 19:16:23.540  7390  7390 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:16:23.560  7341  7384 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:16:23.590  7290  7305 I bt_vendor: bluetooth satus is on
,09-06 19:16:23.590  7290  7358 D bt_userial_mct: userial_open(port:0)
09-06 19:16:23.590  7290  7358 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 19:16:23.590  7290  7358 I bt_vendor: Done intiailizing UART
,09-06 19:16:23.590  7290  7358 I bt_vendor: Done intiailizing UART
,09-06 19:16:23.590  7290  7358 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-06 19:16:23.590  7290  7358 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-06 19:16:23.600  7290  7393 D bt_userial_mct: Entering userial_read_thread()
,09-06 19:16:23.730  1013  1469 I art     : Explicit concurrent mark sweep GC freed 66440(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.450ms total 146.218ms
,09-06 19:16:23.730  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_SAP
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 19:16:23.730  7290  7356 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
09-06 19:16:23.730  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:23.730  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:23.730  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-06 19:16:23.820  7290  7356 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 19:16:23.830  7290  7356 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa418ded1 
,09-06 19:16:23.830  7290  7356 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa418ded1 
,09-06 19:16:23.840  7290  7308 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-06 19:16:23.850  7290  7308 E bt-btif : Calling BTA_HhEnable
,09-06 19:16:23.850  7290  7308 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 19:16:23.850  7290  7308 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-06 19:16:23.850  7290  7308 E BluetoothServiceJni: populateRssiValuesNative
,09-06 19:16:23.850  7290  7308 I bluedroid: getModelRssiValues
09-06 19:16:23.850  7290  7308 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-06 19:16:23.850  7290  7308 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:16:23.860  7290  7308 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
09-06 19:16:23.860  1013  1013 D SettingsProvider: name = bluetooth_name
,09-06 19:16:23.860  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:23.870  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:23.870  7290  7308 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:16:23.870  7290  7308 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:16:23.870  7290  7308 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:16:23.870  7290  7308 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
09-06 19:16:23.870  7290  7308 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-06 19:16:23.870  7290  7308 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-06 19:16:23.870  7290  7308 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-06 19:16:23.870  7290  7308 E bt-btif : btif_sock_init: !vhci_init
,09-06 19:16:23.870  7290  7308 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-06 19:16:23.870  7290  7393 E bt_mct  : hci lib postload completed,
,09-06 19:16:23.870  7290  7308 D IOP_DB_BT: db_open: db_open : handle 3023687696l, read 13894 bytes onto local cache,
09-06 19:16:23.870  7290  7308 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-06 19:16:23.870  7290  7308 D IOP_DB_BT: db_query: result 1,
09-06 19:16:23.870  7290  7308 I         : iop_db_open: iop_db_open status 0
,09-06 19:16:23.880  7290  7308 D bte_conf: Device ID record 1 : primary
,09-06 19:16:23.880  7290  7308 D bte_conf:   vendorId            = 0075
09-06 19:16:23.880  7290  7308 D bte_conf:   vendorIdSource      = 0001
,09-06 19:16:23.880  7290  7308 D bte_conf:   product             = 0100
,09-06 19:16:23.880  7290  7308 D bte_conf:   version             = 0200
,09-06 19:16:23.880  7290  7308 D bte_conf:   clientExecutableURL = 
09-06 19:16:23.880  7290  7308 D bte_conf:   serviceDescription  = 
,09-06 19:16:23.880  7290  7308 D bte_conf:   documentationURL    = 
,09-06 19:16:23.880  7290  7308 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:16:23.880  7290  7305 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 19:16:23.880  7290  7308 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:16:23.880  7290  7305 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:16:23.880  7290  7305 D BluetoothAdapterProperties: State =  11
,09-06 19:16:23.890  1013  1568 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:16:23.890  7290  7305 D BluetoothAdapterProperties: Setting state to 12
09-06 19:16:23.890  7290  7305 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:16:23.900  7290  7308 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:16:23.900  7290  7308 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:16:23.900  7290  7308 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:16:23.900  1013  1477 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-06 19:16:23.900  1013  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:23.900  1013  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:23.900  1013  1477 D SettingsProvider: selectionArgs: false
09-06 19:16:23.900  1013  1477 D SettingsProvider: selectionArgs: 1002
09-06 19:16:23.900  1013  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:23.900  1013  1477 D SettingsProvider: ret = -1
,09-06 19:16:23.900  7290  7305 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:23.900  7290  7305 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 19:16:23.900  1013  4422 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:23.900  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:23.900  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:23.900  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:23.900  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:23.900  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:23.900  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:23.900  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:23.900  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:23.900  1013  4422 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.900  1013  4422 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.900  1013  4422 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:23.900  1013  4422 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.910  7290  7305 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:16:23.910  7290  7305 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,09-06 19:16:23.910  7290  7305 D BluetoothAdapterService: starting service from this receiver
,09-06 19:16:23.910  1013  1130 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:23.910  1013  1130 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.910  1013  1130 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.910  1013  1130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:23.910  1013  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.920  3064  3075 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:16:23.920  7290  7305 I BluetoothAdapterState: Entering On State from state = 11
09-06 19:16:23.920  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:23.920  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-06 19:16:23.920  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.930  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:23.930  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:23.930  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:23.930  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:23.930  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:23.930  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:23.930  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:23.930  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:23.930  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:23.930  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.930  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.930  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.930  7290  7298 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:16:23.930  1992  2003 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:23.930  1992  2003 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:23.940  1427  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:16:23.940  7290  7290 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-06 19:16:23.940  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:23.940  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:16:23.940  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:23.940  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.940  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.940  1427  1442 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:23.940  3064  3072 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:16:23.950  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-06 19:16:23.950  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.950  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.950  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:23.950  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.950  7290  7290 I BluetoothPbapService: Handler(): got msg=1
,09-06 19:16:23.960  3064  3075 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 19:16:23.960  3064  3075 D Bluetoothsap: Binding service...
,09-06 19:16:23.960  1013  1130 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:16:23.960  3064  3064 D BluetoothMap: Proxy object connected
09-06 19:16:23.960  3064  3064 D MapProfile: Bluetooth service connected
09-06 19:16:23.960  3064  3064 D BluetoothMap: getConnectedDevices()
,09-06 19:16:23.970  3064  3075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:16:23.970  3064  3064 D BluetoothPbap: Proxy object connected
09-06 19:16:23.970  3064  3064 D PbapServerProfile: Bluetooth service connected
,09-06 19:16:23.970  7290  7399 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 19:16:23.970  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-06 19:16:23.970  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.970  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.970  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.970  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.970  3064  3064 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-06 19:16:23.970  3064  3064 D SapProfile: Bluetooth service connected
09-06 19:16:23.970  3064  3064 D Bluetoothsap: getConnectedDevices()
,09-06 19:16:23.980  3064  3075 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:16:23.980  3064  7398 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:16:23.980  7290  7399 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:16:23.980  7290  7399 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:23.980  3064  7398 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:23.980  7290  7399 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-06 19:16:23.980  7290  7399 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:16:23.980  7290  7399 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:16:23.980  7290  7399 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@14efc77e
,09-06 19:16:23.980  7290  7399 D BluetoothSocket: channel: 19
09-06 19:16:23.980  7290  7399 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-06 19:16:23.980  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 19:16:23.980  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.980  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.980  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.980  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.980  3064  3064 D BluetoothA2dp: Proxy object connected
09-06 19:16:23.980  3064  3064 D A2dpProfile: Bluetooth service connected
,09-06 19:16:23.980  1427  3281 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:23.980  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:23.980  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:23.990  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.990  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:23.990  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:23.990  1427  3281 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:23.990  1436  1451 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:23.990  1436  1451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:23.990  3064  3072 D BluetoothPan: Binding service...
,09-06 19:16:23.990  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-06 19:16:23.990  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:23.990  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:23.990  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:23.990  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:24.000  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:16:24.000  3064  3064 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:16:24.000  3064  3064 D PanProfile: Bluetooth service connected
09-06 19:16:24.000  1013  1042 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 19:16:24.000  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 19:16:24.000  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 19:16:24.000  1013  1013 D BluetoothA2dp: Proxy object connected
,09-06 19:16:24.000  7290  7299 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:24.000  7290  7299 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:24.000  1427  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:24.000  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:24.000  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:24.000  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:24.000  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:24.000  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:24.000  1427  1442 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:16:24.000  6690  6698 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:24.000  6690  6698 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:24.000  3064  3072 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:24.000  3064  3072 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:24.000  1013  1042 D BluetoothPan: Binding service...
09-06 19:16:24.000  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:16:24.000  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:24.000  1013  1042 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:16:24.000  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:16:24.000  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:16:24.000  1013  1042 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:16:24.010  1427  1438 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:24.010  1427  1438 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:24.010  1013  1013 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:16:24.010  1173  1783 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:24.010  1173  1783 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:24.010  3064  7398 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:24.010  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:16:24.010  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:24.010  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:16:24.010  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:24.010  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:24.010  3064  7398 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:24.010  3064  3064 D HeadsetProfile: Bluetooth service connected
09-06 19:16:24.010  1459  1824 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:24.010  1459  1824 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:24.010  3064  3072 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:16:24.010  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-06 19:16:24.010  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:16:24.010  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:24.010  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:24.010  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:24.020  7341  7349 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:24.020  7341  7349 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:24.020  1459  4117 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:24.020  3064  3064 D BluetoothInputDevice: Proxy object connected
09-06 19:16:24.020  1013  1042 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:24.020  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:24.020  3064  3064 D HidProfile: Bluetooth service connected
,09-06 19:16:24.020  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:24.020  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:24.020  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:24.020  1459  4117 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:16:24.020  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:24.020  1013  1042 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:24.020  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:16:24.020  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
09-06 19:16:24.020  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:24.020  1013  1013 I InputMethodManagerService: [BT Setting State] State =12
09-06 19:16:24.020  1013  1013 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:16:24.030  1427  1427 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@284e49da, true,
09-06 19:16:24.030  1173  1173 D BluetoothTile:  onBluetoothStateChange:
09-06 19:16:24.030  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:24.030  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:16:24.030  1173  1173 D BluetoothTile:  getBluetoothState : 12
09-06 19:16:24.040  1427  1427 D BluetoothHeadset: registerMessageListener
,09-06 19:16:24.040  1013  1494 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 19:16:24.040  1876  1876 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:16:24.040  3064  3064 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:24.040  1013  1469 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 19:16:24.040  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
09-06 19:16:24.040  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:24.040  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:24.050  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:24.050  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:16:24.050  1013  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:24.050  1013  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:16:24.050  1013  1478 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:16:24.050  1013  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:24.050  1013  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:24.050  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:24.050  7290  7298 D HeadsetService: registerMessageListener,
09-06 19:16:24.050  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 19:16:24.050  7290  7298 D HeadsetService: registerMessageListener
09-06 19:16:24.050  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-06 19:16:24.050  7290  7329 D HeadsetStateMachine: Disconnected process message: 70
09-06 19:16:24.050  7290  7329 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@25484df
,09-06 19:16:24.060  7290  7401 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-06 19:16:24.060  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1,
09-06 19:16:24.060  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-06 19:16:24.060  3064  3064 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-06 19:16:24.060  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-06 19:16:24.060  3064  3064 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.,
09-06 19:16:24.060  3064  3064 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 19:16:24.060  3064  3064 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
09-06 19:16:24.060  7290  7329 D HeadsetStateMachine: Disconnected process message: 9
09-06 19:16:24.060  7290  7329 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 19:16:24.060  7290  7401 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:16:24.060  7290  7401 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:24.060  7290  7401 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-06 19:16:24.060  7290  7401 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:16:24.060  7290  7401 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:16:24.060  7290  7401 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21f2b52c
09-06 19:16:24.060  7290  7401 D BluetoothSocket: channel: 5
,09-06 19:16:24.070   282  1011 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-06 19:16:24.070   282  1011 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 19:16:24.070   282  1011 V voice   : voice_set_parameters: exit with code(-2)
09-06 19:16:24.070   282  1011 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,09-06 19:16:24.070   282  1011 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 19:16:24.070   282  1011 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:16:24.070   282  1011 V audio_hw_primary: adev_set_parameters: exit
09-06 19:16:24.070  7290  7329 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 19:16:24.080  3064  3064 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:16:24.080  1013  4422 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:16:24.080  1013  4422 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:16:24.080  1013  4422 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:24.080  1013  4422 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:24.080  1013  4422 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:16:24.090  3064  3064 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:24.090  3064  3064 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:24.090  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:24.090  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:16:24.100  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:24.100  7290  7290 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:16:24.110  1013  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:24.110  1013  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:16:24.110  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:24.110  1013  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:24.110  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:24.120  1992  1992 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:24.120  1013  1469 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:24.120  1013  1469 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:16:24.130  1013  1469 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:24.130  1013  1469 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:24.130  1013  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:24.140  1992  7407 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:16:24.140  1992  1992 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:16:24.140  1013  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:24.150  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:24.150  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:24.150  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:24.160  1013  1494 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:16:24.170  1013  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:24.170  1013  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:24.170  1013  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:24.170  1013  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:24.180  7290  7411 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 19:16:24.180  7290  7411 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:24.180  7290  7411 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-06 19:16:24.180  7290  7411 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:16:24.180  7290  7411 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:16:24.180  7290  7411 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38934856
09-06 19:16:24.180  7290  7411 D BluetoothSocket: channel: 12
09-06 19:16:24.180  7290  7411 I BtOppRfcommListener: Accept thread started.
,09-06 19:16:24.180  1992  7407 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 19:16:25.600  6690  6743 D BluetoothAdapter: disable()
,09-06 19:16:25.610  1013  1478 D SettingsProvider: name = bluetooth_on
,09-06 19:16:25.620  7290  7305 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
09-06 19:16:25.620  7290  7305 D BluetoothAdapterProperties: Setting state to 13
09-06 19:16:25.620  7290  7305 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:16:25.620  7290  7305 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:25.620  7290  7305 D BluetoothAdapterService: updateAdapterState state is 13,
,09-06 19:16:25.620  1013  1452 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:25.620  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:25.620  1013  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:16:25.620  1013  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:25.620  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-06 19:16:25.620  7290  7290 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-06 19:16:25.620  7290  7290 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3f4430d7, channel: 19, state: LISTENING
,09-06 19:16:25.620  7290  7290 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3f4430d7, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@14efc77e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14347dc4mSocket: android.net.LocalSocket@224374ad impl:android.net.LocalSocketImpl@f1393e2 fd:FileDescriptor[74]
09-06 19:16:25.620  7290  7290 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@224374ad impl:android.net.LocalSocketImpl@f1393e2 fd:FileDescriptor[74]
09-06 19:16:25.630  7290  7305 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:16:25.630  7290  7305 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:16:25.630  7290  7305 D BluetoothAdapterService: terminating service from this receiver
,09-06 19:16:25.630  1173  1173 D BluetoothTile:  onBluetoothStateChange:
09-06 19:16:25.630  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:25.630  1013  1013 I InputMethodManagerService: [BT Setting State] State =13
,09-06 19:16:25.640  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:16:25.640  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:25.640  1173  1173 D BluetoothTile:  getBluetoothState : 13
09-06 19:16:25.640  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:25.640  1876  1876 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:16:25.640  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:25.650  1013  1469 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:25.650  3064  3064 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:25.650  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:16:25.650  1013  1569 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:16:25.650  1013  1569 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:16:25.650  1013  1569 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-06 19:16:25.650  1013  1569 D BatteryService: stay LED for fully charged
09-06 19:16:25.650  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:16:25.660  1013  1466 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:16:25.660  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:16:25.660  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:25.660  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:25.660  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:25.660  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:25.660  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:25.660  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:25.660  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:25.660  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:25.660  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:25.660  1013  1130 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:16:25.660  1013  1130 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:25.660  1013  1130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:25.660  1013  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:25.660  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:25.660  1013  1359 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:25.660  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:16:25.670  7290  7305 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:16:25.670  7290  7305 D BluetoothAdapterProperties: mDiscovering is false
09-06 19:16:25.670  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:25.670  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:25.670  1013  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:25.670  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:25.670  1013  1469 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:16:25.670  7290  7305 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 19:16:25.670  3064  3064 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:16:25.670  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:25.670  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:25.670  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:25.670  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:25.670  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:25.670  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:25.670  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:25.670  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:25.670  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:25.670  6690  6690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:16:25.670  1013  1013 I MotionRecognitionService: Plugged
09-06 19:16:25.670  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
09-06 19:16:25.670  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:25.680  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-06 19:16:25.680  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 19:16:25.680  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:16:25.680  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:16:25.690  1013  1469 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:16:25.690  1013  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:16:25.700  1013  1469 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:25.700  1013  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:25.700  1013  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:16:25.700  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:25.700  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:25.700  7290  7308 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:16:25.700  7290  7308 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:16:25.700  7290  7305 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true,
09-06 19:16:25.700  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:16:25.700  7290  7305 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-06 19:16:25.700  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:16:25.700  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:16:25.710  7290  7305 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-06 19:16:25.700  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-06 19:16:25.710  7290  7305 E bt-btif : cmd socket is ]: id 57
,09-06 19:16:25.700  1173  1173 D SViewCoverView: level :100 plugged : 2
09-06 19:16:25.710  7290  7411 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:25.710  7290  7305 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:16:25.710  7290  7356 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-06 19:16:25.710  7290  7356 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 19:16:25.710  7290  7356 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:25.710  7290  7356 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:25.710  7290  7356 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:16:25.710  3064  3064 D BluetoothPbap: Proxy object disconnected
09-06 19:16:25.710  3064  3064 D PbapServerProfile: Bluetooth service disconnected
,09-06 19:16:25.710  3064  3064 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:25.720  3064  3064 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:25.720  7290  7290 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@25310373, channel: 5, state: LISTENING
,09-06 19:16:25.720  7290  7290 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@25310373, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21f2b52c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22ddb230mSocket: android.net.LocalSocket@25cfaea9 impl:android.net.LocalSocketImpl@205b0c2e fd:FileDescriptor[76]
09-06 19:16:25.720  7290  7290 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@25cfaea9 impl:android.net.LocalSocketImpl@205b0c2e fd:FileDescriptor[76]
,09-06 19:16:25.720  7290  7290 I BtOppRfcommListener: stopping Accept Thread
09-06 19:16:25.720  7290  7290 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e0e63cf, channel: 12, state: LISTENING
,09-06 19:16:25.720  7290  7290 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e0e63cf, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38934856, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2fa3c15cmSocket: android.net.LocalSocket@16cb8c65 impl:android.net.LocalSocketImpl@348fbd3a fd:FileDescriptor[80]
09-06 19:16:25.720  7290  7290 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@16cb8c65 impl:android.net.LocalSocketImpl@348fbd3a fd:FileDescriptor[80]
,09-06 19:16:25.730  7290  7411 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:16:25.730  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:25.730  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:16:25.730  7290  7290 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:16:25.730  7290  7329 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:16:25.730  7290  7290 V BluetoothOppManager: cleanUp...
,09-06 19:16:25.760  1992  1992 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:25.760  1992  1992 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:16:25.910  7290  7356 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 19:16:25.910  7290  7356 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:25.910  7290  7356 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:25.910  7290  7356 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:25.910  7290  7356 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:25.910  7290  7356 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:25.910  7290  7356 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:25.910  7290  7356 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:25.910  7290  7356 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:25.910  7290  7356 W bt-btif : ag scb idx 1 not allocated
09-06 19:16:25.910  7290  7356 W bt-btif : ag scb idx 2 not allocated
09-06 19:16:25.910  7290  7356 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:16:25.910  7290  7393 I bt_userial_mct: exiting userial_read_thread
09-06 19:16:25.910  7290  7393 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:16:25.910  7290  7308 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:16:25.910  7290  7358 I bt_vendor: hw_epilog_process
09-06 19:16:25.910  7290  7308 D bt_userial_mct: userial_close
09-06 19:16:25.910  7290  7308 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 19:16:26.300  7290  7308 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-06 19:16:26.300  7290  7308 I bt_vendor: bluetooth satus is on
09-06 19:16:26.300  7290  7308 I bt_vendor: bt-vendor : resetting BT status
09-06 19:16:26.300  7290  7308 I bt_vendor: Starting hciattach daemon
09-06 19:16:26.300  7290  7308 I bt_vendor: try to set false
,09-06 19:16:26.300  7290  7308 I bt_vendor: Starting hciattach daemon
,09-06 19:16:26.300  7290  7308 I bt_vendor: try to set false
09-06 19:16:26.300  7290  7308 I bt_vendor: cleanup
09-06 19:16:26.300  7290  7356 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
09-06 19:16:26.300  7290  7308 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:16:26.300  1013  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:26.300  7290  7308 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:16:26.300  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-06 19:16:26.300  7290  7305 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:16:26.300  7290  7305 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:16:26.300  7290  7305 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-06 19:16:26.300  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:16:26.300  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:16:26.300  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-06 19:16:26.300  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:26.300  1013  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.300  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:26.310  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:16:26.310  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:16:26.310  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:16:26.310  7290  7290 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:16:26.310  1013  1466 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:26.310  7290  7290 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:16:26.310  1013  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.310  7290  7290 D BtGatt.GattService: stop()
09-06 19:16:26.310  7290  7290 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:16:26.310  1013  1466 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:26.310  1013  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,09-06 19:16:26.310  1013  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:26.310  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:16:26.310  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
09-06 19:16:26.310  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:16:26.310  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:26.320  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:26.320  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.320  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.320  7290  7290 D HeadsetService: Received stop request...Stopping profile...
09-06 19:16:26.320  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.320  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:16:26.320  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-06 19:16:26.320  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:26.320  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:16:26.320  1013  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:26.320  1013  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:16:26.320  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:26.320  1013  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:26.320  1013  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.320  1013  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.320  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-06 19:16:26.330  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService,
09-06 19:16:26.330  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:16:26.330  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-06 19:16:26.330  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:26.330  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.330  3064  3064 D HeadsetProfile: Bluetooth service disconnected
,09-06 19:16:26.330  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.330  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.330  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.330  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-06 19:16:26.330  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:16:26.330  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService,
,09-06 19:16:26.330  1013  1569 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:26.330  1013  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.340  1013  1569 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.340  1013  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:26.340  1013  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.340  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:26.340  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:26.340  7290  7305 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:26.340  1013  1130 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:26.340  1013  1130 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-06 19:16:26.340  1013  1130 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:26.340  1013  1130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:26.340  1013  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.340  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-06 19:16:26.350  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:16:26.350  7290  7305 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:16:26.350  1013  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:26.350  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.350  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:26.350  1013  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:26.350  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:26.350  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:26.350  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:16:26.350  7290  7305 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:26.350  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:26.350  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:26.350  7290  7305 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:26.350  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:16:26.350  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:16:26.350  7290  7305 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:16:26.350  7290  7305 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:16:26.350  7290  7305 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:16:26.350  7290  7305 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:16:26.350  7290  7305 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:16:26.350  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-06 19:16:26.350  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 19:16:26.350  7290  7290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:26.350  7290  7290 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 19:16:26.350  7290  7290 D A2dpService: Received stop request...Stopping profile...
,09-06 19:16:26.350  7290  7335 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:16:26.350  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:26.360  1013  1013 D BluetoothA2dp: Proxy object disconnected
,09-06 19:16:26.360  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-06 19:16:26.360  7290  7290 D HidService: Received stop request...Stopping profile...
09-06 19:16:26.360  7290  7290 D HidService: Stopping Bluetooth HidService
09-06 19:16:26.360  7290  7290 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:16:26.360  7290  7290 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 19:16:26.360  7290  7290 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:16:26.360  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:26.360  3064  3064 D BluetoothA2dp: Proxy object disconnected
09-06 19:16:26.360  3064  3064 D A2dpProfile: Bluetooth service disconnected
,09-06 19:16:26.360  3064  3064 D BluetoothInputDevice: Proxy object disconnected
,09-06 19:16:26.360  3064  3064 D HidProfile: Bluetooth service disconnected
09-06 19:16:26.360  7290  7290 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:16:26.360  7290  7290 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:16:26.360  7290  7290 D HealthService: Received stop request...Stopping profile...
,09-06 19:16:26.360  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:26.360  7290  7290 D PanService: Received stop request...Stopping profile...
,09-06 19:16:26.370  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:26.370  1013  1013 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:16:26.370  7290  7290 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 19:16:26.370  3064  3064 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:16:26.370  3064  3064 D PanProfile: Bluetooth service disconnected
,09-06 19:16:26.370  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:26.370  7290  7290 D SapService: Received stop request...Stopping profile...
09-06 19:16:26.370  7290  7290 D SapService: Stopping Bluetooth SapService
09-06 19:16:26.370  7290  7290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8882d04
,09-06 19:16:26.370  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 19:16:26.370  7290  7290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:26.370  7290  7290 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:16:26.370  7290  7290 D BluetoothA2dp: Proxy object disconnected
09-06 19:16:26.370  7290  7290 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-06 19:16:26.380  7290  7336 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-06 19:16:26.380  7290  7290 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:16:26.380  7290  7290 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:16:26.380  3064  3064 D BluetoothMap: Proxy object disconnected
09-06 19:16:26.380  3064  3064 D MapProfile: Bluetooth service disconnected
09-06 19:16:26.380  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 19:16:26.380  7290  7290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:26.380  7290  7290 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:26.380  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 19:16:26.380  7290  7290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:26.380  3064  3064 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:16:26.380  7290  7290 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:26.380  7290  7290 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:16:26.380  7290  7290 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-06 19:16:26.380  3064  3064 D SapProfile: Bluetooth service disconnected
09-06 19:16:26.380  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 19:16:26.380  7290  7290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:26.380  7290  7290 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:26.380  7290  7290 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:16:26.380  7290  7290 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:16:26.380  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-06 19:16:26.380  7290  7290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:16:26.380  7290  7290 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-06 19:16:26.380  7290  7290 E BluetoothAdapterService(143142148): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-06 19:16:26.380  7290  7305 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-06 19:16:26.380  7290  7305 D BluetoothAdapterProperties: Setting state to 10
,09-06 19:16:26.380  7290  7305 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:16:26.380  7290  7305 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:26.380  7290  7305 D BluetoothAdapterService: updateAdapterState state is 10
,09-06 19:16:26.380  7290  7305 D BluetoothAdapterService: Autoconnection is available 
09-06 19:16:26.380  7290  7305 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 19:16:26.380  7290  7305 I BluetoothAdapterState: Entering OffState
,09-06 19:16:26.390  7290  7290 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:16:26.390  7290  7290 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-06 19:16:26.390  3064  3072 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 19:16:26.390  7290  7299 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:16:26.390  1992  2158 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.390  1992  2158 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.390  3064  7398 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:16:26.390  3064  3075 D Bluetoothsap: onBluetoothStateChange: up=false
,09-06 19:16:26.390  3064  3075 D Bluetoothsap: Unbinding service...
,09-06 19:16:26.390  3064  3072 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:16:26.390  1436  1451 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.390  1436  1451 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.400  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:16:26.400  7290  7310 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.400  7290  7310 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.400   287   287 E SMD     : DCD OFF
,09-06 19:16:26.400  6690  6698 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:26.400  6690  6698 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:16:26.400  6690  6698 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-06 19:16:26.400  6690  6698 D BluetoothLeAdvertiser: Exit stop advertising
09-06 19:16:26.400  6690  6698 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 19:16:26.400  6690  6698 D BluetoothLeScanner: Exiting stopAllScan
09-06 19:16:26.400  3064  3075 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.400  3064  3075 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.400  1427  6870 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:26.400  1427  6870 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.400  1173  1784 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.400  1173  1784 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.400  1459  1470 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.400  1459  1470 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.410  3064  7398 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:16:26.410  7341  7351 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:16:26.410  7341  7351 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.410  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:16:26.410  1013  1042 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:16:26.410  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-06 19:16:26.410  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:16:26.420  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:26.420  1013  1013 I InputMethodManagerService: [BT Setting State] State =10
,09-06 19:16:26.420  1013  1013 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:16:26.430  1173  1173 D BluetoothAdapter: 1008569655: getState() :  mService = null. Returning STATE_OFF
,09-06 19:16:26.430  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:16:26.430  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:26.430  1173  1713 D BluetoothAdapter: 1008569655: getState() :  mService = null. Returning STATE_OFF
,09-06 19:16:26.430  1173  1173 D BluetoothTile:  getBluetoothState : 10
09-06 19:16:26.430  1173  1173 D BluetoothAdapter: 1008569655: getState() :  mService = null. Returning STATE_OFF
09-06 19:16:26.430  1173  1173 D BluetoothAdapter: 1008569655: getState() :  mService = null. Returning STATE_OFF
,09-06 19:16:26.430  1013  1227 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:26.430  1013  1569 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:16:26.430  1876  1876 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:16:26.430  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:16:26.430  1173  1713 D BluetoothAdapter: 1008569655: getState() :  mService = null. Returning STATE_OFF
,09-06 19:16:26.430  1992  2161 D BluetoothAdapter: 211007839: getState() :  mService = null. Returning STATE_OFF
09-06 19:16:26.430  1992  2161 D BluetoothAdapter: 211007839: getState() :  mService = null. Returning STATE_OFF
,09-06 19:16:26.440  3064  3064 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:26.440  7290  7308 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-06 19:16:26.440  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:26.440  7290  7290 I GKI_LINUX: GKI_exit_task 1 done
,09-06 19:16:26.440  7290  7290 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:16:26.440  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:26.440  7290  7290 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 19:16:26.440  1013  1025 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:26.440  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.440  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.440  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:26.440  3064  3064 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:16:26.440  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:26.440  7290  7290 I art     : System.exit called, status: 0
09-06 19:16:26.440  7290  7290 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:16:26.450  1013  1569 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:16:26.450  1013  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.450  1013  1569 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:26.450  1013  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:26.450  1013  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:16:26.450  1013  1045 I PowerManagerService: [PWL] Off : 75s ago
09-06 19:16:26.450  1013  1045 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-06 19:16:26.450  1013  1045 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-06 19:16:26.450  1013  1045 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1013, ws=null) (elapsedTime=11989)
09-06 19:16:26.450  1013  1045 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2382)
09-06 19:16:26.450  1013  1045 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2381)
09-06 19:16:26.450  1013  1045 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'StartingDockService' (uid=1000, pid=3064, ws=null) (elapsedTime=9)
,09-06 19:16:26.470  3064  3064 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:26.470  3064  3064 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:26.470  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:26.470  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 19:16:26.480  1013  1452 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 19:16:26.480  1013  1452 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 19:16:26.490  1013  1452 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-06 19:16:26.490  1013  1452 W BroadcastQueue: android.os.TransactionTooLargeException
09-06 19:16:26.490  1013  1452 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:16:26.490  1013  1452 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:16:26.490  1013  1452 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-06 19:16:26.490  1013  1452 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-06 19:16:26.490  1013  1452 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-06 19:16:26.490  1013  1452 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-06 19:16:26.490  1013  1452 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-06 19:16:26.490  1013  1452 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-06 19:16:26.490  1013  1452 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:16:26.490  1013  1452 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-06 19:16:26.490  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:26.490  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:26.490  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:26.490  1013  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:26.500  7428  7428 E Zygote  : MountEmulatedStorage()
,09-06 19:16:26.500  7428  7428 E Zygote  : v2
,09-06 19:16:26.500  7428  7428 I libpersona: KNOX_SDCARD checking this for 1002
09-06 19:16:26.500  7428  7428 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:26.500  7428  7428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:26.500  1013  1452 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7428 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-06 19:16:26.510  7428  7428 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:26.510  7428  7428 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:26.520  7428  7428 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-06 19:16:26.530  7428  7428 D ActivityThread: Added TimaKeyStore provider,
,09-06 19:16:26.540  7428  7428 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 19:16:26.540  7428  7428 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:16:26.560  7428  7428 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding GattService
,09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding HeadsetService
09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding A2dpService
,09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding HidService
09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding HealthService
09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding PanService
09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding SapService
09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding SapClientService
,09-06 19:16:26.590  7428  7428 D BtSettings.ProfileConfig: Adding HidDevService
09-06 19:16:26.590  7428  7428 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 19:16:26.590  1013  1025 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 19:16:26.600  1013  1025 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:26.600  1013  1025 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.600  1013  1025 D SettingsProvider: selectionArgs: false
09-06 19:16:26.600  1013  1025 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.600  1013  1025 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:26.600  1013  1025 D SettingsProvider: ret = -1
09-06 19:16:26.600  1013  1469 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-06 19:16:26.600  1013  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:26.600  1013  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.600  1013  1469 D SettingsProvider: selectionArgs: false
09-06 19:16:26.600  1013  1469 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.600  1013  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:26.600  1013  1469 D SettingsProvider: ret = -1
,09-06 19:16:26.600  1013  4422 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:26.600  1013  4422 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:26.600  1013  4422 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.600  1013  4422 D SettingsProvider: selectionArgs: false
09-06 19:16:26.600  1013  4422 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.600  1013  4422 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:26.600  1013  4422 D SettingsProvider: ret = -1
,09-06 19:16:26.600  1013  4116 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-06 19:16:26.600  1013  4116 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:26.600  1013  4116 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.600  1013  4116 D SettingsProvider: selectionArgs: false
09-06 19:16:26.600  1013  4116 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.600  1013  4116 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:26.600  1013  4116 D SettingsProvider: ret = -1
09-06 19:16:26.600  1013  1568 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-06 19:16:26.600  1013  1568 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:26.600  1013  1568 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.600  1013  1568 D SettingsProvider: selectionArgs: false
09-06 19:16:26.600  1013  1568 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.600  1013  1568 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:26.600  1013  1568 D SettingsProvider: ret = -1
,09-06 19:16:26.600  1013  1466 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-06 19:16:26.600  1013  1466 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:26.600  1013  1466 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.600  1013  1466 D SettingsProvider: selectionArgs: false
09-06 19:16:26.600  1013  1466 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.600  1013  1466 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:26.600  1013  1466 D SettingsProvider: ret = -1
,09-06 19:16:26.600  1013  1359 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 19:16:26.600  1013  1359 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:26.600  1013  1359 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.600  1013  1359 D SettingsProvider: selectionArgs: false
09-06 19:16:26.600  1013  1359 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.600  1013  1359 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:26.600  1013  1359 D SettingsProvider: ret = -1
,09-06 19:16:26.600  1013  1026 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-06 19:16:26.600  1013  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:26.600  1013  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.600  1013  1026 D SettingsProvider: selectionArgs: false
09-06 19:16:26.600  1013  1026 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.600  1013  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:26.600  1013  1026 D SettingsProvider: ret = -1
,09-06 19:16:26.600  1013  1130 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:26.600  1013  1130 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:26.600  1013  1130 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.600  1013  1130 D SettingsProvider: selectionArgs: false
09-06 19:16:26.600  1013  1130 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.600  1013  1130 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:26.600  1013  1130 D SettingsProvider: ret = -1
,09-06 19:16:26.600  1013  1227 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:16:26.600  1013  1227 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:26.600  1013  1227 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.600  1013  1227 D SettingsProvider: selectionArgs: false
,09-06 19:16:26.600  1013  1227 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.600  1013  1227 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:16:26.600  1013  1227 D SettingsProvider: ret = -1
,09-06 19:16:26.610  1013  1569 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 19:16:26.610  1013  1569 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:26.610  1013  1569 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.610  1013  1569 D SettingsProvider: selectionArgs: false
09-06 19:16:26.610  1013  1569 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.610  1013  1569 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:26.610  1013  1569 D SettingsProvider: ret = -1
,09-06 19:16:26.610  1013  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-06 19:16:26.610  1013  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:16:26.610  1013  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:26.610  1013  1478 D SettingsProvider: selectionArgs: false
09-06 19:16:26.610  1013  1478 D SettingsProvider: selectionArgs: 1002
09-06 19:16:26.610  1013  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:26.610  1013  1478 D SettingsProvider: ret = -1
,09-06 19:16:26.620  1992  1992 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:26.620  1013  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:26.620  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:16:26.620  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:26.620  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:26.620  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:26.630  1992  7444 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:16:26.630  1992  1992 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:16:26.640  1013  1227 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:26.640  1013  1227 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:26.640  1013  1227 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:16:26.640  1013  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:26.650  1992  7444 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-06 19:16:27.710  1013  1302 E Watchdog: !@Sync 4
,09-06 19:16:28.400   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:16:28.620  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:16:28.620  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:29.410   287   287 E SMD     : DCD OFF,
09-06 19:16:29.410   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:30.400   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:16:31.400   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:16:31.620  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:31.620  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb40939 added. We now have 6 listener(s)
,09-06 19:16:31.620  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:31.620  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:31.620  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e8d7b7e added. We now have 7 listener(s)
,09-06 19:16:31.620  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:31.630  6690  6743 I System.out: IsBluetoothEnabled
,09-06 19:16:31.630  6690  6743 D BluetoothAdapter: disable()
,09-06 19:16:31.630  1013  1026 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-06 19:16:31.630  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:31.630  6690  6743 D BluetoothAdapter: enable()
,09-06 19:16:31.640  1013  1227 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-06 19:16:31.640  1013  1227 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6690, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:31.640  1013  1227 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:16:31.640  1013  1227 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-06 19:16:31.640  1013  1227 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 19:16:31.640  1013  1227 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 19:16:31.640  1013  1227 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:16:31.640  1013  1227 W ActivityManager: Permission Denial: getCurrentUser() from pid=6690, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:31.640  1013  1227 D SettingsProvider: name = bluetooth_on
09-06 19:16:31.640  1013  1227 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:16:31.640  1013  1227 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:31.650  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-06 19:16:31.650  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:31.650  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-06 19:16:31.650  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-06 19:16:31.680  7428  7428 D BluetoothAdapterState: make
,09-06 19:16:31.690  7428  7428 I bluedroid: init
09-06 19:16:31.690  7428  7450 I BluetoothAdapterState: Entering OffState
,09-06 19:16:31.690  7428  7428 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 19:16:31.690  7428  7428 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:16:31.690  7428  7428 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:16:31.690  7428  7428 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-06 19:16:31.690  7428  7428 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-06 19:16:31.690  7428  7428 I bluedroid: get_profile_interface socket
09-06 19:16:31.690  7428  7428 I bluedroid: get_profile_interface map_client
09-06 19:16:31.690  7428  7453 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-06 19:16:31.700  7428  7428 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,09-06 19:16:31.700  7428  7453 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-06 19:16:31.700  7428  7453 E BluetoothServiceJni: populateRssiValuesNative
,09-06 19:16:31.700  7428  7453 I bluedroid: getModelRssiValues
09-06 19:16:31.700  7428  7453 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:16:31.700  7428  7453 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:16:31.700  7428  7453 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 19:16:31.700  1013  1013 D SettingsProvider: name = bluetooth_name
,09-06 19:16:31.710  7428  7428 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:31.710  1013  1478 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 19:16:31.710  1013  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:31.710  1013  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:31.710  1013  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:31.710  1013  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:31.720  7428  7437 I bluedroid: config_hci_snoop_log
,09-06 19:16:31.720  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 19:16:31.720  1013  1042 D BluetoothManagerService: Ble is always on enable gatt
,09-06 19:16:31.720  1013  1042 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-06 19:16:31.720  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-06 19:16:31.730  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:16:31.730  7428  7428 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-06 19:16:31.740  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:31.740  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:16:31.740  1013  1042 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:16:31.740  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:16:31.740  7428  7450 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 19:16:31.740  7428  7450 D BluetoothAdapterProperties: Setting state to 11
09-06 19:16:31.740  7428  7450 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:16:31.740  7428  7450 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:31.740  7428  7450 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 19:16:31.740  7428  7450 D BluetoothAdapterService: Autoconnection is available 
09-06 19:16:31.740  7428  7450 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 19:16:31.750  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:31.750  1013  1013 I InputMethodManagerService: [BT Setting State] State =11
,09-06 19:16:31.750  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:16:31.750  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:31.750  1173  1173 D BluetoothTile:  getBluetoothState : 11
,09-06 19:16:31.760  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:16:31.760  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:16:31.760  1013  1569 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:31.760  1013  1494 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:16:31.760  7428  7450 D BluetoothSecureManager: getInstant: null
09-06 19:16:31.760  7428  7450 D BluetoothSecureManager: calling getMethod for getService
09-06 19:16:31.760  7428  7450 D BluetoothSecureManager: calling getService
,09-06 19:16:31.760  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 19:16:31.760  1876  1876 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:16:31.760  7428  7450 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2bfa2288
,09-06 19:16:31.760  1013  1227 D BluetoothSecureManagerService: isSecureModeEnabled
09-06 19:16:31.760  1013  1227 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-06 19:16:31.760  7428  7450 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:16:31.760  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:16:31.760  3064  3064 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:31.760  7428  7450 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 19:16:31.760  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:16:31.760  7428  7450 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,09-06 19:16:31.760  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:16:31.770  7428  7450 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-06 19:16:31.770  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:16:31.770  1013  4422 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:31.770  1013  4422 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 19:16:31.770  7428  7450 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-06 19:16:31.770  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:16:31.770  1013  4422 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:31.770  1013  4422 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:31.770  1013  4422 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:16:31.770  7428  7450 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-06 19:16:31.770  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:16:31.770  7428  7450 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 19:16:31.770  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:31.770  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:31.770  7428  7450 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 19:16:31.770  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:16:31.770  7428  7450 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-06 19:16:31.770  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:16:31.770  7428  7450 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:31.770  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:16:31.770  7428  7450 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:31.770  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:16:31.780  7428  7450 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:16:31.780  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:16:31.780  3064  3064 D BluetoothNotiBroadcastReceiver: onReceive
09-06 19:16:31.780  7428  7450 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-06 19:16:31.780  7428  7450 D BluetoothBondStateMachine: make
,09-06 19:16:31.780  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:16:31.780  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:16:31.780  7428  7450 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 19:16:31.780  7428  7455 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:16:31.780  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:31.780  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 19:16:31.790  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:31.790  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 19:16:31.790  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:31.790  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:31.790  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:31.790  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
09-06 19:16:31.790  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:16:31.790  7428  7450 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 19:16:31.790  7428  7428 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:16:31.790  7428  7428 D BtGatt.GattService: Received start request. Starting profile...
,09-06 19:16:31.790  7428  7428 D BtGatt.GattService: start()
09-06 19:16:31.790  7428  7428 D BtGatt.GattService: start()
09-06 19:16:31.790  7428  7428 I bluedroid: get_profile_interface gatt
,09-06 19:16:31.790  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@352f522
09-06 19:16:31.790  7428  7428 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:16:31.800  1013  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:31.800  1013  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:16:31.800  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:31.800  1013  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:31.800  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:31.800  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:31.800  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:31.800  7428  7450 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:16:31.800  1013  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:31.800  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:31.800  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:31.800  1013  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:31.800  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:31.800  7428  7428 D BtGatt.GattService: mStartError = false
09-06 19:16:31.800  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@352f522
,09-06 19:16:31.810  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-06 19:16:31.810  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:16:31.810  7428  7450 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:16:31.810  7428  7428 D HeadsetService: Received start request. Starting profile...
09-06 19:16:31.810  7428  7428 D HeadsetService: start()
,09-06 19:16:31.810  7428  7428 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 19:16:31.810  7428  7428 D HeadsetStateMachine: make
,09-06 19:16:31.810  1013  1569 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:31.810  1013  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:16:31.810  7428  7428 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 19:16:31.820  1013  1569 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:31.820  1013  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:31.820  1013  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:31.820  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-06 19:16:31.820  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:16:31.820  7428  7450 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:16:31.820  1013  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:31.820  1013  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:16:31.820  1013  1469 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:31.820  1013  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:31.820  1013  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:31.820  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 19:16:31.820  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:16:31.820  1013  1469 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-06 19:16:31.820  7428  7450 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-06 19:16:31.820  1013  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 19:16:31.820  1013  1469 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:31.820  1013  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:31.820  1013  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:16:31.830  1013  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:31.830  1013  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:31.830  1013  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:31.830  1013  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:31.830  1013  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:31.830  1013  3354 D SSRM:n  : SIOP:: AP = 330
,09-06 19:16:31.830  1013  1359 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-06 19:16:31.830  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:16:31.830  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:16:31.830  7428  7450 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:16:31.830  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 19:16:31.830  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:31.830  1013  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:31.830  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:16:31.830  1013  1227 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:31.830  1013  1227 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:16:31.830  7428  7428 I bluedroid: get_profile_interface handsfree
,09-06 19:16:31.830  1013  1227 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:31.830  1013  1227 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:31.830  1013  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:31.840  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-06 19:16:31.840  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:16:31.840  7428  7450 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:16:31.840  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:31.840  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:31.840  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:31.840  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:31.840  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:31.850  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:16:31.850  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:31.850  7428  7450 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:16:31.850  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:31.850  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:31.850  7428  7450 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:16:31.850  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:16:31.850  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:16:31.850  7428  7450 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:16:31.850  7428  7450 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:16:31.850  7428  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:16:31.850  7428  7450 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:16:31.850  7428  7450 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 19:16:31.850  7428  7428 I DualScoManager: Instantiating Dual Sco Manager
09-06 19:16:31.850  7428  7428 I DualScoManager: Set HeadsetServiceHelper
09-06 19:16:31.850  7428  7428 D BluetoothAtMessage: createCMTIContentObservers
,09-06 19:16:31.860  1013  1466 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-06 19:16:31.860  1013  1466 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:31.860  1013  1466 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:31.860  1013  1466 D SettingsProvider: selectionArgs: false
09-06 19:16:31.860  1013  1466 D SettingsProvider: selectionArgs: 1002
,09-06 19:16:31.860  1013  1466 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:31.860  1013  1466 D SettingsProvider: ret = -1
,09-06 19:16:31.860  7428  7458 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 19:16:31.860  7428  7428 D HeadsetService: mStartError = false
,09-06 19:16:31.860  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@352f522
09-06 19:16:31.860  7428  7428 E BluetoothAdapterService(55768354): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
09-06 19:16:31.860  7428  7458 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 19:16:31.860  7428  7458 D HeadsetStateMachine: map size, before remove : 0
09-06 19:16:31.860  7428  7458 D HeadsetStateMachine: map size, after remove: 0
,09-06 19:16:31.860  7428  7428 D A2dpService: Received start request. Starting profile...
09-06 19:16:31.860  7428  7428 D A2dpService: start()
,09-06 19:16:31.870  7428  7428 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 19:16:31.870  7428  7428 I bluedroid: get_profile_interface avrcp
,09-06 19:16:31.870  7428  7428 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:16:31.870  7428  7428 D Avrcp   : Initialize Media Controller
,09-06 19:16:31.870  7428  7428 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 19:16:31.870  7428  7428 E Avrcp   : getActiveSessions
,09-06 19:16:31.870  7428  7428 D Avrcp   : pick active media Controller
09-06 19:16:31.870  7428  7428 D Avrcp   : Get the active Media Controller 
,09-06 19:16:31.890  7428  7428 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 19:16:31.890  7428  7462 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-06 19:16:31.890  7428  7428 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:16:31.890  7428  7428 D A2dpStateMachine: make
,09-06 19:16:31.900  7428  7428 I bluedroid: get_profile_interface a2dp
,09-06 19:16:31.900  7428  7464 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 19:16:31.900  7428  7428 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 19:16:31.900  1013  3383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-06 19:16:31.900  7428  7462 D BluetoothMediaBrowser: no now playing list
09-06 19:16:31.900  7428  7462 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 19:16:31.900  7428  7428 D A2dpService: mStartError = false
09-06 19:16:31.900  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@352f522
09-06 19:16:31.900  7428  7463 D A2dpStateMachine: Enter Disconnected: -2,
09-06 19:16:31.900  7428  7428 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:16:31.900  7428  7428 D HidService: Received start request. Starting profile...
09-06 19:16:31.900  7428  7428 D HidService: start()
09-06 19:16:31.900  7428  7428 I bluedroid: get_profile_interface hidhost
09-06 19:16:31.900  7428  7428 D HidService: setHidService(): set to: null
09-06 19:16:31.900  7428  7428 D HidService: mStartError = false
09-06 19:16:31.900  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@352f522
,09-06 19:16:31.910  7428  7428 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 19:16:31.910  7428  7428 D HealthService: Received start request. Starting profile...
09-06 19:16:31.910  7428  7428 D HealthService: start()
,09-06 19:16:31.910  7428  7428 I bluedroid: get_profile_interface health
,09-06 19:16:31.910  7428  7428 D HealthService: mStartError = false
09-06 19:16:31.910  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@352f522
,09-06 19:16:31.910  7428  7428 D HeadsetStateMachine: Try to query the phonestate on bind,
09-06 19:16:31.910  1427  6870 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 19:16:31.910  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-06 19:16:31.910  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:16:31.910  1427  6870 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 19:16:31.910  7428  7428 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:16:31.920  7428  7428 D PanService: Received start request. Starting profile...
09-06 19:16:31.920  7428  7428 D PanService: start()
09-06 19:16:31.920  7428  7428 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:16:31.920  7428  7428 I bluedroid: get_profile_interface pan
,09-06 19:16:31.920  7428  7428 D PanService: mStartError = false
09-06 19:16:31.920  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@352f522
,09-06 19:16:31.920  7428  7428 D HeadsetStateMachine: Proxy object connected
,09-06 19:16:31.920  7428  7428 D BluetoothMapService: Received start request. Starting profile...,
09-06 19:16:31.920  7428  7428 D BluetoothMapService: start()
,09-06 19:16:31.930  7428  7428 D BluetoothMapService: mStartError = false
09-06 19:16:31.930  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@352f522
,09-06 19:16:31.930  7428  7428 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-06 19:16:31.930  7428  7428 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-06 19:16:31.930  7428  7458 D HeadsetStateMachine: Disconnected process message: 11
,09-06 19:16:31.930  7428  7428 D SapService: Received start request. Starting profile...
09-06 19:16:31.930  7428  7428 D SapService: start()
09-06 19:16:31.930  7428  7428 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 19:16:31.930  7428  7428 I bluedroid: get_profile_interface sap
09-06 19:16:31.930  7428  7428 D SapService: mStartError = false
09-06 19:16:31.930  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@352f522
09-06 19:16:31.930  7428  7428 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-06 19:16:31.930  7428  7428 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-06 19:16:31.930  7428  7428 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:16:31.930  1992  1992 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 19:16:31.930  7428  7428 E BluetoothAdapterService(55768354): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 19:16:31.930  7428  7428 D BluetoothA2dp: Proxy object connected
09-06 19:16:31.930  7428  7428 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-06 19:16:31.930  7428  7458 D HeadsetStateMachine: Disconnected process message: 18
,09-06 19:16:31.930  7428  7458 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:16:31.930  7428  7458 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-06 19:16:31.930  7428  7458 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:16:31.930  7428  7428 E BluetoothAdapterService(55768354): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 19:16:31.930  7428  7428 E BluetoothAdapterService(55768354): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 19:16:31.930  7428  7428 E BluetoothAdapterService(55768354): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-06 19:16:31.930  7428  7428 E BluetoothAdapterService(55768354): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:16:31.940  1992  1992 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:16:31.960  7428  7428 E BluetoothAdapterService(55768354): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-06 19:16:31.960  7428  7428 E BluetoothAdapterService(55768354): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 19:16:31.960  7428  7450 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:16:31.960  7428  7450 I bluedroid: enable
,09-06 19:16:31.960  7428  7450 I bt_hci_bdroid: init
,09-06 19:16:31.970  7428  7469 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-06 19:16:31.970  7428  7450 I bt_vendor: bt-vendor : init
,09-06 19:16:31.970  7428  7450 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:16:31.970  7428  7450 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:16:31.970  7428  7450 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-06 19:16:31.970  7428  7450 D bt_userial_mct: userial_init
09-06 19:16:31.970  7428  7450 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:16:31.970  7428  7450 I bt_vendor: Starting hciattach daemon
09-06 19:16:31.970  7428  7450 I bt_vendor: try to set false
,09-06 19:16:31.970  7428  7450 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
09-06 19:16:31.970  7428  7450 I bt_vendor: Starting hciattach daemon
,09-06 19:16:31.970  7428  7450 I bt_vendor: try to set true
,09-06 19:16:31.990  7473  7473 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-06 19:16:32.040  7479  7479 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-06 19:16:32.040  7480  7480 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 19:16:32.060  7482  7482 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:16:32.070  7483  7483 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-06 19:16:32.080  7484  7484 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:16:32.080  7485  7485 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-06 19:16:32.170  1013  2081 V SAMP_SPCM_test: CSC File load.. 
,09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-06 19:16:32.180  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-06 19:16:32.220  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize,
09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
,09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm,
09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
,09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-06 19:16:32.230  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,09-06 19:16:32.240  1013  2081 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-06 19:16:32.240  1013  2081 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-06 19:16:32.240  1013  2081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-06 19:16:32.240  1013  2081 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
,09-06 19:16:32.240  1013  2081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-06 19:16:32.240  1013  2081 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-06 19:16:32.260  7488  7488 E Zygote  : MountEmulatedStorage(),
09-06 19:16:32.260  1013  2081 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7488 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:16:32.260  7488  7488 E Zygote  : v2
09-06 19:16:32.260  7488  7488 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:32.260  7488  7488 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:32.270  7488  7488 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:32.270  7488  7488 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:16:32.280  7488  7488 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:32.300  7488  7488 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:32.310  7488  7488 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:32.330  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,09-06 19:16:32.330  7488  7488 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,09-06 19:16:32.340  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:16:32.380  7428  7450 I bt_vendor: bluetooth satus is on
09-06 19:16:32.380  7428  7471 D bt_userial_mct: userial_open(port:0)
09-06 19:16:32.380  7428  7471 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,09-06 19:16:32.380  7428  7471 I bt_vendor: Done intiailizing UART
,09-06 19:16:32.380  7428  7471 I bt_vendor: Done intiailizing UART
,09-06 19:16:32.380  7428  7471 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 19:16:32.380  7428  7471 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 19:16:32.390  7428  7506 D bt_userial_mct: Entering userial_read_thread()
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_SAP
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 19:16:32.390  7428  7469 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-06 19:16:32.400  1013  2081 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-06 19:16:32.400  1013  1013 I ActivityManager: Killing 7022:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-06 19:16:32.400   287   287 E SMD     : DCD OFF
,09-06 19:16:32.400   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:16:32.480  7428  7469 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 19:16:32.490  7428  7469 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa418ded1 
,09-06 19:16:32.490  7428  7469 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa418ded1 
,09-06 19:16:32.500  7428  7453 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-06 19:16:32.510  7428  7453 E bt-btif : AG evt (hdl 0x00010
,09-06 19:16:32.510  7428  7453 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
09-06 19:16:32.510  7428  7453 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
09-06 19:16:32.510  7428  7453 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:16:32.510  7428  7453 I bluedroid: getModelRssiValues
09-06 19:16:32.510  7428  7453 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:16:32.510  7428  7453 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:16:32.510  1013  1013 D SettingsProvider: name = bluetooth_name
,09-06 19:16:32.510  7428  7453 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 19:16:32.520  7428  7453 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:16:32.520  7428  7453 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:16:32.520  7428  7453 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:16:32.520  7428  7453 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
09-06 19:16:32.520  7428  7453 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-06 19:16:32.520  7428  7453 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-06 19:16:32.520  7428  7453 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-06 19:16:32.520  7428  7453 E bt-btif : btif_sock_init: !vhci_init,
09-06 19:16:32.520  7428  7453 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db,
09-06 19:16:32.530  7428  7453 D IOP_DB_BT: db_open: db_open : handle 3028152336l, read 13894 bytes onto local cache
09-06 19:16:32.530  7428  7453 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-06 19:16:32.530  7428  7453 D IOP_DB_BT: db_query: result 1
,09-06 19:16:32.530  7428  7453 I         : iop_db_open: iop_db_open status 0
09-06 19:16:32.530  7428  7453 D bte_conf: Device ID record 1 : primary
09-06 19:16:32.530  7428  7453 D bte_conf:   vendorId            = 0075
,09-06 19:16:32.530  7428  7453 D bte_conf:   vendorIdSource      = 0001
09-06 19:16:32.530  7428  7453 D bte_conf:   product             = 0100
09-06 19:16:32.530  7428  7453 D bte_conf:   version             = 0200
,09-06 19:16:32.530  7428  7453 D bte_conf:   clientExecutableURL = 
09-06 19:16:32.530  7428  7453 D bte_conf:   serviceDescription  = 
,09-06 19:16:32.530  7428  7453 D bte_conf:   documentationURL    = 
09-06 19:16:32.530  7428  7453 D bte_conf: bte_load_did_conf no section named DID2.
09-06 19:16:32.530  7428  7453 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:16:32.530  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:32.530  7428  7450 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:16:32.530  7428  7450 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:16:32.530  7428  7450 D BluetoothAdapterProperties: State =  11
,09-06 19:16:32.530  1013  4422 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:16:32.530  7428  7506 E bt_mct  : hci lib postload completed
09-06 19:16:32.530  7428  7450 D BluetoothAdapterProperties: Setting state to 12
09-06 19:16:32.530  7428  7450 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:16:32.540  7428  7453 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 19:16:32.540  7428  7453 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:16:32.540  7428  7453 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:16:32.540  1013  1026 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-06 19:16:32.540  1013  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:32.540  1013  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:32.540  1013  1026 D SettingsProvider: selectionArgs: false
09-06 19:16:32.540  1013  1026 D SettingsProvider: selectionArgs: 1002
09-06 19:16:32.540  1013  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:32.540  1013  1026 D SettingsProvider: ret = -1
,09-06 19:16:32.540  7428  7450 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:16:32.540  7428  7450 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 19:16:32.540  1013  1569 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:32.540  1013  1569 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.540  1013  1569 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.540  1013  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:32.540  1013  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.550  7428  7450 D BluetoothAdapterService: Autoconnection is available 
09-06 19:16:32.550  7428  7450 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 19:16:32.550  7428  7450 D BluetoothAdapterService: starting service from this receiver
,09-06 19:16:32.550  1013  4116 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:16:32.550  1013  4116 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-06 19:16:32.550  1013  4116 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.550  1013  4116 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.550  1013  4116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.550  7428  7450 I BluetoothAdapterState: Entering On State from state = 11
,09-06 19:16:32.550  3064  7398 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:16:32.560  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:32.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:32.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:32.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:32.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:32.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:32.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:32.560  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:32.560  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:32.570  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-06 19:16:32.570  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.570  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.570  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:32.570  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.570  1992  2001 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:32.570  1992  2001 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.570  7428  7428 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-06 19:16:32.580  1427  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.580  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:16:32.580  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:32.580  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.580  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.580  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.580  1427  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:32.580  3064  3075 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:16:32.580  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-06 19:16:32.580  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.590  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.590  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.590  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.590  3064  3072 D Bluetoothsap: onBluetoothStateChange: up=true
,09-06 19:16:32.590  3064  3072 D Bluetoothsap: Binding service...
,09-06 19:16:32.590  3064  3072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:16:32.590  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-06 19:16:32.590  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.590  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.590  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.590  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.590  3064  3072 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:16:32.590  3064  7398 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:16:32.600  7428  7428 I BluetoothPbapService: Handler(): got msg=1
09-06 19:16:32.600  3064  3064 D BluetoothMap: Proxy object connected
,09-06 19:16:32.600  3064  3064 D MapProfile: Bluetooth service connected
09-06 19:16:32.600  3064  3064 D BluetoothMap: getConnectedDevices()
,09-06 19:16:32.600  1013  1026 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:16:32.600  3064  7398 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.600  7428  7512 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 19:16:32.620  7428  7512 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:16:32.620  7428  7512 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:32.620  7428  7512 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-06 19:16:32.620  7428  7512 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:16:32.620  7428  7512 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:16:32.620  7428  7512 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21f2b52c
09-06 19:16:32.620  7428  7512 D BluetoothSocket: channel: 19
09-06 19:16:32.620  7428  7512 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-06 19:16:32.650  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:32.650  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:32.650  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:32.650  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:32.650  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:32.650  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:32.650  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:32.650  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:32.660  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:32.660  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:32.660  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f5228df added. We now have 8 listener(s)
09-06 19:16:32.660  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:32.660  1013  1359 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:16:32.660  1013  1359 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-06 19:16:32.660  1013  1359 D SecContentProvider2: mCursor = null
,09-06 19:16:32.660  1013  1359 D WifiService: setWifiEnabled: false pid=6690, uid=10171
,09-06 19:16:32.660  1013  1359 D SettingsProvider: name = wifi_on
,09-06 19:16:32.670  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:32.670  1013  1478 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:16:32.670  1013  1478 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:16:32.670  1013  1478 D SecContentProvider2: mCursor = null
,09-06 19:16:32.670  1013  1478 D WifiService: setWifiEnabled: true pid=6690, uid=10171
,09-06 19:16:32.670  1013  1478 W ActivityManager: Permission Denial: getCurrentUser() from pid=6690, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:16:32.670  1013  1478 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:16:32.670  1013  1478 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6690, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:16:32.670  1013  1478 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:16:32.670  1013  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:16:32.670  1013  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:16:32.670  1013  1478 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:16:32.670  1013  1478 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:16:32.670  1013  1478 D SettingsProvider: name = wifi_on
,09-06 19:16:32.680  1013  1122 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 19:16:32.760  1013  1042 I art     : Explicit concurrent mark sweep GC freed 28101(1614KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.579ms total 160.297ms
,09-06 19:16:32.760  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:16:32.760  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.760  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.760  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.760  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.760  3064  3064 D BluetoothA2dp: Proxy object connected
09-06 19:16:32.760  3064  3064 D A2dpProfile: Bluetooth service connected
,09-06 19:16:32.770  1427  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.770  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:32.770  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:32.770  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.770  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.770  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.770  3064  3064 D BluetoothPbap: Proxy object connected
,09-06 19:16:32.770  3064  3064 D PbapServerProfile: Bluetooth service connected
09-06 19:16:32.770  3064  3064 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 19:16:32.770  3064  3064 D SapProfile: Bluetooth service connected
09-06 19:16:32.770  3064  3064 D Bluetoothsap: getConnectedDevices()
09-06 19:16:32.770  1427  1442 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:32.770  7428  7437 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:16:32.770  1436  1458 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.770  1436  1458 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.770  3064  3072 D BluetoothPan: Binding service...
,09-06 19:16:32.780  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-06 19:16:32.780  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.780  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.780  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.780  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.780  7428  7436 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:32.780  7428  7436 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:32.780  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:16:32.780  3064  3064 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:16:32.780  3064  3064 D PanProfile: Bluetooth service connected
09-06 19:16:32.780  1013  1042 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 19:16:32.780  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:16:32.780  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.780  1013  1013 D BluetoothA2dp: Proxy object connected
,09-06 19:16:32.780  1427  6870 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.780  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:32.780  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:32.780  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.780  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.780  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.780  1427  6870 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:32.780  6690  6700 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.780  6690  6700 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.790  3064  3075 D BluetoothAdapter: onBluetoothStateChange: up=true,
09-06 19:16:32.790  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:16:32.790  3064  3075 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:32.790  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-06 19:16:32.790  1013  1042 D BluetoothPan: Binding service...
,09-06 19:16:32.790  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:32.790  1013  1042 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:16:32.790  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:16:32.790  1013  1042 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:16:32.790  1427  3281 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:32.790  1427  3281 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:32.790  1013  1013 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:16:32.790  1173  1783 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.790  1173  1783 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.790  3064  3072 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.790  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:16:32.790  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:32.790  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.790  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.790  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.790  3064  3072 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:32.790  3064  3064 D HeadsetProfile: Bluetooth service connected
09-06 19:16:32.790  1459  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.790  1459  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.790  3064  3075 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:16:32.800  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-06 19:16:32.800  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.800  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.800  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:16:32.800  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.800  3064  3064 D BluetoothInputDevice: Proxy object connected
09-06 19:16:32.800  3064  3064 D HidProfile: Bluetooth service connected
,09-06 19:16:32.800  7341  7349 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:16:32.800  7341  7349 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:16:32.800  1459  4117 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:16:32.800  1013  1042 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:16:32.800  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:16:32.810  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.810  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.810  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.810  1459  4117 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:16:32.810  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:16:32.810  1013  1042 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:16:32.810  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:16:32.810  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:16:32.810  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:32.810  1013  1013 I InputMethodManagerService: [BT Setting State] State =12
09-06 19:16:32.810  1013  1013 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:16:32.820  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:16:32.820  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:16:32.820  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:32.820  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:32.820  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:32.820  1173  1173 D BluetoothTile:  getBluetoothState : 12
,09-06 19:16:32.820  1427  1427 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3c720e0b, true
,09-06 19:16:32.830  1173  1713 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:16:32.830  1427  1427 D BluetoothHeadset: registerMessageListener
,09-06 19:16:32.830  1876  1876 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:16:32.830  3064  3064 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:32.840  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:32.840  1013  4422 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:16:32.840  1013  4422 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.840  1013  1469 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:32.840  1013  4422 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.840  1013  4422 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:32.840  1013  4422 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:32.840  7428  7436 D HeadsetService: registerMessageListener
09-06 19:16:32.840  1013  1130 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-06 19:16:32.840  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:16:32.840  7428  7436 D HeadsetService: registerMessageListener
,09-06 19:16:32.840  7428  7517 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-06 19:16:32.840  7428  7458 D HeadsetStateMachine: Disconnected process message: 70
09-06 19:16:32.840  7428  7458 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3392bbf5
,09-06 19:16:32.850  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 19:16:32.850  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:16:32.850  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-06 19:16:32.850  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-06 19:16:32.850  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-06 19:16:32.860  3064  3064 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-06 19:16:32.860  7428  7517 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:16:32.860  7428  7517 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:32.860  3064  3064 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,09-06 19:16:32.860  7428  7517 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-06 19:16:32.860  7428  7517 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:16:32.860  7428  7517 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:16:32.860  7428  7517 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f3cdd8a
09-06 19:16:32.860  3064  3064 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 19:16:32.860  3064  3064 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 19:16:32.860  7428  7517 D BluetoothSocket: channel: 5
,09-06 19:16:32.860  7428  7458 D HeadsetStateMachine: Disconnected process message: 9
,09-06 19:16:32.860  7428  7458 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 19:16:32.870   282   681 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-06 19:16:32.870   282   681 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,09-06 19:16:32.870   282   681 V voice   : voice_set_parameters: exit with code(-2)
,09-06 19:16:32.870   282   681 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 19:16:32.870   282   681 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 19:16:32.870   282   681 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:16:32.870   282   681 V audio_hw_primary: adev_set_parameters: exit
,09-06 19:16:32.870  7428  7458 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 19:16:32.880  3064  3064 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:16:32.880  1013  1477 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:16:32.880  1013  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.880  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.880  1013  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.880  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:16:32.890  3064  3064 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:32.890  3064  3064 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:16:32.900  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:32.900  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:16:32.910  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@352f522
,09-06 19:16:32.910  7428  7428 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:16:32.910  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:16:32.910  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.910  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.910  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:32.910  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:16:32.930  1013  4116 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:16:32.940  1992  1992 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:32.940  1013  1359 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:16:32.940  1013  1359 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:16:32.940  1013  1359 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.940  1013  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:32.940  1013  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:32.950  1992  1992 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:16:32.950  1992  7534 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:16:32.950  1013  1466 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:32.950  7428  7532 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:16:32.950  1013  1466 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:32.950  1013  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:32.950  1013  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:32.950  7428  7532 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:32.960  7428  7532 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-06 19:16:32.960  7428  7532 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:16:32.960  7428  7532 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:16:32.960  7428  7532 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38934856
,09-06 19:16:32.970  7428  7532 D BluetoothSocket: channel: 12
09-06 19:16:32.970  7428  7532 I BtOppRfcommListener: Accept thread started.
,09-06 19:16:32.970  1013  1452 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:16:32.970  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:32.970  1013  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:16:32.970  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:16:32.980  1992  7534 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 19:16:33.010  1013  1040 D Tethering: interfaceAdded wlan0
,09-06 19:16:33.010  1013  1125 E Tethering: No numeric data
,09-06 19:16:33.020  1013  1125 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:16:33.020  1013  1125 D Tethering: clearTetheredNotification()
,09-06 19:16:33.020  1013  1119 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:16:33.020  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:33.020  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:16:33.020  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:33.030  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:33.030  1013  1119 V NetworkStats: performPollLocked() took 10ms
09-06 19:16:33.030  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:33.030  1173  1173 D HotspotTile: updateTetherState():false, false
,09-06 19:16:33.030  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:33.030  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:33.030  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:16:33.030  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:33.040  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:16:33.040  1013  1125 D Tethering: InitialState.processMessage what=4
,09-06 19:16:33.040  1013  1125 E Tethering: No numeric data
,09-06 19:16:33.040  1013  1125 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:16:33.040  1013  1125 D Tethering: clearTetheredNotification()
,09-06 19:16:33.040  1013  1040 D Tethering: interfaceAdded p2p0
,09-06 19:16:33.040  1013  1040 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-06 19:16:33.050  1013  1119 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:33.050  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:33.050  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:33.050  1173  1173 D HotspotTile: updateTetherState():false, false
,09-06 19:16:33.050  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:16:33.050  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:33.050  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:33.050  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:33.050  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:16:33.060   277  1000 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-06 19:16:33.060   277  1000 D SoftapController: Softap fwReload - Ok
09-06 19:16:33.060  1013  1119 V NetworkStats: performPollLocked() took 12ms
09-06 19:16:33.060  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:33.060  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:33.060  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:33.060   277  1000 D CommandListener: Setting iface cfg
09-06 19:16:33.060   277  1000 D CommandListener: Trying to bring down wlan0
,09-06 19:16:33.060   277  1000 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:16:33.060  1013  1122 E WifiHW  : supplicant_name : p2p_supplicant
,09-06 19:16:33.070  1013  1122 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-06 19:16:33.080  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:33.080  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:16:33.080  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:33.080  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:16:33.080  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:33.080  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:33.080  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:33.080  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-06 19:16:33.080  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:16:33.090  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-06 19:16:33.090  1173  1173 D HotspotTile: onReceive : 2, 0
,09-06 19:16:33.090  3064  3064 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:33.090  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:33.090  1013  1452 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:33.090  1013  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:33.100  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:33.100  1013  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:33.100  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:33.100  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:16:33.100  1587  1587 I Hs20UtilService: Starting #17
,09-06 19:16:33.100  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 19:16:33.100  1587  1630 I Hs20UtilService: Message received 5011
,09-06 19:16:33.100  6503  6503 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:16:33.100  6503  6503 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:33.110  7536  7536 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-06 19:16:33.110  7536  7536 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:16:33.110  7536  7536 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 19:16:33.120  7536  7536 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-06 19:16:33.120   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7536
09-06 19:16:33.120   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-06 19:16:33.130  7536  7536 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,09-06 19:16:33.130  7536  7536 I wpa_supplicant: ssSupport state is = 1
09-06 19:16:33.130  7536  7536 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:16:33.130  7536  7536 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-06 19:16:33.130   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7536
09-06 19:16:33.130   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-06 19:16:33.290   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-06 19:16:33.290  7536  7536 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-06 19:16:33.340  7536  7536 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-06 19:16:33.340  7536  7536 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:16:33.350  7536  7536 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 19:16:33.350   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7536
09-06 19:16:33.350   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:16:33.350  7536  7536 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:16:33.350  7536  7536 I wpa_supplicant: ssSupport state is = 1
09-06 19:16:33.350  7536  7536 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:33.350  7536  7536 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:33.350  7536  7536 E wpa_supplicant: SIM READ ERROR,
09-06 19:16:33.350  7536  7536 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:33.350  7536  7536 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:33.350  7536  7536 E wpa_supplicant: SIM READ ERROR
09-06 19:16:33.350  7536  7536 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:16:33.350  7536  7536 I wpa_supplicant: wpa_default_ap_write_once,
09-06 19:16:33.350  7536  7536 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:16:33.350  7536  7536 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:33.350  7536  7536 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 19:16:33.350  7536  7536 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:33.350  7536  7536 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-06 19:16:33.360  7536  7536 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-06 19:16:33.360  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 19:16:33.360  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:33.360  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:33.410   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,09-06 19:16:33.410  7536  7536 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-06 19:16:33.800  7536  7536 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-06 19:16:33.800  7536  7536 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-06 19:16:33.810  7536  7536 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 19:16:33.820   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7536
09-06 19:16:33.820   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-06 19:16:33.820  7536  7536 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:16:33.820  7536  7536 I wpa_supplicant: ssSupport state is = 1
,09-06 19:16:33.820  7536  7536 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:16:33.820  7536  7536 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:16:33.830  7536  7536 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 19:16:33.830   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7536
09-06 19:16:33.830   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:16:33.830  7536  7536 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-06 19:16:33.830  7536  7536 I wpa_supplicant: ssSupport state is = 1
09-06 19:16:33.830  7536  7536 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:33.830  7536  7536 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:33.830  7536  7536 E wpa_supplicant: SIM READ ERROR,
09-06 19:16:33.830  7536  7536 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:16:33.830  7536  7536 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:16:33.830  7536  7536 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:16:33.830  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false,
09-06 19:16:33.840  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:16:33.840  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:16:33.840  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
,09-06 19:16:33.840  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:33.840  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:33.910  7536  7536 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-06 19:16:33.910  7536  7536 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:16:33.950  7536  7536 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-06 19:16:33.950  7536  7536 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-06 19:16:33.950  7536  7536 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:16:33.960  1013  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-06 19:16:33.960  1013  1122 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:16:33.960  7536  7536 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-06 19:16:33.960  7536  7536 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:16:33.960  7536  7536 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:16:33.960  7536  7536 E wpa_supplicant: SIM READ ERROR
09-06 19:16:33.960  7536  7536 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:16:33.990  7536  7536 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-06 19:16:34.000  7536  7536 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:16:34.000  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:34.000  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:16:34.000  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:34.000  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:34.010  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:34.010  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:34.010  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:34.010  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-06 19:16:34.010  1173  1713 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:16:34.010  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:34.010  3064  3064 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:34.010  1013  1122 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:16:34.010  1173  1173 D HotspotTile: onReceive : 3, 0
,09-06 19:16:34.020  1013  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:34.020  1013  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:34.020  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:34.020  1013  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:34.020  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:34.020  1013  1122 E WifiConfigStore: Not a HS20
,09-06 19:16:34.030  1587  1587 I Hs20UtilService: Starting #18
,09-06 19:16:34.030  1013  1122 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-06 19:16:34.030  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:16:34.030  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:16:34.030  1587  1630 I Hs20UtilService: Message received 5011
,09-06 19:16:34.030  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:16:34.030  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:34.030  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:34.030  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:34.030  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:34.030  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:34.030  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:34.030  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:34.030  6690  6690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:34.030  6690  6690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:34.030  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:16:34.030  6503  6503 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:16:34.030  6503  6503 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:16:34.030  6503  6503 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:16:34.030  1013  1122 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-06 19:16:34.040  1013  1122 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 19:16:34.040  7536  7536 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 19:16:34.040  7536  7536 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 19:16:34.040  7536  7536 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:16:34.040  7536  7536 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:16:34.040  7536  7536 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:16:34.040  7536  7536 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:16:34.040  7536  7536 I wpa_supplicant: First Scan Start
09-06 19:16:34.040  7536  7536 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:16:34.040  1013  1122 D WifiNative-wlan0: Setting external_sim to 1
,09-06 19:16:34.040  1013  1122 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:16:34.040  1013  1122 I WifiNative-HAL: startHal
09-06 19:16:34.040  1013  1122 E wifi    : getStaticLongField sWifiHalHandle 0x9d69888c
09-06 19:16:34.040  1013  1122 I WifiNative-HAL: Could not start hal
,09-06 19:16:34.050  6956  6956 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:34.050  1013  1122 E WifiNative-wlan0: do suspend true
,09-06 19:16:34.050  1013  1121 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 19:16:34.050  1013  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-06 19:16:34.050   277  1000 D CommandListener: Setting iface cfg
09-06 19:16:34.050   277  1000 D CommandListener: Trying to bring up p2p0
09-06 19:16:34.050  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:16:34.050  1013  1145 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:34.050  1013  1145 I WifiNative-HAL: startHal
09-06 19:16:34.050  1013  1145 E wifi    : getStaticLongField sWifiHalHandle 0x9eb569bc
09-06 19:16:34.050  1013  1145 I WifiNative-HAL: Could not start hal
09-06 19:16:34.050  1013  1145 E WifiScanningService: could not start HAL
09-06 19:16:34.050  1013  1122 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:16:34.050  1013  1122 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:16:34.050  1013  1122 E WifiNative-wlan0: invaild command id : 215
,09-06 19:16:34.060  1013  1122 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:16:34.060  1013  1122 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:16:34.060  1013  1122 E WifiNative-wlan0: invaild command id : 215
,09-06 19:16:34.060  1013  1121 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:16:34.060  1013  1013 D RttService: SCAN_AVAILABLE : 3
09-06 19:16:34.060  1013  1146 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:34.060  1013  1121 D WifiP2pService: P2pEnablingState
,09-06 19:16:34.060  1013  1121 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-06 19:16:34.060  1013  1121 D WifiP2pService: P2p socket connection successful
09-06 19:16:34.060  1013  1121 D WifiP2pService: P2pEnabledState
,09-06 19:16:34.060  7536  7536 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:16:34.060  1013  1121 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:16:34.060  1013  1124 E ConnectivityService: updateNetworkInfo()
09-06 19:16:34.060  7536  7536 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:16:34.060  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 19:16:34.060  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 19:16:34.060  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:16:34.060  1013  1043 D WifiDisplayController: disconnect
09-06 19:16:34.060  1013  1043 D WifiDisplayController: updateConnection
09-06 19:16:34.060  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:16:34.060  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:16:34.060  7536  7536 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-06 19:16:34.060  1013  1122 E WifiStateMachine: Failed to set frequency band 0
,09-06 19:16:34.060  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:34.070  1013  1122 D SecContentProvider2: mCursor = null
,09-06 19:16:34.070  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:16:34.070  1013  1121 D WifiNative-p2p0: p2pGetDeviceAddress
09-06 19:16:34.070  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:16:34.070  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:16:34.070  1013  1121 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-06 19:16:34.070  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:16:34.070  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:16:34.070  3064  3064 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:16:34.070  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:34.070  1013  1122 D SecContentProvider2: mCursor = null
,09-06 19:16:34.070  1013  1121 D WifiP2pService: DeviceAddress: 0a:76:28
,09-06 19:16:34.070  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:34.070  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:34.070  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:16:34.070  3064  3064 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:16:34.070  3064  3832 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:34.070  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:16:34.070  1013  1227 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:16:34.080  1013  1043 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  secondary type: null
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  wps: 0
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  grpcapab: 0
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  devcapab: 0
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  status: 3
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  wfdInfo: null
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  groupownerAddress: null
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  GOdeviceName: null
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  interfaceAddress: 
09-06 19:16:34.080  1013  1043 D WifiDisplayController:  SConnectInfo : null
,09-06 19:16:34.080  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:16:34.080  6926  6926 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:34.080  6926  6926 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 19:16:34.080  6926  6926 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:16:34.080  6941  6941 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:16:34.090  1013  1121 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 19:16:34.090  1013  1121 D WifiP2pService: InactiveState
,09-06 19:16:34.090  1013  1121 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:16:34.090  1013  1121 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:16:34.090  7536  7536 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-06 19:16:34.090  1013  1121 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:16:34.090  1013  1121 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:16:34.690  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:34.690  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:34.690  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:34.690  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:34.690  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:34.690  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:34.690  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:34.690  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:34.690  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:34.700  6690  6743 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 19:16:34.700  6690  6743 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 19:16:34.700  6690  6743 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f06ead2 Bundle[{}],
09-06 19:16:34.700  6690  6743 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:16:34.700  6690  6743 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 19:16:34.710  6690  6743 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:16:34.710  6690  6743 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-06 19:16:34.710  6690  6743 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 19:16:34.710  6690  6743 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:16:34.710  6690  6743 I System.out: Running OutgoingSocketThread
,09-06 19:16:34.720  6690  7544 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1329)
,09-06 19:16:34.720  6690  7544 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49201
,09-06 19:16:34.720  6690  7544 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 19:16:35.230  7536  7536 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
09-06 19:16:35.230  7536  7536 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:16:35.230  7536  7536 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-06 19:16:35.230  7536  7536 I wpa_supplicant: Trying to associate with  'G700',
09-06 19:16:35.230  7536  7536 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-06 19:16:35.230  7536  7536 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-06 19:16:35.240  1013  7542 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,09-06 19:16:35.250  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:35.250  1013  1122 D SecContentProvider2: mCursor = null
,09-06 19:16:35.400   287   287 E SMD     : DCD OFF,
,09-06 19:16:35.510  7536  7536 E wpa_supplicant: Cmd 35605 not handled
,09-06 19:16:35.510  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:16:35.510  7536  7536 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-06 19:16:35.510  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:16:35.510  7536  7536 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 19:16:35.510  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:35.510  7536  7536 I wpa_supplicant: Associated with F4.99.3E
09-06 19:16:35.510  7536  7536 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:16:35.510  7536  7536 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 19:16:35.510  7536  7536 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:16:35.520  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:16:35.520  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:35.520  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:35.520  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:16:35.520  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:16:35.520  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:16:35.520  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:16:35.520  1013  1040 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:16:35.520  7536  7536 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:16:35.520  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-06 19:16:35.520  7536  7536 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-06 19:16:35.520  7536  7536 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-06 19:16:35.520  7536  7536 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-06 19:16:35.530  7536  7536 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:16:35.530  1013  1125 E Tethering: No numeric data
09-06 19:16:35.530  7536  7536 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 19:16:35.530  7536  7536 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 19:16:35.530  1013  1125 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:16:35.530  1013  1125 D Tethering: clearTetheredNotification()
,09-06 19:16:35.530  7536  7536 I wpa_supplicant: Blacklist: Clear (temp) ,
09-06 19:16:35.530  7536  7536 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-06 19:16:35.530  1013  1119 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:35.530  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:16:35.530  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:16:35.530  1013  1040 D Tethering: interfaceStatusChanged wlan0, true
09-06 19:16:35.530  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:35.530  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:35.530  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:35.530  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:35.530  1173  1173 D HotspotTile: updateTetherState():false, false
09-06 19:16:35.530  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:35.540  1013  1122 D SecContentProvider2: mCursor = null
,09-06 19:16:35.540  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:35.540  1013  1119 V NetworkStats: performPollLocked() took 7ms
,09-06 19:16:35.540  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:35.540  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:35.550  1013  1122 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-06 19:16:35.550  1013  1122 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 19:16:35.550  1013  1122 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 19:16:35.550  1013  1124 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 19:16:35.550  1013  1124 E ConnectivityService: updateNetworkInfo()
09-06 19:16:35.550  1013  1124 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:16:35.560  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:35.560  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:16:35.560  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:35.560  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:35.560  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:16:35.560  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:35.560  1013  1122 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:16:35.560  1013  1452 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:16:35.560  1013  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:35.560  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:35.560  1013  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:35.560  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:35.570  1587  1587 I Hs20UtilService: Starting #19
,09-06 19:16:35.570  1587  1630 I Hs20UtilService: Message received 5007
,09-06 19:16:35.570  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:16:35.570  3064  3064 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:16:35.570  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:16:35.580  1013  1122 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:16:35.580  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:16:35.580  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-06 19:16:35.580  3064  3064 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:16:35.580  3064  3832 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:16:35.590   277  1000 D CommandListener: Setting iface cfg
,09-06 19:16:35.590  1013  1122 E WifiStateMachine: Start Dhcp Watchdog 2
,09-06 19:16:35.600  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:16:35.600  1013  1122 D SecContentProvider2: mCursor = null
,09-06 19:16:35.600  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:16:35.600  1013  1122 D SecContentProvider2: mCursor = null
,09-06 19:16:35.610  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:35.610  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:35.610  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:35.610  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:16:35.610  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:35.610  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:35.620  1013  1122 E WifiNative-wlan0: do suspend false
,09-06 19:16:35.620  1013  1121 D WifiP2pService: InactiveState{ what=143375 },
,09-06 19:16:35.620  1013  1121 D WifiP2pService: P2pEnabledState{ what=143375 },
09-06 19:16:35.620  1013  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-06 19:16:35.620  1013  1122 D SecContentProvider2: mCursor = null
,09-06 19:16:35.700  1013  1569 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:16:35.700  1013  1569 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:16:35.700  1013  1569 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-06 19:16:35.700  1013  1569 D BatteryService: stay LED for fully charged
09-06 19:16:35.700  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:16:35.700  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:16:35.700  1013  1013 I MotionRecognitionService: Plugged
09-06 19:16:35.700  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
09-06 19:16:35.700  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:16:35.710  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:16:35.710  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 19:16:35.720  6690  6743 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1330)
09-06 19:16:35.720  6690  6743 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1330)
,09-06 19:16:35.720  6690  6743 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1335)
,09-06 19:16:35.720  6690  6743 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-06 19:16:35.730  6690  6743 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1336)
09-06 19:16:35.730  7428  7428 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:16:35.730  7428  7458 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:16:35.730  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:35.730  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e9892c added. We now have 2 listener(s)
,09-06 19:16:35.730  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:16:35.730  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 19:16:35.730  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 19:16:35.730  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-06 19:16:35.730  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-06 19:16:35.730  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:16:35.730  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:16:35.730  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:35.730  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:35.730  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3442fff5 added. We now have 9 listener(s)
09-06 19:16:35.730  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:35.740  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:35.740  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:35.750  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:35.750  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:35.750  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:35.750  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:35.750  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:35.750  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:35.750  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:35.750  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:35.750  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:35.750  6690  6743 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:35.750  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:35.750  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@345a73fb added. We now have 3 listener(s)
,09-06 19:16:35.750  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:35.750  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:16:35.750  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:35.750  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:35.750  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:35.750  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fc0c18 added. We now have 10 listener(s)
09-06 19:16:35.750  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:35.750  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:35.750  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:35.750  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:35.750  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:35.750  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:35.750  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:35.750  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:16:35.750  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e9892c removed from the list
09-06 19:16:35.750  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:35.750  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3442fff5 removed from the list
,09-06 19:16:35.760  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:35.760  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:35.760  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:35.760  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:16:35.760  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:35.760  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:35.760  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:35.760  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:35.760  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3442fff5 not in the list
09-06 19:16:35.760  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:35.760  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:35.760  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:16:35.760  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:35.760  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:35.760  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fc0c18 removed from the list
09-06 19:16:35.760  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:16:35.770  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:35.770  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:35.770  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:35.770  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@345a73fb removed from the list
,09-06 19:16:35.770  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:16:35.770  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1190a671 added. We now have 2 listener(s)
,09-06 19:16:35.770  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:16:35.770  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:35.770  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:35.770  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:35.770  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39b37c56 added. We now have 9 listener(s)
09-06 19:16:35.770  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:35.770  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:35.770  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:35.780  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:35.780  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:35.780  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:35.780  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:35.780  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:35.780  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:35.780  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:35.780  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:35.780  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:35.780  6690  6743 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:35.780  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:35.780  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:35.780  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11b1d1c4 added. We now have 3 listener(s)
,09-06 19:16:35.780  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:35.790  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:16:35.790  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:35.790  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:35.790  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:35.790  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@383838ad added. We now have 10 listener(s)
09-06 19:16:35.790  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:35.790  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:35.790  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:35.790  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:35.790  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:35.790  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:16:35.790  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:16:35.800  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:16:35.800  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:16:35.800  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:16:35.800  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:16:35.800  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:35.800  7428  7436 D BtGatt.GattService: registerClient() - UUID=2ea03f18-dc6e-4cf3-a04f-4909ace71926
,09-06 19:16:35.840  7549  7549 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:16:35.840  7549  7549 I dhcpcd  : version 5.5.6 starting
,09-06 19:16:35.840  7549  7549 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:16:35.850  7428  7453 D BtGatt.GattService: onClientRegistered() - UUID=2ea03f18-dc6e-4cf3-a04f-4909ace71926, clientIf=6
,09-06 19:16:35.850  6690  6698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:35.860  7428  7516 D BtGatt.GattService: start scan with filters,
09-06 19:16:35.860  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:16:35.860  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:16:35.860  7428  7457 D BtGatt.ScanManager: handling starting scan
09-06 19:16:35.860  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:16:35.860  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
09-06 19:16:35.860  7428  7457 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@352f522
09-06 19:16:35.860  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:16:35.860  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:16:35.860  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:16:35.860  7428  7453 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 19:16:35.860  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:35.860  7428  7457 D BtGatt.ScanManager: allow scan with filters
09-06 19:16:35.860  7428  7457 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:16:35.860  7428  7457 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-06 19:16:35.870  7428  7453 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:16:35.870  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:35.870  7428  7457 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:16:35.870  7428  7457 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:16:35.870  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:16:35.870  7428  7453 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:16:35.870  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:35.880  7428  7453 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:16:35.880  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:35.880  6690  6743 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:16:35.880  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:35.880  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:16:35.880  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:35.880  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:16:35.880  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:16:35.880  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:35.880  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:35.880  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:35.880  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:35.880  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:16:35.890  7428  7516 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:16:35.890  7428  7457 D BtGatt.ScanManager: filter size is 1
09-06 19:16:35.890  7428  7457 D BtGatt.ScanManager: delete FilterIndex - 3,
,09-06 19:16:35.890  7428  7437 D BtGatt.GattService: unregisterClient() - clientIf=6
09-06 19:16:35.890  7428  7453 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:16:35.890  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:35.890  7428  7457 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:16:35.890  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:35.890  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:35.890  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:16:35.890  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:16:35.890  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:16:35.890  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:35.890  7428  7453 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:16:35.890  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:35.890  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:16:35.890  7428  7457 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:16:35.890  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:16:35.890  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:16:35.890  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:35.900  7428  7453 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 19:16:35.900  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:35.900  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:16:35.900  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:35.900  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:35.920  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-06 19:16:35.920  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:35.920  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:35.920  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:35.920  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:16:35.920  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1190a671 removed from the list
09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:35.920  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39b37c56 removed from the list
09-06 19:16:35.920  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:35.920  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:35.920  7549  7549 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-06 19:16:35.920  7549  7549 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-06 19:16:35.920  7549  7549 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-06 19:16:35.920  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:35.920  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:35.920  7549  7549 I dhcpcd  : bssid match
09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:35.920  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39b37c56 not in the list
09-06 19:16:35.920  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:35.920  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:35.920  7549  7549 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
09-06 19:16:35.920  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@383838ad removed from the list
09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:35.920  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:35.920  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:35.920  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11b1d1c4 removed from the list
09-06 19:16:35.920  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:35.920  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@204cb2a9 added. We now have 2 listener(s)
,09-06 19:16:35.920  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:16:35.920  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:16:35.920  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:35.920  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:35.920  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36cdc02e added. We now have 9 listener(s)
,09-06 19:16:35.920  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:35.920  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:35.930  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:35.930  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:35.930  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:35.930  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:35.930  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:35.930  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:35.930  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:35.930  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:35.930  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:35.930  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:35.930  6690  6743 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:35.930  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:35.930  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf7955c added. We now have 3 listener(s)
,09-06 19:16:35.930  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:35.940  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:16:35.940  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:35.940  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:35.940  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:35.940  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1614d065 added. We now have 10 listener(s)
09-06 19:16:35.940  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:35.940  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:16:35.940  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:35.940  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:35.940  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:35.940  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:35.940  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:16:35.940  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:35.940  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:16:35.940  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:16:35.940  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:16:35.950  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:16:35.950  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:16:35.950  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:35.950  7428  7436 D BtGatt.GattService: registerClient() - UUID=88239320-49a1-499b-a652-8acd763f636f
,09-06 19:16:35.990  7428  7453 D BtGatt.GattService: onClientRegistered() - UUID=88239320-49a1-499b-a652-8acd763f636f, clientIf=6
,09-06 19:16:35.990  6690  6700 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:35.990  7428  7510 D BtGatt.GattService: start scan with filters
,09-06 19:16:35.990  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:16:35.990  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:16:35.990  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:16:35.990  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:16:36.000  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:16:36.000  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:16:36.000  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:16:36.000  7428  7457 D BtGatt.ScanManager: handling starting scan
,09-06 19:16:36.000  7428  7453 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:16:36.000  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:16:36.000  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.000  7428  7457 D BtGatt.ScanManager: allow scan with filters
09-06 19:16:36.000  7428  7457 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:16:36.000  7428  7457 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 19:16:36.000  7428  7453 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:16:36.000  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.000  7428  7457 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:16:36.000  7428  7457 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-06 19:16:36.000  7428  7453 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:16:36.000  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.010  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:36.010  6690  6743 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-06 19:16:36.010  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:36.010  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:36.010  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:36.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:36.010  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.010  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:16:36.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:36.010  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@204cb2a9 removed from the list
09-06 19:16:36.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.010  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36cdc02e removed from the list
09-06 19:16:36.010  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:36.010  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:36.010  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.010  7428  7453 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:16:36.010  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.010  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:16:36.010  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.010  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:36.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:36.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:36.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.010  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36cdc02e not in the list
09-06 19:16:36.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:36.010  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:36.010  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:36.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:36.010  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:16:36.010  7428  7510 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:16:36.010  7428  7457 D BtGatt.ScanManager: filter size is 1
,09-06 19:16:36.010  7428  7457 D BtGatt.ScanManager: delete FilterIndex - 4
,09-06 19:16:36.020  7428  7437 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:16:36.020  7428  7453 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:16:36.020  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.020  7428  7457 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:16:36.020  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:16:36.020  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:36.020  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:16:36.020  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 19:16:36.020  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
09-06 19:16:36.020  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:36.020  7428  7453 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:16:36.020  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.020  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:16:36.020  7428  7457 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:16:36.020  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:16:36.020  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:16:36.020  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:36.030  7549  7549 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
09-06 19:16:36.030  7428  7453 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:16:36.030  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.030  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:36.030  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:36.030  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:16:36.030  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:36.030  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:36.030  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.030  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1614d065 removed from the list
09-06 19:16:36.030  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:36.030  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.030  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:36.030  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:36.030  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf7955c removed from the list
,09-06 19:16:36.030  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:36.030  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29870de1 added. We now have 2 listener(s)
,09-06 19:16:36.030  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 19:16:36.030  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:36.030  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:36.030  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:36.030  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31c1a706 added. We now have 9 listener(s)
09-06 19:16:36.030  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:36.030  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:36.040  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:36.040  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:36.040  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:36.040  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:36.040  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:36.040  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:36.040  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:36.040  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:36.040  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:36.040  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-06 19:16:36.040  6690  6743 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:36.040  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:36.040  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@388f33f4 added. We now have 3 listener(s)
,09-06 19:16:36.040  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:36.050  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
09-06 19:16:36.050  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:36.050  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-06 19:16:36.050  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:36.050  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1985a71d added. We now have 10 listener(s)
09-06 19:16:36.050  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:36.050  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:36.050  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:36.050  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:36.050  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:36.050  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:16:36.050  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:36.050  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:16:36.060  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:16:36.060  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:16:36.060  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:16:36.060  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:16:36.060  6690  6743 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:16:36.060  7428  7510 D BtGatt.GattService: registerClient() - UUID=8c09b9c8-42ef-4337-bf5f-3b2f772a2890
,09-06 19:16:36.100  7428  7453 D BtGatt.GattService: onClientRegistered() - UUID=8c09b9c8-42ef-4337-bf5f-3b2f772a2890, clientIf=6
,09-06 19:16:36.110  6690  6700 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:16:36.110  7428  7437 D BtGatt.GattService: start scan with filters
,09-06 19:16:36.110  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:16:36.110  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:16:36.110  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:16:36.110  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:16:36.110  7428  7457 D BtGatt.ScanManager: handling starting scan
,09-06 19:16:36.110  7428  7453 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:16:36.110  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.110  7428  7457 D BtGatt.ScanManager: allow scan with filters
09-06 19:16:36.110  7428  7457 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:16:36.110  7428  7457 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 19:16:36.110  7428  7453 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:16:36.110  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.110  7428  7457 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:16:36.110  7428  7457 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:16:36.120  7428  7453 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:16:36.120  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.120  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:16:36.120  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:16:36.120  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:16:36.120  7428  7453 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:16:36.120  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.120  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:16:36.130  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:36.130  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:36.130  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:36.130  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:36.130  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.130  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:16:36.130  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:36.130  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29870de1 removed from the list
09-06 19:16:36.130  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.130  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31c1a706 removed from the list
09-06 19:16:36.130  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:36.130  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:36.130  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.130  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:16:36.130  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.130  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:16:36.130  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 19:16:36.130  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:36.130  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.130  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31c1a706 not in the list
,09-06 19:16:36.130  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:36.130  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:36.130  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:36.130  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 19:16:36.130  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:16:36.140  7428  7510 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:16:36.140  7428  7457 D BtGatt.ScanManager: filter size is 1
,09-06 19:16:36.140  7428  7457 D BtGatt.ScanManager: delete FilterIndex - 5
,09-06 19:16:36.140  7428  7437 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:16:36.140  7428  7453 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:16:36.140  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.140  7428  7457 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:16:36.140  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:36.140  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:16:36.140  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:16:36.140  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:16:36.140  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:16:36.140  7549  7549 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,09-06 19:16:36.150  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:16:36.150  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,09-06 19:16:36.150  6690  6743 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:16:36.150  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:16:36.150  7428  7453 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:16:36.150  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:16:36.150  7428  7457 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:16:36.150  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:36.150  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:36.150  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:36.150  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.150  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1985a71d removed from the list
09-06 19:16:36.150  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:36.150  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.150  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:36.150  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:36.150  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@388f33f4 removed from the list
09-06 19:16:36.150  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:36.150  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36da9819 added. We now have 2 listener(s)
09-06 19:16:36.150  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:36.150  6690  6690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:36.150  6690  6690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:36.160  7428  7453 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:16:36.160  7428  7453 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:16:36.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 19:16:36.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:36.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:36.160  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:36.160  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31c090de added. We now have 9 listener(s)
09-06 19:16:36.160  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:36.160  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:16:36.170  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:36.170  6690  6743 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:36.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:36.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:16:36.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:36.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:36.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:36.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:36.170  6690  6743 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:36.170  6690  6743 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-06 19:16:36.170  6690  6743 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:36.170  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:36.170  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b790d8c added. We now have 3 listener(s)
,09-06 19:16:36.180  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:36.180  6690  6690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:36.180  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
09-06 19:16:36.180  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:36.180  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:16:36.190  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:36.190  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af39cd5 added. We now have 10 listener(s)
09-06 19:16:36.190  6690  6743 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:36.190  6690  6743 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:36.190  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:36.190  6690  6743 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:36.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:36.190  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.190  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:36.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:36.190  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36da9819 removed from the list
09-06 19:16:36.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.190  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31c090de removed from the list
09-06 19:16:36.190  6690  6743 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:16:36.190  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:36.190  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.190  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:36.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:16:36.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:36.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.190  6690  6743 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31c090de not in the list
09-06 19:16:36.190  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:16:36.190  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:36.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:36.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:36.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:36.190  6690  6743 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af39cd5 removed from the list
,09-06 19:16:36.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:36.190  6690  6743 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:36.190  6690  6743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:36.190  6690  6743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:16:36.190  6690  6743 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b790d8c removed from the list
09-06 19:16:36.190  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 19:16:36.190  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 19:16:36.190  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:16:36.190  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:36.190  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:16:36.190  6690  6743 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:16:36.200  6690  7563 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1343, name: My test thread name)
,09-06 19:16:36.200  6690  7563 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1343, thread name: My test thread name)
09-06 19:16:36.200  6690  7563 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1343, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:16:36.210  6690  7565 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1345, name: My test thread name),
09-06 19:16:36.210  6690  7565 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1345, thread name: My test thread name)
09-06 19:16:36.210  6690  7565 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1345, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:16:36.210  6690  6743 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 19:16:36.210  6690  6743 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:16:36.210  6690  6743 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-06 19:16:36.210  6690  6743 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:16:36.210  6690  6743 D com.test.thalitest.ThaliTestRunner: Total duration: 23253 ms
09-06 19:16:36.210  6690  6743 I jxcore-log: *Native tests were executed*
09-06 19:16:36.210  6690  6743 I jxcore-log: 
,09-06 19:16:36.210  6690  6743 I jxcore-log: Total number of executed tests:  80
09-06 19:16:36.210  6690  6743 I jxcore-log: 
09-06 19:16:36.210  6690  6743 I jxcore-log: Number of passed tests:  80
09-06 19:16:36.210  6690  6743 I jxcore-log: 
09-06 19:16:36.210  6690  6743 I jxcore-log: Number of failed tests:  0
09-06 19:16:36.210  6690  6743 I jxcore-log: ,
09-06 19:16:36.210  6690  6743 I jxcore-log: Number of ignored tests:  0
09-06 19:16:36.210  6690  6743 I jxcore-log: 
09-06 19:16:36.210  6690  6743 I jxcore-log: Total duration:  23253
09-06 19:16:36.210  6690  6743 I jxcore-log: 
09-06 19:16:36.210  6690  6743 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,09-06 19:16:36.210  6690  6743 I jxcore-log: 
09-06 19:16:36.210  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:36.210  6690  6743 I jxcore-log: 
09-06 19:16:36.220  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:36.220  6690  6743 I jxcore-log: 
09-06 19:16:36.220  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:36.220  6690  6743 I jxcore-log: 
09-06 19:16:36.220  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:36.220  6690  6743 I jxcore-log: 
09-06 19:16:36.220  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:36.220  6690  6743 I jxcore-log: 
09-06 19:16:36.220  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:36.220  6690  6743 I jxcore-log: 
09-06 19:16:36.230  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:36.230  6690  6743 I jxcore-log: 
09-06 19:16:36.230  6690  6690 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:16:36.230  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:16:36.230  6690  6743 I jxcore-log: 
09-06 19:16:36.230  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:36.230  6690  6743 I jxcore-log: 
09-06 19:16:36.230  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:36.230  6690  6743 I jxcore-log: 
09-06 19:16:36.230  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:16:36.230  6690  6743 I jxcore-log: 
09-06 19:16:36.230  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:16:36.230  6690  6743 I jxcore-log: 
09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:36.240  6690  6743 I jxcore-log: 
09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:36.240  6690  6743 I jxcore-log: 
09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:16:36.240  6690  6743 I jxcore-log: 
09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:16:36.240  6690  6743 I jxcore-log: 
09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:36.240  6690  6743 I jxcore-log: 
,09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:36.240  6690  6743 I jxcore-log: 
,09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
09-06 19:16:36.240  6690  6743 I jxcore-log: 
09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:16:36.240  6690  6743 I jxcore-log: 
,09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:36.240  6690  6743 I jxcore-log: 
,09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:36.240  6690  6743 I jxcore-log: 
,09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:36.240  6690  6743 I jxcore-log: 
,09-06 19:16:36.240  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:36.240  6690  6743 I jxcore-log: 
,09-06 19:16:36.250  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:36.250  6690  6743 I jxcore-log: 
,09-06 19:16:36.250  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-06 19:16:36.250  6690  6743 I jxcore-log: 
,09-06 19:16:36.250  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:36.250  6690  6743 I jxcore-log: 
,09-06 19:16:36.400  6690  6690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:16:36.410  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:16:36.410  6690  6743 I jxcore-log: 
,09-06 19:16:36.430  1013  1122 E WifiNative-wlan0: do suspend true,
,09-06 19:16:36.450  1013  1121 D WifiP2pService: InactiveState{ what=143375 },
,09-06 19:16:36.450  1013  1121 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:16:36.460  1013  1122 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 19:16:36.460  1013  1122 E WifiStateMachine: VerifyingLinkState enter
,09-06 19:16:36.460  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:36.460  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:36.460  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.460  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.460  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.460  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:36.460  1013  1124 E ConnectivityService: updateNetworkInfo()
09-06 19:16:36.460  1013  1139 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-06 19:16:36.460  1013  1139 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:16:36.460  1013  1139 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
09-06 19:16:36.460  1013  1139 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:16:36.460  1013  1124 D ConnectivityService: Adding iface wlan0 to network 503
09-06 19:16:36.460  1013  1139 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:16:36.460  1013  1124 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-06 19:16:36.470  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:36.470  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:36.470  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.470  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.470  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.470  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:36.480  1013  1130 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:36.480  1013  1130 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:36.480  1013  1130 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:36.480  1013  1130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:36.480  1013  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:36.480  1587  1587 I Hs20UtilService: Starting #20
,09-06 19:16:36.480  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:16:36.480  1587  1630 I Hs20UtilService: Message received 5007
,09-06 19:16:36.490  3064  3064 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 19:16:36.500  1013  1122 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-06 19:16:36.500  1013  1124 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503,
,09-06 19:16:36.500  1013  1124 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,09-06 19:16:36.500  1013  1124 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,09-06 19:16:36.500  1013  1124 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:16:36.500  1013  1124 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
09-06 19:16:36.500  1013  1124 D ConnectivityService: LTETest block dns file not exists
,09-06 19:16:36.510  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.510  1013  1124 V NetworkStats: updateIfacesLocked()
09-06 19:16:36.510  1013  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:16:36.510  1013  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:36.510  1013  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:36.520  1013  1124 V NetworkStats: performPollLocked() took 4ms
09-06 19:16:36.520  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:36.520  1013  1124 E ConnectivityService: updateNetworkInfo()
09-06 19:16:36.520  1013  1124 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-06 19:16:36.520  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.520  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 19:16:36.520  7575  7575 D AndroidRuntime: 
09-06 19:16:36.520  7575  7575 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-06 19:16:36.520  1013  1124 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:36.520  1013  1124 E ConnectivityService: updateNetworkInfo()
09-06 19:16:36.520  1013  1124 V NetworkStats: updateIfacesLocked()
09-06 19:16:36.520  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.520  1013  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:16:36.520  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:16:36.520  1013  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:36.520  1013  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:16:36.520  7575  7575 D AndroidRuntime: CheckJNI is OFF
09-06 19:16:36.520  7575  7575 D AndroidRuntime: readGMSProperty: start
09-06 19:16:36.520  7575  7575 D AndroidRuntime: readGMSProperty: already setted!!
09-06 19:16:36.520  7575  7575 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 19:16:36.520  7575  7575 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:16:36.520  7575  7575 D AndroidRuntime: readGMSProperty: end
09-06 19:16:36.520  7575  7575 D AndroidRuntime: addProductProperty: start
,09-06 19:16:36.520  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.520  1013  1124 V NetworkStats: performPollLocked() took 5ms
,09-06 19:16:36.530  6690  6690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:16:36.530  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:36.530  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:16:36.530  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.530  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.530  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.530  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:36.530  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:16:36.530  6690  6743 I jxcore-log: 
09-06 19:16:36.530  1013  1122 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 19:16:36.540  1013  7545 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:36.540  1013  1124 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
09-06 19:16:36.540  1013  7545 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-06 19:16:36.540  1013  1124 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-06 19:16:36.540  1013  7545 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:36.540  1013  7545 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-06 19:16:36.540  1013  7545 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:16:36.540  1013  1124 D ConnectivityService:    accepting network in place of null
,09-06 19:16:36.540  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:16:36.540  1013  1013 I WifiTrafficPoller: mBoosterFLAG : 0,
09-06 19:16:36.540  1013  1013 I WifiTrafficPoller: current booster mode : FullMode
09-06 19:16:36.540  1013  1121 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:16:36.540  1459  1459 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 19:16:36.540  1459  1459 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:16:36.540  1013  1124 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:16:36.540  1013  1124 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-06 19:16:36.540  1013  1124 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:16:36.540  1013  1122 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:16:36.540  1013  1122 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-06 19:16:36.540  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.540  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.550  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:16:36.550  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:16:36.550  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:36.550  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.550  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.550  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.550  1013  1452 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:36.550  1013  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:16:36.550  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:36.550  1013  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:36.550  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:16:36.550  1013  1013 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-06 19:16:36.550  1013  1124 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} },
09-06 19:16:36.550   277   996 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:16:36.550  1013  1124 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
09-06 19:16:36.550   277   996 D Netd    : getNetworkForDns: using netid 503 for uid 1000
09-06 19:16:36.550  1013  1119 V NetworkStats: updateIfacesLocked()
09-06 19:16:36.550  1013  1125 D Tethering: MasterInitialState.processMessage what=3
09-06 19:16:36.550  1013  1119 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:16:36.550  1587  1587 I Hs20UtilService: Starting #21
09-06 19:16:36.550  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.550  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:36.550  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:16:36.550  1013  1042 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-06 19:16:36.560  1173  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:16:36.560  4757  6753 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 19:16:36.560  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.560  1013  1119 V NetworkStats: performPollLocked() took 6ms
09-06 19:16:36.560  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.560  1013  1120 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 19:16:36.560  1587  1630 I Hs20UtilService: Message received 5007
09-06 19:16:36.560  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.560  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.560  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.560  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:16:36.560  3064  3064 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:16:36.560  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-06 19:16:36.560  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:16:36.560  3064  3064 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-06 19:16:36.560  3064  3064 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 19:16:36.570  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 19:16:36.570  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:36.570  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:16:36.570  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:16:36.570  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:16:36.580  1013  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:16:36.580  1013  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:16:36.580  1013  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:36.580  1013  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:36.580  1013  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:16:36.580  1587  1587 I Hs20UtilService: Starting #22
09-06 19:16:36.580  3064  3064 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:16:36.580  3064  3064 I NearbySettings: MountReceiver.onReceive - Keep current state
09-06 19:16:36.580  1587  1630 I Hs20UtilService: Message received 5007
,09-06 19:16:36.590  1013  1568 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0,
09-06 19:16:36.590  1013  1025 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-06 19:16:36.590  1013  1025 D SecContentProvider2: mCursor = null
,09-06 19:16:36.590  1013  1130 D SecContentProvider2: uri = 15 selection = getToastGravity,
09-06 19:16:36.590  1013  1130 D SecContentProvider2: mCursor = null
,09-06 19:16:36.590  1013  1494 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset,
09-06 19:16:36.590  1013  1494 D SecContentProvider2: mCursor = null
,09-06 19:16:36.600  1013  1026 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
09-06 19:16:36.600  1013  1026 D SecContentProvider2: mCursor = null
,09-06 19:16:36.600  1013  1478 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
09-06 19:16:36.600  1013  1478 D SecContentProvider2: mCursor = null,
09-06 19:16:36.600  1013  1569 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,09-06 19:16:36.600  1013  1569 D SecContentProvider2: mCursor = null
,09-06 19:16:36.620   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-06 19:16:36.630  1013  1568 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013,
,09-06 19:16:36.630  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 19:16:36.660  6690  6690 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:16:36.660  6690  6743 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:16:36.660  6690  6743 I jxcore-log: 
,09-06 19:16:36.660  7575  7575 E AffinityControl: AffinityControl: registerfunction enter
,09-06 19:16:36.690  7575  7575 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-06 19:16:36.700  1013  1026 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-06 19:16:36.700  1013  1026 D PackageManager: START PACKAGE DELETE: observer{166951780}
09-06 19:16:36.700  1013  1026 D PackageManager: pkg{<packageName>}
09-06 19:16:36.700  1013  1026 D PackageManager: user{0}
09-06 19:16:36.700  1013  1026 D PackageManager: caller{2000}
09-06 19:16:36.700  1013  1026 D PackageManager: flags{2}
09-06 19:16:36.700  1013  1026 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-06 19:16:36.700  1013  1026 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-06 19:16:36.700  1013  1026 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-06 19:16:36.700  1013  1026 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-06 19:16:36.700  1013  1052 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-06 19:16:36.700  1013  1052 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-06 19:16:36.700  1013  1052 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,09-06 19:16:36.710  1013  1052 D ApplicationPolicy: getApplicationUninstallationEnabled,
09-06 19:16:36.710  1013  1052 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-06 19:16:36.710  1013  1052 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-06 19:16:36.710  1013  1038 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,09-06 19:16:36.730  1013  1038 I ActivityManager: Killing 6690:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-06 19:16:36.800  1013  1052 W PackageSettings: Skipping PackageSetting{2c36bffd com.example.hello/10168} due to missing metadata
,09-06 19:16:36.810  1013  1466 I WindowState: WIN DEATH: Window{4827ce8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:16:36.810   257   452 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-06 19:16:36.810   257   448 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-06 19:16:36.810  1013  1466 D InputDispatcher: Focus left window: 6690
,09-06 19:16:36.830  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:16:36.830  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:16:36.830  1013  1038 I ActivityManager:   Force finishing activity ActivityRecord{12471a88 u0 com.test.thalitest/.MainActivity t2}
,09-06 19:16:36.840  1013  1359 W ActivityManager: Spurious death for ProcessRecord{3f9c31cd 6690:com.test.thalitest/u0a171}, curProc for 6690: null
,09-06 19:16:36.850  1013  1052 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-06 19:16:36.850  1013  1052 I ActivityManager:   Force finishing activity ActivityRecord{12471a88 u0 com.test.thalitest/.MainActivity t2 f}
,09-06 19:16:36.850  1013  1052 W ActivityManager: Duplicate finish request for ActivityRecord{12471a88 u0 com.test.thalitest/.MainActivity t2 f}
,09-06 19:16:36.890  1013  1052 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-06 19:16:36.910  2639  2639 I art     : Explicit concurrent mark sweep GC freed 19571(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 790us total 33.855ms
,09-06 19:16:36.920  1013  1038 D InputDispatcher: Focused application released
,09-06 19:16:36.920  1013  1038 D FocusedStackFrame: Set to : 0
,09-06 19:16:36.920  1013  1038 W ActivityManager: mDVFSHelper.acquire()
,09-06 19:16:36.930  1013  1038 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-06 19:16:36.960  4757  4757 I art     : Explicit concurrent mark sweep GC freed 22859(1386KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.544ms total 97.249ms
,09-06 19:16:36.970  1479  1479 D Launcher: onRestart, Launcher: 1004344688
,09-06 19:16:36.990  1992  2154 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.,
,09-06 19:16:36.990  1876  1876 E SamsungIME: mOCRHelper is null
,09-06 19:16:37.000  1459  1459 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:16:37.020  1013  1119 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-06 19:16:37.020  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.020  1013  1119 V NetworkStats: performPollLocked(flags=0x3)
,09-06 19:16:37.020  1013  1094 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:16:37.020  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:16:37.020  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:37.030  1013  1119 V NetworkStats: performPollLocked() took 7ms
09-06 19:16:37.030  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:37.030  1479  1479 D Launcher: onStart, Launcher: 1004344688
,09-06 19:16:37.030  1479  1479 D Launcher.HomeView: onStart
,09-06 19:16:37.030  1479  1479 D Launcher: onResume, Launcher: 1004344688
,09-06 19:16:37.030  1013  1026 D SettingsProvider: name = kids_home_mode
09-06 19:16:37.030  1013  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:16:37.030  1013  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:16:37.030  1013  1026 D SettingsProvider: selectionArgs: false
09-06 19:16:37.030  1013  1026 D SettingsProvider: selectionArgs: 10006
09-06 19:16:37.030  1013  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:16:37.030  1013  1026 D SettingsProvider: ret = -1
09-06 19:16:37.030  1479  1479 D Launcher.HomeView: onResume
,09-06 19:16:37.040  1436  1436 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:16:37.040  1436  1436 D RegisteredServicesCache: empty dynamic service
,09-06 19:16:37.040  2907  2907 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 19:16:37 GMT+02:00 2016
,09-06 19:16:37.050  1013  1452 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:16:37.050  1013  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 19:16:37.050  1013  1124 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:37.050  1013  1013 D RCPManagerService: PackageReceiver onReceive()
,09-06 19:16:37.050  1013  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:16:37.050  1013  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:37.050  1013  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 19:16:37.050  1013  1013 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-06 19:16:37.050  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
09-06 19:16:37.060  2907  2907 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
09-06 19:16:37.060  1013  1013 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-06 19:16:37.060  1013  1013 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-06 19:16:37.060  1013  1013 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-06 19:16:37.070  1013  1469 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,09-06 19:16:37.070  1013  1469 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
09-06 19:16:37.070  2907  2907 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-06 19:16:37.070  2907  2907 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 19:16:37.070  1013  1013 I OTPFW   : ProvisionData::getAllEntries Enter
,09-06 19:16:37.080  1013  1013 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-06 19:16:37.080  2907  2907 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 19:16:37.100  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.100  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:16:37.100  1013  1037 D EnterpriseDeviceManagerService: Package has changed for user 0
09-06 19:16:37.100  1013  1037 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-06 19:16:37.100  1013  1469 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-06 19:16:37.100  2907  7600 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 19:16:37.120  1013  1037 W TextServicesManagerService: no available spell checker services found
,09-06 19:16:37.130  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.130  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.130  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.130  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.130  2907  7600 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-06 19:16:37.140  2907  7600 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-06 19:16:37.140  1013  1052 I art     : Explicit concurrent mark sweep GC freed 68470(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 24MB/37MB, paused 10.640ms total 244.226ms,
,09-06 19:16:37.140  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:37.140  1013  1026 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 19:16:37.140  1013  1026 D SecContentProvider2: mCursor = null
,09-06 19:16:37.140  7601  7601 E Zygote  : MountEmulatedStorage()
09-06 19:16:37.150  7601  7601 E Zygote  : v2
,09-06 19:16:37.150  7601  7601 I libpersona: KNOX_SDCARD checking this for 10090
09-06 19:16:37.150  7601  7601 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:37.150  7601  7601 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:37.150  7601  7601 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:37.150  1013  1469 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7601 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-06 19:16:37.150  7601  7601 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:37.150  1436  1436 D RegisteredComponentCache: Collect Tech packages for Knox
,09-06 19:16:37.160  1436  1436 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:16:37.160  2907  7600 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-06 19:16:37.160  1479  1479 D MenuAppsGridFragment: onResume
,09-06 19:16:37.160  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-06 19:16:37.170  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-06 19:16:37.170  1013  1052 D PackageManager: delete codoeFile: 
,09-06 19:16:37.180  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-06 19:16:37.190  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.190  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.190  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.190  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.190  1013  1052 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
09-06 19:16:37.190  1013  1052 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,09-06 19:16:37.200  7617  7617 E Zygote  : MountEmulatedStorage(),
,09-06 19:16:37.200  7617  7617 E Zygote  : v2,
09-06 19:16:37.200  7617  7617 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:37.200  7617  7617 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:37.200  7617  7617 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:37.210  1013  1038 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7617 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:16:37.210  7617  7617 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:37.210  1013  1052 D PackageManager: result of delete: 1{166951780}
,09-06 19:16:37.210  7617  7617 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:37.210  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,09-06 19:16:37.210  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.210  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.210  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.210  7601  7601 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:37.210  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.210  1013  1025 I TactileAssist: enable value -1
09-06 19:16:37.210  1013  1025 I TactileAssist: internal enable value -1
09-06 19:16:37.210  1013  1025 I TactileAssist: intensity value -1
09-06 19:16:37.210  1013  1025 I TactileAssist: saveAppList value true
09-06 19:16:37.210  7601  7601 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:37.210  7575  7575 D AndroidRuntime: Shutting down VM
,09-06 19:16:37.220  1013  1025 I TactileAssist: List of disabled apps :
,09-06 19:16:37.230  7626  7626 E Zygote  : MountEmulatedStorage()
,09-06 19:16:37.230  7626  7626 E Zygote  : v2
09-06 19:16:37.230  7626  7626 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:37.230  7626  7626 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:37.230  7626  7626 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:37.230  7626  7626 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:37.230  7626  7626 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:37.240  1013  1130 D ActivityManager: handle home activity for 0
09-06 19:16:37.240  1013  1038 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7626 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:16:37.240  1013  1130 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-06 19:16:37.240  1013  1130 D KnoxTimeoutHandler: post home show event for user 0
09-06 19:16:37.240  1013  1130 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 19:16:37.240  1013  1130 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:16:37.240  1013  1130 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-06 19:16:37.240  1479  1479 D Launcher.HomeView: onPause
09-06 19:16:37.240  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-06 19:16:37.240  7617  7617 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:37.240  7617  7617 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:37.250  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:37.260  1013  1052 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-06 19:16:37.260  1013  1052 D PackageManager: userId{-1}
09-06 19:16:37.260  1013  1052 D PackageManager: andCode{true}
,09-06 19:16:37.260  7626  7626 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:37.260  7626  7626 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:37.270  2907  7600 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-06 19:16:37.270  1013  1052 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-06 19:16:37.280  1013  1052 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.280  1013  1052 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.280  1013  1052 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.280  1013  1052 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.280   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,09-06 19:16:37.280  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:37.290  1013  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,09-06 19:16:37.290  1013  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-06 19:16:37.290  7647  7647 E Zygote  : MountEmulatedStorage()
09-06 19:16:37.290  7647  7647 E Zygote  : v2
09-06 19:16:37.290  7647  7647 I libpersona: KNOX_SDCARD checking this for 10003
09-06 19:16:37.290  7647  7647 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:37.290  7647  7647 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:37.290  2907  7600 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
09-06 19:16:37.300  7647  7647 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:37.300  7647  7647 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-06 19:16:37.300  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-06 19:16:37.300  2907  7600 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END,
,09-06 19:16:37.300  1013  1494 D InputDispatcher: Focus entered window: 1479
,09-06 19:16:37.300  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:16:37.300  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 19:16:37.310  1479  1479 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-06 19:16:37.310  1013  1013 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-06 19:16:37.310  1013  1013 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-06 19:16:37.310  1013  1052 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7647 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-06 19:16:37.310  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-06 19:16:37.310  1013  1013 V EnterpriseBillingPolicy: uID is 10171
09-06 19:16:37.310  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 19:16:37.310  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-06 19:16:37.310  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 19:16:37.310  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 19:16:37.310  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 19:16:37.310  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-06 19:16:37.310  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 19:16:37.320  1013  1013 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 19:16:37.320  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-06 19:16:37.320  1013  1013 V EnterpriseBillingPolicy: uID is 10171
09-06 19:16:37.320  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 19:16:37.320  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-06 19:16:37.320  1013  3354 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-06 19:16:37.320  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{3d718ec9 token=android.os.BinderProxy@19c34d6b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
09-06 19:16:37.320  1479  1479 D Launcher.HomeView: onStop
,09-06 19:16:37.320  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 19:16:37.320  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 19:16:37.320  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 19:16:37.320  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-06 19:16:37.320  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 19:16:37.320  1013  1130 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-06 19:16:37.330  1013  1013 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-06 19:16:37.330  2907  2907 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-06 19:16:37.330  1013  7660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:16:37.330  7601  7601 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-06 19:16:37.330  1013  1156 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,09-06 19:16:37.330  1013  1130 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6690 uid 10171
,09-06 19:16:37.340  1013  1469 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-06 19:16:37.340  7601  7601 D elm:15121: ELMEngine.ELMEngine( context ).
,09-06 19:16:37.340  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.340  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.340  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.340  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.340  1876  1876 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-06 19:16:37.350  7617  7617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-06 19:16:37.350  7601  7601 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-06 19:16:37.360  7665  7665 E Zygote  : MountEmulatedStorage(),
09-06 19:16:37.360  7665  7665 I libpersona: KNOX_SDCARD checking this for 10048
09-06 19:16:37.360  7665  7665 E Zygote  : v2
,09-06 19:16:37.360  7665  7665 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:37.360  7665  7665 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:37.360  7665  7665 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:37.360  7665  7665 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-06 19:16:37.360  7626  7626 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
09-06 19:16:37.360  7647  7647 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:37.360  7647  7647 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:37.360  1013  1469 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7665 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,09-06 19:16:37.370  1013  4422 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-06 19:16:37.370  1013  4422 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-06 19:16:37.370  1013  4422 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:16:37.370  1013  4422 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:37.370  1013  4422 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-06 19:16:37.380  1013  1568 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-06 19:16:37.380  1013  1568 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-06 19:16:37.380  1013  1568 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:37.380  1013  1568 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:37.380  1013  1568 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-06 19:16:37.380  7601  7601 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-06 19:16:37.390  1013  1478 D SecContentProvider2: uri = -1 selection = getSealedState
09-06 19:16:37.390  1013  1478 D SecContentProvider2: mCursor = null
09-06 19:16:37.390  7626  7626 I PopupuiReceiver_KNOX: getSealedState : true
09-06 19:16:37.390  1013  1130 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
09-06 19:16:37.390  1013  1130 D SecContentProvider2: mCursor = null
,09-06 19:16:37.390  1013  4116 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-06 19:16:37.390  7626  7626 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
09-06 19:16:37.400  1013  1359 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
09-06 19:16:37.400  1013  1359 D SecContentProvider2: mCursor = null
,09-06 19:16:37.400  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.400  7626  7626 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
09-06 19:16:37.400  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.400  7626  7626 D PopupuiReceiver: Action package removed
09-06 19:16:37.400  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.400  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.410  7601  7601 D elm:15121: ElmAgentService : onCreate()
,09-06 19:16:37.410  7601  7675 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-06 19:16:37.410  7601  7675 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-06 19:16:37.410  7601  7675 D elm:15121: MDMBridge.getInstance()
,09-06 19:16:37.410  7601  7675 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-06 19:16:37.410  7601  7675 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-06 19:16:37.420  7665  7665 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-06 19:16:37.420  7682  7682 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:37.420  7665  7665 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:37.420  7682  7682 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:37.420  7575  7575 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-06 19:16:37.420  1013  4116 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7682 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:16:37.420  7682  7682 E Zygote  : MountEmulatedStorage()
09-06 19:16:37.420  1013  1038 W ActivityManager: mDVFSHelper.release()
09-06 19:16:37.420  7682  7682 E Zygote  : v2
09-06 19:16:37.420  7682  7682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:16:37.430  1013  1043 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{355abd81 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:148150
,09-06 19:16:37.430  7682  7682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 19:16:37.430  7682  7682 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:16:37.440  1013  1013 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,09-06 19:16:37.450  1013  4116 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-06 19:16:37.450  1013  1013 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-06 19:16:37.450  1013  1013 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-06 19:16:37.450  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
09-06 19:16:37.450  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-06 19:16:37.450  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.450  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.450  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.450  1013  4116 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.470  1013  1037 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-06 19:16:37.470  7699  7699 E Zygote  : MountEmulatedStorage()
09-06 19:16:37.470  7699  7699 E Zygote  : v2
09-06 19:16:37.470  7699  7699 I libpersona: KNOX_SDCARD checking this for 10145
09-06 19:16:37.470  7699  7699 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:37.470  7699  7699 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:37.470  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:37.470  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:37.480  7699  7699 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:37.480  1013  4116 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7699 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:37.480  7682  7682 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:37.480  7682  7682 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:37.480  1173  1173 I StatusBar: Icon Only
09-06 19:16:37.480  7699  7699 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:16:37.480  1173  1173 D PanelView: There is/are notification(s) 
,09-06 19:16:37.490  1013  1013 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 19:16:37.490  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:37.490  7601  7601 D elm:15121: ElmAgentService : onDestroy().
,09-06 19:16:37.490  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.490  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.490  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.490  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.490  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:37.490  1013  1037 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-06 19:16:37.490  1013  1037 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:37.490  1013  1037 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:16:37.500  7710  7710 E Zygote  : MountEmulatedStorage()
09-06 19:16:37.500  7710  7710 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:16:37.500  7710  7710 E Zygote  : v2
09-06 19:16:37.500  7710  7710 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:37.510  7710  7710 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-06 19:16:37.510  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:37.510  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:16:37.510  7710  7710 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:37.510  7710  7710 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-06 19:16:37.510  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:37.510  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:16:37.510  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:37.520  7699  7699 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:37.520  7699  7699 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:37.520  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:37.520  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:16:37.520  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:37.520  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:16:37.520  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:16:37.530  1013  1013 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7710 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:16:37.530   309   309 I art     : Explicit concurrent mark sweep GC freed 8755(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 24.030ms
,09-06 19:16:37.530  1013  1037 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-06 19:16:37.530  1013  1037 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-06 19:16:37.540  7710  7710 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:37.540  7710  7710 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:37.550  1013  1037 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:37.550  1013  1124 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-06 19:16:37.550   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 791us total 20.618ms
,09-06 19:16:37.560  7665  7665 D Compatibility: onReceive() it will make start service
,09-06 19:16:37.560  1013  1569 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 19:16:37.560  1013  1569 D SecContentProvider2: mCursor = null
,09-06 19:16:37.570  1013  4422 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-06 19:16:37.570  1013  4422 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-06 19:16:37.570  1013  4422 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:16:37.570  1013  4422 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:16:37.570  1013  4422 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-06 19:16:37.580  1013  1494 I ActivityManager: Killing 7088:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-06 19:16:37.580   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 705us total 21.074ms
,09-06 19:16:37.580  1013  1494 I ActivityManager: Killing 7074:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-06 19:16:37.580  7682  7682 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:16:37.580  1013  1494 I ActivityManager: Killing 7108:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-06 19:16:37.590  1013  1469 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-06 19:16:37.590  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.590  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.590  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.590  1013  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.600  7731  7731 E Zygote  : MountEmulatedStorage()
09-06 19:16:37.600  7731  7731 E Zygote  : v2
09-06 19:16:37.600  7731  7731 I libpersona: KNOX_SDCARD checking this for 10052
09-06 19:16:37.600  7731  7731 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:37.600  7731  7731 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:37.600  7710  7710 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-06 19:16:37.600  7710  7710 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-06 19:16:37.600  7710  7710 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
09-06 19:16:37.600  7731  7731 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:37.600  7665  7730 D Compatibility: onHandleIntent(),
09-06 19:16:37.600  7665  7730 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
09-06 19:16:37.610  7731  7731 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 19:16:37.610  7665  7730 D Compatibility: found: 2
,09-06 19:16:37.610  1013  1469 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7731 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-06 19:16:37.620  7665  7730 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-06 19:16:37.620  7665  7730 D Compatibility: skipping ResolveInfo{1fa8b03b com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-06 19:16:37.620  7665  7730 D Compatibility: considering ResolveInfo{29273358 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-06 19:16:37.620  7665  7730 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-06 19:16:37.630  7710  7710 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-06 19:16:37.630  7710  7710 I PCWCLIENTTRACE_PushUtil: sales region : global
09-06 19:16:37.630  7710  7710 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-06 19:16:37.630  7710  7710 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-06 19:16:37.630  1013  1569 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-06 19:16:37.630  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.630  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.630  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.630  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.630  7665  7730 D Compatibility: enabling receiver ResolveInfo{565dcb1 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-06 19:16:37.640  7731  7731 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:37.640  7665  7730 D Compatibility: enabling receiver ResolveInfo{37831596 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-06 19:16:37.640  7731  7731 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:37.640  7682  7682 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-06 19:16:37.650  7747  7747 E Zygote  : MountEmulatedStorage()
09-06 19:16:37.650  7747  7747 E Zygote  : v2
09-06 19:16:37.650  7747  7747 I libpersona: KNOX_SDCARD checking this for 10029
09-06 19:16:37.650  7747  7747 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:37.650  7747  7747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:37.650  7747  7747 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:16:37.650  1013  1359 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0,
09-06 19:16:37.650  1013  1569 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7747 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-06 19:16:37.650  1013  1359 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
09-06 19:16:37.650  1013  1569 I ActivityManager: Killing 7042:com.android.chrome/u0a77 (adj 15): empty #21
09-06 19:16:37.650  7747  7747 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:16:37.660  7665  7730 D Compatibility: enabling receiver ResolveInfo{1b681517 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-06 19:16:37.660  1013  1494 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:16:37.670  7665  7730 D Compatibility: enabling receiver ResolveInfo{8882d04 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-06 19:16:37.670  7699  7699 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-06 19:16:37.670  7699  7699 D ThemeInfoUtil: isCurrentFestival = false
,09-06 19:16:37.670  7665  7730 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-06 19:16:37.680  1013  1569 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-06 19:16:37.680  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.680  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.680  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.680  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.690  7747  7747 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:16:37.690  7747  7747 D ActivityThread: Added TimaKeyStore provider
09-06 19:16:37.700  7762  7762 E Zygote  : MountEmulatedStorage()
09-06 19:16:37.700  7762  7762 E Zygote  : v2
09-06 19:16:37.700  7762  7762 I libpersona: KNOX_SDCARD checking this for 10087
,09-06 19:16:37.700  7762  7762 I libpersona: KNOX_SDCARD not a persona
,09-06 19:16:37.700  7762  7762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:37.700  7762  7762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:16:37.700  7762  7762 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 19:16:37.700  1013  1569 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7762 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
09-06 19:16:37.700  1013  1569 I ActivityManager: Killing 6956:com.google.android.talk/u0a102 (adj 15): empty #21
09-06 19:16:37.700  1013  1569 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-06 19:16:37.710  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.710  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.710  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:16:37.710  1013  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:16:37.730  7762  7762 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:16:37.730  7762  7762 D ActivityThread: Added TimaKeyStore provider
,09-06 19:16:37.740  1013  1124 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-06 19:16:37.740  1013  1124 V NetworkStats: updateIfacesLocked()
09-06 19:16:37.740  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.740  1013  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:16:37.740  1013  1124 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-06 19:16:37.740  1013  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:16:37.750  1013  1569 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7778 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,09-06 19:16:37.750  7778  7778 E Zygote  : MountEmulatedStorage()
09-06 19:16:37.750  7778  7778 I libpersona: KNOX_SDCARD checking this for 10148
09-06 19:16:37.750  7778  7778 E Zygote  : v2
09-06 19:16:37.750  7778  7778 I libpersona: KNOX_SDCARD not a persona
09-06 19:16:37.750  1013  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.750  1013  1569 I ActivityManager: Killing 7149:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
09-06 19:16:37.750  7778  7778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:16:37.750  1013  1124 V NetworkStats: performPollLocked() took 6ms
,09-06 19:16:37.750  7778  7778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:16:37.750  7778  7778 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:16:37.770  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.770  1013  1124 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-06 19:16:37.770  1013  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:16:37.770  1013  1227 I ActivityManager: Killing 7171:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
09-06 19:16:37.780  1173  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 19:16:37.780  1013  1124 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-06 19:16:37.780  4757  6753 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 19:16:37.780  1173  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 19:16:37.780  4757  6753 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295

```
