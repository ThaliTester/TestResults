#### Test 81492074ffbc155_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-16 17:43:20.507  1018  3350 D SSRM:n  : SIOP:: AP = 310
,--------- beginning of main
08-16 17:43:21.247   288   288 E SMD     : DCD OFF
08-16 17:43:21.327  6709  6709 D AndroidRuntime: 
08-16 17:43:21.327  6709  6709 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 17:43:21.337  6709  6709 D AndroidRuntime: CheckJNI is OFF
08-16 17:43:21.337  6709  6709 D AndroidRuntime: readGMSProperty: start
08-16 17:43:21.337  6709  6709 D AndroidRuntime: readGMSProperty: already setted!!
08-16 17:43:21.337  6709  6709 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 17:43:21.337  6709  6709 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 17:43:21.337  6709  6709 D AndroidRuntime: readGMSProperty: end
08-16 17:43:21.337  6709  6709 D AndroidRuntime: addProductProperty: start
08-16 17:43:21.467  6709  6709 E AffinityControl: AffinityControl: registerfunction enter
08-16 17:43:21.497  6709  6709 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 17:43:21.507  1018  1496 E PersonaManagerService: inState():  stateMachine is null !!
08-16 17:43:21.507  1018  1496 I PersonaManagerService: PersonaId don't exist
08-16 17:43:21.507  1018  1496 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-16 17:43:21.507  1018  1496 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 17:43:21.527  1018  1496 W ActivityManager: mDVFSHelper.acquire()
08-16 17:43:21.527   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-16 17:43:21.537   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-16 17:43:21.537  1018  1496 D FocusedStackFrame: Set to : 0
08-16 17:43:21.547  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:21.547  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:21.547  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:21.547  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:21.557  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 17:43:21.557  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-16 17:43:21.557  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 17:43:21.557  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 17:43:21.557  6720  6720 E Zygote  : MountEmulatedStorage()
08-16 17:43:21.557  6720  6720 E Zygote  : v2
08-16 17:43:21.557  6720  6720 I libpersona: KNOX_SDCARD checking this for 10171
08-16 17:43:21.557  6720  6720 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:21.557   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-16 17:43:21.557  6720  6720 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:43:21.567  1018  1496 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6720 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 17:43:21.567  1018  1496 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-16 17:43:21.567  1018  1496 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 17:43:21.567  6720  6720 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:43:21.567  6720  6720 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-16 17:43:21.577  1018  1496 D InputDispatcher: Focused application set to: xxxx
08-16 17:43:21.587  1018  1496 D InputDispatcher: Focus left window: 1498
08-16 17:43:21.587  6709  6709 D AndroidRuntime: Shutting down VM
08-16 17:43:21.587   305   305 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 20.828ms
08-16 17:43:21.587  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:43:21.587  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 17:43:21.597  6720  6720 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:43:21.597  6720  6720 D ActivityThread: Added TimaKeyStore provider
08-16 17:43:21.607   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.440ms
08-16 17:43:21.617  1018  1480 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-16 17:43:21.617  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-16 17:43:21.617   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 18.268ms
08-16 17:43:21.627  1018  1018 V ActivityManager: Display changed displayId=0
08-16 17:43:21.637  1018  1480 D PersonaManager: isKioskContainerExistOnDevice
08-16 17:43:21.647  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-16 17:43:21.667   258   449 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-16 17:43:21.667   258   451 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-16 17:43:21.677  1498  1498 V ActivityThread: updateVisibility : ActivityRecord{572067c token=android.os.BinderProxy@146ac271 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-16 17:43:21.677  1498  1498 D Launcher: onTrimMemory. Level: 20
08-16 17:43:21.747  6720  6720 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-16 17:43:21.767  6720  6720 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 4693-4696)
08-16 17:43:21.767  6720  6720 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-16 17:43:21.787  6709  6709 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-16 17:43:21.797  6720  6720 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {15618cfd}
,08-16 17:43:21.797  6720  6720 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-16 17:43:21.797  6720  6720 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 17:43:21.837  6720  6720 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-16 17:43:21.847  6720  6720 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:43:21.847  6720  6720 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 17:43:21.877  6720  6720 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:43:21.877  6720  6720 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:43:21.877  6720  6720 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:43:21.877  6720  6720 I Adreno-EGL: Local Branch: 
08-16 17:43:21.877  6720  6720 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:43:21.877  6720  6720 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:43:21.877  6720  6720 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 17:43:21.957  6720  6720 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 17:43:21.967  6720  6720 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-16 17:43:21.967  6720  6720 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-16 17:43:21.977  6720  6720 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-16 17:43:21.977  6720  6720 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-16 17:43:22.097  6720  6720 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:43:22.107  6720  6720 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 17:43:22.117  6720  6720 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-16 17:43:22.117  6720  6720 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-16 17:43:22.127  6720  6720 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-16 17:43:22.127  6720  6720 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:43:22.127  6720  6720 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:43:22.147  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{2730208f u0 com.test.thalitest/.MainActivity t2}
,08-16 17:43:22.197  6720  6760 D OpenGLRenderer: Render dirty regions requested: true
,08-16 17:43:22.197  1018  1494 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-16 17:43:22.207  1018  1494 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 17:43:22.207  1018  1494 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 17:43:22.207  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 17:43:22.207  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 17:43:22.207  6720  6747 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-16 17:43:22.217  6720  6720 V ActivityThread: updateVisibility : ActivityRecord{3dcd4ddd token=android.os.BinderProxy@9f5aac6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-16 17:43:22.217  6720  6720 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null,
08-16 17:43:22.217  6720  6720 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-16 17:43:22.227   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-16 17:43:22.247  1018  1506 D InputDispatcher: Focus entered window: 6720
,08-16 17:43:22.247  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 17:43:22.247  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:43:22.247  6720  6720 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 17:43:22.247  6720  6760 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 17:43:22.257  6720  6760 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-16 17:43:22.257  6720  6760 D OpenGLRenderer: Enabling debug mode 0
,08-16 17:43:22.277  1018  1031 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 17:43:22.287  1180  1180 I StatusBar: Icon Only
08-16 17:43:22.287  1180  1180 D PanelView: There is/are notification(s) 
,08-16 17:43:22.287  1018  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:43:22.297  1018  1048 I ActivityManager: Displayed Component not be shown by security: +652ms (total +750ms)
08-16 17:43:22.297  1018  1048 W ActivityManager: mDVFSHelper.release()
08-16 17:43:22.297  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2730208f u0 com.test.thalitest/.MainActivity t2} time:105223
,08-16 17:43:22.297   258   449 I SurfaceFlinger: id=12 Removed uhalitest (7/9),
08-16 17:43:22.297  6720  6720 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-16 17:43:22.297  6720  6720 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9f5aac6 time:105228
08-16 17:43:22.297   258   451 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-16 17:43:22.327  1844  1844 I SamsungIME: getCurrentCandidateView
,08-16 17:43:22.407  6720  6720 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6720
,08-16 17:43:22.427  1844  1844 D SamsungIME: Dismiss ExpandCandiate
,08-16 17:43:22.577  6720  6720 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 17:43:22.597  1844  1844 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 17:43:22.637  1844  1844 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 17:43:22.647  1844  1844 I SamsungIME: KeybaordView init() : load resources
,08-16 17:43:22.667  6720  6766 D jxcore_app_log: JniHelper::setJavaVM(0xb81f32b0), pthread_self() = -1200089344
,08-16 17:43:22.667  1844  1844 I SamsungIME: getCurrentKeyboard
08-16 17:43:22.667  1844  1844 I SamsungIME: getTextKeyboard
,08-16 17:43:22.677  6720  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 17:43:22.677  6720  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 17:43:22.677  6720  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 17:43:22.677  6720  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 17:43:22.677  6720  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 17:43:22.677  6720  6766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d7c489b added. We now have 1 listener(s)
,08-16 17:43:22.687  6720  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-16 17:43:22.687  6720  6766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-16 17:43:22.687  6720  6766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:43:22.687  6720  6766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:43:22.687  1844  1844 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 17:43:22.697  6720  6766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e45176 added. We now have 1 listener(s)
,08-16 17:43:22.697  6720  6766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:22.697  6720  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:43:22.697  6720  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 17:43:22.697  6720  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 17:43:22.697  6720  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 17:43:22.697  6720  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 17:43:22.707  6720  6766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:22.707  6720  6766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-16 17:43:22.717  6720  6766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 17:43:22.717  6720  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:22.717  6720  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:22.717  6720  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:22.717  6720  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:22.717  6720  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:22.717  6720  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:22.717  6720  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:22.717  6720  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:22.717  6720  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 17:43:22.717  6720  6766 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:22.717  6720  6766 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 17:43:22.717  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:22.717  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:22.747  6720  6720 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 17:43:23.177  6720  6773 W jxcore-log: Initializing JXcore engine
08-16 17:43:23.177  6720  6773 W jxcore-log: JXcore engine is ready
,08-16 17:43:23.227  1018  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:43:23.227  1018  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-16 17:43:23.227  1018  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-16 17:43:23.227  1018  1497 D BatteryService: stay LED for fully charged
08-16 17:43:23.227  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-16 17:43:23.227  1018  1018 I MotionRecognitionService: Plugged
08-16 17:43:23.227  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-16 17:43:23.227  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:43:23.227  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
08-16 17:43:23.237  1989  1989 E audit   : type=1400 msg=audit(1471362203.227:205): avc:  denied  { ioctl } for  pid=6773 comm="Thread-1240" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 17:43:23.237  1989  1989 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:43:23.237  1989  1989 E audit   : type=1300 msg=audit(1471362203.227:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f0fb8f8 items=0 ppid=305 ppcomm=main pid=6773 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1240" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-16 17:43:23.237  1989  1989 E audit   : type=1320 msg=audit(1471362203.227:205): 
,08-16 17:43:23.237  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-16 17:43:23.237  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 17:43:23.247  3166  3166 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 17:43:23.247  3166  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:43:23.247  6720  6773 W jxcore-log: Starting JXcore engine
,08-16 17:43:23.257  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-16 17:43:23.257  1180  1180 D SViewCoverView: level :100 plugged : 2
,08-16 17:43:23.257  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-16 17:43:23.257  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-16 17:43:23.257  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-16 17:43:23.357  6720  6773 W jxcore-log: Platform android
08-16 17:43:23.357  6720  6773 W jxcore-log: 
08-16 17:43:23.357  6720  6773 W jxcore-log: Process ARCH arm
08-16 17:43:23.357  6720  6773 W jxcore-log: 
,08-16 17:43:23.537  6720  6773 I jxcore-log: JXcore Cordova bridge is ready!
08-16 17:43:23.537  6720  6773 I jxcore-log: 
,08-16 17:43:23.537  6720  6773 W jxcore-log: JXcore engine is started
,08-16 17:43:23.537  6720  6766 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 17:43:23.537  6720  6720 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 17:43:24.247   288   288 E SMD     : DCD OFF,
,08-16 17:43:25.427  1018  1329 E Watchdog: !@Sync 3
,08-16 17:43:26.227   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-16 17:43:26.237   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-16 17:43:27.247   288   288 E SMD     : DCD OFF
,08-16 17:43:30.247   288   288 E SMD     : DCD OFF
,08-16 17:43:30.267  1018  1050 I PowerManagerService: [PWL] Off : 50s ago,
,08-16 17:43:30.537  1018  3350 D SSRM:n  : SIOP:: AP = 330,
,08-16 17:43:31.237   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:43:31.597  1018  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-16 17:43:32.237   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:43:32.887  5622  5622 D FactoryTest: Not factory mode
,08-16 17:43:32.887  5622  5622 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-16 17:43:32.887  5622  5622 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-16 17:43:32.887  5622  5622 D MTPRx   : still no open session command from host, so toast
,08-16 17:43:32.897  5622  5622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-16 17:43:32.897  5622  5622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-16 17:43:32.897  5622  5622 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115826,
08-16 17:43:32.897  1018  1136 E PersonaManagerService: inState():  stateMachine is null !!
08-16 17:43:32.897  1018  1136 I PersonaManagerService: PersonaId don't exist
08-16 17:43:32.897  1018  1136 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-16 17:43:32.907  1018  1136 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-16 17:43:32.907  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:32.907  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:32.907  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-16 17:43:32.907  1018  1136 W ActivityManager: mDVFSHelper.acquire()
,08-16 17:43:32.937  1018  1136 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:43:32.957  1018  1136 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 17:43:32.957  1018  1136 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 17:43:32.957  1018  1136 D InputDispatcher: Focused application set to: xxxx
,08-16 17:43:32.957  1018  1136 D InputDispatcher: Focus left window: 6720
,08-16 17:43:32.957  5622  5622 E MTPRx   : started activity for popup
,08-16 17:43:32.957  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:43:32.957  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:43:32.987  5622  5622 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-16 17:43:32.987  5622  5622 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-16 17:43:32.987  5622  5622 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 17:43:32.987  5622  5622 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:43:32.987  5622  5622 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:43:32.987  5622  5622 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:43:33.017  5622  5622 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-16 17:43:33.017  1018  1496 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 17:43:33.017  1018  1496 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 17:43:33.017  1018  1496 D InputDispatcher: Focused application set to: xxxx
,08-16 17:43:33.017  1018  1496 D InputDispatcher: Focus entered window: 6720
,08-16 17:43:33.027  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 17:43:33.027  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:43:33.027  1018  1506 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 17:43:33.027  1018  1506 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@33b829fe attribute=null, token = android.os.BinderProxy@2b4ed14e
,08-16 17:43:33.067  5622  5622 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-16 17:43:33.077  5622  5622 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-16 17:43:33.077  5622  5622 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-16 17:43:33.097  6720  6720 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 17:43:33.097  6720  6720 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-16 17:43:33.097  6720  6720 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 17:43:33.097  6720  6720 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-16 17:43:33.107  1018  1308 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-16 17:43:33.107  1018  1308 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-16 17:43:33.107  1018  1308 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-16 17:43:33.107  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-16 17:43:33.107  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 17:43:33.117  6720  6720 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:43:33.117  6720  6720 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 17:43:33.117  6720  6720 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2b9017a2 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1972b09f, 16908290=android.view.AbsSavedState$1@1972b09f}, android:focusedViewId=100}]}]
08-16 17:43:33.117  6720  6720 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 17:43:33.127  6720  6720 V ActivityThread: updateVisibility : ActivityRecord{3dcd4ddd token=android.os.BinderProxy@9f5aac6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 17:43:33.127  6720  6720 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 17:43:33.127  6720  6720 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 17:43:33.127  6720  6720 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9f5aac6 time:116052
,08-16 17:43:33.127  1018  1136 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:43:33.237   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:33.247   288   288 E SMD     : DCD OFF
,08-16 17:43:33.287  1018  3639 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:43:33.287  1018  3639 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-16 17:43:33.287  1018  3639 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-16 17:43:33.287  1018  3639 D BatteryService: stay LED for fully charged
,08-16 17:43:33.287  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:43:33.287  1018  1018 I MotionRecognitionService: Plugged
,08-16 17:43:33.287  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:43:33.287  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:43:33.297  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
08-16 17:43:33.297  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 17:43:33.297  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 17:43:33.307  3166  3166 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 17:43:33.307  3166  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:43:33.317  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-16 17:43:33.317  1180  1180 D SViewCoverView: level :100 plugged : 2
,08-16 17:43:33.317  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-16 17:43:33.317  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-16 17:43:33.317  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-16 17:43:34.237   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:35.237   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:43:35.907  1018  1043 W ActivityManager: mDVFSHelper.release()
,08-16 17:43:36.167  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-16 17:43:36.167  6720  6773 I jxcore-log: 
,08-16 17:43:36.167  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-16 17:43:36.167  6720  6773 I jxcore-log: 
,08-16 17:43:36.177  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:36.177  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:36.177  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:36.177  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:36.177  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:36.177  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:36.177  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:36.177  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:36.177  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:43:36.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 17:43:36.177  6720  6773 I jxcore-log: 
,08-16 17:43:36.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-16 17:43:36.177  6720  6773 I jxcore-log: 
,08-16 17:43:36.237   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-16 17:43:36.247   288   288 E SMD     : DCD OFF
,08-16 17:43:36.607  6720  6773 D ExecuteNativeTests: Running unit tests,
,08-16 17:43:36.697  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:43:36.697  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c added. We now have 2 listener(s)
,08-16 17:43:36.697  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-16 17:43:36.697  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:43:36.697  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:43:36.697  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:36.697  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 added. We now have 2 listener(s)
08-16 17:43:36.697  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:36.697  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:43:36.707  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:36.707  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:36.707  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:36.707  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:36.707  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:36.707  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:36.707  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:36.707  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:36.707  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:36.707  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:43:36.707  6720  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:36.717  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:36.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 17:43:36.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:43:36.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:43:36.717  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:36.717  6720  6773 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 17:43:36.717  6720  6773 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:43:36.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:43:36.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:43:36.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:43:36.717  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:36.717  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:36.717  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:43:36.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:36.717  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:36.717  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:36.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:43:36.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c removed from the list
08-16 17:43:36.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:36.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 removed from the list
08-16 17:43:36.717  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:36.717  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:36.717  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:36.717  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:36.727  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:36.727  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:36.727  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:36.727  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:36.727  6720  6773 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-16 17:43:36.727  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:36.727  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:36.727  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:43:36.727  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:36.727  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:36.727  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:36.727  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:36.727  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:36.727  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:36.727  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:36.727  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:36.727  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:36.727  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:36.737  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:36.737  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:43:36.737  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:36.737  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:36.737  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:43:36.737  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:36.737  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:36.737  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:36.737  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:36.737  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:36.737  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:36.737  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:36.737  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:36.737  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:36.737  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:36.737  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:36.737  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:36.737  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:36.737  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:36.737  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:36.737  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:36.737  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:36.737  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:36.747  6720  6773 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:43:36.747  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:36.747  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:36.747  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:36.747  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:36.747  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:36.747  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:36.747  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:36.747  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:36.747  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:36.747  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:36.747  6720  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:43:36.747  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:43:36.747  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:43:36.747  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:43:36.747  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:36.747  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:43:36.757  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:36.757  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:43:36.757  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:36.767  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:43:36.767  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 17:43:36.767  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 17:43:36.777  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 17:43:36.777  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:43:36.777  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:43:36.777  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:43:36.787  3166  3178 D BtGatt.GattService: registerClient() - UUID=a8593967-bcf6-4b02-987a-34feb8a08d90
,08-16 17:43:36.827  3166  3264 D BtGatt.GattService: onClientRegistered() - UUID=a8593967-bcf6-4b02-987a-34feb8a08d90, clientIf=6
,08-16 17:43:36.837  6720  6732 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:43:36.837  3166  3349 D BtGatt.GattService: start scan with filters
,08-16 17:43:36.837  3166  3268 D BtGatt.ScanManager: handling starting scan
,08-16 17:43:36.837  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:43:36.837  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 17:43:36.837  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 17:43:36.837  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:43:36.847  3166  3268 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:36.847  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:43:36.847  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:43:36.847  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:36.847  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:43:36.847  3166  3264 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-16 17:43:36.847  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:36.847  3166  3268 D BtGatt.ScanManager: allow scan with filters
08-16 17:43:36.847  3166  3268 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:43:36.847  3166  3268 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-16 17:43:36.857  6720  6773 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:43:36.857  3166  3264 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:43:36.857  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:36.857  3166  3268 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:43:36.857  3166  3268 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:43:36.857  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:36.857  6720  6773 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:43:36.867  3166  3264 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 17:43:36.867  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:36.867  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:43:36.867  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:36.867  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:43:36.867  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:36.867  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:36.867  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:43:36.867  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:43:36.867  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:36.867  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:43:36.867  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:43:36.867  3166  3175 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:43:36.867  3166  3178 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:43:36.867  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:43:36.867  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:43:36.867  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:43:36.867  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:43:36.867  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:43:36.867  3166  3264 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 17:43:36.867  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:36.877  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:36.877  3166  3268 D BtGatt.ScanManager: filter size is 1
,08-16 17:43:36.877  3166  3268 D BtGatt.ScanManager: delete FilterIndex - 3
08-16 17:43:36.877  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:43:36.877  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:43:36.877  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:43:36.877  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:36.877  3166  3264 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:43:36.877  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:36.887  3166  3268 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:43:36.887  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:36.887  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:36.887  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:36.887  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:36.887  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:36.887  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:36.887  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:36.887  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:36.887  6720  6773 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 17:43:36.887  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:43:36.887  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:36.887  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:36.887  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:36.887  3166  3264 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 17:43:36.887  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:36.897  3166  3268 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-16 17:43:36.897  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:36.897  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:36.897  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:36.897  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:36.897  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:36.897  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:36.897  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:36.897  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:36.897  3166  3264 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:43:36.897  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:36.897  1018  1096 V AlarmManager: waitForAlarm result :4
,08-16 17:43:36.907  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:36.907  6720  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:43:36.907  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:43:36.907  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:43:36.907  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:43:36.907  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:36.907  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:43:36.907  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:36.917  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:36.917  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:43:36.927  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:43:36.927  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:43:36.927  2015  2015 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-16 17:43:36.937  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:43:36.937  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 17:43:36.937  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:43:36.947  3166  3272 D BtGatt.GattService: registerClient() - UUID=57b0bb57-7a13-48b1-8bfa-dc8e7e1ace75
,08-16 17:43:36.957  1018  1508 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:36.957  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-16 17:43:36.967  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:36.967  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:36.967  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:36.987  3166  3264 D BtGatt.GattService: onClientRegistered() - UUID=57b0bb57-7a13-48b1-8bfa-dc8e7e1ace75, clientIf=6
,08-16 17:43:36.987  6720  6734 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:43:36.987  3166  3349 D BtGatt.GattService: start scan with filters
,08-16 17:43:36.987  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:43:36.987  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:43:36.987  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 17:43:36.987  3166  3268 D BtGatt.ScanManager: handling starting scan
,08-16 17:43:36.987  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:43:36.987  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:36.997  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:43:36.997  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:36.997  3166  3264 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:43:36.997  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:36.997  3166  3268 D BtGatt.ScanManager: allow scan with filters
08-16 17:43:36.997  3166  3268 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:43:36.997  3166  3268 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-16 17:43:36.997  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:43:36.997  3166  3264 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-16 17:43:36.997  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:36.997  3166  3268 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:43:36.997  3166  3268 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:43:37.007  6720  6773 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:43:37.007  3166  3264 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:43:37.007  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:37.007  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:37.007  6720  6773 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:43:37.007  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.007  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:43:37.007  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.007  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:43:37.007  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:37.007  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:37.007  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:43:37.007  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:43:37.007  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:43:37.007  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:43:37.007  3166  3264 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:43:37.007  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:37.007  3166  3178 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:43:37.017  3166  3272 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:43:37.017  3166  3268 D BtGatt.ScanManager: filter size is 1
,08-16 17:43:37.017  3166  3268 D BtGatt.ScanManager: delete FilterIndex - 4
,08-16 17:43:37.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:43:37.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:43:37.017  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:43:37.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:43:37.017  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:43:37.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:37.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:43:37.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:43:37.017  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:43:37.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:37.017  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:37.017  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.017  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:37.017  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.017  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.017  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.017  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.017  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.027  3166  3264 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:43:37.027  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:37.027  3166  3268 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:43:37.027  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.027  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.027  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.027  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:37.027  6720  6773 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:43:37.027  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:37.027  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:37.027  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:37.027  3166  3264 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:43:37.027  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:37.027  3166  3268 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-16 17:43:37.037  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:37.037  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:37.037  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:37.037  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:37.037  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:37.037  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:37.037  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:37.037  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:37.037  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:37.037  6720  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:37.037  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:43:37.037  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:43:37.037  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:43:37.037  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:37.037  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:43:37.037  3166  3264 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:43:37.037  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:37.037  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:37.037  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:37.047  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:43:37.047  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:43:37.047  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:43:37.047  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:43:37.047  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:43:37.047  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:43:37.047  3166  3349 D BtGatt.GattService: registerClient() - UUID=f6454b82-226e-4300-8eb6-aab166ee3b04
,08-16 17:43:37.057  2015  2015 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-16 17:43:37.077  1018  1096 V AlarmManager: waitForAlarm result :4
,08-16 17:43:37.077  1018  1096 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.097  3166  3264 D BtGatt.GattService: onClientRegistered() - UUID=f6454b82-226e-4300-8eb6-aab166ee3b04, clientIf=6
,08-16 17:43:37.097  6720  6734 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:43:37.097  3166  3175 D BtGatt.GattService: start scan with filters
,08-16 17:43:37.097  3166  3268 D BtGatt.ScanManager: handling starting scan
,08-16 17:43:37.097  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-16 17:43:37.097  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:43:37.097  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:43:37.097  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:43:37.107  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:43:37.107  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:43:37.107  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:37.107  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:43:37.107  1018  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:37.107  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.net.NetworkReportService; callingUser = 0; userId(target) = 0
08-16 17:43:37.107  3166  3264 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:43:37.107  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:37.107  3166  3268 D BtGatt.ScanManager: allow scan with filters
08-16 17:43:37.107  3166  3268 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:43:37.107  3166  3268 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-16 17:43:37.107  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.107  6720  6773 I io.jxcore.node.ConnectionHelper: start: OK
08-16 17:43:37.107  1018  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.107  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.117  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.117  6720  6773 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:43:37.117  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.117  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:43:37.117  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.117  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:43:37.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:37.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:37.117  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:43:37.117  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:43:37.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:43:37.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:43:37.117  3166  3264 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:43:37.117  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:37.117  3166  3268 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:43:37.117  3166  3268 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:43:37.117  3166  3349 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:43:37.117  3166  3175 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:43:37.117  3166  3264 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:43:37.117  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:37.117  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:43:37.117  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:43:37.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:43:37.117  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:43:37.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:43:37.127  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:37.127  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:43:37.127  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:43:37.127  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:43:37.127  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:37.127  3166  3264 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:43:37.127  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:37.127  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:43:37.127  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:37.127  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:37.127  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:37.127  6720  6773 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:43:37.127  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.127  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:43:37.127  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.127  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.137  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:37.137  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.137  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.137  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.137  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:43:37.137  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.137  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.137  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.137  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.137  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.137  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.137  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:37.137  6720  6773 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-16 17:43:37.137  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.137  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.137  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.147  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.147  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.147  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.147  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.147  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.147  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.147  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.147  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.147  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.147  3166  3268 D BtGatt.ScanManager: filter size is 1
08-16 17:43:37.147  3166  3268 D BtGatt.ScanManager: delete FilterIndex - 5
,08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.147  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:37.147  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:43:37.147  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.147  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.147  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.147  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.147  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.147  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.147  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.147  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.147  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.147  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.147  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.147  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.147  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:37.147  6720  6773 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 17:43:37.147  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.147  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.147  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.147  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.147  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.147  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.147  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.147  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.147  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.147  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.147  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.147  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.147  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.147  3166  3264 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:43:37.147  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:37.147  3166  3268 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.157  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:37.157  6720  6773 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 17:43:37.157  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.157  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.157  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.157  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.157  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.157  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.157  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.157  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.157  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.157  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.157  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.157  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.157  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:37.157  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:37.157  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 17:43:37.157  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:43:37.157  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:43:37.157  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.157  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.157  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:43:37.157  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.157  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.157  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.157  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.157  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.157  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.157  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.157  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.157  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.157  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.157  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.157  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.157  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.157  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.157  3166  3264 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:43:37.157  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:37.157  3166  3268 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:43:37.167  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.167  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.167  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.167  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:37.167  6720  6773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:37.167  6720  6773 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 17:43:37.167  6720  6773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:37.167  6720  6773 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:43:37.167  6720  6773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 17:43:37.167  6720  6773 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:43:37.167  6720  6773 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 17:43:37.167  6720  6773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 17:43:37.167  6720  6773 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:43:37.167  6720  6773 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 17:43:37.167  6720  6773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-16 17:43:37.167  6720  6773 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:43:37.167  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 17:43:37.167  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-16 17:43:37.167  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 17:43:37.167  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 17:43:37.167  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-16 17:43:37.167  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 17:43:37.167  3166  3264 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:43:37.167  6720  6773 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 17:43:37.167  3166  3264 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:37.167  6720  6773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:37.167  6720  6773 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-16 17:43:37.167  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.167  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.167  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.167  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-16 17:43:37.167  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.167  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.167  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads,
08-16 17:43:37.167  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.167  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.167  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:37.167  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.167  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.167  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.167  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.167  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.167  6720  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1304)
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.177  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.177  6720  6773 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 17:43:37.177  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.177  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:43:37.177  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.177  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.177  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.177  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:43:37.177  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.177  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.177  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.177  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.177  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.177  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.177  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.177  6720  6787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1304
,08-16 17:43:37.177  6720  6773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 17:43:37.177  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.177  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.177  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.177  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.177  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.177  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.177  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:37.177  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.177  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.177  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.177  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.177  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:43:37.177  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.177  6720  6773 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 17:43:37.177  6720  6773 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 17:43:37.177  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:43:37.177  6720  6773 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 17:43:37.177  6720  6773 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:43:37.177  6720  6773 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 17:43:37.177  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:43:37.177  6720  6773 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 17:43:37.177  6720  6773 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:43:37.177  6720  6773 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:43:37.177  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:43:37.177  6720  6773 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 17:43:37.177  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:37.177  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.177  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.177  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.177  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.177  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.177  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.177  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.177  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:43:37.177  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.177  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.177  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:43:37.177  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:43:37.187  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.187  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.187  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.187  6720  6786 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.187  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.187  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.187  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.187  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.187  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list,
08-16 17:43:37.187  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.187  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.187  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:37.187  6720  6720 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
,08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:37.187  6720  6720 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:43:37.187  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.187  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:37.187  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.187  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:37.187  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:37.187  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.187  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.187  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.187  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.187  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.187  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.187  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.187  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.187  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.197  6720  6786 D BluetoothSocket: connect(): myUserId = 0
08-16 17:43:37.197  6720  6786 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:43:37.197  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.197  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.197  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.197  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:37.197  6720  6773 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 17:43:37.197  6720  6773 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:43:37.197  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:43:37.197  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:43:37.197  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.197  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.197  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.197  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.197  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.197  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.197  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.197  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.197  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.197  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.197  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.197  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.197  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.197  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.197  6720  6789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 17:43:37.197  6720  6789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 17:43:37.197  6720  6720 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 17:43:37.197  3166  3178 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:43:37.197  6720  6786 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-16 17:43:37.197  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.197  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.197  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.197  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
,08-16 17:43:37.207  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:37.207  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.207  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.207  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.207  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.207  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.207  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.207  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.207  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.207  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.207  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.207  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.207  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.207  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.207  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.207  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.207  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:43:37.207  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.207  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:37.207  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:37.207  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:37.207  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:37.207  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.207  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.207  6720  6773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3a921c not in the list
08-16 17:43:37.207  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.207  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.207  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:37.207  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.207  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:37.207  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:37.207  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:37.207  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:37.207  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:37.207  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:37.207  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1cee25 not in the list
08-16 17:43:37.207  6720  6773 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 17:43:37.207  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:43:37.207  6720  6773 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 17:43:37.207  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:43:37.207  6720  6773 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 17:43:37.207  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 17:43:37.217  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:43:37.217  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-16 17:43:37.217  6720  6773 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 17:43:37.217  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:43:37.217  6720  6773 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 17:43:37.217  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:43:37.217  6720  6773 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 17:43:37.217  6720  6773 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-16 17:43:37.217  6720  6773 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 17:43:37.217  6720  6773 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 17:43:37.217  6720  6773 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 17:43:37.217  6720  6773 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 17:43:37.217  6720  6773 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 17:43:37.217  6720  6773 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-16 17:43:37.217  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:37.217  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e54ea7f added. We now have 2 listener(s)
,08-16 17:43:37.217  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:37.217  6720  6773 D BluetoothAdapter: enable()
,08-16 17:43:37.217  6720  6773 D BluetoothAdapter: enable(): BT is already enabled..!
,08-16 17:43:37.227  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 17:43:37.227  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:43:37.227  1018  1030 D SecContentProvider2: mCursor = null
,08-16 17:43:37.227  1018  1030 D WifiService: setWifiEnabled: true pid=6720, uid=10171
,08-16 17:43:37.227  1018  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=6720, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:43:37.237  1018  1030 W WifiService: Failed getting userId using ActivityManagerNative,
08-16 17:43:37.237  1018  1030 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6720, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:43:37.237  1018  1030 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 17:43:37.237  1018  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:43:37.237  1018  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:43:37.237  1018  1030 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:43:37.237  1018  1030 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 17:43:37.237  1018  1030 D SettingsProvider: name = wifi_on
,08-16 17:43:37.237  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:37.237  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6d4ba4c added. We now have 3 listener(s)
08-16 17:43:37.237  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:37.247  4781  4781 D ConnectivityManager: CallingUid : 10011, CallingPid : 4781
,08-16 17:43:37.247  1018  1497 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 17:43:37.247  1018  1130 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-16 17:43:37.247  1018  1130 D ConnectivityService: apparently satisfied.  currentScore=60
08-16 17:43:37.247  4781  6790 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:43:37.247  1018  1130 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-16 17:43:37.247  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:37.247  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c1eaa95 added. We now have 4 listener(s)
08-16 17:43:37.247  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:37.247  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:43:37.257  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@154637aa added. We now have 5 listener(s)
08-16 17:43:37.257  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:37.257  1018  1495 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 17:43:37.257  1018  1495 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:43:37.257  1018  1495 D SecContentProvider2: mCursor = null
,08-16 17:43:37.257  1018  1495 D WifiService: setWifiEnabled: false pid=6720, uid=10171
08-16 17:43:37.257  1018  1495 D SettingsProvider: name = wifi_on
,08-16 17:43:37.267  6720  6773 D BluetoothAdapter: disable()
,08-16 17:43:37.267  1018  1128 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 17:43:37.267  1392  1392 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 17:43:37.267  1392  1392 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-16 17:43:37.267  1392  1392 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-16 17:43:37.267  1392  1392 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-16 17:43:37.277  1018  1496 D SettingsProvider: name = bluetooth_on
,08-16 17:43:37.277  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:37.287  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:37.297  3166  3261 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-16 17:43:37.297  3166  3261 D BluetoothAdapterProperties: Setting state to 13
08-16 17:43:37.297  3166  3261 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:43:37.297  3166  3261 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:43:37.297  3166  3261 D BluetoothAdapterService: updateAdapterState state is 13
,08-16 17:43:37.297  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 17:43:37.297  1018  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-16 17:43:37.297  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.297  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-16 17:43:37.297  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:37.297  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:37.297  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:37.297  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:37.297  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:37.297  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:37.297  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:37.297  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:37.297  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 17:43:37.297  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:37.297  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:37.297  3166  3261 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:37.307  1018  1127 D WifiP2pService: InactiveState{ what=147461 }
08-16 17:43:37.297  3166  3261 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-16 17:43:37.307  1018  1127 D WifiP2pService: P2pEnabledState{ what=147461 }
08-16 17:43:37.297  3166  3261 D BluetoothAdapterService: terminating service from this receiver
08-16 17:43:37.307  1018  1127 D WifiP2pService: DefaultState{ what=147461 }
08-16 17:43:37.297  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.297  3166  3166 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-16 17:43:37.297  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:37.297  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:37.297  3166  3166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7e38867, channel: 19, state: LISTENING
08-16 17:43:37.297  3166  3166 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@7e38867, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3af4ba6f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@161aa614mSocket: android.net.LocalSocket@f6afebd impl:android.net.LocalSocketImpl@2d5a3cb2 fd:FileDescriptor[74]
08-16 17:43:37.297  3166  3166 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@f6afebd impl:android.net.LocalSocketImpl@2d5a3cb2 fd:FileDescriptor[74]
08-16 17:43:37.307  1392  1392 I wpa_supplicant: nl80211: Received scan results (16 BSSes)
08-16 17:43:37.307  3166  3261 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 17:43:37.307  3166  3261 D BluetoothAdapterProperties: mDiscovering is false,
08-16 17:43:37.307  1018  1128 E WifiNative-wlan0: do suspend true
08-16 17:43:37.307  1018  1030 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-16 17:43:37.307  1292  1292 D BluetoothPbap: Proxy object disconnected
08-16 17:43:37.307  1292  1292 D PbapServerProfile: Bluetooth service disconnected
,08-16 17:43:37.307  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:37.307  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:37.307  6720  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:37.307  3166  3261 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 17:43:37.317  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:37.317  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:37.317  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:37.317  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:37.317  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:37.317  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:37.317  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:37.317  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:37.317  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:37.317  3166  3264 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:43:37.317  3166  3264 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:43:37.317  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:37.317  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:43:37.327  3166  3261 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 17:43:37.327  3166  3261 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-16 17:43:37.327  3166  3261 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-16 17:43:37.327  3166  3261 E bt-btif : cmd socket is not created
,08-16 17:43:37.327  3166  5199 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 17:43:37.327  3166  3284 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-16 17:43:37.327  3166  3284 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 17:43:37.327  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:37.327  3166  3261 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 17:43:37.327  6720  6786 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@18b92f38, channel: -1, state: INIT
08-16 17:43:37.327  6720  6786 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@18b92f38, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@308c5b11, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2fa82476mSocket: android.net.LocalSocket@2ef7aa77 impl:android.net.LocalSocketImpl@46e06e4 fd:FileDescriptor[106]
08-16 17:43:37.327  6720  6786 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ef7aa77 impl:android.net.LocalSocketImpl@46e06e4 fd:FileDescriptor[106]
08-16 17:43:37.327  6720  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1304)
,08-16 17:43:37.327  3166  3284 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:37.327  3166  3284 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:37.327  3166  3284 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 17:43:37.337  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:37.337  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:37.337  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:37.337  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:37.337  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:37.337  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:37.337  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:37.337  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:37.337  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:37.337  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:37.337  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:43:37.337  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:37.347  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:37.347  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-16 17:43:37.357  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:43:37.357  1844  1844 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:37.357  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:37.357  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:43:37.357  1180  1180 D BluetoothTile:  getBluetoothState : 13
,08-16 17:43:37.357  3166  3166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3060f80, channel: 5, state: LISTENING
08-16 17:43:37.357  3166  3166 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3060f80, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bdb637c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f4dc9b9mSocket: android.net.LocalSocket@5ab71fe impl:android.net.LocalSocketImpl@f2f1d5f fd:FileDescriptor[76]
08-16 17:43:37.357  3166  3166 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@5ab71fe impl:android.net.LocalSocketImpl@f2f1d5f fd:FileDescriptor[76]
,08-16 17:43:37.357  1018  1495 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:37.367  1018  1508 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:43:37.367  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:43:37.367  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:43:37.367  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:37.367  3166  3166 I BtOppRfcommListener: stopping Accept Thread
08-16 17:43:37.367  3166  3166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@287ca3ac, channel: 12, state: LISTENING
08-16 17:43:37.367  3166  3166 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@287ca3ac, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@be20426, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39f84875mSocket: android.net.LocalSocket@1448b00a impl:android.net.LocalSocketImpl@3a52307b fd:FileDescriptor[80]
08-16 17:43:37.367  3166  3166 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1448b00a impl:android.net.LocalSocketImpl@3a52307b fd:FileDescriptor[80]
,08-16 17:43:37.367  3166  5199 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 17:43:37.367  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:37.367  1018  3640 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:37.367  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.377  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:37.377  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:37.377  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:43:37.377  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.377  1018  3640 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:37.377  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.387  3166  3166 V BluetoothOppManager: cleanUp...
,08-16 17:43:37.397  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:37.397  1018  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 17:43:37.397  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.397  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.397  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:37.397  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:43:37.397  4781  6793 W DriveInitializer: Background init thread started
,08-16 17:43:37.407  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:37.407  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:37.417  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:37.417  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 17:43:37.417  1018  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-16 17:43:37.417  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:37.417  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:37.417  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:37.417  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:37.417   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-16 17:43:37.417   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:37.417  4781  6793 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-16 17:43:37.437  6799  6799 E Zygote  : MountEmulatedStorage(),
08-16 17:43:37.437  6799  6799 E Zygote  : v2
08-16 17:43:37.437  6799  6799 I libpersona: KNOX_SDCARD checking this for 10055
08-16 17:43:37.437  6799  6799 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:37.437  1018  1495 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6799 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
08-16 17:43:37.437  1018  1308 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-16 17:43:37.437  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.447  6799  6799 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:37.447  6799  6799 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:37.447  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
08-16 17:43:37.447  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:43:37.447  6799  6799 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:43:37.447   278  1017 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:43:37.447  4781  5056 D NetworkUsageDbReporter: Started reporting usage
,08-16 17:43:37.447  2015  3027 V NativeCrypto: Read error: ssl=0xb86f3788: I/O error during system call, Connection timed out
,08-16 17:43:37.457  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:43:37.457  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:43:37.457  1018  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:37.457  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-16 17:43:37.457  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:37.457  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 17:43:37.457  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.457  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.457  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.457  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.457  2015  3027 V NativeCrypto: SSL shutdown failed: ssl=0xb86f3788: I/O error during system call, Broken pipe
08-16 17:43:37.457  1018  1127 D WifiP2pService: InactiveState{ what=131204 }
08-16 17:43:37.457  1018  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-16 17:43:37.457  2015  3027 E GCM     : Wifi connection closed with errorCode 20
,08-16 17:43:37.467  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling,
,08-16 17:43:37.467  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-16 17:43:37.467  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:37.467  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:37.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:37.467  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 17:43:37.467  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:37.467  1018  1308 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-16 17:43:37.467  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-16 17:43:37.467  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.467  1018  1152 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:37.467  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.467  1018  1308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.467  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.477  1018  1494 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-16 17:43:37.477  1018  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 17:43:37.487  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:43:37.487  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
,08-16 17:43:37.487  1018  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-6ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:37.487  1018  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-6ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:37.487  1018  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 17:43:37.487  1018  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:37.487  1018  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-16 17:43:37.487  1018  1727 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
,08-16 17:43:37.487  1018  1727 I qtaguid : Tagging socket 348 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
08-16 17:43:37.487  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 17:43:37.497  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 17:43:37.497  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-16 17:43:37.497  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:43:37.497  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-16 17:43:37.497  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:37.497  1018  1048 D WifiDisplayController: disconnect
08-16 17:43:37.497  1018  1048 D WifiDisplayController: updateConnection
08-16 17:43:37.497  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:37.497  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:43:37.497  1018  1127 D WifiP2pService: P2pDisablingState
08-16 17:43:37.497  1018  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 17:43:37.497  6799  6799 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:43:37.497  1018  1127 D WifiP2pService: p2p socket connection lost
08-16 17:43:37.497  6799  6799 D ActivityThread: Added TimaKeyStore provider
08-16 17:43:37.497  1018  1127 D WifiP2pService: P2pDisabledState
08-16 17:43:37.497  1018  1128 E WifiNative-wlan0: do suspend true
08-16 17:43:37.497  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 17:43:37.497  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:43:37.497  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:43:37.497  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 17:43:37.507  1018  1727 I qtaguid : Untagging socket 348
08-16 17:43:37.507  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 17:43:37.507  1018  1727 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:43:37.517  1018  1136 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:43:37.517  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:43:37.527  3166  3284 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:37.527  3166  3284 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:37.527  3166  3284 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:43:37.527  3166  3284 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:37.527  3166  3284 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:37.527  3166  3284 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:43:37.527  3166  3284 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:37.527  3166  3284 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:37.527  3166  3284 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:43:37.527  3166  3284 W bt-btif : ag scb idx 1 not allocated
08-16 17:43:37.527  3166  3284 W bt-btif : ag scb idx 2 not allocated
08-16 17:43:37.527  3166  3284 E bt-btif : BTA AG is already disabled, ignoring ...
,08-16 17:43:37.527  3166  3326 I bt_userial_mct: exiting userial_read_thread
08-16 17:43:37.527  3166  3326 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-16 17:43:37.527  3166  3264 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 17:43:37.527  3166  3286 I bt_vendor: hw_epilog_process,
,08-16 17:43:37.527  3166  3264 D bt_userial_mct: userial_close
08-16 17:43:37.527  3166  3264 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0,
,08-16 17:43:37.557  2015  2015 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 17:43:37.557  6799  6799 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-16 17:43:37.587  6799  6799 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-16 17:43:37.597  6799  6799 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-16 17:43:37.597  6799  6799 D UserAnalysis: Create SecureDbHelper
,08-16 17:43:37.607  6799  6799 D IntelligenceServiceApplication: onCreate()
,08-16 17:43:37.617  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-16 17:43:37.617  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:37.617  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:37.617  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:37.617  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1190
08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: keeping row: 959
08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 10200
08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: keeping row: 957
08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 14277
,08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: keeping row: 956
08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 5915
08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: keeping row: 955
08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 110504
,08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: keeping row: 953
,08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 83895
08-16 17:43:37.617  1018  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: keeping row: 952
08-16 17:43:37.617  1018  1127 D WifiP2pService: DefaultState{ what=143375 }
08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 333231
08-16 17:43:37.617  4781  5056 D NetworkUsageDbReporter: keeping row: 951
08-16 17:43:37.617  6799  6799 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-16 17:43:37.627  6828  6828 E Zygote  : MountEmulatedStorage()
,08-16 17:43:37.627  6828  6828 I libpersona: KNOX_SDCARD checking this for 10105
08-16 17:43:37.627  6828  6828 E Zygote  : v2
08-16 17:43:37.627  6828  6828 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:37.637  6828  6828 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:43:37.637  1018  1480 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6828 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-16 17:43:37.637  6828  6828 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:43:37.637  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-16 17:43:37.637  6828  6828 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-16 17:43:37.637  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:37.637  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:37.637  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.637  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.637  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.637  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:37.647  6799  6799 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-16 17:43:37.647  6799  6799 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-16 17:43:37.657  4781  5056 D NetworkUsageDbReporter: Finished reporting usage.
,08-16 17:43:37.657   278  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 17:43:37.657   278  1013 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-16 17:43:37.657   278  1017 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:43:37.657  1018  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-16 17:43:37.657  1018  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-16 17:43:37.657  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:37.657  1018  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-16 17:43:37.657  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:37.657  1018  1130 V NetworkStats: updateIfacesLocked()
08-16 17:43:37.657  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:43:37.657  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:43:37.657  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 17:43:37.657  1392  1392 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-16 17:43:37.667  1018  1130 V NetworkStats: performPollLocked() took 7ms
08-16 17:43:37.667  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:37.667  6828  6828 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:37.667  6828  6828 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:37.677  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 17:43:37.677  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:37.677  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.677  1018  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-16 17:43:37.677  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.677  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.677  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:37.677  1180  1717 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 17:43:37.677  4781  6790 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-16 17:43:37.677  1018  1130 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
08-16 17:43:37.677  1468  1468 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 17:43:37.677  1468  1468 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:43:37.677  1018  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-16 17:43:37.677  1018  1130 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-16 17:43:37.677  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 17:43:37.687  1018  1727 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-10ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:43:37.687  1018  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 17:43:37.687  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 17:43:37.687  6720  6720 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:43:37.707  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:37.707  1018  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:37.707  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 17:43:37.707  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:43:37.707  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:37.707  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.707  1180  1180 D HotspotTile: onReceive : 0, 0
08-16 17:43:37.707  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.707  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:43:37.707  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.707  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:37.707  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:37.707  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-16 17:43:37.717  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:37.717  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:37.717  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:37.717  1018  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-16 17:43:37.717  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-16 17:43:37.727  1018  1131 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:43:37.727  1018  1125 V NetworkStats: updateIfacesLocked()
08-16 17:43:37.727  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:37.727  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:37.727  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:37.727  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:37.727  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:37.727  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:37.727  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:37.727  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:37.727  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:37.727  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:37.727  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:37.727  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:37.727  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:43:37.727  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
08-16 17:43:37.727  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 17:43:37.727  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 17:43:37.727  1180  1180 D StatusBar.NetworkController: updateDataNetType()
08-16 17:43:37.727  1180  1180 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 17:43:37.727  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-16 17:43:37.727  1018  1506 I art     : Explicit concurrent mark sweep GC freed 47985(2MB) AllocSpace objects, 21(384KB) LOS objects, 33% free, 24MB/36MB, paused 8.065ms total 204.902ms
08-16 17:43:37.727  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:37.727  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:43:37.727  1018  1308 I ActivityManager: Killing 6420:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-16 17:43:37.727  1018  1130 D ConnectivityService: nai.networkMonitor.doQuit()
,08-16 17:43:37.727  1018  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-16 17:43:37.727  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:43:37.727  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:43:37.727  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:43:37.737  1018  1125 V NetworkStats: performPollLocked() took 12ms
08-16 17:43:37.737  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:37.737  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 17:43:37.737  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:37.737  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 17:43:37.737  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-16 17:43:37.737  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-16 17:43:37.737  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:37.737  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:43:37.737  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.737  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.737  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:37.737  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:37.737  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:37.737  1018  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-16 17:43:37.737  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:37.737  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:37.737  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:37.737  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:37.737  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:37.737  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:37.737  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:37.737  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:37.737  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:37.737  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:37.737  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:37.747  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:37.747  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:37.747  3166  3264 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 17:43:37.747  3166  3264 I bt_vendor: bluetooth satus is on
08-16 17:43:37.747  3166  3264 I bt_vendor: bt-vendor : resetting BT status
08-16 17:43:37.747  3166  3264 I bt_vendor: Starting hciattach daemon
08-16 17:43:37.747  3166  3264 I bt_vendor: try to set false
,08-16 17:43:37.747  3166  3264 I bt_vendor: Starting hciattach daemon
08-16 17:43:37.747  3166  3264 I bt_vendor: try to set false
,08-16 17:43:37.747  3166  3264 I bt_vendor: cleanup
08-16 17:43:37.747  3166  3284 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-16 17:43:37.747  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:37.747  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-16 17:43:37.747  3166  3264 I GKI_LINUX: GKI_exit_task 0 done
08-16 17:43:37.747  3166  3264 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-16 17:43:37.757  3166  3261 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 17:43:37.757  3166  3261 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:43:37.757  3166  3261 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-16 17:43:37.757  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 17:43:37.757  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 17:43:37.757  3166  3261 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 17:43:37.757  1018  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:37.757  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.757  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.757  1018  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:37.757  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:37.767  3166  3166 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:43:37.767  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:43:37.767  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:37.767  3166  3261 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:37.767  3166  3166 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:43:37.767  3166  3166 D BtGatt.GattService: stop()
08-16 17:43:37.767  3166  3166 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:43:37.777  1392  1392 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:43:37.777  1018  3639 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:37.777  1018  3639 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.777  1018  3639 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.777  1018  3639 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:37.777  1018  3639 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:37.777  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:43:37.777  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:37.777  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:37.777  3166  3261 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:37.777  3166  3166 D HeadsetService: Received stop request...Stopping profile...
,08-16 17:43:37.787  1018  3640 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:37.787  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.787  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.787  1018  3640 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:37.787  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:37.787  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 17:43:37.787  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:37.787  3166  3261 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:43:37.787  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:37.787  4781  6793 W DriveInitializer: Background init thread ended
,08-16 17:43:37.797  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 17:43:37.797  1292  1292 D HeadsetProfile: Bluetooth service disconnected
08-16 17:43:37.797  1018  3639 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:37.797  1018  3639 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.797  1018  3639 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.797  1018  3639 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:37.797  1018  3639 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:37.797  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:43:37.797  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 17:43:37.797  3166  3261 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:43:37.797  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:37.797  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.797  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.797  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:37.797  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:37.807  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 17:43:37.807  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 17:43:37.807  3166  3261 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 17:43:37.807  1018  1308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:37.807  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.807  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.807  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:37.807  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:37.807  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:37.807  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:37.817  3166  3261 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:37.817  1018  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:37.817  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.817  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.817  1018  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:37.817  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:37.817  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 17:43:37.817  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 17:43:37.817  3166  3261 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:43:37.817  1018  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:37.817  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.817  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.817  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:37.817  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:37.827  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:43:37.827  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:43:37.827  1392  1392 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 17:43:37.827  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:43:37.827  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:37.827  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:43:37.827  3166  3261 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:37.827  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:37.827  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:43:37.827  3166  3261 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:37.827  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:43:37.827  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 17:43:37.827  3166  3261 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:43:37.827  3166  3261 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:43:37.827  3166  3261 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 17:43:37.827  3166  3261 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:43:37.827  3166  3261 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 17:43:37.827  3166  3166 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-16 17:43:37.827  3166  3166 D A2dpService: Received stop request...Stopping profile...
,08-16 17:43:37.837  3166  3275 D A2dpStateMachine: Exit Disconnected: -1
,08-16 17:43:37.837  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:37.837  1018  1018 D BluetoothA2dp: Proxy object disconnected
,08-16 17:43:37.837  3166  3166 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-16 17:43:37.837  3166  3166 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:37.837  3166  3166 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 17:43:37.837  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 17:43:37.837  3166  3166 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 17:43:37.837  3166  3166 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 17:43:37.837  1292  1292 D BluetoothA2dp: Proxy object disconnected
08-16 17:43:37.837  1292  1292 D A2dpProfile: Bluetooth service disconnected
08-16 17:43:37.837  3166  3166 D HidService: Received stop request...Stopping profile...
08-16 17:43:37.837  3166  3166 D HidService: Stopping Bluetooth HidService,
08-16 17:43:37.837  3166  3166 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:43:37.837  3166  3166 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-16 17:43:37.837  3166  3166 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:43:37.837  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:37.847  3166  3166 D HealthService: Received stop request...Stopping profile...
,08-16 17:43:37.847  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:37.847  1292  1292 D BluetoothInputDevice: Proxy object disconnected
08-16 17:43:37.847  3166  3166 D PanService: Received stop request...Stopping profile...
08-16 17:43:37.847  1292  1292 D HidProfile: Bluetooth service disconnected
08-16 17:43:37.847  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:37.847  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:43:37.847  1392  1392 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-16 17:43:37.847  1392  1392 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-16 17:43:37.847  1392  1392 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-16 17:43:37.847  1392  1392 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-16 17:43:37.847  1392  1392 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-16 17:43:37.857  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:37.857  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:37.857  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:37.857  1292  1292 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:43:37.857  1292  1292 D PanProfile: Bluetooth service disconnected
,08-16 17:43:37.857  1018  1131 D Tethering: InitialState.processMessage what=4
,08-16 17:43:37.857  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:43:37.857  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:37.857  3166  3166 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 17:43:37.857  1018  1131 E Tethering: No numeric data
,08-16 17:43:37.857  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:43:37.857  1018  1131 D Tethering: clearTetheredNotification()
08-16 17:43:37.857  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:37.857  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:37.857  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:37.857  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:37.867  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:37.867  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:37.867  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:43:37.867  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:37.867  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:43:37.867  1180  1180 D HotspotTile: updateTetherState():false, false
,08-16 17:43:37.867  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:37.867  1018  1125 V NetworkStats: performPollLocked() took 3ms
08-16 17:43:37.867  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:37.867  3166  3166 D SapService: Received stop request...Stopping profile...
08-16 17:43:37.867  3166  3166 D SapService: Stopping Bluetooth SapService
08-16 17:43:37.867  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:37.867  1292  1292 D BluetoothMap: Proxy object disconnected
08-16 17:43:37.867  1292  1292 D MapProfile: Bluetooth service disconnected
,08-16 17:43:37.877  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:37.877  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:37.877  3166  3166 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-16 17:43:37.877  3166  3166 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:37.877  3166  3166 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 17:43:37.877  3166  3166 D BluetoothA2dp: Proxy object disconnected
08-16 17:43:37.877  3166  3166 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-16 17:43:37.877  3166  3276 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-16 17:43:37.877  3166  3166 I GKI_LINUX: GKI_exit_task 2 done
08-16 17:43:37.877  3166  3166 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-16 17:43:37.877  3166  3166 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 17:43:37.877  3166  3166 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:37.877  3166  3166 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:37.877  3166  3166 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 17:43:37.877  3166  3166 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:37.877  3166  3166 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:37.877  3166  3166 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:43:37.877  3166  3166 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-16 17:43:37.877  3166  3166 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 17:43:37.877  3166  3166 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:37.877  3166  3166 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:37.877  3166  3166 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:43:37.877  3166  3166 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 17:43:37.877  3166  3166 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-16 17:43:37.877  3166  3166 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:43:37.877  3166  3166 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-16 17:43:37.877  3166  3166 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-16 17:43:37.877  3166  3166 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 17:43:37.877  3166  3166 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-16 17:43:37.887  1292  1292 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-16 17:43:37.887  1292  1292 D SapProfile: Bluetooth service disconnected
,08-16 17:43:37.887  3166  3261 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 17:43:37.887  3166  3261 D BluetoothAdapterProperties: Setting state to 10
08-16 17:43:37.887  3166  3261 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 17:43:37.887  3166  3261 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:43:37.887  3166  3261 D BluetoothAdapterService: updateAdapterState state is 10
,08-16 17:43:37.887  3166  3261 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:37.887  3166  3261 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 17:43:37.887  3166  3261 I BluetoothAdapterState: Entering OffState
,08-16 17:43:37.887  3166  3349 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:43:37.897   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-16 17:43:37.897   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:37.897  6828  6853 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
08-16 17:43:37.897  2015  2192 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:37.897  2015  2192 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:37.907  1180  1624 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:37.907  1180  1624 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:37.907  1292  1301 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:43:37.907  1292  1300 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:37.907  1292  1300 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:37.907  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 17:43:37.907  6720  6732 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:37.907  6720  6732 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:43:37.907  6720  6732 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-16 17:43:37.907  6720  6732 D BluetoothLeAdvertiser: Exit stop advertising
08-16 17:43:37.907  6720  6732 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 17:43:37.907  6720  6732 D BluetoothLeScanner: Exiting stopAllScan
08-16 17:43:37.907   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb71b37c8
08-16 17:43:37.907   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-16 17:43:37.907   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-16 17:43:37.907   273   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1222953672)
,08-16 17:43:37.927  1292  1300 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 17:43:37.927  1292  1301 D Bluetoothsap: onBluetoothStateChange: up=false
,08-16 17:43:37.927  1292  1301 D Bluetoothsap: Unbinding service...
,08-16 17:43:37.927  1440  1461 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:37.927  1440  1461 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:37.937  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:37.937  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:37.937  3166  3175 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:37.937  3166  3175 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:37.947  1468  3313 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:37.947  1468  3313 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:37.947  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:43:37.947  1292  1301 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 17:43:37.957  1448  1489 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:37.957   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-16 17:43:37.957   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:37.957  1448  1489 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:37.957  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:37.957  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:37.957  1292  1300 D BluetoothInputDevice: onBluetoothStateChange: up=false,
08-16 17:43:37.957  6828  6853 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-16 17:43:37.957  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:37.957  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:37.967  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:37.967  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:37.967  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:37.967  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:37.967  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 17:43:37.977  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:37.977  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:37.977  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:37.977  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 17:43:37.987   273   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-16 17:43:37.987   273   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-16 17:43:37.987   273   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1222953672) wakelock released: 1, error no: 0
08-16 17:43:37.987   273   340 I rmt_storage: 
08-16 17:43:37.987  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:37.987   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb71b37c8
08-16 17:43:37.987  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:37.987  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:37.987  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:37.987  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:37.987  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 17:43:37.987  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-16 17:43:37.987  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:43:37.997  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:37.997  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:37.997  1180  1180 D BluetoothAdapter: 180112583: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:37.997  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:43:37.997  1180  1724 D BluetoothAdapter: 180112583: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:37.997  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:37.997  1180  1180 D BluetoothTile:  getBluetoothState : 10
,08-16 17:43:37.997  1180  1724 D BluetoothAdapter: 180112583: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:37.997  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:38.007  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:38.007  1180  1180 D BluetoothAdapter: 180112583: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:38.007  1018  1497 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:43:38.007  1180  1180 D BluetoothAdapter: 180112583: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:38.007  1844  1844 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-16 17:43:38.007  1018  3639 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false,
08-16 17:43:38.007  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:38.007  2015  2197 D BluetoothAdapter: 88134581: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:38.007  2015  2197 D BluetoothAdapter: 88134581: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:38.017  1392  1392 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:43:38.017  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:38.017  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:38.017  1018  1308 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:38.017  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:43:38.017  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:38.017  3166  3264 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 17:43:38.017  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:38.017  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:38.017  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:38.027  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:38.027  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:38.027  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.027  1018  1308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.027  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:43:38.027  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:38.027  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 17:43:38.027  3166  3166 I GKI_LINUX: GKI_exit_task 1 done
08-16 17:43:38.027  3166  3166 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 17:43:38.027  3166  3166 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 17:43:38.027  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:38.027  1468  1468 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:38.027  3166  3166 I art     : System.exit called, status: 0
08-16 17:43:38.027  3166  3166 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 17:43:38.027  1468  1468 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:38.037  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:43:38.037  1018  1030 I ActivityManager: Process com.android.bluetooth (pid 3166)(adj 0) has died(29,728)
,08-16 17:43:38.057  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:38.057  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:38.057  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:38.057  1392  1392 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 17:43:38.137  6828  6828 D StrictMode: StrictMode policy violation; ~duration=237 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:38.137  6828  6828 D StrictMode: StrictMode policy violation; ~duration=231 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:38.137  6828  6828 D StrictMode: StrictMode policy violation; ~duration=230 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:38.137  6828  6828 D StrictMode: StrictMode policy violation; ~duration=228 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.e.b(PG:170)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:38.137  6828  6828 D StrictMode: StrictMode policy violation; ~duration=223 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.k.d(PG:583)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.e.b(PG:170)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:38.137  6828  6828 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:38.147  1018  1495 I ActivityManager: Killing 6316:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-16 17:43:38.137  6828  6828 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:38.137  6828  6828 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:38.137  6828  6828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:38.147  2015  2015 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-16 17:43:38.147  2015  2015 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-16 17:43:38.157  1018  1494 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:38.157  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:43:38.157  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.157  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.157  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:43:38.157  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:43:38.157  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:43:38.167  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:43:38.167  2205  2205 I Hs20UtilService: Starting #8
08-16 17:43:38.167  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-16 17:43:38.167  2205  2222 I Hs20UtilService: Message received 5007
08-16 17:43:38.167  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-16 17:43:38.167  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:43:38.167  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:38.167  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:38.167  1292  2321 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 17:43:38.177  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:38.177  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:43:38.177  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:38.177  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:38.177  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:38.177  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:38.177  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:38.177  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-16 17:43:38.177  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:43:38.177  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:38.177  1180  1180 D HotspotTile: onReceive : 1, 0
08-16 17:43:38.177  2015  2197 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:43:38.177  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:38.177  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:38.187  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:38.187  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 17:43:38.187  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:43:38.187  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:43:38.187  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:43:38.187  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:38.187  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:38.187  1292  2321 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 17:43:38.187  1018  1308 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-16 17:43:38.197  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:38.197  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:38.197  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:38.197  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:38.207  6884  6884 E Zygote  : MountEmulatedStorage()
08-16 17:43:38.207  6884  6884 E Zygote  : v2
08-16 17:43:38.207  6884  6884 I libpersona: KNOX_SDCARD checking this for 10064
08-16 17:43:38.207  6884  6884 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:38.207  6884  6884 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:43:38.207  1018  1308 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6884 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:43:38.217  6884  6884 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:38.217  6884  6884 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:43:38.217  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:43:38.217  6828  6878 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 17:43:38.217  1018  1018 I ApplicationPolicy: updateDataUsageMap
,08-16 17:43:38.237  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:38.237  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:38.237  6884  6884 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:38.237  6884  6884 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:38.247  1018  1506 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:38.247  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.247  1018  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.247  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.257  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:38.257  6884  6884 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 17:43:38.277  6884  6884 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:43:38.277  6884  6884 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 17:43:38.307  6884  6884 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:43:38.307  1018  1308 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-16 17:43:38.307  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:38.307  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:38.307  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:38.307  1018  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:38.327  1018  1308 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6901 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:43:38.327  1018  1308 I ActivityManager: Killing 6450:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-16 17:43:38.327  6901  6901 E Zygote  : MountEmulatedStorage()
08-16 17:43:38.327  6901  6901 I libpersona: KNOX_SDCARD checking this for 10065
08-16 17:43:38.327  6901  6901 E Zygote  : v2
08-16 17:43:38.327  6901  6901 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:38.327  6901  6901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:38.327  6901  6901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:38.327  6901  6901 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:38.347  6901  6901 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:38.347  6901  6901 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:38.367  6901  6901 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:43:38.377  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.377  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.377  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-16 17:43:38.377  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-16 17:43:38.377  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:38.377  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:38.377  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:38.377  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:38.397  6917  6917 E Zygote  : MountEmulatedStorage()
,08-16 17:43:38.397  6917  6917 E Zygote  : v2
08-16 17:43:38.397  6917  6917 I libpersona: KNOX_SDCARD checking this for 10102
08-16 17:43:38.397  6917  6917 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:38.397  6917  6917 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:43:38.397  1018  1031 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6917 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-16 17:43:38.397  1018  3639 I ActivityManager: Killing 6479:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-16 17:43:38.407  6917  6917 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:38.407  6917  6917 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:43:38.427  6917  6917 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:38.427  6917  6917 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:38.437  6917  6917 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 17:43:38.627  6917  6937 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-16 17:43:38.627  6917  6937 I Babel_SMS: MmsConfig.loadMmsSettings
08-16 17:43:38.627  6917  6937 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-16 17:43:38.627  6917  6937 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 17:43:38.657  6917  6937 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-16 17:43:38.657  6917  6937 I Babel_SMS: MmsConfig.loadFromResources
,08-16 17:43:38.657  6917  6937 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 17:43:38.657  6917  6937 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-16 17:43:38.687  1018  1480 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-16 17:43:38.687  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-16 17:43:38.687  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.687  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.687  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 17:43:38.717  6917  6917 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:43:38.717  6917  6917 I Babel_Crash: startup - clean
,08-16 17:43:38.747  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.747  1018  1308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.747  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.757  1018  1308 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:43:38.757  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:43:38.757  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.757  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.757  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:38.757  2205  2205 I Hs20UtilService: Starting #9
,08-16 17:43:38.757  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:43:38.757  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:38.767  2205  2222 I Hs20UtilService: Message received 5007
08-16 17:43:38.767  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:43:38.767  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:43:38.767  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 17:43:38.767  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:38.767  1292  2321 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:43:38.767  6917  6917 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:43:38.767  6917  6917 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 17:43:38.767  6917  6917 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 17:43:38.777  1018  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:38.777  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:38.777  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.777  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.777  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:38.777  6917  6917 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-16 17:43:38.777  2205  2205 I Hs20UtilService: Starting #10
,08-16 17:43:38.777  6917  6917 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-16 17:43:38.777  2205  2222 I Hs20UtilService: Message received 5011
,08-16 17:43:38.777  6917  6917 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-16 17:43:38.777  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:43:38.777  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:38.787  6534  6534 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:38.787  6917  6917 W AudioCapabilities: Unsupported mime audio/x-ima
,08-16 17:43:38.787  6534  6534 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-16 17:43:38.787  6917  6917 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 17:43:38.787  6917  6917 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 17:43:38.787  1018  1045 D Tethering: interfaceRemoved wlan0
08-16 17:43:38.787  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 17:43:38.807  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.807  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.807  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.807  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.807  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.807  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.807  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.807  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.807  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.817  6917  6917 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 17:43:38.817  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.817  6917  6917 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 17:43:38.817  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.817  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.817  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.817  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.817  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.827  6917  6917 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-16 17:43:38.827  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.827  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.827  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.827  6917  6917 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 17:43:38.827  6917  6917 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 17:43:38.827  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.827  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.827  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.827  6917  6917 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-16 17:43:38.837  6917  6917 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-16 17:43:38.837  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.837  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.837  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.837  6917  6917 W VideoCapabilities: Unsupported mime video/mp43
,08-16 17:43:38.837  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.837  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.837  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.837  6917  6917 W VideoCapabilities: Unsupported mime video/sorenson
08-16 17:43:38.837  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.837  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.837  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.847  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.847  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.847  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.847  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.847  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.847  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.847  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.847  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.847  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.847  6917  6917 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 17:43:38.847  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.847  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.847  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.857  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.857  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.857  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:38.867  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:38.867  1018  1508 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 17:43:38.867  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:43:38.867  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.867  1018  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:38.867  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:43:38.877  6917  6917 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 17:43:38.877  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:38.877  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:38.887  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:38.887  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 17:43:38.887  1018  1045 D Tethering: interfaceRemoved p2p0
08-16 17:43:38.887  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 17:43:38.887  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-16 17:43:38.887  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:38.887  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:38.887  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:38.887  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:38.907  6941  6941 E Zygote  : MountEmulatedStorage()
08-16 17:43:38.907  6941  6941 E Zygote  : v2
08-16 17:43:38.907  6941  6941 I libpersona: KNOX_SDCARD checking this for 1002
08-16 17:43:38.907  6941  6941 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:38.907  6941  6941 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:38.907  6941  6941 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:43:38.907  1018  1494 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6941 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-16 17:43:38.907  6941  6941 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:38.917  6917  6917 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:43:38.917  6917  6917 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:43:38.927  6917  6917 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-16 17:43:38.927  6941  6941 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:38.927  6917  6917 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:43:38.927  6941  6941 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:38.927  6917  6917 I vclib   : onServiceConnected
,08-16 17:43:38.937  1018  1495 I ActivityManager: Killing 6504:com.samsung.android.sm/1000 (adj 15): empty #21
,08-16 17:43:38.947  6941  6941 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 17:43:38.947  6941  6941 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.,
,08-16 17:43:38.977  6941  6941 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding GattService
,08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding HeadsetService
,08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding A2dpService
,08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding HidService
,08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding HealthService
08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding PanService
08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding SapService
08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding SapClientService
08-16 17:43:39.007  6941  6941 D BtSettings.ProfileConfig: Adding HidDevService
,08-16 17:43:39.007  6941  6941 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-16 17:43:39.007  1018  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-16 17:43:39.007  1018  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:39.007  1018  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:43:39.007  1018  1495 D SettingsProvider: selectionArgs: false
08-16 17:43:39.007  1018  1495 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:39.007  1018  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:39.007  1018  1495 D SettingsProvider: ret = -1
,08-16 17:43:39.017  1018  1508 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:39.017  1018  1508 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:39.017  1018  1508 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:39.017  1018  1508 D SettingsProvider: selectionArgs: false
08-16 17:43:39.017  1018  1508 D SettingsProvider: selectionArgs: 1002
08-16 17:43:39.017  1018  1508 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:39.017  1018  1508 D SettingsProvider: ret = -1
,08-16 17:43:39.017  1018  3640 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-16 17:43:39.017  1018  3640 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:39.017  1018  3640 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:43:39.017  1018  3640 D SettingsProvider: selectionArgs: false
08-16 17:43:39.017  1018  3640 D SettingsProvider: selectionArgs: 1002
08-16 17:43:39.017  1018  3640 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:39.017  1018  3640 D SettingsProvider: ret = -1
,08-16 17:43:39.017  1018  1494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-16 17:43:39.017  1018  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:39.017  1018  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:39.017  1018  1494 D SettingsProvider: selectionArgs: false
08-16 17:43:39.017  1018  1494 D SettingsProvider: selectionArgs: 1002
08-16 17:43:39.017  1018  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:39.017  1018  1494 D SettingsProvider: ret = -1
,08-16 17:43:39.017  1018  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-16 17:43:39.017  1018  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:39.017  1018  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:39.017  1018  1480 D SettingsProvider: selectionArgs: false
08-16 17:43:39.017  1018  1480 D SettingsProvider: selectionArgs: 1002
08-16 17:43:39.017  1018  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:39.017  1018  1480 D SettingsProvider: ret = -1
,08-16 17:43:39.017  1018  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-16 17:43:39.017  1018  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:39.017  1018  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:39.017  1018  1497 D SettingsProvider: selectionArgs: false
08-16 17:43:39.017  1018  1497 D SettingsProvider: selectionArgs: 1002
08-16 17:43:39.017  1018  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:39.017  1018  1497 D SettingsProvider: ret = -1
,08-16 17:43:39.017  1018  1496 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-16 17:43:39.017  1018  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:39.017  1018  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:39.017  1018  1496 D SettingsProvider: selectionArgs: false
,08-16 17:43:39.017  1018  1496 D SettingsProvider: selectionArgs: 1002
08-16 17:43:39.017  1018  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:39.017  1018  1496 D SettingsProvider: ret = -1
,08-16 17:43:39.017  1018  3639 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-16 17:43:39.017  1018  3639 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:39.017  1018  3639 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:43:39.017  1018  3639 D SettingsProvider: selectionArgs: false
08-16 17:43:39.017  1018  3639 D SettingsProvider: selectionArgs: 1002
08-16 17:43:39.017  1018  3639 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:39.017  1018  3639 D SettingsProvider: ret = -1
,08-16 17:43:39.017  1018  1136 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:43:39.017  1018  1136 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:39.017  1018  1136 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:39.017  1018  1136 D SettingsProvider: selectionArgs: false
08-16 17:43:39.017  1018  1136 D SettingsProvider: selectionArgs: 1002
08-16 17:43:39.017  1018  1136 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:43:39.017  1018  1136 D SettingsProvider: ret = -1
08-16 17:43:39.017  1018  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:39.017  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:39.017  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:39.017  1018  1030 D SettingsProvider: selectionArgs: false
,08-16 17:43:39.017  1018  1030 D SettingsProvider: selectionArgs: 1002
08-16 17:43:39.017  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:39.017  1018  1030 D SettingsProvider: ret = -1
08-16 17:43:39.027  1018  1308 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-16 17:43:39.027  1018  1308 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:39.027  1018  1308 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:39.027  1018  1308 D SettingsProvider: selectionArgs: false
08-16 17:43:39.027  1018  1308 D SettingsProvider: selectionArgs: 1002
08-16 17:43:39.027  1018  1308 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:39.027  1018  1308 D SettingsProvider: ret = -1
08-16 17:43:39.027  1018  1506 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-16 17:43:39.027  1018  1506 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:39.027  1018  1506 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:39.027  1018  1506 D SettingsProvider: selectionArgs: false
08-16 17:43:39.027  1018  1506 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:39.027  1018  1506 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:39.027  1018  1506 D SettingsProvider: ret = -1
,08-16 17:43:39.027  1018  1495 I ActivityManager: Killing 6553:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-16 17:43:39.037  2015  2015 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:43:39.037  1018  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:39.037  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 17:43:39.037  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:39.037  1018  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:39.037  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:39.047  2015  6958 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 17:43:39.047  2015  2015 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.,
,08-16 17:43:39.047  1018  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:39.047  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-16 17:43:39.047  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:39.047  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:39.047  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:39.047  2205  2205 I Hs20UtilService: Starting #11
08-16 17:43:39.047  2205  2222 I Hs20UtilService: Message received 5011
,08-16 17:43:39.057  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:43:39.057  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:39.057  6534  6534 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:39.057  6534  6534 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:43:39.057  1018  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:39.057  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:39.057  1018  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:39.057  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:39.077  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-16 17:43:39.087  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:43:39.087  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.087  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.087  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.097  1018  3367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:43:39.097  6961  6961 E Zygote  : MountEmulatedStorage()
08-16 17:43:39.097  1018  1136 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6961 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 17:43:39.097  6961  6961 E Zygote  : v2
08-16 17:43:39.097  1018  1508 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:39.097  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:39.097  6961  6961 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:43:39.097  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:39.097  6961  6961 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:39.097  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:43:39.097  6961  6961 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:39.107  6961  6961 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:39.107  2015  6958 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-16 17:43:39.107  6961  6961 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:39.127  6961  6961 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:39.127  6961  6961 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:39.147  6961  6961 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-16 17:43:39.147  6961  6961 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-16 17:43:39.147  6961  6961 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-16 17:43:39.167  6961  6961 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-16 17:43:39.167  6961  6961 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 17:43:39.167  6961  6961 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 17:43:39.167  6961  6961 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:39.177  1018  1030 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-16 17:43:39.177  6961  6976 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-16 17:43:39.177  1018  1030 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-16 17:43:39.187  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-16 17:43:39.187  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.187  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.187  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.187  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.207  6978  6978 E Zygote  : MountEmulatedStorage(),
08-16 17:43:39.207  6978  6978 I libpersona: KNOX_SDCARD checking this for 10001
,08-16 17:43:39.207  6978  6978 E Zygote  : v2
08-16 17:43:39.207  6978  6978 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:39.207  6978  6978 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:43:39.207  6978  6978 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:39.217  6978  6978 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-16 17:43:39.217  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6978 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-16 17:43:39.217  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast,
,08-16 17:43:39.227  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.227  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.227  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.227  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.237  6978  6978 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:39.237  6978  6978 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:39.247  6990  6990 E Zygote  : MountEmulatedStorage()
,08-16 17:43:39.247  6990  6990 E Zygote  : v2
08-16 17:43:39.247  6990  6990 I libpersona: KNOX_SDCARD checking this for 10031
,08-16 17:43:39.247  6990  6990 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:39.247  6990  6990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:43:39.257   288   288 E SMD     : DCD OFF
,08-16 17:43:39.257  6990  6990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:39.257  6990  6990 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-16 17:43:39.257  1018  1030 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6990 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-16 17:43:39.267  1756  1756 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 17:43:39.267  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-16 17:43:39.277  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:43:39.277  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:43:39.277  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.277  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.277  6990  6990 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:39.287  6990  6990 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:39.287  7007  7007 E Zygote  : MountEmulatedStorage()
08-16 17:43:39.287  7007  7007 E Zygote  : v2
08-16 17:43:39.287  7007  7007 I libpersona: KNOX_SDCARD checking this for 10121
08-16 17:43:39.287  7007  7007 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:39.297  7007  7007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:39.297  7007  7007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:43:39.297  1018  1043 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7007 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-16 17:43:39.297  7007  7007 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:39.307  2610  2763 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,08-16 17:43:39.317  1756  1756 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-16 17:43:39.317  1756  1756 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-16 17:43:39.317  1756  1756 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-16 17:43:39.317  1756  1756 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-16 17:43:39.327  1756  1756 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 17:43:39.337  7007  7007 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:43:39.337  1756  1756 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-16 17:43:39.337  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-16 17:43:39.337  7007  7007 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:39.337  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.337  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.337  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.337  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.347  6990  6990 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-16 17:43:39.357  7023  7023 E Zygote  : MountEmulatedStorage(),
08-16 17:43:39.357  7023  7023 E Zygote  : v2
08-16 17:43:39.357  7023  7023 I libpersona: KNOX_SDCARD checking this for 10077
,08-16 17:43:39.357  7023  7023 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:39.357  7023  7023 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:39.357  7023  7023 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:39.357  7023  7023 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
08-16 17:43:39.367  1018  1030 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7023 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:43:39.377  1018  1030 I ActivityManager: Killing 6569:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-16 17:43:39.397   305   305 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 772us total 34.594ms
,08-16 17:43:39.397  7023  7023 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:39.397  7023  7023 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:39.397  1018  3639 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-16 17:43:39.407  1018  3639 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.407  1018  3639 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.407  1018  3639 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.407  1018  3639 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.407  2767  7040 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
08-16 17:43:39.407  7007  7007 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:43:39.407  7007  7007 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 17:43:39.407  7007  7007 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:43:39.407  2767  7040 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-16 17:43:39.407  2767  7040 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-16 17:43:39.407  2767  7040 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-16 17:43:39.407  2767  7040 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-16 17:43:39.417  7007  7007 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
08-16 17:43:39.417   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 20.923ms
,08-16 17:43:39.437   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.645ms
,08-16 17:43:39.457  7042  7042 E Zygote  : MountEmulatedStorage(),
08-16 17:43:39.457  7042  7042 E Zygote  : v2
,08-16 17:43:39.457  7042  7042 I libpersona: KNOX_SDCARD checking this for 10032
08-16 17:43:39.457  7042  7042 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:39.457  7042  7042 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:43:39.457  1018  3639 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7042 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:43:39.457  7007  7007 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-16 17:43:39.467  7042  7042 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:39.467  7042  7042 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-16 17:43:39.477  7007  7007 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-16 17:43:39.477  1018  1508 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-16 17:43:39.477  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.477  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.477  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.477  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.497  7057  7057 E Zygote  : MountEmulatedStorage()
,08-16 17:43:39.497  7057  7057 E Zygote  : v2
08-16 17:43:39.497  7057  7057 I libpersona: KNOX_SDCARD checking this for 10141
08-16 17:43:39.497  7057  7057 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:39.497  7057  7057 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:39.497  7042  7042 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-16 17:43:39.497  7057  7057 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:39.497  7042  7042 D ActivityThread: Added TimaKeyStore provider
08-16 17:43:39.497  1018  1508 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7057 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-16 17:43:39.497  7057  7057 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:43:39.497  1018  1508 I ActivityManager: Killing 6586:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-16 17:43:39.497  1018  1508 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
08-16 17:43:39.507  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.507  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.507  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.507  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.517  7071  7071 E Zygote  : MountEmulatedStorage()
08-16 17:43:39.517  7071  7071 E Zygote  : v2
08-16 17:43:39.517  7071  7071 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:43:39.517  7071  7071 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:39.517  7071  7071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:39.517  7071  7071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:39.517  7071  7071 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:39.517  1018  1508 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7071 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 17:43:39.527  1018  1508 I ActivityManager: Killing 6519:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-16 17:43:39.527  7057  7057 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:39.527  7057  7057 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:39.557  7071  7071 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:43:39.557  7071  7071 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:39.557  7057  7057 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-16 17:43:39.557  7057  7057 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:43:39.557  7057  7057 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:43:39.557  7057  7057 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 17:43:39.587  7042  7087 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-16 17:43:39.597  7042  7087 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-16 17:43:39.597  7042  7087 D SPPClientService: PushLog.txt file is not deleted.
,08-16 17:43:39.597  7042  7087 D SPPClientService: PushLog.txt file is not deleted.
08-16 17:43:39.597  7042  7087 D SPPClientService: ============PushLog. stop!
,08-16 17:43:39.607  7042  7042 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-16 17:43:39.607  1018  3639 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-16 17:43:39.607  1018  3639 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.607  1018  3639 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.607  1018  3639 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.607  1018  3639 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.607  7071  7071 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-16 17:43:39.617  1018  1506 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:39.627  7089  7089 E Zygote  : MountEmulatedStorage(),
08-16 17:43:39.627  7089  7089 E Zygote  : v2
08-16 17:43:39.627  7089  7089 I libpersona: KNOX_SDCARD checking this for 10036
08-16 17:43:39.627  7089  7089 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:39.627  7089  7089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:43:39.627  1018  3639 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7089 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:43:39.627  1018  3639 I ActivityManager: Killing 6050:com.android.mms/u0a41 (adj 15): empty #21
,08-16 17:43:39.637  7089  7089 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:39.637  7089  7089 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-16 17:43:39.637  1018  1497 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-16 17:43:39.637  1018  1508 D RCPManagerService: exchangeData() failure , invalid userId
08-16 17:43:39.637  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-16 17:43:39.637  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:39.637  1018  1497 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-16 17:43:39.637  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-16 17:43:39.657  7089  7089 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:39.657  7089  7089 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:39.667  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 17:43:39.687  1018  1497 D CountryDetector: No listener is left
,08-16 17:43:39.687  1018  1136 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:39.697  7042  7102 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-16 17:43:39.697  7089  7089 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@19655a45
,08-16 17:43:39.697  1018  1506 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:39.707  7089  7089 I SA      : [SSP] onCreated
,08-16 17:43:39.727  7089  7089 I SA      : [TPM] There is no property file
,08-16 17:43:39.727  7089  7089 I SA      : [SCU] isHaveSA() - false
,08-16 17:43:39.727  7089  7089 I SA      : [TPM] getModelProperty : null
,08-16 17:43:39.727  7089  7089 I SA      : [TPM] getCSCProperty : null
,08-16 17:43:39.727  7089  7089 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-16 17:43:39.727  7089  7089 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-16 17:43:39.727  7089  7089 I SA      : [DM] TFT FEATURE: false
,08-16 17:43:39.737  7089  7089 I SA      : [DM] init START
,08-16 17:43:39.737  7089  7089 I SA      : [DM] This device is not a Vodafone
,08-16 17:43:39.747  7089  7089 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-16 17:43:39.747  7089  7089 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-16 17:43:39.747  7089  7089 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-16 17:43:39.747  7089  7089 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-16 17:43:39.747  7089  7089 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-16 17:43:39.747  7089  7089 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-16 17:43:39.747  7089  7089 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-16 17:43:39.757  7089  7089 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 17:43:39.757  7089  7089 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-16 17:43:39.757  7089  7089 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-16 17:43:39.757  7089  7089 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-16 17:43:39.757  7089  7089 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-16 17:43:39.757  7089  7089 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-16 17:43:39.757  7089  7089 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-16 17:43:39.757  7089  7089 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-16 17:43:39.757  7089  7089 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-16 17:43:39.757  7089  7089 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-16 17:43:39.757  7089  7089 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-16 17:43:39.767  7089  7089 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-16 17:43:39.767  7089  7089 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-16 17:43:39.767  7089  7089 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-16 17:43:39.767  7089  7089 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-16 17:43:39.767  7089  7089 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-16 17:43:39.767  7089  7089 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-16 17:43:39.767  7089  7089 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-16 17:43:39.767  7089  7089 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-16 17:43:39.767  7089  7089 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-16 17:43:39.767  7089  7089 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-16 17:43:39.767  7089  7089 I SA      : [SCU] isHaveSA() - false
08-16 17:43:39.767  7089  7089 I SA      : support phone number id : false
08-16 17:43:39.767  7089  7089 I SA      : [DM] Supports Ref Jpn : true
,08-16 17:43:39.767  7089  7089 I SA      : [DM] init END
08-16 17:43:39.767  7089  7089 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-16 17:43:39.777  7089  7089 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-16 17:43:39.777  7089  7089 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-16 17:43:39.777  1018  1136 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-16 17:43:39.777  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.777  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.777  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.777  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.787  1018  1506 D RCPManagerService: exchangeData() failure , invalid userId,
08-16 17:43:39.787  7071  7071 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
08-16 17:43:39.787  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:39.787  7119  7119 E Zygote  : MountEmulatedStorage()
,08-16 17:43:39.787  7119  7119 E Zygote  : v2
08-16 17:43:39.797  7119  7119 I libpersona: KNOX_SDCARD checking this for 10068
08-16 17:43:39.797  7119  7119 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:39.797  7119  7119 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:43:39.797  7089  7089 I SA      : [SLFUCHKMGR] constructor called
08-16 17:43:39.797  7071  7071 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
08-16 17:43:39.797  7071  7071 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
08-16 17:43:39.797  7119  7119 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:43:39.797  7071  7071 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-16 17:43:39.797  7071  7071 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
08-16 17:43:39.797  7071  7071 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
08-16 17:43:39.807  1018  1136 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7119 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-16 17:43:39.807  7119  7119 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-16 17:43:39.807  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-16 17:43:39.807  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.807  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.807  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.807  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.817  1018  1508 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:39.817  7119  7119 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:39.817  7119  7119 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:39.827  7089  7089 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-16 17:43:39.827  7089  7089 I SA      : [OR] == isSIMCardReady false ==
,08-16 17:43:39.827  7135  7135 E Zygote  : MountEmulatedStorage()
08-16 17:43:39.827  1018  1480 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7135 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:43:39.827  7135  7135 E Zygote  : v2
08-16 17:43:39.827  7135  7135 I libpersona: KNOX_SDCARD checking this for 10008
08-16 17:43:39.827  7135  7135 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:39.837  7135  7135 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:39.837  1018  1480 I ActivityManager: Killing 6612:com.qualcomm.timeservice/1000 (adj 15): empty #21,
,08-16 17:43:39.837  7135  7135 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:39.837  7135  7135 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-16 17:43:39.837  1018  1495 I ActivityManager: Killing 6647:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-16 17:43:39.847  1018  1508 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:39.847  7089  7089 I SA      : [SCU] == networkStateCheck == false
,08-16 17:43:39.847  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-16 17:43:39.847  7089  7089 I SA      : [OR] onReceive END
,08-16 17:43:39.847  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.847  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.847  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.847  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.857  7135  7135 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:39.857  7135  7135 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:39.867  7119  7119 D BadgeProvider: onCreate
,08-16 17:43:39.867  7119  7119 D BadgeProvider: DatabaseHelper,
,08-16 17:43:39.867  7151  7151 E Zygote  : MountEmulatedStorage()
,08-16 17:43:39.867  7151  7151 E Zygote  : v2
08-16 17:43:39.877  7151  7151 I libpersona: KNOX_SDCARD checking this for 10009
08-16 17:43:39.877  7151  7151 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:39.877  7151  7151 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:39.877  1018  1480 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7151 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-16 17:43:39.877  1018  1480 I ActivityManager: Killing 6666:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-16 17:43:39.877  7151  7151 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:39.877  7151  7151 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-16 17:43:39.877  1018  1496 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-16 17:43:39.877  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-16 17:43:39.887  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:39.887  1018  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:39.887  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 17:43:39.887  1018  1480 I ActivityManager: Killing 6465:com.android.calendar/u0a131 (adj 15): empty #21
,08-16 17:43:39.897  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-16 17:43:39.897  7151  7151 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:39.897  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.897  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.897  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:39.897  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:39.897  7151  7151 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:39.907  1225  1225 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:39.907  7119  7132 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-16 17:43:39.927  7168  7168 E Zygote  : MountEmulatedStorage()
,08-16 17:43:39.927  7168  7168 E Zygote  : v2
08-16 17:43:39.927  7168  7168 I libpersona: KNOX_SDCARD checking this for 10110
08-16 17:43:39.937  7168  7168 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:43:39.927  7168  7168 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:39.927  1018  1494 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7168 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:43:39.937  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-16 17:43:39.937  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-16 17:43:39.937  1018  1031 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:43:39.937  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:39.937  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-16 17:43:39.937  7168  7168 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:43:39.937  7168  7168 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-16 17:43:39.947  6917  7160 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 17:43:39.957  1018  1030 I ActivityManager: Killing 6631:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-16 17:43:39.957  7119  7132 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-16 17:43:39.957  7119  7132 D BadgeProvider: sendNotify, [notify] : null
08-16 17:43:39.957  7119  7132 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-16 17:43:39.957  7119  7132 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-16 17:43:39.957  7119  7132 D BadgeProvider: update, [UpdateCount] : 1
08-16 17:43:39.957  1498  1498 D Launcher.Model: reloadBadges entered.
,08-16 17:43:39.967  7168  7168 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:39.977  7168  7168 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:40.007  1018  3640 I ActivityManager: Killing 5971:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-16 17:43:40.007  2919  2919 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 17:43:40 GMT+02:00 2016
,08-16 17:43:40.017  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-16 17:43:40.017  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 17:43:40.017  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:40.017  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:40.017  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 17:43:40.017  2919  2919 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-16 17:43:40.027  2919  2919 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-16 17:43:40.027  2919  2919 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 17:43:40.027  2919  2919 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 17:43:40.037  2919  7184 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 17:43:40.037  2919  7184 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-16 17:43:40.037  2919  7184 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-16 17:43:40.047  2919  7184 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-16 17:43:40.047  2919  2919 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-16 17:43:40.057  1018  1495 I ActivityManager: Killing 5810:com.android.vending/u0a26 (adj 15): empty #21
,08-16 17:43:40.067  1018  3640 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:40.067  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-16 17:43:40.067  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:40.067  1018  3640 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:40.067  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:40.087  4781  7186 I iu.SyncManager: SYNC; picasa accounts
08-16 17:43:40.087  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-16 17:43:40.087  1018  1506 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-16 17:43:40.087  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-16 17:43:40.087  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-16 17:43:40.117  4781  4781 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-16 17:43:40.167  1018  1308 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-16 17:43:40.267   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 17:43:40.267   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:40.267  7168  7190 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 17:43:40.277   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 17:43:40.277   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:40.277  7168  7190 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 17:43:40.287   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 17:43:40.287   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:40.287  7168  7191 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 17:43:40.287   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 17:43:40.287   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:40.297  7168  7191 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 17:43:40.307  1018  1494 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 17:43:40.307  1018  1494 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:43:40.307  1018  1494 D SecContentProvider2: mCursor = null
,08-16 17:43:40.307  1018  1494 D WifiService: setWifiEnabled: true pid=6720, uid=10171
,08-16 17:43:40.307  1018  1494 W ActivityManager: Permission Denial: getCurrentUser() from pid=6720, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:43:40.317  1018  1494 W WifiService: Failed getting userId using ActivityManagerNative
08-16 17:43:40.317  1018  1494 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6720, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:43:40.317  1018  1494 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 17:43:40.317  1018  1494 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:43:40.317  1018  1494 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:43:40.317  1018  1494 W WifiService: 	,at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:43:40.317  1018  1494 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 17:43:40.317  1018  1494 D SettingsProvider: name = wifi_on
,08-16 17:43:40.317  7168  7168 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
08-16 17:43:40.317  7168  7168 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 17:43:40.317  7168  7168 I GAv4    :   adb logcat -s GAv4
08-16 17:43:40.317  1018  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 17:43:40.337  7168  7168 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:43:40.337  1018  1506 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-16 17:43:40.387  7168  7168 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:43:40.397  7168  7194 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:43:40.557  1018  3350 D SSRM:n  : SIOP:: AP = 350
,08-16 17:43:40.627  1018  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:40.637  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:40.637  1018  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:40.637  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms,
,08-16 17:43:40.667  7168  7168 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-16 17:43:40.677  7168  7168 I cr.library_loader: Time to load native libraries: 1 ms (timestamps 3605-3606)
08-16 17:43:40.677  7168  7168 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-16 17:43:40.687  7168  7168 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {161aa614}
08-16 17:43:40.687  7168  7168 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-16 17:43:40.687  7168  7168 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 17:43:40.697  1018  1045 D Tethering: interfaceAdded wlan0
,08-16 17:43:40.697  1018  1131 E Tethering: No numeric data
,08-16 17:43:40.707  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 17:43:40.707  1018  1131 D Tethering: clearTetheredNotification()
,08-16 17:43:40.707  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:43:40.707  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:40.707  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-16 17:43:40.707  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:43:40.707  7168  7168 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-16 17:43:40.707  7168  7168 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:43:40.707  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:43:40.717  1180  1180 D HotspotTile: updateTetherState():false, false
,08-16 17:43:40.717  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:40.717  1018  1125 V NetworkStats: performPollLocked() took 7ms
,08-16 17:43:40.717  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:40.717  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:40.717  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:40.717  1018  1131 D Tethering: InitialState.processMessage what=4
,08-16 17:43:40.717  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:40.717  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:40.717  1018  1131 E Tethering: No numeric data
,08-16 17:43:40.717  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:43:40.717  1018  1131 D Tethering: clearTetheredNotification()
,08-16 17:43:40.717  7168  7168 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 17:43:40.717  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:43:40.717  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:40.717  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:40.717  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:43:40.727  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-16 17:43:40.727  1180  1180 D HotspotTile: updateTetherState():false, false
08-16 17:43:40.727  1018  1045 D Tethering: interfaceAdded p2p0
,08-16 17:43:40.727  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-16 17:43:40.727  1018  1125 V NetworkStats: performPollLocked() took 6ms
08-16 17:43:40.727  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:40.727  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:43:40.727  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:40.727  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:40.727   278  1017 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-16 17:43:40.727  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:43:40.727  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:43:40.727   278  1017 D SoftapController: Softap fwReload - Ok
,08-16 17:43:40.727   278  1017 D CommandListener: Setting iface cfg
08-16 17:43:40.727   278  1017 D CommandListener: Trying to bring down wlan0
,08-16 17:43:40.737   278  1017 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:43:40.737  1018  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-16 17:43:40.737  7168  7168 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:43:40.737  7168  7168 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:43:40.737  7168  7168 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:43:40.737  7168  7168 I Adreno-EGL: Local Branch: 
08-16 17:43:40.737  7168  7168 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:43:40.737  7168  7168 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:43:40.737  7168  7168 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-16 17:43:40.737  1018  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-16 17:43:40.737  1018  1128 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-16 17:43:40.747  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:40.747  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:43:40.747  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:40.747  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:40.747  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:40.747  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:40.757  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:40.757  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:40.757  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-16 17:43:40.757  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:43:40.757  1180  1180 D HotspotTile: onReceive : 2, 0
,08-16 17:43:40.757  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:40.767  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:40.767  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:40.787  7222  7222 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-16 17:43:40.787  7222  7222 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 17:43:40.787  7222  7222 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 17:43:40.807  7222  7222 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-16 17:43:40.807   407   407 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7222
08-16 17:43:40.807   407   407 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-16 17:43:40.807  7222  7222 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 17:43:40.807  7222  7222 I wpa_supplicant: ssSupport state is = 1
08-16 17:43:40.807  7222  7222 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 17:43:40.807  7222  7222 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-16 17:43:40.807   407   407 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7222
08-16 17:43:40.807   407   407 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
08-16 17:43:40.807  7168  7230 W cr.media: Requires BLUETOOTH permission
,08-16 17:43:40.827  7168  7168 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
,08-16 17:43:40.837  7168  7168 I NSApplication: Starting up...
,08-16 17:43:40.837  1018  1030 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-16 17:43:40.837  1018  1031 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-16 17:43:40.847  1018  1506 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-16 17:43:40.847  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:40.847  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:40.847  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:40.847  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:40.857  1018  1506 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7236 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-16 17:43:40.857  1018  1506 I ActivityManager: Killing 6884:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-16 17:43:40.867  7236  7236 E Zygote  : MountEmulatedStorage()
,08-16 17:43:40.867  7236  7236 E Zygote  : v2
08-16 17:43:40.867  7236  7236 I libpersona: KNOX_SDCARD checking this for 10117
08-16 17:43:40.867  7236  7236 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:40.867  7236  7236 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:43:40.867  7236  7236 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 17:43:40.877  7236  7236 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:43:40.897  7236  7236 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:43:40.897  7236  7236 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:40.917  7236  7236 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:43:40.997   407   407 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-16 17:43:41.007  7222  7222 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-16 17:43:41.057  7222  7222 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-16 17:43:41.057  7222  7222 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-16 17:43:41.067  7222  7222 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-16 17:43:41.067   407   407 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7222
08-16 17:43:41.067   407   407 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-16 17:43:41.067  7222  7222 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-16 17:43:41.067  7222  7222 I wpa_supplicant: ssSupport state is = 1
08-16 17:43:41.067  7222  7222 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:43:41.067  7222  7222 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:43:41.067  7222  7222 E wpa_supplicant: SIM READ ERROR
08-16 17:43:41.067  7222  7222 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:41.067  7222  7222 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:43:41.067  7222  7222 E wpa_supplicant: SIM READ ERROR
,08-16 17:43:41.067  7222  7222 I wpa_supplicant: Blacklist: Clear (all) 
08-16 17:43:41.067  7222  7222 I wpa_supplicant: wpa_default_ap_write_once,
08-16 17:43:41.067  7222  7222 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:43:41.067  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:41.067  7222  7222 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:41.067  7222  7222 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 17:43:41.067  7222  7222 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:43:41.067  7222  7222 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:43:41.067  7222  7222 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 17:43:41.067  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:41.067  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:41.167  7222  7222 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-16 17:43:41.237   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:41.277  7222  7222 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-16 17:43:41.277  7222  7222 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-16 17:43:41.287  1018  3640 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.,
,08-16 17:43:41.297  1018  3640 I ActivityManager: Killing 6901:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-16 17:43:41.297  7222  7222 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-16 17:43:41.297   407   407 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7222
08-16 17:43:41.297   407   407 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 17:43:41.297  7222  7222 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-16 17:43:41.297  7222  7222 I wpa_supplicant: ssSupport state is = 1
,08-16 17:43:41.307  1018  1494 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-16 17:43:41.307  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:41.307  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:41.307  7222  7222 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 17:43:41.307  7222  7222 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-16 17:43:41.307  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:41.307  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:41.307  2205  2205 I Hs20UtilService: Starting #12
,08-16 17:43:41.307  2205  2222 I Hs20UtilService: Message received 5011
,08-16 17:43:41.307  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:43:41.307  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:41.307  6534  6534 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:41.307  6534  6534 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:43:41.317  7222  7222 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-16 17:43:41.317   407   407 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7222
08-16 17:43:41.317   407   407 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 17:43:41.317  7222  7222 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-16 17:43:41.317  7222  7222 I wpa_supplicant: ssSupport state is = 1
08-16 17:43:41.317  7222  7222 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:41.317  7222  7222 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:43:41.317  7222  7222 E wpa_supplicant: SIM READ ERROR
08-16 17:43:41.317  7222  7222 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:43:41.317  7222  7222 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:43:41.317  7222  7222 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 17:43:41.327  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:43:41.327  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:41.327  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:43:41.327  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:41.327  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:43:41.327  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:43:41.427  7222  7222 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-16 17:43:41.427  7222  7222 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 17:43:41.507  1018  1042 E libprocessgroup: failed to kill 1 processes for processgroup 6901,
08-16 17:43:41.507  7222  7222 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-16 17:43:41.507  7222  7222 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-16 17:43:41.507  7222  7222 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 17:43:41.707  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 17:43:41.707  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:41.707  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:43:41.747  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-16 17:43:41.747  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-16 17:43:41.747  7222  7222 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-16 17:43:41.747  7222  7222 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:41.747  7222  7222 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-16 17:43:41.747  7222  7222 E wpa_supplicant: SIM READ ERROR
08-16 17:43:41.747  7222  7222 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:43:41.787  7222  7222 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-16 17:43:41.797  7222  7222 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-16 17:43:41.797  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:41.797  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,08-16 17:43:41.797  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:41.797  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:43:41.797  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:41.797  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:41.797  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:41.797  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:41.797  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:41.807  1180  1180 D HotspotTile: onReceive : 3, 0
08-16 17:43:41.797  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-16 17:43:41.797  1018  1128 D WifiConfigStore: Loading config and enabling all networks 
,08-16 17:43:41.807  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:41.807  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:41.807  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:41.807  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:41.807  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:41.807  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:41.807  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:41.807  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:41.817  1018  3639 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:41.817  1018  3639 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:43:41.817  1018  1128 E WifiConfigStore: Not a HS20
08-16 17:43:41.817  1018  3639 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:41.817  1018  3639 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:41.817  1018  3639 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:43:41.817  1018  1128 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 17:43:41.817  2205  2205 I Hs20UtilService: Starting #13
08-16 17:43:41.817  2205  2222 I Hs20UtilService: Message received 5011
08-16 17:43:41.827  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:43:41.827  1018  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
08-16 17:43:41.827  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:41.827  6534  6534 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:41.827  6534  6534 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-16 17:43:41.827  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-16 17:43:41.827  7222  7222 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-16 17:43:41.827  7222  7222 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-16 17:43:41.827  7222  7222 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 17:43:41.827  7222  7222 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 17:43:41.827  7222  7222 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 17:43:41.827  7222  7222 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 17:43:41.827  7222  7222 I wpa_supplicant: First Scan Start
08-16 17:43:41.827  7222  7222 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-16 17:43:41.827  1018  1128 D WifiNative-wlan0: Setting external_sim to 1
08-16 17:43:41.827  1018  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:43:41.827  1018  1128 I WifiNative-HAL: startHal
08-16 17:43:41.827  1018  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9d4fd88c
08-16 17:43:41.827  1018  1128 I WifiNative-HAL: Could not start hal
08-16 17:43:41.837  1018  1128 E WifiNative-wlan0: do suspend true
08-16 17:43:41.837  1018  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
08-16 17:43:41.837  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-16 17:43:41.837  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 17:43:41.837  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-16 17:43:41.837  1018  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:41.837  1018  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:41.837  1018  1151 I WifiNative-HAL: startHal
08-16 17:43:41.837  1018  1127 D WifiP2pService: P2pEnablingState
08-16 17:43:41.837  1018  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e4a79bc
08-16 17:43:41.837  1018  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 17:43:41.837  1018  1151 I WifiNative-HAL: Could not start hal
08-16 17:43:41.837  1018  1127 D WifiP2pService: P2p socket connection successful
08-16 17:43:41.837  1018  1151 E WifiScanningService: could not start HAL
08-16 17:43:41.837   278  1017 D CommandListener: Setting iface cfg
08-16 17:43:41.837   278  1017 D CommandListener: Trying to bring up p2p0
08-16 17:43:41.837  1018  1127 D WifiP2pService: P2pEnabledState
08-16 17:43:41.837  6917  6917 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:43:41.837  1018  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 17:43:41.837  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:43:41.837  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:43:41.837  1018  1128 E WifiNative-wlan0: invaild command id : 215
08-16 17:43:41.837  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:43:41.837  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:43:41.837  1018  1128 E WifiNative-wlan0: invaild command id : 215
08-16 17:43:41.847  7222  7222 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:43:41.847  7222  7222 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:43:41.847  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 17:43:41.847  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 17:43:41.847  1018  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:41.847  7222  7222 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-16 17:43:41.847  1018  1128 E WifiStateMachine: Failed to set frequency band 0
08-16 17:43:41.847  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 17:43:41.847  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:41.847  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:41.847  1018  1128 D SecContentProvider2: mCursor = null
08-16 17:43:41.847  1018  1048 D WifiDisplayController: disconnect
08-16 17:43:41.847  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:41.847  1018  1048 D WifiDisplayController: updateConnection
08-16 17:43:41.847  1018  1128 D SecContentProvider2: mCursor = null
08-16 17:43:41.847  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:41.847  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress
08-16 17:43:41.847  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:43:41.847  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-16 17:43:41.857  1018  1127 D WifiP2pService: DeviceAddress: 0a:76:28
08-16 17:43:41.877  1018  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
08-16 17:43:41.877  1018  1127 D WifiP2pService: InactiveState
08-16 17:43:41.877  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
08-16 17:43:41.877  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
08-16 17:43:41.877  7222  7222 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:43:41.877  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
08-16 17:43:41.877  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:43:41.927  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 17:43:41.927  1018  1506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:43:41.927  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:43:41.927  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 17:43:41.927  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:43:41.927  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-16 17:43:41.927  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 17:43:41.927  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  secondary type: null
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  wps: 0
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  grpcapab: 0
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  devcapab: 0
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  status: 3
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  wfdInfo: null
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-16 17:43:41.927  1018  1048 D WifiDisplayController:  SConnectInfo : null
,08-16 17:43:41.937  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:43:41.937  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:41.937  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:43:41.937  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:43:41.937  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:41.937  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:43:41.937  1292  2321 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:43:41.937  1018  1496 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-16 17:43:41.947  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:41.947  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:41.947  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:41.947  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:41.957  7266  7266 E Zygote  : MountEmulatedStorage()
08-16 17:43:41.957  7266  7266 E Zygote  : v2
08-16 17:43:41.957  7266  7266 I libpersona: KNOX_SDCARD checking this for 10064
08-16 17:43:41.957  7266  7266 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:41.957  1018  1496 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7266 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:43:41.967  7266  7266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:43:41.967  7266  7266 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 17:43:41.967  7266  7266 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:41.997  7266  7266 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:41.997  7266  7266 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:42.017  7266  7266 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 17:43:42.027  7266  7266 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:43:42.037  7266  7266 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 17:43:42.067  7266  7266 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:43:42.067  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-16 17:43:42.067  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:42.067  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:42.067  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:42.067  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:42.087  7281  7281 E Zygote  : MountEmulatedStorage(),
08-16 17:43:42.087  7281  7281 E Zygote  : v2
,08-16 17:43:42.087  7281  7281 I libpersona: KNOX_SDCARD checking this for 10065
08-16 17:43:42.087  7281  7281 I libpersona: KNOX_SDCARD not a persona,
,08-16 17:43:42.087  1018  1136 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7281 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-16 17:43:42.087  1018  1136 I ActivityManager: Killing 6799:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-16 17:43:42.097  7281  7281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:42.097  7281  7281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:43:42.097  7281  7281 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:42.117   305   305 I art     : Explicit concurrent mark sweep GC freed 8688(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 697us total 31.666ms
,08-16 17:43:42.127  7281  7281 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:42.127  7281  7281 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:42.137   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 694us total 19.515ms
,08-16 17:43:42.147  7281  7281 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:43:42.157  1018  1508 I ActivityManager: Killing 6941:com.android.bluetooth/1002 (adj 15): empty #21
,08-16 17:43:42.157   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 676us total 20.234ms
,08-16 17:43:42.237   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:42.257   288   288 E SMD     : DCD OFF
,08-16 17:43:43.077  7222  7222 I wpa_supplicant: nl80211: Received scan results (33 BSSes)
08-16 17:43:43.087  7222  7222 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-16 17:43:43.087  7222  7222 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-16 17:43:43.087  7222  7222 I wpa_supplicant: Trying to associate with  'G700'
08-16 17:43:43.087  1018  7262 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-16 17:43:43.087  7222  7222 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-16 17:43:43.087  7222  7222 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-16 17:43:43.107  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:43.107  1018  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:43.197  7222  7222 E wpa_supplicant: Cmd 35605 not handled
,08-16 17:43:43.197  7222  7222 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-16 17:43:43.197  7222  7222 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-16 17:43:43.197  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.197  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.197  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:43.197  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.197  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.197  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:43.197  7222  7222 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-16 17:43:43.207  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.207  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.207  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:43.207  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 17:43:43.207  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 17:43:43.207  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-16 17:43:43.207  7222  7222 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-16 17:43:43.207  7222  7222 I wpa_supplicant: Associated with F4.99.3E
,08-16 17:43:43.207  1018  1131 E Tethering: No numeric data
,08-16 17:43:43.207  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:43:43.207  1018  1131 D Tethering: clearTetheredNotification()
08-16 17:43:43.207  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:43:43.207  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.207  7222  7222 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-16 17:43:43.207  7222  7222 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-16 17:43:43.207  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:43.207  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:43:43.217  7222  7222 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-16 17:43:43.217  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-16 17:43:43.217  1180  1180 D HotspotTile: updateTetherState():false, false
,08-16 17:43:43.217  1018  1125 V NetworkStats: performPollLocked() took 9ms
08-16 17:43:43.217  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:43.217  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:43.217  7222  7222 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:43:43.217  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 17:43:43.217  7222  7222 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-16 17:43:43.227  7222  7222 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-16 17:43:43.227  7222  7222 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-16 17:43:43.227  7222  7222 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 17:43:43.227  7222  7222 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-16 17:43:43.227  7222  7222 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-16 17:43:43.227  7222  7222 I wpa_supplicant: Blacklist: Clear (temp) 
,08-16 17:43:43.227  7222  7222 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-16 17:43:43.227  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 17:43:43.227  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
,08-16 17:43:43.227  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-16 17:43:43.227  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:43:43.227  1018  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:43.237  1018  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-16 17:43:43.237   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:43.247  1018  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 17:43:43.247  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:43.247  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:43.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.247  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.257  1018  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-16 17:43:43.257  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:43.257  1018  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-16 17:43:43.257  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
08-16 17:43:43.257  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:43:43.257  1018  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:43.257  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:43:43.257  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:43.257  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.257  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:43:43.257  2205  2205 I Hs20UtilService: Starting #14
,08-16 17:43:43.257  2205  2222 I Hs20UtilService: Message received 5007
,08-16 17:43:43.267  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:43.267  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:43:43.267  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:43.267  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
08-16 17:43:43.267  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:43:43.267  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:43.267  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:43:43.267  1292  2321 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:43:43.277   278  1017 D CommandListener: Setting iface cfg,
,08-16 17:43:43.277  1018  1128 E WifiStateMachine: Start Dhcp Watchdog 2
,08-16 17:43:43.287  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:43.287  1018  1128 D SecContentProvider2: mCursor = null
08-16 17:43:43.287  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:43.287  1018  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:43.297  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:43.297  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:43.297  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.297  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.297  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.297  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.297  1018  1128 E WifiNative-wlan0: do suspend false
,08-16 17:43:43.297  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-16 17:43:43.297  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:43:43.297  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-16 17:43:43.297  1018  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:43.317  1018  3640 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:43:43.317  1018  3640 D WifiService: setWifiEnabled: false pid=6720, uid=10171
08-16 17:43:43.317  1018  3640 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:43:43.317  1018  3640 D SecContentProvider2: mCursor = null
08-16 17:43:43.317  1018  3640 D SettingsProvider: name = wifi_on
,08-16 17:43:43.327  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:43.347  1018  1128 E WifiNative-wlan0: do suspend true
,08-16 17:43:43.357  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:43:43.357  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-16 17:43:43.357  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-16 17:43:43.357  1018  1030 D BatteryService: stay LED for fully charged
08-16 17:43:43.357  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:43:43.367  1018  1018 I MotionRecognitionService: Plugged
08-16 17:43:43.367  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:43:43.367  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-16 17:43:43.367  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 17:43:43.367  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
08-16 17:43:43.367  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-16 17:43:43.367  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
08-16 17:43:43.367  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:43:43.387   278  1017 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:43:43.387  1018  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:43.387  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:43:43.387  1018  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:43.387  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-16 17:43:43.387   278  1017 E Netd    : no such netId 503
,08-16 17:43:43.387  1018  1130 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
,08-16 17:43:43.397  1018  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-16 17:43:43.397  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-16 17:43:43.397  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 17:43:43.397  1180  1180 D SViewCoverView: level :100 plugged : 2
,08-16 17:43:43.397  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.397  1018  1130 V NetworkStats: updateIfacesLocked()
08-16 17:43:43.397  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:43.397  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:43.397  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:43:43.397  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-16 17:43:43.397  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-16 17:43:43.397  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-16 17:43:43.397  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:43.397  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:43.397  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.397  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.397  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.397  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.397  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-16 17:43:43.397  1018  1130 V NetworkStats: performPollLocked() took 4ms
,08-16 17:43:43.407  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:43.407  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:43:43.407  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.407  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.407  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.407  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.407  1018  1508 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-16 17:43:43.407  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:43:43.407  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.407  1018  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.407  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:43.417  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.417  2205  2205 I Hs20UtilService: Starting #15
,08-16 17:43:43.417  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.417  1018  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-16 17:43:43.417  1018  7296 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:43.417  1018  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-16 17:43:43.417  1018  7296 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 17:43:43.417  1018  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-16 17:43:43.417  1018  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-16 17:43:43.417  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 17:43:43.417  1018  1127 D WifiP2pService: InactiveState{ what=131204 }
08-16 17:43:43.417  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:43.417  2205  2222 I Hs20UtilService: Message received 5007
08-16 17:43:43.417  1018  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
08-16 17:43:43.417  1018  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 17:43:43.417  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-16 17:43:43.417  1018  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:43.417  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-16 17:43:43.417  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:43:43.417  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:43:43.417  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:43.417  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:43:43.417  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: FAILED
08-16 17:43:43.417  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 17:43:43.417  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:43:43.417  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:43.417  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:43:43.417  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-16 17:43:43.417  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:43:43.427  1292  2321 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 17:43:43.427  1018  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:43.427  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 17:43:43.427  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 17:43:43.427  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-16 17:43:43.427  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:43.427  1018  1048 D WifiDisplayController: disconnect
08-16 17:43:43.427  1018  1048 D WifiDisplayController: updateConnection
08-16 17:43:43.427  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-16 17:43:43.427  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:43:43.427  1018  1127 D WifiP2pService: P2pDisablingState
08-16 17:43:43.427  1018  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 17:43:43.427  1018  1127 D WifiP2pService: p2p socket connection lost
,08-16 17:43:43.427  1018  1127 D WifiP2pService: P2pDisabledState
,08-16 17:43:43.427  1018  1128 E WifiNative-wlan0: do suspend true
,08-16 17:43:43.427  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 17:43:43.427  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:43:43.427  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:43:43.427  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 17:43:43.437  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-16 17:43:43.437  1018  1497 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:43:43.437  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:43:43.437  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:43:43.437  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:43.437  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:43:43.437  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:43:43.437  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:43.437  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:43:43.437  1292  2321 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:43:43.447  7266  7266 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:43:43.447  7266  7266 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-16 17:43:43.447  7266  7266 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:43:43.447  7281  7281 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:43:43.457  1018  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-16 17:43:43.457  1018  1127 D WifiP2pService: DefaultState{ what=143375 }
,08-16 17:43:43.457   278  1017 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:43:43.467  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:43.467  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:43.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.467  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.467  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 17:43:43.467  7222  7222 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-16 17:43:43.477  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:43.477  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:43.477  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.477  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.477  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.477  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.487  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:43.487  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:43.487  1018  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:43.487  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-16 17:43:43.487  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.487  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.487  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.487  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.487  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:43.487  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-16 17:43:43.487  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:43.487  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:43:43.487  1180  1180 D HotspotTile: onReceive : 0, 0
,08-16 17:43:43.487  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:43.487  1018  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:43.497  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:43.497  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.497  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.497  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:43.497  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:43.497  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:43.497  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:43.497  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:43.497  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:43.497  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:43.497  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:43.497  2205  2205 I Hs20UtilService: Starting #16
08-16 17:43:43.497  2205  2222 I Hs20UtilService: Message received 5007
08-16 17:43:43.497  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:43:43.497  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:43:43.497  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:43:43.497  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:43:43.507  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:43.507  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:43.507  1292  2321 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 17:43:43.517  1018  3640 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:43.517  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:43:43.517  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.517  1018  3640 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.517  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:43:43.517  7300  7300 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-16 17:43:43.517  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:43:43.517  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:43.517  6534  6534 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:43.517  6534  6534 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-16 17:43:43.517  7300  7300 I dhcpcd  : version 5.5.6 starting
08-16 17:43:43.527  2205  2205 I Hs20UtilService: Starting #17
08-16 17:43:43.527  7300  7300 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-16 17:43:43.527  2205  2222 I Hs20UtilService: Message received 5011
,08-16 17:43:43.567  7300  7300 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-16 17:43:43.567  7300  7300 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-16 17:43:43.567  7300  7300 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-16 17:43:43.567  7300  7300 I dhcpcd  : bssid match
,08-16 17:43:43.567  7300  7300 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-16 17:43:43.627  7222  7222 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:43:43.667  7222  7222 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-16 17:43:43.667  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:43:43.667  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:43.667  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:43:43.677  7300  7300 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
08-16 17:43:43.677  7300  7300 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-16 17:43:43.697  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 17:43:43.697  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.697  1018  1045 D Tethering: interfaceStatusChanged wlan0, false,
,08-16 17:43:43.697  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.697  1018  1131 D Tethering: InitialState.processMessage what=4
08-16 17:43:43.707  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:43:43.697  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.697  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:43.707  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:43:43.697  1018  1131 E Tethering: No numeric data
08-16 17:43:43.707  1180  1180 D HotspotTile: updateTetherState():false, false
08-16 17:43:43.697  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:43:43.707  1018  1125 V NetworkStats: performPollLocked() took 7ms
08-16 17:43:43.697  1018  1131 D Tethering: clearTetheredNotification()
08-16 17:43:43.707  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.707  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:43.707  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:43:43.707  7222  7222 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-16 17:43:43.707  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.707  7222  7222 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-16 17:43:43.717  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.707  7222  7222 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-16 17:43:43.707  7222  7222 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-16 17:43:43.707  7222  7222 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-16 17:43:43.717  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.717  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:43.717  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.717  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:43.877  7222  7222 I wpa_supplicant: Blacklist: Clear (all) ,
,08-16 17:43:43.947  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.947  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.947  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:43.947  7222  7222 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 17:43:43.947  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.947  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.947  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:44.057  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-16 17:43:44.057  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 17:43:44.057  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:44.067  6917  6917 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:43:44.067  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-16 17:43:44.067  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:44.067  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:44.067  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:44.067  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:44.067  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:44.067  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-16 17:43:44.067  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:44.067  1180  1180 D HotspotTile: onReceive : 1, 0
,08-16 17:43:44.067  2015  2197 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:43:44.067  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:43:44.067  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:44.077  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:44.077  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:44.077  1018  1497 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-16 17:43:44.077  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:44.077  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:44.077  1018  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:44.077  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-16 17:43:44.077  2205  2205 I Hs20UtilService: Starting #18
,08-16 17:43:44.077  2205  2222 I Hs20UtilService: Message received 5011
08-16 17:43:44.087  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:43:44.087  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:44.087  6534  6534 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 17:43:44.087  6534  6534 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:43:44.117  1018  1496 I ActivityManager: Killing 6828:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-16 17:43:44.237   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:44.787   278  1011 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-16 17:43:44.787  1018  1045 D Tethering: interfaceRemoved wlan0
,08-16 17:43:44.787  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 17:43:44.927  1018  1045 D Tethering: interfaceRemoved p2p0
,08-16 17:43:44.927  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 17:43:45.247   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:45.257   288   288 E SMD     : DCD OFF
,08-16 17:43:45.807  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 17:43:46.247   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-16 17:43:46.327  6720  6773 D BluetoothAdapter: enable()
,08-16 17:43:46.337  1018  1494 W ActivityManager: Permission Denial: getCurrentUser() from pid=6720, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:43:46.337  1018  1494 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 17:43:46.337  1018  1494 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6720, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:43:46.337  1018  1494 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 17:43:46.337  1018  1494 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-16 17:43:46.337  1018  1494 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-16 17:43:46.337  1018  1494 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-16 17:43:46.337  1018  1494 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:43:46.337  1018  1494 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:46.337  1018  1494 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:46.337  1018  1494 D SettingsProvider: name = bluetooth_on,
,08-16 17:43:46.347  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:46.347  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-16 17:43:46.347  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-16 17:43:46.347  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-16 17:43:46.347  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:43:46.347  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:46.347  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:46.347  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:46.367  1018  1047 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7330 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
08-16 17:43:46.367  7330  7330 E Zygote  : MountEmulatedStorage()
08-16 17:43:46.367  7330  7330 I libpersona: KNOX_SDCARD checking this for 1002,
08-16 17:43:46.367  7330  7330 E Zygote  : v2
08-16 17:43:46.367  7330  7330 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:46.367  7330  7330 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:46.367  7330  7330 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 17:43:46.377  7330  7330 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:46.397  7330  7330 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:46.397  7330  7330 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:46.417  7330  7330 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 17:43:46.417  7330  7330 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:43:46.447  7330  7330 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-16 17:43:46.477  7330  7330 D BtSettings.ProfileConfig: Adding GattService,
08-16 17:43:46.477  7330  7330 D BtSettings.ProfileConfig: Adding HeadsetService
08-16 17:43:46.477  7330  7330 D BtSettings.ProfileConfig: Adding A2dpService
,08-16 17:43:46.477  7330  7330 D BtSettings.ProfileConfig: Adding HidService
08-16 17:43:46.477  7330  7330 D BtSettings.ProfileConfig: Adding HealthService
,08-16 17:43:46.477  7330  7330 D BtSettings.ProfileConfig: Adding PanService
08-16 17:43:46.477  7330  7330 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-16 17:43:46.477  7330  7330 D BtSettings.ProfileConfig: Adding SapService
08-16 17:43:46.477  7330  7330 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-16 17:43:46.477  7330  7330 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-16 17:43:46.487  7330  7330 D BtSettings.ProfileConfig: Adding SapClientService
08-16 17:43:46.487  7330  7330 D BtSettings.ProfileConfig: Adding HidDevService,
08-16 17:43:46.487  7330  7330 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-16 17:43:46.487  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-16 17:43:46.487  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:46.487  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:46.487  1018  1031 D SettingsProvider: selectionArgs: false
08-16 17:43:46.487  1018  1031 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.487  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.487  1018  1031 D SettingsProvider: ret = -1
08-16 17:43:46.487  1018  3639 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-16 17:43:46.487  1018  3639 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:46.487  1018  3639 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:46.487  1018  3639 D SettingsProvider: selectionArgs: false
08-16 17:43:46.487  1018  3639 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.487  1018  3639 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.487  1018  3639 D SettingsProvider: ret = -1
,08-16 17:43:46.487  1018  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:46.487  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:46.487  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:46.487  1018  1030 D SettingsProvider: selectionArgs: false
08-16 17:43:46.487  1018  1030 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.487  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.487  1018  1030 D SettingsProvider: ret = -1
08-16 17:43:46.487  1018  3640 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-16 17:43:46.487  1018  3640 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:46.487  1018  3640 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:46.487  1018  3640 D SettingsProvider: selectionArgs: false
08-16 17:43:46.487  1018  3640 D SettingsProvider: selectionArgs: 1002,
08-16 17:43:46.487  1018  3640 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.487  1018  3640 D SettingsProvider: ret = -1
08-16 17:43:46.487  1018  1308 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-16 17:43:46.487  1018  1308 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:46.487  1018  1308 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:46.487  1018  1308 D SettingsProvider: selectionArgs: false
08-16 17:43:46.487  1018  1308 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.487  1018  1308 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.487  1018  1308 D SettingsProvider: ret = -1
08-16 17:43:46.487  1018  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
08-16 17:43:46.487  1018  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:46.487  1018  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-16 17:43:46.487  1018  1495 D SettingsProvider: selectionArgs: false
08-16 17:43:46.487  1018  1495 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.487  1018  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.487  1018  1495 D SettingsProvider: ret = -1
08-16 17:43:46.487  1018  1136 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:46.487  1018  1136 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:46.487  1018  1136 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:46.487  1018  1136 D SettingsProvider: selectionArgs: false
08-16 17:43:46.487  1018  1136 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.487  1018  1136 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.487  1018  1136 D SettingsProvider: ret = -1,
,08-16 17:43:46.497  1018  1496 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-16 17:43:46.497  1018  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:46.497  1018  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:46.497  1018  1496 D SettingsProvider: selectionArgs: false
08-16 17:43:46.497  1018  1496 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.497  1018  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.497  1018  1496 D SettingsProvider: ret = -1
08-16 17:43:46.497  1018  1506 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:43:46.497  1018  1506 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:46.497  1018  1506 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:46.497  1018  1506 D SettingsProvider: selectionArgs: false
08-16 17:43:46.497  1018  1506 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.497  1018  1506 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.497  1018  1506 D SettingsProvider: ret = -1,
08-16 17:43:46.497  1018  1494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:46.497  1018  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:46.497  1018  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:43:46.497  1018  1494 D SettingsProvider: selectionArgs: false
08-16 17:43:46.497  1018  1494 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.497  1018  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.497  1018  1494 D SettingsProvider: ret = -1
08-16 17:43:46.497  1018  1508 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-16 17:43:46.497  1018  1508 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:46.497  1018  1508 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:46.497  1018  1508 D SettingsProvider: selectionArgs: false
08-16 17:43:46.497  1018  1508 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.497  1018  1508 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.497  1018  1508 D SettingsProvider: ret = -1
08-16 17:43:46.497  1018  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-16 17:43:46.497  1018  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:46.497  1018  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:46.497  1018  1480 D SettingsProvider: selectionArgs: false
08-16 17:43:46.497  1018  1480 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.497  1018  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.497  1018  1480 D SettingsProvider: ret = -1
,08-16 17:43:46.517  7330  7330 D BluetoothAdapterState: make
,08-16 17:43:46.517  7330  7330 I bluedroid: init
,08-16 17:43:46.517  7330  7345 I BluetoothAdapterState: Entering OffState
,08-16 17:43:46.527  7330  7330 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-16 17:43:46.527  7330  7330 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 17:43:46.527  7330  7330 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 17:43:46.527  7330  7330 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 17:43:46.527  7330  7330 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-16 17:43:46.527  7330  7330 I bluedroid: get_profile_interface socket
08-16 17:43:46.527  7330  7330 I bluedroid: get_profile_interface map_client
,08-16 17:43:46.527  7330  7348 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-16 17:43:46.527  7330  7330 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-16 17:43:46.537  7330  7348 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-16 17:43:46.537  7330  7348 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:43:46.537  7330  7348 I bluedroid: getModelRssiValues
08-16 17:43:46.537  7330  7348 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 17:43:46.537  7330  7348 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:43:46.537  1018  1018 D SettingsProvider: name = bluetooth_name
,08-16 17:43:46.537  7330  7348 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-16 17:43:46.537  7330  7330 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:46.537  1018  1494 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:43:46.547  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:46.547  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:46.547  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.547  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:46.547  7330  7340 I bluedroid: config_hci_snoop_log
,08-16 17:43:46.547  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-16 17:43:46.547  1018  1047 D BluetoothManagerService: Ble is always on enable gatt
,08-16 17:43:46.547  1018  1047 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-16 17:43:46.547  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-16 17:43:46.557  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:43:46.557  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:46.557  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:46.557  7330  7330 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-16 17:43:46.557  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 17:43:46.567  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 17:43:46.567  7330  7345 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-16 17:43:46.567  7330  7345 D BluetoothAdapterProperties: Setting state to 11
,08-16 17:43:46.567  7330  7345 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 17:43:46.567  7330  7345 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 17:43:46.567  7330  7345 D BluetoothAdapterService: updateAdapterState state is 11
,08-16 17:43:46.567  7330  7345 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:46.567  7330  7345 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-16 17:43:46.567  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:46.567  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-16 17:43:46.577  7330  7345 D BluetoothSecureManager: getInstant: null
08-16 17:43:46.577  7330  7345 D BluetoothSecureManager: calling getMethod for getService
,08-16 17:43:46.577  7330  7345 D BluetoothSecureManager: calling getService
,08-16 17:43:46.577  7330  7345 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@11ea5eb5
,08-16 17:43:46.577  1018  1308 D BluetoothSecureManagerService: isSecureModeEnabled
08-16 17:43:46.577  1018  1308 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-16 17:43:46.577  7330  7345 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:43:46.577  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 17:43:46.577  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:43:46.577  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:46.577  1180  1180 D BluetoothTile:  getBluetoothState : 11
,08-16 17:43:46.577  7330  7345 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,08-16 17:43:46.577  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:46.577  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:43:46.577  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:43:46.587  1844  1844 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:46.587  7330  7345 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-16 17:43:46.587  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:46.587  7330  7345 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-16 17:43:46.587  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:43:46.587  7330  7345 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-16 17:43:46.587  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 17:43:46.587  7330  7345 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,08-16 17:43:46.587  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 17:43:46.587  1018  1506 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:46.587  1018  1480 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:43:46.587  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:46.587  7330  7345 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-16 17:43:46.587  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:46.587  7330  7345 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-16 17:43:46.587  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 17:43:46.587  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-16 17:43:46.587  7330  7345 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-16 17:43:46.587  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:43:46.587  1018  3640 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:46.587  7330  7345 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:46.587  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:43:46.597  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:46.597  7330  7345 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:46.597  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 17:43:46.597  7330  7345 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 17:43:46.597  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:43:46.597  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:43:46.597  1018  3640 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:43:46.597  7330  7345 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-16 17:43:46.597  1018  3640 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:46.597  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
08-16 17:43:46.597  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:46.607  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:46.607  7330  7345 D BluetoothBondStateMachine: make
,08-16 17:43:46.607  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 17:43:46.607  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 17:43:46.607  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 17:43:46.607  1018  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:46.607  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 17:43:46.607  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:46.607  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.607  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.607  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-16 17:43:46.607  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:46.607  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:43:46.607  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:43:46.607  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:46.607  7330  7349 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:43:46.607  7330  7330 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:43:46.607  7330  7330 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:43:46.607  7330  7330 D BtGatt.GattService: start()
08-16 17:43:46.607  7330  7330 D BtGatt.GattService: start()
08-16 17:43:46.607  7330  7330 I bluedroid: get_profile_interface gatt
,08-16 17:43:46.607  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-16 17:43:46.607  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:46.617  7330  7330 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:43:46.617  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:46.617  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:46.617  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:46.617  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:46.627  7352  7352 E Zygote  : MountEmulatedStorage()
,08-16 17:43:46.627  7352  7352 E Zygote  : v2
08-16 17:43:46.627  7352  7352 I libpersona: KNOX_SDCARD checking this for 10055
08-16 17:43:46.627  7352  7352 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:46.627  7352  7352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:43:46.627  1018  1031 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7352 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-16 17:43:46.627  7352  7352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:43:46.637  7352  7352 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:46.637  1018  3639 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:46.637  1018  3639 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 17:43:46.637  1018  3639 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.637  1018  3639 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.637  1018  3639 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:46.637  7330  7330 D BtGatt.GattService: mStartError = false
08-16 17:43:46.637  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:46.647  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:43:46.647  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:43:46.647  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:46.647  1018  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:46.647  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:46.647  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.647  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.647  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:46.647  7330  7330 D HeadsetService: Received start request. Starting profile...
08-16 17:43:46.647  7330  7330 D HeadsetService: start()
,08-16 17:43:46.647  7330  7330 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 17:43:46.647  7330  7330 D HeadsetStateMachine: make
08-16 17:43:46.647  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 17:43:46.647  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:46.647  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-16 17:43:46.647  1018  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:46.647  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 17:43:46.647  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.647  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.647  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:46.647  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-16 17:43:46.647  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:43:46.647  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-16 17:43:46.647  1018  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:46.647  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:43:46.657  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.657  1018  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.657  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:46.657  7330  7330 E HeadsetStateMachine: # of Max HF connection is 2
08-16 17:43:46.657  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 17:43:46.657  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:43:46.657  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 17:43:46.657  1018  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:46.657  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:43:46.667  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.667  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.667  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:46.667  7352  7352 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:46.667  7352  7352 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:46.667  1018  1136 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-16 17:43:46.667  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 17:43:46.667  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:43:46.667  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:46.667  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:46.667  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.667  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.667  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:43:46.677  1018  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:46.677  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:43:46.677  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.677  1018  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.677  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:46.677  1018  1494 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-16 17:43:46.677  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 17:43:46.677  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 17:43:46.677  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:43:46.677  7330  7345 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:43:46.677  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.677  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.677  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:43:46.677  7330  7330 I bluedroid: get_profile_interface handsfree
,08-16 17:43:46.677  1018  1308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:46.687  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:43:46.687  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.687  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.687  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:46.687  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:46.687  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:46.687  7330  7345 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:46.687  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:46.687  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:46.687  7330  7345 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:46.687  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:43:46.687  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:43:46.687  7330  7345 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:43:46.687  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:43:46.687  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:43:46.687  7330  7345 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:43:46.687  7330  7345 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-16 17:43:46.697  7352  7352 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-16 17:43:46.697  7330  7330 I DualScoManager: Instantiating Dual Sco Manager
08-16 17:43:46.697  7330  7330 I DualScoManager: Set HeadsetServiceHelper
08-16 17:43:46.697  7330  7330 D BluetoothAtMessage: createCMTIContentObservers
,08-16 17:43:46.707  1018  1494 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-16 17:43:46.707  1018  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:46.707  1018  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:46.707  1018  1494 D SettingsProvider: selectionArgs: false
08-16 17:43:46.707  1018  1494 D SettingsProvider: selectionArgs: 1002
08-16 17:43:46.707  1018  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:46.707  1018  1494 D SettingsProvider: ret = -1
,08-16 17:43:46.707  7330  7361 D HeadsetStateMachine: Enter Disconnected: -2
,08-16 17:43:46.707  7330  7330 D HeadsetService: mStartError = false
08-16 17:43:46.707  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:46.707  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-16 17:43:46.707  7330  7361 D HeadsetStateMachine: Clear mHeadsetBrsf
08-16 17:43:46.707  7330  7361 D HeadsetStateMachine: map size, before remove : 0
08-16 17:43:46.707  7330  7361 D HeadsetStateMachine: map size, after remove: 0
,08-16 17:43:46.707  7330  7330 D A2dpService: Received start request. Starting profile...
08-16 17:43:46.707  7330  7330 D A2dpService: start()
,08-16 17:43:46.717  7330  7330 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 17:43:46.717  7330  7330 I bluedroid: get_profile_interface avrcp
,08-16 17:43:46.717  7330  7330 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 17:43:46.727  7330  7330 D Avrcp   : Initialize Media Controller
,08-16 17:43:46.727  7330  7330 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-16 17:43:46.727  7330  7330 E Avrcp   : getActiveSessions
,08-16 17:43:46.727  7330  7330 D Avrcp   : pick active media Controller
08-16 17:43:46.727  7330  7330 D Avrcp   : Get the active Media Controller 
,08-16 17:43:46.727  7352  7352 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-16 17:43:46.727  7352  7352 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-16 17:43:46.727  7352  7352 D UserAnalysis: Create SecureDbHelper
,08-16 17:43:46.737  7352  7352 D IntelligenceServiceApplication: onCreate()
,08-16 17:43:46.737  1018  1308 I ActivityManager: Killing 6961:com.sec.pcw.device/1000 (adj 15): empty #21
,08-16 17:43:46.747  7330  7330 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 17:43:46.747  7330  7373 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-16 17:43:46.747  7352  7352 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-16 17:43:46.747  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-16 17:43:46.747  7330  7330 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:43:46.747  7330  7330 D A2dpStateMachine: make
08-16 17:43:46.747  7330  7330 I bluedroid: get_profile_interface a2dp
08-16 17:43:46.747  7330  7375 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 17:43:46.747  7330  7330 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 17:43:46.757  7352  7352 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-16 17:43:46.757  7330  7330 D A2dpService: mStartError = false
08-16 17:43:46.757  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:46.757  7330  7374 D A2dpStateMachine: Enter Disconnected: -2
,08-16 17:43:46.757  7330  7330 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:43:46.757  7330  7330 D HidService: Received start request. Starting profile...
08-16 17:43:46.757  7330  7330 D HidService: start()
08-16 17:43:46.757  7330  7330 I bluedroid: get_profile_interface hidhost
08-16 17:43:46.757  7330  7330 D HidService: setHidService(): set to: null
08-16 17:43:46.757  7330  7330 D HidService: mStartError = false
08-16 17:43:46.757  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:46.757  7330  7330 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 17:43:46.757  7330  7373 D BluetoothMediaBrowser: no now playing list
08-16 17:43:46.757  7330  7373 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 17:43:46.767  7330  7330 D HealthService: Received start request. Starting profile...
08-16 17:43:46.767  7330  7330 D HealthService: start()
,08-16 17:43:46.767  7330  7330 I bluedroid: get_profile_interface health
,08-16 17:43:46.767  7330  7330 D HealthService: mStartError = false
08-16 17:43:46.767  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:46.767  7330  7330 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 17:43:46.767  7330  7330 D PanService: Received start request. Starting profile...
08-16 17:43:46.767  7330  7330 D PanService: start()
08-16 17:43:46.767  7330  7330 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:43:46.767  7330  7330 I bluedroid: get_profile_interface pan
,08-16 17:43:46.767  7330  7330 D PanService: mStartError = false
08-16 17:43:46.767  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:46.767  7330  7330 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 17:43:46.767  7352  7352 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-16 17:43:46.767  1440  1461 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 17:43:46.777  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-16 17:43:46.777  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:43:46.777  1440  1461 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 17:43:46.777  7330  7330 D BluetoothMapService: Received start request. Starting profile...,
,08-16 17:43:46.777  7330  7330 D BluetoothMapService: start()
,08-16 17:43:46.777  7330  7330 D BluetoothMapService: mStartError = false,
08-16 17:43:46.777  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:46.777  7330  7330 D HeadsetStateMachine: Proxy object connected
08-16 17:43:46.777  7330  7330 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-16 17:43:46.787  7330  7330 D SapService: Received start request. Starting profile...
,08-16 17:43:46.787  7330  7330 D SapService: start()
08-16 17:43:46.787  7330  7330 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 17:43:46.787  7330  7330 I bluedroid: get_profile_interface sap
08-16 17:43:46.787  7330  7330 D SapService: mStartError = false
08-16 17:43:46.787  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:46.787  7330  7330 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-16 17:43:46.787  7330  7330 D HeadsetPhoneState: sendDeviceDataStateChanged
08-16 17:43:46.787  7330  7330 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-16 17:43:46.787  7330  7330 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 17:43:46.787  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-16 17:43:46.787  7330  7330 D BluetoothA2dp: Proxy object connected
08-16 17:43:46.787  7330  7330 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-16 17:43:46.787  7330  7361 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:43:46.787  7330  7361 D HeadsetStateMachine: Disconnected process message: 18
08-16 17:43:46.787  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 17:43:46.787  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-16 17:43:46.787  7330  7361 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:43:46.787  1018  1508 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-16 17:43:46.787  7330  7361 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 17:43:46.787  7330  7361 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:43:46.787  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:46.787  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:46.787  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:46.787  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:46.807  7380  7380 E Zygote  : MountEmulatedStorage()
,08-16 17:43:46.807  7380  7380 E Zygote  : v2
08-16 17:43:46.807  7380  7380 I libpersona: KNOX_SDCARD checking this for 10105
08-16 17:43:46.807  7380  7380 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:46.807  7380  7380 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:43:46.807  7380  7380 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 17:43:46.807  1018  1508 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7380 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-16 17:43:46.807  7380  7380 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:43:46.817  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-16 17:43:46.817  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 17:43:46.837  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-16 17:43:46.837  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 17:43:46.847  7380  7380 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:46.847  7380  7380 D ActivityThread: Added TimaKeyStore provider
08-16 17:43:46.847  7330  7345 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-16 17:43:46.847  7330  7345 I bluedroid: enable
,08-16 17:43:46.847  7330  7345 I bt_hci_bdroid: init
08-16 17:43:46.847  7330  7395 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-16 17:43:46.857  7330  7345 I bt_vendor: bt-vendor : init
08-16 17:43:46.857  7330  7345 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 17:43:46.857  7330  7345 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 17:43:46.857  7330  7345 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-16 17:43:46.857  7330  7345 D bt_userial_mct: userial_init
,08-16 17:43:46.857  7330  7345 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 17:43:46.857  7330  7345 I bt_vendor: Starting hciattach daemon
08-16 17:43:46.857  7330  7345 I bt_vendor: try to set false
,08-16 17:43:46.857  7330  7345 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-16 17:43:46.857  7330  7345 I bt_vendor: Starting hciattach daemon
08-16 17:43:46.857  7330  7345 I bt_vendor: try to set true
,08-16 17:43:46.877  7399  7399 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-16 17:43:46.927  7405  7405 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-16 17:43:46.927  7406  7406 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 17:43:46.947  7410  7410 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 17:43:46.957  7411  7411 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-16 17:43:46.967  7412  7412 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 17:43:46.977  7413  7413 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-16 17:43:46.997   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-16 17:43:46.997   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:46.997  7380  7414 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-16 17:43:46.997   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-16 17:43:46.997   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:46.997  7380  7414 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-16 17:43:47.147  7380  7380 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 17:43:47.147  7380  7380 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:47.147  7380  7380 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:47.147  7380  7380 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.e.b(PG:170)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:47.147  7380  7380 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.k.d(PG:583)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.e.b(PG:170)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:47.147  7380  7380 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:47.147  7380  7380 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:47.147  7380  7380 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:47.147  7380  7380 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:47.147  1018  1480 I ActivityManager: Killing 6978:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
08-16 17:43:47.157  2015  2015 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-16 17:43:47.157  2015  2015 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:43:47.197  7428  7428 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
08-16 17:43:47.207  7429  7429 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 17:43:47.217  7380  7416 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 17:43:47.257  7330  7345 I bt_vendor: bluetooth satus is on
,08-16 17:43:47.257  7330  7397 D bt_userial_mct: userial_open(port:0)
08-16 17:43:47.257  7330  7397 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 17:43:47.267  7330  7397 I bt_vendor: Done intiailizing UART
,08-16 17:43:47.267  7330  7397 I bt_vendor: Done intiailizing UART
08-16 17:43:47.267  7330  7397 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-16 17:43:47.267  7330  7397 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 17:43:47.277  7330  7432 D bt_userial_mct: Entering userial_read_thread()
,08-16 17:43:47.397  1018  1308 I art     : Explicit concurrent mark sweep GC freed 92477(5MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.376ms total 159.079ms
,08-16 17:43:47.397  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:47.397  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:47.397  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:47.397  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_SAP
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 17:43:47.407  7330  7395 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-16 17:43:47.507  7330  7395 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-16 17:43:47.507  7330  7395 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa410fed1 
,08-16 17:43:47.507  7330  7395 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa410fed1 
,08-16 17:43:47.517  7330  7348 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-16 17:43:47.527  7330  7348 E bt-btif : Calling BTA_HhEnable
,08-16 17:43:47.527  7330  7348 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 17:43:47.527  7330  7348 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-16 17:43:47.527  7330  7348 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:43:47.527  7330  7348 I bluedroid: getModelRssiValues
,08-16 17:43:47.527  7330  7348 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-16 17:43:47.527  7330  7348 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:43:47.537  1018  1018 D SettingsProvider: name = bluetooth_name
,08-16 17:43:47.537  7330  7348 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-16 17:43:47.537  7330  7348 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:43:47.537  7330  7348 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:43:47.537  7330  7348 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:43:47.537  7330  7348 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-16 17:43:47.547  7330  7348 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-16 17:43:47.547  7330  7348 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-16 17:43:47.547  7330  7348 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 17:43:47.547  7330  7348 E bt-btif : btif_sock_init: !vhci_init
,08-16 17:43:47.547  7330  7348 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-16 17:43:47.547  7330  7348 D IOP_DB_BT: db_open: db_open : handle 3028070416l, read 13894 bytes onto local cache
,08-16 17:43:47.547  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:47.547  7330  7348 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-16 17:43:47.547  7330  7348 D IOP_DB_BT: db_query: result 1
08-16 17:43:47.547  7330  7348 I         : iop_db_open: iop_db_open status 0
,08-16 17:43:47.547  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:47.547  7330  7348 D bte_conf: Device ID record 1 : primary
08-16 17:43:47.547  7330  7348 D bte_conf:   vendorId            = 0075
08-16 17:43:47.547  7330  7348 D bte_conf:   vendorIdSource      = 0001
08-16 17:43:47.547  7330  7348 D bte_conf:   product             = 0100
08-16 17:43:47.547  7330  7348 D bte_conf:   version             = 0200
08-16 17:43:47.547  7330  7348 D bte_conf:   clientExecutableURL = 
08-16 17:43:47.547  7330  7348 D bte_conf:   serviceDescription  = 
08-16 17:43:47.547  7330  7348 D bte_conf:   documentationURL    = 
08-16 17:43:47.547  7330  7348 D bte_conf: bte_load_did_conf no section named DID2.
,08-16 17:43:47.547  7330  7348 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 17:43:47.557  7330  7345 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 17:43:47.557  7330  7345 D BluetoothAdapterProperties: ScanMode =  20
,08-16 17:43:47.557  7330  7345 D BluetoothAdapterProperties: State =  11
,08-16 17:43:47.557  1018  1495 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:43:47.557  7330  7345 D BluetoothAdapterProperties: Setting state to 12
08-16 17:43:47.557  7330  7345 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 17:43:47.557  7330  7432 E bt_mct  : hci lib postload completed
,08-16 17:43:47.557  7330  7348 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:43:47.557  7330  7348 D BluetoothAdapterProperties: Scan Mode:21
08-16 17:43:47.557  7330  7348 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:43:47.567  1018  1494 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-16 17:43:47.567  1018  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:47.567  1018  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:47.567  1018  1494 D SettingsProvider: selectionArgs: false
,08-16 17:43:47.567  1018  1494 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:47.567  1018  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:43:47.567  1018  1494 D SettingsProvider: ret = -1
,08-16 17:43:47.567  7330  7345 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 17:43:47.567  7330  7345 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 17:43:47.567  1018  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:47.567  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:43:47.577  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:47.577  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:47.577  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.577  7330  7345 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:47.577  7330  7345 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 17:43:47.577  7330  7345 D BluetoothAdapterService: starting service from this receiver
,08-16 17:43:47.577  1018  1308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:47.577  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 17:43:47.577  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:47.587  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:47.587  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.587  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.587  7330  7345 I BluetoothAdapterState: Entering On State from state = 11
,08-16 17:43:47.587  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:47.587  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:43:47.587  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:47.587  2015  2192 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:47.587  2015  2192 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:47.597  1018  1047 D BluetoothPan: Binding service...
,08-16 17:43:47.597  6720  6720 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-16 17:43:47.597  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:43:47.597  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:47.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:47.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:47.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:47.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:47.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:47.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:47.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:47.597  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:43:47.597  1180  5372 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:47.597  1180  5372 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:47.597  7330  7338 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:43:47.607  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:47.607  1292  1301 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:43:47.607  1292  1301 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:47.607  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-16 17:43:47.617  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:47.617  7330  7330 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-16 17:43:47.617  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:47.617  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.617  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.617  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:47.617  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:47.617  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:47.617  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:47.617  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:47.617  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:47.617  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:47.617  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:47.617  1292  1301 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:47.617  1292  1301 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:47.617  1292  1292 D BluetoothA2dp: Proxy object connected
,08-16 17:43:47.617  1292  1292 D A2dpProfile: Bluetooth service connected
,08-16 17:43:47.627  1440  1461 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:47.627  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:47.627  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:43:47.627  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:47.627  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:47.627  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.627  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.627  1440  1461 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:47.627  6720  6732 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:47.627  6720  6732 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:47.637  1292  1300 D BluetoothPan: Binding service...
,08-16 17:43:47.637  7330  7330 I BluetoothPbapService: Handler(): got msg=1
,08-16 17:43:47.637  1018  1496 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:43:47.637  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:43:47.637  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:43:47.637  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:47.637  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.637  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.637  1292  1292 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:43:47.637  1292  1292 D PanProfile: Bluetooth service connected
,08-16 17:43:47.637  7380  7391 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:47.637  7380  7391 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:47.637  1292  7437 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:43:47.647  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 17:43:47.647  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-16 17:43:47.647  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-16 17:43:47.647  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:47.647  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.647  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.647  7330  7438 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 17:43:47.647  1440  1461 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:47.647  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:47.647  1292  1292 D BluetoothMap: Proxy object connected
08-16 17:43:47.647  1292  1292 D MapProfile: Bluetooth service connected
08-16 17:43:47.647  1292  1292 D BluetoothMap: getConnectedDevices()
,08-16 17:43:47.647  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:47.647  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:47.647  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.647  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.647  1440  1461 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:47.657  1468  3313 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:47.657  7330  7438 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:43:47.657  7330  7438 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:43:47.657  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:43:47.657  7330  7438 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-16 17:43:47.657  7330  7438 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:43:47.657  7330  7438 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:43:47.657  7330  7438 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1260194e
,08-16 17:43:47.657  7330  7438 D BluetoothSocket: channel: 19
08-16 17:43:47.657  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:43:47.657  7330  7438 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 17:43:47.657  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:47.657  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:47.657  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.657  1468  3313 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:47.657  1292  1300 D Bluetoothsap: onBluetoothStateChange: up=true
,08-16 17:43:47.657  1292  1300 D Bluetoothsap: Binding service...
,08-16 17:43:47.667  1292  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 17:43:47.667  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-16 17:43:47.667  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:43:47.667  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:47.667  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.667  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.667  1292  1300 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 17:43:47.667  1440  1485 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:43:47.667  1440  1485 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:47.667  1292  1292 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 17:43:47.677  7330  7338 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:47.677  7330  7338 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:47.677  1292  1292 D SapProfile: Bluetooth service connected
08-16 17:43:47.677  1292  1292 D Bluetoothsap: getConnectedDevices()
,08-16 17:43:47.677  1292  1301 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:47.677  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:47.677  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:47.677  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:47.677  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.677  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.677  1292  1301 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 17:43:47.677  1292  1292 D HeadsetProfile: Bluetooth service connected
,08-16 17:43:47.677  1468  1484 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:47.677  1468  1484 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:47.677  1440  1461 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:47.677  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:47.677  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:47.677  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:47.677  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.677  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.677  1440  1461 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:47.677  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:43:47.677  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:47.677  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:43:47.677  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-16 17:43:47.677  1018  1018 D BluetoothA2dp: Proxy object connected
08-16 17:43:47.677  1292  1300 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 17:43:47.687  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-16 17:43:47.687  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:43:47.687  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:47.687  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.687  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.687  1448  1481 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:47.687  1448  1481 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:47.687  1292  1301 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:43:47.687  1292  1292 D BluetoothPbap: Proxy object connected
,08-16 17:43:47.687  1292  1292 D PbapServerProfile: Bluetooth service connected
,08-16 17:43:47.687  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-16 17:43:47.687  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:43:47.687  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:47.687  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:47.687  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.697  1292  1292 D BluetoothInputDevice: Proxy object connected
08-16 17:43:47.697  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:47.697  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:47.697  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 17:43:47.697  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:43:47.697  1292  1292 D HidProfile: Bluetooth service connected
,08-16 17:43:47.697  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:47.697  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-16 17:43:47.697  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:43:47.697  1440  1440 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@172994aa, true
,08-16 17:43:47.707  1440  1440 D BluetoothHeadset: registerMessageListener
,08-16 17:43:47.707  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:43:47.707  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:43:47.707  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:47.707  1180  1180 D BluetoothTile:  getBluetoothState : 12
,08-16 17:43:47.707  1844  1844 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:47.707  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:47.717  1018  3640 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:47.717  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-16 17:43:47.717  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:47.717  7330  7340 D HeadsetService: registerMessageListener
,08-16 17:43:47.717  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:47.717  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:47.717  1018  3640 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:47.717  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:47.727  7330  7340 D HeadsetService: registerMessageListener
,08-16 17:43:47.727  7330  7361 D HeadsetStateMachine: Disconnected process message: 70
08-16 17:43:47.727  7330  7361 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3af4ba6f
,08-16 17:43:47.727  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-16 17:43:47.727  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:43:47.727  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:47.727  1292  1292 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-16 17:43:47.727  1292  1292 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-16 17:43:47.737  1018  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:47.737  1018  1495 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-16 17:43:47.737  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-16 17:43:47.737  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-16 17:43:47.737  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 17:43:47.737  1292  1292 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-16 17:43:47.737  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:43:47.737  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:47.737  7330  7361 D HeadsetStateMachine: Disconnected process message: 9
08-16 17:43:47.737  1292  1292 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-16 17:43:47.737  7330  7361 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 17:43:47.737  7330  7441 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 17:43:47.737  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:47.747  7330  7441 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:43:47.747  7330  7441 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:43:47.747   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-16 17:43:47.747   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 17:43:47.747   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-16 17:43:47.747   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 17:43:47.747   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 17:43:47.747   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 17:43:47.747   283   283 V audio_hw_primary: adev_set_parameters: exit
08-16 17:43:47.747  7330  7441 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-16 17:43:47.747  7330  7441 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:43:47.747  7330  7441 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:43:47.747  7330  7441 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bdb637c
08-16 17:43:47.747  7330  7361 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 17:43:47.747  7330  7441 D BluetoothSocket: channel: 5
,08-16 17:43:47.747  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:47.757  1018  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 17:43:47.757  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:43:47.757  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:47.757  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.757  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:43:47.767  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:47.767  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:47.777  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:47.777  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 17:43:47.787  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:47.787  7330  7330 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 17:43:47.787  1018  1308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:47.787  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 17:43:47.787  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:47.787  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.787  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:47.797  2015  2015 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:43:47.797  1018  3639 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:47.797  1018  3639 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 17:43:47.807  1018  3639 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:47.807  1018  3639 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:47.807  1018  3639 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:47.807  2015  2015 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:43:47.817  2015  7448 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 17:43:47.817  1018  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:47.817  1018  1506 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:43:47.817  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:47.817  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:47.817  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:47.827  7330  7452 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:43:47.827  7330  7452 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:43:47.837  7330  7452 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-16 17:43:47.837  7330  7452 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:43:47.837  7330  7452 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:43:47.837  7330  7452 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@be20426
,08-16 17:43:47.837  7330  7452 D BluetoothSocket: channel: 12
08-16 17:43:47.837  7330  7452 I BtOppRfcommListener: Accept thread started.
,08-16 17:43:47.837  1018  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:47.837  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:47.837  1018  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:47.837  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:47.847  2015  7448 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-16 17:43:48.257   288   288 E SMD     : DCD OFF
,08-16 17:43:49.357  6720  6773 D BluetoothAdapter: disable()
,08-16 17:43:49.357  1018  1136 D SettingsProvider: name = bluetooth_on
,08-16 17:43:49.367  7330  7345 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-16 17:43:49.367  7330  7345 D BluetoothAdapterProperties: Setting state to 13
08-16 17:43:49.367  7330  7345 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:43:49.367  7330  7345 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:43:49.367  7330  7345 D BluetoothAdapterService: updateAdapterState state is 13
,08-16 17:43:49.367  1018  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:49.367  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:43:49.377  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:49.377  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:49.377  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:49.377  7330  7330 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-16 17:43:49.377  7330  7345 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:49.377  7330  7345 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-16 17:43:49.377  7330  7345 D BluetoothAdapterService: terminating service from this receiver
,08-16 17:43:49.377  7330  7330 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7e38867, channel: 19, state: LISTENING
,08-16 17:43:49.377  7330  7330 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@7e38867, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1260194e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@161aa614mSocket: android.net.LocalSocket@f6afebd impl:android.net.LocalSocketImpl@2d5a3cb2 fd:FileDescriptor[74]
08-16 17:43:49.377  7330  7330 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@f6afebd impl:android.net.LocalSocketImpl@2d5a3cb2 fd:FileDescriptor[74]
,08-16 17:43:49.377  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:49.377  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-16 17:43:49.387  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:43:49.387  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:43:49.397  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:49.397  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:49.397  1180  1180 D BluetoothTile:  getBluetoothState : 13
,08-16 17:43:49.397  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:49.397  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:43:49.397  1018  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:49.407  1018  1495 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:43:49.407  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:43:49.407  1844  1844 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:49.407  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:49.417  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:49.417  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:49.417  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:49.417  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:49.417  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:49.417  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:49.417  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:49.417  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:49.417  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:49.417  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:49.417  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:49.417  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 17:43:49.427  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:49.427  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:49.427  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:49.427  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:49.427  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:49.427  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:49.427  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:49.427  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:49.427  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:49.427  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:49.427  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:49.427  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:49.427  6720  6720 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:49.427  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:43:49.427  7330  7345 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 17:43:49.427  7330  7345 D BluetoothAdapterProperties: mDiscovering is false
,08-16 17:43:49.427  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:49.427  1018  3640 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:49.427  1018  1497 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:43:49.427  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:43:49.437  7330  7345 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 17:43:49.437  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:49.437  1018  3640 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:49.437  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:49.437  1018  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 17:43:49.447  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:43:49.447  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:49.447  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:49.447  7330  7348 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:43:49.447  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:43:49.447  7330  7348 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:43:49.457  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:49.457  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:49.457  1292  1292 D BluetoothPbap: Proxy object disconnected
08-16 17:43:49.457  1292  1292 D PbapServerProfile: Bluetooth service disconnected
,08-16 17:43:49.467  7330  7345 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 17:43:49.467  7330  7345 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-16 17:43:49.467  7330  7345 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-16 17:43:49.467  7330  7345 E bt-btif : cmd socket is not created
,08-16 17:43:49.467  7330  7452 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 17:43:49.467  7330  7395 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-16 17:43:49.467  7330  7345 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 17:43:49.467  7330  7395 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 17:43:49.467  7330  7395 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:49.467  7330  7395 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:49.467  7330  7395 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 17:43:49.477  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:49.477  7330  7330 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@31964403, channel: 5, state: LISTENING
08-16 17:43:49.477  7330  7330 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@31964403, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bdb637c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3060f80mSocket: android.net.LocalSocket@1f4dc9b9 impl:android.net.LocalSocketImpl@5ab71fe fd:FileDescriptor[76]
08-16 17:43:49.477  7330  7330 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1f4dc9b9 impl:android.net.LocalSocketImpl@5ab71fe fd:FileDescriptor[76]
,08-16 17:43:49.477  7330  7330 I BtOppRfcommListener: stopping Accept Thread
08-16 17:43:49.477  7330  7330 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f2f1d5f, channel: 12, state: LISTENING
08-16 17:43:49.477  7330  7330 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f2f1d5f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@be20426, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@287ca3acmSocket: android.net.LocalSocket@39f84875 impl:android.net.LocalSocketImpl@1448b00a fd:FileDescriptor[80]
08-16 17:43:49.477  7330  7330 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@39f84875 impl:android.net.LocalSocketImpl@1448b00a fd:FileDescriptor[80]
08-16 17:43:49.477  7330  7452 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 17:43:49.477  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:49.487  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:49.487  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 17:43:49.487  7330  7330 V BluetoothOppManager: cleanUp...
,08-16 17:43:49.517  2015  2015 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:43:49.527  2015  2015 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:43:49.677  7330  7395 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 17:43:49.677  7330  7395 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:49.677  7330  7395 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:43:49.677  7330  7395 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:49.677  7330  7395 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:49.677  7330  7395 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:43:49.677  7330  7395 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:49.677  7330  7395 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:49.677  7330  7395 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:43:49.677  7330  7395 W bt-btif : ag scb idx 1 not allocated
08-16 17:43:49.677  7330  7395 W bt-btif : ag scb idx 2 not allocated
08-16 17:43:49.677  7330  7395 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 17:43:49.677  7330  7432 I bt_userial_mct: exiting userial_read_thread
08-16 17:43:49.677  7330  7432 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 17:43:49.677  7330  7348 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 17:43:49.677  7330  7397 I bt_vendor: hw_epilog_process
08-16 17:43:49.677  7330  7348 D bt_userial_mct: userial_close
08-16 17:43:49.677  7330  7348 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 17:43:50.597  1018  3350 D SSRM:n  : SIOP:: AP = 330
,08-16 17:43:50.787  7330  7348 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 17:43:50.787  7330  7348 I bt_vendor: bluetooth satus is on
,08-16 17:43:50.787  7330  7348 I bt_vendor: bt-vendor : resetting BT status
08-16 17:43:50.787  7330  7348 I bt_vendor: Starting hciattach daemon
,08-16 17:43:50.787  7330  7348 I bt_vendor: try to set false
,08-16 17:43:50.787  7330  7348 I bt_vendor: Starting hciattach daemon
,08-16 17:43:50.787  7330  7348 I bt_vendor: try to set false
,08-16 17:43:50.787  7330  7348 I bt_vendor: cleanup,
,08-16 17:43:50.787  7330  7395 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
,08-16 17:43:50.787  7330  7348 I GKI_LINUX: GKI_exit_task 0 done
08-16 17:43:50.787  7330  7348 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-16 17:43:50.797  7330  7345 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-16 17:43:50.797  7330  7345 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 17:43:50.797  7330  7345 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-16 17:43:50.797  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-16 17:43:50.797  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 17:43:50.797  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 17:43:50.797  1018  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-16 17:43:50.797  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
,08-16 17:43:50.797  1018  1136 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:43:50.797  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:50.797  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-16 17:43:50.807  7330  7330 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 17:43:50.807  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:43:50.807  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:43:50.807  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:50.807  1018  1308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:50.807  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-16 17:43:50.807  7330  7330 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:43:50.807  7330  7330 D BtGatt.GattService: stop()
,08-16 17:43:50.807  7330  7330 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:43:50.807  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:50.807  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:50.807  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:50.807  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:43:50.807  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:43:50.807  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:50.807  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:50.807  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.807  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:50.807  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:50.807  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:50.817  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:50.817  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-16 17:43:50.817  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:50.817  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:43:50.817  1018  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:50.817  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.817  7330  7330 D HeadsetService: Received stop request...Stopping profile...
,08-16 17:43:50.817  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:50.817  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:50.817  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:50.817  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:43:50.817  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:43:50.817  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:43:50.817  1018  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:50.817  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:50.817  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.817  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:50.817  1018  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:50.817  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:50.827  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-16 17:43:50.827  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 17:43:50.827  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 17:43:50.827  1018  1308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-16 17:43:50.827  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.827  1018  1308 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:50.827  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:50.827  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:50.827  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 17:43:50.827  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:43:50.827  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:50.827  7330  7345 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:50.827  1018  3640 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:50.837  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0,
08-16 17:43:50.837  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:50.837  1018  3640 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:50.837  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:50.837  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 17:43:50.837  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:43:50.837  7330  7345 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:43:50.837  1018  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:50.837  1292  1292 D HeadsetProfile: Bluetooth service disconnected
,08-16 17:43:50.837  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.837  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:50.837  1018  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:50.837  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:50.837  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:43:50.837  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:43:50.847  7330  7345 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:50.847  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:43:50.847  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:50.847  7330  7345 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:43:50.847  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:43:50.847  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 17:43:50.847  7330  7345 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-16 17:43:50.847  7330  7345 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:43:50.847  7330  7345 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 17:43:50.847  7330  7345 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:43:50.847  7330  7345 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-16 17:43:50.847  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-16 17:43:50.847  7330  7330 D A2dpService: Received stop request...Stopping profile...
08-16 17:43:50.847  7330  7374 D A2dpStateMachine: Exit Disconnected: -1
,08-16 17:43:50.847  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:50.847  1018  1018 D BluetoothA2dp: Proxy object disconnected
,08-16 17:43:50.857  1292  1292 D BluetoothA2dp: Proxy object disconnected
08-16 17:43:50.857  1292  1292 D A2dpProfile: Bluetooth service disconnected
,08-16 17:43:50.857  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 17:43:50.857  7330  7330 D HidService: Received stop request...Stopping profile...
,08-16 17:43:50.857  7330  7330 D HidService: Stopping Bluetooth HidService
,08-16 17:43:50.857  7330  7330 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:43:50.857  7330  7330 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,08-16 17:43:50.857  7330  7330 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:43:50.857  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:50.857  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-16 17:43:50.857  7330  7330 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:50.857  7330  7330 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 17:43:50.857  7330  7330 D HealthService: Received stop request...Stopping profile...
,08-16 17:43:50.857  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:50.857  1292  1292 D BluetoothInputDevice: Proxy object disconnected
,08-16 17:43:50.857  1292  1292 D HidProfile: Bluetooth service disconnected
,08-16 17:43:50.867  7330  7330 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 17:43:50.867  7330  7330 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 17:43:50.867  7330  7330 D PanService: Received stop request...Stopping profile...
08-16 17:43:50.867  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:50.867  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:43:50.867  1292  1292 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:43:50.867  7330  7330 D BluetoothMapService: Received stop request...Stopping profile...
08-16 17:43:50.867  1292  1292 D PanProfile: Bluetooth service disconnected
,08-16 17:43:50.867  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:50.867  7330  7330 D SapService: Received stop request...Stopping profile...
,08-16 17:43:50.867  7330  7330 D SapService: Stopping Bluetooth SapService
08-16 17:43:50.867  7330  7330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:50.867  1292  1292 D BluetoothMap: Proxy object disconnected
08-16 17:43:50.867  1292  1292 D MapProfile: Bluetooth service disconnected
,08-16 17:43:50.877  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-16 17:43:50.877  7330  7330 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:43:50.877  7330  7330 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 17:43:50.877  7330  7330 D BluetoothA2dp: Proxy object disconnected
,08-16 17:43:50.877  7330  7330 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-16 17:43:50.877  7330  7375 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-16 17:43:50.877  7330  7330 I GKI_LINUX: GKI_exit_task 2 done
08-16 17:43:50.877  7330  7330 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-16 17:43:50.877  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 17:43:50.877  7330  7330 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:50.877  7330  7330 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:50.877  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 17:43:50.877  7330  7330 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:50.877  7330  7330 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:50.877  7330  7330 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:43:50.877  7330  7330 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:43:50.877  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 17:43:50.877  7330  7330 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:50.877  7330  7330 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:50.877  7330  7330 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:43:50.877  7330  7330 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 17:43:50.877  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-16 17:43:50.877  7330  7330 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 17:43:50.877  7330  7330 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-16 17:43:50.877  7330  7330 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-16 17:43:50.877  7330  7330 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 17:43:50.877  7330  7330 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-16 17:43:50.877  1292  1292 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-16 17:43:50.877  1292  1292 D SapProfile: Bluetooth service disconnected
,08-16 17:43:50.887  7330  7345 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 17:43:50.887  7330  7345 D BluetoothAdapterProperties: Setting state to 10
08-16 17:43:50.887  7330  7345 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 17:43:50.887  7330  7345 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:43:50.887  7330  7345 D BluetoothAdapterService: updateAdapterState state is 10
,08-16 17:43:50.887  7330  7345 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:50.887  2015  2188 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:50.887  2015  2188 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:50.887  1180  1189 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:50.887  7330  7345 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 17:43:50.887  7330  7345 I BluetoothAdapterState: Entering OffState
08-16 17:43:50.887  1180  1189 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
08-16 17:43:50.887  7330  7363 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:43:50.887  1292  1301 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:43:50.887  1292  7437 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:50.887  1292  7437 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:50.887  6720  6732 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:50.887  6720  6732 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:43:50.887  6720  6732 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-16 17:43:50.887  6720  6732 D BluetoothLeAdvertiser: Exit stop advertising
08-16 17:43:50.887  6720  6732 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 17:43:50.887  6720  6732 D BluetoothLeScanner: Exiting stopAllScan
,08-16 17:43:50.887  7380  7394 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:50.887  7380  7394 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:50.897  1292  1301 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 17:43:50.897  1292  7437 D Bluetoothsap: onBluetoothStateChange: up=false
,08-16 17:43:50.897  1292  7437 D Bluetoothsap: Unbinding service...
,08-16 17:43:50.897  1440  1461 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:50.897  1440  1461 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:50.897  7330  7338 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:50.897  7330  7338 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:50.897  1468  1633 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:50.897  1468  1633 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:50.897  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:43:50.897  1292  1301 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 17:43:50.907  1448  1481 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:50.907  1448  1481 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:50.907  1292  7437 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 17:43:50.907  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:50.907  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:50.907  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 17:43:50.907  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 17:43:50.917  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:50.917  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-16 17:43:50.917  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:43:50.917  7330  7348 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 17:43:50.917  7330  7330 I GKI_LINUX: GKI_exit_task 1 done
08-16 17:43:50.917  7330  7330 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-16 17:43:50.917  7330  7330 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 17:43:50.917  1180  1180 D BluetoothAdapter: 180112583: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:50.917  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:43:50.917  1180  1724 D BluetoothAdapter: 180112583: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:50.927  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:50.927  1180  1180 D BluetoothTile:  getBluetoothState : 10
,08-16 17:43:50.927  1180  1724 D BluetoothAdapter: 180112583: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:50.927  1180  1180 D BluetoothAdapter: 180112583: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:50.927  1180  1180 D BluetoothAdapter: 180112583: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:50.927  1018  1497 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:50.927  1018  1494 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:43:50.927  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:43:50.927  2015  2197 D BluetoothAdapter: 88134581: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:50.927  2015  2197 D BluetoothAdapter: 88134581: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:50.937  1844  1844 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-16 17:43:50.937  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:50.937  7330  7330 I art     : System.exit called, status: 0
08-16 17:43:50.937  7330  7330 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 17:43:50.937  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:50.937  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:50.937  1018  3639 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:50.937  1018  3639 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.937  1018  3639 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:50.937  1018  3639 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:50.937  1018  3639 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:50.947  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:50.947  1018  3640 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:43:50.947  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.947  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:50.947  1018  3640 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:50.947  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:43:50.947  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:50.957  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:50.957  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:50.957  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 17:43:51.067  1018  1031 I ActivityManager: Process com.android.bluetooth (pid 7330)(adj 0) has died(40,723)
,08-16 17:43:51.077  2015  2015 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:43:51.077  1018  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-16 17:43:51.077  1018  1497 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:43:51.077  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-16 17:43:51.077  1018  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:51.077  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:51.087  2015  2015 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:43:51.097  2015  7469 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 17:43:51.097  1018  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:51.107  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:51.107  1018  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:51.107  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:51.117  2015  7469 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-16 17:43:51.267   288   288 E SMD     : DCD OFF
,08-16 17:43:52.367  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop,
08-16 17:43:52.367  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:53.417  1018  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:43:53.417  1018  1508 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-16 17:43:53.417  1018  1508 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-16 17:43:53.417  1018  1508 D BatteryService: stay LED for fully charged
08-16 17:43:53.417  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:43:53.417  1018  1018 I MotionRecognitionService: Plugged
,08-16 17:43:53.417  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:43:53.427  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:43:53.427  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate,
,08-16 17:43:53.427  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 17:43:53.427  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-16 17:43:53.447  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-16 17:43:53.447  1180  1180 D SViewCoverView: level :100 plugged : 2
,08-16 17:43:53.447  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-16 17:43:53.457  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-16 17:43:53.457  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-16 17:43:54.267   288   288 E SMD     : DCD OFF
,08-16 17:43:55.277  1018  1050 I PowerManagerService: [PWL] Off : 75s ago
08-16 17:43:55.277  1018  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-16 17:43:55.277  1018  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-16 17:43:55.277  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=17543)
,08-16 17:43:55.367  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-16 17:43:55.367  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@214a974d added. We now have 6 listener(s)
08-16 17:43:55.367  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-16 17:43:55.377  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:55.377  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@396a1202 added. We now have 7 listener(s)
08-16 17:43:55.377  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-16 17:43:55.377  6720  6773 I System.out: IsBluetoothEnabled
08-16 17:43:55.377  6720  6773 D BluetoothAdapter: disable()
08-16 17:43:55.377  1018  1031 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-16 17:43:55.377  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 17:43:55.377  6720  6773 D BluetoothAdapter: enable()
08-16 17:43:55.387  1018  3639 W ActivityManager: Permission Denial: getCurrentUser() from pid=6720, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:43:55.387  1018  3639 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 17:43:55.387  1018  3639 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6720, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:43:55.387  1018  3639 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 17:43:55.387  1018  3639 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-16 17:43:55.387  1018  3639 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-16 17:43:55.387  1018  3639 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-16 17:43:55.387  1018  3639 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 17:43:55.387  1018  3639 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:43:55.387  1018  3639 D SettingsProvider: name = bluetooth_on
08-16 17:43:55.387  1018  3639 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:55.397  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-16 17:43:55.397  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:43:55.397  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-16 17:43:55.397  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-16 17:43:55.397  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:55.397  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:55.397  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:55.397  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:55.417  7475  7475 E Zygote  : MountEmulatedStorage()
08-16 17:43:55.417  7475  7475 E Zygote  : v2
08-16 17:43:55.417  7475  7475 I libpersona: KNOX_SDCARD checking this for 1002
,08-16 17:43:55.417  7475  7475 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:55.417  7475  7475 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:43:55.417  7475  7475 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 17:43:55.427  1018  1047 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7475 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-16 17:43:55.427  7475  7475 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:43:55.427  1018  1329 E Watchdog: !@Sync 4,
,08-16 17:43:55.447  7475  7475 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:55.447  7475  7475 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:55.457  7475  7475 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 17:43:55.457  7475  7475 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:43:55.487  7475  7475 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding GattService
,08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding HeadsetService
08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding A2dpService
,08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding HidService
08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding HealthService
08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding PanService
08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding SapService
08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding SapClientService
08-16 17:43:55.517  7475  7475 D BtSettings.ProfileConfig: Adding HidDevService
,08-16 17:43:55.517  7475  7475 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-16 17:43:55.527  1018  1308 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService,
08-16 17:43:55.527  1018  1308 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:55.527  1018  1308 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.527  1018  1308 D SettingsProvider: selectionArgs: false
08-16 17:43:55.527  1018  1308 D SettingsProvider: selectionArgs: 1002,
08-16 17:43:55.527  1018  1308 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:43:55.527  1018  1308 D SettingsProvider: ret = -1
,08-16 17:43:55.527  1018  1496 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-16 17:43:55.527  1018  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:55.527  1018  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.527  1018  1496 D SettingsProvider: selectionArgs: false
08-16 17:43:55.527  1018  1496 D SettingsProvider: selectionArgs: 1002
08-16 17:43:55.527  1018  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:55.527  1018  1496 D SettingsProvider: ret = -1
,08-16 17:43:55.527  1018  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-16 17:43:55.527  1018  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:55.527  1018  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.527  1018  1497 D SettingsProvider: selectionArgs: false
08-16 17:43:55.527  1018  1497 D SettingsProvider: selectionArgs: 1002
08-16 17:43:55.527  1018  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:55.527  1018  1497 D SettingsProvider: ret = -1
,08-16 17:43:55.527  1018  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-16 17:43:55.527  1018  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:55.527  1018  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.527  1018  1495 D SettingsProvider: selectionArgs: false
,08-16 17:43:55.527  1018  1495 D SettingsProvider: selectionArgs: 1002
08-16 17:43:55.527  1018  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:43:55.527  1018  1495 D SettingsProvider: ret = -1
,08-16 17:43:55.527  1018  1506 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-16 17:43:55.527  1018  1506 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:55.527  1018  1506 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.527  1018  1506 D SettingsProvider: selectionArgs: false
08-16 17:43:55.527  1018  1506 D SettingsProvider: selectionArgs: 1002
08-16 17:43:55.527  1018  1506 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:55.527  1018  1506 D SettingsProvider: ret = -1
,08-16 17:43:55.537  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-16 17:43:55.537  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:55.537  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.537  1018  1031 D SettingsProvider: selectionArgs: false
08-16 17:43:55.537  1018  1031 D SettingsProvider: selectionArgs: 1002
08-16 17:43:55.537  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:55.537  1018  1031 D SettingsProvider: ret = -1
,08-16 17:43:55.537  1018  1494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-16 17:43:55.537  1018  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:55.537  1018  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.537  1018  1494 D SettingsProvider: selectionArgs: false
08-16 17:43:55.537  1018  1494 D SettingsProvider: selectionArgs: 1002
08-16 17:43:55.537  1018  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:55.537  1018  1494 D SettingsProvider: ret = -1
,08-16 17:43:55.537  1018  3640 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-16 17:43:55.537  1018  3640 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:55.537  1018  3640 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.537  1018  3640 D SettingsProvider: selectionArgs: false
08-16 17:43:55.537  1018  3640 D SettingsProvider: selectionArgs: 1002
08-16 17:43:55.537  1018  3640 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:55.537  1018  3640 D SettingsProvider: ret = -1
,08-16 17:43:55.537  1018  1136 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:55.537  1018  1136 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:55.537  1018  1136 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.537  1018  1136 D SettingsProvider: selectionArgs: false
08-16 17:43:55.537  1018  1136 D SettingsProvider: selectionArgs: 1002
08-16 17:43:55.537  1018  1136 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:55.537  1018  1136 D SettingsProvider: ret = -1
,08-16 17:43:55.537  1018  3639 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:55.537  1018  3639 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:55.537  1018  3639 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.537  1018  3639 D SettingsProvider: selectionArgs: false
08-16 17:43:55.537  1018  3639 D SettingsProvider: selectionArgs: 1002
08-16 17:43:55.537  1018  3639 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:55.537  1018  3639 D SettingsProvider: ret = -1
,08-16 17:43:55.537  1018  1508 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-16 17:43:55.537  1018  1508 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:55.537  1018  1508 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.537  1018  1508 D SettingsProvider: selectionArgs: false
08-16 17:43:55.537  1018  1508 D SettingsProvider: selectionArgs: 1002
08-16 17:43:55.537  1018  1508 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:55.537  1018  1508 D SettingsProvider: ret = -1
,08-16 17:43:55.537  1018  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
08-16 17:43:55.537  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:55.537  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:43:55.537  1018  1030 D SettingsProvider: selectionArgs: false
08-16 17:43:55.537  1018  1030 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:55.537  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:55.537  1018  1030 D SettingsProvider: ret = -1
,08-16 17:43:55.557  7475  7475 D BluetoothAdapterState: make
,08-16 17:43:55.557  7475  7475 I bluedroid: init
,08-16 17:43:55.557  7475  7475 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 17:43:55.557  7475  7475 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 17:43:55.557  7475  7475 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 17:43:55.557  7475  7475 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 17:43:55.557  7475  7490 I BluetoothAdapterState: Entering OffState
,08-16 17:43:55.567  7475  7475 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-16 17:43:55.567  7475  7475 I bluedroid: get_profile_interface socket
08-16 17:43:55.567  7475  7475 I bluedroid: get_profile_interface map_client
,08-16 17:43:55.567  7475  7493 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-16 17:43:55.567  7475  7475 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-16 17:43:55.567  7475  7493 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-16 17:43:55.567  7475  7493 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:43:55.567  7475  7493 I bluedroid: getModelRssiValues
,08-16 17:43:55.567  7475  7493 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-16 17:43:55.567  7475  7493 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:43:55.567  7475  7475 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:55.577  1018  1018 D SettingsProvider: name = bluetooth_name
,08-16 17:43:55.577  1018  3639 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-16 17:43:55.577  1018  3639 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.577  1018  3639 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.577  1018  3639 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.577  1018  3639 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.577  7475  7483 I bluedroid: config_hci_snoop_log
,08-16 17:43:55.577  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 17:43:55.587  7475  7493 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-16 17:43:55.587  1018  1047 D BluetoothManagerService: Ble is always on enable gatt
,08-16 17:43:55.587  1018  1047 I BluetoothManagerService: enableGattForLeMode, doBind called
08-16 17:43:55.587  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-16 17:43:55.587  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:43:55.597  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:55.597  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:55.597  7475  7475 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-16 17:43:55.597  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 17:43:55.597  7475  7490 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-16 17:43:55.597  7475  7490 D BluetoothAdapterProperties: Setting state to 11
,08-16 17:43:55.597  7475  7490 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 17:43:55.597  7475  7490 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 17:43:55.597  7475  7490 D BluetoothAdapterService: updateAdapterState state is 11
,08-16 17:43:55.597  7475  7490 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:55.597  7475  7490 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-16 17:43:55.607  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:55.607  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-16 17:43:55.607  7475  7490 D BluetoothSecureManager: getInstant: null
08-16 17:43:55.607  7475  7490 D BluetoothSecureManager: calling getMethod for getService
08-16 17:43:55.607  7475  7490 D BluetoothSecureManager: calling getService
,08-16 17:43:55.607  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:43:55.607  7475  7490 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3ea3a94a
,08-16 17:43:55.607  1018  1494 D BluetoothSecureManagerService: isSecureModeEnabled
08-16 17:43:55.607  1018  1494 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-16 17:43:55.607  7475  7490 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:43:55.607  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 17:43:55.607  7475  7490 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-16 17:43:55.607  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:55.607  7475  7490 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-16 17:43:55.607  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:55.607  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:55.617  7475  7490 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-16 17:43:55.617  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:43:55.617  7475  7490 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-16 17:43:55.617  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 17:43:55.617  1180  1180 D BluetoothTile:  getBluetoothState : 11
,08-16 17:43:55.617  1844  1844 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:55.617  7475  7490 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-16 17:43:55.617  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 17:43:55.617  7475  7490 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-16 17:43:55.617  1018  1136 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:43:55.617  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:55.617  7475  7490 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-16 17:43:55.617  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 17:43:55.617  7475  7490 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-16 17:43:55.617  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:43:55.617  7475  7490 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:55.617  1018  1496 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-16 17:43:55.617  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:43:55.617  7475  7490 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:55.617  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:43:55.617  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-16 17:43:55.617  7475  7490 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 17:43:55.617  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 17:43:55.617  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:43:55.617  7475  7490 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-16 17:43:55.617  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:43:55.627  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:55.627  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.627  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 17:43:55.627  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:55.627  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:55.627  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:55.627  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:55.627  7475  7490 D BluetoothBondStateMachine: make
,08-16 17:43:55.627  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:55.637  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 17:43:55.637  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 17:43:55.637  7475  7490 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 17:43:55.637  7475  7495 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 17:43:55.637  1018  3639 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:55.637  1018  3639 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.637  1018  3639 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.637  1018  3639 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.637  1018  3639 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.637  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:43:55.637  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:43:55.637  7475  7490 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:55.637  7475  7475 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:43:55.637  7475  7475 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:43:55.637  7475  7475 D BtGatt.GattService: start()
08-16 17:43:55.637  7475  7475 D BtGatt.GattService: start()
08-16 17:43:55.637  7475  7475 I bluedroid: get_profile_interface gatt
,08-16 17:43:55.637  7475  7475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:55.637  7475  7475 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:43:55.647  1018  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:55.647  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:55.647  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.647  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.647  1018  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.647  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.657  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:43:55.657  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:43:55.657  7475  7490 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:55.657  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:55.657  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 17:43:55.657  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:55.657  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.657  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:55.657  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:55.657  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.667  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 17:43:55.667  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:55.667  7475  7490 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:43:55.667  7475  7475 D BtGatt.GattService: mStartError = false
08-16 17:43:55.667  7475  7475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:55.667  7475  7475 D HeadsetService: Received start request. Starting profile...
08-16 17:43:55.667  7475  7475 D HeadsetService: start()
,08-16 17:43:55.667  7475  7475 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 17:43:55.667  7475  7475 D HeadsetStateMachine: make
,08-16 17:43:55.667  7475  7475 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 17:43:55.677  1018  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:55.677  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.677  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:55.677  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.677  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.677  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-16 17:43:55.677  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 17:43:55.677  7475  7490 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:43:55.677  1018  1495 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-16 17:43:55.677  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.687  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.687  1018  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.687  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:43:55.687  1018  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:55.687  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.687  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.687  1018  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.687  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.687  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-16 17:43:55.687  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:43:55.687  7475  7490 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 17:43:55.687  1018  1497 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-16 17:43:55.697  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.697  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.697  1018  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.697  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:43:55.697  1018  3640 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:55.697  7475  7475 I bluedroid: get_profile_interface handsfree
,08-16 17:43:55.697  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.697  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.707  1018  3640 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.707  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.707  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:55.707  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:55.707  7475  7490 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:55.707  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:55.717  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.717  7475  7475 I DualScoManager: Instantiating Dual Sco Manager
,08-16 17:43:55.717  7475  7475 I DualScoManager: Set HeadsetServiceHelper
,08-16 17:43:55.717  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:55.717  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:55.717  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.717  7475  7475 D BluetoothAtMessage: createCMTIContentObservers
,08-16 17:43:55.717  1018  1496 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-16 17:43:55.717  1018  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:55.717  1018  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:55.717  1018  1496 D SettingsProvider: selectionArgs: false
08-16 17:43:55.717  1018  1496 D SettingsProvider: selectionArgs: 1002
08-16 17:43:55.717  1018  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:43:55.717  1018  1496 D SettingsProvider: ret = -1
08-16 17:43:55.717  7475  7498 D HeadsetStateMachine: Enter Disconnected: -2
,08-16 17:43:55.727  7475  7475 D HeadsetService: mStartError = false
08-16 17:43:55.727  7475  7475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:55.727  7475  7498 D HeadsetStateMachine: Clear mHeadsetBrsf
08-16 17:43:55.727  7475  7498 D HeadsetStateMachine: map size, before remove : 0
08-16 17:43:55.727  7475  7498 D HeadsetStateMachine: map size, after remove: 0
,08-16 17:43:55.727  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 17:43:55.727  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:43:55.727  7475  7490 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-16 17:43:55.727  7475  7475 D A2dpService: Received start request. Starting profile...
08-16 17:43:55.727  7475  7475 D A2dpService: start()
,08-16 17:43:55.727  7475  7475 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 17:43:55.727  7475  7475 I bluedroid: get_profile_interface avrcp
,08-16 17:43:55.727  1018  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:55.737  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.737  7475  7475 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 17:43:55.737  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.737  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.737  7475  7475 D Avrcp   : Initialize Media Controller
08-16 17:43:55.737  7475  7475 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-16 17:43:55.737  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.737  7475  7475 E Avrcp   : getActiveSessions
08-16 17:43:55.737  7475  7475 D Avrcp   : pick active media Controller
08-16 17:43:55.737  7475  7475 D Avrcp   : Get the active Media Controller 
,08-16 17:43:55.737  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:43:55.737  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:55.737  7475  7490 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:55.737  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:55.737  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:55.737  7475  7490 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:55.737  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:43:55.737  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:43:55.737  7475  7490 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:43:55.737  7475  7490 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:43:55.737  7475  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:43:55.737  7475  7490 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:43:55.737  7475  7490 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-16 17:43:55.757  7475  7475 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 17:43:55.757  7475  7503 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-16 17:43:55.757  7475  7475 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:43:55.757  7475  7475 D A2dpStateMachine: make
,08-16 17:43:55.757  7475  7475 I bluedroid: get_profile_interface a2dp
,08-16 17:43:55.757  7475  7505 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 17:43:55.757  7475  7475 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 17:43:55.767  7475  7475 D A2dpService: mStartError = false
08-16 17:43:55.767  7475  7475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:55.767  7475  7475 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-16 17:43:55.767  7475  7475 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:43:55.767  7475  7475 D HidService: Received start request. Starting profile...
08-16 17:43:55.767  7475  7475 D HidService: start()
08-16 17:43:55.767  7475  7475 I bluedroid: get_profile_interface hidhost
08-16 17:43:55.767  7475  7504 D A2dpStateMachine: Enter Disconnected: -2
08-16 17:43:55.767  7475  7475 D HidService: setHidService(): set to: null
08-16 17:43:55.767  7475  7475 D HidService: mStartError = false
08-16 17:43:55.767  7475  7475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:55.767  7475  7475 D HeadsetStateMachine: Try to query the phonestate on bind
08-16 17:43:55.767  1440  1485 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 17:43:55.767  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-16 17:43:55.767  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:43:55.767  1440  1485 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 17:43:55.767  7475  7475 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 17:43:55.767  7475  7475 D HealthService: Received start request. Starting profile...
08-16 17:43:55.767  7475  7475 D HealthService: start()
,08-16 17:43:55.777  7475  7475 I bluedroid: get_profile_interface health
,08-16 17:43:55.777  7475  7475 D HealthService: mStartError = false
08-16 17:43:55.777  7475  7475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:55.777  7475  7475 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-16 17:43:55.777  7475  7475 D HeadsetStateMachine: Proxy object connected
,08-16 17:43:55.777  7475  7475 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 17:43:55.777  7475  7498 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:43:55.777  7475  7475 D PanService: Received start request. Starting profile...
08-16 17:43:55.777  7475  7475 D PanService: start()
08-16 17:43:55.777  7475  7475 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:43:55.777  7475  7475 I bluedroid: get_profile_interface pan
,08-16 17:43:55.777  7475  7503 D BluetoothMediaBrowser: no now playing list
08-16 17:43:55.777  7475  7503 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 17:43:55.777  7475  7475 D PanService: mStartError = false
08-16 17:43:55.777  7475  7475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:55.777  7475  7475 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-16 17:43:55.777  7475  7475 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-16 17:43:55.777  7475  7498 D HeadsetStateMachine: Disconnected process message: 18
,08-16 17:43:55.787  7475  7475 D BluetoothMapService: Received start request. Starting profile...
08-16 17:43:55.787  7475  7475 D BluetoothMapService: start()
,08-16 17:43:55.787  2015  2015 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:43:55.787  2015  2015 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:43:55.787  7475  7475 D BluetoothMapService: mStartError = false
08-16 17:43:55.787  7475  7475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:55.787  7475  7475 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-16 17:43:55.787  7475  7475 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 17:43:55.787  7475  7498 D HeadsetStateMachine: Disconnected process message: 10
08-16 17:43:55.787  7475  7475 D BluetoothA2dp: Proxy object connected
08-16 17:43:55.787  7475  7475 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-16 17:43:55.787  7475  7498 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 17:43:55.787  7475  7475 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
08-16 17:43:55.787  7475  7498 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:43:55.797  7475  7475 D SapService: Received start request. Starting profile...
08-16 17:43:55.797  7475  7475 D SapService: start()
08-16 17:43:55.797  7475  7475 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 17:43:55.797  7475  7475 I bluedroid: get_profile_interface sap
,08-16 17:43:55.797  7475  7475 D SapService: mStartError = false
08-16 17:43:55.797  7475  7475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:55.797  7475  7475 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 17:43:55.797  7475  7475 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 17:43:55.797  7475  7475 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-16 17:43:55.797  7475  7475 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 17:43:55.817  7475  7475 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 17:43:55.817  7475  7475 E BluetoothAdapterService(288720212): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 17:43:55.817  7475  7490 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-16 17:43:55.817  7475  7490 I bluedroid: enable
,08-16 17:43:55.817  7475  7490 I bt_hci_bdroid: init
,08-16 17:43:55.817  7475  7510 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-16 17:43:55.817  7475  7490 I bt_vendor: bt-vendor : init
,08-16 17:43:55.817  7475  7490 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 17:43:55.817  7475  7490 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-16 17:43:55.817  7475  7490 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-16 17:43:55.817  7475  7490 D bt_userial_mct: userial_init
,08-16 17:43:55.827  7475  7490 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 17:43:55.827  7475  7490 I bt_vendor: Starting hciattach daemon
,08-16 17:43:55.827  7475  7490 I bt_vendor: try to set false
,08-16 17:43:55.827  7475  7490 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-16 17:43:55.827  7475  7490 I bt_vendor: Starting hciattach daemon
08-16 17:43:55.827  7475  7490 I bt_vendor: try to set true
,08-16 17:43:55.837  7514  7514 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-16 17:43:55.887  7520  7520 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-16 17:43:55.897  7521  7521 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 17:43:55.907  7523  7523 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 17:43:55.917  7524  7524 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-16 17:43:55.927  7525  7525 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 17:43:55.937  7526  7526 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-16 17:43:56.147  7529  7529 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-16 17:43:56.157  7530  7530 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 17:43:56.187  7475  7490 I bt_vendor: bluetooth satus is on,
,08-16 17:43:56.187  7475  7512 D bt_userial_mct: userial_open(port:0)
08-16 17:43:56.187  7475  7512 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 17:43:56.187  7475  7512 I bt_vendor: Done intiailizing UART
,08-16 17:43:56.187  7475  7512 I bt_vendor: Done intiailizing UART
,08-16 17:43:56.187  7475  7512 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,08-16 17:43:56.187  7475  7512 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-16 17:43:56.187  7475  7532 D bt_userial_mct: Entering userial_read_thread()
,08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_SAP
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 17:43:56.197  7475  7510 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-16 17:43:56.247   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:43:56.287  7475  7510 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-16 17:43:56.297  7475  7510 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa410fed1 
,08-16 17:43:56.297  7475  7510 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa410fed1 
,08-16 17:43:56.307  7475  7493 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-16 17:43:56.317  7475  7493 E bt-btif : Calling BTA_HhEnable
,08-16 17:43:56.317  7475  7493 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 17:43:56.317  7475  7493 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-16 17:43:56.317  7475  7493 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:43:56.317  7475  7493 I bluedroid: getModelRssiValues
,08-16 17:43:56.317  7475  7493 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-16 17:43:56.317  7475  7493 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:43:56.317  1018  1018 D SettingsProvider: name = bluetooth_name
,08-16 17:43:56.317  7475  7493 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-16 17:43:56.327  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:56.327  7475  7493 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 17:43:56.327  7475  7493 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:43:56.327  7475  7493 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:43:56.327  7475  7493 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-16 17:43:56.337  7475  7493 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-16 17:43:56.337  7475  7493 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-16 17:43:56.337  7475  7493 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 17:43:56.337  7475  7493 E bt-btif : btif_sock_init: !vhci_init
,08-16 17:43:56.337  7475  7493 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-16 17:43:56.337  7475  7493 D IOP_DB_BT: db_open: db_open : handle 3025866768l, read 13894 bytes onto local cache
,08-16 17:43:56.337  7475  7493 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-16 17:43:56.337  7475  7493 D IOP_DB_BT: db_query: result 1
,08-16 17:43:56.337  7475  7493 I         : iop_db_open: iop_db_open status 0
08-16 17:43:56.337  7475  7532 E bt_mct  : hci lib postload completed
,08-16 17:43:56.337  7475  7493 D bte_conf: Device ID record 1 : primary
08-16 17:43:56.337  7475  7493 D bte_conf:   vendorId            = 0075
08-16 17:43:56.337  7475  7493 D bte_conf:   vendorIdSource      = 0001
08-16 17:43:56.337  7475  7493 D bte_conf:   product             = 0100
08-16 17:43:56.337  7475  7493 D bte_conf:   version             = 0200
08-16 17:43:56.337  7475  7493 D bte_conf:   clientExecutableURL = 
08-16 17:43:56.337  7475  7493 D bte_conf:   serviceDescription  = 
08-16 17:43:56.337  7475  7493 D bte_conf:   documentationURL    = 
08-16 17:43:56.337  7475  7493 D bte_conf: bte_load_did_conf no section named DID2.
,08-16 17:43:56.337  7475  7490 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 17:43:56.337  7475  7490 D BluetoothAdapterProperties: ScanMode =  20
08-16 17:43:56.337  7475  7490 D BluetoothAdapterProperties: State =  11
,08-16 17:43:56.337  1018  1031 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:43:56.347  7475  7493 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 17:43:56.347  7475  7490 D BluetoothAdapterProperties: Setting state to 12
,08-16 17:43:56.347  7475  7490 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 17:43:56.347  7475  7493 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:43:56.347  7475  7493 D BluetoothAdapterProperties: Scan Mode:21
,08-16 17:43:56.347  1018  3639 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-16 17:43:56.347  1018  3639 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:56.347  1018  3639 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:56.347  1018  3639 D SettingsProvider: selectionArgs: false
08-16 17:43:56.347  1018  3639 D SettingsProvider: selectionArgs: 1002
08-16 17:43:56.347  1018  3639 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:56.347  1018  3639 D SettingsProvider: ret = -1
08-16 17:43:56.347  7475  7490 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:43:56.347  7475  7490 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 17:43:56.347  7475  7493 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:43:56.347  1018  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:56.357  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.357  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:56.357  1018  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:56.357  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.357  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:56.357  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:56.357  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:56.357  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:56.357  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:56.357  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:56.357  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:56.357  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:56.367  7475  7490 D BluetoothAdapterService: Autoconnection is available 
,08-16 17:43:56.367  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:56.367  7475  7490 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 17:43:56.367  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:43:56.367  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-16 17:43:56.367  7475  7490 D BluetoothAdapterService: starting service from this receiver
08-16 17:43:56.367  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 17:43:56.367  2015  2188 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:56.367  2015  2188 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:56.367  1018  1047 D BluetoothPan: Binding service...
08-16 17:43:56.367  1018  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:56.367  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.367  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:43:56.367  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.367  1018  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.367  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.377  7475  7490 I BluetoothAdapterState: Entering On State from state = 11
08-16 17:43:56.377  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:43:56.377  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.377  1180  1956 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:43:56.377  1180  1956 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:56.377  7475  7502 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:43:56.377  7475  7502 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:56.387  1292  1300 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:43:56.387  1292  1300 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-16 17:43:56.387  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:43:56.387  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.387  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:56.387  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:56.387  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.397  7475  7475 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-16 17:43:56.397  1292  1292 D BluetoothA2dp: Proxy object connected
,08-16 17:43:56.397  1292  1292 D A2dpProfile: Bluetooth service connected
,08-16 17:43:56.397  1292  7437 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:43:56.397  1292  7437 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:56.407  1440  7439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:56.407  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:56.407  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:56.407  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.407  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.407  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.407  1440  7439 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:56.407  6720  6734 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:56.407  6720  6734 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:56.407  7475  7483 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:43:56.407  1292  1301 D BluetoothPan: Binding service...
,08-16 17:43:56.417  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:43:56.417  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.417  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:56.417  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:56.417  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:56.417  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:56.417  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:56.417  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:56.417  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:56.417  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:56.417  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:56.417  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.417  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.417  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:43:56.417  7475  7475 I BluetoothPbapService: Handler(): got msg=1
08-16 17:43:56.417  7380  7391 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:56.417  7380  7391 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:56.417  1292  1292 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:43:56.417  1292  1292 D PanProfile: Bluetooth service connected
,08-16 17:43:56.417  1018  3640 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:43:56.427  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:56.427  1292  7437 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:43:56.427  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:56.427  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33327713 added. We now have 8 listener(s)
08-16 17:43:56.427  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:56.427  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-16 17:43:56.427  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.427  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.427  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.427  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.427  7475  7537 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 17:43:56.437  1292  1292 D BluetoothMap: Proxy object connected
,08-16 17:43:56.437  1292  1292 D MapProfile: Bluetooth service connected
,08-16 17:43:56.437  1440  1485 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:56.437  7475  7537 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:43:56.437  7475  7537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:43:56.437  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:56.437  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:43:56.437  1292  1292 D BluetoothMap: getConnectedDevices()
,08-16 17:43:56.437  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.437  1018  3640 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:43:56.437  1018  3640 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:43:56.437  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.437  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.437  1018  3640 D SecContentProvider2: mCursor = null
,08-16 17:43:56.437  1018  3640 D WifiService: setWifiEnabled: false pid=6720, uid=10171
,08-16 17:43:56.437  1440  1485 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:56.437  1018  3640 D SettingsProvider: name = wifi_on
,08-16 17:43:56.437  1468  1633 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:56.447  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:56.447  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:56.447  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.447  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.447  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.447  7475  7537 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-16 17:43:56.447  7475  7537 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:43:56.447  7475  7537 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-16 17:43:56.447  7475  7537 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1260194e
08-16 17:43:56.447  7475  7537 D BluetoothSocket: channel: 19
08-16 17:43:56.447  7475  7537 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 17:43:56.447  1468  1633 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:56.447  1292  1300 D Bluetoothsap: onBluetoothStateChange: up=true
08-16 17:43:56.447  1292  1300 D Bluetoothsap: Binding service...
,08-16 17:43:56.447  1292  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 17:43:56.447  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-16 17:43:56.447  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.447  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.447  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.447  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.447  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:56.457  1292  1292 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 17:43:56.457  1292  1292 D SapProfile: Bluetooth service connected
08-16 17:43:56.457  1292  1292 D Bluetoothsap: getConnectedDevices()
,08-16 17:43:56.457  1018  1480 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:43:56.457  1018  1480 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:43:56.457  1018  1480 D SecContentProvider2: mCursor = null
08-16 17:43:56.457  1292  1300 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 17:43:56.457  1018  1480 D WifiService: setWifiEnabled: true pid=6720, uid=10171
,08-16 17:43:56.457  1018  1480 W ActivityManager: Permission Denial: getCurrentUser() from pid=6720, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:43:56.457  1018  1480 W WifiService: Failed getting userId using ActivityManagerNative
08-16 17:43:56.457  1018  1480 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6720, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:43:56.457  1018  1480 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-16 17:43:56.457  1018  1480 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:43:56.457  1018  1480 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:43:56.457  1018  1480 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:43:56.457  1018  1480 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:43:56.457  1018  1480 D SettingsProvider: name = wifi_on
,08-16 17:43:56.457  1440  7439 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:43:56.457  1440  7439 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:56.467  1292  1301 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:56.467  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:56.467  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:56.467  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:56.467  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:56.467  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.467  1018  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 17:43:56.467  1292  1301 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:56.467  1292  1292 D HeadsetProfile: Bluetooth service connected
,08-16 17:43:56.477  1468  1484 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:56.477  1468  1484 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:56.477  1440  1461 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:56.477  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:43:56.477  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:56.477  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.477  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.477  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.477  1440  1461 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:56.477  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:43:56.477  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:56.477  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:43:56.477  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.477  1292  1300 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 17:43:56.477  1018  1018 D BluetoothA2dp: Proxy object connected
,08-16 17:43:56.477  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-16 17:43:56.487  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.487  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.487  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.487  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.487  1448  1489 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:43:56.487  1448  1489 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:56.487  1292  1301 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:43:56.487  1292  1292 D BluetoothPbap: Proxy object connected
08-16 17:43:56.487  1292  1292 D PbapServerProfile: Bluetooth service connected
,08-16 17:43:56.497  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.497  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-16 17:43:56.497  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.497  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 17:43:56.497  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.497  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:43:56.497  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:56.497  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 17:43:56.507  1292  1292 D BluetoothInputDevice: Proxy object connected,
08-16 17:43:56.507  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2,
,08-16 17:43:56.507  1292  1292 D HidProfile: Bluetooth service connected
,08-16 17:43:56.507  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-16 17:43:56.507  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-16 17:43:56.507  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0),
,08-16 17:43:56.517  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:43:56.517  1440  1440 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2d7c489b, true
,08-16 17:43:56.517  1440  1440 D BluetoothHeadset: registerMessageListener
,08-16 17:43:56.517  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:43:56.517  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:56.527  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:43:56.527  1180  1180 D BluetoothTile:  getBluetoothState : 12
,08-16 17:43:56.527  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:56.527  1844  1844 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:56.527  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:56.537  1018  1136 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:56.537  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-16 17:43:56.537  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:56.537  7475  7502 D HeadsetService: registerMessageListener
08-16 17:43:56.537  1018  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:56.537  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.537  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:56.537  7475  7502 D HeadsetService: registerMessageListener,
08-16 17:43:56.537  1180  1724 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:43:56.537  7475  7498 D HeadsetStateMachine: Disconnected process message: 70,
08-16 17:43:56.537  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-16 17:43:56.537  7475  7498 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3af4ba6f
08-16 17:43:56.537  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:43:56.547  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:56.547  1018  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:56.547  7475  7542 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 17:43:56.547  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-16 17:43:56.547  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-16 17:43:56.547  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 17:43:56.547  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:56.547  1292  1292 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-16 17:43:56.547  7475  7498 D HeadsetStateMachine: Disconnected process message: 9
,08-16 17:43:56.547  7475  7498 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 17:43:56.557  7475  7542 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:43:56.557  7475  7542 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:43:56.557  1292  1292 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-16 17:43:56.557  1292  1292 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-16 17:43:56.557  1292  1292 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-16 17:43:56.557  7475  7542 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-16 17:43:56.557  7475  7542 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:43:56.557  7475  7542 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:43:56.557  7475  7542 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bdb637c
,08-16 17:43:56.557  7475  7542 D BluetoothSocket: channel: 5
,08-16 17:43:56.567   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-16 17:43:56.567   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 17:43:56.567   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-16 17:43:56.567   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 17:43:56.567   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 17:43:56.567   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 17:43:56.567   283   283 V audio_hw_primary: adev_set_parameters: exit
,08-16 17:43:56.567  7475  7498 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 17:43:56.577  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:56.577  1018  1496 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:43:56.577  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.577  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.577  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.577  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:43:56.577  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:56.587  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive,
,08-16 17:43:56.587  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:56.587  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 17:43:56.597  7475  7475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
08-16 17:43:56.597  7475  7475 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 17:43:56.597  1018  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:56.597  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.597  1018  1496 W ActivityManager: userId = 0, bbcId = -10000,
,08-16 17:43:56.597  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.597  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.607  2015  2015 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:43:56.607  1018  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:56.607  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.617  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.617  1018  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:56.617  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:56.617  2015  2015 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:43:56.617  2015  7548 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 17:43:56.767  1018  1496 I art     : Explicit concurrent mark sweep GC freed 23660(1370KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.352ms total 138.151ms
08-16 17:43:56.767  1018  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:56.767  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.767  1018  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:56.767  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:56.777  1018  3639 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:43:56.777  1018  3640 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:56.787  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:56.787  1018  3640 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:56.787  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:56.787  2015  7548 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-16 17:43:56.797  7475  7558 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 17:43:56.797  7475  7558 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:43:56.797  7475  7558 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-16 17:43:56.797  7475  7558 D BluetoothSocket: bindListen(), new LocalSocket 
,08-16 17:43:56.797  7475  7558 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:43:56.797  7475  7558 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@be20426
,08-16 17:43:56.797  7475  7558 D BluetoothSocket: channel: 12
,08-16 17:43:56.797  7475  7558 I BtOppRfcommListener: Accept thread started.
,08-16 17:43:56.827  1018  1045 D Tethering: interfaceAdded wlan0
,08-16 17:43:56.827  1018  1131 E Tethering: No numeric data
,08-16 17:43:56.827  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:43:56.827  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:56.827  1018  1131 D Tethering: clearTetheredNotification()
08-16 17:43:56.837  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:43:56.827  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:56.837  1180  1180 D HotspotTile: updateTetherState():false, false
08-16 17:43:56.837  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:56.837  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:43:56.837  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:56.837  1018  1125 V NetworkStats: performPollLocked() took 4ms
08-16 17:43:56.837  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:56.837  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:56.837  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:56.837  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:56.837  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:56.837  1018  1131 D Tethering: InitialState.processMessage what=4
,08-16 17:43:56.837  1018  1131 E Tethering: No numeric data
,08-16 17:43:56.837  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 17:43:56.847  1018  1131 D Tethering: clearTetheredNotification()
,08-16 17:43:56.847  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:56.847  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:56.847  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:56.847  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:43:56.847  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-16 17:43:56.847  1180  1180 D HotspotTile: updateTetherState():false, false
,08-16 17:43:56.847  1018  1045 D Tethering: interfaceAdded p2p0
,08-16 17:43:56.847  1018  1125 V NetworkStats: performPollLocked() took 5ms
08-16 17:43:56.847  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:56.847  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-16 17:43:56.847  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:56.847  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:56.847  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:56.847  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:43:56.847  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:43:56.847   278  1017 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-16 17:43:56.857   278  1017 D SoftapController: Softap fwReload - Ok
,08-16 17:43:56.857   278  1017 D CommandListener: Setting iface cfg
08-16 17:43:56.857   278  1017 D CommandListener: Trying to bring down wlan0
,08-16 17:43:56.857   278  1017 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:43:56.857  1018  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-16 17:43:56.897  7560  7560 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-16 17:43:56.897  7560  7560 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 17:43:56.897  7560  7560 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 17:43:56.907  7560  7560 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-16 17:43:56.907   407   407 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7560
08-16 17:43:56.907   407   407 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 17:43:56.907  7560  7560 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 17:43:56.907  7560  7560 I wpa_supplicant: ssSupport state is = 1
08-16 17:43:56.907  7560  7560 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 17:43:56.907  7560  7560 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-16 17:43:56.907   407   407 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7560
08-16 17:43:56.907   407   407 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-16 17:43:56.957  1018  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-16 17:43:56.967  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:56.967  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:43:56.967  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:56.967  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:56.967  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:56.967  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:56.967  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:56.967  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-16 17:43:56.967  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:56.967  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:43:56.967  1180  1180 D HotspotTile: onReceive : 2, 0
,08-16 17:43:56.967  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:56.977  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:56.977  1018  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:56.977  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:56.977  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:56.977  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:56.977  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:56.987  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:43:56.987  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-16 17:43:56.987  6534  6534 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 17:43:56.987  6534  6534 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-16 17:43:56.987  2205  2205 I Hs20UtilService: Starting #19
,08-16 17:43:56.987  2205  2222 I Hs20UtilService: Message received 5011
,08-16 17:43:57.067   407   407 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-16 17:43:57.067  7560  7560 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-16 17:43:57.107  7560  7560 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-16 17:43:57.107  7560  7560 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 17:43:57.117  7560  7560 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 17:43:57.117   407   407 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7560
08-16 17:43:57.117   407   407 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 17:43:57.117  7560  7560 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-16 17:43:57.117  7560  7560 I wpa_supplicant: ssSupport state is = 1
08-16 17:43:57.117  7560  7560 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:57.117  7560  7560 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:43:57.117  7560  7560 E wpa_supplicant: SIM READ ERROR
08-16 17:43:57.117  7560  7560 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:43:57.117  7560  7560 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:43:57.117  7560  7560 E wpa_supplicant: SIM READ ERROR
08-16 17:43:57.117  7560  7560 I wpa_supplicant: Blacklist: Clear (all) 
08-16 17:43:57.117  7560  7560 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:43:57.117  7560  7560 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:43:57.117  7560  7560 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-16 17:43:57.117  7560  7560 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 17:43:57.117  7560  7560 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:57.117  7560  7560 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-16 17:43:57.127  7560  7560 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-16 17:43:57.127  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:43:57.127  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:57.127  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:57.187  7560  7560 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-16 17:43:57.247   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:57.267   288   288 E SMD     : DCD OFF,
,08-16 17:43:57.297  7560  7560 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-16 17:43:57.297  7560  7560 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-16 17:43:57.317  7560  7560 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 17:43:57.317   407   407 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7560
,08-16 17:43:57.317   407   407 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-16 17:43:57.317  7560  7560 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 17:43:57.317  7560  7560 I wpa_supplicant: ssSupport state is = 1,
08-16 17:43:57.317  7560  7560 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 17:43:57.317  7560  7560 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-16 17:43:57.337  7560  7560 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 17:43:57.337   407   407 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7560
08-16 17:43:57.337   407   407 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-16 17:43:57.337  7560  7560 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 17:43:57.337  7560  7560 I wpa_supplicant: ssSupport state is = 1,
08-16 17:43:57.337  7560  7560 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:57.337  7560  7560 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-16 17:43:57.337  7560  7560 E wpa_supplicant: SIM READ ERROR
08-16 17:43:57.337  7560  7560 I wpa_supplicant: wpa_default_ap_write_once
,08-16 17:43:57.337  7560  7560 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-16 17:43:57.337  7560  7560 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 17:43:57.337  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 17:43:57.337  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:57.337  1018  1045 D Tethering: interfaceStatusChanged p2p0, false,
,08-16 17:43:57.347  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:43:57.347  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:57.347  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:43:57.417  7560  7560 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-16 17:43:57.417  7560  7560 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 17:43:57.547  7560  7560 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-16 17:43:57.547  7560  7560 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-16 17:43:57.547  7560  7560 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 17:43:57.557  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-16 17:43:57.557  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 17:43:57.557  7560  7560 I wpa_supplicant: HOTSPOT20_ENABLE called
08-16 17:43:57.557  7560  7560 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:43:57.557  7560  7560 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:43:57.557  7560  7560 E wpa_supplicant: SIM READ ERROR
08-16 17:43:57.557  7560  7560 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:43:57.577  7560  7560 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-16 17:43:57.587  7560  7560 I wpa_supplicant: Skip scan - bUseNetwork false
08-16 17:43:57.587  1180  1724 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:43:57.587  1018  1128 D WifiConfigStore: Loading config and enabling all networks 
08-16 17:43:57.587  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:57.587  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:57.587  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:57.587  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:57.587  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:57.587  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:57.587  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:57.587  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:57.587  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-16 17:43:57.587  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:57.587  1180  1180 D HotspotTile: onReceive : 3, 0
,08-16 17:43:57.597  1018  1494 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:57.597  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:57.597  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:57.597  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:57.597  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:57.597  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:57.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:57.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:57.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:57.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:57.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:57.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:57.597  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:57.607  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:57.607  1018  1128 E WifiConfigStore: Not a HS20
,08-16 17:43:57.607  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:43:57.607  6534  6534 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:57.607  6534  6534 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:57.607  6534  6534 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-16 17:43:57.607  1018  1128 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 17:43:57.607  2205  2205 I Hs20UtilService: Starting #20
08-16 17:43:57.607  2205  2222 I Hs20UtilService: Message received 5011
08-16 17:43:57.617  1018  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
08-16 17:43:57.617  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-16 17:43:57.617  7560  7560 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-16 17:43:57.617  7560  7560 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-16 17:43:57.617  7560  7560 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 17:43:57.617  7560  7560 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 17:43:57.617  7560  7560 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 17:43:57.617  7560  7560 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 17:43:57.617  7560  7560 I wpa_supplicant: First Scan Start
08-16 17:43:57.617  7560  7560 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-16 17:43:57.617  1018  1128 D WifiNative-wlan0: Setting external_sim to 1
08-16 17:43:57.617  1018  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:43:57.617  1018  1128 I WifiNative-HAL: startHal
08-16 17:43:57.617  1018  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9d4fd88c
08-16 17:43:57.617  1018  1128 I WifiNative-HAL: Could not start hal
08-16 17:43:57.617  6917  6917 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:43:57.617  1018  1128 E WifiNative-wlan0: do suspend true
08-16 17:43:57.627  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-16 17:43:57.627  1018  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
08-16 17:43:57.627  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 17:43:57.627   278  1017 D CommandListener: Setting iface cfg
08-16 17:43:57.627   278  1017 D CommandListener: Trying to bring up p2p0
08-16 17:43:57.627  1018  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:57.627  1018  1151 I WifiNative-HAL: startHal
08-16 17:43:57.627  1018  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e4a79bc
08-16 17:43:57.627  1018  1151 I WifiNative-HAL: Could not start hal
08-16 17:43:57.627  1018  1151 E WifiScanningService: could not start HAL
08-16 17:43:57.627  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:43:57.627  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:43:57.627  1018  1128 E WifiNative-wlan0: invaild command id : 215
08-16 17:43:57.627  1018  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 17:43:57.627  1018  1127 D WifiP2pService: P2pEnablingState
08-16 17:43:57.627  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-16 17:43:57.627  1018  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 17:43:57.627  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:43:57.627  1018  1127 D WifiP2pService: P2p socket connection successful
08-16 17:43:57.627  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:43:57.627  1018  1128 E WifiNative-wlan0: invaild command id : 215
08-16 17:43:57.627  1018  1127 D WifiP2pService: P2pEnabledState
08-16 17:43:57.627  1018  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:57.627  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 17:43:57.627  7560  7560 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:43:57.627  1018  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:57.627  7560  7560 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:43:57.627  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 17:43:57.627  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 17:43:57.627  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:57.627  1018  1048 D WifiDisplayController: disconnect
08-16 17:43:57.627  1018  1048 D WifiDisplayController: updateConnection
08-16 17:43:57.627  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:57.637  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:43:57.637  7560  7560 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-16 17:43:57.637  1018  1128 E WifiStateMachine: Failed to set frequency band 0
08-16 17:43:57.637  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:57.637  1018  1128 D SecContentProvider2: mCursor = null
08-16 17:43:57.637  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress
08-16 17:43:57.637  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:43:57.637  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:43:57.637  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:43:57.637  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:43:57.637  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-16 17:43:57.637  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-16 17:43:57.637  1018  1136 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:43:57.637  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-16 17:43:57.647  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 17:43:57.647  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  secondary type: null
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  wps: 0
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  grpcapab: 0
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  devcapab: 0
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  status: 3
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  wfdInfo: null
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-16 17:43:57.647  1018  1048 D WifiDisplayController:  SConnectInfo : null
08-16 17:43:57.647  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:57.647  1018  1128 D SecContentProvider2: mCursor = null
08-16 17:43:57.647  1018  1127 D WifiP2pService: DeviceAddress: 0a:76:28
08-16 17:43:57.647  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:43:57.647  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:43:57.647  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:43:57.647  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:57.647  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:57.647  1292  2321 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 17:43:57.657  7266  7266 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-16 17:43:57.657  7266  7266 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-16 17:43:57.657  7266  7266 D FileShare-Client: Outbound.stopDelayTimer - 
08-16 17:43:57.657  7281  7281 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-16 17:43:57.667  1018  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-16 17:43:57.667  1018  1127 D WifiP2pService: InactiveState
,08-16 17:43:57.667  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-16 17:43:57.667  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:43:57.667  7560  7560 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 17:43:57.667  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
08-16 17:43:57.667  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:43:57.837  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 17:43:57.837  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:57.837  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:43:58.247   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:58.477  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:58.477  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:58.477  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:58.477  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:58.477  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:58.477  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:58.477  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:58.477  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:58.487  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:58.487  6720  6773 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 17:43:58.487  6720  6773 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 17:43:58.497  6720  6773 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2b9017a2 Bundle[{}]
,08-16 17:43:58.497  6720  6773 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 17:43:58.497  6720  6773 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 17:43:58.497  6720  6773 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 17:43:58.497  6720  6773 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 17:43:58.497  6720  6773 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 17:43:58.497  6720  6773 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:43:58.507  6720  6773 I System.out: Running OutgoingSocketThread
,08-16 17:43:58.507  6720  7568 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1334)
,08-16 17:43:58.507  6720  7568 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43043
,08-16 17:43:58.507  6720  7568 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 17:43:58.827  7560  7560 I wpa_supplicant: nl80211: Received scan results (27 BSSes),
08-16 17:43:58.827  7560  7560 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-16 17:43:58.827  7560  7560 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-16 17:43:58.827  7560  7560 I wpa_supplicant: Trying to associate with  'G700'
08-16 17:43:58.827  7560  7560 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-16 17:43:58.827  7560  7560 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-16 17:43:58.827  1018  7565 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-16 17:43:58.847  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:58.847  1018  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:58.937  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:58.937  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:58.937  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:58.937  7560  7560 E wpa_supplicant: Cmd 35605 not handled
,08-16 17:43:58.937  7560  7560 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-16 17:43:58.937  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:58.937  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:58.937  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:58.937  7560  7560 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-16 17:43:58.947  7560  7560 I wpa_supplicant: Associated with F4.99.3E
08-16 17:43:58.947  7560  7560 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:43:58.947  7560  7560 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
08-16 17:43:58.947  7560  7560 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-16 17:43:58.947  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:58.947  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:58.947  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:58.947  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 17:43:58.947  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 17:43:58.947  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-16 17:43:58.947  1018  1131 E Tethering: No numeric data
,08-16 17:43:58.947  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:43:58.957  1018  1131 D Tethering: clearTetheredNotification()
,08-16 17:43:58.957  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:58.957  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:43:58.957  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:58.957  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:43:58.957  7560  7560 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:43:58.957  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:43:58.957  7560  7560 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-16 17:43:58.957  1180  1180 D HotspotTile: updateTetherState():false, false
08-16 17:43:58.957  7560  7560 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-16 17:43:58.957  7560  7560 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-16 17:43:58.957  7560  7560 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:43:58.957  7560  7560 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-16 17:43:58.957  7560  7560 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-16 17:43:58.957  7560  7560 I wpa_supplicant: Blacklist: Clear (temp) 
08-16 17:43:58.957  7560  7560 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-16 17:43:58.967  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 17:43:58.967  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 17:43:58.967  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-16 17:43:58.967  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:58.967  1018  1125 V NetworkStats: performPollLocked() took 11ms
,08-16 17:43:58.967  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:58.967  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:58.967  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:58.967  1018  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:58.977  1018  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-16 17:43:58.977  1018  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 17:43:58.987  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:58.987  1018  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-16 17:43:58.987  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:58.987  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:58.987  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:58.987  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:58.987  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:58.987  1018  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-16 17:43:58.987  1018  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:58.987  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 17:43:58.987  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:58.997  1018  1308 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:43:58.997  1018  1308 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:58.997  1018  1308 W ActivityManager: userId = 0, bbcId = -10000,
,08-16 17:43:58.997  1018  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:58.997  1018  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-16 17:43:58.997  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:59.007  2205  2205 I Hs20UtilService: Starting #21
08-16 17:43:59.007  2205  2222 I Hs20UtilService: Message received 5007
,08-16 17:43:59.007  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:43:59.007  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:59.007  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:43:59.017  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:43:59.017  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:59.017  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:59.017  1292  2321 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:43:59.027   278  1017 D CommandListener: Setting iface cfg
,08-16 17:43:59.027  1018  1128 E WifiStateMachine: Start Dhcp Watchdog 3
,08-16 17:43:59.027  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:43:59.027  1018  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:59.037  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:59.037  1018  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:59.047  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:59.047  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:43:59.047  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.047  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.047  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.047  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.057  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-16 17:43:59.057  1018  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:59.057  1018  1128 E WifiNative-wlan0: do suspend false
,08-16 17:43:59.057  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-16 17:43:59.057  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:43:59.097  1018  3367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:43:59.247   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:59.277  7573  7573 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-16 17:43:59.287  7573  7573 I dhcpcd  : version 5.5.6 starting,
08-16 17:43:59.287  7573  7573 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-16 17:43:59.337  7573  7573 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-16 17:43:59.337  7573  7573 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
08-16 17:43:59.337  7573  7573 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-16 17:43:59.337  7573  7573 I dhcpcd  : bssid match
08-16 17:43:59.337  7573  7573 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-16 17:43:59.417  7573  7573 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-16 17:43:59.477  7573  7573 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-16 17:43:59.507  6720  6773 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1335)
08-16 17:43:59.507  6720  6773 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1335)
,08-16 17:43:59.517  6720  6773 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1340),
,08-16 17:43:59.517  6720  6773 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 17:43:59.517  6720  6773 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1341)
,08-16 17:43:59.517  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-16 17:43:59.517  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1876ad50 added. We now have 2 listener(s)
,08-16 17:43:59.527  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-16 17:43:59.527  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:43:59.527  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:43:59.527  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:59.527  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f365b49 added. We now have 9 listener(s)
08-16 17:43:59.527  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:59.527  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:43:59.537  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:59.537  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:59.537  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:59.537  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:59.537  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-16 17:43:59.537  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:59.537  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:59.537  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:59.537  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:59.537  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:43:59.537  6720  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:43:59.537  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:43:59.547  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a43716f added. We now have 3 listener(s)
,08-16 17:43:59.547  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:59.547  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 17:43:59.547  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-16 17:43:59.547  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:43:59.547  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:43:59.547  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-16 17:43:59.547  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6214e7c added. We now have 10 listener(s)
08-16 17:43:59.547  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:59.547  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:59.547  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-16 17:43:59.547  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:59.547  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:59.547  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.547  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:59.547  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:43:59.547  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1876ad50 removed from the list
08-16 17:43:59.547  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:59.547  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f365b49 removed from the list
08-16 17:43:59.547  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:59.547  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:59.547  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.547  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:59.557  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:59.557  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:59.557  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:59.557  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f365b49 not in the list
08-16 17:43:59.557  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.557  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:59.557  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:59.557  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:59.557  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:43:59.557  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6214e7c removed from the list
08-16 17:43:59.557  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:59.557  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:43:59.557  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:59.557  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:43:59.557  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a43716f removed from the list
,08-16 17:43:59.557  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:43:59.557  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32006305 added. We now have 2 listener(s)
08-16 17:43:59.557  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-16 17:43:59.557  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:43:59.557  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:43:59.567  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:59.567  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333df5a added. We now have 9 listener(s)
08-16 17:43:59.567  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:59.567  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:43:59.567  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-16 17:43:59.577  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:59.577  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:59.577  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-16 17:43:59.577  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:59.577  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-16 17:43:59.577  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:59.577  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:59.577  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:59.577  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:59.577  6720  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:59.587  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:43:59.587  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2372d668 added. We now have 3 listener(s)
,08-16 17:43:59.587  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 17:43:59.587  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:59.587  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-16 17:43:59.587  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:43:59.587  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:43:59.587  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:43:59.587  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11a92a81 added. We now have 10 listener(s)
08-16 17:43:59.587  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:59.587  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:43:59.587  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:43:59.587  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:43:59.587  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:59.587  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:43:59.597  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:43:59.607  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:43:59.607  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-16 17:43:59.617  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:43:59.617  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:43:59.617  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:43:59.617  7475  7483 D BtGatt.GattService: registerClient() - UUID=0a788e2b-54f9-4660-80b8-987a6659b1b1
,08-16 17:43:59.657  7475  7493 D BtGatt.GattService: onClientRegistered() - UUID=0a788e2b-54f9-4660-80b8-987a6659b1b1, clientIf=6,
,08-16 17:43:59.657  6720  6732 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-16 17:43:59.657  7475  7535 D BtGatt.GattService: start scan with filters
08-16 17:43:59.657  7475  7497 D BtGatt.ScanManager: handling starting scan
,08-16 17:43:59.667  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:43:59.667  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:43:59.667  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:43:59.667  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:43:59.667  7475  7497 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11358554
,08-16 17:43:59.667  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:59.667  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:43:59.667  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:43:59.667  7475  7493 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,08-16 17:43:59.667  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:59.677  7475  7497 D BtGatt.ScanManager: allow scan with filters
08-16 17:43:59.677  7475  7497 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:43:59.677  7475  7497 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-16 17:43:59.677  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-16 17:43:59.677  7475  7493 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:43:59.677  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-16 17:43:59.677  7475  7497 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:43:59.677  7475  7497 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-16 17:43:59.687  7475  7493 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:43:59.687  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:59.687  6720  6773 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:43:59.687  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:59.687  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:43:59.687  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.687  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:43:59.687  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:59.687  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:59.687  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:43:59.687  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:43:59.687  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 17:43:59.687  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:43:59.687  7475  7493 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:43:59.687  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:59.687  7475  7541 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:43:59.697  7475  7483 D BtGatt.GattService: unregisterClient() - clientIf=6,
,08-16 17:43:59.697  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:43:59.697  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:43:59.697  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:43:59.697  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:43:59.697  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:43:59.697  7475  7497 D BtGatt.ScanManager: filter size is 1
08-16 17:43:59.697  7475  7497 D BtGatt.ScanManager: delete FilterIndex - 3
,08-16 17:43:59.707  7475  7493 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-16 17:43:59.707  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:59.707  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:59.707  7475  7497 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:43:59.707  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:43:59.707  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:43:59.707  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:43:59.707  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:59.707  7475  7493 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:43:59.707  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:59.707  7475  7497 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:43:59.707  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-16 17:43:59.707  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:59.707  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:59.707  7475  7493 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:43:59.707  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:59.717  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:59.717  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:59.717  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:59.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:59.717  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.717  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:59.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:43:59.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32006305 removed from the list
08-16 17:43:59.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:59.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333df5a removed from the list
08-16 17:43:59.717  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:59.717  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:59.717  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.717  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:59.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:59.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:59.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:59.717  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@333df5a not in the list
08-16 17:43:59.717  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.717  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:59.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:59.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:43:59.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:59.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11a92a81 removed from the list
08-16 17:43:59.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:59.717  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.717  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:59.717  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:43:59.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2372d668 removed from the list
08-16 17:43:59.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:43:59.717  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bbcedbd added. We now have 2 listener(s)
,08-16 17:43:59.717  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-16 17:43:59.727  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:43:59.727  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:43:59.727  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:43:59.727  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d0effb2 added. We now have 9 listener(s)
08-16 17:43:59.727  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:59.727  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:43:59.727  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:59.737  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:59.737  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-16 17:43:59.737  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:59.737  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:59.737  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:59.737  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:59.737  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-16 17:43:59.737  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:59.737  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:43:59.737  6720  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:59.737  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:43:59.737  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17780a80 added. We now have 3 listener(s)
,08-16 17:43:59.737  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:59.737  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:59.737  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-16 17:43:59.737  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:43:59.737  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:43:59.737  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:59.737  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@304fa8b9 added. We now have 10 listener(s)
08-16 17:43:59.737  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:59.737  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:43:59.737  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:43:59.737  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:43:59.737  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:43:59.737  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:59.737  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:43:59.747  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:43:59.747  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:43:59.747  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:43:59.757  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:43:59.757  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:43:59.757  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:43:59.757  7475  7535 D BtGatt.GattService: registerClient() - UUID=782cdf2f-667b-41fb-a444-3cf2adc33a1b
,08-16 17:43:59.797  7475  7493 D BtGatt.GattService: onClientRegistered() - UUID=782cdf2f-667b-41fb-a444-3cf2adc33a1b, clientIf=6
,08-16 17:43:59.797  6720  6734 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:43:59.797  7475  7502 D BtGatt.GattService: start scan with filters
,08-16 17:43:59.797  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:43:59.797  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:43:59.797  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:43:59.797  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:43:59.807  7475  7497 D BtGatt.ScanManager: handling starting scan
,08-16 17:43:59.807  7475  7493 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 17:43:59.807  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:59.807  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:59.807  7475  7497 D BtGatt.ScanManager: allow scan with filters
,08-16 17:43:59.807  7475  7497 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:43:59.807  7475  7497 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-16 17:43:59.807  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:43:59.807  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:59.807  7475  7493 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:43:59.807  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:59.807  7475  7497 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:43:59.807  7475  7497 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:43:59.817  7475  7493 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:43:59.817  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:59.817  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:43:59.817  7475  7493 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:43:59.817  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:59.827  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:43:59.827  6720  6773 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 17:43:59.827  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:59.827  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:43:59.827  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:43:59.827  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:59.827  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:43:59.827  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:43:59.827  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:43:59.827  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bbcedbd removed from the list
08-16 17:43:59.827  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:43:59.827  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d0effb2 removed from the list
08-16 17:43:59.827  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:59.827  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:59.827  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:43:59.827  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 17:43:59.827  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:43:59.827  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:59.837  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:43:59.837  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:59.837  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:43:59.837  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d0effb2 not in the list
08-16 17:43:59.837  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:43:59.837  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:43:59.837  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:43:59.837  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 17:43:59.837  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:43:59.837  7475  7483 D BtGatt.GattService: stopScan() - queue size =1,
,08-16 17:43:59.837  7475  7535 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:43:59.837  7475  7497 D BtGatt.ScanManager: filter size is 1
,08-16 17:43:59.837  7475  7497 D BtGatt.ScanManager: delete FilterIndex - 4
,08-16 17:43:59.837  7475  7493 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:43:59.847  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:59.847  7475  7497 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:43:59.847  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:43:59.847  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:43:59.847  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:43:59.847  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:43:59.847  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:43:59.847  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:59.847  7475  7493 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-16 17:43:59.847  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:59.847  7475  7497 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:43:59.847  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:43:59.847  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:43:59.847  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:43:59.847  7475  7493 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:43:59.847  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:59.847  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:59.847  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:43:59.847  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:43:59.847  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:59.847  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:59.847  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:59.847  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:59.847  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@304fa8b9 removed from the list
,08-16 17:43:59.847  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:59.847  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.847  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:59.847  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:43:59.847  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17780a80 removed from the list
08-16 17:43:59.857  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:43:59.857  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b91775 added. We now have 2 listener(s)
,08-16 17:43:59.857  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-16 17:43:59.857  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:43:59.857  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:43:59.857  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:43:59.857  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2772d30a added. We now have 9 listener(s)
08-16 17:43:59.857  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:59.857  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:43:59.857  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:59.867  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:59.867  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:59.867  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:59.867  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:59.867  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:59.867  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:59.867  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:59.867  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:59.867  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:59.867  6720  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:59.867  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:59.867  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:59.867  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:43:59.867  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@353ca998 added. We now have 3 listener(s)
,08-16 17:43:59.867  1018  1128 E WifiNative-wlan0: do suspend true
,08-16 17:43:59.877  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-16 17:43:59.877  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:43:59.877  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:43:59.877  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:43:59.877  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a10b5f1 added. We now have 10 listener(s)
08-16 17:43:59.877  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:59.877  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:43:59.877  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:43:59.877  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:43:59.877  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:59.877  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:43:59.877  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-16 17:43:59.887  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:43:59.887  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-16 17:43:59.887  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-16 17:43:59.887  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:43:59.887  6720  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:43:59.887  7475  7502 D BtGatt.GattService: registerClient() - UUID=06042299-97db-40d4-869c-acb0d3e0c736
,08-16 17:43:59.897  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-16 17:43:59.897  1018  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-16 17:43:59.897  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:59.897  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:43:59.897  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.897  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.897  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
08-16 17:43:59.897  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:59.897  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.897  1018  1128 E WifiStateMachine: VerifyingLinkState enter
,08-16 17:43:59.907  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:43:59.907  1018  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-16 17:43:59.907  1018  1130 D ConnectivityService: Adding iface wlan0 to network 504
,08-16 17:43:59.917  1018  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-16 17:43:59.917  1018  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:43:59.917  1018  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:43:59.917  1018  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:43:59.917  1018  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-16 17:43:59.927  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:59.927  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:59.927  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:59.927  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:59.927  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.927  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.927  1018  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-16 17:43:59.927  7475  7493 D BtGatt.GattService: onClientRegistered() - UUID=06042299-97db-40d4-869c-acb0d3e0c736, clientIf=6
08-16 17:43:59.927  6720  6732 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:43:59.937  7475  7541 D BtGatt.GattService: start scan with filters,
08-16 17:43:59.937  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:43:59.937  1018  1497 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:59.937  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,08-16 17:43:59.937  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:43:59.937  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:43:59.937  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:43:59.937  7475  7497 D BtGatt.ScanManager: handling starting scan
08-16 17:43:59.937  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:59.937  1018  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:59.937  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:43:59.937  1018  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-16 17:43:59.937  2205  2205 I Hs20UtilService: Starting #22
,08-16 17:43:59.937  1018  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-16 17:43:59.937  2205  2222 I Hs20UtilService: Message received 5007,
08-16 17:43:59.937  7475  7493 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:43:59.937  1018  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-16 17:43:59.937  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:59.937  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:43:59.937  1018  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 17:43:59.937  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:43:59.937  1018  1130 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-16 17:43:59.937  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:43:59.937  1018  1130 D ConnectivityService: LTETest block dns file not exists
08-16 17:43:59.937  7475  7497 D BtGatt.ScanManager: allow scan with filters
08-16 17:43:59.937  7475  7497 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:43:59.937  7475  7497 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-16 17:43:59.947  1018  1130 V NetworkStats: updateIfacesLocked()
08-16 17:43:59.937  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:43:59.947  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:59.947  7475  7493 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:43:59.947  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:59.947  7475  7497 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 17:43:59.947  7475  7497 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-16 17:43:59.947  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:59.947  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-16 17:43:59.947  1292  1292 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 17:43:59.947  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:43:59.957  7475  7493 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:43:59.957  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:59.957  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 17:43:59.957  1018  1130 V NetworkStats: performPollLocked() took 11ms
08-16 17:43:59.957  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:59.957  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 17:43:59.957  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:59.957  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:59.957  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:59.957  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:59.957  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:59.957  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.957  7475  7493 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:43:59.957  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:59.967  1018  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 17:43:59.967  1018  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 17:43:59.967  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 17:43:59.967  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
08-16 17:43:59.967  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
,08-16 17:43:59.967  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:59.967  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-16 17:43:59.967  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.977  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.977  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:59.977  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:59.977  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:59.977  1018  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:59.977  1018  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-16 17:43:59.977  1018  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:59.977  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:43:59.977  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:59.977  1018  1130 V NetworkStats: updateIfacesLocked()
08-16 17:43:59.977  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:43:59.977  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:59.977  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:59.977  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:43:59.977  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:43:59.977  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:43:59.977  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:59.977  1018  1130 V NetworkStats: performPollLocked() took 2ms
,08-16 17:43:59.977  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:59.977  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:59.977  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:59.987  2205  2205 I Hs20UtilService: Starting #23
,08-16 17:43:59.987  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:59.987  1018  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-16 17:43:59.987  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:59.987  1018  7570 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:59.987  1018  7570 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-16 17:43:59.987  1018  7570 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:59.987  1018  7570 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-16 17:43:59.987  1018  7570 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:43:59.987   278  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 17:43:59.987  1018  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-16 17:43:59.987   278  1013 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-16 17:43:59.987  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:59.987  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:59.987  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:59.987  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:59.987  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.987  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:43:59.987  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:43:59.987  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b91775 removed from the list
08-16 17:43:59.987  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:59.987  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2772d30a removed from the list
08-16 17:43:59.987  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:59.987  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:59.987  2205  2222 I Hs20UtilService: Message received 5007
08-16 17:43:59.987  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:43:59.987  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:43:59.987  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.987  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
08-16 17:43:59.987  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:59.987  1018  1096 V AlarmManager: waitForAlarm result :8
08-16 17:43:59.987  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:59.987  1018  1130 D ConnectivityService:    accepting network in place of null
08-16 17:43:59.987  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:43:59.987  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:43:59.987  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:59.987  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:59.987  1018  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 17:43:59.987  1018  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-16 17:43:59.987  1292  2321 V NearbySettings: MountReceiver.mPrefHandler - 7002,
08-16 17:43:59.997  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:59.997  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:59.997  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:59.997  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2772d30a not in the list
08-16 17:43:59.997  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:59.997  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:43:59.997  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:43:59.997  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:43:59.997  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:43:59.997  1018  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 17:43:59.997  1018  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-16 17:43:59.997  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 17:43:59.997  1468  1468 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-16 17:43:59.997  1468  1468 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 17:43:59.997  1018  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-16 17:43:59.997  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-16 17:43:59.997  1018  1131 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:43:59.997  1018  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-16 17:43:59.997  7475  7535 D BtGatt.GattService: stopScan() - queue size =1
08-16 17:43:59.997  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 17:43:59.997  1018  1125 V NetworkStats: updateIfacesLocked()
08-16 17:43:59.997  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:59.997  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:43:59.997  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:59.997  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:43:59.997  7475  7497 D BtGatt.ScanManager: filter size is 1
08-16 17:43:59.997  1180  1717 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:43:59.997  7475  7497 D BtGatt.ScanManager: delete FilterIndex - 5
08-16 17:43:59.997  4781  6790 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:43:59.997  7475  7541 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:43:59.997  7475  7493 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 17:43:59.997  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:44:00.007  7475  7497 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:44:00.007  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:44:00.007  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:44:00.007  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:44:00.007  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:44:00.007  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:44:00.007  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:00.007  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:00.007  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:00.007  1018  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-16 17:44:00.007  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:00.007  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
08-16 17:44:00.007  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:44:00.007  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 17:44:00.007  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 17:44:00.007  1180  1180 D StatusBar.NetworkController: updateDataNetType()
08-16 17:44:00.007  1180  1180 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 17:44:00.007  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 17:44:00.007  1018  1125 V NetworkStats: performPollLocked() took 8ms
08-16 17:44:00.007  7475  7493 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:44:00.007  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:00.007  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:44:00.007  7475  7497 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:44:00.007  7475  7493 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:44:00.007  7475  7493 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:00.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:44:00.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:44:00.017  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:44:00.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:00.017  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 17:44:00.017  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-16 17:44:00.017  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-16 17:44:00.017  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:44:00.017  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 17:44:00.017  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:00.017  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:00.017  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:00.017  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:00.017  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:00.017  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:00.017  1018  3640 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-16 17:44:00.017  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:00.017  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:44:00.017  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:00.017  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:44:00.017  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a10b5f1 removed from the list
08-16 17:44:00.017  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:00.017  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:00.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:00.017  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:44:00.017  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@353ca998 removed from the list
08-16 17:44:00.017  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:00.017  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d69c02d added. We now have 2 listener(s)
,08-16 17:44:00.017  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:00.017  6720  6720 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:00.017  6720  6720 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:44:00.017  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:00.017  1018  3640 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:44:00.017  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:44:00.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-16 17:44:00.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:00.017  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:00.017  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:00.027  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e62b962 added. We now have 9 listener(s)
,08-16 17:44:00.027  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:00.027  2205  2205 I Hs20UtilService: Starting #24
08-16 17:44:00.027  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:44:00.027  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:44:00.027  2205  2222 I Hs20UtilService: Message received 5007
,08-16 17:44:00.027  1292  1292 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 17:44:00.027  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:44:00.027  6720  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:44:00.027  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:00.027  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:00.027  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:00.027  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:00.027  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:44:00.027  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:44:00.027  6720  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:44:00.037  1018  2064 V SAMP_SPCM_test: CSC File load.. 
08-16 17:44:00.037  1018  1136 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application,
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings,
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
,08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-16 17:44:00.037  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
08-16 17:44:00.047  1018  3640 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-16 17:44:00.047  1018  3640 D SecContentProvider2: mCursor = null
08-16 17:44:00.047  6720  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:44:00.047  6720  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:44:00.047  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:00.047  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11e313b0 added. We now have 3 listener(s)
08-16 17:44:00.047  1018  1136 D SecContentProvider2: uri = 15 selection = getToastGravity
08-16 17:44:00.047  1018  1136 D SecContentProvider2: mCursor = null
08-16 17:44:00.047  1018  1497 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-16 17:44:00.047  1018  1497 D SecContentProvider2: mCursor = null
,08-16 17:44:00.047  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 17:44:00.047  1018  1494 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-16 17:44:00.047  1018  1494 D SecContentProvider2: mCursor = null
08-16 17:44:00.047  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:00.057  1018  3639 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-16 17:44:00.057  1018  3639 D SecContentProvider2: mCursor = null
,08-16 17:44:00.057  1018  1136 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-16 17:44:00.057  1018  1136 D SecContentProvider2: mCursor = null
,08-16 17:44:00.077  1018  7570 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application,
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
,08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-16 17:44:00.077  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
,08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
,08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
,08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-16 17:44:00.087  1018  2064 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-16 17:44:00.107  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-16 17:44:00.107  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:00.107  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:00.107  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:00.107  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37cf3229 added. We now have 10 listener(s)
08-16 17:44:00.107  6720  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:00.107  6720  6773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:44:00.107  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:44:00.107  6720  6773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:44:00.107  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:00.107  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:00.107  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:44:00.107  1018  2064 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-16 17:44:00.107  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:00.107  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d69c02d removed from the list
08-16 17:44:00.107  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:00.107  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e62b962 removed from the list
08-16 17:44:00.107  6720  6773 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:44:00.107  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:00.107  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:00.107  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:00.107  1018  2064 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:00.107  1018  2064 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:00.117  1018  2064 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:00.117  1018  2064 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:00.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:00.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:00.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:00.117  6720  6773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e62b962 not in the list
08-16 17:44:00.117  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:00.117  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:00.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:00.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:00.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:00.117  6720  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37cf3229 removed from the list
08-16 17:44:00.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:00.117  6720  6773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:00.117  6720  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:00.117  6720  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:00.117  6720  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11e313b0 removed from the list
08-16 17:44:00.117  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 17:44:00.117  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 17:44:00.117  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 17:44:00.117  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:44:00.117  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 17:44:00.117  6720  6773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:44:00.127  6720  7609 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1348, name: My test thread name)
08-16 17:44:00.127  6720  7609 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1348, thread name: My test thread name)
08-16 17:44:00.127  6720  7609 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1348, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:44:00.127  6720  7610 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1350, name: My test thread name)
08-16 17:44:00.127  6720  7610 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1350, thread name: My test thread name)
08-16 17:44:00.127  6720  7610 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1350, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:44:00.137   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
08-16 17:44:00.137  6720  6773 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 17:44:00.137  6720  6773 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 17:44:00.137  6720  6773 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 17:44:00.137  6720  6773 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 17:44:00.137  6720  6773 D com.test.thalitest.ThaliTestRunner: Total duration: 23442 ms
08-16 17:44:00.137  6720  6773 I jxcore-log: Total number of executed tests:  80
08-16 17:44:00.137  6720  6773 I jxcore-log: 
08-16 17:44:00.137  6720  6773 I jxcore-log: Number of passed tests:  80
08-16 17:44:00.137  6720  6773 I jxcore-log: 
08-16 17:44:00.137  6720  6773 I jxcore-log: Number of failed tests:  0
08-16 17:44:00.137  6720  6773 I jxcore-log: 
08-16 17:44:00.137  6720  6773 I jxcore-log: Number of ignored tests:  0
08-16 17:44:00.137  6720  6773 I jxcore-log: 
08-16 17:44:00.137  6720  6773 I jxcore-log: Total duration:  23442
08-16 17:44:00.137  6720  6773 I jxcore-log: 
08-16 17:44:00.137  6720  6773 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 17:44:00.137  6720  6773 I jxcore-log: 
08-16 17:44:00.137  7611  7611 E Zygote  : MountEmulatedStorage()
08-16 17:44:00.137  7611  7611 E Zygote  : v2
08-16 17:44:00.137  7611  7611 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:44:00.137  7611  7611 I libpersona: KNOX_SDCARD not a persona
08-16 17:44:00.147  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:00.147  6720  6773 I jxcore-log: 
08-16 17:44:00.147  1018  1130 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-16 17:44:00.147  1018  7570 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:44:00 GMT], X-Android-Received-Millis=[1471362240152], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471362240114]}
08-16 17:44:00.147  1018  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-16 17:44:00.147  1018  7570 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 17:44:00.147  1018  1130 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-16 17:44:00.147  1018  7570 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-16 17:44:00.147  1018  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-16 17:44:00.147  7611  7611 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:44:00.147  1180  1717 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:44:00.147  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 17:44:00.147  4781  6790 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:44:00.147  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:00.147  6720  6773 I jxcore-log: 
08-16 17:44:00.157  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:00.157  6720  6773 I jxcore-log: 
08-16 17:44:00.157  7611  7611 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:44:00.157  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:00.157  6720  6773 I jxcore-log: 
08-16 17:44:00.157  7611  7611 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:44:00.157  1018  2064 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7611 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 17:44:00.157  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:00.157  6720  6773 I jxcore-log: 
08-16 17:44:00.157  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:00.157  6720  6773 I jxcore-log: 
08-16 17:44:00.157  6720  6720 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 17:44:00.167  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:00.167  6720  6773 I jxcore-log: 
08-16 17:44:00.167  1018  1496 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
08-16 17:44:00.167  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:00.167  6720  6773 I jxcore-log: 
08-16 17:44:00.167  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:00.167  6720  6773 I jxcore-log: 
08-16 17:44:00.167  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:00.167  6720  6773 I jxcore-log: 
08-16 17:44:00.167  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:00.167  6720  6773 I jxcore-log: 
08-16 17:44:00.167  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:44:00.167  6720  6773 I jxcore-log: 
08-16 17:44:00.167  1180  1180 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-16 17:44:00.167  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:44:00.167  6720  6773 I jxcore-log: 
08-16 17:44:00.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:00.177  6720  6773 I jxcore-log: 
08-16 17:44:00.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:00.177  6720  6773 I jxcore-log: 
08-16 17:44:00.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-16 17:44:00.177  6720  6773 I jxcore-log: 
08-16 17:44:00.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:44:00.177  6720  6773 I jxcore-log: 
08-16 17:44:00.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:00.177  6720  6773 I jxcore-log: 
08-16 17:44:00.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:00.177  6720  6773 I jxcore-log: 
08-16 17:44:00.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:44:00.177  6720  6773 I jxcore-log: 
08-16 17:44:00.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:44:00.177  6720  6773 I jxcore-log: 
08-16 17:44:00.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:00.177  6720  6773 I jxcore-log: 
08-16 17:44:00.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:00.177  6720  6773 I jxcore-log: 
08-16 17:44:00.177  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:00.177  6720  6773 I jxcore-log: 
08-16 17:44:00.187  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:00.187  6720  6773 I jxcore-log: 
08-16 17:44:00.187  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:00.187  6720  6773 I jxcore-log: 
08-16 17:44:00.187  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:00.187  6720  6773 I jxcore-log: 
08-16 17:44:00.187  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:00.187  6720  6773 I jxcore-log: 
08-16 17:44:00.187  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
08-16 17:44:00.187  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 17:44:00.187  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 17:44:00.187  1180  1180 D StatusBar.NetworkController: updateDataNetType()
08-16 17:44:00.187  1180  1180 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 17:44:00.187  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-16 17:44:00.187  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 17:44:00.187  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-16 17:44:00.187  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-16 17:44:00.197  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:44:00.197  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 17:44:00.197  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:00.197  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:00.197  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:00.197  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:00.207  6720  6720 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 17:44:00.207  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:00.207  6720  6773 I jxcore-log: 
08-16 17:44:00.217  7611  7611 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:44:00.217  7611  7611 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:00.237  7611  7611 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:44:00.247   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:44:00.267   288   288 E SMD     : DCD OFF
,08-16 17:44:00.287  1018  2064 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72,
,08-16 17:44:00.357  6720  6720 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:44:00.357  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:00.357  6720  6773 I jxcore-log: 
,08-16 17:44:00.467  7627  7627 D AndroidRuntime: 
08-16 17:44:00.467  7627  7627 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 17:44:00.467  7627  7627 D AndroidRuntime: CheckJNI is OFF,
08-16 17:44:00.467  7627  7627 D AndroidRuntime: readGMSProperty: start
08-16 17:44:00.467  7627  7627 D AndroidRuntime: readGMSProperty: already setted!!,
08-16 17:44:00.467  7627  7627 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 17:44:00.467  7627  7627 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 17:44:00.467  7627  7627 D AndroidRuntime: readGMSProperty: end
08-16 17:44:00.467  7627  7627 D AndroidRuntime: addProductProperty: start
,08-16 17:44:00.497  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:44:00.497  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:44:00.517  6720  6720 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-16 17:44:00.517  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-16 17:44:00.517  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:00.517  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:00.517  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:00.517  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-16 17:44:00.517  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-16 17:44:00.517  6720  6720 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
08-16 17:44:00.517  6720  6720 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:44:00.517  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-16 17:44:00.517  6720  6720 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 17:44:00.517  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:00.517  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:00.517  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:00.517  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:00.527  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:00.527  6720  6773 I jxcore-log: 
08-16 17:44:00.527  6720  6773 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:00.527  6720  6773 I jxcore-log: 
,08-16 17:44:00.527  7635  7635 E Zygote  : MountEmulatedStorage()
08-16 17:44:00.527  7635  7635 E Zygote  : v2
08-16 17:44:00.527  7635  7635 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:44:00.527  7635  7635 I libpersona: KNOX_SDCARD not a persona
,08-16 17:44:00.537  7635  7635 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 17:44:00.537  7635  7635 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:44:00.537  7635  7635 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-16 17:44:00.537  1018  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7635 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 17:44:00.557  1018  3639 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-16 17:44:00.557  1018  3639 D SecContentProvider2: mCursor = null
,08-16 17:44:00.567  7635  7635 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:44:00.567  7635  7635 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:00.597  7635  7635 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-16 17:44:00.597  7635  7635 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-16 17:44:00.597  7635  7635 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-16 17:44:00.607  1018  3350 D SSRM:n  : SIOP:: AP = 320
,08-16 17:44:00.617  7635  7635 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-16 17:44:00.617  7635  7635 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-16 17:44:00.617  7635  7635 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 17:44:00.617  7635  7635 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:44:00.617  1018  3639 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-16 17:44:00.617  1018  3639 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-16 17:44:00.617  1018  3639 I ActivityManager: Killing 6990:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-16 17:44:00.617  7627  7627 E AffinityControl: AffinityControl: registerfunction enter
,08-16 17:44:00.627  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-16 17:44:00.627  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:00.627  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:00.627  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:00.627  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:00.647  7652  7652 E Zygote  : MountEmulatedStorage()
,08-16 17:44:00.647  7652  7652 E Zygote  : v2
08-16 17:44:00.647  7652  7652 I libpersona: KNOX_SDCARD checking this for 10001
08-16 17:44:00.647  7652  7652 I libpersona: KNOX_SDCARD not a persona
,08-16 17:44:00.647  7652  7652 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-16 17:44:00.647  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7652 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:44:00.647  7627  7627 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-16 17:44:00.647  7652  7652 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:44:00.647  7652  7652 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:44:00.667  1018  1496 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-16 17:44:00.667  1018  1496 D PackageManager: START PACKAGE DELETE: observer{945580268}
08-16 17:44:00.667  1018  1496 D PackageManager: pkg{<packageName>}
08-16 17:44:00.667  1018  1496 D PackageManager: user{0}
08-16 17:44:00.667  1018  1496 D PackageManager: caller{2000}
08-16 17:44:00.667  1018  1496 D PackageManager: flags{2}
08-16 17:44:00.667  1018  1496 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-16 17:44:00.667  1018  1496 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-16 17:44:00.667  1018  1496 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-16 17:44:00.667  1018  1496 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-16 17:44:00.667  1018  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-16 17:44:00.667  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-16 17:44:00.667  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-16 17:44:00.667  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-16 17:44:00.667  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-16 17:44:00.677  1018  1057 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-16 17:44:00.697  7652  7652 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:44:00.697  7652  7652 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:00.767  1018  1057 W PackageSettings: Skipping PackageSetting{36c12609 com.example.hello/10168} due to missing metadata,
,08-16 17:44:00.817  1756  1756 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 17:44:00.827  7007  7007 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:44:00.837  1018  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-16 17:44:00.837  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:44:00.837  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:00.837  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:44:00.837  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:00.857  7669  7669 E Zygote  : MountEmulatedStorage()
08-16 17:44:00.857  7669  7669 I libpersona: KNOX_SDCARD checking this for 10031
08-16 17:44:00.857  7669  7669 E Zygote  : v2
08-16 17:44:00.857  7669  7669 I libpersona: KNOX_SDCARD not a persona
,08-16 17:44:00.857  7669  7669 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:44:00.857  7669  7669 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 17:44:00.867  7669  7669 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:44:00.867  1018  1495 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7669 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-16 17:44:00.877  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-16 17:44:00.877  1018  1043 I ActivityManager: Killing 6720:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-16 17:44:00.877  1018  1043 I ActivityManager:   Force finishing activity ActivityRecord{2730208f u0 com.test.thalitest/.MainActivity t2}
,08-16 17:44:00.877  1018  1494 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,08-16 17:44:00.877  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.877  7007  7007 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-16 17:44:00.877  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:00.877  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:00.887  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
08-16 17:44:00.887  7007  7007 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-16 17:44:00.897  2610  2621 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-16 17:44:00.897  7669  7669 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:44:00.897  7669  7669 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:00.897  1018  1043 D InputDispatcher: Focus left window: 6720
,08-16 17:44:00.897   258   449 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-16 17:44:00.897   258   915 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-16 17:44:00.917  1018  1043 D InputDispatcher: Focused application released
,08-16 17:44:00.917  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:44:00.917  1018  1043 D FocusedStackFrame: Set to : 0
08-16 17:44:00.917  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:44:00.927  1018  1043 W ActivityManager: mDVFSHelper.acquire(),
,08-16 17:44:00.937  1018  1043 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-16 17:44:00.937  1756  1756 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-16 17:44:00.937  1756  1756 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-16 17:44:00.947  1756  1756 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-16 17:44:00.947  1756  1756 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-16 17:44:00.967  1018  1057 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-16 17:44:00.967  1018  3640 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:44:00.967  1498  1498 D Launcher: onRestart, Launcher: 1024704
,08-16 17:44:00.967  1018  1136 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:44:00.997  1018  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-16 17:44:00.997  1018  1130 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-16 17:44:01.007  1498  1498 D Launcher: onStart, Launcher: 1024704
,08-16 17:44:01.007  1498  1498 D Launcher.HomeView: onStart
,08-16 17:44:01.007  1498  1498 D Launcher: onResume, Launcher: 1024704
,08-16 17:44:01.017  1018  1030 D SettingsProvider: name = kids_home_mode
,08-16 17:44:01.017  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:44:01.027  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:44:01.027  1018  1030 D SettingsProvider: selectionArgs: false
08-16 17:44:01.027  1018  1030 D SettingsProvider: selectionArgs: 10006
08-16 17:44:01.027  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:44:01.027  1018  1030 D SettingsProvider: ret = -1
,08-16 17:44:01.027  1498  1498 D Launcher.HomeView: onResume
,08-16 17:44:01.027  2647  2647 I art     : Explicit concurrent mark sweep GC freed 19868(1134KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 2.344ms total 56.282ms
,08-16 17:44:01.047  1498  1498 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-16 17:44:01.057  1756  1756 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 17:44:01.067  1756  1756 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-16 17:44:01.077  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-16 17:44:01.087  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010,
08-16 17:44:01.087  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0,
08-16 17:44:01.087  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-16 17:44:01.087  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-16 17:44:01.087  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-16 17:44:01.097  1844  1844 E SamsungIME: mOCRHelper is null
,08-16 17:44:01.097  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-16 17:44:01.097  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-16 17:44:01.107  1018  1042 E libprocessgroup: failed to kill 1 processes for processgroup 6720
,08-16 17:44:01.117  2015  2185 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 17:44:01.117  1498  1498 D MenuAppsGridFragment: onResume
,08-16 17:44:01.117  4781  4781 I art     : Explicit concurrent mark sweep GC freed 12834(732KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.365ms total 141.667ms
,08-16 17:44:01.127  1498  1498 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-16 17:44:01.127  1498  1498 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-16 17:44:01.127  1468  1468 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 17:44:01.127  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:44:01.147  1448  1448 D RegisteredServicesCache: empty dynamic service
,08-16 17:44:01.147  1018  1030 D ActivityManager: handle home activity for 0
08-16 17:44:01.147  1018  1030 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-16 17:44:01.147  1018  1030 D KnoxTimeoutHandler: post home show event for user 0
08-16 17:44:01.147  1018  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 17:44:01.147  1018  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 17:44:01.147  1018  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-16 17:44:01.147  1498  1498 D Launcher.HomeView: onPause
,08-16 17:44:01.147  1498  1498 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-16 17:44:01.157  7151  7151 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-16 17:44:01.177  7071  7071 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:44:01.177  7071  7071 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-16 17:44:01.177  7071  7071 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-16 17:44:01.177  7071  7071 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-16 17:44:01.197   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-16 17:44:01.197  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-16 17:44:01.207  1018  1496 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
08-16 17:44:01.207  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.207  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.207  1018  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:44:01.207  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-16 17:44:01.207  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-16 17:44:01.207  1018  1136 D InputDispatcher: Focus entered window: 1498
,08-16 17:44:01.207  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:44:01.207  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 17:44:01.207  1018  1508 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-16 17:44:01.207  1018  1508 D SecContentProvider2: mCursor = null
,08-16 17:44:01.207  1498  1498 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 17:44:01.207  1018  1125 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-16 17:44:01.207  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:01.207  1018  1125 V NetworkStats: performPollLocked(flags=0x3)
,08-16 17:44:01.217  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:44:01.217  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:44:01.217  1018  1125 V NetworkStats: performPollLocked() took 9ms
08-16 17:44:01.217  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:01.227  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:01.227  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:01.237  1018  3639 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-16 17:44:01.237  1018  3639 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.237  1018  3639 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.237  1018  3639 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:44:01.237  1018  3639 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 17:44:01.247   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-16 17:44:01.257  1498  1498 V ActivityThread: updateVisibility : ActivityRecord{572067c token=android.os.BinderProxy@146ac271 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-16 17:44:01.257  1498  1498 D Launcher.HomeView: onStop
,08-16 17:44:01.257  1018  1494 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 17:44:01.257  1018  1494 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6720 uid 10171
,08-16 17:44:01.267  1018  7696 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:44:01.277  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-16 17:44:01.277  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 17:44:01.287  1844  1844 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-16 17:44:01.287  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-16 17:44:01.287  1018  1018 V EnterpriseBillingPolicy: uID is 10171
08-16 17:44:01.287  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 17:44:01.287  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 17:44:01.297  6917  7695 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-16 17:44:01.297  6917  7695 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:44:01.297  6917  7695 I System.out: (HTTPLog)-Static: isShipBuild true
08-16 17:44:01.297  6917  7695 I System.out: (HTTPLog)-Thread-1250-290247543: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-16 17:44:01.297  6917  7695 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:44:01.297  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 17:44:01.297  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 17:44:01.297  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 17:44:01.297  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-16 17:44:01.297  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 17:44:01.307  1018  1018 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-16 17:44:01.307  1448  1448 D RegisteredComponentCache: Collect Tech packages for Knox
,08-16 17:44:01.317   278  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 17:44:01.317   278  1013 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-16 17:44:01.317  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:44:01.327  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-16 17:44:01.337  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-16 17:44:01.337  1018  1042 W TextServicesManagerService: no available spell checker services found
,08-16 17:44:01.347  6917  7695 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 17:44:01.357  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 17:44:01.357  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-16 17:44:01.357  1018  3350 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-16 17:44:01.357  1018  1048 W ActivityManager: mDVFSHelper.release()
,08-16 17:44:01.357  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7e8b7cc u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:144289
,08-16 17:44:01.357  1018  1162 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-16 17:44:01.367  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-16 17:44:01.367  1018  1018 V EnterpriseBillingPolicy: uID is 10171
,08-16 17:44:01.367  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
,08-16 17:44:01.367  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 17:44:01.367  2767  7701 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
08-16 17:44:01.367  2767  7701 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-16 17:44:01.367  2767  7701 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-16 17:44:01.377  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 17:44:01.377  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 17:44:01.377  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 17:44:01.377  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-16 17:44:01.377  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 17:44:01.387  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,08-16 17:44:01.387  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,08-16 17:44:01.387  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-16 17:44:01.387  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 17:44:01.387  7042  7042 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-16 17:44:01.397  7089  7089 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-16 17:44:01.397  7089  7089 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-16 17:44:01.397  7089  7089 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-16 17:44:01.407  1180  1180 I StatusBar: Icon Only
08-16 17:44:01.407  7089  7089 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-16 17:44:01.407  7089  7089 I SA      : [OR] == isSIMCardReady false ==
08-16 17:44:01.407  1180  1180 D PanelView: There is/are notification(s) 
,08-16 17:44:01.407  7089  7089 I SA      : [SCU] == networkStateCheck == true
,08-16 17:44:01.417  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:01.417  7089  7089 I SA      : [DM] getCountryCodeFromCSC : PL
08-16 17:44:01.417  7089  7089 I SA      : isChinaCountryCode : false
08-16 17:44:01.417  7089  7089 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-16 17:44:01.417  7089  7089 I SA      : [OR] == networkStateCheck true ==
,08-16 17:44:01.417  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:01.427  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:01.427  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:01.427  7089  7089 I SA      : [OR] GetMyCountryZoneTask
,08-16 17:44:01.427  7089  7089 I SA      : [OR] onReceive END
,08-16 17:44:01.437  6917  7695 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 17:44:01.437  1225  1225 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:44:01.447  1018  1497 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-16 17:44:01.447  1018  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.447  1018  1497 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.447  1018  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.447  1018  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-16 17:44:01.447  2767  7701 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-16 17:44:01.457  7089  7702 I SA      : [SRS] prepareGetMyCountryZone
,08-16 17:44:01.487  2767  7701 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-16 17:44:01.487  1018  1031 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-16 17:44:01.487  2767  7701 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-16 17:44:01.487  1018  1031 D SecContentProvider2: mCursor = null
08-16 17:44:01.487  2767  7701 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-16 17:44:01.487  2767  7701 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-16 17:44:01.487  2767  7701 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-16 17:44:01.497  2767  7701 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-16 17:44:01.497  2767  7701 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-16 17:44:01.507  7135  7135 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-16 17:44:01.507  2767  7701 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-16 17:44:01.517  7135  7135 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-16 17:44:01.517  7089  7702 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-16 17:44:01.517  7089  7702 I SA      : [SSP] query invoked
,08-16 17:44:01.527  7089  7702 I SA      : [TPMU] GetMccFromDB : null
,08-16 17:44:01.527  7089  7702 I SA      : [SCU] getMccFromPreferece mcc = 260
08-16 17:44:01.527  7089  7702 I SA      : [LBE] isSupportCheckDomainRegion : false
08-16 17:44:01.527  7135  7135 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
08-16 17:44:01.527  7089  7702 I SA      : [TPM] isNoProxy(default) : true
,08-16 17:44:01.537  7135  7135 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-16 17:44:01.537  2767  7701 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-16 17:44:01.537  1018  1136 I ActivityManager: Killing 7119:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-16 17:44:01.537  1018  1057 I art     : Explicit concurrent mark sweep GC freed 85764(5MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 24MB/36MB, paused 3.101ms total 380.501ms
08-16 17:44:01.537  7089  7702 E File    : fail readDirectory() errno=2
,08-16 17:44:01.557  2919  2919 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 17:44:01 GMT+02:00 2016
,08-16 17:44:01.557  1018  1496 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-16 17:44:01.557  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.557  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:01.557  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:44:01.557  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 17:44:01.567  2919  2919 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-16 17:44:01.577  2919  2919 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-16 17:44:01.577  2919  2919 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 17:44:01.587  2919  2919 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 17:44:01.587  2919  7708 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 17:44:01.587  2919  7708 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-16 17:44:01.587  2919  7708 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-16 17:44:01.597  2919  7708 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-16 17:44:01.597  2919  7708 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-16 17:44:01.597  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-16 17:44:01.607  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:01.607  1018  1030 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:44:01.607  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:01.637  2919  7708 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-16 17:44:01.637  2919  7708 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-16 17:44:01.647  1018  1495 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-16 17:44:01.647  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.647  2919  2919 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-16 17:44:01.647  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.647  1018  1495 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-16 17:44:01.647  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-16 17:44:01.647  1018  1057 D PackageManager: delete codoeFile: 
,08-16 17:44:01.657  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:01.657  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 17:44:01.657  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:44:01.657  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:44:01.667  1018  1057 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-16 17:44:01.667  1018  1057 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-16 17:44:01.667  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:01.667  1018  1136 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:44:01.667  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
08-16 17:44:01.667  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:01.667  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:44:01.667  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:44:01.667  1018  1057 D PackageManager: result of delete: 1{945580268}
,08-16 17:44:01.667  7151  7151 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-16 17:44:01.677  7151  7151 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-16 17:44:01.677  7151  7151 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-16 17:44:01.677  7151  7151 D InitializeManagerStateMachine: exit::IDLE
08-16 17:44:01.677  7151  7151 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-16 17:44:01.677  7151  7151 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-16 17:44:01.677  7151  7151 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-16 17:44:01.677  7151  7151 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-16 17:44:01.677  7151  7151 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-16 17:44:01.677  7151  7151 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-16 17:44:01.677  7151  7151 D InitializeManagerStateMachine: entry::SUCCESS
08-16 17:44:01.677  7151  7151 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-16 17:44:01.687   278  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 17:44:01.687   278  1013 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-16 17:44:01.687  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:01.687  7627  7627 D AndroidRuntime: Shutting down VM
,08-16 17:44:01.687  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:44:01.687  4781  4781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 17:44:01.697  7151  7151 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-16 17:44:01.697  7151  7151 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
08-16 17:44:01.697  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:44:01.697  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:44:01.697  7151  7151 D InitializeManagerStateMachine: exit::SUCCESS
08-16 17:44:01.697  7151  7151 D InitializeManagerStateMachine: entry::IDLE
,08-16 17:44:01.697  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:01.697  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:44:01.697  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:44:01.697  1018  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-16 17:44:01.697  1018  1057 D PackageManager: userId{-1}
08-16 17:44:01.697  1018  1057 D PackageManager: andCode{true}
,08-16 17:44:01.707  1018  1030 I ActivityManager: Killing 4259:com.google.process.gapps/u0a11 (adj 15): empty #21
,08-16 17:44:01.707  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:44:01.707  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:44:01.707  1018  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.707  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:01.717  4781  7186 I iu.UploadsManager: num queued entries: 0
,08-16 17:44:01.717  4781  7186 I iu.UploadsManager: num updated entries: 0
,08-16 17:44:01.717  4781  7186 I iu.SyncManager: NEXT; no task
,08-16 17:44:01.717  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:01.717  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:01.717  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:01.717  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:01.727  7711  7711 E Zygote  : MountEmulatedStorage(),
08-16 17:44:01.727  7711  7711 I libpersona: KNOX_SDCARD checking this for 10003
08-16 17:44:01.727  7711  7711 E Zygote  : v2
08-16 17:44:01.727  7711  7711 I libpersona: KNOX_SDCARD not a persona
,08-16 17:44:01.727  7711  7711 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:44:01.737  7711  7711 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 17:44:01.737  7711  7711 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:44:01.737  1018  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7711 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 17:44:01.737   255   255 E lowmemorykiller: Error writing /proc/4259/oom_score_adj; errno=22
08-16 17:44:01.737  1018  1494 W ActivityManager: ProcessRecord{3df614e6 4259:com.google.process.gapps/u0a11} is already killed
,08-16 17:44:01.737  1018  1494 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 17:44:01.747  1018  1494 I ActivityManager: Existing provider com.google.android.gsf/.gservices.GservicesProvider is crashing; detaching ProcessRecord{3ffd382e 4781:com.google.android.gms/u0a11}
,08-16 17:44:01.747  1018  1494 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gsf
,08-16 17:44:01.747  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:01.757  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:01.757  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:01.757  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:01.767  7711  7711 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:44:01.767  7711  7711 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:01.767  7723  7723 E Zygote  : MountEmulatedStorage()
,08-16 17:44:01.767  7723  7723 I libpersona: KNOX_SDCARD checking this for 10011
08-16 17:44:01.767  7723  7723 E Zygote  : v2
08-16 17:44:01.767  7723  7723 I libpersona: KNOX_SDCARD not a persona
08-16 17:44:01.767  1018  1494 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7723 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-16 17:44:01.777  7723  7723 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:44:01.777  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-16 17:44:01.777  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-16 17:44:01.777  7723  7723 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:44:01.777  7723  7723 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:44:01.807  7723  7723 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:44:01.807  7723  7723 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:01.807  1498  1498 I Choreographer: Skipped 31 frames!  The application may be doing too much work on its main thread.
,08-16 17:44:01.817  1498  1498 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@146ac271 time:144740
,08-16 17:44:01.817  1018  1496 I ActivityManager: Killing 7352:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-16 17:44:01.817  2015  7709 I qtaguid : Tagging socket 49 with tag 1000040700000000{268436487,0} for uid -1, pid: 2015, getuid(): 10011
,08-16 17:44:01.857  7723  7723 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-16 17:44:01.857  1018  3640 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:44:01.857  1018  3640 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.857  1018  3640 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.867  1018  3640 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:44:01.867  1018  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:44:01.897  7627  7627 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-16 17:44:01.907  1018  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:44:01.907  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.907  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:01.907  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:44:01.907  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:44:01.927  7723  7723 I GoogleHttpClient: GMS http client unavailable, use old client
,08-16 17:44:01.947  7723  7723 I GoogleHttpClient: GMS http client unavailable, use old client
,08-16 17:44:01.987  1018  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:44:01.997  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:01.997  1018  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:44:01.997  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:44:02.007  1018  1043 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-16 17:44:02.007  2919  2919 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 17:44:02 GMT+02:00 2016
,08-16 17:44:02.007  1018  1494 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-16 17:44:02.017  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 17:44:02.017  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:02.017  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:02.017  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 17:44:02.027  2919  2919 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.,
,08-16 17:44:02.027  2919  2919 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-16 17:44:02.027  1018  1496 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-16 17:44:02.027  1018  1496 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-16 17:44:02.027  1018  1496 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-16 17:44:02.027  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:02.027  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:02.027  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:02.027  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:02.037  2919  2919 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 17:44:02.047  7754  7754 E Zygote  : MountEmulatedStorage()
,08-16 17:44:02.047  7754  7754 E Zygote  : v2
08-16 17:44:02.047  7754  7754 I libpersona: KNOX_SDCARD checking this for 10090
08-16 17:44:02.047  7754  7754 I libpersona: KNOX_SDCARD not a persona
,08-16 17:44:02.047  7754  7754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:44:02.047  7754  7754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-16 17:44:02.047  1018  1496 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7754 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-16 17:44:02.047  2919  2919 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 17:44:02.047  7754  7754 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:44:02.057  2919  7753 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 17:44:02.057  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-16 17:44:02.067  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:02.067  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:02.067  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:02.067  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:02.067   305   305 I art     : Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 21.939ms
,08-16 17:44:02.067  2919  7753 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-16 17:44:02.077  1018  1136 I TactileAssist: enable value -1
08-16 17:44:02.077  1018  1136 I TactileAssist: internal enable value -1
08-16 17:44:02.077  1018  1136 I TactileAssist: intensity value -1
08-16 17:44:02.077  1018  1136 I TactileAssist: saveAppList value true
,08-16 17:44:02.077  7754  7754 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:44:02.077  7754  7754 D ActivityThread: Added TimaKeyStore provider
08-16 17:44:02.087  1018  1136 I TactileAssist: List of disabled apps :
08-16 17:44:02.087  2919  7753 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-16 17:44:02.087  2919  7753 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-16 17:44:02.087  7089  7702 I SA      : [RC New] Execute method=[GET] start
08-16 17:44:02.087   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.761ms
,08-16 17:44:02.107   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 667us total 16.600ms
,08-16 17:44:02.117  7769  7769 E Zygote  : MountEmulatedStorage()
08-16 17:44:02.117  7769  7769 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:44:02.117  7769  7769 E Zygote  : v2
08-16 17:44:02.117  7769  7769 I libpersona: KNOX_SDCARD not a persona
08-16 17:44:02.117  1018  1043 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7769 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 17:44:02.117  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-16 17:44:02.117  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:02.117  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:02.117  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:02.117  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:02.117  7769  7769 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 17:44:02.127  7089  7702 I SA      : [RC New] Security=[true]
,08-16 17:44:02.127  7769  7769 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 17:44:02.127  7769  7769 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:44:02.127  7089  7702 I System.out: Thread-1296(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
08-16 17:44:02.127  7089  7702 I System.out: Thread-1296(ApacheHTTPLog):isSBSettingEnabled false
08-16 17:44:02.127  7089  7702 I System.out: Thread-1296(ApacheHTTPLog):isShipBuild true
08-16 17:44:02.127  7089  7702 I System.out: Thread-1296(ApacheHTTPLog):SMARTBONDING_ENABLED is false
08-16 17:44:02.127  7089  7702 I System.out: Thread-1296(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-16 17:44:02.127   278  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 17:44:02.127   278  1013 D Netd    : getNetworkForDns: using netid 504 for uid 10036
,08-16 17:44:02.137  7780  7780 E Zygote  : MountEmulatedStorage()
08-16 17:44:02.137  7780  7780 E Zygote  : v2
08-16 17:44:02.137  7780  7780 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:44:02.137  7780  7780 I libpersona: KNOX_SDCARD not a persona
,08-16 17:44:02.137  7780  7780 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 17:44:02.137  2919  7753 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-16 17:44:02.137  7780  7780 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 17:44:02.147  7780  7780 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:44:02.147  1018  1043 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7780 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 17:44:02.147  4781  7752 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-16 17:44:02.147  4781  7752 D SchedPeriodicTask: Scheduled AdAttestation task.
08-16 17:44:02.147  7769  7769 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:44:02.157  7769  7769 D ActivityThread: Added TimaKeyStore provider
08-16 17:44:02.157  2919  7753 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-16 17:44:02.157  2919  7753 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.klmsagent/databases/klms.db'.
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
,08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:02.157  2919  7753 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:02.157  2919  7753 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:02.157  2919  7753 W SQLiteOpenHelper: Opened klms.db in read-only mode
,08-16 17:44:02.167  2919  7753 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-16 17:44:02.167  2919  7753 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-16 17:44:02.167  7780  7780 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:44:02.167  7780  7780 D ActivityThread: Added TimaKeyStore provider

```
