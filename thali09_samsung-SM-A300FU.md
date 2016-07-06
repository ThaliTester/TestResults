#### Test 72145431eb52a3d_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main
07-06 12:18:12.167   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,--------- beginning of system
07-06 12:18:12.337  1016  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 12:18:12.457  1016  3522 D SSRM:n  : SIOP:: AP = 260
07-06 12:18:12.597  6757  6757 D AndroidRuntime: 
07-06 12:18:12.597  6757  6757 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-06 12:18:12.597  6757  6757 D AndroidRuntime: CheckJNI is OFF
07-06 12:18:12.597  6757  6757 D AndroidRuntime: readGMSProperty: start
07-06 12:18:12.597  6757  6757 D AndroidRuntime: readGMSProperty: already setted!!
07-06 12:18:12.597  6757  6757 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-06 12:18:12.597  6757  6757 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-06 12:18:12.597  6757  6757 D AndroidRuntime: readGMSProperty: end
07-06 12:18:12.597  6757  6757 D AndroidRuntime: addProductProperty: start
07-06 12:18:12.717  6757  6757 E AffinityControl: AffinityControl: registerfunction enter
07-06 12:18:12.747  6757  6757 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-06 12:18:12.757  1016  1535 E PersonaManagerService: inState():  stateMachine is null !!
07-06 12:18:12.757  1016  1535 I PersonaManagerService: PersonaId don't exist
07-06 12:18:12.757  1016  1535 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-06 12:18:12.757  1016  1535 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-06 12:18:12.777  1016  1535 W ActivityManager: mDVFSHelper.acquire()
07-06 12:18:12.777  1016  1535 D FocusedStackFrame: Set to : 0
07-06 12:18:12.777  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-06 12:18:12.777  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-06 12:18:12.787  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:12.787  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:12.787  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:12.787  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:12.797  6768  6768 E Zygote  : MountEmulatedStorage()
07-06 12:18:12.797  6768  6768 E Zygote  : v2
07-06 12:18:12.797  6768  6768 I libpersona: KNOX_SDCARD checking this for 10170
07-06 12:18:12.797  6768  6768 I libpersona: KNOX_SDCARD not a persona
07-06 12:18:12.797  6768  6768 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-06 12:18:12.797  1016  1535 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6768 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-06 12:18:12.797  1016  1535 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-06 12:18:12.797  1016  1535 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-06 12:18:12.797  1016  1535 D InputDispatcher: Focused application set to: xxxx
07-06 12:18:12.797  1016  1535 D InputDispatcher: Focus left window: 1480
07-06 12:18:12.797  6757  6757 D AndroidRuntime: Shutting down VM
07-06 12:18:12.797  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-06 12:18:12.797  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-06 12:18:12.797  6768  6768 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 12:18:12.797   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-06 12:18:12.807  6768  6768 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-06 12:18:12.817  6768  6768 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 12:18:12.817  6768  6768 D ActivityThread: Added TimaKeyStore provider
07-06 12:18:12.827  1016  1534 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-06 12:18:12.827  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-06 12:18:12.837  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-06 12:18:12.837  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 12:18:12.847  1016  1534 D PersonaManager: isKioskContainerExistOnDevice
07-06 12:18:12.857  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-06 12:18:12.877   257  1096 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
07-06 12:18:12.877   257   443 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
07-06 12:18:12.887  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{9d8a317 token=android.os.BinderProxy@dc9fe13 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-06 12:18:12.887  1480  1480 D Launcher: onTrimMemory. Level: 20
07-06 12:18:12.957  6768  6768 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-06 12:18:12.967  6768  6768 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7563-7565)
07-06 12:18:12.967  6768  6768 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 12:18:12.997  6768  6768 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22ae666a}
07-06 12:18:12.997  6768  6768 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 12:18:13.007  6768  6768 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-06 12:18:13.007  6757  6757 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-06 12:18:13.047  6768  6768 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-06 12:18:13.047  6768  6768 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 12:18:13.047  6768  6768 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-06 12:18:13.067  6768  6768 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-06 12:18:13.067  6768  6768 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-06 12:18:13.067  6768  6768 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-06 12:18:13.077  6768  6768 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-06 12:18:13.077  6768  6768 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-06 12:18:13.077  6768  6768 I Adreno-EGL: Build Date: 04/06/15 Mon
07-06 12:18:13.077  6768  6768 I Adreno-EGL: Local Branch: 
07-06 12:18:13.077  6768  6768 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-06 12:18:13.077  6768  6768 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-06 12:18:13.077  6768  6768 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-06 12:18:13.167   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 12:18:13.277  6768  6794 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-06 12:18:13.327  6768  6768 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 12:18:13.337  6768  6768 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-06 12:18:13.347  6768  6768 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-06 12:18:13.347  6768  6768 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-06 12:18:13.347  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{5399f66 u0 com.test.thalitest/.MainActivity t44}
,07-06 12:18:13.357  6768  6768 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-06 12:18:13.357  6768  6768 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 12:18:13.357  6768  6768 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 12:18:13.427  6768  6807 D OpenGLRenderer: Render dirty regions requested: true
,07-06 12:18:13.437  1016  3947 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-06 12:18:13.437  1016  3947 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-06 12:18:13.437  1016  3947 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-06 12:18:13.437  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-06 12:18:13.437  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,07-06 12:18:13.497  6768  6768 V ActivityThread: updateVisibility : ActivityRecord{322c077d token=android.os.BinderProxy@89bb327 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-06 12:18:13.507  6768  6768 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,07-06 12:18:13.507  6768  6768 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-06 12:18:13.507   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-06 12:18:13.517  1016  3944 D InputDispatcher: Focus entered window: 6768
,07-06 12:18:13.527  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-06 12:18:13.527  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-06 12:18:13.527  6768  6768 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-06 12:18:13.527  6768  6807 I OpenGLRenderer: Initialized EGL, version 1.4
,07-06 12:18:13.537  6768  6807 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,07-06 12:18:13.537  6768  6807 D OpenGLRenderer: Enabling debug mode 0
,07-06 12:18:13.557  1016  1135 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-06 12:18:13.557  1170  1170 I StatusBar: Icon Only
07-06 12:18:13.557  1170  1170 D PanelView: There is/are notification(s) 
07-06 12:18:13.557  1016  6810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-06 12:18:13.567  1016  1046 I ActivityManager: Displayed Component not be shown by security: +722ms (total +2m3s874ms)
07-06 12:18:13.567  1016  1046 W ActivityManager: mDVFSHelper.release()
07-06 12:18:13.567  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5399f66 u0 com.test.thalitest/.MainActivity t44} time:238169
07-06 12:18:13.577   257   438 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
07-06 12:18:13.577  6768  6768 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-06 12:18:13.577  6768  6768 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@89bb327 time:238175
07-06 12:18:13.577   257  6123 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
07-06 12:18:13.587  1863  1863 I SamsungIME: getCurrentCandidateView
07-06 12:18:13.637  6768  6768 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6768
07-06 12:18:13.687  1863  1863 D SamsungIME: Dismiss ExpandCandiate
07-06 12:18:13.837  1863  1863 I SamsungIME: getDebugLevel  : 0x4f4c
07-06 12:18:13.897  1863  1863 I SamsungIME: getDebugLevel  : 0x4f4c
07-06 12:18:13.907  1863  1863 I SamsungIME: KeybaordView init() : load resources
07-06 12:18:13.927  6768  6768 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-06 12:18:13.947  1863  1863 I SamsungIME: getCurrentKeyboard
07-06 12:18:13.947  1863  1863 I SamsungIME: getTextKeyboard
07-06 12:18:13.967  1863  1863 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
07-06 12:18:14.027  6768  6811 D jxcore_app_log: JniHelper::setJavaVM(0xb7a042f0), pthread_self() = -1208616656
07-06 12:18:14.027  6768  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-06 12:18:14.027  6768  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-06 12:18:14.027  6768  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-06 12:18:14.027  6768  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-06 12:18:14.027  6768  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-06 12:18:14.027  6768  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b2c9ed added. We now have 1 listener(s)
07-06 12:18:14.037  6768  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
07-06 12:18:14.037  6768  6811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
07-06 12:18:14.037  6768  6811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-06 12:18:14.037  6768  6811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@136ff870 added. We now have 1 listener(s)
07-06 12:18:14.047  6768  6811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-06 12:18:14.047  6768  6811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-06 12:18:14.057  6768  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-06 12:18:14.057  6768  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-06 12:18:14.057  6768  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-06 12:18:14.057  6768  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-06 12:18:14.057  6768  6811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-06 12:18:14.057  6768  6811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
07-06 12:18:14.067  6768  6811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-06 12:18:14.067  6768  6811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-06 12:18:14.067  6768  6811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-06 12:18:14.067  6768  6811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-06 12:18:14.067  6768  6811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-06 12:18:14.067  6768  6811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-06 12:18:14.067  6768  6811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-06 12:18:14.067  6768  6811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-06 12:18:14.067  6768  6811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-06 12:18:14.067  6768  6811 D io.jxcore.node.ConnectivityMonitor: start: OK
07-06 12:18:14.067  6768  6768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-06 12:18:14.067  6768  6768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-06 12:18:14.077  6768  6811 I io.jxcore.node.LifeCycleMonitor: start: OK
07-06 12:18:14.097  6768  6768 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-06 12:18:14.167   321   321 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
07-06 12:18:14.207   290   290 E SMD     : DCD OFF
,07-06 12:18:14.617  6768  6817 W jxcore-log: Initializing JXcore engine
07-06 12:18:14.617  6768  6817 W jxcore-log: JXcore engine is ready
,07-06 12:18:14.677  1997  1997 E audit   : type=1400 msg=audit(1467800294.667:205): avc:  denied  { ioctl } for  pid=6817 comm="Thread-1208" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-06 12:18:14.677  1997  1997 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-06 12:18:14.677  1997  1997 E audit   : type=1300 msg=audit(1467800294.667:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9f5048f8 items=0 ppid=306 ppcomm=main pid=6817 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1208" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-06 12:18:14.677  1997  1997 E audit   : type=1320 msg=audit(1467800294.667:205): 
,07-06 12:18:14.687  6768  6817 W jxcore-log: Starting JXcore engine
,07-06 12:18:14.787  6768  6817 W jxcore-log: Platform android
07-06 12:18:14.787  6768  6817 W jxcore-log: 
07-06 12:18:14.787  6768  6817 W jxcore-log: Process ARCH arm
07-06 12:18:14.787  6768  6817 W jxcore-log: 
,07-06 12:18:14.997  6768  6817 I jxcore-log: JXcore Cordova bridge is ready!
07-06 12:18:14.997  6768  6817 I jxcore-log: 
,07-06 12:18:14.997  6768  6817 W jxcore-log: JXcore engine is started
,07-06 12:18:14.997  6768  6811 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-06 12:18:14.997  6768  6768 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-06 12:18:15.007  6768  6817 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-06 12:18:15.007  6768  6817 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-06 12:18:15.017  6768  6768 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-06 12:18:15.017  6768  6768 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
07-06 12:18:15.017  1016  3949 D FocusedStackFrame: Set to : 0
07-06 12:18:15.017  1016  3949 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-06 12:18:15.017  1016  3949 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-06 12:18:15.017  1016  3949 D InputDispatcher: Focused application set to: xxxx
07-06 12:18:15.017  1016  3949 D InputDispatcher: Focus left window: 6768
07-06 12:18:15.027  1016  3949 I ActivityManager: Killing 6321:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,07-06 12:18:15.027  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-06 12:18:15.027  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 12:18:15.027  6768  6768 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-06 12:18:15.037  6768  6768 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-06 12:18:15.037  6768  6768 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-06 12:18:15.037  6768  6768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-06 12:18:15.037  6768  6768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-06 12:18:15.037  6768  6768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-06 12:18:15.037  6768  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b2c9ed removed from the list
07-06 12:18:15.037  6768  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-06 12:18:15.037  6768  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@136ff870 removed from the list
07-06 12:18:15.037  6768  6768 D io.jxcore.node.ConnectivityMonitor: stop
07-06 12:18:15.037  6768  6768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-06 12:18:15.037  6768  6768 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-06 12:18:15.047   257  6122 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
07-06 12:18:15.047   257   438 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,07-06 12:18:15.057  1016  1029 W ActivityManager: mDVFSHelper.acquire()
,07-06 12:18:15.067  1016  1029 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-06 12:18:15.087  1480  1480 D Launcher: onRestart, Launcher: 457473846
,07-06 12:18:15.087  1480  1480 D Launcher: onStart, Launcher: 457473846
,07-06 12:18:15.087  1480  1480 D Launcher.HomeView: onStart
,07-06 12:18:15.087  1480  1480 D Launcher: onResume, Launcher: 457473846
,07-06 12:18:15.087  1016  3947 D SettingsProvider: name = kids_home_mode
,07-06 12:18:15.087  1016  3947 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-06 12:18:15.087  1016  3947 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-06 12:18:15.087  1016  3947 D SettingsProvider: selectionArgs: false
07-06 12:18:15.087  1016  3947 D SettingsProvider: selectionArgs: 10006
,07-06 12:18:15.087  1016  3947 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-06 12:18:15.087  1016  3947 D SettingsProvider: ret = -1
,07-06 12:18:15.087  1480  1480 D Launcher.HomeView: onResume
,07-06 12:18:15.107  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-06 12:18:15.117  1480  1480 D MenuAppsGridFragment: onResume,
,07-06 12:18:15.117  1480  1480 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true,
,07-06 12:18:15.117  1480  1480 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-06 12:18:15.127  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,07-06 12:18:15.127  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 12:18:15.127  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-06 12:18:15.127  1016  1354 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,07-06 12:18:15.127  1016  1354 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-06 12:18:15.127  1016  1354 W ActivityManager: userId = 0, bbcId = -10000
,07-06 12:18:15.127  1016  1354 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-06 12:18:15.127  1016  1354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
07-06 12:18:15.127  1016  1354 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast,
,07-06 12:18:15.137  1016  1354 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-06 12:18:15.137  1016  1354 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.137  1016  1354 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.137  1016  1354 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-06 12:18:15.147  6821  6821 E Zygote  : MountEmulatedStorage()
07-06 12:18:15.147  6821  6821 E Zygote  : v2
07-06 12:18:15.147  6821  6821 I libpersona: KNOX_SDCARD checking this for 10039
07-06 12:18:15.147  6821  6821 I libpersona: KNOX_SDCARD not a persona
,07-06 12:18:15.147  1016  1354 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6821 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,07-06 12:18:15.157  1016  1535 D ActivityManager: handle home activity for 0
07-06 12:18:15.157  1016  1535 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0,
07-06 12:18:15.157  1016  1535 D KnoxTimeoutHandler: post home show event for user 0
07-06 12:18:15.157  1016  1535 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-06 12:18:15.157  1016  1535 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-06 12:18:15.157  1016  1535 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-06 12:18:15.157  6821  6821 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
07-06 12:18:15.157  6821  6821 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 12:18:15.157  6821  6821 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-06 12:18:15.157  1480  1480 D Launcher.HomeView: onPause
07-06 12:18:15.157  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
07-06 12:18:15.157  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-06 12:18:15.157  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-06 12:18:15.157  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-06 12:18:15.157  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-06 12:18:15.157  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,07-06 12:18:15.157  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 12:18:15.157  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-06 12:18:15.167  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
07-06 12:18:15.167  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 12:18:15.167  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-06 12:18:15.167  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,07-06 12:18:15.167  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.167  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.167  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-06 12:18:15.167  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-06 12:18:15.187  6834  6834 E Zygote  : MountEmulatedStorage()
,07-06 12:18:15.187  6834  6834 E Zygote  : v2
07-06 12:18:15.187  6834  6834 I libpersona: KNOX_SDCARD checking this for 10089
07-06 12:18:15.187  6834  6834 I libpersona: KNOX_SDCARD not a persona
,07-06 12:18:15.187  6834  6834 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-06 12:18:15.187  1016  1041 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6834 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a,
,07-06 12:18:15.187  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
07-06 12:18:15.187  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 12:18:15.187  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-06 12:18:15.187  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-06 12:18:15.187  6834  6834 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-06 12:18:15.187  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.197  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.197  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.197  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-06 12:18:15.197  6834  6834 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-06 12:18:15.197  6821  6821 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-06 12:18:15.197  6821  6821 D ActivityThread: Added TimaKeyStore provider
,07-06 12:18:15.207  6847  6847 E Zygote  : MountEmulatedStorage()
,07-06 12:18:15.207  6847  6847 E Zygote  : v2
,07-06 12:18:15.207  6847  6847 I libpersona: KNOX_SDCARD checking this for 10139
07-06 12:18:15.207  6847  6847 I libpersona: KNOX_SDCARD not a persona
,07-06 12:18:15.207  6847  6847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-06 12:18:15.217  1016  1041 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6847 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,07-06 12:18:15.217  6847  6847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-06 12:18:15.217  6847  6847 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-06 12:18:15.227  6834  6834 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 12:18:15.227  6834  6834 D ActivityThread: Added TimaKeyStore provider
,07-06 12:18:15.237   257   257 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,07-06 12:18:15.237  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-06 12:18:15.237  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,07-06 12:18:15.247  1016  1536 D InputDispatcher: Focus entered window: 1480
,07-06 12:18:15.247  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-06 12:18:15.247  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101,
07-06 12:18:15.247  1480  1480 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-06 12:18:15.257  6834  6834 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-06 12:18:15.257  6834  6834 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
07-06 12:18:15.257  6847  6847 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-06 12:18:15.257  6847  6847 D ActivityThread: Added TimaKeyStore provider
,07-06 12:18:15.257  1016  1534 W ActivityManager: userId = 0, bbcId = -10000,
07-06 12:18:15.257  1016  1534 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1480, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-06 12:18:15.257  1016  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 12:18:15.257  6821  6821 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-06 12:18:15.257  1016  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-06 12:18:15.257  6821  6821 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-06 12:18:15.257  6821  6821 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-06 12:18:15.257  6821  6821 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-06 12:18:15.267  1480  1480 D Launcher.HomeView: onStop
07-06 12:18:15.257  6821  6821 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-06 12:18:15.257  6821  6821 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-06 12:18:15.257  6821  6821 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-06 12:18:15.267  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{9d8a317 token=android.os.BinderProxy@dc9fe13 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true,
07-06 12:18:15.267  1016  1476 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-06 12:18:15.267  1016  6868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 12:18:15.267  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
07-06 12:18:15.267  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 12:18:15.267  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-06 12:18:15.267  2622  2622 D Recents_RecreateReceiver: onReceive by home
,07-06 12:18:15.277  6768  6768 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-06 12:18:15.277  1016  3944 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-06 12:18:15.277  1016  3944 W ActivityManager: userId = 0, bbcId = -10000
07-06 12:18:15.277  1016  3944 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 12:18:15.277  1016  3944 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,07-06 12:18:15.277  1016  3944 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.277  1016  3944 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.277  1016  3944 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.277  1016  3944 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.277  1863  1863 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-06 12:18:15.287  1170  1170 I StatusBar: Icon Only,
07-06 12:18:15.287  6870  6870 I libpersona: KNOX_SDCARD checking this for 10084
07-06 12:18:15.287  1170  1170 D PanelView: There is/are notification(s) 
,07-06 12:18:15.287  6870  6870 I libpersona: KNOX_SDCARD not a persona
07-06 12:18:15.287  6870  6870 E Zygote  : MountEmulatedStorage()
07-06 12:18:15.287  6870  6870 E Zygote  : v2
07-06 12:18:15.287  6870  6870 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-06 12:18:15.297  1016  3944 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6870 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,07-06 12:18:15.297  6870  6870 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 12:18:15.297  6870  6870 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-06 12:18:15.307  1480  1480 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@dc9fe13 time:239906
,07-06 12:18:15.327  6870  6870 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 12:18:15.327  6819  6819 D AndroidRuntime: 
07-06 12:18:15.327  6819  6819 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-06 12:18:15.327  6870  6870 D ActivityThread: Added TimaKeyStore provider
,07-06 12:18:15.327  6819  6819 D AndroidRuntime: CheckJNI is OFF
,07-06 12:18:15.327  6819  6819 D AndroidRuntime: readGMSProperty: start
07-06 12:18:15.327  6819  6819 D AndroidRuntime: readGMSProperty: already setted!!
07-06 12:18:15.327  6819  6819 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-06 12:18:15.327  6819  6819 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-06 12:18:15.327  6819  6819 D AndroidRuntime: readGMSProperty: end
07-06 12:18:15.327  6819  6819 D AndroidRuntime: addProductProperty: start
,07-06 12:18:15.337  1016  1046 W ActivityManager: mDVFSHelper.release()
07-06 12:18:15.337  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2e76d0a9 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t42} time:239932
,07-06 12:18:15.347  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-06 12:18:15.347  6847  6847 V TaskCloserActivity: TaskCloserActivity enter()
,07-06 12:18:15.357  6870  6870 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-06 12:18:15.367  6847  6847 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-06 12:18:15.377  1016  1535 W ActivityManager: userId = 0, bbcId = -10000
,07-06 12:18:15.377  1016  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-06 12:18:15.377  1016  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
07-06 12:18:15.377  1016  1535 I ActivityManager: Killing 6338:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,07-06 12:18:15.377  1016  1535 I ActivityManager: Killing 6355:com.osp.app.signin/u0a36 (adj 15): empty #21
,07-06 12:18:15.387  1016  1476 W ActivityManager: userId = 0, bbcId = -10000
07-06 12:18:15.387  1016  1476 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-06 12:18:15.387  1016  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 12:18:15.387  1016  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,07-06 12:18:15.387  1016  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.387  1016  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.387  1016  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.387  1016  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-06 12:18:15.407  6895  6895 E Zygote  : MountEmulatedStorage()
07-06 12:18:15.407  6895  6895 I libpersona: KNOX_SDCARD checking this for 10135
07-06 12:18:15.407  6895  6895 E Zygote  : v2
07-06 12:18:15.407  6895  6895 I libpersona: KNOX_SDCARD not a persona
,07-06 12:18:15.407  6895  6895 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-06 12:18:15.407  6895  6895 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-06 12:18:15.407  6895  6895 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-06 12:18:15.407  1016  1476 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6895 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
07-06 12:18:15.407  1016  1476 I ActivityManager: Killing 6380:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,07-06 12:18:15.417  1016  3947 D PersonaManager: isKioskContainerExistOnDevice
,07-06 12:18:15.437  6895  6895 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-06 12:18:15.437  6895  6895 D ActivityThread: Added TimaKeyStore provider
,07-06 12:18:15.457  6895  6895 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-06 12:18:15.457  6895  6895 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-06 12:18:15.457  6895  6895 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-06 12:18:15.457  6895  6895 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-06 12:18:15.457  6895  6895 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-06 12:18:15.467  6819  6819 E AffinityControl: AffinityControl: registerfunction enter
,07-06 12:18:15.487  1016  1535 I ActivityManager: Killing 6218:com.android.mms/u0a41 (adj 15): empty #21
,07-06 12:18:15.497  6819  6819 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-06 12:18:15.517  1016  1470 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
07-06 12:18:15.517  1016  1470 D PackageManager: START PACKAGE DELETE: observer{949307876},
07-06 12:18:15.517  1016  1470 D PackageManager: pkg{<packageName>}
07-06 12:18:15.517  1016  1470 D PackageManager: user{0}
07-06 12:18:15.517  1016  1470 D PackageManager: caller{2000}
07-06 12:18:15.517  1016  1470 D PackageManager: flags{2}
,07-06 12:18:15.517  6821  6821 D NearbySource: Nearby Source Create!
07-06 12:18:15.517  1016  1470 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-06 12:18:15.517  1016  1470 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
07-06 12:18:15.517  1016  1470 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-06 12:18:15.517  1016  1470 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,07-06 12:18:15.517  6821  6821 D NearbyContext: Nearby Context Create!
,07-06 12:18:15.527  1016  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,07-06 12:18:15.527  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,07-06 12:18:15.527  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-06 12:18:15.527  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
07-06 12:18:15.527  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-06 12:18:15.527  1016  1056 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
07-06 12:18:15.527  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,07-06 12:18:15.537  1016  1041 I ActivityManager: Killing 6768:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-06 12:18:15.567   256   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-06 12:18:15.567   256   532 W Vold    : Returning OperationFailed - no handler for errno 0
,07-06 12:18:15.567  6821  6821 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,07-06 12:18:15.567  6821  6821 D SLinkSource: Samsung link source created
,07-06 12:18:15.587  1016  3947 D CountryDetector: No listener is left,
,07-06 12:18:15.637  1016  1056 W PackageSettings: Skipping PackageSetting{2bc39a91 com.example.hello/10168} due to missing metadata
,07-06 12:18:15.677  1016  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-06 12:18:15.697  1016  1536 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-06 12:18:15.697  1016  1056 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,07-06 12:18:15.697  6821  6821 D GalleryCacheReady: Receive : home resume
,07-06 12:18:15.717  1016  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-06 12:18:15.757  6489  6489 I art     : Explicit concurrent mark sweep GC freed 610(35KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 861us total 46.737ms
,07-06 12:18:15.767  2782  2782 I art     : Explicit concurrent mark sweep GC freed 24242(1313KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.148ms total 45.638ms
,07-06 12:18:15.777  1016  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-06 12:18:15.777  1863  1863 E SamsungIME: mOCRHelper is null
,07-06 12:18:15.787  2024  2206 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-06 12:18:15.797  6821  6912 D ContactProvider: getAllContactInfoList Start
,07-06 12:18:15.797  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,07-06 12:18:15.797  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 12:18:15.797  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
07-06 12:18:15.797  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,07-06 12:18:15.797  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.797  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.797  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.797  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:15.797  1452  1452 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-06 12:18:15.807  6913  6913 E Zygote  : MountEmulatedStorage()
07-06 12:18:15.807  6913  6913 E Zygote  : v2
07-06 12:18:15.807  6913  6913 I libpersona: KNOX_SDCARD checking this for 10041
07-06 12:18:15.807  6913  6913 I libpersona: KNOX_SDCARD not a persona
,07-06 12:18:15.817  6913  6913 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-06 12:18:15.827  6913  6913 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 12:18:15.827  1016  1029 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=6913 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
07-06 12:18:15.827  6913  6913 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-06 12:18:15.837  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,07-06 12:18:15.847   306   306 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 802us total 32.893ms
,07-06 12:18:15.867  6913  6913 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-06 12:18:15.867  6913  6913 D ActivityThread: Added TimaKeyStore provider
,07-06 12:18:15.877  4766  4766 I art     : Explicit concurrent mark sweep GC freed 21019(1299KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 12MB/16MB, paused 1.263ms total 166.793ms
,07-06 12:18:15.877   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 815us total 21.932ms
,07-06 12:18:15.877  1016  1122 V NetworkStats: removeUidsLocked() for UIDs [10170]
07-06 12:18:15.877  1016  1122 V NetworkStats: performPollLocked(flags=0x3)
07-06 12:18:15.877  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,07-06 12:18:15.877  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
07-06 12:18:15.877  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,07-06 12:18:15.887  1016  1122 V NetworkStats: performPollLocked() took 6ms,
07-06 12:18:15.887  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,07-06 12:18:15.897  1438  1438 D RegisteredServicesCache: empty dynamic service
,07-06 12:18:15.897   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 21.825ms
,07-06 12:18:15.927  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,07-06 12:18:15.927  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
07-06 12:18:15.927  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-06 12:18:15.937  1016  1040 W TextServicesManagerService: no available spell checker services found
,07-06 12:18:15.937  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,07-06 12:18:15.947  6913  6913 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-06 12:18:15.947  6913  6913 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-06 12:18:15.947  6913  6913 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-06 12:18:15.947  6913  6913 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-06 12:18:15.947  6913  6913 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
07-06 12:18:15.947  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-06 12:18:15.947  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-06 12:18:15.977  1016  1479 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-06 12:18:15.977  1016  1479 D SecContentProvider2: mCursor = null
,07-06 12:18:15.977  1016  1016 I art     : Explicit concurrent mark sweep GC freed 57898(4MB) AllocSpace objects, 53(848KB) LOS objects, 33% free, 24MB/36MB, paused 4.068ms total 261.793ms
,07-06 12:18:15.977  1016  1056 I art     : WaitForGcToComplete blocked for 132.838ms for cause Explicit
,07-06 12:18:15.977  6821  6912 D ContactProvider: getAllContactInfoList End
,07-06 12:18:15.987  6821  6912 I syncContacts: thread: 1193, sync time = 374
,07-06 12:18:16.007  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.007  6913  6913 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,07-06 12:18:16.027  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.057  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.057  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,07-06 12:18:16.057  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-06 12:18:16.067  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.067  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-06 12:18:16.067  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-06 12:18:16.067  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,07-06 12:18:16.087  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,07-06 12:18:16.087  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-06 12:18:16.157  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-06 12:18:16.157  1016  1056 I art     : Explicit concurrent mark sweep GC freed 13596(732KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.853ms total 178.618ms
,07-06 12:18:16.157  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.167  6913  6913 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 117.139ms
,07-06 12:18:16.177  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.197  1016  1056 D PackageManager: delete codoeFile: 
,07-06 12:18:16.197  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.197  1016  1056 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
07-06 12:18:16.197  1016  1056 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,07-06 12:18:16.197  1016  1056 D PackageManager: result of delete: 1{949307876}
,07-06 12:18:16.197  6819  6819 D AndroidRuntime: Shutting down VM
,07-06 12:18:16.207  1016  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-06 12:18:16.207  1016  1056 D PackageManager: userId{-1}
07-06 12:18:16.207  1016  1056 D PackageManager: andCode{true}
,07-06 12:18:16.207  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-06 12:18:16.217  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-06 12:18:16.217  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-06 12:18:16.217  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-06 12:18:16.217  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.237  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.247  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.247  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-06 12:18:16.247  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-06 12:18:16.247  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.247  6913  6913 D Mms/TelephonyPermission: start operation mode monitor
,07-06 12:18:16.257  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-06 12:18:16.257  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-06 12:18:16.257  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-06 12:18:16.257  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-06 12:18:16.257  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-06 12:18:16.257  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-06 12:18:16.257  6913  6930 D Mms/ArtClassLoader: init before art
,07-06 12:18:16.257  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-06 12:18:16.257  1016  1016 V EnterpriseBillingPolicy: uID is 10170
07-06 12:18:16.257  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
07-06 12:18:16.257  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-06 12:18:16.257  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-06 12:18:16.257  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-06 12:18:16.257  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-06 12:18:16.257  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-06 12:18:16.257  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-06 12:18:16.257  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-06 12:18:16.257  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
07-06 12:18:16.257  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-06 12:18:16.257  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-06 12:18:16.267  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=44_task.xml
07-06 12:18:16.267  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-06 12:18:16.267  1016  1016 V EnterpriseBillingPolicy: uID is 10170
07-06 12:18:16.267  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
07-06 12:18:16.267  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-06 12:18:16.267  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-06 12:18:16.267  1016  3522 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-06 12:18:16.267  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-06 12:18:16.267  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-06 12:18:16.267  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-06 12:18:16.267  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-06 12:18:16.267  1016  1016 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
07-06 12:18:16.267  6913  6913 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-06 12:18:16.267  6913  6913 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
07-06 12:18:16.267  6913  6913 D Mms/TelephonyPermission: isDefault true
,07-06 12:18:16.267  6913  6913 D Mms/MmsApp: onCreate() com.android.mms
,07-06 12:18:16.307  6913  6913 D Mms/MmsApp: [start]    initCountryIso consume time = 304.532135
,07-06 12:18:16.317  1016  1536 D CountryDetector: The first listener is added
,07-06 12:18:16.317  6913  6913 D Mms/MmsApp: [end]    initCountryIso consume time = 5.809115
07-06 12:18:16.317  6913  6913 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.109271
,07-06 12:18:16.327  6913  6913 D Mms/MmsConfig: before partial update
,07-06 12:18:16.337  6913  6913 D Mms/MmsConfig: Load Resize quality : 80
,07-06 12:18:16.337  6913  6913 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,07-06 12:18:16.347  6913  6913 D EasySignUpManager_1.0.1: isAuth is false
,07-06 12:18:16.347  6913  6913 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,07-06 12:18:16.347  1452  1473 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6913
,07-06 12:18:16.347  1452  1473 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.224 ms
,07-06 12:18:16.357  6913  6913 D EasySignUpManager_1.0.1: isAuth is false
,07-06 12:18:16.357  6913  6913 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,07-06 12:18:16.357  6913  6913 E CscParser: mps_code.dat does not exist
,07-06 12:18:16.357  6913  6913 E CscParser: customer_path =/system/csc/customer.xml
07-06 12:18:16.357  6913  6913 E CscParser: fileName + /system/csc/customer.xml
,07-06 12:18:16.367  6913  6913 E CscParser: mps_code.dat does not exist
,07-06 12:18:16.367  6913  6913 E CscParser: customer_path =/system/csc/customer.xml
07-06 12:18:16.367  6913  6913 E CscParser: fileName + /system/csc/customer.xml
,07-06 12:18:16.377  6913  6913 D CscParser: getInstance fileName =/system/csc/customer.xml
,07-06 12:18:16.377  6913  6913 D Mms/MmsConfig:  enable multiwindow = false
,07-06 12:18:16.387  6913  6913 E Mms/MessageUtils: setCountryDetector : update country detector info 
,07-06 12:18:16.387  6913  6913 E Mms/MessageUtils: updateCountryIso : update country iso info 
,07-06 12:18:16.387  6913  6913 D Mms/MmsConfig: [end]    init() consume time = 74.383958
,07-06 12:18:16.397  6913  6913 D Mms/Contact: [start]    init() consume time = 1.272292
,07-06 12:18:16.397  1452  1469 D TP/MmsSmsProvider: query,matched:13, calling pid = 6913
,07-06 12:18:16.397  1452  1469 D TP/MmsSmsProvider: match 13:Elapsed time : 1.026 ms
,07-06 12:18:16.407  6913  6913 D Mms/Contact: [end]    init consume time = 13.147031
,07-06 12:18:16.407  6819  6819 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,07-06 12:18:16.427  6913  6937 D Mms/DraftCache: [start]    rebuildCache consume time = 16.056146
,07-06 12:18:16.427  6913  6913 D Mms/MethodReflector: getSubId is called
07-06 12:18:16.427  6913  6913 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,07-06 12:18:16.427  1452  1473 D TP/MmsSmsProvider: query,matched:12, calling pid = 6913
,07-06 12:18:16.427  1452  1473 D TP/MmsSmsProvider: match 12:Elapsed time : 0.918 ms
,07-06 12:18:16.427  6913  6913 D Mms/MethodReflector: getTelephonyProperty is called
07-06 12:18:16.427  6913  6913 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-06 12:18:16.427  6913  6913 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-06 12:18:16.427  6913  6913 D Mms/DownloadManager: auto download without roaming -> true
07-06 12:18:16.427  6913  6913 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-06 12:18:16.427  6913  6913 D Mms/MethodReflector: getSubId is called
,07-06 12:18:16.427  6913  6913 D Mms/MethodReflector: getDefaultSmsSubId is called
07-06 12:18:16.427  6913  6913 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
07-06 12:18:16.427  6913  6913 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
07-06 12:18:16.427  6913  6913 D Mms/MethodReflector: getTelephonyProperty is called
07-06 12:18:16.427  6913  6913 D Mms/DownloadManager: roaming -> false (slotId = 1)
07-06 12:18:16.427  6913  6913 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
07-06 12:18:16.427  6913  6913 D Mms/DownloadManager: auto download without roaming -> true
07-06 12:18:16.427  6913  6913 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
07-06 12:18:16.427  6913  6913 D Mms/DownloadManager: auto download during roaming secondary -> false
07-06 12:18:16.427  6913  6913 D Mms/DownloadManager: mAutoDownload ------> true
,07-06 12:18:16.427  6913  6937 D Mms/DraftCache: [end]    rebuildCache consume time = 9.83927
,07-06 12:18:16.467  6913  6913 D ComposerPerformance: 1467800296470 ms / [DONE] Composer constructor
,07-06 12:18:16.467  6913  6913 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,07-06 12:18:16.467  6913  6913 I Mms/ReservationManager: ReservationManager()
07-06 12:18:16.467  6913  6913 I Mms/ReservationManager: resetAfterConnected()
07-06 12:18:16.467  1452  1469 D TP/MmsSmsProvider: query,matched:7, calling pid = 6913
,07-06 12:18:16.477  6913  6938 D Mms/Conversation: [start]    init() consume time = 40.475105
,07-06 12:18:16.477  1452  1469 D TP/MmsSmsProvider: match 7:Elapsed time : 3.424 ms
,07-06 12:18:16.477  1452  1727 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,07-06 12:18:16.477  1452  1727 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false,
07-06 12:18:16.477  1452  1727 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,07-06 12:18:16.477  1452  1727 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,07-06 12:18:16.487  6913  6913 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,07-06 12:18:16.487  1452  1727 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,07-06 12:18:16.487  1452  1727 D TP/MmsSmsProvider: need read changed broadcast:false
07-06 12:18:16.487  6913  6913 D Mms/MmsApp: [end]    onCreate() consume time = 15.236041
,07-06 12:18:16.487  6913  6938 D Mms/Conversation: [end]    init consume time = 0.69375
07-06 12:18:16.487  6913  6913 D Mms/UIEventReceiver: ui event
07-06 12:18:16.487  1016  3949 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
07-06 12:18:16.487  6913  6913 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
07-06 12:18:16.487  6913  6913 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
07-06 12:18:16.487  1016  3949 W ActivityManager: userId = 0, bbcId = -10000
07-06 12:18:16.487  1016  3949 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 12:18:16.487  1016  3949 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-06 12:18:16.487  6913  6938 D Mms/MessagingNotification: [start]    init() consume time = 3.369532
,07-06 12:18:16.497  6913  6913 D Mms/MethodReflector: getSubId is called
07-06 12:18:16.497  6913  6913 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,07-06 12:18:16.497  6913  6913 D Mms/MethodReflector: getTelephonyProperty is called
07-06 12:18:16.497  6913  6913 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-06 12:18:16.497  6913  6913 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-06 12:18:16.497  6913  6913 D Mms/DownloadManager: auto download without roaming -> true
07-06 12:18:16.497  6913  6913 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-06 12:18:16.497  6913  6913 D Mms/DownloadManager: mAutoDownload ------> true
,07-06 12:18:16.497  6913  6938 D Mms/MessagingNotification: [end]    init consume time = 8.266145
,07-06 12:18:16.497  6847  6847 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-06 12:18:16.507  6913  6940 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 3.460313
,07-06 12:18:16.507  1016  3944 I ActivityManager: Killing 6423:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,07-06 12:18:16.507  2731  2731 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jul 06 12:18:16 GMT+02:00 2016
,07-06 12:18:16.507  1016  1476 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-06 12:18:16.507  1016  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-06 12:18:16.507  6913  6941 D Mms/Synchronizer: [start]    doSync consume time = 6.56026
,07-06 12:18:16.517  1016  1476 W ActivityManager: userId = 0, bbcId = -10000
07-06 12:18:16.517  1452  1473 D TP/MmsSmsProvider: query,matched:0, calling pid = 6913
07-06 12:18:16.517  1452  1473 V TP/MmsSmsProvider: getSimpleConversations entered.
,07-06 12:18:16.517  1016  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-06 12:18:16.517  1016  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-06 12:18:16.517  1452  1473 D TP/MmsSmsProvider: match 0:Elapsed time : 3.131 ms
,07-06 12:18:16.517  2731  2731 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-06 12:18:16.517  1016  1135 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
,07-06 12:18:16.517  1016  1135 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-06 12:18:16.517  1452  1727 D TP/MmsSmsProvider: update, matched:300, calling pid = 6913
07-06 12:18:16.517  1016  1135 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-06 12:18:16.517  1452  1727 V TP/MmsSmsProvider: syncDBData start
,07-06 12:18:16.527  1452  1727 V TP/MmsSmsProvider: syncDBData sms end
07-06 12:18:16.527  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:16.527  1452  1723 D TP/MmsSmsProvider: query,matched:400, calling pid = 6913
07-06 12:18:16.527  1452  1727 V TP/MmsSmsProvider: syncDBData mms end
,07-06 12:18:16.527  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-06 12:18:16.527  1452  1727 V TP/MmsSmsProvider: syncDBData end
07-06 12:18:16.527  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:16.527  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-06 12:18:16.527  2731  2731 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-06 12:18:16.527  2731  2731 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-06 12:18:16.537  2731  2731 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-06 12:18:16.537  2731  6942 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-06 12:18:16.537  6943  6943 E Zygote  : MountEmulatedStorage()
,07-06 12:18:16.537  6943  6943 E Zygote  : v2
07-06 12:18:16.537  6943  6943 I libpersona: KNOX_SDCARD checking this for 10090
07-06 12:18:16.537  6943  6943 I libpersona: KNOX_SDCARD not a persona
,07-06 12:18:16.537  1016  1135 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6943 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,07-06 12:18:16.537  2731  6942 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-06 12:18:16.547  2731  6942 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,07-06 12:18:16.547  6943  6943 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-06 12:18:16.547  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,07-06 12:18:16.547  6913  6913 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
07-06 12:18:16.547  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-06 12:18:16.547  2731  6942 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
07-06 12:18:16.547  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-06 12:18:16.547  6943  6943 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 12:18:16.547  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:16.547  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 12:18:16.547  6943  6943 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-06 12:18:16.567  6951  6951 E Zygote  : MountEmulatedStorage()
07-06 12:18:16.567  6951  6951 E Zygote  : v2
07-06 12:18:16.567  6951  6951 I libpersona: KNOX_SDCARD checking this for 1000
,07-06 12:18:16.567  6951  6951 I libpersona: KNOX_SDCARD not a persona
07-06 12:18:16.567  6951  6951 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-06 12:18:16.567  6951  6951 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-06 12:18:16.567  6951  6951 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,07-06 12:18:16.587  1016  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6951 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-06 12:18:16.587  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,07-06 12:18:16.587  6943  6943 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-06 12:18:16.587  6943  6943 D ActivityThread: Added TimaKeyStore provider

```
