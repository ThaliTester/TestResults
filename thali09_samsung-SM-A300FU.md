#### Test 75789268a22e351_thali09_samsung-SM-A300FU Logs


```
--------- beginning of system,
07-07 15:12:55.000  1014  3594 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
07-07 15:12:55.240   293   293 E SMD     : DCD OFF
07-07 15:12:55.270  6879  6879 D AndroidRuntime: 
07-07 15:12:55.270  6879  6879 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-07 15:12:55.270  6879  6879 D AndroidRuntime: CheckJNI is OFF
07-07 15:12:55.270  6879  6879 D AndroidRuntime: readGMSProperty: start
07-07 15:12:55.270  6879  6879 D AndroidRuntime: readGMSProperty: already setted!!
07-07 15:12:55.270  6879  6879 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-07 15:12:55.270  6879  6879 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-07 15:12:55.270  6879  6879 D AndroidRuntime: readGMSProperty: end
07-07 15:12:55.270  6879  6879 D AndroidRuntime: addProductProperty: start
07-07 15:12:55.400  6879  6879 E AffinityControl: AffinityControl: registerfunction enter
07-07 15:12:55.420  6879  6879 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-07 15:12:55.430  1014  1462 E PersonaManagerService: inState():  stateMachine is null !!
07-07 15:12:55.430  1014  1462 I PersonaManagerService: PersonaId don't exist
07-07 15:12:55.430  1014  1462 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-07 15:12:55.440  1014  1462 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 15:12:55.450  1014  1462 W ActivityManager: mDVFSHelper.acquire()
07-07 15:12:55.450  1014  1462 D FocusedStackFrame: Set to : 0
07-07 15:12:55.460  1014  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-07 15:12:55.460  1014  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-07 15:12:55.460  1014  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:55.460  1014  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:55.460  1014  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:55.460  1014  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:55.470  6890  6890 E Zygote  : MountEmulatedStorage()
07-07 15:12:55.480  6890  6890 E Zygote  : v2
07-07 15:12:55.480  6890  6890 I libpersona: KNOX_SDCARD checking this for 10170
07-07 15:12:55.480  6890  6890 I libpersona: KNOX_SDCARD not a persona
07-07 15:12:55.480  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-07 15:12:55.480  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-07 15:12:55.480   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
07-07 15:12:55.480  6890  6890 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 15:12:55.480  1014  1462 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6890 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-07 15:12:55.480  1014  1462 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-07 15:12:55.480  1014  1462 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 15:12:55.490  6890  6890 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 15:12:55.490  1014  1462 D InputDispatcher: Focused application set to: xxxx
07-07 15:12:55.490  1014  1462 D InputDispatcher: Focus left window: 1478
07-07 15:12:55.490  6890  6890 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-07 15:12:55.490  6879  6879 D AndroidRuntime: Shutting down VM
07-07 15:12:55.490  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 15:12:55.490  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 15:12:55.510  6890  6890 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 15:12:55.510  6890  6890 D ActivityThread: Added TimaKeyStore provider
07-07 15:12:55.510  1014  1489 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-07 15:12:55.520  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 15:12:55.530  1014  1489 D PersonaManager: isKioskContainerExistOnDevice
07-07 15:12:55.540  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-07 15:12:55.560   257  6130 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-07 15:12:55.560   257   442 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-07 15:12:55.570  1478  1478 V ActivityThread: updateVisibility : ActivityRecord{2ff4eb6a token=android.os.BinderProxy@188df554 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-07 15:12:55.570  1478  1478 D Launcher: onTrimMemory. Level: 20
07-07 15:12:55.640  6890  6890 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-07 15:12:55.650  6890  6890 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 3223-3224)
07-07 15:12:55.650  6890  6890 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 15:12:55.670  6890  6890 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {321f8402}
07-07 15:12:55.670  6890  6890 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 15:12:55.680  6890  6890 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-07 15:12:55.690  6879  6879 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-07 15:12:55.710  6890  6890 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-07 15:12:55.710  6890  6890 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 15:12:55.710  6890  6890 E SysUtils: ApplicationContext is null in ApplicationStatus
07-07 15:12:55.730  6890  6890 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-07 15:12:55.730  6890  6890 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-07 15:12:55.730  6890  6890 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-07 15:12:55.740  6890  6890 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-07 15:12:55.740  6890  6890 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-07 15:12:55.740  6890  6890 I Adreno-EGL: Build Date: 04/06/15 Mon
07-07 15:12:55.740  6890  6890 I Adreno-EGL: Local Branch: 
07-07 15:12:55.740  6890  6890 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-07 15:12:55.740  6890  6890 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-07 15:12:55.740  6890  6890 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
07-07 15:12:55.950  6890  6916 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-07 15:12:55.990  6890  6890 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 15:12:56.010  6890  6890 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-07 15:12:56.020  6890  6890 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-07 15:12:56.020  6890  6890 D PhoneWindow: *FMB* installDecor flags : -2139027200
07-07 15:12:56.030  6890  6890 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-07 15:12:56.030  6890  6890 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 15:12:56.030  6890  6890 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 15:12:56.040  1014  1040 W ActivityManager: Activity pause timeout for ActivityRecord{10d6cd46 u0 com.test.thalitest/.MainActivity t44}
07-07 15:12:56.100  6890  6929 D OpenGLRenderer: Render dirty regions requested: true
07-07 15:12:56.110  1014  1213 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-07 15:12:56.110  1014  1213 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-07 15:12:56.110  1014  1213 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-07 15:12:56.110  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-07 15:12:56.110  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
07-07 15:12:56.120  6890  6890 V ActivityThread: updateVisibility : ActivityRecord{13fcd175 token=android.os.BinderProxy@cc43e5f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-07 15:12:56.120  6890  6890 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-07 15:12:56.120  6890  6890 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-07 15:12:56.130   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
07-07 15:12:56.130  1014  1436 D InputDispatcher: Focus entered window: 6890
07-07 15:12:56.130  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 15:12:56.140  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 15:12:56.140  6890  6890 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-07 15:12:56.140  6890  6929 I OpenGLRenderer: Initialized EGL, version 1.4
07-07 15:12:56.140  6890  6929 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-07 15:12:56.140  6890  6929 D OpenGLRenderer: Enabling debug mode 0
07-07 15:12:56.160  1014  1213 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-07 15:12:56.160  1170  1170 I StatusBar: Icon Only
07-07 15:12:56.160  1170  1170 D PanelView: There is/are notification(s) 
07-07 15:12:56.160  6890  6890 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@cc43e5f time:263738
07-07 15:12:56.170  1014  6931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-07 15:12:56.170  6890  6890 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-07 15:12:56.180  1856  1856 I SamsungIME: getCurrentCandidateView
07-07 15:12:56.190  1014  1045 I ActivityManager: Displayed Component not be shown by security: +650ms (total +2m29s529ms)
07-07 15:12:56.190  1014  1045 W ActivityManager: mDVFSHelper.release()
07-07 15:12:56.190  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{10d6cd46 u0 com.test.thalitest/.MainActivity t44} time:263762
07-07 15:12:56.190   257  6129 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
07-07 15:12:56.190   257   449 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
07-07 15:12:56.300  6890  6890 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6890
07-07 15:12:56.300  1856  1856 D SamsungIME: Dismiss ExpandCandiate
,07-07 15:12:56.470  1856  1856 I SamsungIME: getDebugLevel  : 0x4f4c
,07-07 15:12:56.480  6890  6890 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-07 15:12:56.500  1856  1856 I SamsungIME: getDebugLevel  : 0x4f4c
,07-07 15:12:56.510  1856  1856 I SamsungIME: KeybaordView init() : load resources
,07-07 15:12:56.540  1856  1856 I SamsungIME: getCurrentKeyboard
07-07 15:12:56.540  1856  1856 I SamsungIME: getTextKeyboard
,07-07 15:12:56.560  1856  1856 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-07 15:12:56.580  6890  6934 D jxcore_app_log: JniHelper::setJavaVM(0xb8ea02f0), pthread_self() = -1187006952
,07-07 15:12:56.590  6890  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-07 15:12:56.590  6890  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-07 15:12:56.590  6890  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-07 15:12:56.590  6890  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-07 15:12:56.590  6890  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-07 15:12:56.590  6890  6934 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ea601e5 added. We now have 1 listener(s)
,07-07 15:12:56.600  6890  6934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,07-07 15:12:56.600  6890  6934 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,07-07 15:12:56.600  6890  6934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 15:12:56.600  6890  6934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3898aac8 added. We now have 1 listener(s)
07-07 15:12:56.610  6890  6934 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 15:12:56.610  6890  6934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-07 15:12:56.610  6890  6934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-07 15:12:56.610  6890  6934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-07 15:12:56.610  6890  6934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-07 15:12:56.610  6890  6934 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-07 15:12:56.620  6890  6934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 15:12:56.620  6890  6934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,07-07 15:12:56.630  6890  6934 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 15:12:56.630  6890  6934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 15:12:56.630  6890  6934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 15:12:56.630  6890  6934 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 15:12:56.630  6890  6934 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 15:12:56.630  6890  6934 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 15:12:56.630  6890  6934 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 15:12:56.630  6890  6934 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-07 15:12:56.630  6890  6934 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-07 15:12:56.630  6890  6934 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-07 15:12:56.630  6890  6934 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-07 15:12:56.630  6890  6890 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 15:12:56.630  6890  6890 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 15:12:56.660  6890  6890 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-07 15:12:57.220  6890  6939 W jxcore-log: Initializing JXcore engine
07-07 15:12:57.220  6890  6939 W jxcore-log: JXcore engine is ready
,07-07 15:12:57.270  2024  2024 E audit   : type=1400 msg=audit(1467897177.270:205): avc:  denied  { ioctl } for  pid=6939 comm="Thread-1243" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-07 15:12:57.270  2024  2024 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-07 15:12:57.270  2024  2024 E audit   : type=1300 msg=audit(1467897177.270:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=1 a3=9f2028f8 items=0 ppid=324 ppcomm=main pid=6939 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1243" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-07 15:12:57.270  2024  2024 E audit   : type=1320 msg=audit(1467897177.270:205): 
,07-07 15:12:57.280  6890  6939 W jxcore-log: Starting JXcore engine
,07-07 15:12:57.380  6890  6939 W jxcore-log: Platform android,
07-07 15:12:57.380  6890  6939 W jxcore-log: 
07-07 15:12:57.380  6890  6939 W jxcore-log: Process ARCH arm
07-07 15:12:57.380  6890  6939 W jxcore-log: 
,07-07 15:12:57.580  6890  6939 I jxcore-log: JXcore Cordova bridge is ready!
07-07 15:12:57.580  6890  6939 I jxcore-log: 
,07-07 15:12:57.590  6890  6939 W jxcore-log: JXcore engine is started
,07-07 15:12:57.590  6890  6934 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-07 15:12:57.590  6890  6890 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-07 15:12:57.600  6890  6939 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-07 15:12:57.600  6890  6939 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-07 15:12:57.610  6890  6890 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-07 15:12:57.610  6890  6890 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-07 15:12:57.610  1014  1494 D FocusedStackFrame: Set to : 0
07-07 15:12:57.610  1014  1494 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 15:12:57.610  1014  1494 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-07 15:12:57.610  1014  1494 D InputDispatcher: Focused application set to: xxxx
07-07 15:12:57.620  1014  1494 D InputDispatcher: Focus left window: 6890
07-07 15:12:57.620  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 15:12:57.620  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 15:12:57.620  1014  1494 I ActivityManager: Killing 6389:com.sec.pcw.device/1000 (adj 15): empty #21
,07-07 15:12:57.630  6890  6890 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-07 15:12:57.630  6890  6890 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,07-07 15:12:57.630  6890  6890 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 15:12:57.630  6890  6890 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 15:12:57.630  6890  6890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 15:12:57.630  6890  6890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 15:12:57.630  6890  6890 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ea601e5 removed from the list
07-07 15:12:57.630  6890  6890 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 15:12:57.630  6890  6890 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3898aac8 removed from the list
07-07 15:12:57.630  6890  6890 D io.jxcore.node.ConnectivityMonitor: stop
07-07 15:12:57.630  6890  6890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-07 15:12:57.640  6890  6890 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-07 15:12:57.660   257   442 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
07-07 15:12:57.660   257   449 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,07-07 15:12:57.670  1014  1494 W ActivityManager: mDVFSHelper.acquire()
,07-07 15:12:57.680  1014  1494 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-07 15:12:57.700  1478  1478 D Launcher: onRestart, Launcher: 17161806
,07-07 15:12:57.700  1478  1478 D Launcher: onStart, Launcher: 17161806
,07-07 15:12:57.700  1478  1478 D Launcher.HomeView: onStart
,07-07 15:12:57.710  1478  1478 D Launcher: onResume, Launcher: 17161806
,07-07 15:12:57.710  1014  1472 D SettingsProvider: name = kids_home_mode
,07-07 15:12:57.710  1014  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-07 15:12:57.710  1014  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-07 15:12:57.710  1014  1472 D SettingsProvider: selectionArgs: false
07-07 15:12:57.710  1014  1472 D SettingsProvider: selectionArgs: 10006
07-07 15:12:57.710  1014  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-07 15:12:57.710  1014  1472 D SettingsProvider: ret = -1
,07-07 15:12:57.710  1478  1478 D Launcher.HomeView: onResume
,07-07 15:12:57.720  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-07 15:12:57.720  1478  1478 D MenuAppsGridFragment: onResume
,07-07 15:12:57.730  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:57.730  1014  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:57.730  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-07 15:12:57.730  1014  1489 D ActivityManager: handle home activity for 0,
07-07 15:12:57.730  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
07-07 15:12:57.730  1014  1489 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0,
,07-07 15:12:57.730  1014  1489 D KnoxTimeoutHandler: post home show event for user 0
,07-07 15:12:57.730  1014  1462 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
07-07 15:12:57.730  1014  1489 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-07 15:12:57.730  1014  1462 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-07 15:12:57.730  1014  1489 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-07 15:12:57.730  1014  1462 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
07-07 15:12:57.730  1014  1489 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-07 15:12:57.740  1014  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 15:12:57.730  1014  1014 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-07 15:12:57.740  1014  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.730  1014  1014 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-07 15:12:57.740  1014  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.730  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,07-07 15:12:57.740  1014  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.730  1478  1478 D Launcher.HomeView: onPause
07-07 15:12:57.730  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-07 15:12:57.730  1014  1462 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:57.730  1014  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
07-07 15:12:57.730  1014  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-07 15:12:57.750  6944  6944 E Zygote  : MountEmulatedStorage()
,07-07 15:12:57.750  6944  6944 E Zygote  : v2
07-07 15:12:57.750  6944  6944 I libpersona: KNOX_SDCARD checking this for 10039
07-07 15:12:57.750  6944  6944 I libpersona: KNOX_SDCARD not a persona
07-07 15:12:57.750  1014  1462 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6944 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,07-07 15:12:57.760   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
07-07 15:12:57.760  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:57.760  1014  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:57.760  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-07 15:12:57.760  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:57.760  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 15:12:57.760  1014  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:57.760  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-07 15:12:57.760  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
07-07 15:12:57.770  6944  6944 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 15:12:57.770  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.770  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.770  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.770  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.770  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 15:12:57.770  6944  6944 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 15:12:57.770  6944  6944 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 15:12:57.780  1014  1326 D InputDispatcher: Focus entered window: 1478
07-07 15:12:57.780  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 15:12:57.780  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 15:12:57.780  1478  1478 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-07 15:12:57.790  1014  1076 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-07 15:12:57.790  1014  6955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-07 15:12:57.790  6890  6890 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-07 15:12:57.790  1856  1856 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
07-07 15:12:57.790  1014  1040 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6953 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
07-07 15:12:57.790  6953  6953 E Zygote  : MountEmulatedStorage()
07-07 15:12:57.790  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:57.790  1014  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:57.790  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-07 15:12:57.790  6953  6953 E Zygote  : v2
07-07 15:12:57.790  6953  6953 I libpersona: KNOX_SDCARD checking this for 10089
07-07 15:12:57.790  6953  6953 I libpersona: KNOX_SDCARD not a persona
,07-07 15:12:57.800  6953  6953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 15:12:57.800  6695  6695 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
07-07 15:12:57.800  6953  6953 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 15:12:57.800  1170  1170 I StatusBar: Icon Only
07-07 15:12:57.800  1170  1170 D PanelView: There is/are notification(s) 
07-07 15:12:57.800  6953  6953 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-07 15:12:57.820  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:57.820  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:57.820  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-07 15:12:57.830  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:57.830  1014  1026 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1478, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-07 15:12:57.830  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:57.830  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-07 15:12:57.830  6953  6953 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 15:12:57.830  6953  6953 D ActivityThread: Added TimaKeyStore provider
,07-07 15:12:57.830  6944  6944 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 15:12:57.830  6944  6944 D ActivityThread: Added TimaKeyStore provider
,07-07 15:12:57.830  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:57.830  1014  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:57.830  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-07 15:12:57.830  1478  1478 V ActivityThread: updateVisibility : ActivityRecord{2ff4eb6a token=android.os.BinderProxy@188df554 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-07 15:12:57.830  1478  1478 D Launcher.HomeView: onStop
,07-07 15:12:57.830  1478  1478 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@188df554 time:265409
,07-07 15:12:57.840  2589  2589 D Recents_RecreateReceiver: onReceive by home
,07-07 15:12:57.860  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:57.860  1014  1076 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-07 15:12:57.860  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:57.860  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,07-07 15:12:57.860  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.860  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.860  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.860  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 15:12:57.860  6953  6953 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-07 15:12:57.860  6953  6953 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,07-07 15:12:57.860  6944  6944 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-07 15:12:57.860  6944  6944 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-07 15:12:57.860  6944  6944 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-07 15:12:57.860  6944  6944 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-07 15:12:57.860  6944  6944 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-07 15:12:57.860  6944  6944 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-07 15:12:57.860  6944  6944 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-07 15:12:57.870  6978  6978 E Zygote  : MountEmulatedStorage()
07-07 15:12:57.870  6978  6978 E Zygote  : v2
07-07 15:12:57.870  6978  6978 I libpersona: KNOX_SDCARD checking this for 10084
07-07 15:12:57.870  6978  6978 I libpersona: KNOX_SDCARD not a persona
,07-07 15:12:57.870  6978  6978 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 15:12:57.880  1014  1076 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6978 uid=10084 gids={50084, 9997} abi=armeabi-v7a
07-07 15:12:57.880  6978  6978 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 15:12:57.880  6978  6978 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
07-07 15:12:57.880  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{24a44040 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t42} time:265455
07-07 15:12:57.880  1014  1045 W ActivityManager: mDVFSHelper.release()
,07-07 15:12:57.900  6978  6978 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 15:12:57.910  6978  6978 D ActivityThread: Added TimaKeyStore provider
,07-07 15:12:57.910  6940  6940 D AndroidRuntime: 
07-07 15:12:57.910  6940  6940 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-07 15:12:57.910  6940  6940 D AndroidRuntime: CheckJNI is OFF
,07-07 15:12:57.910  6940  6940 D AndroidRuntime: readGMSProperty: start
07-07 15:12:57.910  6940  6940 D AndroidRuntime: readGMSProperty: already setted!!
07-07 15:12:57.910  6940  6940 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-07 15:12:57.910  6940  6940 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-07 15:12:57.910  6940  6940 D AndroidRuntime: readGMSProperty: end
07-07 15:12:57.910  6940  6940 D AndroidRuntime: addProductProperty: start
,07-07 15:12:57.920  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:57.920  1014  1472 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-07 15:12:57.920  1014  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:57.920  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,07-07 15:12:57.920  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 15:12:57.920  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.920  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:57.920  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 15:12:57.930  6978  6978 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-07 15:12:57.940  6994  6994 E Zygote  : MountEmulatedStorage()
07-07 15:12:57.940  6994  6994 I libpersona: KNOX_SDCARD checking this for 10135
07-07 15:12:57.940  6994  6994 E Zygote  : v2
07-07 15:12:57.940  6994  6994 I libpersona: KNOX_SDCARD not a persona
,07-07 15:12:57.940  1014  1472 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6994 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,07-07 15:12:57.940  1014  1472 I ActivityManager: Killing 6436:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,07-07 15:12:57.950  6994  6994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 15:12:57.950  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-07 15:12:57.960  1014  1326 I ActivityManager: Killing 6442:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21,
07-07 15:12:57.960  6994  6994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 15:12:57.960  6994  6994 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 15:12:57.980  6994  6994 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 15:12:57.990  6994  6994 D ActivityThread: Added TimaKeyStore provider
,07-07 15:12:58.000  6994  6994 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-07 15:12:58.000  6994  6994 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-07 15:12:58.000  6994  6994 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-07 15:12:58.000  6994  6994 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-07 15:12:58.000  6994  6994 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-07 15:12:58.010  1014  1494 D PersonaManager: isKioskContainerExistOnDevice
,07-07 15:12:58.020  1014  1436 I ActivityManager: Killing 6479:com.sec.spp.push/u0a32 (adj 15): empty #21
,07-07 15:12:58.050  6940  6940 E AffinityControl: AffinityControl: registerfunction enter
,07-07 15:12:58.060  6944  6944 D NearbySource: Nearby Source Create!
,07-07 15:12:58.060  6944  6944 D NearbyContext: Nearby Context Create!
,07-07 15:12:58.070  6940  6940 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-07 15:12:58.080  1014  1472 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-07 15:12:58.080  1014  1472 D PackageManager: START PACKAGE DELETE: observer{325612401}
07-07 15:12:58.080  1014  1472 D PackageManager: pkg{<packageName>}
07-07 15:12:58.080  1014  1472 D PackageManager: user{0}
07-07 15:12:58.080  1014  1472 D PackageManager: caller{2000}
07-07 15:12:58.080  1014  1472 D PackageManager: flags{2}
07-07 15:12:58.080  1014  1472 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-07 15:12:58.080  1014  1472 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-07 15:12:58.080  1014  1472 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-07 15:12:58.080  1014  1472 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-07 15:12:58.080  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-07 15:12:58.080  1014  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-07 15:12:58.080  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-07 15:12:58.080  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
07-07 15:12:58.080  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-07 15:12:58.090  1014  1055 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
07-07 15:12:58.090  1014  1040 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
07-07 15:12:58.090  1014  1040 I ActivityManager: Killing 6890:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-07 15:12:58.100   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-07 15:12:58.100   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,07-07 15:12:58.100  6944  6944 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
07-07 15:12:58.100  6944  6944 D SLinkSource: Samsung link source created
,07-07 15:12:58.170  1014  1055 W PackageSettings: Skipping PackageSetting{bd026d1 com.example.hello/10168} due to missing metadata
,07-07 15:12:58.220  1014  1055 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,07-07 15:12:58.240   293   293 E SMD     : DCD OFF
,07-07 15:12:58.290  1014  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
07-07 15:12:58.290  2739  2739 I art     : Explicit concurrent mark sweep GC freed 23432(1279KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 948us total 48.260ms
,07-07 15:12:58.310  6510  6510 I art     : Explicit concurrent mark sweep GC freed 611(35KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 739us total 76.259ms
,07-07 15:12:58.310  1014  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-07 15:12:58.330  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-07 15:12:58.340  4630  4630 I art     : Explicit concurrent mark sweep GC freed 20999(1307KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 12MB/16MB, paused 1.244ms total 101.835ms
,07-07 15:12:58.340  1856  1856 E SamsungIME: mOCRHelper is null
,07-07 15:12:58.340  2031  2194 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-07 15:12:58.350  1014  1121 V NetworkStats: removeUidsLocked() for UIDs [10170]
07-07 15:12:58.350  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
07-07 15:12:58.350  1014  1121 V NetworkStats: performPollLocked(flags=0x3)
,07-07 15:12:58.360  1453  1453 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-07 15:12:58.360  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
07-07 15:12:58.360  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-07 15:12:58.370  1014  1121 V NetworkStats: performPollLocked() took 14ms
,07-07 15:12:58.370  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
07-07 15:12:58.370  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,07-07 15:12:58.380  1438  1438 D RegisteredServicesCache: empty dynamic service
,07-07 15:12:58.390  1014  1026 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-07 15:12:58.400  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,07-07 15:12:58.400  6944  6944 D GalleryCacheReady: Receive : home resume
,07-07 15:12:58.400  6944  7019 D ContactProvider: getAllContactInfoList Start
,07-07 15:12:58.400  1014  1489 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:58.400  1014  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:58.400  1014  1489 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
07-07 15:12:58.400  1014  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-07 15:12:58.400  1014  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 15:12:58.410  1014  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:58.410  1014  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:58.410  1014  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 15:12:58.420  7021  7021 E Zygote  : MountEmulatedStorage()
,07-07 15:12:58.420  7021  7021 E Zygote  : v2
07-07 15:12:58.420  7021  7021 I libpersona: KNOX_SDCARD checking this for 10041
07-07 15:12:58.420  7021  7021 I libpersona: KNOX_SDCARD not a persona
,07-07 15:12:58.420  7021  7021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
07-07 15:12:58.420  1014  1489 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=7021 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
07-07 15:12:58.420  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
07-07 15:12:58.420  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
07-07 15:12:58.420  7021  7021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 15:12:58.420  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
07-07 15:12:58.420  7021  7021 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-07 15:12:58.460  1014  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
07-07 15:12:58.460  1014  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-07 15:12:58.460  1014  1039 W TextServicesManagerService: no available spell checker services found
,07-07 15:12:58.470  7021  7021 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 15:12:58.470  7021  7021 D ActivityThread: Added TimaKeyStore provider
,07-07 15:12:58.500  6944  7019 D ContactProvider: getAllContactInfoList End
,07-07 15:12:58.500  6944  7019 I syncContacts: thread: 1228, sync time = 250
,07-07 15:12:58.510  7021  7021 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-07 15:12:58.510  7021  7021 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-07 15:12:58.510  7021  7021 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-07 15:12:58.510  7021  7021 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-07 15:12:58.510  7021  7021 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,07-07 15:12:58.510  1014  1014 I art     : Explicit concurrent mark sweep GC freed 56884(4MB) AllocSpace objects, 62(992KB) LOS objects, 33% free, 23MB/35MB, paused 8.224ms total 245.511ms
,07-07 15:12:58.510  1014  1055 I art     : WaitForGcToComplete blocked for 202.571ms for cause Explicit
,07-07 15:12:58.540  7021  7021 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,07-07 15:12:58.550  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.560  1014  1437 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-07 15:12:58.560  1014  1437 D SecContentProvider2: mCursor = null
,07-07 15:12:58.570  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.590  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,07-07 15:12:58.600  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-07 15:12:58.610  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,07-07 15:12:58.610  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,07-07 15:12:58.610  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,07-07 15:12:58.610  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.620  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,07-07 15:12:58.620  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.620  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-07 15:12:58.690  1014  1055 I art     : Explicit concurrent mark sweep GC freed 11697(555KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.941ms total 171.429ms
,07-07 15:12:58.700  1014  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-07 15:12:58.710  7021  7021 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 119.600ms
,07-07 15:12:58.710  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.720  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.720  1014  1055 D PackageManager: delete codoeFile: 
,07-07 15:12:58.740  1014  1055 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
07-07 15:12:58.740  1014  1055 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,07-07 15:12:58.740  1014  1055 D PackageManager: result of delete: 1{325612401}
,07-07 15:12:58.740  6940  6940 D AndroidRuntime: Shutting down VM
,07-07 15:12:58.750  1014  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-07 15:12:58.750  1014  1055 D PackageManager: userId{-1}
07-07 15:12:58.750  1014  1055 D PackageManager: andCode{true}
,07-07 15:12:58.750  1014  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-07 15:12:58.750  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.760  1014  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-07 15:12:58.760  1014  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-07 15:12:58.760  1014  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-07 15:12:58.760  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.780  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.790  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.790  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.790  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-07 15:12:58.790  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.790  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-07 15:12:58.790  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-07 15:12:58.790  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-07 15:12:58.790  1014  1014 V EnterpriseBillingPolicy: uID is 10170
07-07 15:12:58.790  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
07-07 15:12:58.790  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-07 15:12:58.800  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 15:12:58.800  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-07 15:12:58.800  7021  7037 D Mms/ArtClassLoader: init before art
,07-07 15:12:58.800  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicy: uID is 10170
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-07 15:12:58.800  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-07 15:12:58.800  1014  3518 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-07 15:12:58.800  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-07 15:12:58.800  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-07 15:12:58.800  7021  7021 D Mms/TelephonyPermission: start operation mode monitor
,07-07 15:12:58.800  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 15:12:58.800  1014  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-07 15:12:58.800  1014  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
07-07 15:12:58.800  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=44_task.xml
,07-07 15:12:58.810  1014  1014 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,07-07 15:12:58.810  7021  7021 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-07 15:12:58.820  7021  7021 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
07-07 15:12:58.820  7021  7021 D Mms/TelephonyPermission: isDefault true
,07-07 15:12:58.820  7021  7021 D Mms/MmsApp: onCreate() com.android.mms
,07-07 15:12:58.860  7021  7021 D Mms/MmsApp: [start]    initCountryIso consume time = 317.665468
,07-07 15:12:58.860  1014  1462 D CountryDetector: The first listener is added
,07-07 15:12:58.860  7021  7021 D Mms/MmsApp: [end]    initCountryIso consume time = 5.616407
07-07 15:12:58.860  7021  7021 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.105989
,07-07 15:12:58.880  7021  7021 D Mms/MmsConfig: before partial update
,07-07 15:12:58.890  7021  7021 D Mms/MmsConfig: Load Resize quality : 80
,07-07 15:12:58.890  7021  7021 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,07-07 15:12:58.900  7021  7021 D EasySignUpManager_1.0.1: isAuth is false
,07-07 15:12:58.900  7021  7021 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,07-07 15:12:58.900  1453  1474 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7021
,07-07 15:12:58.900  1453  1474 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.317 ms
,07-07 15:12:58.910  7021  7021 D EasySignUpManager_1.0.1: isAuth is false
,07-07 15:12:58.910  7021  7021 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,07-07 15:12:58.910  7021  7021 E CscParser: mps_code.dat does not exist
07-07 15:12:58.910  7021  7021 E CscParser: customer_path =/system/csc/customer.xml
07-07 15:12:58.910  7021  7021 E CscParser: fileName + /system/csc/customer.xml
,07-07 15:12:58.920  7021  7021 E CscParser: mps_code.dat does not exist
07-07 15:12:58.920  7021  7021 E CscParser: customer_path =/system/csc/customer.xml
07-07 15:12:58.920  7021  7021 E CscParser: fileName + /system/csc/customer.xml
,07-07 15:12:58.930  7021  7021 D CscParser: getInstance fileName =/system/csc/customer.xml
,07-07 15:12:58.930  7021  7021 D Mms/MmsConfig:  enable multiwindow = false
,07-07 15:12:58.940  7021  7021 E Mms/MessageUtils: setCountryDetector : update country detector info 
07-07 15:12:58.940  7021  7021 E Mms/MessageUtils: updateCountryIso : update country iso info 
,07-07 15:12:58.940  7021  7021 D Mms/MmsConfig: [end]    init() consume time = 75.082344
,07-07 15:12:58.940  7021  7021 D Mms/Contact: [start]    init() consume time = 1.316771
,07-07 15:12:58.950  6940  6940 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-07 15:12:58.950  1453  1474 D TP/MmsSmsProvider: query,matched:13, calling pid = 7021
,07-07 15:12:58.960  1453  1474 D TP/MmsSmsProvider: match 13:Elapsed time : 2.219 ms
,07-07 15:12:58.960  7021  7021 D Mms/Contact: [end]    init consume time = 19.306093
,07-07 15:12:58.970  7021  7046 D Mms/DraftCache: [start]    rebuildCache consume time = 12.388803
,07-07 15:12:58.980  1453  3845 D TP/MmsSmsProvider: query,matched:12, calling pid = 7021
,07-07 15:12:58.980  1453  3845 D TP/MmsSmsProvider: match 12:Elapsed time : 1.289 ms
,07-07 15:12:58.980  7021  7046 D Mms/DraftCache: [end]    rebuildCache consume time = 7.931458
,07-07 15:12:58.990  7021  7021 D Mms/MethodReflector: getSubId is called
,07-07 15:12:58.990  7021  7021 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,07-07 15:12:58.990  7021  7021 D Mms/MethodReflector: getTelephonyProperty is called
,07-07 15:12:58.990  7021  7021 D Mms/DownloadManager: roaming -> false (slotId = 0)
,07-07 15:12:58.990  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-07 15:12:58.990  7021  7021 D Mms/DownloadManager: auto download without roaming -> true
,07-07 15:12:58.990  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,07-07 15:12:58.990  7021  7021 D Mms/MethodReflector: getSubId is called
,07-07 15:12:58.990  7021  7021 D Mms/MethodReflector: getDefaultSmsSubId is called
,07-07 15:12:58.990  7021  7021 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
07-07 15:12:58.990  7021  7021 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
,07-07 15:12:58.990  7021  7021 D Mms/MethodReflector: getTelephonyProperty is called
07-07 15:12:58.990  7021  7021 D Mms/DownloadManager: roaming -> false (slotId = 1)
,07-07 15:12:58.990  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
07-07 15:12:58.990  7021  7021 D Mms/DownloadManager: auto download without roaming -> true
,07-07 15:12:59.000  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
07-07 15:12:59.000  7021  7021 D Mms/DownloadManager: auto download during roaming secondary -> false
,07-07 15:12:59.000  7021  7021 D Mms/DownloadManager: mAutoDownload ------> true
,07-07 15:12:59.040  7021  7021 D ComposerPerformance: 1467897179044 ms / [DONE] Composer constructor
,07-07 15:12:59.040  7021  7021 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,07-07 15:12:59.040  7021  7021 I Mms/ReservationManager: ReservationManager()
07-07 15:12:59.040  7021  7021 I Mms/ReservationManager: resetAfterConnected()
,07-07 15:12:59.040  1453  1704 D TP/MmsSmsProvider: query,matched:7, calling pid = 7021
,07-07 15:12:59.040  1453  1704 D TP/MmsSmsProvider: match 7:Elapsed time : 1.744 ms
,07-07 15:12:59.050  7021  7049 D Mms/Conversation: [start]    init() consume time = 66.367812
,07-07 15:12:59.050  7021  7021 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,07-07 15:12:59.050  1453  3845 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,07-07 15:12:59.050  7021  7021 D Mms/MmsApp: [end]    onCreate() consume time = 5.997448
,07-07 15:12:59.050  7021  7021 D Mms/UIEventReceiver: ui event
,07-07 15:12:59.050  1014  1472 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,07-07 15:12:59.060  7021  7021 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,07-07 15:12:59.060  7021  7021 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,07-07 15:12:59.060  7021  7021 D Mms/MethodReflector: getSubId is called
07-07 15:12:59.060  7021  7021 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,07-07 15:12:59.060  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,07-07 15:12:59.060  1014  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:59.060  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-07 15:12:59.060  7021  7021 D Mms/MethodReflector: getTelephonyProperty is called
07-07 15:12:59.060  7021  7021 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-07 15:12:59.060  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-07 15:12:59.060  7021  7021 D Mms/DownloadManager: auto download without roaming -> true
07-07 15:12:59.060  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-07 15:12:59.060  7021  7021 D Mms/DownloadManager: mAutoDownload ------> true
,07-07 15:12:59.070  6695  6695 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-07 15:12:59.070  1014  1213 I ActivityManager: Killing 6430:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,07-07 15:12:59.070  2688  2688 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jul 07 15:12:59 GMT+02:00 2016
,07-07 15:12:59.080  1014  1076 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-07 15:12:59.080  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-07 15:12:59.080  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
07-07 15:12:59.080  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 15:12:59.080  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-07 15:12:59.080  2688  2688 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-07 15:12:59.080  1014  1436 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
,07-07 15:12:59.080  1014  1436 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-07 15:12:59.080  1014  1436 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-07 15:12:59.090  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 15:12:59.090  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:59.090  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:59.090  1014  1436 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 15:12:59.090  2688  2688 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-07 15:12:59.090  2688  2688 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-07 15:12:59.090  2688  2688 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-07 15:12:59.090  2688  7050 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
07-07 15:12:59.090  2688  7050 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-07 15:12:59.100  7051  7051 E Zygote  : MountEmulatedStorage(),
07-07 15:12:59.100  7051  7051 I libpersona: KNOX_SDCARD checking this for 10090
07-07 15:12:59.100  7051  7051 E Zygote  : v2
07-07 15:12:59.100  7051  7051 I libpersona: KNOX_SDCARD not a persona
07-07 15:12:59.100  1014  1436 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7051 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,07-07 15:12:59.100  2688  7050 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,07-07 15:12:59.100  7051  7051 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 15:12:59.100  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
07-07 15:12:59.100  7021  7021 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
07-07 15:12:59.100  2688  7050 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-07 15:12:59.110  7051  7051 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 15:12:59.110  7051  7051 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 15:12:59.110  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:59.110  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:59.110  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 15:12:59.110  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
