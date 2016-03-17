#### Test 63186632d456b18_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
03-17 09:50:14.448   290   290 E SMD     : DCD OFF
03-17 09:50:14.448   317   317 I ServiceManager: Waiting for service AtCmdFwd...
--------- beginning of system
03-17 09:50:14.488  1019  2738 D SSRM:a  : DeviceInfo:: 000000000000
03-17 09:50:14.488  1019  2738 D SSRM:a  : SettingsAirViewInfo:: 000000000
,03-17 09:50:15.428  5921  5921 D AndroidRuntime: 
03-17 09:50:15.428  5921  5921 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 09:50:15.428  5921  5921 D AndroidRuntime: CheckJNI is OFF
03-17 09:50:15.438  5921  5921 D AndroidRuntime: readGMSProperty: start
03-17 09:50:15.438  5921  5921 D AndroidRuntime: readGMSProperty: already setted!!
03-17 09:50:15.438  5921  5921 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 09:50:15.438  5921  5921 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 09:50:15.438  5921  5921 D AndroidRuntime: readGMSProperty: end
03-17 09:50:15.438  5921  5921 D AndroidRuntime: addProductProperty: start
03-17 09:50:15.448   317   317 I ServiceManager: Waiting for service AtCmdFwd...
03-17 09:50:15.568  5921  5921 E AffinityControl: AffinityControl: registerfunction enter
03-17 09:50:15.598  5921  5921 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 09:50:15.618  1019  1481 E PersonaManagerService: inState():  stateMachine is null !!
03-17 09:50:15.618  1019  1481 I PersonaManagerService: PersonaId don't exist
03-17 09:50:15.618  1019  1481 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 09:50:15.618  1019  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 09:50:15.638  1019  1481 W ActivityManager: mDVFSHelper.acquire()
03-17 09:50:15.638  1019  1481 D FocusedStackFrame: Set to : 0
03-17 09:50:15.648  1019  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:50:15.648  1019  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:50:15.648  1019  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:50:15.648  1019  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:50:15.648  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 09:50:15.648  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 09:50:15.668  1019  1481 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5933 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 09:50:15.668  1019  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 09:50:15.668  1019  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 09:50:15.668  5933  5933 E Zygote  : MountEmulatedStorage()
03-17 09:50:15.668  5933  5933 I libpersona: KNOX_SDCARD checking this for 10167
03-17 09:50:15.668  5933  5933 E Zygote  : v2
03-17 09:50:15.668  5933  5933 I libpersona: KNOX_SDCARD not a persona
03-17 09:50:15.668  1019  1481 D InputDispatcher: Focused application set to: xxxx
03-17 09:50:15.668  1019  1481 D InputDispatcher: Focus left window: 1482
03-17 09:50:15.668  5933  5933 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:50:15.668  5921  5921 D AndroidRuntime: Shutting down VM
03-17 09:50:15.668  5933  5933 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:50:15.668  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 09:50:15.668  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 09:50:15.668  5933  5933 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 09:50:15.668   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
03-17 09:50:15.688  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 09:50:15.688  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 09:50:15.698  5933  5933 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:50:15.698  5933  5933 D ActivityThread: Added TimaKeyStore provider
03-17 09:50:15.698  1019  1536 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 09:50:15.698  1019  1019 V ActivityManager: Display changed displayId=0
03-17 09:50:15.708  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 09:50:15.728  1019  1536 D PersonaManager: isKioskContainerExistOnDevice
03-17 09:50:15.748  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 09:50:15.768   259  1856 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
03-17 09:50:15.768   259   450 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
03-17 09:50:15.778  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{2be879d0 token=android.os.BinderProxy@2e8ac929 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 09:50:15.778  1482  1482 D Launcher: onTrimMemory. Level: 20
03-17 09:50:15.828  5933  5933 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-17 09:50:15.848  5933  5933 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 699-701)
03-17 09:50:15.848  5933  5933 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 09:50:15.868  5933  5933 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1de55bb1}
03-17 09:50:15.868  5933  5933 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 09:50:15.868  5933  5933 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 09:50:15.878  5921  5921 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 09:50:15.898  5933  5933 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 09:50:15.908  5933  5933 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:50:15.908  5933  5933 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 09:50:15.918  5933  5933 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 09:50:15.928  5933  5933 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 09:50:15.928  5933  5933 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 09:50:15.928  5933  5933 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 09:50:15.928  5933  5933 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 09:50:15.928  5933  5933 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 09:50:15.928  5933  5933 I Adreno-EGL: Local Branch: 
03-17 09:50:15.928  5933  5933 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 09:50:15.928  5933  5933 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 09:50:15.928  5933  5933 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 09:50:16.148  5933  5933 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:50:16.158  5933  5933 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 09:50:16.168  5933  5933 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-17 09:50:16.168  5933  5933 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 09:50:16.168  5933  5933 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 09:50:16.178  5933  5933 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:50:16.178  5933  5933 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:50:16.228  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{e2fa271 u0 com.test.thalitest/.MainActivity t22}
,03-17 09:50:16.328  5933  5973 D OpenGLRenderer: Render dirty regions requested: true
,03-17 09:50:16.328  1019  1480 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 09:50:16.328  1019  1480 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 09:50:16.328  1019  1480 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 09:50:16.328  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 09:50:16.328  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 09:50:16.338  5933  5960 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 09:50:16.338  5933  5933 V ActivityThread: updateVisibility : ActivityRecord{3f4a8559 token=android.os.BinderProxy@f856ea3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-17 09:50:16.348  5933  5933 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-17 09:50:16.348  5933  5933 D PhoneWindow: *FMB* isFloatingMenuEnabled return false,
,03-17 09:50:16.358   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,03-17 09:50:16.368  1019  1032 D InputDispatcher: Focus entered window: 5933
,03-17 09:50:16.368  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 09:50:16.368  5933  5933 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 09:50:16.368  5933  5973 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 09:50:16.368  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 09:50:16.378  5933  5973 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 09:50:16.378  5933  5973 D OpenGLRenderer: Enabling debug mode 0
,03-17 09:50:16.398  1019  1539 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 09:50:16.408  1175  1175 I StatusBar: Icon Only
,03-17 09:50:16.408  1175  1175 D PanelView: There is/are notification(s) 
,03-17 09:50:16.408  1019  5976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 09:50:16.428  1019  1049 I ActivityManager: Displayed Component not be shown by security: +701ms (total +783ms)
,03-17 09:50:16.428  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e2fa271 u0 com.test.thalitest/.MainActivity t22} time:81288
03-17 09:50:16.428  1019  1049 W ActivityManager: mDVFSHelper.release()
,03-17 09:50:16.438  1849  1849 I SamsungIME: getCurrentCandidateView
,03-17 09:50:16.438  5933  5933 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 09:50:16.438   259  1099 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
03-17 09:50:16.438  5933  5933 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f856ea3 time:81295
03-17 09:50:16.438   259   450 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,03-17 09:50:16.448   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 09:50:16.498  5933  5933 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5933
,03-17 09:50:16.498  1019  2788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 09:50:16.528  1849  1849 D SamsungIME: Dismiss ExpandCandiate
,03-17 09:50:16.558  1849  1849 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 09:50:16.598  1849  1849 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 09:50:16.608  1849  1849 I SamsungIME: KeybaordView init() : load resources
,03-17 09:50:16.638  1849  1849 I SamsungIME: getCurrentKeyboard
,03-17 09:50:16.638  1849  1849 I SamsungIME: getTextKeyboard
,03-17 09:50:16.648  1849  1849 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 09:50:16.668  5933  5933 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 09:50:16.808  1849  1863 W art     : Suspending all threads took: 6.591ms,
,03-17 09:50:16.868  5933  5974 D jxcore_app_log: JniHelper::setJavaVM(0xb8bb4448), pthread_self() = -1191344440
,03-17 09:50:16.878  5933  5974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 09:50:16.878  5933  5974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 09:50:16.878  5933  5974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 09:50:16.878  5933  5974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 09:50:16.878  5933  5974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-17 09:50:16.878  5933  5974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@371c01ce added. We now have 1 listener(s)
,03-17 09:50:16.878  5933  5974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,03-17 09:50:16.878  5933  5974 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,03-17 09:50:16.878  5933  5974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-17 09:50:16.878  5933  5974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
03-17 09:50:16.878  5933  5974 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 09:50:16.878  5933  5974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: MANUFACTURER_DATA
03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10bab685 added. We now have 1 listener(s)
,03-17 09:50:16.888  5933  5974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 09:50:16.888  5933  5974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 09:50:16.898  5933  5974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 09:50:16.898  5933  5974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 09:50:16.898  5933  5974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 09:50:16.898  5933  5974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 09:50:16.898  5933  5974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-17 09:50:16.898  5933  5974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
03-17 09:50:16.908  5933  5974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 09:50:16.908  5933  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 09:50:16.908  5933  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 09:50:16.908  5933  5974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 09:50:16.908  5933  5974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 09:50:16.908  5933  5974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 09:50:16.908  5933  5974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 09:50:16.908  5933  5974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 09:50:16.908  5933  5974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 09:50:16.908  5933  5974 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 09:50:16.918  5933  5933 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 09:50:16.918  5933  5933 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 09:50:16.938  5933  5933 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 09:50:17.448   290   290 E SMD     : DCD OFF
,03-17 09:50:17.448   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 09:50:17.508  5933  5986 W jxcore-log: Initializing JXcore engine
03-17 09:50:17.508  5933  5986 W jxcore-log: JXcore engine is ready
,03-17 09:50:17.558  1865  1865 E audit   : type=1400 msg=audit(1458204617.558:205): avc:  denied  { ioctl } for  pid=5986 comm="Thread-1025" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
03-17 09:50:17.558  1865  1865 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 09:50:17.558  1865  1865 E audit   : type=1300 msg=audit(1458204617.558:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e8968f8 items=0 ppid=307 ppcomm=main pid=5986 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1025" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null),
03-17 09:50:17.558  1865  1865 E audit   : type=1320 msg=audit(1458204617.558:205): 
,03-17 09:50:17.568  5933  5986 W jxcore-log: Starting JXcore engine
,03-17 09:50:17.668  5933  5986 W jxcore-log: Platform android
03-17 09:50:17.668  5933  5986 W jxcore-log: 
03-17 09:50:17.668  5933  5986 W jxcore-log: Process ARCH arm
03-17 09:50:17.668  5933  5986 W jxcore-log: 
,03-17 09:50:17.878  5933  5986 I jxcore-log: JXcore Cordova bridge is ready!
03-17 09:50:17.878  5933  5986 I jxcore-log: 
,03-17 09:50:17.878  5933  5986 W jxcore-log: JXcore engine is started
,03-17 09:50:17.888  5933  5974 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 09:50:17.888  5933  5933 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 09:50:17.898  5933  5986 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 09:50:17.898  5933  5986 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 09:50:17.908  5933  5933 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-17 09:50:17.908  5933  5933 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 09:50:17.908  1019  1031 D FocusedStackFrame: Set to : 0
03-17 09:50:17.908  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 09:50:17.908  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 09:50:17.908  1019  1031 D InputDispatcher: Focused application set to: xxxx
03-17 09:50:17.908  1019  1031 D InputDispatcher: Focus left window: 5933
03-17 09:50:17.918  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 09:50:17.918  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 09:50:17.918  1019  1031 I ActivityManager: Killing 4967:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
03-17 09:50:17.928  5933  5974 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 09:50:17.938   259   450 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,03-17 09:50:17.948   259   452 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,03-17 09:50:17.958  1019  1032 W ActivityManager: mDVFSHelper.acquire()
,03-17 09:50:17.958  5933  5933 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@c66f50b that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 09:50:17.958  5933  5933 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@c66f50b that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:50:17.958  5933  5933 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 09:50:17.958  1019  1032 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 09:50:17.968  5933  5933 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@32fa6cda that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 09:50:17.968  5933  5933 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@32fa6cda that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:50:17.968  5933  5933 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 09:50:17.988  1482  1482 D Launcher: onRestart, Launcher: 1055979524
,03-17 09:50:17.988  1482  1482 D Launcher: onStart, Launcher: 1055979524
,03-17 09:50:17.988  1482  1482 D Launcher.HomeView: onStart
,03-17 09:50:17.988  1482  1482 D Launcher: onResume, Launcher: 1055979524
,03-17 09:50:17.988  1019  1538 D SettingsProvider: name = kids_home_mode
,03-17 09:50:17.988  1019  1538 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:50:17.988  1019  1538 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:50:17.988  1019  1538 D SettingsProvider: selectionArgs: false
,03-17 09:50:17.988  1019  1538 D SettingsProvider: selectionArgs: 10006
03-17 09:50:17.988  1019  1538 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-17 09:50:17.988  1019  1538 D SettingsProvider: ret = -1
,03-17 09:50:17.988  1482  1482 D Launcher.HomeView: onResume
,03-17 09:50:17.998  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 09:50:17.998  1482  1482 D MenuAppsGridFragment: onResume
,03-17 09:50:18.008  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:50:18.008  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:18.008  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,03-17 09:50:18.008  1019  1351 D ActivityManager: handle home activity for 0
,03-17 09:50:18.008  1019  1351 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-17 09:50:18.008  1019  1351 D KnoxTimeoutHandler: post home show event for user 0
03-17 09:50:18.008  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 09:50:18.008  1019  1351 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 09:50:18.008  1019  1351 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 09:50:18.008  1019  1351 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 09:50:18.008  1482  1482 D Launcher.HomeView: onPause
03-17 09:50:18.008  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 09:50:18.008  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 09:50:18.008  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 09:50:18.008  1019  1032 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,03-17 09:50:18.008  1019  1032 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
03-17 09:50:18.018  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 09:50:18.018  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:50:18.018  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:18.018  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
03-17 09:50:18.028  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:50:18.028  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:18.028  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
03-17 09:50:18.028  4983  4983 D GalleryCacheReady: Receive : home resume
03-17 09:50:18.028  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:50:18.028  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:18.028  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,03-17 09:50:18.038  2537  2537 D Recents_RecreateReceiver: onReceive by home
,03-17 09:50:18.038  1019  1043 W libprocessgroup: failed to open /acct/uid_10035/pid_4967/cgroup.procs: No such file or directory
,03-17 09:50:18.038  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:50:18.038  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:18.038  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,03-17 09:50:18.048  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:50:18.048  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:18.048  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-17 09:50:18.048  4725  4725 D Mms/UIEventReceiver: ui event
,03-17 09:50:18.048   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,03-17 09:50:18.058  5894  5894 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME,
03-17 09:50:18.058  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:50:18.058  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:18.058  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 09:50:18.058  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
03-17 09:50:18.058  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 09:50:18.058  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:50:18.058  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:50:18.058  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:50:18.058  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:50:18.058  1019  1217 D InputDispatcher: Focus entered window: 1482
,03-17 09:50:18.068  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 09:50:18.068  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 09:50:18.068  1482  1482 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 09:50:18.078  5993  5993 E Zygote  : MountEmulatedStorage()
03-17 09:50:18.078  5993  5993 I libpersona: KNOX_SDCARD checking this for 10135
03-17 09:50:18.078  5993  5993 E Zygote  : v2
03-17 09:50:18.078  5993  5993 I libpersona: KNOX_SDCARD not a persona
03-17 09:50:18.078  1019  1481 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 09:50:18.078  5993  5993 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:50:18.078  1019  5995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 09:50:18.078  5993  5993 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:50:18.078  1019  1480 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5993 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-17 09:50:18.078  1849  1849 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 09:50:18.078  5993  5993 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:50:18.088  1175  1175 I StatusBar: Icon Only
03-17 09:50:18.088  1175  1175 D PanelView: There is/are notification(s) 
,03-17 09:50:18.088  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:50:18.088  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:18.088  1019  1480 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1482, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
03-17 09:50:18.088  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-17 09:50:18.098  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:50:18.098  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:18.098  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,03-17 09:50:18.098  5933  5933 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 09:50:18.118  5993  5993 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:50:18.118  5993  5993 D ActivityThread: Added TimaKeyStore provider
03-17 09:50:18.118  1482  1482 D Launcher.HomeView: onStop
03-17 09:50:18.118  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{2be879d0 token=android.os.BinderProxy@2e8ac929 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 09:50:18.118  1482  1482 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e8ac929 time:82973
,03-17 09:50:18.138  5993  5993 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 09:50:18.138  5993  5993 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 09:50:18.138  5993  5993 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 09:50:18.138  5993  5993 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 09:50:18.138  5993  5993 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 09:50:18.138  1019  1049 W ActivityManager: mDVFSHelper.release()
03-17 09:50:18.138  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c811770 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:82995
,03-17 09:50:18.168  1019  1539 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
03-17 09:50:18.168  1019  1539 I ActivityManager: Killing 4417:com.google.android.music:main/u0a108 (adj 15): empty #31
,03-17 09:50:18.178  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:50:18.178  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:18.178  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-17 09:50:18.178  5894  5894 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-17 09:50:18.208  5987  5987 D AndroidRuntime: 
03-17 09:50:18.208  5987  5987 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 09:50:18.208  5987  5987 D AndroidRuntime: CheckJNI is OFF
,03-17 09:50:18.208  5987  5987 D AndroidRuntime: readGMSProperty: start
03-17 09:50:18.208  5987  5987 D AndroidRuntime: readGMSProperty: already setted!!
03-17 09:50:18.208  5987  5987 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,03-17 09:50:18.208  5987  5987 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 09:50:18.208  5987  5987 D AndroidRuntime: readGMSProperty: end
03-17 09:50:18.208  5987  5987 D AndroidRuntime: addProductProperty: start
,03-17 09:50:18.228  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 09:50:18.268  1019  1140 D PersonaManager: isKioskContainerExistOnDevice,
,03-17 09:50:18.278  1019  1043 W libprocessgroup: failed to open /acct/uid_10108/pid_4417/cgroup.procs: No such file or directory,
,03-17 09:50:18.418  5987  5987 E AffinityControl: AffinityControl: registerfunction enter
,03-17 09:50:18.448  5987  5987 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 09:50:18.448   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-17 09:50:18.458  1019  1351 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
03-17 09:50:18.458  1019  1351 D PackageManager: START PACKAGE DELETE: observer{127050053}
03-17 09:50:18.458  1019  1351 D PackageManager: pkg{<packageName>}
03-17 09:50:18.458  1019  1351 D PackageManager: user{0}
03-17 09:50:18.458  1019  1351 D PackageManager: caller{2000},
03-17 09:50:18.458  1019  1351 D PackageManager: flags{2}
,03-17 09:50:18.458  1019  1351 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 09:50:18.458  1019  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,03-17 09:50:18.458  1019  1351 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,03-17 09:50:18.458  1019  1057 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
03-17 09:50:18.458  1019  1351 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
03-17 09:50:18.458  1019  1351 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 09:50:18.458  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
03-17 09:50:18.458  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-17 09:50:18.458  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
03-17 09:50:18.458  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-17 09:50:18.458  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
03-17 09:50:18.458  1019  1044 I ActivityManager: Killing 5933:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,03-17 09:50:18.498  1019  1097 V AlarmManager: waitForAlarm result :4
,03-17 09:50:18.538  1019  1057 W PackageSettings: Skipping PackageSetting{2ab40b82 com.example.hello/10346} due to missing metadata
,03-17 09:50:18.578  1175  1175 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,03-17 09:50:18.588  1175  1175 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
03-17 09:50:18.588  1175  1175 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
,03-17 09:50:18.598  1019  1057 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-17 09:50:18.618  1019  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-17 09:50:18.658  4008  4008 I art     : Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 863us total 30.776ms
,03-17 09:50:18.658  1019  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 09:50:18.678  1797  2110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 09:50:18.688  1849  1849 E SamsungIME: mOCRHelper is null
,03-17 09:50:18.718  3661  3661 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 09:50:18 GMT+01:00 2016
,03-17 09:50:18.718  5258  5258 I art     : Explicit concurrent mark sweep GC freed 11523(827KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 917us total 108.791ms
,03-17 09:50:18.738  1019  1534 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:50:18.738  1019  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 09:50:18.738  1019  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 09:50:18.748  3661  3661 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 09:50:18.748  3661  3661 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 09:50:18.748  1019  1129 V NetworkStats: removeUidsLocked() for UIDs [10167]
,03-17 09:50:18.758  1019  1129 V NetworkStats: performPollLocked(flags=0x3)
,03-17 09:50:18.758  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 09:50:18.758  3661  3661 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 09:50:18.758  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 09:50:18.758  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 09:50:18.758  1019  1534 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
03-17 09:50:18.758  1019  1534 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
03-17 09:50:18.758  1019  1534 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
03-17 09:50:18.758  1019  1534 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,03-17 09:50:18.768  1019  1129 V NetworkStats: performPollLocked() took 12ms
03-17 09:50:18.768  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 09:50:18.768  1019  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:50:18.768  1019  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:50:18.768  1019  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:50:18.768  1019  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:50:18.778  1019  1539 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 09:50:18.778  1019  1539 D SecContentProvider2: mCursor = null
,03-17 09:50:18.778  3661  3661 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 09:50:18.778  6021  6021 E Zygote  : MountEmulatedStorage(),
03-17 09:50:18.778  6021  6021 E Zygote  : v2
03-17 09:50:18.778  6021  6021 I libpersona: KNOX_SDCARD checking this for 10090
,03-17 09:50:18.778  6021  6021 I libpersona: KNOX_SDCARD not a persona
03-17 09:50:18.788  6021  6021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 09:50:18.788  6021  6021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:50:18.788  1019  1534 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6021 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-17 09:50:18.788  6021  6021 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:50:18.788  3661  6020 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 09:50:18.808  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 09:50:18.808  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 09:50:18.808  3661  6020 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,03-17 09:50:18.818  3661  6020 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,03-17 09:50:18.818  3661  6020 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,03-17 09:50:18.838  6021  6021 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:50:18.838  6021  6021 D ActivityThread: Added TimaKeyStore provider
,03-17 09:50:18.838  1441  1441 D RegisteredServicesCache: empty dynamic service
,03-17 09:50:18.848  1019  1019 I art     : Explicit concurrent mark sweep GC freed 50671(3MB) AllocSpace objects, 21(340KB) LOS objects, 33% free, 24MB/36MB, paused 7.268ms total 230.101ms
,03-17 09:50:18.858  1019  1057 I art     : WaitForGcToComplete blocked for 117.920ms for cause Explicit
,03-17 09:50:18.858  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
03-17 09:50:18.858  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-17 09:50:18.858  1019  1043 W TextServicesManagerService: no available spell checker services found
,03-17 09:50:18.888  6021  6021 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 09:50:18.898  6021  6021 D elm:15121: ELMEngine.ELMEngine( context ).
,03-17 09:50:18.898  6021  6021 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-17 09:50:18.898  1019  1140 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:50:18.898  1019  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:18.898  1019  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 09:50:18.898  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:18.898  6021  6021 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 09:50:18.898  3661  6020 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,03-17 09:50:18.908  6021  6021 D elm:15121: ElmAgentService : onCreate()
,03-17 09:50:18.908  6021  6036 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 09:50:18.908  6021  6036 D elm:15121: MainReceiver.listeningToPackageRemoved()
03-17 09:50:18.908  6021  6036 D elm:15121: MDMBridge.getInstance()
03-17 09:50:18.908  6021  6036 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-17 09:50:18.908  3661  6020 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,03-17 09:50:18.918  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:18.918  1019  1019 D RCPManagerService: PackageReceiver onReceive()
03-17 09:50:18.918  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:18.918  6021  6036 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 09:50:18.918  3661  6020 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,03-17 09:50:18.918  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 09:50:18.918  3661  3661 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 09:50:18.918  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-17 09:50:18.928  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:18.948  6021  6021 D elm:15121: ElmAgentService : onDestroy().
,03-17 09:50:19.038  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 09:50:19.038  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:19.038  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:19.038  1019  1057 I art     : Explicit concurrent mark sweep GC freed 13121(628KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 2.919ms total 188.206ms
,03-17 09:50:19.048  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:19.058  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 09:50:19.058  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 09:50:19.058  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 09:50:19.058  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:19.088  1019  1057 D PackageManager: delete codoeFile: 
,03-17 09:50:19.088  1019  1057 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-17 09:50:19.088  1019  1057 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-17 09:50:19.088  1019  1057 D PackageManager: result of delete: 1{127050053}
,03-17 09:50:19.098  5987  5987 D AndroidRuntime: Shutting down VM
,03-17 09:50:19.108  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:19.108  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:19.108  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-17 09:50:19.108  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-17 09:50:19.108  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,03-17 09:50:19.108  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:50:19.108  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 09:50:19.108  1019  1019 V EnterpriseBillingPolicy: uID is 10167
,03-17 09:50:19.108  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 09:50:19.118  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 09:50:19.118  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:50:19.118  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 09:50:19.118  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 09:50:19.118  1019  1051 I PowerManagerService: [PWL] Off : 5s ago
03-17 09:50:19.118  1019  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,03-17 09:50:19.118  1019  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-17 09:50:19.118  1019  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=2041, ws=null) (elapsedTime=46872)
,03-17 09:50:19.118  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:50:19.118  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 09:50:19.118  1019  2738 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-17 09:50:19.118  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 09:50:19.128  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 09:50:19.118  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 09:50:19.128  1019  1162 D TaskPersister: removeObsoleteFile: deleting file=22_task.xml
,03-17 09:50:19.128  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 09:50:19.128  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-17 09:50:19.138  5636  5636 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 09:50:19.138  5636  5636 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 09:50:19.138  5636  5636 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,03-17 09:50:19.138  5636  5636 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,03-17 09:50:19.148  5737  5737 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-17 09:50:19.148  5737  5737 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,03-17 09:50:19.158  1019  1140 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:50:19.158  1019  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:19.158  1019  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,03-17 09:50:19.168  4983  4983 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,03-17 09:50:19.218  4725  4725 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,03-17 09:50:19.228  1019  1481 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:50:19.228  1019  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:19.228  1019  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-17 09:50:19.228  1019  1351 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:50:19.228  1019  1351 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:19.228  1019  1351 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,03-17 09:50:19.238  4725  6039 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,03-17 09:50:19.238  4725  6039 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
03-17 09:50:19.238  1019  3630 I TactileAssist: enable value -1
03-17 09:50:19.238  1019  3630 I TactileAssist: internal enable value -1
,03-17 09:50:19.238  1019  3630 I TactileAssist: intensity value -1
03-17 09:50:19.238  1019  3630 I TactileAssist: saveAppList value true
,03-17 09:50:19.238  1019  3630 I TactileAssist: List of disabled apps :
,03-17 09:50:19.258  5700  5700 D Compatibility: onReceive() it will make start service
,03-17 09:50:19.258  1019  2990 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:50:19.258  1019  2990 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:19.258  1019  2990 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,03-17 09:50:19.268  1019  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:50:19.268  1019  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:50:19.268  1019  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:50:19.268  1019  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:50:19.268  5700  6040 D Compatibility: onHandleIntent()
,03-17 09:50:19.278  5700  6040 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,03-17 09:50:19.278  6041  6041 E Zygote  : MountEmulatedStorage(),
03-17 09:50:19.278  6041  6041 I libpersona: KNOX_SDCARD checking this for 10055
,03-17 09:50:19.278  6041  6041 E Zygote  : v2
03-17 09:50:19.278  6041  6041 I libpersona: KNOX_SDCARD not a persona
03-17 09:50:19.278  6041  6041 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:50:19.278  1019  1538 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6041 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
03-17 09:50:19.278  6041  6041 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:50:19.288  5700  6040 D Compatibility: found: 2
03-17 09:50:19.288  5700  6040 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity,
03-17 09:50:19.288  6041  6041 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:50:19.288  5700  6040 D Compatibility: skipping ResolveInfo{387e2896 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-17 09:50:19.288  5700  6040 D Compatibility: considering ResolveInfo{38192c17 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
03-17 09:50:19.288  5700  6040 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
03-17 09:50:19.288  5700  6040 D Compatibility: enabling receiver ResolveInfo{3ef0f804 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000},
,03-17 09:50:19.288  5700  6040 D Compatibility: enabling receiver ResolveInfo{f4301ed com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-17 09:50:19.298  5700  6040 D Compatibility: enabling receiver ResolveInfo{146c3822 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-17 09:50:19.298  5700  6040 D Compatibility: enabling receiver ResolveInfo{377a72b3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000},
,03-17 09:50:19.308  5987  5987 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 09:50:19.308  5700  6040 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,03-17 09:50:19.318  1019  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 09:50:19.318  1019  1057 D PackageManager: userId{-1}
03-17 09:50:19.318  1019  1057 D PackageManager: andCode{true}
,03-17 09:50:19.318  6041  6041 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:50:19.318  6041  6041 D ActivityThread: Added TimaKeyStore provider
,03-17 09:50:19.358  6041  6041 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 09:50:19.408  6041  6041 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 09:50:19.408  6041  6041 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 09:50:19.408  6041  6041 D UserAnalysis: Create SecureDbHelper
,03-17 09:50:19.408  6041  6041 D IntelligenceServiceApplication: onCreate()
,03-17 09:50:19.408  6041  6041 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,03-17 09:50:19.418  6041  6041 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30),
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
,03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method),
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:50:19.418  6041  6041 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: Couldn't open privacy for writing (will try read-only):,
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:50:19.418  6041  6041 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:50:19.418  6041  6041 W SQLiteOpenHelper: Opened privacy in read-only mode
03-17 09:50:19.418  6041  6041 D IntelligenceServiceApplication: no applications having user consent for prediction
03-17 09:50:19.428  6041  6041 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-17 09:50:19.428  5092  5092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,03-17 09:50:19.428  1019  1536 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:50:19.428  1019  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:50:19.428  1019  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 09:50:19.428  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:50:19.428  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:50:19.428  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:50:19.428  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:50:19.438  6041  6041 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 09:50:19.438  6041  6041 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:50:19.438  6041  6041 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: ,	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:50:19.438  6041  6041 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:50:19.438  6041  6041 D AndroidRuntime: Shutting down VM
03-17 09:50:19.448  6060  6060 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 09:50:19.438  6041  6041 E AndroidRuntime: FATAL EXCEPTION: main
03-17 09:50:19.438  6041  6041 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 6041
03-17 09:50:19.438  6041  6041 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699),
03-17 09:50:19.438  6041  6041 E AndroidRuntime: ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
,03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:50:19.438  6041  6041 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:50:19.448  6060  6060 I libpersona: KNOX_SDCARD not a persona
03-17 09:50:19.448  5092  6059 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
03-17 09:50:19.448  6060  6060 E Zygote  : MountEmulatedStorage()
,03-17 09:50:19.448  6060  6060 E Zygote  : v2
03-17 09:50:19.448  6060  6060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:50:19.448  1019  1032 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6060 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 09:50:19.448  6060  6060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:50:19.448  1019  1534 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
03-17 09:50:19.448  6060  6060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:50:19.458  6041  6041 I Process : Sending signal. PID: 6041 SIG: 9
,03-17 09:50:19.468  5092  6059 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:50:19.468  5092  6059 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 09:50:19.468  5092  6059 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:50:19.468  5092  6059 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDataba,se.java:699)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:50:19.468  5092  6059 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-17 09:50:19.468  5092  6059 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:50:19.468  5092  6059 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: Can't write: system_app_crash
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop171.tmp: open failed: EROFS (Read-only file system)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 09:50:19.468  1019  6066 E DropBoxManagerService: 	... 5 more
03-17 09:50:19.478  6060  6060 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:50:19.478  1019  1350 I ActivityManager: Killing 4156:com.sec.spp.push/u0a32 (adj 15): empty #31
03-17 09:50:19.478  6060  6060 D ActivityThread: Added TimaKeyStore provider

```
