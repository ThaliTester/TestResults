#### Test 7578926821ef376_thali09_samsung-SM-A300FU Logs


```
--------- beginning of system,
07-07 20:27:26.559  1016  3465 D SSRM:n  : SIOP:: AP = 330
--------- beginning of main
07-07 20:27:26.829  6631  6631 D AndroidRuntime: 
07-07 20:27:26.829  6631  6631 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-07 20:27:26.829  6631  6631 D AndroidRuntime: CheckJNI is OFF
07-07 20:27:26.829  6631  6631 D AndroidRuntime: readGMSProperty: start
07-07 20:27:26.829  6631  6631 D AndroidRuntime: readGMSProperty: already setted!!
07-07 20:27:26.829  6631  6631 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-07 20:27:26.829  6631  6631 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-07 20:27:26.829  6631  6631 D AndroidRuntime: readGMSProperty: end
07-07 20:27:26.829  6631  6631 D AndroidRuntime: addProductProperty: start
07-07 20:27:26.959  6631  6631 E AffinityControl: AffinityControl: registerfunction enter
07-07 20:27:26.989  6631  6631 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-07 20:27:26.999  1016  1028 E PersonaManagerService: inState():  stateMachine is null !!
07-07 20:27:26.999  1016  1028 I PersonaManagerService: PersonaId don't exist
07-07 20:27:26.999  1016  1028 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-07 20:27:26.999  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 20:27:27.019  1016  1028 W ActivityManager: mDVFSHelper.acquire()
07-07 20:27:27.019  1016  1028 D FocusedStackFrame: Set to : 0
07-07 20:27:27.029  1016  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-07 20:27:27.029  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:27.029  1016  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-07 20:27:27.029  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:27.029  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:27.029  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:27.039  6642  6642 E Zygote  : MountEmulatedStorage()
07-07 20:27:27.039  6642  6642 E Zygote  : v2
07-07 20:27:27.039  6642  6642 I libpersona: KNOX_SDCARD checking this for 10170
07-07 20:27:27.039  6642  6642 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:27.049  1016  1028 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6642 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-07 20:27:27.049  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-07 20:27:27.049  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 20:27:27.049  1016  1028 D InputDispatcher: Focused application set to: xxxx
07-07 20:27:27.049  1016  1028 D InputDispatcher: Focus left window: 1496
07-07 20:27:27.049  6631  6631 D AndroidRuntime: Shutting down VM
07-07 20:27:27.049  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-07 20:27:27.049  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-07 20:27:27.049  6642  6642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 20:27:27.049  6642  6642 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:27.049  6642  6642 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-07 20:27:27.049   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-07 20:27:27.069  6642  6642 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:27.069  6642  6642 D ActivityThread: Added TimaKeyStore provider
07-07 20:27:27.079  1016  1511 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-07 20:27:27.079  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 20:27:27.079  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 20:27:27.079  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 20:27:27.089  1016  1511 D PersonaManager: isKioskContainerExistOnDevice
07-07 20:27:27.099  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-07 20:27:27.129   257   418 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
07-07 20:27:27.129   257  1038 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
07-07 20:27:27.139  1496  1496 D Launcher: onTrimMemory. Level: 20
07-07 20:27:27.139  1496  1496 V ActivityThread: updateVisibility : ActivityRecord{2402c476 token=android.os.BinderProxy@1a6e96a9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-07 20:27:27.209  6642  6642 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-07 20:27:27.219  6642  6642 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3131-3133)
07-07 20:27:27.219  6642  6642 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:27:27.259  6642  6642 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {75d12ec}
07-07 20:27:27.259  6642  6642 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:27:27.259  6642  6642 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-07 20:27:27.259  6631  6631 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-07 20:27:27.289  1016  1042 W ProcessCpuTracker: Skipping unknown process pid 6631
,07-07 20:27:27.299  6642  6642 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-07 20:27:27.299  6642  6642 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:27:27.299  6642  6642 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-07 20:27:27.319  6642  6642 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-07 20:27:27.319  6642  6642 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-07 20:27:27.319  6642  6642 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-07 20:27:27.329  6642  6642 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-07 20:27:27.329  6642  6642 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-07 20:27:27.329  6642  6642 I Adreno-EGL: Build Date: 04/06/15 Mon
07-07 20:27:27.329  6642  6642 I Adreno-EGL: Local Branch: 
07-07 20:27:27.329  6642  6642 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-07 20:27:27.329  6642  6642 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-07 20:27:27.329  6642  6642 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-07 20:27:27.519  6642  6668 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-07 20:27:27.569  6642  6642 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:27:27.579  6642  6642 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-07 20:27:27.589  6642  6642 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-07 20:27:27.589  6642  6642 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-07 20:27:27.599  1016  1042 W ActivityManager: Activity pause timeout for ActivityRecord{cbc973f u0 com.test.thalitest/.MainActivity t44}
,07-07 20:27:27.599  6642  6642 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-07 20:27:27.609  6642  6642 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:27:27.609  6642  6642 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:27:27.679  6642  6681 D OpenGLRenderer: Render dirty regions requested: true
,07-07 20:27:27.689  1016  1215 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-07 20:27:27.689  1016  1215 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-07 20:27:27.689  1016  1215 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-07 20:27:27.689  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-07 20:27:27.689  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,07-07 20:27:27.699  6642  6642 V ActivityThread: updateVisibility : ActivityRecord{12a4c287 token=android.os.BinderProxy@140710a1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-07 20:27:27.699  6642  6642 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,07-07 20:27:27.699  6642  6642 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-07 20:27:27.709   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-07 20:27:27.719  1016  1495 D InputDispatcher: Focus entered window: 6642
,07-07 20:27:27.729  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
07-07 20:27:27.729  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 20:27:27.729  6642  6642 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-07 20:27:27.729  6642  6681 I OpenGLRenderer: Initialized EGL, version 1.4,
07-07 20:27:27.729  6642  6681 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-07 20:27:27.729  6642  6681 D OpenGLRenderer: Enabling debug mode 0
,07-07 20:27:27.749  1016  1511 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-07 20:27:27.759  1173  1173 I StatusBar: Icon Only
,07-07 20:27:27.759  1173  1173 D PanelView: There is/are notification(s) 
,07-07 20:27:27.759  1016  6683 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-07 20:27:27.779  1016  1047 I ActivityManager: Displayed Component not be shown by security: +681ms (total +19s999ms)
,07-07 20:27:27.779  1016  1047 W ActivityManager: mDVFSHelper.release()
07-07 20:27:27.779  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{cbc973f u0 com.test.thalitest/.MainActivity t44} time:133693
,07-07 20:27:27.779   257   416 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,07-07 20:27:27.779  1893  1893 I SamsungIME: getCurrentCandidateView
,07-07 20:27:27.779   257   418 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,07-07 20:27:27.789  6642  6642 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection,
07-07 20:27:27.789  6642  6642 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@140710a1 time:133702
,07-07 20:27:27.879  6642  6642 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6642
,07-07 20:27:27.889  1893  1893 D SamsungIME: Dismiss ExpandCandiate
,07-07 20:27:27.889   289   289 E SMD     : DCD OFF
,07-07 20:27:27.999  6642  6642 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-07 20:27:28.109  1893  1893 I SamsungIME: getDebugLevel  : 0x4f4c
,07-07 20:27:28.139  1893  1893 I SamsungIME: getDebugLevel  : 0x4f4c
,07-07 20:27:28.159  1893  1893 I SamsungIME: KeybaordView init() : load resources
,07-07 20:27:28.179  6642  6686 D jxcore_app_log: JniHelper::setJavaVM(0xb8b002f0), pthread_self() = -1190806216
,07-07 20:27:28.179  1893  1893 I SamsungIME: getCurrentKeyboard
07-07 20:27:28.179  1893  1893 I SamsungIME: getTextKeyboard
,07-07 20:27:28.189  6642  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-07 20:27:28.189  6642  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-07 20:27:28.189  6642  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-07 20:27:28.189  6642  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-07 20:27:28.189  6642  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-07 20:27:28.189  6642  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9dd5b77 added. We now have 1 listener(s)
,07-07 20:27:28.199  6642  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,07-07 20:27:28.199  6642  6686 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,07-07 20:27:28.199  6642  6686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:27:28.199  6642  6686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:27:28.199  1893  1893 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cc3702 added. We now have 1 listener(s)
07-07 20:27:28.209  6642  6686 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:27:28.209  6642  6686 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-07 20:27:28.209  6642  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:27:28.209  6642  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-07 20:27:28.209  6642  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-07 20:27:28.209  6642  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-07 20:27:28.219  6642  6686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:27:28.219  6642  6686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,07-07 20:27:28.229  6642  6686 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:28.229  6642  6686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:28.229  6642  6686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:28.229  6642  6686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:28.229  6642  6686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:28.229  6642  6686 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:27:28.229  6642  6686 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:27:28.229  6642  6686 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:27:28.229  6642  6686 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-07 20:27:28.229  6642  6686 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-07 20:27:28.229  6642  6642 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:28.229  6642  6642 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:28.239  6642  6686 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-07 20:27:28.269  6642  6642 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-07 20:27:28.789  6642  6691 W jxcore-log: Initializing JXcore engine
07-07 20:27:28.789  6642  6691 W jxcore-log: JXcore engine is ready
07-07 20:27:28.849  2047  2047 E audit   : type=1400 msg=audit(1467916048.849:205): avc:  denied  { ioctl } for  pid=6691 comm="Thread-1193" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-07 20:27:28.849  2047  2047 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:28.849  2047  2047 E audit   : type=1300 msg=audit(1467916048.849:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9eb008f8 items=0 ppid=322 ppcomm=main pid=6691 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1193" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-07 20:27:28.849  2047  2047 E audit   : type=1320 msg=audit(1467916048.849:205): 
07-07 20:27:28.859  6642  6691 W jxcore-log: Starting JXcore engine
07-07 20:27:28.959  6642  6691 W jxcore-log: Platform android
07-07 20:27:28.959  6642  6691 W jxcore-log: 
07-07 20:27:28.959  6642  6691 W jxcore-log: Process ARCH arm
07-07 20:27:28.959  6642  6691 W jxcore-log: 
07-07 20:27:29.159  6642  6691 I jxcore-log: JXcore Cordova bridge is ready!
07-07 20:27:29.159  6642  6691 I jxcore-log: 
07-07 20:27:29.159  6642  6691 W jxcore-log: JXcore engine is started
07-07 20:27:29.169  6642  6686 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-07 20:27:29.169  6642  6642 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-07 20:27:29.179  6642  6691 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-07 20:27:29.179  6642  6691 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
07-07 20:27:29.189  6642  6642 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-07 20:27:29.189  6642  6642 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
07-07 20:27:29.189  1016  1493 D FocusedStackFrame: Set to : 0
07-07 20:27:29.189  1016  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 20:27:29.189  1016  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-07 20:27:29.189  1016  1493 D InputDispatcher: Focused application set to: xxxx
07-07 20:27:29.189  1016  1493 D InputDispatcher: Focus left window: 6642
07-07 20:27:29.199  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 20:27:29.199  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 20:27:29.199  1016  1493 I ActivityManager: Killing 6243:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
07-07 20:27:29.209  6642  6642 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-07 20:27:29.209  6642  6642 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-07 20:27:29.209  6642  6642 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:27:29.209  6642  6642 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:29.209  6642  6642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:29.209  6642  6642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:27:29.209  6642  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9dd5b77 removed from the list
07-07 20:27:29.209  6642  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:29.209  6642  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cc3702 removed from the list
07-07 20:27:29.209  6642  6642 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:29.209  6642  6642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-07 20:27:29.209  6642  6642 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-07 20:27:29.219   257   418 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
07-07 20:27:29.229   257   416 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
07-07 20:27:29.229  1016  1479 W ActivityManager: mDVFSHelper.acquire()
07-07 20:27:29.229  1016  1479 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-07 20:27:29.259  1496  1496 D Launcher: onRestart, Launcher: 427717080
07-07 20:27:29.259  1496  1496 D Launcher: onStart, Launcher: 427717080
07-07 20:27:29.259  1496  1496 D Launcher.HomeView: onStart
07-07 20:27:29.259  1496  1496 D Launcher: onResume, Launcher: 427717080
07-07 20:27:29.259  1016  1391 D SettingsProvider: name = kids_home_mode
07-07 20:27:29.259  1016  1391 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-07 20:27:29.259  1016  1391 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-07 20:27:29.259  1016  1391 D SettingsProvider: selectionArgs: false
07-07 20:27:29.259  1016  1391 D SettingsProvider: selectionArgs: 10006
07-07 20:27:29.259  1016  1391 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-07 20:27:29.259  1016  1391 D SettingsProvider: ret = -1
07-07 20:27:29.259  1496  1496 D Launcher.HomeView: onResume
07-07 20:27:29.269  1496  1496 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-07 20:27:29.269  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:29.269  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.269  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
07-07 20:27:29.269  1496  1496 D MenuAppsGridFragment: onResume
07-07 20:27:29.269  1496  1496 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
07-07 20:27:29.279  1496  1496 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
07-07 20:27:29.279  1016  1479 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
07-07 20:27:29.279  1016  1479 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
07-07 20:27:29.279  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:29.279  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.279  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
07-07 20:27:29.279  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
07-07 20:27:29.279  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.279  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.279  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.279  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.299  6694  6694 E Zygote  : MountEmulatedStorage()
07-07 20:27:29.299  6694  6694 I libpersona: KNOX_SDCARD checking this for 10039
07-07 20:27:29.299  6694  6694 E Zygote  : v2
07-07 20:27:29.299  6694  6694 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:29.299  1016  1479 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6694 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
07-07 20:27:29.299  6694  6694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 20:27:29.299  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
07-07 20:27:29.299  1016  1028 D ActivityManager: handle home activity for 0
07-07 20:27:29.299  1016  1028 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-07 20:27:29.299  1016  1028 D KnoxTimeoutHandler: post home show event for user 0
07-07 20:27:29.299  1016  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-07 20:27:29.299  1016  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-07 20:27:29.299  1016  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-07 20:27:29.299  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-07 20:27:29.299  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-07 20:27:29.299  1496  1496 D Launcher.HomeView: onPause
07-07 20:27:29.299  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-07 20:27:29.299  6694  6694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:29.299  1496  1496 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-07 20:27:29.299  6694  6694 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:29.309  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:29.309  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.309  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-07 20:27:29.309  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:29.309  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-07 20:27:29.309  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.309  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
07-07 20:27:29.309  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.309  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.309  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.309  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.329  6708  6708 E Zygote  : MountEmulatedStorage()
07-07 20:27:29.329  6708  6708 E Zygote  : v2
07-07 20:27:29.329  6708  6708 I libpersona: KNOX_SDCARD checking this for 10089
07-07 20:27:29.329  6708  6708 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:29.329  6708  6708 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 20:27:29.329  1016  1042 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6708 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
07-07 20:27:29.329  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:29.329  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.329  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-07 20:27:29.329  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-07 20:27:29.329  6708  6708 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:29.329  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.329  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.329  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.329  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.329  6708  6708 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
07-07 20:27:29.339  6694  6694 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:29.339  6694  6694 D ActivityThread: Added TimaKeyStore provider
07-07 20:27:29.349  6723  6723 E Zygote  : MountEmulatedStorage()
07-07 20:27:29.349  6723  6723 E Zygote  : v2
07-07 20:27:29.349  6723  6723 I libpersona: KNOX_SDCARD checking this for 10139
07-07 20:27:29.349  6723  6723 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:29.349  6723  6723 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 20:27:29.349  1016  1042 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6723 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
07-07 20:27:29.359  6723  6723 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:29.359  6708  6708 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:29.359  6708  6708 D ActivityThread: Added TimaKeyStore provider
07-07 20:27:29.359  6723  6723 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:29.379  1016  1078 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:29.379  1016  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.379  1016  1078 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1496, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-07 20:27:29.379  1016  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-07 20:27:29.389   257   257 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
07-07 20:27:29.389  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:29.389  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.389  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
07-07 20:27:29.389  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 20:27:29.389  6694  6694 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-07 20:27:29.389  6694  6694 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-07 20:27:29.389  6694  6694 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-07 20:27:29.389  6694  6694 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-07 20:27:29.389  6694  6694 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-07 20:27:29.389  6694  6694 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-07 20:27:29.389  6694  6694 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-07 20:27:29.389  2626  2626 D Recents_RecreateReceiver: onReceive by home
07-07 20:27:29.389  6708  6708 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-07 20:27:29.389  6708  6708 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
07-07 20:27:29.389  1016  1535 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:29.389  1016  1535 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-07 20:27:29.389  1016  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.389  1016  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
07-07 20:27:29.399  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.399  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.399  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.399  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.399  6723  6723 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:29.399  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 20:27:29.399  6723  6723 D ActivityThread: Added TimaKeyStore provider
07-07 20:27:29.399  1016  1078 D InputDispatcher: Focus entered window: 1496
07-07 20:27:29.399  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 20:27:29.399  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 20:27:29.399  1496  1496 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-07 20:27:29.419  1496  1496 V ActivityThread: updateVisibility : ActivityRecord{2402c476 token=android.os.BinderProxy@1a6e96a9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-07 20:27:29.419  1496  1496 D Launcher.HomeView: onStop
07-07 20:27:29.419  1016  1215 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-07 20:27:29.419  6740  6740 E Zygote  : MountEmulatedStorage()
07-07 20:27:29.419  6740  6740 I libpersona: KNOX_SDCARD checking this for 10084
07-07 20:27:29.419  6740  6740 E Zygote  : v2
07-07 20:27:29.419  6740  6740 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:29.419  6740  6740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 20:27:29.419  1016  1535 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6740 uid=10084 gids={50084, 9997} abi=armeabi-v7a
07-07 20:27:29.429  6740  6740 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:29.429  6740  6740 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
07-07 20:27:29.429  6642  6642 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-07 20:27:29.429  1016  6745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-07 20:27:29.429  1893  1893 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-07 20:27:29.429  1173  1173 I StatusBar: Icon Only
07-07 20:27:29.429  1173  1173 D PanelView: There is/are notification(s) 
,07-07 20:27:29.459  1496  1496 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1a6e96a9 time:135373
,07-07 20:27:29.469  6740  6740 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 20:27:29.469  6740  6740 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:29.479  6723  6723 V TaskCloserActivity: TaskCloserActivity enter()
,07-07 20:27:29.479  1016  4445 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:29.479  1016  4445 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.479  1016  4445 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
07-07 20:27:29.479  1016  4445 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-07 20:27:29.479  1016  4445 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.479  1016  4445 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.479  1016  4445 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.479  1016  4445 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:29.479  6723  6723 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
07-07 20:27:29.489  6740  6740 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-07 20:27:29.499  6761  6761 E Zygote  : MountEmulatedStorage()
07-07 20:27:29.499  6761  6761 E Zygote  : v2
07-07 20:27:29.499  6761  6761 I libpersona: KNOX_SDCARD checking this for 10135
07-07 20:27:29.499  6761  6761 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:29.499  6761  6761 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 20:27:29.499  6761  6761 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:29.499  1016  4445 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6761 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,07-07 20:27:29.499  6761  6761 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:29.499  1016  4445 I ActivityManager: Killing 6258:com.sec.spp.push/u0a32 (adj 15): empty #21
,07-07 20:27:29.509  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1458e5e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t42} time:135423
07-07 20:27:29.509  1016  1047 W ActivityManager: mDVFSHelper.release()
,07-07 20:27:29.519  1016  4445 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:29.519  1016  4445 I ActivityManager: Killing 6276:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
07-07 20:27:29.519  1016  4445 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.519  1016  4445 I ActivityManager: Killing 6316:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
07-07 20:27:29.519  1016  4445 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-07 20:27:29.529  1016  1078 D PersonaManager: isKioskContainerExistOnDevice
,07-07 20:27:29.549  6761  6761 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:29.549  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
07-07 20:27:29.549  6761  6761 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:29.559  6761  6761 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,07-07 20:27:29.559  6761  6761 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-07 20:27:29.559  6761  6761 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,07-07 20:27:29.559  6761  6761 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-07 20:27:29.569  6761  6761 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-07 20:27:29.599  6694  6694 D NearbySource: Nearby Source Create!
,07-07 20:27:29.599  6694  6694 D NearbyContext: Nearby Context Create!
,07-07 20:27:29.599  1016  1493 I ActivityManager: Killing 6296:com.osp.app.signin/u0a36 (adj 15): empty #21
,07-07 20:27:29.629   256   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-07 20:27:29.629   256   533 W Vold    : Returning OperationFailed - no handler for errno 0
,07-07 20:27:29.629  6694  6694 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,07-07 20:27:29.639  6694  6694 D SLinkSource: Samsung link source created,
,07-07 20:27:29.669  6694  6778 D ContactProvider: getAllContactInfoList Start
,07-07 20:27:29.679  1016  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-07 20:27:29.689  1016  1495 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-07 20:27:29.689  6694  6694 D GalleryCacheReady: Receive : home resume
,07-07 20:27:29.689  1016  1966 W ActivityManager: userId = 0, bbcId = -10000
,07-07 20:27:29.689  1016  1966 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.689  1016  1966 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-07 20:27:29.689  6160  6160 D Mms/UIEventReceiver: ui event
,07-07 20:27:29.699  1016  1966 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,07-07 20:27:29.699  1016  1966 W ActivityManager: userId = 0, bbcId = -10000
,07-07 20:27:29.699  1016  1966 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:29.699  1016  1966 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-07 20:27:29.709  6723  6723 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE,
07-07 20:27:29.709  1016  1495 I ActivityManager: Killing 6354:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,07-07 20:27:29.719  6694  6778 D ContactProvider: getAllContactInfoList End
,07-07 20:27:29.719  6694  6778 I syncContacts: thread: 1178, sync time = 50
,07-07 20:27:29.719  6759  6759 D AndroidRuntime: 
07-07 20:27:29.719  6759  6759 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-07 20:27:29.719  6759  6759 D AndroidRuntime: CheckJNI is OFF
07-07 20:27:29.719  6759  6759 D AndroidRuntime: readGMSProperty: start
07-07 20:27:29.719  6759  6759 D AndroidRuntime: readGMSProperty: already setted!!
07-07 20:27:29.719  6759  6759 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-07 20:27:29.719  6759  6759 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,07-07 20:27:29.719  6759  6759 D AndroidRuntime: readGMSProperty: end
07-07 20:27:29.719  6759  6759 D AndroidRuntime: addProductProperty: start
,07-07 20:27:29.849  6759  6759 E AffinityControl: AffinityControl: registerfunction enter
,07-07 20:27:29.879  6759  6759 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-07 20:27:29.889  1016  1495 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,07-07 20:27:29.889  1016  1495 D PackageManager: START PACKAGE DELETE: observer{836538717}
07-07 20:27:29.889  1016  1495 D PackageManager: pkg{<packageName>}
07-07 20:27:29.889  1016  1495 D PackageManager: user{0}
07-07 20:27:29.889  1016  1495 D PackageManager: caller{2000}
07-07 20:27:29.889  1016  1495 D PackageManager: flags{2}
07-07 20:27:29.889  1016  1495 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-07 20:27:29.889  1016  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-07 20:27:29.889  1016  1495 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,07-07 20:27:29.889  1016  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
07-07 20:27:29.889  1016  1495 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-07 20:27:29.889  1016  1495 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-07 20:27:29.889  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
07-07 20:27:29.889  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-07 20:27:29.889  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
07-07 20:27:29.889  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true,
,07-07 20:27:29.899  1016  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,07-07 20:27:29.899  1016  1042 I ActivityManager: Killing 6642:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-07 20:27:29.969  1016  1057 W PackageSettings: Skipping PackageSetting{17d15f com.example.hello/10168} due to missing metadata
,07-07 20:27:29.999  1016  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,07-07 20:27:30.019  1016  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-07 20:27:30.049  2773  2773 I art     : Explicit concurrent mark sweep GC freed 24249(1313KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 991us total 38.087ms
,07-07 20:27:30.059  6432  6432 I art     : Explicit concurrent mark sweep GC freed 632(36KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 990us total 43.400ms
,07-07 20:27:30.079  1016  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-07 20:27:30.109  1893  1893 E SamsungIME: mOCRHelper is null
,07-07 20:27:30.109  2065  2208 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-07 20:27:30.119  4735  4735 I art     : Explicit concurrent mark sweep GC freed 19666(1245KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 12MB/16MB, paused 1.501ms total 103.602ms
,07-07 20:27:30.129  2710  2710 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jul 07 20:27:30 GMT+02:00 2016
,07-07 20:27:30.129  1016  1493 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-07 20:27:30.129  1016  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-07 20:27:30.129  1016  1493 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:30.129  1016  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-07 20:27:30.129  1016  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-07 20:27:30.139  2710  2710 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-07 20:27:30.139  1457  1457 D PersonaManager: isKioskContainerExistOnDevice
,07-07 20:27:30.159  1016  1479 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
07-07 20:27:30.159  1016  1479 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-07 20:27:30.159  1457  1457 D RegisteredServicesCache: empty dynamic service
,07-07 20:27:30.159  1016  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
,07-07 20:27:30.159  1016  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-07 20:27:30.159  1016  1041 W TextServicesManagerService: no available spell checker services found
,07-07 20:27:30.169  2710  2710 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-07 20:27:30.169  1016  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
07-07 20:27:30.169  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
07-07 20:27:30.169  1016  1124 V NetworkStats: performPollLocked(flags=0x3)
,07-07 20:27:30.169  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
07-07 20:27:30.169  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-07 20:27:30.169  2710  2710 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-07 20:27:30.179  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:30.179  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-07 20:27:30.179  2710  2710 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-07 20:27:30.179  1016  1124 V NetworkStats: performPollLocked() took 16ms
07-07 20:27:30.179  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,07-07 20:27:30.199  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 20:27:30.199  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.199  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.199  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.199  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.209  6789  6789 E Zygote  : MountEmulatedStorage()
07-07 20:27:30.209  6789  6789 I libpersona: KNOX_SDCARD checking this for 10090
07-07 20:27:30.209  6789  6789 E Zygote  : v2
07-07 20:27:30.209  6789  6789 I libpersona: KNOX_SDCARD not a persona
,07-07 20:27:30.209  6789  6789 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 20:27:30.209  2710  6787 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-07 20:27:30.219  1016  1479 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6789 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,07-07 20:27:30.219  6789  6789 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 20:27:30.219  6789  6789 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 20:27:30.219  2710  6787 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-07 20:27:30.229  6160  6160 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,07-07 20:27:30.229  2710  6787 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,07-07 20:27:30.229  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,07-07 20:27:30.239  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.239  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.239  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.239  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.239  2710  6787 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-07 20:27:30.239  1016  1016 I art     : Explicit concurrent mark sweep GC freed 42727(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 24MB/36MB, paused 5.122ms total 222.718ms
,07-07 20:27:30.239  1016  1057 I art     : WaitForGcToComplete blocked for 95.858ms for cause Explicit
07-07 20:27:30.249  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:30.249  6801  6801 E Zygote  : MountEmulatedStorage()
07-07 20:27:30.249  6801  6801 E Zygote  : v2
07-07 20:27:30.249  6801  6801 I libpersona: KNOX_SDCARD checking this for 1000
07-07 20:27:30.249  6801  6801 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:30.249  6801  6801 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 20:27:30.249  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 20:27:30.249  6801  6801 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 20:27:30.259  6801  6801 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 20:27:30.279  6801  6801 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 20:27:30.279  6801  6801 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:30.289  1016  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6801 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-07 20:27:30.289  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,07-07 20:27:30.299  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.299  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.299  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.299  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.299  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,07-07 20:27:30.299  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,07-07 20:27:30.309  6789  6789 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-07 20:27:30.309  6789  6789 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:30.309  6819  6819 E Zygote  : MountEmulatedStorage(),
07-07 20:27:30.309  6819  6819 I libpersona: KNOX_SDCARD checking this for 1000
07-07 20:27:30.309  6819  6819 E Zygote  : v2
07-07 20:27:30.309  6819  6819 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:30.309  6819  6819 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 20:27:30.309  6819  6819 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:30.319  6819  6819 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:30.319  1016  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6819 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-07 20:27:30.339  1016  4007 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-07 20:27:30.339  1016  4007 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
07-07 20:27:30.339  1016  4007 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:30.339  1016  4007 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:30.339  1016  4007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
07-07 20:27:30.339  1016  1215 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-07 20:27:30.339  1016  1215 D SecContentProvider2: mCursor = null
,07-07 20:27:30.349  1016  4445 I TactileAssist: enable value -1
07-07 20:27:30.349  1016  4445 I TactileAssist: internal enable value -1
07-07 20:27:30.349  1016  4445 I TactileAssist: intensity value -1
07-07 20:27:30.349  1016  4445 I TactileAssist: saveAppList value true
,07-07 20:27:30.359  6160  6833 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
07-07 20:27:30.359  6160  6833 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,07-07 20:27:30.369  6819  6819 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 20:27:30.369  1016  4445 I TactileAssist: List of disabled apps :
,07-07 20:27:30.369  6819  6819 D ActivityThread: Added TimaKeyStore provider
07-07 20:27:30.369  2710  6787 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-07 20:27:30.389  2710  6787 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-07 20:27:30.389  2710  6787 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,07-07 20:27:30.399  1457  1457 D RegisteredComponentCache: Collect Tech packages for Knox
,07-07 20:27:30.409  1457  1457 D PersonaManager: isKioskContainerExistOnDevice
,07-07 20:27:30.409  1016  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-07 20:27:30.419  2710  2710 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,07-07 20:27:30.419  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:30.429  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:30.429  6789  6789 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-07 20:27:30.439  6789  6789 D elm:15121: ELMEngine.ELMEngine( context ).
,07-07 20:27:30.439  6789  6789 D elm:15121: MDMBridge.setEnterpriseBridge()
,07-07 20:27:30.439  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-07 20:27:30.439  1016  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-07 20:27:30.439  1016  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-07 20:27:30.439  1016  1479 D BatteryService: stay LED for fully charged
,07-07 20:27:30.439  6414  6414 D Compatibility: onReceive() it will make start service
,07-07 20:27:30.439  1016  1078 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-07 20:27:30.439  1016  1078 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
07-07 20:27:30.439  6801  6801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,07-07 20:27:30.449  1016  1078 W ActivityManager: userId = 0, bbcId = -10000
,07-07 20:27:30.449  1016  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:30.449  6819  6819 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
07-07 20:27:30.449  1016  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,07-07 20:27:30.449  1016  1535 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-07 20:27:30.449  1016  1535 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,07-07 20:27:30.449  1016  1535 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:30.449  1016  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:30.449  1016  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,07-07 20:27:30.459  6789  6789 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-07 20:27:30.459  1016  4007 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-07 20:27:30.459  1016  4007 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,07-07 20:27:30.459  1016  4007 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:30.459  1016  4007 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:30.459  1016  4007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,07-07 20:27:30.459  1016  1479 D SecContentProvider2: uri = -1 selection = getSealedState
,07-07 20:27:30.459  1016  1479 D SecContentProvider2: mCursor = null
07-07 20:27:30.459  6819  6819 I PopupuiReceiver_KNOX: getSealedState : true
,07-07 20:27:30.459  1016  1966 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
07-07 20:27:30.459  1016  1966 D SecContentProvider2: mCursor = null
,07-07 20:27:30.459  6819  6819 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,07-07 20:27:30.469  1016  1215 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
07-07 20:27:30.469  1016  1215 D SecContentProvider2: mCursor = null
07-07 20:27:30.469  2898  2898 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-07 20:27:30.469  6819  6819 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
07-07 20:27:30.469  1016  1016 D RCPManagerService: PackageReceiver onReceive()
07-07 20:27:30.469  6819  6819 D PopupuiReceiver: Action package removed
,07-07 20:27:30.469  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-07 20:27:30.469  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-07 20:27:30.469  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-07 20:27:30.469  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,07-07 20:27:30.469  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,07-07 20:27:30.479  6789  6789 D elm:15121: ElmAgentService : onCreate()
,07-07 20:27:30.479  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-07 20:27:30.479  2898  2898 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-07 20:27:30.479  2898  2898 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
,07-07 20:27:30.479  2898  2898 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-07 20:27:30.479  2898  2898 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-07 20:27:30.479  2898  2898 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
,07-07 20:27:30.479  2898  2898 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-07 20:27:30.479  2898  2898 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:30.479  2898  2898 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:30.479  2898  2898 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
,07-07 20:27:30.479  2898  2898 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:30.479  2898  2898 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:27:30.479  2898  2898 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,07-07 20:27:30.479  2898  2898 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-07 20:27:30.479  6789  6835 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,07-07 20:27:30.489  6789  6835 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-07 20:27:30.489  1016  1215 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
07-07 20:27:30.489  6789  6835 D elm:15121: MDMBridge.getInstance()
07-07 20:27:30.489  6789  6835 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-07 20:27:30.489  1016  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.489  1016  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.489  1016  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.489  1016  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.489  6789  6835 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-07 20:27:30.489  6414  6836 D Compatibility: onHandleIntent()
07-07 20:27:30.489  6414  6836 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10170, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,07-07 20:27:30.499  6414  6836 D Compatibility: found: 2
07-07 20:27:30.499  6414  6836 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-07 20:27:30.499  6414  6836 D Compatibility: skipping ResolveInfo{32f3d8bb com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-07 20:27:30.499  6414  6836 D Compatibility: considering ResolveInfo{197e71d8 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-07 20:27:30.499  6414  6836 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,07-07 20:27:30.499  6414  6836 D Compatibility: enabling receiver ResolveInfo{6967931 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-07 20:27:30.499  6839  6839 E Zygote  : MountEmulatedStorage()
,07-07 20:27:30.499  6839  6839 E Zygote  : v2
07-07 20:27:30.499  6839  6839 I libpersona: KNOX_SDCARD checking this for 1000
07-07 20:27:30.499  6839  6839 I libpersona: KNOX_SDCARD not a persona
,07-07 20:27:30.509  6839  6839 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 20:27:30.509  6839  6839 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 20:27:30.509  6839  6839 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:30.509  6414  6836 D Compatibility: enabling receiver ResolveInfo{13e4b816 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-07 20:27:30.529  1016  1215 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6839 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-07 20:27:30.529   322   322 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 22.543ms
,07-07 20:27:30.529  1016  1511 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:30.529  1016  1511 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-07 20:27:30.529  1016  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:30.529  1016  1511 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-07 20:27:30.529  1016  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-07 20:27:30.529  6414  6836 D Compatibility: enabling receiver ResolveInfo{1f7d4597 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-07 20:27:30.539  6789  6789 D elm:15121: ElmAgentService : onDestroy().
,07-07 20:27:30.539  6839  6839 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:30.539   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 16.781ms
07-07 20:27:30.539  6839  6839 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:30.549  6414  6836 D Compatibility: enabling receiver ResolveInfo{3d54d384 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
07-07 20:27:30.549  1016  1511 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,07-07 20:27:30.549  1016  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.549  1016  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.549  1016  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.549  1016  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.549  1016  1057 I art     : Explicit concurrent mark sweep GC freed 13985(849KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 4.307ms total 305.245ms
,07-07 20:27:30.559  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:30.559   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 16.768ms
07-07 20:27:30.569  6414  6836 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,07-07 20:27:30.569  6432  6854 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-07 20:27:30.569  1016  1057 D PackageManager: delete codoeFile: 
,07-07 20:27:30.579  1016  1511 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6857 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,07-07 20:27:30.579  6857  6857 E Zygote  : MountEmulatedStorage()
07-07 20:27:30.579  6857  6857 E Zygote  : v2
07-07 20:27:30.579  6857  6857 I libpersona: KNOX_SDCARD checking this for 10145
07-07 20:27:30.579  6857  6857 I libpersona: KNOX_SDCARD not a persona,
07-07 20:27:30.579  1016  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
07-07 20:27:30.579  6857  6857 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
07-07 20:27:30.579  1016  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
07-07 20:27:30.589  1016  1057 D PackageManager: result of delete: 1{836538717}
,07-07 20:27:30.589  6857  6857 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 20:27:30.589  6857  6857 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,07-07 20:27:30.599  6759  6759 D AndroidRuntime: Shutting down VM
,07-07 20:27:30.609  6857  6857 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:30.609  6857  6857 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:30.609  6839  6839 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-07 20:27:30.629  1016  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-07 20:27:30.629  1016  1057 D PackageManager: userId{-1}
07-07 20:27:30.629  1016  1057 D PackageManager: andCode{true}
,07-07 20:27:30.629  1016  1479 I ActivityManager: Killing 6372:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
07-07 20:27:30.629  1016  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-07 20:27:30.629  1016  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-07 20:27:30.629  1016  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-07 20:27:30.629  1016  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-07 20:27:30.639  6839  6839 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
07-07 20:27:30.639  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
07-07 20:27:30.639  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-07 20:27:30.639  1016  1028 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
07-07 20:27:30.639  1016  1028 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
07-07 20:27:30.639  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 20:27:30.639  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-07 20:27:30.649  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-07 20:27:30.649  1016  1016 V EnterpriseBillingPolicy: uID is 10170
07-07 20:27:30.649  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
07-07 20:27:30.649  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-07 20:27:30.649  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-07 20:27:30.649  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.649  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-07 20:27:30.649  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-07 20:27:30.649  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-07 20:27:30.649  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-07 20:27:30.649  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.649  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.649  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.659  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:30.659  6873  6873 E Zygote  : MountEmulatedStorage()
07-07 20:27:30.659  6873  6873 E Zygote  : v2
07-07 20:27:30.659  6873  6873 I libpersona: KNOX_SDCARD checking this for 10055
07-07 20:27:30.659  6873  6873 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:30.659  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 20:27:30.659  6873  6873 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 20:27:30.669  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
07-07 20:27:30.669  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-07 20:27:30.669  6873  6873 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 20:27:30.669  6873  6873 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:30.669  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 20:27:30.669  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 20:27:30.669  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-07 20:27:30.679  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
07-07 20:27:30.679  1016  1479 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6873 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
07-07 20:27:30.679  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
07-07 20:27:30.679  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:30.679  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-07 20:27:30.679  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-07 20:27:30.679  1016  1161 D TaskPersister: removeObsoleteFile: deleting file=44_task.xml
07-07 20:27:30.679  1016  1016 V EnterpriseBillingPolicy: uID is 10170
07-07 20:27:30.679  1016  3465 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-07 20:27:30.679  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
07-07 20:27:30.679  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-07 20:27:30.679  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-07 20:27:30.679  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-07 20:27:30.679  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-07 20:27:30.679  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-07 20:27:30.679  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-07 20:27:30.679  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-07 20:27:30.689  1016  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
07-07 20:27:30.689  1016  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-07 20:27:30.689  1016  1016 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,07-07 20:27:30.689  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-07 20:27:30.689  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-07 20:27:30.689  6873  6873 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:30.689  1429  1429 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-07 20:27:30.689  1429  1429 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-07 20:27:30.699  6873  6873 D ActivityThread: Added TimaKeyStore provider,
,07-07 20:27:30.709  3359  3359 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-07 20:27:30.709  3359  3453 D HeadsetStateMachine: Disconnected process message: 10
,07-07 20:27:30.719  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-07 20:27:30.719  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-07 20:27:30.719  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-07 20:27:30.729  6857  6857 D ThemeInfoUtil: getCurrentFestivalName is [null]
,07-07 20:27:30.729  6857  6857 D ThemeInfoUtil: isCurrentFestival = false
,07-07 20:27:30.729  6471  6471 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
,07-07 20:27:30.729  6471  6471 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,07-07 20:27:30.739  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,07-07 20:27:30.739  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.739  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.739  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.739  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.749  6888  6888 E Zygote  : MountEmulatedStorage()
07-07 20:27:30.749  6888  6888 E Zygote  : v2
07-07 20:27:30.749  6888  6888 I libpersona: KNOX_SDCARD checking this for 10148
07-07 20:27:30.749  6888  6888 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:30.749  6888  6888 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 20:27:30.749  6888  6888 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:30.749  6888  6888 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 20:27:30.759  1016  1479 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6888 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
07-07 20:27:30.759  1016  1479 I ActivityManager: Killing 6391:com.wsomacp/u0a23 (adj 15): empty #21
,07-07 20:27:30.759  1016  1493 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-07 20:27:30.759  1016  1493 W ActivityManager: userId = 0, bbcId = -10000
,07-07 20:27:30.759  1016  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:30.759  6873  6873 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
07-07 20:27:30.759  1016  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,07-07 20:27:30.769  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,07-07 20:27:30.769  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.769  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.769  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.769  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.779  6888  6888 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-07 20:27:30.779  6888  6888 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:30.789  6903  6903 E Zygote  : MountEmulatedStorage()
07-07 20:27:30.789  6903  6903 E Zygote  : v2
07-07 20:27:30.789  6903  6903 I libpersona: KNOX_SDCARD checking this for 1000
07-07 20:27:30.789  6903  6903 I libpersona: KNOX_SDCARD not a persona
,07-07 20:27:30.789  6903  6903 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 20:27:30.789  6903  6903 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 20:27:30.789  6903  6903 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:30.789  1016  1016 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6903 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-07 20:27:30.789  1016  1535 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:30.789  1016  1535 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
07-07 20:27:30.789  1016  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:30.789  1016  1535 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
07-07 20:27:30.789  1016  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
07-07 20:27:30.799  6873  6873 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,07-07 20:27:30.799  6873  6873 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-07 20:27:30.799  6873  6873 D UserAnalysis: Create SecureDbHelper,
07-07 20:27:30.799  1016  4007 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-07 20:27:30.799  1016  4007 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:30.799  1016  4007 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-07 20:27:30.799  1016  4007 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:30.799  1016  4007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-07 20:27:30.799  6471  6471 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,07-07 20:27:30.809  1016  1016 I MotionRecognitionService: Plugged
07-07 20:27:30.809  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,07-07 20:27:30.809  6471  6911 I FilterInstaller: FilterPackageService : ACTION_REMOVED
07-07 20:27:30.809  6759  6759 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-07 20:27:30.809  6471  6911 D FilterUnInstaller: before removeFromFS
,07-07 20:27:30.819  1016  1511 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider
,07-07 20:27:30.819  1016  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.819  1016  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.819  1016  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.819  1016  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.829  6903  6903 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 20:27:30.829  6903  6903 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:30.829  6919  6919 E Zygote  : MountEmulatedStorage()
07-07 20:27:30.839  6919  6919 E Zygote  : v2
07-07 20:27:30.839  6919  6919 I libpersona: KNOX_SDCARD checking this for 10095
07-07 20:27:30.839  6919  6919 I libpersona: KNOX_SDCARD not a persona
,07-07 20:27:30.839  6919  6919 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-07 20:27:30.839  6919  6919 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:30.839  1016  1511 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6919 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,07-07 20:27:30.839  6919  6919 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 20:27:30.849  1016  1493 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-07 20:27:30.849  1016  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-07 20:27:30.849  1016  1493 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:30.849  1016  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:30.849  1016  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-07 20:27:30.849  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-07 20:27:30.849  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:30.849  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:30.849  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-07 20:27:30.859  6888  6888 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,07-07 20:27:30.859  6873  6873 D IntelligenceServiceApplication: onCreate()
07-07 20:27:30.859  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
07-07 20:27:30.859  6873  6873 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
07-07 20:27:30.859  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.859  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.859  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.859  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.869  6919  6919 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-07 20:27:30.869  6919  6919 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:30.879  6873  6873 D IntelligenceServiceApplication: no applications having user consent for prediction
07-07 20:27:30.879  6903  6903 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
07-07 20:27:30.879  6935  6935 E Zygote  : MountEmulatedStorage()
07-07 20:27:30.879  6903  6903 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
07-07 20:27:30.879  6903  6903 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
07-07 20:27:30.879  6935  6935 E Zygote  : v2
07-07 20:27:30.879  6935  6935 I libpersona: KNOX_SDCARD checking this for 1000
07-07 20:27:30.879  6935  6935 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:30.889  6935  6935 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 20:27:30.889  6935  6935 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:30.889   289   289 E SMD     : DCD OFF
07-07 20:27:30.889  6935  6935 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:30.889  1016  1028 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6935 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-07 20:27:30.899  1016  1535 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-07 20:27:30.899  6873  6873 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,07-07 20:27:30.899  1016  4445 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
07-07 20:27:30.899  1016  4445 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0,
07-07 20:27:30.909  1016  4445 W ActivityManager: userId = 0, bbcId = -10000
,07-07 20:27:30.909  1016  4445 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:30.909  1016  4445 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,07-07 20:27:30.909  1016  1493 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-07 20:27:30.909  1016  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-07 20:27:30.909  1016  1493 W ActivityManager: userId = 0, bbcId = -10000
,07-07 20:27:30.909  6903  6903 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-07 20:27:30.909  1016  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:30.909  1016  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-07 20:27:30.909  6903  6903 I PCWCLIENTTRACE_PushUtil: sales region : global
07-07 20:27:30.919  6903  6903 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-07 20:27:30.919  6903  6903 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
07-07 20:27:30.919  6873  6873 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
07-07 20:27:30.919  6873  6873 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,07-07 20:27:30.919  1016  1966 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
07-07 20:27:30.919  1016  1966 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.919  1016  1966 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.919  1016  1966 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.919  1016  1966 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:30.929  6873  6873 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-07 20:27:30.929  6873  6873 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-07 20:27:30.929  6873  6873 D AndroidRuntime: Shutting down VM
07-07 20:27:30.929  6873  6873 E AndroidRuntime: FATAL EXCEPTION: main
07-07 20:27:30.929  6873  6873 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 6873
07-07 20:27:30.929  6873  6873 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.d,atabase.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-07 20:27:30.929  6873  6873 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-07 20:27:30.929  6919  6919 D PreloadFilterInstaller: uses FILTER_DB_VER_1
07-07 20:27:30.939  6935  6935 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:30.939  6935  6935 D ActivityThread: Added TimaKeyStore provider
07-07 20:27:30.939  6953  6953 E Zygote  : MountEmulatedStorage()
07-07 20:27:30.939  6953  6953 I libpersona: KNOX_SDCARD checking this for 1000
07-07 20:27:30.939  6953  6953 E Zygote  : v2
07-07 20:27:30.939  6953  6953 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:30.939  6432  6854 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-07 20:27:30.939  6432  6854 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-07 20:27:30.939  6953  6953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 20:27:30.949  6919  6919 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
07-07 20:27:30.949  1016  1966 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6953 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-07 20:27:30.949  6919  6919 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: Couldn't open filter.db for writing (will try read-only):
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-07 20:27:30.949  6919  6919 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-07 20:27:30.949  6953  6953 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:30.949  6953  6953 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:30.949  6919  6919 W SQLiteOpenHelper: Opened filter.db in read-only mode
07-07 20:27:30.959  6919  6919 E SQLiteLog: (284) automatic index on titles(filter_id)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: Exception thrown from onTableChanged
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.j(InternalIcingCorporaProvider.java:661)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.a(InternalIcingCorporaProvider.java:652)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.g(InternalIcingCorporaProvider.java:590)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:290)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.z.amO(UpdateIcingCorporaService.java:358)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.ab.amQ(UpdateIcingCorporaService.java:297)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.aF(UpdateIcingCorporaService.java:194)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.b.amO(AppDataSearchDbOpenHelperBase.java:246)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.b.call(AppDataSearchDbOpenHelperBase.java:227)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
07-07 20:27:30.959  6432  6854 E AppDataSearchHelper: 	... 16 more
07-07 20:27:30.959  6432  6854 W AppDataSearchHelper: Table change notification failed for com.google.android.gms.appdatasearch.a.k@be7fd6a1
07-07 20:27:30.959  1016  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-07 20:27:30.959  6432  6854 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 395 ms] updated apps [took 395 ms] 
07-07 20:27:30.969  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:30.969  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:30.969  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-07 20:27:30.969  1016  1966 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
07-07 20:27:30.969  1016  1966 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.969  1016  1966 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.969  1016  1966 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.969  1016  1966 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.969  6953  6953 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:30.969  6953  6953 D ActivityThread: Added TimaKeyStore provider
07-07 20:27:30.989  6968  6968 E Zygote  : MountEmulatedStorage()
07-07 20:27:30.989  6968  6968 I libpersona: KNOX_SDCARD checking this for 10152
07-07 20:27:30.989  6968  6968 E Zygote  : v2
07-07 20:27:30.989  6968  6968 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:30.989  6968  6968 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 20:27:30.989  1016  1966 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6968 uid=10152 gids={50152, 9997} abi=armeabi-v7a
07-07 20:27:30.989  1016  1966 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:30.989  6935  6935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
07-07 20:27:30.989  1016  1966 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:30.989  1016  1966 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
07-07 20:27:30.989  1016  1966 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
07-07 20:27:30.989  1016  1966 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
07-07 20:27:30.999  6968  6968 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 20:27:30.999  6968  6968 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:30.999  1016  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice

```
